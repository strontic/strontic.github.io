﻿---
title: TRACERT.EXE | TCP/IP Traceroute Command
excerpt: What is TRACERT.EXE?
---

# TRACERT.EXE 

* File Path: `C:\Windows\system32\TRACERT.EXE`
* Description: TCP/IP Traceroute Command

## Hashes

Type | Hash
-- | --
MD5 | `FEDBAC964787AD4898109A744FB6EC02`
SHA1 | `1DAEA40E923EE1FD8C5832274CDD478A45685E46`
SHA256 | `743F8E8A91B2D1E0DB9323109034DE91A1E065242A33A90BB787A63EDB860B35`
SHA384 | `9E54E476DC22C560595DF071A8511B630C2BF1887FBD1137A8F790D01611D607F68B0E84B3046F3FE92A23CC3B411852`
SHA512 | `A4B486F99F19914148A2D06433CFE007992096B497BFDE66EAA740308413D3F7D899CE7D75EBC392C4DE482F0B788DD081DB4E010FDE4B636894948415B31F65`
SSDEEP | `384:NYFTJuM9IzcKonUb4W1MAYZC7dbcpJplmmL1y9W6aW:NYFtuMMjiIbdEpQmL1i`
IMP | `7A80F2FE2DD40125FA241B4F53DF08D1`
PESHA1 | `475164396A1A4B265AF9311400F15FB02C07B620`
PE256 | `6EC690DE44666B3F1FDE55C6A6B56E40263F90BAEE6CD437CDF58BE290F49E34`

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

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\TRACERT.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tracert.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/743f8e8a91b2d1e0db9323109034de91a1e065242a33a90bb787a63edb860b35/detection


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


