﻿---
title: NETSTAT.EXE | TCP/IP Netstat Command
excerpt: What is NETSTAT.EXE?
---

# NETSTAT.EXE 

* File Path: `C:\Windows\SysWOW64\NETSTAT.EXE`
* Description: TCP/IP Netstat Command

## Hashes

Type | Hash
-- | --
MD5 | `FFE367661AFCD0ED0EB8E305A436797A`
SHA1 | `79A5027CD9BA4C5BD29D5A5C5EE28C616E2F0FEA`
SHA256 | `1F07B7C0C17324AEEAD6E7105A9668976D8731414448F56AACEE49BAA01351F6`
SHA384 | `72313F7DBCE927CB9AC5FE67EFD79C6A223CBD507A5382A21A6DBFDA886B153FF90C72B5438129E9ABEF6BEFA4C3C557`
SHA512 | `C43B790C82A27F82F63963F2BB9CD5F0F985CDF034AB4CC5CAEBE1CE5BA13DE235A658D0EE4B5AA3F4C5BC1EA25163E434E4C0E8FD88B8F12C991FE089E9C525`
SSDEEP | `384:XH/8LvAy7E9FKkUpzMiMJ2D33ns3FIC/UomimtUcuVO55O6ozvAXFuy4ahYvE3G2:XHrRWkUa53Fky1u/oLsu1vEubS6`

## Runtime Data

### Usage (stderr):
```cmhg

Displays protocol statistics and current TCP/IP network connections.

NETSTAT [-a] [-b] [-e] [-f] [-n] [-o] [-p proto] [-r] [-s] [-x] [-t] [interval]

  -a            Displays all connections and listening ports.
  -b            Displays the executable involved in creating each connection or
                listening port. In some cases well-known executables host
                multiple independent components, and in these cases the
                sequence of components involved in creating the connection
                or listening port is displayed. In this case the executable
                name is in [] at the bottom, on top is the component it called,
                and so forth until TCP/IP was reached. Note that this option
                can be time-consuming and will fail unless you have sufficient
                permissions.
  -e            Displays Ethernet statistics. This may be combined with the -s
                option.
  -f            Displays Fully Qualified Domain Names (FQDN) for foreign
                addresses.
  -n            Displays addresses and port numbers in numerical form.
  -o            Displays the owning process ID associated with each connection.
  -p proto      Shows connections for the protocol specified by proto; proto
                may be any of: TCP, UDP, TCPv6, or UDPv6.  If used with the -s
                option to display per-protocol statistics, proto may be any of:
                IP, IPv6, ICMP, ICMPv6, TCP, TCPv6, UDP, or UDPv6.
  -q            Displays all connections, listening ports, and bound
                nonlistening TCP ports. Bound nonlistening ports may or may not
                be associated with an active connection.
  -r            Displays the routing table.
  -s            Displays per-protocol statistics.  By default, statistics are
                shown for IP, IPv6, ICMP, ICMPv6, TCP, TCPv6, UDP, and UDPv6;
                the -p option may be used to specify a subset of the default.
  -t            Displays the current connection offload state.
  -x            Displays NetworkDirect connections, listeners, and shared
                endpoints.
  -y            Displays the TCP connection template for all connections.
                Cannot be combined with the other options.
  interval      Redisplays selected statistics, pausing interval seconds
                between each display.  Press CTRL+C to stop redisplaying
                statistics.  If omitted, netstat will print the current
                configuration information once.


```

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netstat.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `NETSTAT.EXE` being misused. While `NETSTAT.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\netstat.exe' `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | description = "Chinese Hacktool Set - file netstat.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## netstat

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays active TCP connections, ports on which the computer is listening, Ethernet statistics, the IP routing table, IPv4 statistics (for the IP, ICMP, TCP, and UDP protocols), and IPv6 statistics (for the IPv6, ICMPv6, TCP over IPv6, and UDP over IPv6 protocols). Used without parameters, this command displays active TCP connections.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
netstat [-a] [-b] [-e] [-n] [-o] [-p <Protocol>] [-r] [-s] [<interval>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -a | Displays all active TCP connections and the TCP and UDP ports on which the computer is listening. |
| -b | Displays the executable involved in creating each connection or listening port. In some cases well-known executables host multiple independent components, and in these cases the sequence of components involved in creating the connection or listening port is displayed. In this case the executable name is in [] at the bottom, on top is the component it called, and so forth until TCP/IP was reached. Note that this option can be time-consuming and will fail unless you have sufficient permissions.
| -e | Displays Ethernet statistics, such as the number of bytes and packets sent and received. This parameter can be combined with **-s**. |
| -n | Displays active TCP connections, however, addresses and port numbers are expressed numerically and no attempt is made to determine names. |
| -o | Displays active TCP connections and includes the process ID (PID) for each connection. You can find the application based on the PID on the Processes tab in Windows Task Manager. This parameter can be combined with **-a**, **-n**, and **-p**. |
| -p `<Protocol>` | Shows connections for the protocol specified by *Protocol*. In this case, the *Protocol* can be tcp, udp, tcpv6, or udpv6. If this parameter is used with **-s** to display statistics by protocol, *Protocol* can be tcp, udp, icmp, ip, tcpv6, udpv6, icmpv6, or ipv6. |
| -s | Displays statistics by protocol. By default, statistics are shown for the TCP, UDP, ICMP, and IP protocols. If the IPv6 protocol is installed, statistics are shown for the TCP over IPv6, UDP over IPv6, ICMPv6, and IPv6 protocols. The **-p** parameter can be used to specify a set of protocols. |
| -r | Displays the contents of the IP routing table. This is equivalent to the route print command. |
| `<interval>` | Redisplays the selected information every *interval* seconds. Press CTRL+C to stop the redisplay. If this parameter is omitted, this command prints the selected information only once. |
| /? | Displays help at the command prompt. |

##### Remarks

- The **netstat** command provides statistics for the following:

    | Parameter | Description |
    | --------- | ----------- |
    | Proto | The name of the protocol (TCP or UDP). |
    | Local address | The IP address of the local computer and the port number being used. The name of the local computer that corresponds to the IP address and the name of the port is shown unless the **-n** parameter is specified. If the port is not yet established, the port number is shown as an asterisk (*). |
    | Foreign address | The IP address and port number of the remote computer to which the socket is connected. The names that corresponds to the IP address and the port are shown unless the **-n** parameter is specified. If the port is not yet established, the port number is shown as an asterisk (*). |
    | State | Indicates the state of a TCP connection, including:<ul><li>CLOSE_WAIT</li><li>CLOSED</li><li>ESTABLISHED</li><li>FIN_WAIT_1</li><li>FIN_WAIT_2</li><li>LAST_ACK</li><li>LISTEN</li><li>SYN_RECEIVED</li><li>SYN_SEND</li><li>TIMED_WAIT</li></ul> |

#### Examples

To display both the Ethernet statistics and the statistics for all protocols, type:

```
netstat -e -s
```

To display the statistics for only the TCP and UDP protocols, type:

```
netstat -s -p tcp udp
```

To display active TCP connections and the process IDs every 5 seconds, type:

```
netstat -o 5
```

To display active TCP connections and the process IDs using numerical form, type:

```
netstat -n -o
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


