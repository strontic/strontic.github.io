---
title: cmdl32.exe | Microsoft Connection Manager Auto-Download
excerpt: What is cmdl32.exe?
---

# cmdl32.exe 

* File Path: `C:\WINDOWS\system32\cmdl32.exe`
* Description: Microsoft Connection Manager Auto-Download

## Hashes

Type | Hash
-- | --
MD5 | `67039B98067CFE9B5B9739C9BBB41267`
SHA1 | `900F212C4CB63F1F6951FB46A4CF5D27184BEEA6`
SHA256 | `335D472C81B05E6DF922B5523FE026AF2FCD48D025FA040F6896513C674F20D8`
SHA384 | `F2A742DDA7E1AE54832DEA6AF8B37720E536C43ECB13E83817FB850A47D8D605F743B0FD337AB4A99420AD634913E95E`
SHA512 | `34D297C3C337D0CC3C2A10880E8FBC1320F8811697EDB739FF803214A27D4A0EE4FA13AFBDB6C11CF60409C2C53DC4A014966DE7AEB520CDE2B12CCF9EAFA414`
SSDEEP | `1536:y3w2uo1ZtqEoPsxYlDRkd7yyPxL4teP0etTeVkheKdm2cdI:y3wi1qvYYVRzqt3eKdmtI`
IMP | `056F4AD9405ED9764A5EED3AD07A7804`
PESHA1 | `3F41F5BA73D40DF1F4A3A4B624F2E64852B24FD0`
PE256 | `E337AD7114A78331A3F5B171E584489F291037D804245A7A1F773A90D217A473`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\system32\cmdl32.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMDL32.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.22000.1 (WinBuild.160101.0800)
* Product Version: 7.2.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/335d472c81b05e6df922b5523fe026af2fcd48d025fa040f6896513c674f20d8/detection


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


