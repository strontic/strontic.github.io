---
title: PING.EXE | TCP/IP Ping Command
excerpt: What is PING.EXE?
---

# PING.EXE 

* File Path: `C:\windows\SysWOW64\PING.EXE`
* Description: TCP/IP Ping Command

## Hashes

Type | Hash
-- | --
MD5 | `60DD39FE21BF99A2F1549A8DDB23D962`
SHA1 | `FC104193FB0151AC127BF76EF2D476FD6C03D4BE`
SHA256 | `E3CD6A30D8EEA5BA802A453C9FF6225625A61074323E956FB04854E2F3EB627E`
SHA384 | `AA020A5D242153E737B170587C52CE3CF04E1A2131225BC561B9B17DE13F5381327A0FE302CB86B7FF4A0FFEBE4A6FE8`
SHA512 | `3A0B5E1A2C895862BFBE169DF6B50C70E3FFE01E9EA6AE57EC37E1CC567252E85B41DFE99BD9B424E272509193772DD5B3671A3FD6D867FCFD6F2862A40E7B40`
SSDEEP | `384:XjixTgsPP56i9BilW843qe4h3HUXZ37O5PNEm6uwEWjlWM:4kibiM843D4hXCgORuqJ`

## Signature

* Status: The file C:\windows\SysWOW64\PING.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ping.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `PING.EXE` being misused. While `PING.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_qbot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_qbot.yml) | `CommandLine: '* /c ping.exe -n 6 127.0.0.1 & type *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- ping.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ping_hex_ip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ping_hex_ip.yml) | `- '\ping.exe 0x'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ping_hex_ip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ping_hex_ip.yml) | `- 'ping.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\ping.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $a7="ping.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ping

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Verifies IP-level connectivity to another TCP/IP computer by sending Internet Control Message Protocol (ICMP) echo Request messages. The receipt of corresponding echo Reply messages are displayed, along with round-trip times. ping is the primary TCP/IP command used to troubleshoot connectivity, reachability, and name resolution. Used without parameters, this command displays Help content.

You can also use this command to test both the computer name and the IP address of the computer. If pinging the IP address is successful, but pinging the computer name isn't, you might have a name resolution problem. In this case, make sure the computer name you are specifying can be resolved through the local Hosts file, by using Domain Name System (DNS) queries, or through NetBIOS name resolution techniques.

> [!NOTE]
> This command is available only if the Internet Protocol (TCP/IP) is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
ping [/t] [/a] [/n <count>] [/l <size>] [/f] [/I <TTL>] [/v <TOS>] [/r <count>] [/s <count>] [{/j <hostlist> | /k <hostlist>}] [/w <timeout>] [/R] [/S <Srcaddr>] [/4] [/6] <targetname>
```

#### Parameters

| Parameter | Description |
|:--:|---|
| /t | Specifies ping continue sending echo Request messages to the destination until interrupted. To interrupt and display statistics, press CTRL+ENTER. To interrupt and quit this command, press CTRL+C. |
| /a | Specifies reverse name resolution be performed on the destination IP address. If this is successful, ping displays the corresponding host name. |
| /n `<count>` | Specifies the number of echo Request messages be sent. The default is 4. |
| /l `<size>` | Specifies the length, in bytes, of the **Data** field in the echo Request messages. The default is 32. The maximum size is 65,527. |
| /f | Specifies that echo Request messages are sent with the **Do not Fragment** flag in the IP header set to 1 (available on IPv4 only). The echo Request message can't be fragmented by routers in the path to the destination. This parameter is useful for troubleshooting path Maximum Transmission Unit (PMTU) problems. |
| /I `<TTL>` | Specifies the value of the Time To Live (TTL) field in the IP header for echo Request messages sent. The default is the default TTL value for the host. The maximum *TTL* is 255. |
| /v `<TOS>` | Specifies the value of the Type Of Service (TOS) field in the IP header for echo Request messages sent (available on IPv4 only). The default is 0. *TOS* is specified as a decimal value from 0 through 255. |
| /r `<count>` | Specifies the **Record Route** option in the IP header is used to record the path taken by the echo Request message and corresponding echo Reply message (available on IPv4 only). Each hop in the path uses an entry in the **Record Route** option. If possible, specify a *count* equal to or greater than the number of hops between the source and destination. The *count* must be a minimum of 1 and a maximum of 9. |
| /s `<count>` | Specifies that the **Internet timestamp** option in the IP header is used to record the time of arrival for the echo Request message and corresponding echo Reply message for each hop. The *count* must be a minimum of 1 and a maximum of 4. This is required for link-local destination addresses. |
| /j `<hostlist>` | Specifies the echo Request messages use the **Loose Source Route** option in the IP header with the set of intermediate destinations specified in *hostlist* (available on IPv4 only). With loose source routing, successive intermediate destinations can be separated by one or multiple routers. The maximum number of addresses or names in the host list is 9. The host list is a series of IP addresses (in dotted decimal notation) separated by spaces. |
| /k `<hostlist>` | Specifies the echo Request messages use the **Strict Source Route** option in the IP header with the set of intermediate destinations specified in *hostlist* (available on IPv4 only). With strict source routing, the next intermediate destination must be directly reachable (it must be a neighbor on an interface of the router). The maximum number of addresses or names in the host list is 9. The host list is a series of IP addresses (in dotted decimal notation) separated by spaces. |
| /w `<timeout>` | Specifies the amount of time, in milliseconds, to wait for the echo Reply message corresponding to a given echo Request message. If the echo Reply message is not received within the time-out, the "Request timed out" error message is displayed. The default time-out is 4000 (4 seconds). |
| /R | Specifies the round-trip path is traced (available on IPv6 only). |
| /S `<Srcaddr>` | Specifies the source address to use (available on IPv6 only). |
| /4 | Specifies IPv4 used to ping. This parameter is not required to identify the target host with an IPv4 address. It is only required to identify the target host by name. |
| /6 | Specifies IPv6 used to ping. This parameter is not required to identify the target host with an IPv6 address. It is only required to identify the target host by name. |
| `<targetname>` | Specifies the host name or IP address of the destination. |
| /? | Displays help at the command prompt. |

#### Example of the ping command output

```
C:\>ping example.microsoft.com
    pinging example.microsoft.com [192.168.239.132] with 32 bytes of data:
    Reply from 192.168.239.132: bytes=32 time=101ms TTL=124
    Reply from 192.168.239.132: bytes=32 time=100ms TTL=124
    Reply from 192.168.239.132: bytes=32 time=120ms TTL=124
    Reply from 192.168.239.132: bytes=32 time=120ms TTL=124
```

#### Examples

To ping the destination 10.0.99.221 and resolve 10.0.99.221 to its host name, type:

```
ping /a 10.0.99.221
```

To ping the destination 10.0.99.221 with 10 echo Request messages, each of which has a Data field of 1000 bytes, type:

```
ping /n 10 /l 1000 10.0.99.221
```

To ping the destination 10.0.99.221 and record the route for 4 hops, type:

```
ping /r 4 10.0.99.221
```

To ping the destination 10.0.99.221 and specify the loose source route of 10.12.0.1-10.29.3.1-10.1.44.1, type:

```
ping /j 10.12.0.1 10.29.3.1 10.1.44.1 10.0.99.221
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


