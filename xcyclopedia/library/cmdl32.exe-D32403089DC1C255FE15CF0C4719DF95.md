﻿---
title: cmdl32.exe | Microsoft Connection Manager Auto-Download
excerpt: What is cmdl32.exe?
---

# cmdl32.exe 

* File Path: `C:\windows\system32\cmdl32.exe`
* Description: Microsoft Connection Manager Auto-Download

## Hashes

Type | Hash
-- | --
MD5 | `D32403089DC1C255FE15CF0C4719DF95`
SHA1 | `C2314E7DE37DA6820BD190B3015DF5E727B81092`
SHA256 | `41D6A65AE50F7D01D5B641C062FFE3121AD8BFBF53ACFC5631CB1410F8B17FB9`
SHA384 | `DF688479A6BEB469F5855219424ED7EE898D3E5026D704ABE269C36F06BDA4E818BF0B057C13AAE62933F9AE9923442C`
SHA512 | `350C7A330866122E22A8E796366A2B765C9AA939C40F12FB6883A102D930D6FF41951BD406234A34E79C7346DEC8B7F7B4F05725BC7879B122F14897D0D8AFC8`
SSDEEP | `1536:sEzQXkp8Kdn9sFBIJqog8fMtILOajOPI:P8KdKaso4hlI`

## Signature

* Status: The file C:\windows\system32\cmdl32.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CMDL32.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.02.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 7.02.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


