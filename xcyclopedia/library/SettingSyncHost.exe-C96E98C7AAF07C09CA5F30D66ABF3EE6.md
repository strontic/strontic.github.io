---
title: SettingSyncHost.exe | Host Process for Setting Synchronization
excerpt: What is SettingSyncHost.exe?
---

# SettingSyncHost.exe 

* File Path: `C:\Windows\system32\SettingSyncHost.exe`
* Description: Host Process for Setting Synchronization

## Hashes

Type | Hash
-- | --
MD5 | `C96E98C7AAF07C09CA5F30D66ABF3EE6`
SHA1 | `35CA7AC6AFBB477B80AD0372B9CF34612D5AF5C3`
SHA256 | `F31163E9FC05D8490733C41D8FBB2B4FB407E1A4CEF0B1E9855E5813B3026F98`
SHA384 | `2A245444BD6398C48A4A3B8CCD3BDEEAE5F80478856E1B6F2D1F2E51DEAC7F5E44620ED967E37F1B85DD42291566168B`
SHA512 | `AAFE8F5FAEF08E6FC91303510327D6316A1D29EDFE00C31A62DDFE4D1FF0A11A8C7EC9856FFFBE8F07F9505ACF90712CC671AE4B7228AB0ABA793AF3B4030235`
SSDEEP | `24576:U8VMMOqumbzhPHvpgy5Cgr5Z5Vj19sTDPtFL:IWvdpNwgVZ5VjcTztFL`
IMP | `8049F9993FD0B0E41EDE568A3C5646B8`
PESHA1 | `D6CCB4314E125902BF22EC46AE17BC690D4A0B64`
PE256 | `5BC27781630401B52E51BB4305BA82BE69E4F4F2923D00DCC08FA8500E644FAA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SettingSyncHost.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SettingSyncHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f31163e9fc05d8490733c41d8fbb2b4fb407e1a4cef0b1e9855e5813b3026f98/detection


## Possible Misuse

*The following table contains possible examples of `SettingSyncHost.exe` being misused. While `SettingSyncHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `title: Using SettingSyncHost.exe as LOLBin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `description: Detects using SettingSyncHost.exe to run hijacked binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `- https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `Name: SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScript anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScriptNoCab anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\System32\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\SysWOW64\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- IOC: SettingSyncHost.exe should not be run on a normal workstation`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Link: https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin/`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


