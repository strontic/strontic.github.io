---
title: TRACERT.EXE | TCP/IP Traceroute Command
excerpt: What is TRACERT.EXE?
---

# TRACERT.EXE 

* File Path: `C:\windows\system32\TRACERT.EXE`
* Description: TCP/IP Traceroute Command

## Hashes

Type | Hash
-- | --
MD5 | `2F2FFD789E57A77E0869E5E321602D13`
SHA1 | `37590B5426D950D8834179EEA55C694DD66D1FA4`
SHA256 | `4E8114C4ECB6AFFEDBF56FAD3F5A11101CFEA6A05C6BF00CDE4BE45DB682A2BD`
SHA384 | `0E75FC6DD93642D31D3016D18B5B265795012E4B817A76FF21BE60394E64A63C3C6E340F1BCCEEA93B655A33CE8531BD`
SHA512 | `828A9520DCBB8BC5C3A27361F1CFDD2D6F961F07884DE5BF90D91A8A3BE8A0635947C6722EE44C67FE15F4806F22F6D27B5A067A66838306145A03950CED9315`
SSDEEP | `384:fkpX9jPMV5J9VKVy8hyFp1txWHZcJjy2HWcaW:fqyHVKUcyFTaHZEjyC`

## Signature

* Status: The file C:\windows\system32\TRACERT.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tracert.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


