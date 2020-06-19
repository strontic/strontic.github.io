
# verifiergui.exe 

* File Path: `C:\Windows\SysWOW64\verifiergui.exe`
* Description: Driver Verifier Manager
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4DC139CE2F54F89EF5876272DC590D3C`
SHA1 | `09A16471B95429E8775E8EC900D97AF105D59D26`
SHA256 | `E1BDA156B07B827FEBA54BB2C0341F5678886B70EA463F06D2AE1A162CA585AC`
SHA384 | `30D5DA54EB25B58255BA71BFBD4B31A26C65858F93ED591804535879871AC6FFB48923CBBDA221A87BBA04103BAA1C9F`
SHA512 | `0C6403606D7A167085A9BE783D72F634B331D8DD36D75CBE5386A690AB4D2B18932448C0B103F0C98CD140FC81A4925355A49A1BF2E65401CE58F9F02122C572`
SSDEEP | `3072:6X2X3Xv22pr9X/XDoXdBewFXyEXm6XVvXQRjXwcJVIZen+Vcv2JBwwRBkBnRzePp:qGnjvsD5T5QpZfSwnR12q7USGMFR6t`

## Runtime Data

### Usage (stdout):
```Batchfile
 
Copyright (c) Microsoft Corporation. All rights reserved.
 
COMMON USAGE: 
  verifier /?
  verifier /standard /all
  verifier /standard /driver NAME [NAME ...]
  verifier /flags FLAGS /all
  verifier /flags FLAGS /driver NAME [NAME ...]
  verifier /rules [OPTION ...]
  verifier /query
  verifier /querysettings
  verifier /bootmode [persistent|resetonbootfail|oneboot]
  verifier /reset
  verifier /faults [PROB [TAGS [APPS [MINS]]]]
  verifier /faultssystematic [OPTION ...]
  verifier /log LOG_FILE_NAME [/interval SECONDS]
  verifier /volatile /flags FLAGS
  verifier /volatile /adddriver NAME [NAME ...]
  verifier /volatile /removedriver NAME [NAME ...]
  verifier /volatile /faults [PROB [TAGS [APPS [MINS]]]]
 
/?
  This help.
 
/standard
  Enable the Driver Verifier standard flags. 
  This is functionally equivalent to '/flags 0x209BB'
 
/all
  Enable Driver Verifier on all drivers in a system.
 
/driver NAME [NAME ...]
  Specify the driver or list of drivers that should be verified.
  NAME is the name and extension of the file to verify (example: driver.sys).
  To enable Driver Verifier on more than one driver, list all drivers using a
  space separated list.  Wildcard values (such as n*.sys) are not supported.
 
/flags FLAGS 
  Specify which options are enabled for verification. 
  FLAGS value must be a number in decimal or hex (with 0x prefix).
  Note: Flags are applied to all drivers being checked by Driver Verifier. 
 
  STANDARD FLAGS:
  These flags are considered standard options for Driver Verifier and can be 
  set using '/standard' or by the combination of the options: '/flags 0x209BB'
    bit  0 (0x00000001) - Special pool
    bit  1 (0x00000002) - Force IRQL checking
    bit  3 (0x00000008) - Pool tracking
    bit  4 (0x00000010) - I/O verification
    bit  5 (0x00000020) - Deadlock detection
    bit  7 (0x00000080) - DMA checking
    bit  8 (0x00000100) - Security checks
    bit 11 (0x00000800) - Miscellaneous checks
    bit 17 (0x00020000) - DDI compliance checking
 
  ADDITIONAL FLAGS:
  These flags are designed for specific scenario testing.
  Flags marked with a (*) require I/O Verification (bit 4) also be enabled.
  Flags marked with a (**) support disabling of individual rules.
    bit  2 (0x00000004) - Randomized low resources simulation
    bit  9 (0x00000200) - Force pending I/O requests (*)
    bit 10 (0x00000400) - IRP logging (*)
    bit 13 (0x00002000) - Invariant MDL checking for stack (*)
    bit 14 (0x00004000) - Invariant MDL checking for driver (*)
    bit 15 (0x00008000) - Power framework delay fuzzing
    bit 16 (0x00010000) - Port/miniport interface checking
    bit 18 (0x00040000) - Systematic low resources simulation
    bit 19 (0x00080000) - DDI compliance checking (additional)
    bit 21 (0x00200000) - NDIS/WIFI verification (**)
    bit 23 (0x00800000) - Kernel synchronization delay fuzzing
    bit 24 (0x01000000) - VM switch verification
    bit 25 (0x02000000) - Code integrity checks
 
/rules [OPTION ...]
  Options for rules that can be disabled (advanced). 
  query:      shows current status of controllable rules.
  reset:      resets all rules to their default state.
  default ID: sets rule ID to its default state.
  disable ID: disables specified rule ID.
 
/query
  Display a summary of Driver Verifier's current activity.
 
/querysettings
  Display a summary of the options and drivers that are currently enabled, 
  or options and drivers that will be verified after the next boot.  The 
  display does not include drivers and options added using /volatile.
 
/bootmode
  Sets the verifier boot mode.  Requires reboot to take effect.
  persistent:      Ensures that DV settings are persistent over many reboots.
                   This is default.
  resetonbootfail: If OS fails to boot, reset verifier for subsequent boots.
  oneboot:         Only enable verifier for next boot.
 
/reset
  Clear Driver Verifier flag and driver settings. Does not clear bootmode.
  Requires reboot to take effect.
 
/faults [PROB [TAGS [APPS [MINS]]]]
  Enable the Randomized low resources simulation bit and optionally control
  parameters for the Randomized low resources simulation.
  PROB: A number between 1 and 10000 specifying the fault injection 
        probability. If this parameter is not specified, then the default 
        value of 600 (6%) will be used.
  TAGS: A space separated list of the pool tags to be injected with faults.
        If this parameter is not specified, then any pool allocation can be
        injected with faults.
  APPS: A space separated list of the image filename of the applications that
        will be injected with faults. If this parameter is not specified then
        the Randomized low resources simulation can take place in any
        application.
  MINS: A positive number indicating the of minutes after rebooting during 
        which no fault injection will occur. If this parameter is not 
        specified, then the default length of 8 minutes will be used.
 
/faultssystematic [OPTION ...]
  Options for controlling the Systematic low resources simulation.
  enableboottime:       enables fault injections across reboots.
  disableboottime:      disables fault injections across reboots (default).
  recordboottime:       enables fault injections in 'what if' mode across
                        reboots.
  resetboottime:        disables fault injections across reboots and clears
                        the stack exclusion list.
  enableruntime:        dynamically enables fault injections.
  disableruntime:       dynamically disables fault injections.
  recordruntime:        dynamically enables fault injections in 'what if'
                        mode.
  resetruntime:         dynamically disables fault injections and clears the
                        previosly faulted stack list.
  querystatistics:      shows the current fault injection statistics.
  incrementcounter:     increments the test pass counter used to identify
                        when a fault was injected.
  getstackid COUNTER:   retrieves the indicated injected stack id.
  excludestack STACKID: excludes the stack from fault injection.
 
/log LOG_FILE_NAME [/interval SECONDS]
  Create a log file with the name LOG_FILE_NAME. 
  If '/interval' option is not specified, the default 30 seconds is used. 
  Note: If a 'verifier /log' command is typed at the command line, the command
  prompt does not return. Use CTRL+C to close the log and return.
 
/volatile
  Change the verifier settings dynamically without rebooting the system.
  Volatile settings are in effect until the next system reboot. 
 
/volatile /adddriver NAME [NAME ...]
  Add the specified driver or drivers to the list of drivers that will be 
  checked with volatile settings. 
 
/volatile /removedriver NAME [NAME ...]
  Remove the specified driver or drivers from the list of drivers that are
  being checked with volatile settings. 
 

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verifiergui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\verifiergui.exe](verifiergui.exe-1FFDE5339B78158668EDF02922258208.md) | 40




MIT License. Copyright (c) 2020 Strontic.


