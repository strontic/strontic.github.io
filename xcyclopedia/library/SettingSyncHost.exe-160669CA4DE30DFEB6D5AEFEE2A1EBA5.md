﻿---
title: SettingSyncHost.exe | Host Process for Setting Synchronization
excerpt: What is SettingSyncHost.exe?
---

# SettingSyncHost.exe 

* File Path: `C:\Windows\SysWOW64\SettingSyncHost.exe`
* Description: Host Process for Setting Synchronization

## Hashes

Type | Hash
-- | --
MD5 | `160669CA4DE30DFEB6D5AEFEE2A1EBA5`
SHA1 | `9B136E60CE3D6A44171031AE783987778EC1B164`
SHA256 | `020436DBAF8B73F2CA01EDF68F8098A38BC1FEF8551A51EF424B2C63F5DF3BB1`
SHA384 | `963A22899B507AD69F0EA13F3FB51A59B6D3045900B0E3D9846B77434827F2FFB14B32041BC20BA06800FB8192C06E12`
SHA512 | `226C7545B694933DB3D6BF97E573C9FBC65C18BB8036B87CD81ECD4D52CB247A3DD3DA56EA75F3ED39FD02BFA33C52ABF4D36B77CAA8E204CAE60D68832E9F89`
SSDEEP | `24576:r3TP5qU6KEtzaIsvdNCtCsDTlUDQp6IB+MZV9aF9Xqw:LTOt2IsVNC0sdUDaPkFEw`
IMP | `0AE2ABEE2FDDD74040A4859EE309463A`
PESHA1 | `0A6C4EF8E1C78CFA0B6A9FAA98F66561A303D596`
PE256 | `706B1D97259D5EFCFB5ADCCB80B03A52B94193AC3F65872360E36A812C70D345`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\SettingSyncHost.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SettingSyncHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/020436dbaf8b73f2ca01edf68f8098a38bc1fef8551a51ef424b2c63f5df3bb1/detection/


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


