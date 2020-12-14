---
title: ExtExport.exe | Internet Explorer ImpExp FF exporter
excerpt: What is ExtExport.exe?
---

# ExtExport.exe 

* File Path: `C:\Program Files\internet explorer\ExtExport.exe`
* Description: Internet Explorer ImpExp FF exporter

## Hashes

Type | Hash
-- | --
MD5 | `1D71EDDF5BC772FF5AAE7AD292A179D4`
SHA1 | `092FE10D1B8DACBED9611F30CC82AF6978CC3818`
SHA256 | `D3156EE400DDE48A9F7178CF5C8717A2553BF9ACD3C2322717A53BF207842D8C`
SHA384 | `AF6C94E5AC7941269276B20DA75C93B792FE8ADA0473D6889A8367B3530B75BBE2BF54DC48EC2D048BC1C0F02953FAB2`
SHA512 | `6C2EC4A4539DE31B01A25458B06266F981D749786AC3BDD593F50011F8A524461E6BDB00EEDF4553DF3EA7FE154D8A376FE4447B79067F9E27FF0A7108311E20`
SSDEEP | `1536:MdqbrEa+KYumBchwizRJxdWyfZdSgGjHVTfY2Mv3+3xbKZ/HMsQt1TZ/Iutz:MdqbrEZK+cS+0a8gyrMv3+3xbKZ/HMse`
IMP | `53D3D6675DF14EB40803104BF2C8993D`
PESHA1 | `A1C08826220C653EB4D5BF79E5628172582C7891`
PE256 | `6E588FFE1C271454677CF91976389450453F0774507422C13042D7701FED2ED4`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\internet explorer\ExtExport.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\SYSTEM32\iertutil.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extexport.exe
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/d3156ee400dde48a9f7178cf5c8717a2553bf9acd3c2322717a53bf207842d8c/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\ExtExport.exe](ExtExport.exe-3253FD643C51C133C3489A146781913B.md) | 33
[C:\Program Files (x86)\Internet Explorer\ExtExport.exe](ExtExport.exe-72AC703193E2AD95FF112D3BF08DD4B2.md) | 33
[C:\Program Files\Internet Explorer\ExtExport.exe](ExtExport.exe-B11437540BDFC36FEE80CAEFFF057D41.md) | 46

## Possible Misuse

*The following table contains possible examples of `ExtExport.exe` being misused. While `ExtExport.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `Name: Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Command: Extexport.exe c:\test foo bar` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Path: C:\Program Files\Internet Explorer\Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Path: C:\Program Files (x86)\Internet Explorer\Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- IOC: Extexport.exe loads dll and is execute from other folder the original path` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Link: http://www.hexacorn.com/blog/2018/04/24/extexport-yet-another-lolbin/` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [guildma](https://github.com/eset/malware-ioc/blob/master/guildma/README.adoc) | `** `C:\Program Files (x86)\Internet Explorer\ExtExport.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [guildma](https://github.com/eset/malware-ioc/blob/master/guildma/README.adoc) | `** `C:\Program Files\Internet Explorer\ExtExport.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


