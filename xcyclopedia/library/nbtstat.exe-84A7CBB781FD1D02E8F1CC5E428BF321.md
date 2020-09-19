---
title: nbtstat.exe | TCP/IP NetBios Information
---

# nbtstat.exe 

* File Path: `C:\windows\system32\nbtstat.exe`
* Description: TCP/IP NetBios Information

## Hashes

Type | Hash
-- | --
MD5 | `84A7CBB781FD1D02E8F1CC5E428BF321`
SHA1 | `6633FAFDA738097DD5EEB90F902D36DC951364DE`
SHA256 | `778CD1EBFDC9FA6457497741DA5431E4DE16F2FAD490ED88ADE6E3BEC16096B1`
SHA384 | `66F1AEB28A34034021493DDC37BB4BDFF24BA5DC9E43AF92C22BAE9133C5A887D34464FC1E0DF73B34AAFA1720E7726B`
SHA512 | `76D99AE928304BBB51B7E181B3097249963E1B50C83DF155E1C20D52E2F7323E5CF1926023DD1C4A75DF89C4C4CC88E2875F403B8BA3D0F12C631F624DC28C05`
SSDEEP | `384:3f9uU67jGzIG2Q5s84I8jQwdJBF4RDc+Ii95IQ5an9YWXrW:31uU6OI584IkBAhQT`

## Signature

* Status: The file C:\windows\system32\nbtstat.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: nbtinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `nbtstat.exe` being misused. While `nbtstat.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- nbtstat.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- nbtstat` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries will likely look for details about the network configuration and settings of systems they access or through information discovery of remote systems. Several operating system administration utilities exist that can be used to gather this information. Examples include [Arp](https://attack.mitre.org/software/S0099), [ipconfig](https://attack.mitre.org/software/S0100)/[ifconfig](https://attack.mitre.org/software/S0101), [nbtstat](https://attack.mitre.org/software/S0102), and [route](https://attack.mitre.org/software/S0103).\n\nAdversaries may use the information from [System Network Configuration Discovery](https://attack.mitre.org/techniques/T1016) during automated discovery to shape follow-on behaviors, including whether or not the adversary fully infects the target and/or attempts specific actions.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-lightneuron-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-lightneuron-event.json) | `"description": "Adversaries will likely look for details about the network configuration and settings of systems they access or through information discovery of remote systems. Several operating system administration utilities exist that can be used to gather this information. Examples include Arp, ipconfig/ifconfig, nbtstat, and route.\n\nDetection: System and network discovery techniques normally occur throughout an operation as an adversary learns the environment. Data and events should not be viewed in isolation, but as part of a chain of behavior that could lead to other activities, such as Lateral Movement, based on the information obtained.\n\nMonitor processes and command-line arguments for actions that could be taken to gather system and network information. Remote access tools with built-in features may interact directly with the Windows API to gather information. Information may also be acquired through Windows system management tools such as Windows Management Instrumentation and PowerShell.\n\nPlatforms: Linux, macOS, Windows\n\nData Sources: Process command-line parameters, Process monitoring\n\nPermissions Required: User",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | <blockquote>Adversaries may look for details about the network configuration and settings of systems they access or through information discovery of remote systems. Several operating system administration utilities exist that can be used to gather this information. Examples include [Arp](https://attack.mitre.org/software/S0099), [ipconfig](https://attack.mitre.org/software/S0100)/[ifconfig](https://attack.mitre.org/software/S0101), [nbtstat](https://attack.mitre.org/software/S0102), and [route](https://attack.mitre.org/software/S0103). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | nbtstat -n | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_terracotta.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_terracotta.yar) | 		$s3 = "\\nbtstat.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) |       $ = "nbtstat" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## nbtstat

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays NetBIOS over TCP/IP (NetBT) protocol statistics, NetBIOS name tables for both the local computer and remote computers, and the NetBIOS name cache. This command also allows a refresh of the NetBIOS name cache and the names registered with Windows Internet Name Service (WINS). Used without parameters, this command displays Help information.

This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
nbtstat [/a <remotename>] [/A <IPaddress>] [/c] [/n] [/r] [/R] [/RR] [/s] [/S] [<interval>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| /a `<remotename>` | Displays the NetBIOS name table of a remote computer, where *remotename* is the NetBIOS computer name of the remote computer. The NetBIOS name table is the list of NetBIOS names that corresponds to NetBIOS applications running on that computer. |
| /A `<IPaddress>` | Displays the NetBIOS name table of a remote computer, specified by the IP address (in dotted decimal notation) of the remote computer. |
| /c | Displays the contents of the NetBIOS name cache, the table of NetBIOS names and their resolved IP addresses. |
| /n | Displays the NetBIOS name table of the local computer. The status of **registered** indicates that the name is registered either by broadcast or with a WINS server. |
| /r | Displays NetBIOS name resolution statistics. |
| /R | Purges the contents of the NetBIOS name cache and then reloads the pre-tagged entries from the **Lmhosts** file. |
| /RR | Releases and then refreshes NetBIOS names for the local computer that is registered with WINS servers. |
| /s | Displays NetBIOS client and server sessions, attempting to convert the destination IP address to a name. |
| /S | Displays NetBIOS client and server sessions, listing the remote computers by destination IP address only. |
| `<interval>` | Displays selected statistics, pausing the number of seconds specified in *interval* between each display. Press CTRL+C to stop displaying statistics. If this parameter is omitted, **nbtstat** prints the current configuration information only once. |
| /? | Displays help at the command prompt. |

##### Remarks

- The **nbtstat** command-line parameters are case-sensitive.

- The column headings generated by the **nbtstat** command, include:

    | Heading | Description |
    | ------- | ----------- |
    | Input | The number of bytes received. |
    | Output | The number of bytes sent. |
    | In/Out | Whether the connection is from the computer (outbound) or from another computer to the local computer (inbound). |
    | Life | The remaining time that a name table cache entry will live before it is purged. |
    | Local Name | The local NetBIOS name associated with the connection. |
    | Remote Host | The name or IP address associated with the remote computer. |
    | `<03>` | The last byte of a NetBIOS name converted to hexadecimal. Each NetBIOS name is 16 characters long. This last byte often has special significance because the same name might be present several times on a computer, differing only in the last byte. For example, `<20>` is a space in ASCII text. |
    | type | The type of name. A name can either be a unique name or a group name. |
    | Status | Whether the NetBIOS service on the remote computer is running (registered) or a duplicate computer name has registered the same service (Conflict). |
    | State | The state of NetBIOS connections. |

- The possible NetBIOS connection states, include:

    | State | Description |
    | ------- | ----------- |
    | Connected | A session has been established. |
    | listening | This endpoint is available for an inbound connection. |
    | Idle | This endpoint has been opened but cannot receive connections. |
    | Connecting | A session is in the connecting phase and the name-to-IP address mapping of the destination is being resolved. |
    | Accepting | An inbound session is currently being accepted and will be connected shortly. |
    | Reconnecting | A session is trying to reconnect (it failed to connect on the first attempt). |
    | Outbound | A session is in the connecting phase and the TCP connection is currently being created. |
    | Inbound | An inbound session is in the connecting phase. |
    | Disconnecting | A session is in the process of disconnecting. |
    | Disconnected | The local computer has issued a disconnect and it is waiting for confirmation from the remote system. |

#### Examples

To display the NetBIOS name table of the remote computer with the NetBIOS computer name of *CORP07*, type:

```
nbtstat /a CORP07
```

To display the NetBIOS name table of the remote computer assigned the IP address of *10.0.0.99*, type:

```
nbtstat /A 10.0.0.99
```

To display the NetBIOS name table of the local computer, type:

```
nbtstat /n
```

To display the contents of the local computer NetBIOS name cache, type:

```
nbtstat /c
```

To purge the NetBIOS name cache and reload the pre-tagged entries in the local *Lmhosts* file, type:

```
nbtstat /R
```

To release the NetBIOS names registered with the WINS server and re-register them, type:

```
nbtstat /RR
```

To display NetBIOS session statistics by IP address every five seconds, type:

```
nbtstat /S 5
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


