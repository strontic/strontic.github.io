---
title: schtasks.exe | Task Scheduler Configuration Tool
excerpt: What is schtasks.exe?
---

# schtasks.exe 

* File Path: `C:\Windows\system32\schtasks.exe`
* Description: Task Scheduler Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `EEB7A2162E4DBE32B56BEB84658483AE`
SHA1 | `58ECB25B08A24660E71CE411C2C1D8709572ABEC`
SHA256 | `A9A4FD9C1BB7C5CF8F77F761CAE60F4AC4AFB8DAEEBB46B3AD6983D5E599CDC1`
SHA384 | `635D3E950548BD61C8918B122CC1D2E30333FEA38FE82C12F4CAA1CA0F91901C8FC004B83C83480EA00706217D66CAC9`
SHA512 | `2901FF71D1F027DF4150C81B93F48E2BD3FA1F33FBC24977826945FBF570C580B6F338CC0751C3E5DF62D76789BB499847366E1F74DD15A0F97E225B80593E42`
SSDEEP | `3072:ZLEWdGDTw9q+nboxZiF9l2qeqg266jY1wPcspJNmtwHbVvUB9QMEZaS:lpUw91cZgf2VqgKPbpJNmtGUjQME`

## Runtime Data

### Usage (stdout):
```cmhg

SCHTASKS /parameter [arguments]

Description:
    Enables an administrator to create, delete, query, change, run and
    end scheduled tasks on a local or remote system. 

Parameter List:
    /Create         Creates a new scheduled task.

    /Delete         Deletes the scheduled task(s).

    /Query          Displays all scheduled tasks.

    /Change         Changes the properties of scheduled task.

    /Run            Runs the scheduled task on demand.

    /End            Stops the currently running scheduled task.

    /ShowSid        Shows the security identifier corresponding to a scheduled task name.

    /?              Displays this help message.

Examples:
    SCHTASKS 
    SCHTASKS /?
    SCHTASKS /Run /?
    SCHTASKS /End /?
    SCHTASKS /Create /?
    SCHTASKS /Delete /?
    SCHTASKS /Query  /?
    SCHTASKS /Change /?
    SCHTASKS /ShowSid /?

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '-help'.
Type "SCHTASKS /QUERY /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sctasks.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `schtasks.exe` being misused. While `schtasks.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'schtasks* /create *AppData'  # Scheduled task creation pointing to AppData` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rare_schtasks_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_rare_schtasks_creations.yml) | `title: Rare Schtasks Creations` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_slingshot.yml) | `Image\|endswith: '\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- schtasks.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `title: Default PowerSploit and Empire Schtasks Persistence` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- https://github.com/EmpireProject/Empire/blob/master/lib/modules/powershell/persistence/userland/schtasks.py` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- https://github.com/EmpireProject/Empire/blob/master/lib/modules/powershell/persistence/elevated/schtasks.py` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONLOGON*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *DAILY*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *ONIDLE*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*schtasks*/Create*/SC *Updater*/TN *Updater*/TR *powershell*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_schtask_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_schtask_creation.yml) | `Image: '*\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_win10_sched_task_0day.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_win10_sched_task_0day.yml) | `Image\|endswith: '\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\schtasks.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Schtasks.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Schtasks.yml) | `Name: Schtasks.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Schtasks.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Schtasks.yml) | `- Command: schtasks /create /sc minute /mo 1 /tn "Reverse shell" /tr c:\some\directory\revshell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Schtasks.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Schtasks.yml) | `- Path: c:\windows\system32\schtasks.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Schtasks.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Schtasks.yml) | `- Path: c:\windows\syswow64\schtasks.exe` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "Utilities such as [at](https://attack.mitre.org/software/S0110) and [schtasks](https://attack.mitre.org/software/S0111), along with the Windows Task Scheduler, can be used to schedule programs or scripts to be executed at a date and time. A task can also be scheduled on a remote system, provided the proper authentication is met to use RPC and file and printer sharing is turned on. Scheduling a task on a remote system typically required being a member of the Administrators group on the the remote system. (Citation: TechNet Task Scheduler Security)\n\nAn adversary may use task scheduling to execute programs at system startup or on a scheduled basis for persistence, to conduct remote Execution as part of Lateral Movement, to gain SYSTEM privileges, or to run a process under the context of a specified account.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Utilities such as [at](https://attack.mitre.org/software/S0110) and [schtasks](https://attack.mitre.org/software/S0111), along with the Windows Task Scheduler, can be used to schedule programs or scripts to be executed at a date and time. A task can also be scheduled on a remote system, provided the proper authentication is met to use RPC and file and printer sharing is turned on. Scheduling a task on a remote system typically required being a member of the Administrators group on the remote system. (Citation: TechNet Task Scheduler Security)\n\nAn adversary may use task scheduling to execute programs at system startup or on a scheduled basis for persistence, to conduct remote Execution as part of Lateral Movement, to gain SYSTEM privileges, or to run a process under the context of a specified account.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Utilities such as at and schtasks, along with the Windows Task Scheduler, can be used to schedule programs or scripts to be executed at a date and time. A task can also be scheduled on a remote system, provided the proper authentication is met to use RPC and file and printer sharing is turned on. Scheduling a task on a remote system typically required being a member of the Administrators group on the the remote system. (Citation: TechNet Task Scheduler Security)\n\nAn adversary may use task scheduling to execute programs at system startup or on a scheduled basis for persistence, to conduct remote Execution as part of Lateral Movement, to gain SYSTEM privileges, or to run a process under the context of a specified account.\n\nDetection: Monitor scheduled task creation from common utilities using command-line invocation. Legitimate scheduled tasks may be created during installation of new software or through system administration functions. Monitor process execution from the <code>svchost.exe<\/code> in Windows 10 and the Windows Task Scheduler <code>taskeng.exe<\/code> for older versions of Windows. (Citation: Twitter Leoloobeek Scheduled Task) If scheduled tasks are not used for persistence, then the adversary is likely to remove the task when the action is complete. Monitor Windows Task Scheduler stores in <code>%systemroot%\\System32\\Tasks<\/code> for change entries related to scheduled tasks that do not correlate with known software, patch cycles, etc. Data and events should not be viewed in isolation, but as part of a chain of behavior that could lead to other activities, such as network connections made for Command and Control, learning details about the environment through Discovery, and Lateral Movement.\n\nConfigure event logging for scheduled task creation and changes by enabling the \"Microsoft-Windows-TaskScheduler\/Operational\" setting within the event logging service. (Citation: TechNet Forum Scheduled Task Operational Setting) Several events will then be logged on scheduled task activity, including: (Citation: TechNet Scheduled Task Events)\n\n*Event ID 106 - Scheduled task registered\n*Event ID 140 - Scheduled task updated\n*Event ID 141 - Scheduled task removed\n\nTools such as Sysinternals Autoruns may also be used to detect system changes that could be attempts at persistence, including listing current scheduled tasks. (Citation: TechNet Autoruns) Look for changes to tasks that do not correlate with known software, patch cycles, etc. Suspicious program execution through scheduled tasks may show up as outlier processes that have not been seen before when compared against historical data.\n\nMonitor processes and command-line arguments for actions that could be taken to create tasks. Remote access tools with built-in features may interact directly with the Windows API to perform these functions outside of typical system utilities. Tasks may also be created through Windows system management tools such as Windows Management Instrumentation and PowerShell, so additional logging may need to be configured to gather the appropriate data.\n\nPlatforms: Windows\n\nData Sources: File monitoring, Process command-line parameters, Process monitoring, Windows event logs\n\nEffective Permissions: Administrator, SYSTEM, User\n\nPermissions Required: Administrator, SYSTEM, User\n\nRemote Support: Yes\n\nContributors: Travis Smith, Tripwire, Leo Loobeek, @leoloobeek, Alain Homewood, Insomnia Security",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | Find all Schtasks: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") schtasks.exe` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") schtasks.exe \| stats values(CommandLine)` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") schtasks.exe \| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") schtasks.exe \| stats values(CommandLine) by host` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3") source="WinEventLog:Security"  schtasks.exe \| stats values(Process_Command_Line) by  Creator_Process_Name` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv2") source="WinEventLog:Security"  schtasks.exe \| stats values(Process_Command_Line) by ComputerName` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe \| stats values(Image) by ParentImage` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe ParentImage=*\\powershell.exe\| stats values(Image) by ParentImage ParentCommandLine` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | ### Begin Tuning Schtasks Search | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*powershell.exe*\| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine!="*\Office Automatic Updates*" CommandLine!="*\Office ClickToRun*" \| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*Create* ParentImage!=*\\OfficeClicktoRun.exe \| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe \| table Computer, User, CommandLine, _time` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*Create* ParentImage!=*\\OfficeClicktoRun.exe \| table Computer, User, CommandLine, _time` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Creating W32Time similar named service using schtasks [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Creating W32Time similar named service using schtasks [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | <blockquote>Adversaries may attempt to manipulate the name of a task or service to make it appear legitimate or benign. Tasks/services executed by the Task Scheduler or systemd will typically be given a name and/or description.(Citation: TechNet Schtasks)(Citation: Systemd Service Units) Windows services will have a service name as well as a display name. Many benign tasks and services exist that have commonly associated names. Adversaries may give tasks or services names that are similar or identical to those of legitimate ones. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | - [Atomic Test #1 - Creating W32Time similar named service using schtasks](#atomic-test-1---creating-w32time-similar-named-service-using-schtasks) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | ## Atomic Test #1 - Creating W32Time similar named service using schtasks | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | Creating W32Time similar named service (win32times) using schtasks just like threat actor dubbed "Operation Wocao" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | schtasks /create /ru system /sc daily /tr "cmd /c powershell.exe -ep bypass -file c:\T1036.004_NonExistingScript.ps1" /tn win32times /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | schtasks /query /tn win32times | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | schtasks /tn win32times /delete /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | Note: The <code>at.exe</code> command line utility has been deprecated in current versions of Windows in favor of <code>schtasks</code>.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | <blockquote>Adversaries may abuse the Windows Task Scheduler to perform task scheduling for initial or recurring execution of malicious code. There are multiple ways to access the Task Scheduler in Windows. The <code>schtasks</code> can be run directly on the command line, or the Task Scheduler can be opened through the GUI within the Administrator Tools section of the Control Panel. In some cases, adversaries have used a .NET wrapper for the Windows Task Scheduler, and alternatively, adversaries have used the Windows netapi32 library to create a scheduled task. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | The deprecated [at](https://attack.mitre.org/software/S0110) utility could also be abused by adversaries (ex: [At (Windows)](https://attack.mitre.org/techniques/T1053/002)), though <code>at.exe</code> can not access tasks created with <code>schtasks</code> or the Control Panel. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnLogon" /sc onlogon /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnStartup" /sc onstart /ru system /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /delete /tn "T1053_005_OnLogon" /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /delete /tn "T1053_005_OnStartup" /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | SCHTASKS /Create /SC ONCE /TN spawn /TR #{task_command} /ST #{time} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | SCHTASKS /Delete /TN spawn /F >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | SCHTASKS /Create /S #{target} /RU #{user_name} /RP #{password} /TN "Atomic task" /TR "#{task_command}" /SC daily /ST #{time} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | SCHTASKS /Delete /S #{target} /RU #{user_name} /RP #{password} /TN "Atomic task" /F >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt34.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt34.yar) | $x6 = "schtasks /create /F /ru SYSTEM /sc minute /mo 1 /tn" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7_backdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7_backdoor.yar) | $x3 = "schtasks /Create /f /tn \"GoogleUpdateTaskMachineSystem\" /tr \"wscript.exe" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7_backdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7_backdoor.yar) | $x4 = "schtasks /Delete /F /TN \"\"GoogleUpdateTaskMachineCore" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7_backdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7_backdoor.yar) | $x5 = "schtasks /Delete /F /TN \"GoogleUpdateTaskMachineCore" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | $s3 = "C:\\Windows\\System32\\cmd.exe /C schtasks /create /tn \"\\Microsoft\\Windows\\PLA\\System\\Microsoft Windows\" /tr " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | $s4 = "C:\\Windows\\System32\\cmd.exe /C schtasks /create /tn \"Microsoft Windows\" /tr " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_khrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_khrat.yar) | $x1 = "CreateObject(\"WScript.Shell\").Run \"schtasks /create /sc MINUTE /tn" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x4 = "$cmdSchedule = 'schtasks /create /tn \"ProxyServerUpdater\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s6 = "schtasks /create /F /sc minute /mo " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $two1 = "& SchTasks /Delete /F /TN " ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $two3 = "vbs = \"cmd.exe /c SchTasks" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x2 = "schtasks /create /F /ru SYSTEM /sc minute /mo 10 /tn" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $x1 = "cmd /c schtasks /query /tn TimeUpdate > NUL 2>&1" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $x2 = "schtasks /create /sc minute /mo 0002 /tn TimeUpdate /tr" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rancor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rancor.yar) | $x3 = "CreateObject(\"Wscript.Shell\").Run \"schtasks /create" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_badrabbit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_badrabbit.yar) | $x1 = "schtasks /Create /SC ONCE /TN viserion_%u /RU SYSTEM /TR \"%ws\" /ST" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_badrabbit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_badrabbit.yar) | $x2 = "schtasks /Create /RU SYSTEM /SC ONSTART /TN rhaegal /TR \"%ws /C Start \\\"\\\" \\\"%wsdispci.exe\\\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $x2 = "schtasks /create /sc minute /mo 1 /tn Server /tr " fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | $x2 = "schtasks /Create /SC HOURLY /MO %d /ST 00:%02d:00 /TN \"%s\" /TR \"%s\" /RU \"SYSTEM\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $s5 = "schtasks %ws/Create /SC once /TN \"\" /TR \"%ws\" /ST %02d:%02d" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_recon_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_recon_indicators.yar) | $s15 = "schtasks.exe /create " ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rottenpotato.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rottenpotato.yar) | $x3 = "/C schtasks.exe /Create /TN omg /TR" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s0 = "objShell.Run \"schtasks /change /TN wDw00t /disable\",,True" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s3 = "objShell.Run \"schtasks /run /TN wDw00t\",,True" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s6 = "a.WriteLine (\"schtasks /delete /f /TN wDw00t\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s11 = "Set objExecObject = objShell.Exec(\"cmd /c schtasks /query /XML /TN wDw00t\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s12 = "objShell.Run \"schtasks /create /TN wDw00t /sc monthly /tr \"\"\"+biatchFile+\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## schtasks commands

Schedules commands and programs to run periodically or at a specific time, adds and removes tasks from the schedule, starts and stops tasks on demand, and displays and changes scheduled tasks.

> [!NOTE]
> The **schtasks.exe** tool performs the same operations as **Scheduled Tasks** in **Control Panel**. You can use these tools together and interchangeably.

### Required permissions

- To schedule, view, and change all tasks on the local computer, you must be a member of the Administrators group.

- To schedule, view, and change all tasks on the remote computer, you must be a member of the Administrators group on the remote computer, or you must use the **/u** parameter to provide the credentials of an Administrator of the remote computer.

- You can use the **/u** parameter in a **/create** or **/change** operation if the local and remote computers are in the same domain, or if the local computer is in a domain that the remote computer domain trusts. Otherwise, the remote computer can't authenticate the user account specified, and it can't verify that the account is a member of the Administrators group.

- The task you plan to run must have the appropriate permission; these permissions vary by task. By default, tasks run with the permissions of the current user of the local computer, or with the permissions of the user specified by the **/u** parameter, if one is included. o run a task with permissions of a different user account or with system permissions, use the **/ru** parameter.

### Syntax

```
schtasks change
schtasks create
schtasks delete
schtasks end
schtasks query
schtasks run
```

#### Parameters

| Parameter | Description |
|--|--|
| [schtasks change](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-change.md) | Changes one or more of the following properties of a task:<ul><li>The program that the task runs (/tr)</li><li>The user account under which the task runs (/ru)</li><li>The password for the user account (/rp)</li><li>Adds the interactive-only property to the task (/it)</li></ul> |
| [schtasks create](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-create.md) | Schedules a new task.|
| [schtasks delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-delete.md) | Deletes a scheduled task. |
| [schtasks end](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-end.md) | Stops a program started by a task. |
| [schtasks query](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-query.md) | Displays tasks scheduled to run on the computer. |
| [schtasks run](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks-run.md) | Starts a scheduled task immediately. The **run** operation ignores the schedule, but uses the program file location, user account, and password saved in the task to run the task immediately. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


