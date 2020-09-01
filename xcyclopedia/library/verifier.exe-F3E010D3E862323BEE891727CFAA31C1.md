---
title: verifier.exe | Verifier Configuration Editor
---

# verifier.exe 

* File Path: `C:\WINDOWS\system32\verifier.exe`
* Description: Verifier Configuration Editor

## Hashes

Type | Hash
-- | --
MD5 | `F3E010D3E862323BEE891727CFAA31C1`
SHA1 | `9DDA34B51ECA17DD15D2AB6435A2D24BDCCE0F4F`
SHA256 | `21C898775E0640EABD0D1CF03A7A69336BCB08BA28A27C34FA4A211C66F6BE66`
SHA384 | `8D3688621C073F608C070B22AFADB8F18BF7998F0D924DB79D88D20E6284761198C1D4CAF6620C415D861E42DADB8DA5`
SHA512 | `632E1144D3924EFAFBF1FD519F39F82751B2F0767D2F4B52889C750177D6FB6AB6D36E725BF9DBC1FCBC71FA26058630BB0D4BBF82534C343480E0A7AC2B241E`
SSDEEP | `3072:xHYDGZ2xcI9EiQQ6U2zJ0HwZpHKG5c5VoJe3+Vcv2JxQQBBEB3BefnjHrjqR+Da5:xHYDGZ2xcI9UJU2zaHwZpqGAC4T5`

## Runtime Data

### Usage (stdout):
```Batchfile

Copyright (c) Microsoft Corporation. All rights reserved.

SYNTAX:

    verifier {/? | /help}
    verifier /standard /all
    verifier /standard /driver <name> [<name> ...]
    verifier {/ruleclasses | /rc} <options> [<ruleclass_1> <ruleclass_2> ...] /all
    verifier /flags <options> [<options> ...] /all
    verifier /flags <options> [<options> ...] /driver <name> [<name> ...]
    verifier /rules {query | reset | default <id> | disable <id>}
    verifier /query
    verifier /querysettings
    verifier /bootmode {persistent | resetonbootfail | oneboot | resetonunusualshutdown}
    verifier /persistthroughupgrade
    verifier /reset
    verifier /faults [probability [pool_tags [applications [delay_minutes]]]]
    verifier /faultssystematic [<options> ...]
    verifier /log <file_name> [/interval <seconds>]
    verifier /volatile /flags <options> [<options> ...]
    verifier /volatile /adddriver <name> [<name> ...]
    verifier /volatile /removedriver <name> [<name> ...]
    verifier /volatile /faults [probability [pool_tags [applications
                [delay_minutes]]]]
    verifier /domain {wdm | ndis | ks | audio} [rules.all | rules.default ]
                /driver ... [/logging | /livedump]
    verifier /logging
    verifier /livedump

PARAMETERS:

    /? or /help
        Displays this help message.

    /standard
        Specifies standard Driver Verifier flags.

    /all
        Specifies that all installed drivers will be verified after the next
        boot.

    /driver <name> [<name> ...]
        Specifies one or more drivers (image names) that will be verified.
        Wildcard values (e.g. n*.sys) are not supported.

    /driver.exclude <name> [<name> ...]
        Specifies one or more drivers (image names) that will be excluded
        from verification. This parameter is applicable only if all drivers
        are selected for verification. Wildcard values (e.g. n*.sys) are not
        supported.

    /flags <options> [<options> ...]
        Specifies one or more options that should be enabled for verification.
        Flags are applied to all drivers being checked by Driver Verifier. The
        provided options values must be either in decimal, hexadecimal ("0x"
        prefix), octal ("0o" prefix) or binary ("0b" prefix) format.

        Standard Flags:
          Standard Driver Verifier options can be specified using '/standard'.
          WDF verification is included in /standard but is not shown here.

          0x00000001 (bit  0) - Special pool
          0x00000002 (bit  1) - Force IRQL checking
          0x00000008 (bit  3) - Pool tracking
          0x00000010 (bit  4) - I/O verification
          0x00000020 (bit  5) - Deadlock detection
          0x00000080 (bit  7) - DMA checking
          0x00000100 (bit  8) - Security checks
          0x00000800 (bit 11) - Miscellaneous checks
          0x00020000 (bit 17) - DDI compliance checking

        Additional Flags:
          These flags are intended for specific scenario testing. Flags marked
          with (*) require I/O Verification (bit 4) that will be automatically
          enabled. Flags marked with (**) support disabling of individual
          rules.

          0x00000004 (bit  2) - Randomized low resources simulation
          0x00000200 (bit  9) - Force pending I/O requests (*)
          0x00000400 (bit 10) - IRP logging (*)
          0x00002000 (bit 13) - Invariant MDL checking for stack (*)
          0x00004000 (bit 14) - Invariant MDL checking for driver (*)
          0x00008000 (bit 15) - Power framework delay fuzzing
          0x00010000 (bit 16) - Port/miniport interface checking
          0x00040000 (bit 18) - Systematic low resources simulation
          0x00080000 (bit 19) - DDI compliance checking (additional)
          0x00200000 (bit 21) - NDIS/WIFI verification (**)
          0x00800000 (bit 23) - Kernel synchronization delay fuzzing
          0x01000000 (bit 24) - VM switch verification
          0x02000000 (bit 25) - Code integrity checks

    /ruleclasses or /rc [<ruleclass_1> <ruleclass_2> ... <ruleclass_k>]
        This parameter is larger set of '/flags' above. While '/flags' is
        limited to 32 bit bitmap expression, this can include more than 32
        verification classes. Each positive decimal integer represents a
        verification class. Multiple classes can be expressed by separating
        each class id with space character. Following rule classes IDs are
        available and leading 0's can be omitted.

        Standard Rule Classes:

                   1 - Special pool
                   2 - Force IRQL checking
                   4 - Pool tracking
                   5 - I/O verification
                   6 - Deadlock detection
                   8 - DMA checking
                   9 - Security checks
                  12 - Miscellaneous checks
                  18 - DDI compliance checking
                  34 - WDF Verification

        Additional Rule Classes:
          These rule classes are intended for specific scenario testing. Rule
          classes are marked with (*) require I/O Verification (5) that will
          be automatically enabled. Flags marked with (**) support disabling
          of individual rules.

                   3 - Randomized low resources simulation
                  10 - Force pending I/O requests (*)
                  11 - IRP logging (*)
                  14 - Invariant MDL checking for stack (*)
                  15 - Invariant MDL checking for driver (*)
                  16 - Power framework delay fuzzing
                  17 - Port/miniport interface checking
                  19 - Systematic low resources simulation
                  20 - DDI compliance checking (additional)
                  22 - NDIS/WIFI verification (**)
                  24 - Kernel synchronization delay fuzzing
                  25 - VM switch verification
                  26 - Code integrity checks

    /log.code_integrity
        This option suppresses Code Integrity violation breaks and collects
        only statistics for verified drivers. Statistics could be extracted
        via /log option or kernel debugger. This parameter is applicable only
        if Code Integrity checks are enabled.

    /rules {query | reset | default <id> | disable <id>}
        Specifies rules level control (advanced).

          query           Shows current status of controllable rules.
          reset           Resets all rules to their default state.
          default <id>    Sets rule ID to its default state.
          disable <id>    Disables specified rule ID.

    /query
        Display runtime Driver Verifier statistics and settings.

    /querysettings
        Displays a summary of the options and drivers that are currently
        enabled, or options and drivers that will be verified after the
        next boot. The display does not include drivers and options added
        using /volatile.

    /bootmode
        Specifies the Driver Verifier boot mode. This option requires system
        reboot to take effect.

          persistent        Ensures that Driver Verifier settings are
                            persistent across reboots. This is the default
                            value.
          resetonbootfail   Disables Driver Verifier for subsequent reboots
                            if the system failed to start.
          resetonunusualshutdown
                            Driver Verifier persists until unusual shutdown
                            happens. Its abbrevation, 'rous', can be used.
          oneboot           Enables Driver Verifier only for the next boot.

    /persistthroughupgrade
        Makes the Driver Verifier settings persist through upgrade. Driver
        Verifier will be active during system upgrade.

    /reset
        Clears Driver Verifier flags and driver settings. This option requires
        system reboot to take effect.

    /faults [probability [pool_tags [applications [delay_minutes]]]]
        Enable the Randomized low resources simulation feature and optionally
        control parameters for the Randomized low resources simulation.

          Probability     Specifies the probability that Driver Verifier will
                          fail a given allocation. The value represents the
                          number of chances in 10,000 that Driver Verifier will
                          fail the allocation. The default value 600, means
                          600/10000 or 6.
          Pool Tags:      Specifies a space separated list of the pool tags to
                          be injected with faults. By default, any pool
                          allocation can be injected with faults.
          Applications    Specifies a space separated list of image file names
                          (an executable) that will be injected with faults. By
                          default, any pool allocation can be injected with
                          faults.
          DelayMinutes    Specifies the number of minutes after booting during
                          which Driver Verifier does not intentionally fail any
                          allocations. This delay allows the drivers to load
                          and the system to stabilize before the test begins.
                          The default value is 8 minutes.

    /faultssystematic [<options> ...]
        Controls the Systematic low resources simulation parameters.

          enableboottime          Enables fault injections across reboots.
          disableboottime         Disables fault injections across reboots.
                                  This is the default value.
          recordboottime          Enables fault injections in 'what if' mode
                                  across reboots.
          resetboottime           Disables fault injections across reboots and
                                  clears the stack exclusion list.
          enableruntime           Dynamically enables fault injections.
          disableruntime          Dynamically disables fault injections.
          recordruntime           Dynamically enables fault injections in
                                  'what if' mode.
          resetruntime            Dynamically disables fault injections and
                                  clears the previously faulted stack list.
          querystatistics         Shows the current fault injection statistics.
          incrementcounter        Increments the test pass counter used to
                                  identify when a fault was injected.
          getstackid <counter>    Retrieves the indicated injected stack id.
          excludestack <stack_id> Excludes the stack from fault injection.

    /log <file_name> [/interval <seconds>]
        Creates a log file with the specified name and periodically writes the
        runtime statistics to this file. The interval between log file updates
        is controlled by the '/interval' parameter. The default value is 30
        seconds. Use CTRL+C to close the log and return.

    /volatile
        Changes Driver Verifier settings without rebooting the computer.
        Volatile settings take effect immediately and are in effect until the
        next system reboot.

    /volatile /adddriver <name> [<name> ...]
        Starts the verification for the specified driver or drivers.

    /volatile /removedriver <name> [<name> ...]
        Stops the verification for the specified driver or drivers.

    /domain {wdm | ndis | ks | audio} [rules.all | rules.default] /driver ...
        [/logging | /livedump]
        Controls the verifier extension settings. The following verifier
        extension types are supported:

          wdm               Enabled verifier extension for WDM drivers.
          ndis              Enabled verifier extension for networking drivers.
          ks                Enabled verifier extension for kernel mode
                            streaming drivers.
          audio             Enabled verifier extension for audio drivers.

        The following extension options are supported:

          rules.default     Enables default validation rules for the selected
                            verifier extension.
          rules.all         Enables all validation rules for the selected
                            verifier extension.

        /logging
          Enables logging for violated rules detected by the selected verifier
          extensions.

        /livedump
          Enables live memory dump collection for violated rules detected by
          the selected verifier extensions.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\verifier.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verifier.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\verifier.exe](verifier.exe-2116190AE866163ED485C4FD3E13D03B.md) | 54
[C:\Windows\system32\verifier.exe](verifier.exe-33D4E51F4BEFAE3ACEFA2F5EFFD19F7C.md) | 55
[C:\Windows\system32\verifier.exe](verifier.exe-99EBA9BAF9E048AB6BD29148F4989672.md) | 55
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-03A76A765ABE56C8999A548331F191D9.md) | 55
[C:\WINDOWS\system32\verifiergui.exe](verifiergui.exe-050165D2C58117E249E314450DA9CE85.md) | 52
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-3B4696162C3ABD7BB68D8630464AFC99.md) | 27
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-D6E799255D28472DB220D7270B445728.md) | 52


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## verifier

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Driver verifier manager.

### Syntax
```
verifier /standard /driver <name> [<name> ...]
verifier /standard /all
verifier [/flags <flags>] [/faults [<probability> [<tags> [<applications> [<minutes>]]]] /driver <name> [<name>...]
verifier [/flags FLAGS] [/faults [<probability> [<tags> [<applications> [<minutes>]]]] /all
verifier /querysettings
verifier /volatile /flags <flags>
verifier /volatile /adddriver <name> [<name>...]
verifier /volatile /removedriver <name> [<name>...]
verifier /volatile /faults [<probability> [<tags> [<applications>]]
verifier /reset
verifier /query
verifier /log <LogFileName> [/interval <seconds>]
```
##### Parameters
|Parameter|Description|
|-------|--------|
|\<flags>|Must be a number in decimal or hexadecimal, combination of bits:<p>-   **Value: description**<br />-   **bit 0:** special pool checking<br />-   **bit 1:** force irql checking<br />-   **bit 2:** low resources simulation<br />-   **bit 3:** pool tracking<br />-   **bit 4:** I/O verification<br />-   **bit 5:** deadlock detection<br />-   **bit 6:** unused<br />-   **bit 7:** DMA verification<br />-   **bit 8:** security checks<br />-   **bit 9:** force pending I/O requests<br />-   **bit 10:** IRP logging<br />-   **bit 11:** miscellaneous checks<p>for example, **/flags 27** is equivalent with **/flags 0x1B**|
|/volatile|Used to change the verifier settings dynamically without restarting the system. Any new settings will be lost when the system is restarted.|
|\<probability>|Number between 1 and 10,000 specifying the fault injection probability. For example, specifying 100 means a fault injection probability of 1% (100/10,000).<p>if this parameter is not specified then the default probability of 6% will be used.|
|\<tags>|Specifies the pool tags that will be injected with faults, separated by space characters. If this parameter is not specified then any pool allocation can be injected with faults.|
|\<applications>|Specifies the image file name of the applications that will be injected with faults, separated by space characters. If this parameter is not specified then low resources simulation can take place in any application.|
|\<minutes>|A positive number specifying the length of the period after rebooting, in minutes, during which no fault injection will occur. If this parameter is not specified then the default length of 8 minutes will be used.|
|/?|Displays help at the command prompt.|

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


