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
MD5 | `D6E799255D28472DB220D7270B445728`
SHA1 | `07092974428BAA7ED3AA926AD4F277BC84DABE7C`
SHA256 | `5D1868E396A185B1893A9092858CDEE53664D5554DF4D3F797B48CFF8E94F7AF`
SHA384 | `A293CA98B890B1A6453CD6614FACEEF68BB9C61D92FE773C4CC01E6575F084AE754F97FBDDA807EE3B052537CD7CEFE6`
SHA512 | `25443CF769286BB194B60E62335735080B772ADE98D5131E92CC4076BC4DC3713E229B7DE95149AD1DB738BF8337AB679B24F56BE6B61DD9EEC1C5DF78897CB9`
SSDEEP | `3072:6uSWXsgFf1R7Wx6maDkCc8XDc5VoJe3+Vcv2JxQQBBEB3BefnjA+Trjq+rfCFG2P:Y7gBjm6g2b2F8a`
IMP | `21008BDE061FD8E970A7B9F78832EBE1`
PESHA1 | `DEA8AC30547C25CAD1337F1B6287EEDEFE1949D8`
PE256 | `766DB8BADA9DC495468BB135ECFAA6495C7A8C9CE8C9C37CFA4BD64C59384D04`

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
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\COMDLG32.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\imagehlp.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\verifiergui.exe |
C:\Windows\system32\VERSION.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\System32\WINTRUST.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verifiergui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5d1868e396a185b1893a9092858cdee53664d5554df4d3f797b48cff8e94f7af/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\verifier.exe](verifier.exe-2116190AE866163ED485C4FD3E13D03B.md) | 49
[C:\Windows\system32\verifier.exe](verifier.exe-33D4E51F4BEFAE3ACEFA2F5EFFD19F7C.md) | 57
[C:\Windows\system32\verifier.exe](verifier.exe-99EBA9BAF9E048AB6BD29148F4989672.md) | 60
[C:\WINDOWS\system32\verifier.exe](verifier.exe-F3E010D3E862323BEE891727CFAA31C1.md) | 52
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-03A76A765ABE56C8999A548331F191D9.md) | 54
[C:\WINDOWS\system32\verifiergui.exe](verifiergui.exe-050165D2C58117E249E314450DA9CE85.md) | 55
[C:\Windows\system32\verifiergui.exe](verifiergui.exe-3B4696162C3ABD7BB68D8630464AFC99.md) | 29




MIT License. Copyright (c) 2020 Strontic.


