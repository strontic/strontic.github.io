---
title: bitsadmin.exe | BITS administration utility
excerpt: What is bitsadmin.exe?
---

# bitsadmin.exe 

* File Path: `C:\windows\SysWOW64\bitsadmin.exe`
* Description: BITS administration utility

## Hashes

Type | Hash
-- | --
MD5 | `9AC75D112F499D1466ADFD96738BF978`
SHA1 | `86BB60A6AAE15C260A0D68D6C7802E1EDFD8E680`
SHA256 | `E5892202DB9C37F741BA345D2BAAE658893E10F11FF67DD481DB6693FA3861D3`
SHA384 | `57F9231B14154431C35040A0A89FF3064795D5B3EC589B28875CDC9564769C2F1F773DC42333C9F79E126A8C39090E7E`
SHA512 | `A391A58A25C26908D49FCDE27B363C4FC7568B0AB9C76FA6FDF29BC36EBA4EFF2EE89F2FCB564A152C7F0D69AE2496F106E9470229ED03918921198B69BFD27D`
SSDEEP | `3072:a/+YmI3tJONozWyC/iVBVbGtFRVNkT0jPQHN8+VbpW/5xUITFc:zRaVB5G/AmQHNDlW/52`

## Signature

* Status: The file C:\windows\SysWOW64\bitsadmin.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: bitsadmin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 7.7.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 7.7.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `bitsadmin.exe` being misused. While `bitsadmin.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_bitsadmin_susp_tld.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_bitsadmin_susp_tld.yml) | `title: Bitsadmin to Uncommon TLD`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_bitsadmin_susp_tld.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_bitsadmin_susp_tld.yml) | `description: Detects Bitsadmin connections to domains with uncommon TLDs - https://twitter.com/jhencinski/status/1102695118455349248 - https://isc.sans.edu/forums/diary/Investigating+Microsoft+BITS+Activity/23281/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_bitsadmin_susp_tld.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_bitsadmin_susp_tld.yml) | `- Rare programs that use Bitsadmin and update from regional TLDs e.g. .uk or .ca`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- 'bitsadmin /transfer'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `- '*\bitsadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '*\BITSADMIN*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '*\BITSADMIN*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_bitsjob.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_bitsjob.yml) | `title: Suspicious Bitsadmin Job via PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_creation_bitsadmin_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_creation_bitsadmin_download.yml) | `title: Bitsadmin Download`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_creation_bitsadmin_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_creation_bitsadmin_download.yml) | `description: Detects usage of bitsadmin downloading a file`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_creation_bitsadmin_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_creation_bitsadmin_download.yml) | `- https://blog.netspi.com/15-ways-to-download-a-file/#bitsadmin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_creation_bitsadmin_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_creation_bitsadmin_download.yml) | `- '*\bitsadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_creation_bitsadmin_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_creation_bitsadmin_download.yml) | `- '*copy bitsadmin.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\bitsadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_mssql.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_shell_spawn_from_mssql.yml) | `- '*\bitsadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `- '*\bitsadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Name: Bitsadmin.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\1.txt:cmd.exe NULL bitsadmin /RESUME 1 bitsadmin /complete 1`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: Create a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command from an Alternate data stream, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 bitsadmin /addfile 1 https://live.sysinternals.com/autoruns.exe c:\data\playfolder\autoruns.exe bitsadmin /RESUME 1 bitsadmin /complete 1`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: Create a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /RESUME 1 & bitsadmin /Complete 1 & bitsadmin /reset`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\cmd.exe NULL & bitsadmin /RESUME 1 & bitsadmin /Reset`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: One-liner that creates a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Path: C:\Windows\System32\bitsadmin.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Path: C:\Windows\SysWOW64\bitsadmin.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- IOC: Child process from bitsadmin.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- IOC: bitsadmin creates new files`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- IOC: bitsadmin adds data to alternate data stream`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Bitsadmin Download (cmd) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Bitsadmin Download (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #9: Windows - BITSAdmin BITS Download [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Bitsadmin Download (cmd) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Bitsadmin Download (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #9: Windows - BITSAdmin BITS Download [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | - [Atomic Test #9 - Windows - BITSAdmin BITS Download](#atomic-test-9---windows---bitsadmin-bits-download) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | ## Atomic Test #9 - Windows - BITSAdmin BITS Download | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | This test uses BITSAdmin.exe to schedule a BITS job for the download of a file. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | C:\Windows\System32\bitsadmin.exe /transfer #{bits_job_name} /Priority HIGH #{remote_file} #{local_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | The interface to create and manage BITS jobs is accessible through [PowerShell](https://attack.mitre.org/techniques/T1059/001)  (Citation: Microsoft BITS) and the [BITSAdmin](https://attack.mitre.org/software/S0190) tool. (Citation: Microsoft BITSAdmin) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | - [Atomic Test #1 - Bitsadmin Download (cmd)](#atomic-test-1---bitsadmin-download-cmd) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | - [Atomic Test #2 - Bitsadmin Download (PowerShell)](#atomic-test-2---bitsadmin-download-powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | ## Atomic Test #1 - Bitsadmin Download (cmd) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | This test simulates an adversary leveraging bitsadmin.exe to download | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /transfer /Download /priority Foreground #{remote_file} #{local_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | ## Atomic Test #2 - Bitsadmin Download (PowerShell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | This test simulates an adversary leveraging bitsadmin.exe to schedule a BITS transferand execute a payload in multiple steps. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /create #{bits_job_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /addfile #{bits_job_name} #{remote_file} #{local_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /setnotifycmdline #{bits_job_name} #{command_path} "" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /resume #{bits_job_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | bitsadmin.exe /complete #{bits_job_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | bitsadmin /transfer myDownloadJob /download /priority normal "https://www.win-rar.com/fileadmin/winrar-versions/winrar/th/winrar-x64-580.exe" #{rar_installer} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | bitsadmin /transfer myDownloadJob /download /priority normal "https://www.7-zip.org/a/7z2002-x64.exe" #{7zip_installer} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $x1 = "egsvr32.exe \"/u bitsadmin /canceft\\windows\\currebitsadmin" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_github_net_redteam_tools_guids.yara](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_github_net_redteam_tools_guids.yara) | reference = "https://github.com/bitsadmin/nopowershell" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_github_net_redteam_tools_guids.yara](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_github_net_redteam_tools_guids.yara) | reference = "https://github.com/bitsadmin/fakelogonscreen" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_recon_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_recon_indicators.yar) | $s13 = "bitsadmin /rawreturn /transfer getfile" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | reference = "https://github.com/bitsadmin/nopowershell" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## bitsadmin

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012, Windows 10

Bitsadmin is a command-line tool used to create, download or upload jobs, and to monitor their progress. The bitsadmin tool uses switches to identify the work to perform. You can call `bitsadmin /?` or `bitsadmin /help` to get a list of switches.

Most switches require a `<job>` parameter, which you set to the job's display name, or GUID. A job's display name doesn't have to be unique. The **/create** and **/list** switches return a job's GUID.

By default, you can access information about your own jobs. To access information for another user's jobs, you must have administrator privileges. If the job was created in an elevated state, then you must run **bitsadmin** from an elevated window; otherwise, you'll have read-only access to the job.

Many of the switches correspond to methods in the [BITS interfaces](/windows/win32/bits/bits-interfaces). For additional details that may be relevant to using a switch, see the corresponding method.

Use the following switches to create a job, set and retrieve the properties of a job, and monitor the status of a job. For examples that show how to use some of these switches to perform tasks, see [bitsadmin examples](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-examples.md).

### Available switches

- [bitsadmin /addfile](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfile.md)
- [bitsadmin /addfileset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfileset.md)
- [bitsadmin /addfilewithranges](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfilewithranges.md)
- [bitsadmin /cache](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache.md)
- [bitsadmin /cache /delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-delete.md)
- [bitsadmin /cache /deleteurl](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-deleteurl.md)
- [bitsadmin /cache /getexpirationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-getexpirationtime.md)
- [bitsadmin /cache /getlimit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-getlimit.md)
- [bitsadmin /cache /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-help.md)
- [bitsadmin /cache /info](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-info.md)
- [bitsadmin /cache /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-list.md)
- [bitsadmin /cache /setexpirationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-setexpirationtime.md)
- [bitsadmin /cache /setlimit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-setlimit.md)
- [bitsadmin /cache /clear](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-clear.md)
- [bitsadmin /cancel](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cancel.md)
- [bitsadmin /complete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-complete.md)
- [bitsadmin /create](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-create.md)
- [bitsadmin /examples](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-examples.md)
- [bitsadmin /getaclflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getaclflags.md)
- [bitsadmin /getbytestotal](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getbytestotal.md)
- [bitsadmin /getbytestransferred](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getbytestransferred.md)
- [bitsadmin /getclientcertificate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getclientcertificate.md)
- [bitsadmin /getcompletiontime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcompletiontime.md)
- [bitsadmin /getcreationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcreationtime.md)
- [bitsadmin /getcustomheaders](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcustomheaders.md)
- [bitsadmin /getdescription](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getdescription.md)
- [bitsadmin /getdisplayname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getdisplayname.md)
- [bitsadmin /geterror](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-geterror.md)
- [bitsadmin /geterrorcount](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-geterrorcount.md)
- [bitsadmin /getfilestotal](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getfilestotal.md)
- [bitsadmin /getfilestransferred](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getfilestransferred.md)
- [bitsadmin /gethelpertokenflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethelpertokenflags.md)
- [bitsadmin /gethelpertokensid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethelpertokensid.md)
- [bitsadmin /gethttpmethod](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethttpmethod.md)
- [bitsadmin /getmaxdownloadtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getmaxdownloadtime.md)
- [bitsadmin /getminretrydelay](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getminretrydelay.md)
- [bitsadmin /getmodificationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getmodificationtime.md)
- [bitsadmin /getnoprogresstimeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnoprogresstimeout.md)
- [bitsadmin /getnotifycmdline](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifycmdline.md)
- [bitsadmin /getnotifyflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifyflags.md)
- [bitsadmin /getnotifyinterface](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifyinterface.md)
- [bitsadmin /getowner](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getowner.md)
- [bitsadmin /getpeercachingflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getpeercachingflags.md)
- [bitsadmin /getpriority](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getpriority.md)
- [bitsadmin /getproxybypasslist](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxybypasslist.md)
- [bitsadmin /getproxylist](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxylist.md)
- [bitsadmin /getproxyusage](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxyusage.md)
- [bitsadmin /getreplydata](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplydata.md)
- [bitsadmin /getreplyfilename](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplyfilename.md)
- [bitsadmin /getreplyprogress](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplyprogress.md)
- [bitsadmin /getsecurityflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getsecurityflags.md)
- [bitsadmin /getstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getstate.md)
- [bitsadmin /gettemporaryname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gettemporaryname.md)
- [bitsadmin /gettype](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gettype.md)
- [bitsadmin /getvalidationstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getvalidationstate.md)
- [bitsadmin /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-help.md)
- [bitsadmin /info](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-info.md)
- [bitsadmin /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-list.md)
- [bitsadmin /listfiles](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-listfiles.md)
- [bitsadmin /makecustomheaderswriteonly](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-makecustomheaderswriteonly.md)
- [bitsadmin /monitor](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-monitor.md)
- [bitsadmin /nowrap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-nowrap.md)
- [bitsadmin /peercaching](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching.md)
- [bitsadmin /peercaching /getconfigurationflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-getconfigurationflags.md)
- [bitsadmin /peercaching /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-help.md)
- [bitsadmin /peercaching /setconfigurationflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-setconfigurationflags.md)
- [bitsadmin /peers](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers.md)
- [bitsadmin /peers /clear](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-clear.md)
- [bitsadmin /peers /discover](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-discover.md)
- [bitsadmin /peers /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-help.md)
- [bitsadmin /peers /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-list.md)
- [bitsadmin /rawreturn](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-rawreturn.md)
- [bitsadmin /removeclientcertificate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-removeclientcertificate.md)
- [bitsadmin /removecredentials](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-removecredentials.md)
- [bitsadmin /replaceremoteprefix](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-replaceremoteprefix.md)
- [bitsadmin /reset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-reset.md)
- [bitsadmin /resume](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-resume.md)
- [bitsadmin /setaclflag](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setaclflag.md)
- [bitsadmin /setclientcertificatebyid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setclientcertificatebyid.md)
- [bitsadmin /setclientcertificatebyname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setclientcertificatebyname.md)
- [bitsadmin /setcredentials](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setcredentials.md)
- [bitsadmin /setcustomheaders](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setcustomheaders.md)
- [bitsadmin /setdescription](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setdescription.md)
- [bitsadmin /setdisplayname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setdisplayname.md)
- [bitsadmin /sethelpertoken](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethelpertoken.md)
- [bitsadmin /sethelpertokenflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethelpertokenflags.md)
- [bitsadmin /sethttpmethod](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethttpmethod.md)
- [bitsadmin /setmaxdownloadtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setmaxdownloadtime.md)
- [bitsadmin /setminretrydelay](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setminretrydelay.md)
- [bitsadmin /setnoprogresstimeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnoprogresstimeout.md)
- [bitsadmin /setnotifycmdline](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnotifycmdline.md)
- [bitsadmin /setnotifyflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnotifyflags.md)
- [bitsadmin /setpeercachingflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setpeercachingflags.md)
- [bitsadmin /setpriority](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setpriority.md)
- [bitsadmin /setproxysettings](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setproxysettings.md)
- [bitsadmin /setreplyfilename](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setreplyfilename.md)
- [bitsadmin /setsecurityflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setsecurityflags.md)
- [bitsadmin /setvalidationstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setvalidationstate.md)
- [bitsadmin /suspend](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-suspend.md)
- [bitsadmin /takeownership](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-takeownership.md)
- [bitsadmin /transfer](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-transfer.md)
- [bitsadmin /util](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util.md)
- [bitsadmin /util /enableanalyticchannel](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-enableanalyticchannel.md)
- [bitsadmin /util /getieproxy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-getieproxy.md)
- [bitsadmin /util /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-help.md)
- [bitsadmin /util /repairservice](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-repairservice.md)
- [bitsadmin /util /setieproxy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-setieproxy.md)
- [bitsadmin /util /version](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-version.md)
- [bitsadmin /wrap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-wrap.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


