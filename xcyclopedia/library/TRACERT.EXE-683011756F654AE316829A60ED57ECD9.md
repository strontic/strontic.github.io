---
title: TRACERT.EXE | TCP/IP Traceroute Command
---

# TRACERT.EXE 

* File Path: `C:\windows\SysWOW64\TRACERT.EXE`
* Description: TCP/IP Traceroute Command

## Hashes

Type | Hash
-- | --
MD5 | `683011756F654AE316829A60ED57ECD9`
SHA1 | `BBAD6A7AFFC7511A9A6EEBC6BB8A93C201FE4364`
SHA256 | `61C0CA8E85623254FDC4A5FAAE60789888CDBDEB2E302092B5F4846D9EC68BA8`
SHA384 | `02060DE5D8068178B05D56F5FE7DD90C2612E8E8F61EEDCF88B1C6FCD3074E45A16845F92EAEA10804AEE5911F67F8D6`
SHA512 | `B259C01864F0B733A1FAE5226EB6D9B7F13B156D5BA4A5C702C1CB87CC75C1B701116CCD8E44F28066D4F770F48F3ED4F596BA9AAB051BAAF7A92A4A3AC3D76A`
SSDEEP | `384:bBNb1gKpfllTM3XPqwh3jT3WcaWvlByV:HrfvTzwBjbjlBy`

## Signature

* Status: The file C:\windows\SysWOW64\TRACERT.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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

*The following table contains possible examples of `TRACERT.EXE` being misused. While `TRACERT.EXE` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- 'tracert -h 10 yahoo.com'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- tracert.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tracert

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Determines the path taken to a destination by sending Internet Control Message Protocol (ICMP) echo Request or ICMPv6 messages to the destination with incrementally increasing time to Live (TTL) field values. The path displayed is the list of near/side router interfaces of the routers in the path between a source host and a destination. The near/side interface is the interface of the router that is closest to the sending host in the path. Used without parameters, tracert displays help.


### Syntax

```
tracert [/d] [/h <MaximumHops>] [/j <Hostlist>] [/w <timeout>] [/R] [/S <Srcaddr>] [/4][/6] <TargetName>
```

##### Parameters

|Parameter|Description|
|-------|--------|
|/d|Prevents **tracert** from attempting to resolve the IP addresses of intermediate routers to their names. This can speed up the display of **tracert** results.|
|/h \<MaximumHops>|Specifies the maximum number of hops in the path to search for the target (destination). The default is 30 hops.|
|/j \<Hostlist>|Specifies that echo Request messages use the Loose Source Route option in the IP header with the set of intermediate destinations specified in *Hostlist*. With loose source routing, successive intermediate destinations can be separated by one or multiple routers. The maximum number of addresses or names in the host list is 9. The *Hostlist* is a series of IP addresses (in dotted decimal notation) separated by spaces. Use this parameter only when tracing IPv4 addresses.|
|/w \<timeout>|Specifies the amount of time in milliseconds to wait for the ICMP time Exceeded or echo Reply message corresponding to a given echo Request message to be received. If not received within the time-out, an asterisk (*) is displayed. The default time-out is 4000 (4 seconds).|
|/R|Specifies that the IPv6 Routing extension header be used to send an echo Request message to the local host, using the destination as an intermediate destination and testing the reverse route.|
|/S \<Srcaddr>|Specifies the source address to use in the echo Request messages. Use this parameter only when tracing IPv6 addresses.|
|/4|Specifies that tracert.exe can use only IPv4 for this trace.|
|/6|Specifies that tracert.exe can use only IPv6 for this trace.|
|\<TargetName>|Specifies the destination, identified either by IP address or host name.|
|/?|Displays help at the command prompt.|

### Remarks

- This diagnostic tool determines the path taken to a destination by sending ICMP echo Request messages with varying time to Live (TTL) values to the destination. Each router along the path is required to decrement the TTL in an IP packet by at least 1 before forwarding it. Effectively, the TTL is a maximum link counter. When the TTL on a packet reaches 0, the router is expected to return an ICMP time Exceeded message to the source computer. tracert determines the path by sending the first echo Request message with a TTL of 1 and incrementing the TTL by 1 on each subsequent transmission until the target responds or the maximum number of hops is reached. The maximum number of hops is 30 by default and can be specified using the **/h** parameter. The path is determined by examining the ICMP time Exceeded messages returned by intermediate routers and the echo Reply message returned by the destination. However, some routers do not return time Exceeded messages for packets with expired TTL values and are invisible to the tracert command. In this case, a row of asterisks (*) is displayed for that hop.
- To trace a path and provide network latency and packet loss for each router and link in the path, use the [**pathping**](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pathping.md) command.
- This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Examples

To trace the path to the host named corp7.microsoft.com, type:
```
tracert corp7.microsoft.com
```
To trace the path to the host named corp7.microsoft.com and prevent the resolution of each IP address to its name, type:
```
tracert /d corp7.microsoft.com
```
To trace the path to the host named corp7.microsoft.com and use the loose source route 10.12.0.1/10.29.3.1/10.1.44.1, type:
```
tracert /j 10.12.0.1 10.29.3.1 10.1.44.1 corp7.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


