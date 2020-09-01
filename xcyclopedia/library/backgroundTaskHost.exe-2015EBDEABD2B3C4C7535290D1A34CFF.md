---
title: backgroundTaskHost.exe | Background Task Host
---

# backgroundTaskHost.exe 

* File Path: `C:\windows\system32\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `2015EBDEABD2B3C4C7535290D1A34CFF`
SHA1 | `85E7FF8562531243BA4054C8555CC10B21A5B6E1`
SHA256 | `C0A4C60C7747EDACF18735F0BA41F2D7DEDAC813B3F4D4CE6E18F9D1E6CE746F`
SHA384 | `CA9CDDF1E41F267D9B8F1D2EB4B98C8DEC9F060FB22CC59C0629E5076CE68E096DAA8ED436084A45305D01E1AF6E15C8`
SHA512 | `64F45396FBD8A42A38EAEABFF7FF310FDDC48CB2F4116D8B976F79C77497D53FE6606554EB4F7EA09711448C6E5254F5FC6BB24E33FEB6FA495C37311B3995EC`
SSDEEP | `192:l4vXfNPm8jCQVkHW5EpYvateomzETeAOL/SQOke5WpeGWig:8f0Jz49y1TeP7OkuWMGWig`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\baaupdate.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: The file C:\windows\system32\backgroundTaskHost.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `         - BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


