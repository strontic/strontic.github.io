﻿---
title: verifiergui.exe | Driver Verifier Manager
excerpt: What is verifiergui.exe?
---

# verifiergui.exe 

* File Path: `C:\WINDOWS\SysWOW64\verifiergui.exe`
* Description: Driver Verifier Manager

## Hashes

Type | Hash
-- | --
MD5 | `C52445F1AD490322ADC5D1AC5EFEEA61`
SHA1 | `F64F8435E78829771AE66C82F1F99B66C8F284AF`
SHA256 | `9BF9B7BE973D88E8875DF7D8AECD0D48EF641D788D829BA63D7267AD2AF479A3`
SHA384 | `FE2375BE6225989857EF99A3753A78596A26F7D1EF8E23419A8B9B3AACCF2488130A4BD81C01ABA34642386736E602B9`
SHA512 | `227408D122AA6B01BAD2FA7A1AB89B96C778505F2018D30DB1EA55FE86D654837D5C2FC5ED8614EB9AA2C16692FE98AF7AEA6479B4AEB299C94990299F9FE750`
SSDEEP | `3072:JcJVIZen+Vcv2JBwwJBkBnRePnj0d+z7zqZzOrb4pEr3tVTjrbUsFUSQpZv3kht3:0KdOsFNhTDzFoV//+`
IMP | `8483DB300823CBF76507101B5FC77710`
PESHA1 | `A15C440E130D32634D7A4551346A04C0BA9D0501`
PE256 | `A79712FD3AAA0101F299EA1B2314A8329AC783C85C7AFFDDB47EAF22A4A44456`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\verifiergui.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verifiergui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9bf9b7be973d88e8875df7d8aecd0d48ef641d788d829ba63d7267ad2af479a3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\verifiergui.exe](verifiergui.exe-1FFDE5339B78158668EDF02922258208.md) | 49
[C:\Windows\SysWOW64\verifiergui.exe](verifiergui.exe-4DC139CE2F54F89EF5876272DC590D3C.md) | 38
[C:\Windows\SysWOW64\verifiergui.exe](verifiergui.exe-56D77A92B6AFACDE189C0A5613A0F6CA.md) | 57
[C:\Windows\SysWOW64\verifiergui.exe](verifiergui.exe-F61085E8A94C91AE6FF47F0D6FF449AF.md) | 55




MIT License. Copyright (c) 2020-2021 Strontic.


