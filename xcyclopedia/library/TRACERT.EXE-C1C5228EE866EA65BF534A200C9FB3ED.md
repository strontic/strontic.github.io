---
title: TRACERT.EXE | TCP/IP Traceroute Command
excerpt: What is TRACERT.EXE?
---

# TRACERT.EXE 

* File Path: `C:\WINDOWS\SysWOW64\TRACERT.EXE`
* Description: TCP/IP Traceroute Command

## Hashes

Type | Hash
-- | --
MD5 | `C1C5228EE866EA65BF534A200C9FB3ED`
SHA1 | `071B5C16DA2CC8838272039C1ABA604B833302D6`
SHA256 | `DB796C9CC5B166AF946EF1160FBE8367FDE2C69574C97CA7281A5DFBCF1FEDC1`
SHA384 | `EAA1F344A268E16CEF09B837F28C19348B66B02C915FEFF97B37A3ABE1DCD5DB62A3FCB18438CA574351475E742113E2`
SHA512 | `A8A8E2D2C27B633DC7F8C4244183B8246F3A4E76504A3119903B6D492A43E2672A6EBF26C0374E3324659E9ED531FD4FB3F24C316DF06003594D35200AF89485`
SSDEEP | `192:A+8h406PrMtawCWQVW985fkqZc1/cwRcwKAvXGgGwmiQRLejC/eWBaW6e3A:A+l06PrnR5VWIZhAvf5mtLeuGWBaW`
IMP | `0727B2E083DCEAE4BC2D3B322A5A2171`
PESHA1 | `ACAAF6D7C00D760E807149E3A637AA8064618D44`
PE256 | `FE73CD05F949B1F3FF015FBBA4C092ACFEF14624D22DF8D5B88E93537C8749C5`

## Runtime Data

### Usage (stdout):
```cmhg
--help is not a valid command option.

Usage: tracert [-d] [-h maximum_hops] [-j host-list] [-w timeout] 
               [-R] [-S srcaddr] [-4] [-6] target_name

Options:
    -d                 Do not resolve addresses to hostnames.
    -h maximum_hops    Maximum number of hops to search for target.
    -j host-list       Loose source route along host-list (IPv4-only).
    -w timeout         Wait timeout milliseconds for each reply.
    -R                 Trace round-trip path (IPv6-only).
    -S srcaddr         Source address to use (IPv6-only).
    -4                 Force using IPv4.
    -6                 Force using IPv6.

```

### Child Processes:
conhost.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\TRACERT.EXE |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tracert.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/db796c9cc5b166af946ef1160fbe8367fde2c69574c97ca7281a5dfbcf1fedc1/detection


## Possible Misuse

*The following table contains possible examples of `TRACERT.EXE` being misused. While `TRACERT.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- tracert.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\tracert.exe' `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tracert

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

This diagnostic tool determines the path taken to a destination by sending Internet Control Message Protocol (ICMP) echo Request or ICMPv6 messages to the destination with incrementally increasing time to live (TTL) field values. Each router along the path is required to decrement the TTL in an IP packet by at least 1 before forwarding it. Effectively, the TTL is a maximum link counter. When the TTL on a packet reaches 0, the router is expected to return an ICMP time Exceeded message to the source computer.

This command determines the path by sending the first echo Request message with a TTL of 1 and incrementing the TTL by 1 on each subsequent transmission until the target responds or the maximum number of hops is reached. The maximum number of hops is 30 by default and can be specified using the **/h** parameter.

The path is determined by examining the ICMP time Exceeded messages returned by intermediate routers and the echo Reply message returned by the destination. However, some routers do not return time Exceeded messages for packets with expired TTL values and are invisible to the **tracert** command. In this case, a row of asterisks (`*`) is displayed for that hop. The path displayed is the list of near/side router interfaces of the routers in the path between a source host and a destination. The near/side interface is the interface of the router that is closest to the sending host in the path.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.
>
> To trace a path and provide network latency and packet loss for each router and link in the path, use the [pathping command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pathping.md) command.

### Syntax

```
tracert [/d] [/h <maximumhops>] [/j <hostlist>] [/w <timeout>] [/R] [/S <srcaddr>] [/4][/6] <targetname>
```

#### Parameters

| Parameter | Description |
|--|--|
| /d | Stops attempts to resolve the IP addresses of intermediate routers to their names. This can speed up the return of results. |
| /h `<maximumhops>` | Specifies the maximum number of hops in the path to search for the target (destination). The default is 30 hops. |
| /j `<hostlist>` | Specifies that echo Request messages use the Loose Source Route option in the IP header with the set of intermediate destinations specified in `<hostlist>`. With loose source routing, successive intermediate destinations can be separated by one or multiple routers. The maximum number of addresses or names in the list is *9*. The `<hostlist>` is a series of IP addresses (in dotted decimal notation) separated by spaces. Use this parameter only when tracing IPv4 addresses. |
| /w `<timeout>` | Specifies the amount of time in milliseconds to wait for the ICMP time Exceeded or echo Reply message corresponding to a given echo Request message to be received. If not received within the time-out, an asterisk (`*`) is displayed. The default time-out is 4000 (4 seconds). |
| /R | Specifies that the IPv6 Routing extension header be used to send an echo Request message to the local host, using the destination as an intermediate destination and testing the reverse route. |
| /S `<srcaddr>` | Specifies the source address to use in the echo Request messages. Use this parameter only when tracing IPv6 addresses. |
| /4 | Specifies that tracert.exe can use only IPv4 for this trace. |
| /6 | Specifies that tracert.exe can use only IPv6 for this trace. |
| `<targetname>` | Specifies the destination, identified either by IP address or host name. |
| /? | Displays help at the command prompt. |

### Examples

To trace the path to the host named *corp7.microsoft.com*, type:

```
tracert corp7.microsoft.com
```

To trace the path to the host named *corp7.microsoft.com* and prevent the resolution of each IP address to its name, type:

```
tracert /d corp7.microsoft.com
```

To trace the path to the host named *corp7.microsoft.com* and use the loose source route *10.12.0.1/10.29.3.1/10.1.44.1*, type:

```
tracert /j 10.12.0.1 10.29.3.1 10.1.44.1 corp7.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [pathping command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pathping.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


