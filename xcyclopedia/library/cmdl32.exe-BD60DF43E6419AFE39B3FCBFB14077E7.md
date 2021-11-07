---
title: cmdl32.exe | Microsoft Connection Manager Auto-Download
excerpt: What is cmdl32.exe?
---

# cmdl32.exe 

* File Path: `C:\Windows\SysWOW64\cmdl32.exe`
* Description: Microsoft Connection Manager Auto-Download

## Hashes

Type | Hash
-- | --
MD5 | `BD60DF43E6419AFE39B3FCBFB14077E7`
SHA1 | `ED73F4A5605FBDE7CA7454D8E851B6EB6F14DA11`
SHA256 | `85B76DE4B1E44D375DF9D8D668B4BC4B91565A9BC652654C789A5EAD6D5E1AEC`
SHA384 | `5695D998DF905488A9C5F5605D5D21DFC9989985A258FF4CAE395D10E29729DCA75862DB6DE7E0920DD9CAF96ADA118A`
SHA512 | `537078C7BBA3F2E28152618F89A78F49B9D018CB9CE7F79DA974E0324D7EACA4D08273BE897616E8C891E182634895294B48B059C2AAA8F7A10F9B8FE6F4BB3C`
SSDEEP | `768:OTqHPEiucKttmhpGt7ZnPJ+GO7fRk+gogm4m5LXaqauwwiI/:OT+PEJcKtt+ye//4z0BiI`
IMP | `BA2BC70069F6B2E3580725012BA0CDE5`
PESHA1 | `35727A5A79C3779A925870D6609B24AE85E25051`
PE256 | `CBBD67909F480504ACD15C1A8087947E1F1F5FAE1CFD6EEBDF65ED7750E1E852`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\cmdl32.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMDL32.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.19041.1 (WinBuild.160101.0800)
* Product Version: 7.2.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/85b76de4b1e44d375df9d8d668b4bc4b91565a9bc652654c789a5ead6d5e1aec/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\cmdl32.exe](cmdl32.exe-5C354F6BA0DF7D01B2CB5CF08140B67E.md) | 43
[C:\Windows\SysWOW64\cmdl32.exe](cmdl32.exe-87390E37E36622B054D4BDCBB7997B6C.md) | 54
[C:\WINDOWS\SysWOW64\cmdl32.exe](cmdl32.exe-CD38B65FBFF35E1D3E307DD70F1D2E99.md) | 50

## Possible Misuse

*The following table contains possible examples of `cmdl32.exe` being misused. While `cmdl32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `title: Suspicious Cmdl32 Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `description: lolbas Cmdl32 is use to download a payload to evade antivirus`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Cmdl32/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `cmdl32:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- Image\|endswith: '\cmdl32.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `- OriginalFileName: CMDL32.EXE`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_pc_susp_cmdl32_lolbas.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_pc_susp_cmdl32_lolbas.yml) | `condition: cmdl32 and options`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `Name: cmdl32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Command: cmdl32 /vpn /lan %cd%\config`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Path: C:\Windows\System32\cmdl32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdl32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdl32.yml) | `- Path: C:\Windows\SysWOW64\cmdl32.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


