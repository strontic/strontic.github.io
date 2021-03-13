---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
excerpt: What is VSSVC.exe?
---

# VSSVC.exe 

* File Path: `C:\Windows\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service

## Hashes

Type | Hash
-- | --
MD5 | `183B5C67CF8AACDF33CFD357A72F9490`
SHA1 | `9515ACD323639BB5A55515B625CFA6CF5135BEDE`
SHA256 | `8A2E257EFE4E583B6379E91009DE252FA64F2A43F134B7FC1560CC3E8FBF3688`
SHA384 | `BAF743000A8F94765B5B78410343071AD1628F43D8A4138E27DF07C79B3801F3DBD446B20D44C0EF7E979FAECC1B45F8`
SHA512 | `5556EEC8D863929D195BF70597A05180AAF4FA785727EB45E5CBA8E89CF3BA4C8330D7FB6A10C5F428C8E2EAA6718A05EA8A5A2D0CE44DD04BF8FE3FB5F9D83C`
SSDEEP | `24576:uJwA9WElVxAGjQIjoBcd8ZcGldiPnqOxsX9A:uVFVMoo6uZjldiPJxsX`
IMP | `D013BBE605003724306CBF26BE73548F`
PESHA1 | `2F89363FE79FB60AA0FFB6BE8BD0CA37A87D4FD4`
PE256 | `02D75AE609764D0829B7465AF85B3E17A1ED09FA97432417944DF2FC9E818194`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\system32\AUTHZ.dll |
C:\Windows\system32\bcd.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\DEVOBJ.dll |
C:\Windows\system32\FLTLIB.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\VirtDisk.dll |
C:\Windows\system32\VSSAPI.DLL |
C:\Windows\system32\VssTrace.DLL |
C:\Windows\system32\VSSVC.exe |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/8a2e257efe4e583b6379e91009de252fa64f2a43f134b7fc1560cc3e8fbf3688/detection/


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


