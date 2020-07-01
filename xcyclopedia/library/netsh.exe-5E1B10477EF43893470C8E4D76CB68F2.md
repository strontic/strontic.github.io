---
title: netsh.exe | Network Command Shell
---

# netsh.exe 

* File Path: `C:\windows\system32\netsh.exe`
* Description: Network Command Shell
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5E1B10477EF43893470C8E4D76CB68F2`
SHA1 | `74FC4C5A24F6FDE2D8492A58624094065C8F4ACA`
SHA256 | `71131C1535887FAC329EDCA024DBED4C6A2BDC4F9E91CE2443EE359016521836`
SHA384 | `BF376E2CF4948E1CD1F1189F583D70923F9D03F4E853F2FECCC7A4C913B3DF052C5466318E272E23DECD21550B6B9B40`
SHA512 | `FDB7C3C55FE4165FC8D1F9DA91A9C48DB7ED940AB59BFB9E1F1DEECBF7317BDC69DF80E4613A7C211F8DB422B95CC3EDAB4202C01F5629C43E030CA535B97AF2`
SSDEEP | `1536:/FVbOdPjb9ZuPvDstdCkEnQrlVETxwzaMEjaWwIv/:dw9hLJPlVEtw2xn3`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\netsh.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: netsh.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `netsh.exe` being misused. While `netsh.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `            - 'netsh advfirewall firewall add rule name=powershell dir=in'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - netsh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `title: Netsh RDP Port Opening` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `description: Detects netsh commands that opens the port 3389 used for RDP, used in Sarwent Malware` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `            - netsh` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add.yml) | `title: Netsh Port or Application Allowed` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add.yml) | `            - '*netsh*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `title: Netsh Program Allowed with Suspcious Location` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `description: Detects Netsh commands that allows a suspcious application location on Windows Firewall` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `            - 'netsh'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `            - netsh` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `title: Capture a Network Trace with netsh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `description: Detects capture a network trace via netsh.exe trace functionality` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `            - netsh` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `    - Legitimate administrator or user uses netsh.exe trace functionality for legitimate reason` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `title: Netsh Port Forwarding` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `description: Detects netsh commands that configure a port forwarding` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `            - netsh interface portproxy add v4tov4 *` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `title: Netsh RDP Port Forwarding` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `description: Detects netsh commands that configure a port forwarding of port 3389 used for RDP` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `            - netsh i* p*=3389 c*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `title: Harvesting of Wifi Credentials Using netsh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `description: Detect the harvesting of wifi credentials using netsh.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `            - 'netsh wlan s* p* k*=clear'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `    - Legitimate administrator or user uses netsh.exe wlan functionality for legitimate reason` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `            - 'netsh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `            - '\netsh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `title: Firewall Disabled via Netsh` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `description: Detects netsh commands that turns off the Windows firewall` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `            - netsh firewall set opmode mode=disable` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `            - netsh advfirewall set * state off` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `title: Suspicious Netsh DLL Persistence` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `description: Detects persitence via netsh helper` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `        Image\|endswith: '\netsh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `            - netsh advfirewall firewall *\AppData\\*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `Name: Netsh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `          netsh.exe trace start capture=yes filemode=append persistent=yes tracefile=\\server\share\file.etl IPv4.Address=!(<IPofRemoteFileShare>)` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `          netsh.exe trace show status` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `  - Command: netsh.exe add helper C:\Path\file.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `    Description: Load (execute) NetSh.exe helper DLL file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `  - Command: netsh interface portproxy add v4tov4 listenport=8080 listenaddress=0.0.0.0 connectport=8000 connectaddress=192.168.1.1` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `Name: Netsh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `Description: Netsh is a Windows tool used to manipulate network interface settings.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `  - Command: netsh.exe add helper C:\Users\User\file.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `    Description: Use Netsh in order to execute a .dll file and also gain persistence, every time the netsh command is called` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `  - Path: C:\WINDOWS\System32\Netsh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `  - Path: C:\WINDOWS\SysWOW64\Netsh.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `  - IOC: Netsh initiating a network connection` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `                "description": "Adversaries may attempt to get a listing of security software, configurations, defensive tools, and sensors that are installed on the system. This may include things such as local firewall rules and anti-virus. Adversaries may use the information from [Security Software Discovery](https://attack.mitre.org/techniques/T1063) during automated discovery to shape follow-on behaviors, including whether or not the adversary fully infects the target and/or attempts specific actions.\n\n\n### Windows\n\nExample commands that can be used to obtain security software information are [netsh](https://attack.mitre.org/software/S0108), <code>reg query</code> with [Reg](https://attack.mitre.org/software/S0075), <code>dir</code> with [cmd](https://attack.mitre.org/software/S0106), and [Tasklist](https://attack.mitre.org/software/S0057), but other indicators of discovery behavior may be more specific to the type of software or security system the adversary is looking for.\n\n### Mac\n\nIt's becoming more common to see macOS malware perform checks for LittleSnitch and KnockKnock software.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Launch Daemon](../../T1543.004/T1543.004.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Impair Defenses [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Path Interception by Unquoted Path [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [InstallUtil](../../T1218.004/T1218.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Local Account](../../T1136.001/T1136.001.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Group Policy Modification [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Silver Ticket [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| Standard Encoding [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Path Interception [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Hide Artifacts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Two-Factor Authentication Interception [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| [Web Protocols](../../T1071.001/T1071.001.md) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | netsh interface show | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Enumerates Windows Firewall Rules using netsh. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn netsh.exe to list firewall rules. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | netsh advfirewall firewall show rule name=all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | Upon execution there will be a new proxy entry in netsh | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy show all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy add v4tov4 listenport=#{listenport} connectport=#{connectport} connectaddress=#{connectaddress} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy delete v4tov4 listenport=#{listenport} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | Example commands that can be used to obtain security software information are [netsh](https://attack.mitre.org/software/S0108), <code>reg query</code> with [Reg](https://attack.mitre.org/software/S0075), <code>dir</code> with [cmd](https://attack.mitre.org/software/S0106), and [Tasklist](https://attack.mitre.org/software/S0057), but other indicators of discovery behavior may be more specific to the type of software or security system the adversary is looking for. It is becoming more common to see macOS malware perform checks for LittleSnitch and KnockKnock software.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | netsh.exe advfirewall  show allprofiles | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | # T1546.007 - Netsh Helper DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | <blockquote>Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs. Netsh.exe (also referred to as Netshell) is a command-line scripting utility used to interact with the network configuration of a system. It contains functionality to add helper DLLs for extending functionality of the utility. (Citation: TechNet Netsh) The paths to registered netsh.exe helper DLLs are entered into the Windows Registry at <code>HKLM\SOFTWARE\Microsoft\Netsh</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | Adversaries can use netsh.exe helper DLLs to trigger execution of arbitrary code in a persistent manner. This execution would take place anytime netsh.exe is executed, which could happen automatically, with another persistence technique, or if other software (ex: VPN) is present on the system that executes netsh.exe as part of its normal functionality. (Citation: Github Netsh Helper CS Beacon)(Citation: Demaske Netsh Persistence)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | - [Atomic Test #1 - Netsh Helper DLL Registration](#atomic-test-1---netsh-helper-dll-registration) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | ## Atomic Test #1 - Netsh Helper DLL Registration | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | Netsh interacts with other operating system components using dynamic-link library (DLL) files | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | netsh.exe add helper #{helper_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall set currentprofile state off | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall set currentprofile state on | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall set rule group="remote desktop" new enable=Yes | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall set rule group="file and printer sharing" new enable=Yes | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall reset | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall add rule name="atomic testing" action=allow dir=in protocol=TCP localport=450 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall delete rule name="atomic testing" protocol=TCP localport=450 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## netsh

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2016

The Network Shell command-line scripting utility that allows you to, either locally or remotely, display or modify the network configuration of a currently running computer. You can start this utility at the command prompt or in Windows PowerShell.

### Syntax

```
netsh [-a <Aliasfile>][-c <Context>][-r <Remotecomputer>][-u [<domainname>\<username>][-p <Password> | [{<NetshCommand> | -f <scriptfile>}]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -a `<Aliasfile>` | Specifies that you are returned to the netsh prompt after running Aliasfile and the name of the text file that contains one or more netsh commands. |
| -c `<Context>` | Specifies that netsh enters the specified netsh context and the netsh context to enter. |
| -r `<Remotecomputer>` | Specifies the remote computer to configure.<p>**Important:** If you use this parameter, you must make sure the Remote Registry service is running on the remote computer. If it isn't running, Windows displays a â€œNetwork Path Not Foundâ€ error message. |
| -u `<domainname>\<username>` | Specifies the domain and user account name to use while running the netsh command under a user account. If you omit the domain, the local domain is used by default. |
| -p `<Password>` | Specifies the password for the user account specified by the `-u <username>` parameter. |
| `<NetshCommand>` | Specifies the netsh command to run. |
| -f `<scriptfile>` | Exits the netsh command after running the specified script file. |
| /? | Displays help at the command prompt. |

##### Remarks

- If you specify **-r** followed by another command, netsh runs the command on the remote computer and then returns to the Cmd.exe command prompt. If you specify **-r** without another command, netsh opens in remote mode. The process is similar to using **set machine** at the Netsh command prompt. When you use **-r**, you set the target computer for the current instance of netsh only. After you exit and reenter netsh, the target computer is reset as the local computer. You can run netsh commands on a remote computer by specifying a computer name stored in WINS, a UNC name, an Internet name to be resolved by the DNS server, or an IP address.

- If your string value contains spaces between characters, you must enclose the string value in quotation marks. For example, `-r "contoso remote device"`

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


