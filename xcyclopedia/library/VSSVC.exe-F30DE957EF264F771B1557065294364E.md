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
MD5 | `F30DE957EF264F771B1557065294364E`
SHA1 | `2038EF619BC2FED8812AB02F67998E3FD6A3F59B`
SHA256 | `C354EBF05CFBB95AAF954038E237D184F9CB2787859B063C9161B57393D90FD0`
SHA384 | `6084385C67572A5446BF87998F1A744D3D3CEA280D544EF35CE539E7DE4E6E7D7BD1E53B3355F7F68B5D217BFA01432C`
SHA512 | `457C7CB5BCEF08CEEA96A064DB3880F2404F24518FAA9347673549A072B3CCFA7E9A87E5D0D6E229D9C1021D0EAF872C7CC94B86FD80EAEDF8A221C469AD174A`
SSDEEP | `24576:NsdFa3EdB/N6BKnzcVsLEeX/Kv/SQ7rBq+:NgaQN6wn0sL/X/ebPB`
IMP | `D00B30A89169E1569AEB550D84D5FE66`
PESHA1 | `A0BAA860245437A922BE382731AA7D6DD7E280C6`
PE256 | `B57A12BF15AA0CBB6E5742011A034CB33A875C943C9C44EB9377C487F3C49995`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\VSSVC.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c354ebf05cfbb95aaf954038e237d184f9cb2787859b063c9161b57393d90fd0/detection


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_vssaudit_secevent_source_registration.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_vssaudit_secevent_source_registration.yml) | `- Legitimate use of VSSVC. Maybe backup operations. It would usually be done by C:\Windows\System32\VSSVC.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


