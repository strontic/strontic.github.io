---
title: control.exe | Windows Control Panel
excerpt: What is control.exe?
---

# control.exe 

* File Path: `C:\windows\SysWOW64\control.exe`
* Description: Windows Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `F74B09C54E47526BB0679F8F0967AD0E`
SHA1 | `14ACDB96C0CF537B20099962B2536BCA48775DC4`
SHA256 | `088B7693BE0643277D16A66862B4446A288AFB86B2E987FE7A943126D0DD08F0`
SHA384 | `4084BF18B0E4C83B02D4C22C6176D4656AF15A860FC357B666BCCF46763D396E44284C53F8FB5D5F9C885343365807DA`
SHA512 | `08C22D09276984DC35CD660E02A0593898970AAABFE0EC1CF2DA8236F04AFF372624BA48D8BE9B6BAF411EB867554F016A08E92453B9943F81558DEDF87D14C2`
SSDEEP | `1536:e4EMLqAaMre/qzSpZ3r1q6QkjfkQUk8+k6kawM1x8Dkf8dani25imK:NLL9rr7Sp5+1k12b/Af885RK`

## Signature

* Status: The file C:\windows\SysWOW64\control.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CONTROL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\control.exe](control.exe-3011923664DA91ED45B0FA6AE852DD1A.md) | 68
[C:\WINDOWS\system32\control.exe](control.exe-44A936B4839A614723811EA66423B432.md) | 80
[C:\windows\system32\control.exe](control.exe-4B605DF70C49B6B9D65652879ACAEE32.md) | 85
[C:\WINDOWS\system32\control.exe](control.exe-62D970D8B60F75C12D21C740F2D8A5DA.md) | 83
[C:\Windows\system32\control.exe](control.exe-88EA810385F455C74306D71C4879C61C.md) | 80
[C:\Windows\system32\control.exe](control.exe-924219B426830FF7476AF7D22AE91DE1.md) | 85
[C:\Windows\system32\control.exe](control.exe-D7D596CA323E67AAE7F8752BD9B45A1E.md) | 82
[C:\Windows\SysWOW64\control.exe](control.exe-1F13E714A0FEA8887707DFF49287996F.md) | 86
[C:\Windows\SysWOW64\control.exe](control.exe-359DE40504BF90EFD590C248B71C8B81.md) | 85
[C:\Windows\SysWOW64\control.exe](control.exe-4DBD69D4C9DA5AAAC731F518EF8EBEA0.md) | 65
[C:\WINDOWS\SysWOW64\control.exe](control.exe-C7C91F18B0F90ABE6C09D3CEAA895E83.md) | 83
[C:\Windows\SysWOW64\control.exe](control.exe-C8FA632CEF3B25E6AAD2C3ACFCF98E59.md) | 85
[C:\WINDOWS\SysWOW64\control.exe](control.exe-DB53126BF65990E37E3A3B12D3DEDBCE.md) | 85

## Possible Misuse

*The following table contains possible examples of `control.exe` being misused. While `control.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_cve_2021_40444.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_cve_2021_40444.yml) | `Image\|endswith: '\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_cve_2021_40444.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_cve_2021_40444.yml) | `CommandLine\|endswith: '\control.exe input.dll'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `description: Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `ParentImage\|endswith: '\System32\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `description: Detects using WorkFolders.exe to execute an arbitrary control.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `Image\|endswith: '\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `Image: 'C:\Windows\System32\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `Name: Control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Command: control.exe c:\windows\tasks\file.txt:evil.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\System32\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\SysWOW64\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- IOC: Control.exe executing files from alternate data streams.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `Description: Execute control.exe in the current working directory`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | <blockquote>Adversaries may abuse control.exe to proxy execution of malicious payloads. The Windows Control Panel process binary (control.exe) handles execution of Control Panel items, which are utilities that allow users to view and adjust computer settings. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | This test simulates an adversary leveraging control.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | control.exe #{cpl_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


