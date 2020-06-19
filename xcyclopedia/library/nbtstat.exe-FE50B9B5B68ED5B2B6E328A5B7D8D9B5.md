
# nbtstat.exe 

* File Path: `C:\WINDOWS\system32\nbtstat.exe`
* Description: TCP/IP NetBios Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FE50B9B5B68ED5B2B6E328A5B7D8D9B5`
SHA1 | `5AA269F216EC8B4DB21B534347565F0AFBAD2CA0`
SHA256 | `40ABBD7EBDB3CD6FA60E9AF4A584E99D7295DD10D97FECCFEAF5183F5A943C54`
SHA384 | `8376751B6C39755AB318CDCE7A11FECDAD318FDDEFA6192BDE7C3172B3CE38F724379CA7875E298C66C167B6D29183C0`
SHA512 | `F842778706CC220EAC7794264D89E6A39C171B18B5FC7B8417124AEE2C2F8946B89762FF21C09A61BB12CA319AF99310BB05B1CB4DAFC3AB423F5A9FA4E07632`
SSDEEP | `384:KCZSVzL69ZiDYYv2L9Q9RlS9ptktI7J8WUrW:K2SFOPiMYUyPT9`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

Displays protocol statistics and current TCP/IP connections using NBT
(NetBIOS over TCP/IP).

NBTSTAT [ [-a RemoteName] [-A IP address] [-c] [-n]
        [-r] [-R] [-RR] [-s] [-S] [interval] ]

  -a   (adapter status) Lists the remote machine's name table given its name
  -A   (Adapter status) Lists the remote machine's name table given its
                        IP address.
  -c   (cache)          Lists NBT's cache of remote [machine] names and their IP addresses
  -n   (names)          Lists local NetBIOS names.
  -r   (resolved)       Lists names resolved by broadcast and via WINS
  -R   (Reload)         Purges and reloads the remote cache name table
  -S   (Sessions)       Lists sessions table with the destination IP addresses
  -s   (sessions)       Lists sessions table converting destination IP
                        addresses to computer NETBIOS names.
  -RR  (ReleaseRefresh) Sends Name Release packets to WINS and then, starts Refresh

  RemoteName   Remote host machine name.
  IP address   Dotted decimal representation of the IP address.
  interval     Redisplays selected statistics, pausing interval seconds
               between each display. Press Ctrl+C to stop redisplaying
               statistics.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nbtinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `nbtstat.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - nbtstat.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `            - nbtstat` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-lightneuron-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-lightneuron-event.json) | `                                "description": "Adversaries will likely look for details about the network configuration and settings of systems they access or through information discovery of remote systems. Several operating system administration utilities exist that can be used to gather this information. Examples include Arp, ipconfig/ifconfig, nbtstat, and route.\n\nDetection: System and network discovery techniques normally occur throughout an operation as an adversary learns the environment. Data and events should not be viewed in isolation, but as part of a chain of behavior that could lead to other activities, such as Lateral Movement, based on the information obtained.\n\nMonitor processes and command-line arguments for actions that could be taken to gather system and network information. Remote access tools with built-in features may interact directly with the Windows API to gather information. Information may also be acquired through Windows system management tools such as Windows Management Instrumentation and PowerShell.\n\nPlatforms: Linux, macOS, Windows\n\nData Sources: Process command-line parameters, Process monitoring\n\nPermissions Required: User",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | <blockquote>Adversaries may look for details about the network configuration and settings of systems they access or through information discovery of remote systems. Several operating system administration utilities exist that can be used to gather this information. Examples include [Arp](https://attack.mitre.org/software/S0099), [ipconfig](https://attack.mitre.org/software/S0100)/[ifconfig](https://attack.mitre.org/software/S0101), [nbtstat](https://attack.mitre.org/software/S0102), and [route](https://attack.mitre.org/software/S0103). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | nbtstat -n | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

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


