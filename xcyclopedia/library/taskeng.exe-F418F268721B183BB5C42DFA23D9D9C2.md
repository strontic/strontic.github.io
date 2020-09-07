---
title: taskeng.exe | Task Scheduler Engine
---

# taskeng.exe 

* File Path: `C:\windows\SysWOW64\taskeng.exe`
* Description: Task Scheduler Engine

## Hashes

Type | Hash
-- | --
MD5 | `F418F268721B183BB5C42DFA23D9D9C2`
SHA1 | `BA63C551843CC8053B6B77DFF4FCE8332F5E9546`
SHA256 | `9137B804681B06E87DFD6F548F9CECFDA0DA5AA17CBE0E673032EC465168C9F1`
SHA384 | `F8975E3C3E1C9DA4F658A19FF7C7B624FA6225AE898895243458D662FFB7C74FBE020475D885851949F372B98B86185C`
SHA512 | `55584BFBFD24A190481059A07D980A7861FF140EB5E78551E88C22D69B229AF8E9AA1EB2BD94630C57703B00C0B767601721D3C0894183ABE8699AED9ABD45D1`
SSDEEP | `6144:gqbWy0mX3WR/qeGR1ItEXK9RjUt1ucVGF6IwNpmOo55:gqCy0mX36GLItE69mt1L4pOmOo55`

## Signature

* Status: The file C:\windows\SysWOW64\taskeng.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: taskeng.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `taskeng.exe` being misused. While `taskeng.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `            - 'taskeng.exe*' # atexec on win7 (parent is "taskeng.exe {AFA79333-694C-4BEE-910E-E57D9A3518F6} S-1-5-18:NT AUTHORITY\System:Service:")` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `					"description": "Utilities such as at and schtasks, along with the Windows Task Scheduler, can be used to schedule programs or scripts to be executed at a date and time. A task can also be scheduled on a remote system, provided the proper authentication is met to use RPC and file and printer sharing is turned on. Scheduling a task on a remote system typically required being a member of the Administrators group on the the remote system. (Citation: TechNet Task Scheduler Security)\n\nAn adversary may use task scheduling to execute programs at system startup or on a scheduled basis for persistence, to conduct remote Execution as part of Lateral Movement, to gain SYSTEM privileges, or to run a process under the context of a specified account.\n\nDetection: Monitor scheduled task creation from common utilities using command-line invocation. Legitimate scheduled tasks may be created during installation of new software or through system administration functions. Monitor process execution from the <code>svchost.exe<\/code> in Windows 10 and the Windows Task Scheduler <code>taskeng.exe<\/code> for older versions of Windows. (Citation: Twitter Leoloobeek Scheduled Task) If scheduled tasks are not used for persistence, then the adversary is likely to remove the task when the action is complete. Monitor Windows Task Scheduler stores in <code>%systemroot%\\System32\\Tasks<\/code> for change entries related to scheduled tasks that do not correlate with known software, patch cycles, etc. Data and events should not be viewed in isolation, but as part of a chain of behavior that could lead to other activities, such as network connections made for Command and Control, learning details about the environment through Discovery, and Lateral Movement.\n\nConfigure event logging for scheduled task creation and changes by enabling the \"Microsoft-Windows-TaskScheduler\/Operational\" setting within the event logging service. (Citation: TechNet Forum Scheduled Task Operational Setting) Several events will then be logged on scheduled task activity, including: (Citation: TechNet Scheduled Task Events)\n\n*Event ID 106 - Scheduled task registered\n*Event ID 140 - Scheduled task updated\n*Event ID 141 - Scheduled task removed\n\nTools such as Sysinternals Autoruns may also be used to detect system changes that could be attempts at persistence, including listing current scheduled tasks. (Citation: TechNet Autoruns) Look for changes to tasks that do not correlate with known software, patch cycles, etc. Suspicious program execution through scheduled tasks may show up as outlier processes that have not been seen before when compared against historical data.\n\nMonitor processes and command-line arguments for actions that could be taken to create tasks. Remote access tools with built-in features may interact directly with the Windows API to perform these functions outside of typical system utilities. Tasks may also be created through Windows system management tools such as Windows Management Instrumentation and PowerShell, so additional logging may need to be configured to gather the appropriate data.\n\nPlatforms: Windows\n\nData Sources: File monitoring, Process command-line parameters, Process monitoring, Windows event logs\n\nEffective Permissions: Administrator, SYSTEM, User\n\nPermissions Required: Administrator, SYSTEM, User\n\nRemote Support: Yes\n\nContributors: Travis Smith, Tripwire, Leo Loobeek, @leoloobeek, Alain Homewood, Insomnia Security",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


