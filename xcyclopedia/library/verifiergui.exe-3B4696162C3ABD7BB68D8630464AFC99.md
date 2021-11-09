---
title: verifiergui.exe | Driver Verifier Manager
excerpt: What is verifiergui.exe?
---

# verifiergui.exe 

* File Path: `C:\Windows\system32\verifiergui.exe`
* Description: Driver Verifier Manager

## Hashes

Type | Hash
-- | --
MD5 | `3B4696162C3ABD7BB68D8630464AFC99`
SHA1 | `D89C8E14A565B074C3F3F0988206C59FD169ABB2`
SHA256 | `C32C386510ECA15C717B98025AE032C810E6E258593528BB45481D720CF73AEF`
SHA384 | `B11E4B7E67D2C7C0E1AA5D9E27B4BBBBC66FD746FF88C7FC082EE87B1BC124BE773713EFB34C8207942B70C50B3CFC7D`
SHA512 | `A4CF263EF16B111DE858D45DD61F64EA0526BAB3BBA3B64F59730F4D452EA1B3374FA2B1ED6FB6D32CE59BAAFC2AE665E0D9DF9F45227BD482835C699BB7826D`
SSDEEP | `3072:/cXwItRck0gsAuAB5OYUge4lLVXfInXq+Wx5+9iWKNt5DNeE+daEc5VoJe3+Vcvz:mww3BBongplBvInXq+Wx5+9iWKNt5DNk`

## Runtime Data

### Usage (stdout):
```cmhg
 
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
[C:\Windows\system32\verifier.exe](verifier.exe-2116190AE866163ED485C4FD3E13D03B.md) | 33
[C:\Windows\system32\verifier.exe](verifier.exe-33D4E51F4BEFAE3ACEFA2F5EFFD19F7C.md) | 27
[C:\WINDOWS\system32\verifier.exe](verifier.exe-423CC3565BF713A1BA514AF8F8B061C9.md) | 25
[C:\Windows\system32\verifier.exe](verifier.exe-99EBA9BAF9E048AB6BD29148F4989672.md) | 27
[C:\WINDOWS\system32\verifier.exe](verifier.exe-F3E010D3E862323BEE891727CFAA31C1.md) | 27
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-03A76A765ABE56C8999A548331F191D9.md) | 27
[C:\WINDOWS\system32\verifiergui.exe](verifiergui.exe-050165D2C58117E249E314450DA9CE85.md) | 29
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-D6E799255D28472DB220D7270B445728.md) | 29




MIT License. Copyright (c) 2020-2021 Strontic.


