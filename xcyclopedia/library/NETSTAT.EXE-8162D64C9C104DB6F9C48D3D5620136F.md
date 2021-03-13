---
title: NETSTAT.EXE | TCP/IP Netstat Command
excerpt: What is NETSTAT.EXE?
---

# NETSTAT.EXE 

* File Path: `C:\windows\SysWOW64\NETSTAT.EXE`
* Description: TCP/IP Netstat Command

## Hashes

Type | Hash
-- | --
MD5 | `8162D64C9C104DB6F9C48D3D5620136F`
SHA1 | `77550AD626BBA9DA9C354AA410C1829F35D0602F`
SHA256 | `020D818A559A554EC18AB66779DB4AA756CABA7412F0454041A4923FBB34A1A9`
SHA384 | `3CBD967A03DEFA0202B4BE8A60B61FCC707B683D57474104AC84F53095EBBE53EDFDA2E51DD541681A95A514755F63CF`
SHA512 | `542B0338244BCA8F3D6C5962764F5F35EC923A84ADFC13B2FD51B6A636AE555438E3E3886B51BE392B933584B28BF4319D3A97751345F5220B2C1B380630A038`
SSDEEP | `768:cMA18zvJ3ULUSZtqUEWqb1hxCn8vl8GZef/cLozK+73Q:tA18zvJ3ULUSZtqTb1hQn8vl84ef0LCW`

## Signature

* Status: The file C:\windows\SysWOW64\NETSTAT.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: netstat.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.18202 (winblue_ltsb.160119-0600)
* Product Version: 6.3.9600.18202
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `NETSTAT.EXE` being misused. While `NETSTAT.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | description = "Chinese Hacktool Set - file netstat.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## netstat

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


