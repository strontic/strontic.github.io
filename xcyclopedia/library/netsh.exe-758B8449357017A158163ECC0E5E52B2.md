---
title: netsh.exe | Network Command Shell
excerpt: What is netsh.exe?
---

# netsh.exe 

* File Path: `C:\Windows\system32\netsh.exe`
* Description: Network Command Shell

## Hashes

Type | Hash
-- | --
MD5 | `758B8449357017A158163ECC0E5E52B2`
SHA1 | `21190DE3629B7A40409897CAF9563EB1EE1944B2`
SHA256 | `D70D165B6706C61C56F2CA91307F4BBDB9846ACAE1DA3CFD84BF978FFB21AF23`
SHA384 | `D5ACD229C559F8699783B4B072DE45CC6010F815ECFDBAAE3649BFC72AA1F3AE2833D30F3F8E77B09800A254FFDA1D85`
SHA512 | `3A8CB1435A6503B9AC100E2CA49C347386143595E40AF81D8334F665740B414B3628DC4E461316E25A33DD9106B9D7D9B157067F368DD9ADB3FA5DC1B4DCC0F0`
SSDEEP | `1536:xb5iUv5pSTKh6SwRe2nrA56c6PlCNbiA9SDi:xb5i+7SToHwRe2n056vPlCdhke`
IMP | `90B4317BE51850B8EF9F14EB56FB7DDC`
PESHA1 | `FD72D611DBDC94D9F3D23A749F2AEEBB8DDFCF90`
PE256 | `E59EC436DFC12EA561AAE563C414206636EF5A556509A01CA56E45FDD238B14F`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: C:\Windows\system32\netsh.exe [-a AliasFile] [-c Context] [-r RemoteMachine] [-u [DomainName\]UserName] [-p Password | *]
             [Command | -f ScriptFile]

The following commands are available:

Commands in this context:
?              - Displays a list of commands.
add            - Adds a configuration entry to a list of entries.
advfirewall    - Changes to the `netsh advfirewall' context.
branchcache    - Changes to the `netsh branchcache' context.
bridge         - Changes to the `netsh bridge' context.
delete         - Deletes a configuration entry from a list of entries.
dhcpclient     - Changes to the `netsh dhcpclient' context.
dnsclient      - Changes to the `netsh dnsclient' context.
dump           - Displays a configuration script.
exec           - Runs a script file.
firewall       - Changes to the `netsh firewall' context.
help           - Displays a list of commands.
http           - Changes to the `netsh http' context.
interface      - Changes to the `netsh interface' context.
ipsec          - Changes to the `netsh ipsec' context.
ipsecdosprotection - Changes to the `netsh ipsecdosprotection' context.
lan            - Changes to the `netsh lan' context.
namespace      - Changes to the `netsh namespace' context.
netio          - Changes to the `netsh netio' context.
ras            - Changes to the `netsh ras' context.
rpc            - Changes to the `netsh rpc' context.
set            - Updates configuration settings.
show           - Displays information.
trace          - Changes to the `netsh trace' context.
wfp            - Changes to the `netsh wfp' context.
winhttp        - Changes to the `netsh winhttp' context.
winsock        - Changes to the `netsh winsock' context.

The following sub-contexts are available:
 advfirewall branchcache bridge dhcpclient dnsclient firewall http interface ipsec ipsecdosprotection lan namespace netio ras rpc trace wfp winhttp winsock

To view help for a command, type the command, followed by a space, and then
 type ?.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netsh.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netsh.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d70d165b6706c61c56f2ca91307f4bbdb9846acae1da3cfd84bf978ffb21af23/detection/


## Possible Misuse

*The following table contains possible examples of `netsh.exe` being misused. While `netsh.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `- 'netsh advfirewall firewall add rule name=powershell dir=in'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- netsh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `title: Netsh RDP Port Opening`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `description: Detects netsh commands that opens the port 3389 used for RDP, used in Sarwent Malware`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_allow_port_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_allow_port_rdp.yml) | `- netsh`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add.yml) | `title: Netsh Port or Application Allowed`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add.yml) | `- '*netsh*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `title: Netsh Program Allowed with Suspcious Location`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `description: Detects Netsh commands that allows a suspcious application location on Windows Firewall`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `- 'netsh'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_fw_add_susp_image.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_fw_add_susp_image.yml) | `- netsh`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `title: Capture a Network Trace with netsh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `description: Detects capture a network trace via netsh.exe trace functionality`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `- netsh`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_packet_capture.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_packet_capture.yml) | `- Legitimate administrator or user uses netsh.exe trace functionality for legitimate reason`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `title: Netsh Port Forwarding`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `description: Detects netsh commands that configure a port forwarding`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd.yml) | `- netsh interface portproxy add v4tov4 *`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `title: Netsh RDP Port Forwarding`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `description: Detects netsh commands that configure a port forwarding of port 3389 used for RDP`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_port_fwd_3389.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_port_fwd_3389.yml) | `- netsh i* p*=3389 c*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `title: Harvesting of Wifi Credentials Using netsh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `description: Detect the harvesting of wifi credentials using netsh.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `- 'netsh wlan s* p* k*=clear'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_netsh_wifi_credential_harvesting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_netsh_wifi_credential_harvesting.yml) | `- Legitimate administrator or user uses netsh.exe wlan functionality for legitimate reason`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'netsh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\netsh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `title: Firewall Disabled via Netsh`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `description: Detects netsh commands that turns off the Windows firewall`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `- netsh firewall set opmode mode=disable`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_firewall_disable.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_firewall_disable.yml) | `- netsh advfirewall set * state off`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `title: Suspicious Netsh DLL Persistence`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `description: Detects persitence via netsh helper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_netsh_dll_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_netsh_dll_persistence.yml) | `Image\|endswith: '\netsh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `Name: Netsh.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `netsh.exe trace start capture=yes filemode=append persistent=yes tracefile=\\server\share\file.etl IPv4.Address=!(<IPofRemoteFileShare>)`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `netsh.exe trace show status`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Path\file.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `Description: Load (execute) NetSh.exe helper DLL file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Netsh.yml) | `- Command: netsh interface portproxy add v4tov4 listenport=8080 listenaddress=0.0.0.0 connectport=8000 connectaddress=192.168.1.1`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `Name: Netsh.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `Description: Netsh is a Windows tool used to manipulate network interface settings.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Command: netsh.exe add helper C:\Users\User\file.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `Description: Use Netsh in order to execute a .dll file and also gain persistence, every time the netsh command is called`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Path: C:\WINDOWS\System32\Netsh.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Path: C:\WINDOWS\SysWOW64\Netsh.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- IOC: Netsh initiating a network connection`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries may attempt to get a listing of security software, configurations, defensive tools, and sensors that are installed on the system. This may include things such as local firewall rules and anti-virus. Adversaries may use the information from [Security Software Discovery](https://attack.mitre.org/techniques/T1063) during automated discovery to shape follow-on behaviors, including whether or not the adversary fully infects the target and/or attempts specific actions.\n\n\n### Windows\n\nExample commands that can be used to obtain security software information are [netsh](https://attack.mitre.org/software/S0108), <code>reg query</code> with [Reg](https://attack.mitre.org/software/S0075), <code>dir</code> with [cmd](https://attack.mitre.org/software/S0106), and [Tasklist](https://attack.mitre.org/software/S0057), but other indicators of discovery behavior may be more specific to the type of software or security system the adversary is looking for.\n\n### Mac\n\nIt's becoming more common to see macOS malware perform checks for LittleSnitch and KnockKnock software.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1546.007 Netsh Helper DLL](../../T1546.007/T1546.007.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Netsh Helper DLL Registration [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Launch Daemon](../../T1543.004/T1543.004.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [Gatekeeper Bypass](../../T1553.001/T1553.001.md) \| Unsecured Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [Path Interception by Unquoted Path](../../T1574.009/T1574.009.md) \| [Hide Artifacts](../../T1564/T1564.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Local Account](../../T1136.001/T1136.001.md) \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| [File Deletion](../../T1070.004/T1070.004.md) \| [Security Account Manager](../../T1003.002/T1003.002.md) \|  \|  \|  \|  \| [Remote Access Software](../../T1219/T1219.md) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Netsh Helper DLL](../../T1546.007/T1546.007.md) \| Path Interception [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Hidden File System [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal or Forge Kerberos Tickets [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \| Symmetric Cryptography [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | netsh interface show interface | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Enumerates Windows Firewall Rules using netsh. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn netsh.exe to list firewall rules. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | netsh advfirewall firewall show rule name=all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1040.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1040/T1040.md) | netsh trace start capture=yes tracefile=%temp%\trace.etl maxsize=10 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1040.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1040/T1040.md) | netsh trace stop | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | Upon execution there will be a new proxy entry in netsh | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy show all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy add v4tov4 listenport=#{listenport} connectport=#{connectport} connectaddress=#{connectaddress} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1090.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1090.001/T1090.001.md) | netsh interface portproxy delete v4tov4 listenport=#{listenport} -ErrorAction Ignore \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | Example commands that can be used to obtain security software information are [netsh](https://attack.mitre.org/software/S0108), <code>reg query</code> with [Reg](https://attack.mitre.org/software/S0075), <code>dir</code> with [cmd](https://attack.mitre.org/software/S0106), and [Tasklist](https://attack.mitre.org/software/S0057), but other indicators of discovery behavior may be more specific to the type of software or security system the adversary is looking for. It is becoming more common to see macOS malware perform checks for LittleSnitch and KnockKnock software. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | netsh.exe advfirewall  show allprofiles | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | # T1546.007 - Netsh Helper DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | <blockquote>Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs. Netsh.exe (also referred to as Netshell) is a command-line scripting utility used to interact with the network configuration of a system. It contains functionality to add helper DLLs for extending functionality of the utility. (Citation: TechNet Netsh) The paths to registered netsh.exe helper DLLs are entered into the Windows Registry at <code>HKLM\SOFTWARE\Microsoft\Netsh</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | Adversaries can use netsh.exe helper DLLs to trigger execution of arbitrary code in a persistent manner. This execution would take place anytime netsh.exe is executed, which could happen automatically, with another persistence technique, or if other software (ex: VPN) is present on the system that executes netsh.exe as part of its normal functionality. (Citation: Github Netsh Helper CS Beacon)(Citation: Demaske Netsh Persistence)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | - [Atomic Test #1 - Netsh Helper DLL Registration](#atomic-test-1---netsh-helper-dll-registration) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | ## Atomic Test #1 - Netsh Helper DLL Registration | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | Netsh interacts with other operating system components using dynamic-link library (DLL) files | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | netsh.exe add helper #{helper_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall set currentprofile state off | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall set currentprofile state on >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall set rule group="remote desktop" new enable=Yes | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall set rule group="file and printer sharing" new enable=Yes | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall reset >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall add rule name="atomic testing" action=allow dir=in protocol=TCP localport=450 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall delete rule name="atomic testing" protocol=TCP localport=450 >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall add rule name="Open Port to Any" dir=in protocol=tcp localport=#{local_port} action=allow profile=any | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall delete rule name="Open Port to Any" \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall add rule name="Atomic Test" dir=in action=allow program="C:\Users\$env:UserName\AtomicTest.exe" enable=yes | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.004/T1562.004.md) | netsh advfirewall firewall delete rule name="Atomic Test" \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ar18_165a.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ar18_165a.yar) | $s1 = "netsh.exe advfirewall firewall add rule name=\"PortOpenning\" dir=in protocol=tcp localport=%d action=allow enable=yes" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ar18_165a.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ar18_165a.yar) | $s2 = "netsh.exe firewall add portopening TCP %d \"PortOpenning\" enable" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_aug20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_aug20.yar) | $str_netsh_1 = "netsh firewall add portopening TCP %d" ascii wide nocase  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_aug20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_aug20.yar) | $str_netsh_2 = "netsh firewall delete portopening TCP %d" ascii wide nocase  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_phish_gina_dec15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_phish_gina_dec15.yar) | $s1 = "netsh.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_malware_set_qa.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_malware_set_qa.yar) | $s6 = "netsh firewall delete allowedprogram" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_backnet.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_backnet.yar) | $s3 = "/C netsh wlan show profile" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $s2 = "netsh firewall add allowedprogram" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | description = "Detects a suspicious command line with netsh and the portproxy command" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | reference = "https://docs.microsoft.com/en-us/windows-server/networking/technologies/netsh/netsh-interface-portproxy" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $x1 = "netsh interface portproxy add v4tov4 listenport=" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020-2021 Strontic.


