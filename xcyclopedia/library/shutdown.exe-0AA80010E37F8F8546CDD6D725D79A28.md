﻿---
title: shutdown.exe | Windows Shutdown and Annotation Tool
excerpt: What is shutdown.exe?
---

# shutdown.exe 

* File Path: `C:\windows\system32\shutdown.exe`
* Description: Windows Shutdown and Annotation Tool

## Hashes

Type | Hash
-- | --
MD5 | `0AA80010E37F8F8546CDD6D725D79A28`
SHA1 | `BC95B18EDC07B12B56E7FC177356631A1EDD23F0`
SHA256 | `7C8E3DBC64BCB84D6B58DBB0A633B6B0F0BCF6746EACEDD93ABE2C9C41E80318`
SHA384 | `C255BB474AC29962DAA8923D5A45D58C383B28CB7A30C8EDA5FD1200FEB5F36411E3B230816A58BE9918785210F1F030`
SHA512 | `A53E16FFCBD68E1F632F78D5C3F66B24B7C82D9698EA84C8387424E508B2BF11F739389D09F770E678E631E0ED604987E4DE320C7B837DC9FD55000C8544102F`
SSDEEP | `768:ql+9cWbY70D/oFunwwFHvHUQLNymwCXX2zv5jz+:n/oFmwwFP/wEX2zvRz`

## Signature

* Status: The file C:\windows\system32\shutdown.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: SHUTDOWN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `shutdown.exe` being misused. While `shutdown.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [macos_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_system_shutdown_reboot.yml) | `title: 'System Shutdown/Reboot'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [macos_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_system_shutdown_reboot.yml) | `description: 'Adversaries may shutdown/reboot systems to interrupt access to, or aid in the destruction of, those systems.'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [macos_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_system_shutdown_reboot.yml) | `- '/shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_system_shutdown_reboot.yml) | `title: 'System Shutdown/Reboot'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_system_shutdown_reboot.yml) | `description: 'Adversaries may shutdown/reboot systems to interrupt access to, or aid in the destruction of, those systems.'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_system_shutdown_reboot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_system_shutdown_reboot.yml) | `- 'shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_dos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_dos.yml) | `description: Detect a system being shutdown or put into different boot mode`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_dos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_dos.yml) | `- 'shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `# Shutdown in safe mode immediately `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `- 'shutdown /r /f /t 00'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `- Scripts that shutdown the system immediately and reboot them in safe mode are unlikely`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_asep_reg_keys_modification.yml) | `- '\Group Policy\Scripts\Shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_asep_reg_keys_modification.yml) | `- '\Shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `shutdown`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Shutdown System - Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #6: Shutdown System via `halt` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #8: Shutdown System via `poweroff` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #6: Shutdown System via `halt` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #8: Shutdown System via `poweroff` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Shutdown System - Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/linux-matrix.md) | \|  \|  \| Implant Internal Image [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Setuid and Setgid](../../T1548.001/T1548.001.md) \| [Dynamic Linker Hijacking](../../T1574.006/T1574.006.md) \| [Private Keys](../../T1552.004/T1552.004.md) \| [System Checks](../../T1497.001/T1497.001.md) \|  \| Remote Email Collection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/macos-matrix.md) | \|  \|  \| Modify Authentication Process [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Re-opened Applications](../../T1547.007/T1547.007.md) \| Hidden Window [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal Web Session Cookie [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Owner/User Discovery](../../T1033/T1033.md) \|  \|  \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \| [Scheduled Task](../../T1053.005/T1053.005.md) \| [Container Orchestration Job](../../T1053.007/T1053.007.md) \| [Default Accounts](../../T1078.001/T1078.001.md) \| [DLL Search Order Hijacking](../../T1574.001/T1574.001.md) \| [Keychain](../../T1555.001/T1555.001.md) \| [Query Registry](../../T1012/T1012.md) \|  \| [Local Email Collection](../../T1114.001/T1114.001.md) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \| [Windows Management Instrumentation](../../T1047/T1047.md) \| [Domain Account](../../T1136.002/T1136.002.md) \| [Dynamic-link Library Injection](../../T1055.001/T1055.001.md) \| [Disable or Modify System Firewall](../../T1562.004/T1562.004.md) \| Man-in-the-Middle [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| System Location Discovery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| Remote Data Staging [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | # T1529 - System Shutdown/Reboot | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | <blockquote>Adversaries may shutdown/reboot systems to interrupt access to, or aid in the destruction of, those systems. Operating systems may contain commands to initiate a shutdown/reboot of a machine. In some cases, these commands may also be used to initiate a shutdown/reboot of a remote computer.(Citation: Microsoft Shutdown Oct 2017) Shutting down or rebooting systems may disrupt access to computer resources for legitimate users. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | Adversaries may attempt to shutdown/reboot a system after impacting it in other ways, such as [Disk Structure Wipe](https://attack.mitre.org/techniques/T1561/002) or [Inhibit System Recovery](https://attack.mitre.org/techniques/T1490), to hasten the intended effects on system availability.(Citation: Talos Nyetya June 2017)(Citation: Talos Olympic Destroyer 2018)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #1 - Shutdown System - Windows](#atomic-test-1---shutdown-system---windows) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #3 - Restart System via `shutdown` - macOS/Linux](#atomic-test-3---restart-system-via-shutdown---macoslinux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #4 - Shutdown System via `shutdown` - macOS/Linux](#atomic-test-4---shutdown-system-via-shutdown---macoslinux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #6 - Shutdown System via `halt` - Linux](#atomic-test-6---shutdown-system-via-halt---linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #8 - Shutdown System via `poweroff` - Linux](#atomic-test-8---shutdown-system-via-poweroff---linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #1 - Shutdown System - Windows | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Timeout period before shutdown (seconds) \| Integer \| 1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /s /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /r /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #3 - Restart System via `shutdown` - macOS/Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -r #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #4 - Shutdown System via `shutdown` - macOS/Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Time to shutdown (can be minutes or specific time) \| String \| now\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -h #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #6 - Shutdown System via `halt` - Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #8 - Shutdown System via `poweroff` - Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | shutdown /r /t 0 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | $s3 = "shutdown /r /t %d" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | $s9 = "shutdown.exe" fullword wide /* Goodware String - occured 1 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $DK_shutdown = "shutdown /r /t %d" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keylogger_cn.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keylogger_cn.yar) | $s3 = "shutdown.exe -r -t 0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turbo_campaign.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turbo_campaign.yar) | $s32 = "shutdown" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $s7 = "shutdown -r -t 00" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $c2 = "shutdown -r -t 00" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [pua_xmrig_monero_miner.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/pua_xmrig_monero_miner.yar) | $s2 = "* COMMANDS:     'h' hashrate, 'p' pause, 'r' resume, 'q' shutdown" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [0821b0b0-7902-4a7b-8052-80bda5a43684.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/0821b0b0-7902-4a7b-8052-80bda5a43684.yml) | `name: Shutdown Target System`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [0821b0b0-7902-4a7b-8052-80bda5a43684.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/0821b0b0-7902-4a7b-8052-80bda5a43684.yml) | `description: Force shutdown a target system using Process Injection and raw shellcode`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## shutdown

Enables you to shut down or restart local or remote computers, one at a time.

### Syntax

```
shutdown [/i | /l | /s | /sg | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/fw] [/f] [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]
```

#### Parameters

| Parameter | Description |
|--|--|
| /i | Displays the **Remote Shutdown** box. The **/i** option must be the first parameter following the command. If **/i** is specified, all other options are ignored. |
| /l | Logs off the current user immediately, with no time-out period. You cannot use **/l** with **/m** or **/t**. |
| /s | Shuts down the computer. |
| /sg | Shuts down the computer. On the next boot, if **Automatic Restart Sign-On** is enabled, the device automatically signs in and locks based on the last interactive user. After sign in, it restarts any registered applications. |
| /r | Restarts the computer after shutdown. |
| /g | Shuts down the computer. On the next restart, if **Automatic Restart Sign-On** is enabled, the device automatically signs in and locks based on the last interactive user. After sign in, it restarts any registered applications. |
| /a | Aborts a system shutdown. Effective only during the time-out period. To use **/a**, you must also use the **/m** option. |
| /p | Turns off the local computer only (not a remote computer)â€”with no time-out period or warning. You can use **/p** only with **/d** or **/f**. If your computer doesn't support power-off functionality, it will shut down when you use **/p**, but the power to the computer will remain on. |
| /h | Puts the local computer into hibernation, if hibernation is enabled. You can use **/h** only with **/f**. |
| hybrid | Shuts down the device and prepares it for fast startup. This option must be used with the **/s** option. |
| /fw | Combining this option with a shutdown option causes the next restart to go to the firmware user interface. |
| /e | Enables you to document the reason for the unexpected shutdown on the target computer. |
| /o | Goes to the **Advanced boot options** menu and restarts the device. This option must be used with the **/r** option. |
| /f | Forces running applications to close without warning users.<br>**Caution:** Using the **/f** option might result in loss of unsaved data. |
| /m `\\<computername>` | Specifies the target computer. Can't be used with the **/l** option. |
| /t `<xxx>` | Sets the time-out period before shutdown to *xxx* seconds. The valid range is 0-315360000 (10 years), with a default of 30. If the timeout period is greater than 0, the **/f** parameter is implied. |
| /d `[p | u:]<XX>:<YY>` | Lists the reason for the system restart or shutdown. The supported parameter values are:<ul><li>**p** - Indicates that the restart or shutdown is planned.</li><li>**u** - Indicates that the reason is user-defined.<p>**NOTE**<br>If **p** or **u** aren't specified, the restart or shutdown is unplanned.</li><li>*xx* - Specifies the major reason number (a positive integer, less than 256).</li><li>*yy* Specifies the minor reason number (a positive integer, less than 65536).</li></ul> |
| /c `<comment>` | Enables you to comment in detail about the reason for the shutdown. You must first provide a reason by using the **/d** option and you must enclose your comments in quotation marks. You can use a maximum of 511 characters. |
| /? | Displays help at the command prompt, including a list of the major and minor reasons that are defined on your local computer. |

##### Remarks

- Users must be assigned the **Shut down the system** user right to shut down a local or remotely administered computer that is using the **shutdown** command.

- Users must be members of the **Administrators** group to annotate an unexpected shutdown of a local or remotely administered computer. If the target computer is joined to a domain, members of the **Domain Admins** group might be able to perform this procedure. For more information, see:

  - [Default local groups](/previous-versions/windows/it-pro/windows-server-2003/cc785098(v=ws.10))

  - [Default groups](/previous-versions/windows/it-pro/windows-server-2003/cc756898(v=ws.10))

- If you want to shut down more than one computer at a time, you can call **shutdown** for each computer by using a script, or you can use **shutdown** **/i** to display the **Remote Shutdown** box.

- If you specify major and minor reason codes, you must first define these reason codes on each computer where you plan to use the reasons. If the reason codes aren't defined on the target computer, Shutdown Event Tracker can't log the correct reason text.

- Remember to indicate that a shutdown is planned by using the **p** parameter. Not using the **p** parameter, indicates that the shutdown was unplanned.

  - Using the **p** parameter, along the reason code for an unplanned shutdown, causes the shutdown to fail.

  - Not using the **p** parameter, and only providing the reason code for an planned shutdown, also causes the shutdown to fail

### Examples

To force apps to close and to restart the local computer after a one-minute delay, with the reason *Application: Maintenance (Planned)* and the comment "Reconfiguring myapp.exe", type:

```
shutdown /r /t 60 /c "Reconfiguring myapp.exe" /f /d p:4:1
```

To restart the remote computer *myremoteserver* with the same parameters as the previous example, type:

```
shutdown /r /m \\myremoteserver /t 60 /c "Reconfiguring myapp.exe" /f /d p:4:1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


