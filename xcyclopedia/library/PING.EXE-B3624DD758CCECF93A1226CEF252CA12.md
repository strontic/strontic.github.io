---
title: PING.EXE | TCP/IP Ping Command
excerpt: What is PING.EXE?
---

# PING.EXE 

* File Path: `C:\Windows\SysWOW64\PING.EXE`
* Description: TCP/IP Ping Command

## Hashes

Type | Hash
-- | --
MD5 | `B3624DD758CCECF93A1226CEF252CA12`
SHA1 | `FCF4DAD8C4AD101504B1BF47CBBDDBAC36B558A7`
SHA256 | `4AAA74F294C15AEB37ADA8185D0DEAD58BD87276A01A814ABC0C4B40545BF2EF`
SHA384 | `4A2C6917CB8EB958DED1BE985F2053B76E2A5AF6E4EEF75C577DD9700A7C63F28867743CF2B0CFA979E14C69FE859566`
SHA512 | `C613D18511B00FA25FC7B1BDDE10D96DEBB42A99B5AAAB9E9826538D0E229085BB371F0197F6B1086C4F9C605F01E71287FFC5442F701A95D67C232A5F031838`
SSDEEP | `384:PVhNH/TqNcx+5tTAjtn3bPcPwoeGULZbiWBlWjVw:PVhZXx+5tTetLVohULZJgw`
IMP | `6C1FE20B3F9688A9263FFDF9FF417272`
PESHA1 | `306AC6B860783CC69BF7915472BCB41FC9A08343`
PE256 | `18AC70758DE5A85B011FCE39F9D27143DA97F9F6DB94127510BF3417C299669B`

## Runtime Data

### Usage (stdout):
```cmhg
Bad option --help.

Usage: ping [-t] [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]
            [-r count] [-s count] [[-j host-list] | [-k host-list]]
            [-w timeout] [-R] [-S srcaddr] [-c compartment] [-p]
            [-4] [-6] target_name

Options:
    -t             Ping the specified host until stopped.
                   To see statistics and continue - type Control-Break;
                   To stop - type Control-C.
    -a             Resolve addresses to hostnames.
    -n count       Number of echo requests to send.
    -l size        Send buffer size.
    -f             Set Don't Fragment flag in packet (IPv4-only).
    -i TTL         Time To Live.
    -v TOS         Type Of Service (IPv4-only. This setting has been deprecated
                   and has no effect on the type of service field in the IP
                   Header).
    -r count       Record route for count hops (IPv4-only).
    -s count       Timestamp for count hops (IPv4-only).
    -j host-list   Loose source route along host-list (IPv4-only).
    -k host-list   Strict source route along host-list (IPv4-only).
    -w timeout     Timeout in milliseconds to wait for each reply.
    -R             Use routing header to test reverse route also (IPv6-only).
                   Per RFC 5095 the use of this routing header has been
                   deprecated. Some systems may drop echo requests if
                   this header is used.
    -S srcaddr     Source address to use.
    -c compartment Routing compartment identifier.
    -p             Ping a Hyper-V Network Virtualization provider address.
    -4             Force using IPv4.
    -6             Force using IPv6.


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\PING.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ping.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/4aaa74f294c15aeb37ada8185d0dead58bd87276a01a814abc0c4b40545bf2ef/detection


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


