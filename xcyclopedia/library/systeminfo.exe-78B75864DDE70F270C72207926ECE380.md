﻿---
title: systeminfo.exe | Displays system information
excerpt: What is systeminfo.exe?
---

# systeminfo.exe 

* File Path: `C:\Windows\SysWOW64\systeminfo.exe`
* Description: Displays system information

## Hashes

Type | Hash
-- | --
MD5 | `78B75864DDE70F270C72207926ECE380`
SHA1 | `1240BBE7589C2DDB4110C6506B659C3E3EBD3B12`
SHA256 | `81E6D6CB7A0F50F5BC331FD2AF48A90F2DCEE9FF7EF4F1ABE0B87866F7837985`
SHA384 | `D23B5DF4A1CF7EAB5BD70F7068D35AFBAD3DCFD3D91A2AAADC1D986EF112D2DBE9560E86C7498901F0ACED5644B5370C`
SHA512 | `71FFB6E94E2258D6B3A488423AF0CFDC48C15B61CCF02DF584C1C81047F8048F2C732988500FB8B429CD18754006BED637B6F2717431194ADD465096F74E672B`
SSDEEP | `1536:BHJiQveHyrh8h1j7F9QBXh2H5uZcrePiokhkGzc1UxRh4:3cx9Qtha5uZc6PiXJIUxT`
IMP | `C0D1DE37ED694783E9A9D18EB4AA4342`
PESHA1 | `5C8472C3BEF8987EC8F4B01D91E28246EA6033A4`
PE256 | `F532C8B8623A3BB8DDEDE630DC7AA5FCC98EA6A945338BC4173D5E48BED1C9AF`

## Runtime Data

### Usage (stdout):
```cmhg

SYSTEMINFO [/S system [/U username [/P [password]]]] [/FO format] [/NH]

Description:
    This tool displays operating system configuration information for
    a local or remote machine, including service pack levels.

Parameter List:
    /S      system           Specifies the remote system to connect to.

    /U      [domain\]user    Specifies the user context under which
                             the command should execute.

    /P      [password]       Specifies the password for the given
                             user context. Prompts for input if omitted.

    /FO     format           Specifies the format in which the output
                             is to be displayed.
                             Valid values: "TABLE", "LIST", "CSV".

    /NH                      Specifies that the "Column Header" should
                             not be displayed in the output.
                             Valid only for "TABLE" and "CSV" formats.

    /?                       Displays this help message.

Examples:
    SYSTEMINFO
    SYSTEMINFO /?
    SYSTEMINFO /S system
    SYSTEMINFO /S system /U user
    SYSTEMINFO /S system /U domain\user /P password /FO TABLE
    SYSTEMINFO /S system /FO LIST
    SYSTEMINFO /S system /FO CSV /NH

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "SYSTEMINFO /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sysinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/81e6d6cb7a0f50f5bc331fd2af48a90f2dcee9ff7ef4f1abe0b87866f7837985/detection/


## Possible Misuse

*The following table contains possible examples of `systeminfo.exe` being misused. While `systeminfo.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'systeminfo'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `description: Detects the use of stordiag.exe to execute schtasks.exe systeminfo.exe and fltmc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `- '\systeminfo.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- systeminfo.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- systeminfo`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\systeminfo.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `Description: Once executed, Stordiag.exe will execute schtasks.exe systeminfo.exe and fltmc.exe - if stordiag.exe is copied to a folder and an arbitrary executable is renamed to one of these names, stordiag.exe will execute it.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `- IOC: systeminfo.exe, fltmc.exe or schtasks.exe being executed outside of their normal path of c:\windows\system32\ or c:\windows\syswow64\`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [backdoordiplomacy](https://github.com/eset/malware-ioc/blob/master/backdoordiplomacy/README.adoc) | `* `systeminfo.oicp.net``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [backdoordiplomacy](https://github.com/eset/malware-ioc/blob/master/backdoordiplomacy/README.adoc) | `* `systeminfo.myftp.name``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [backdoordiplomacy](https://github.com/eset/malware-ioc/blob/master/backdoordiplomacy/README.adoc) | `* `systeminfo.cleansite.info``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "An adversary may attempt to get detailed information about the operating system and hardware, including version, patches, hotfixes, service packs, and architecture. Adversaries may use the information from [System Information Discovery](https://attack.mitre.org/techniques/T1082) during automated discovery to shape follow-on behaviors, including whether or not the adversary fully infects the target and/or attempts specific actions.\n\n### Windows\n\nExample commands and utilities that obtain this information include <code>ver</code>, [Systeminfo](https://attack.mitre.org/software/S0096), and <code>dir</code> within [cmd](https://attack.mitre.org/software/S0106) for identifying information based on present files and directories.\n\n### Mac\n\nOn Mac, the <code>systemsetup</code> command gives a detailed breakdown of the system, but it requires administrative privileges. Additionally, the <code>system_profiler</code> gives a very detailed breakdown of configurations, firewall rules, mounted volumes, hardware, and many other things without needing elevated permissions.\n\n### AWS\n\nIn Amazon Web Services (AWS), the Application Discovery Service may be used by an adversary to identify servers, virtual machines, software, and software dependencies running.(Citation: Amazon System Discovery)\n\n### GCP\n\nOn Google Cloud Platform (GCP) <code>GET /v1beta1/{parent=organizations/*}/assets</code> or <code>POST /v1beta1/{parent=organizations/*}/assets:runDiscovery</code> may be used to list an organizations cloud assets, or perform asset discovery on a cloud environment.(Citation: Google Command Center Dashboard)\n\n### Azure\n\nIn Azure, the API request <code>GET https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Compute/virtualMachines/{vmName}?api-version=2019-03-01</code> may be used to retrieve information about the model or instance view of a virtual machine.(Citation: Microsoft Virutal Machine API)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries may check for the presence of a virtual machine environment (VME) or sandbox to avoid potential detection of tools and activities. If the adversary detects a VME, they may alter their malware to conceal the core functions of the implant or disengage from the victim. They may also search for VME artifacts before dropping secondary or additional payloads. Adversaries may use the information from learned from [Virtualization/Sandbox Evasion](https://attack.mitre.org/techniques/T1497) during automated discovery to shape follow-on behaviors.\n\nAdversaries may use several methods including [Security Software Discovery](https://attack.mitre.org/techniques/T1063) to accomplish [Virtualization/Sandbox Evasion](https://attack.mitre.org/techniques/T1497) by searching for security monitoring tools (e.g., Sysinternals, Wireshark, etc.) to help determine if it is an analysis environment. Additional methods include use of sleep timers or loops within malware code to avoid operating within a temporary sandboxes. (Citation: Unit 42 Pirpi July 2015)\n\n###Virtual Machine Environment Artifacts Discovery###\n\nAdversaries may use utilities such as [Windows Management Instrumentation](https://attack.mitre.org/techniques/T1047), [PowerShell](https://attack.mitre.org/techniques/T1086), [Systeminfo](https://attack.mitre.org/software/S0096), and the [Query Registry](https://attack.mitre.org/techniques/T1012) to obtain system information and search for VME artifacts. Adversaries may search for VME artifacts in memory, processes, file system, and/or the Registry. Adversaries may use [Scripting](https://attack.mitre.org/techniques/T1064) to combine these checks into one script and then have the program exit if it determines the system to be a virtual environment. Also, in applications like VMWare, adversaries can use a special I/O port to send commands and receive output. Adversaries may also check the drive size. For example, this can be done using the Win32 DeviceIOControl function. \n\nExample VME Artifacts in the Registry(Citation: McAfee Virtual Jan 2017)\n\n* <code>HKLM\\SOFTWARE\\Oracle\\VirtualBox Guest Additions</code>\n* <code>HKLM\\HARDWARE\\Description\\System\\”SystemBiosVersion”;”VMWARE”</code>\n* <code>HKLM\\HARDWARE\\ACPI\\DSDT\\BOX_</code>\n\nExample VME files and DLLs on the system(Citation: McAfee Virtual Jan 2017)\n\n* <code>WINDOWS\\system32\\drivers\\vmmouse.sys</code> \n* <code>WINDOWS\\system32\\vboxhook.dll</code>\n* <code>Windows\\system32\\vboxdisp.dll</code>\n\nCommon checks may enumerate services running that are unique to these applications, installed programs on the system, manufacturer/product fields for strings relating to virtual machine applications, and VME-specific hardware/processor instructions.(Citation: McAfee Virtual Jan 2017)\n\n###User Activity Discovery###\n\nAdversaries may search for user activity on the host (e.g., browser history, cache, bookmarks, number of files in the home directories, etc.) for reassurance of an authentic environment. They might detect this type of information via user interaction and digital signatures. They may have malware check the speed and frequency of mouse clicks to determine if it’s a sandboxed environment.(Citation: Sans Virtual Jan 2016) Other methods may rely on specific user interaction with the system before the malicious code is activated. Examples include waiting for a document to close before activating a macro (Citation: Unit 42 Sofacy Nov 2018) and waiting for a user to double click on an embedded image to activate (Citation: FireEye FIN7 April 2017).\n\n###Virtual Hardware Fingerprinting Discovery###\n\nAdversaries may check the fan and temperature of the system to gather evidence that can be indicative a virtual environment. An adversary may perform a CPU check using a WMI query <code>$q = “Select * from Win32_Fan” Get-WmiObject -Query $q</code>. If the results of the WMI query return more than zero elements, this might tell them that the machine is a physical one. (Citation: Unit 42 OilRig Sept 2018)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `"description": "An adversary may attempt to get detailed information about the operating system and hardware, including version, patches, hotfixes, service packs, and architecture.\n\n### Windows\n\nExample commands and utilities that obtain this information include <code>ver<\/code>, [Systeminfo](https:\/\/attack.mitre.org\/software\/S0096), and <code>dir<\/code> within [cmd](https:\/\/attack.mitre.org\/software\/S0106) for identifying information based on present files and directories.\n\n### Mac\n\nOn Mac, the <code>systemsetup<\/code> command gives a detailed breakdown of the system, but it requires administrative privileges. Additionally, the <code>system_profiler<\/code> gives a very detailed breakdown of configurations, firewall rules, mounted volumes, hardware, and many other things without needing elevated permissions.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "An adversary may attempt to get detailed information about the operating system and hardware, including version, patches, hotfixes, service packs, and architecture.\n\n===Windows===\n\nExample commands and utilities that obtain this information include <code>ver<\/code>, Systeminfo, and <code>dir<\/code> within cmd for identifying information based on present files and directories.\n\n===Mac===\n\nOn Mac, the <code>systemsetup<\/code> command gives a detailed breakdown of the system, but it requires administrative privileges. Additionally, the <code>system_profiler<\/code> gives a very detailed breakdown of configurations, firewall rules, mounted volumes, hardware, and many other things without needing elevated permissions.\n\nDetection: System and network discovery techniques normally occur throughout an operation as an adversary learns the environment. Data and events should not be viewed in isolation, but as part of a chain of behavior that could lead to other activities based on the information obtained.\n\nMonitor processes and command-line arguments for actions that could be taken to gather system and network information. Remote access tools with built-in features may interact directly with the Windows API to gather information. Information may also be acquired through Windows system management tools such as Windows Management Instrumentation and PowerShell.\n\nPlatforms: Linux, macOS, Windows\n\nData Sources: Process command-line parameters, Process monitoring\n\nPermissions Required: User",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1082.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1082/T1082.md) | Tools such as [Systeminfo](https://attack.mitre.org/software/S0096) can be used to gather detailed system information. A breakdown of system data can also be gathered through the macOS <code>systemsetup</code> command, but it requires administrative privileges. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1082.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1082/T1082.md) | systeminfo | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | $a1 = "& SYSTEMINFO) ELSE EXIT" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s2 = "/c systeminfo >> %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s1 = "cmd.exe /c systeminfo " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keylogger_cn.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keylogger_cn.yar) | $s1 = "\\cmd.exe /c \"systeminfo.exe >> " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $s2 = "cmd /c systeminfo >%s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sednit_delphidownloader.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sednit_delphidownloader.yar) | $s5 = "53595354454D494E464F2026205441534B4C495354" ascii /* hex encoded string 'SYSTEMINFO & TASKLIST' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_crimson_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_crimson_rat.yar) | $x3 = "cmd.exe/c systeminfo >> 1.txt" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $a5 = "SystemInfo" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_recon_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_recon_indicators.yar) | $s6 = "systeminfo" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $ = "systeminfo" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## systeminfo

Displays detailed configuration information about a computer and its operating system, including operating system configuration, security information, product ID, and hardware properties (such as RAM, disk space, and network cards).

### Syntax

```
systeminfo [/s <computer> [/u <domain>\<username> [/p <password>]]] [/fo {TABLE | LIST | CSV}] [/nh]
```

#### Parameters

| Parameter | Description |
|--|--|
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain>\<username>` | Runs the command with the account permissions of the specified user account. If **/u** is not specified, this command uses the permissions of the user who is currently logged on to the computer that is issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /fo `<format>` | Specifies the output format with one of the following values:<ul><li>**TABLE** - Displays output in a table.</li><li>**LIST** - Displays output in a list.</li><li>**CSV** - Displays output in comma-separated values (.csv) format.</li></ul> |
| /nh | Suppresses column headers in the output. Valid when the **/fo** parameter is set to TABLE or CSV. |
| /? | Displays help at the command prompt. |

### Examples

To view configuration information for a computer named *Srvmain*, type:

```
systeminfo /s srvmain
```

To remotely view configuration information for a computer named *Srvmain2* that is located on the *Maindom* domain, type:

```
systeminfo /s srvmain2 /u maindom\hiropln
```

To remotely view configuration information (in list format) for a computer named *Srvmain2* that is located on the *Maindom* domain, type:

```
systeminfo /s srvmain2 /u maindom\hiropln /p p@ssW23 /fo list
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


