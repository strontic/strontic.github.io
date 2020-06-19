
# PING.EXE 

* File Path: `C:\WINDOWS\SysWOW64\PING.EXE`
* Description: TCP/IP Ping Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `36A1F0BBF757F52C9F051C91D11DE6AA`
SHA1 | `1BA5FE277C64F780BB1307DDF73860BAE015874D`
SHA256 | `09E7534F7703B4E067455F0D83A77EFA28A04C368381C5A0456282A57E801B04`
SHA384 | `98EA48255579136BF4E34FE002995A815B310D0E8281D577C4A3299E3DDF5EFA3259B18EB657C0351B06636F3DCED961`
SHA512 | `135B9038B9017DA387850F24A0E960763F8115E9A5DDD05422BB89129FC6E296173FA18466F89A65EEA5DB621953E9CCC44ADDDE8C8BCB0F8D5E6833B5CDF093`
SSDEEP | `384:ICqLnT9yke5khypn1X5ObPcPQooZJLZbKWAlWz:IlO5khyN1a1oYJLZQE`

## Runtime Data

### Usage (stdout):
```Batchfile
Bad option -help.

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

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ping.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `PING.EXE` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_qbot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_qbot.yml) | `        CommandLine: '* /c ping.exe -n 6 127.0.0.1 & type *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - ping.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ping_hex_ip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ping_hex_ip.yml) | `            - '*\ping.exe 0x*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\ping.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## ping

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

The **ping** command verifies IP-level connectivity to another TCP/IP computer by sending Internet Control Message Protocol (ICMP) echo Request messages. The receipt of corresponding echo Reply messages are displayed, along with round-trip times. ping is the primary TCP/IP command used to troubleshoot connectivity, reachability, and name resolution. Used without parameters,  **ping** displays help.

### Syntax

```
ping [/t] [/a] [/n <Count>] [/l <Size>] [/f] [/I <TTL>] [/v <TOS>] [/r <Count>] [/s <Count>] [{/j <Hostlist> | /k <Hostlist>}] [/w <timeout>] [/R] [/S <Srcaddr>] [/4] [/6] <TargetName>
```

##### Parameters

|Parameter|Description|
|-------|--------|
|/t|Specifies that ping continue sending echo Request messages to the destination until interrupted. To interrupt and display statistics, press CTRL+break. To interrupt and quit **ping**, press CTRL+C.|
|/a|Specifies that reverse name resolution is performed on the destination IP address. If this is successful, ping displays the corresponding host name.|
|/n \<Count\>|Specifies the number of echo Request messages sent. The default is 4.|
|/l \<Size\>|Specifies the length, in bytes, of the Data field in the echo Request messages sent. The default is 32. The maximum Size is 65,527.|
|/f|Specifies that echo Request messages are sent with the Do not Fragment flag in the IP header set to 1 (available on IPv4 only). The echo Request message cannot be fragmented by routers in the path to the destination. This parameter is useful for troubleshooting path Maximum Transmission Unit (PMTU) problems.|
|/I \<TTL\>|Specifies the value of the TTL field in the IP header for echo Request messages sent. The default is the default TTL value for the host. The maximum *TTL* is 255.|
|/v \<TOS\>|Specifies the value of the type of Service (TOS) field in the IP header for echo Request messages sent (available on IPv4 only). The default is 0. *TOS* is specified as a decimal value from 0 through 255.|
|/r \<Count\>|Specifies that the Record Route option in the IP header is used to record the path taken by the echo Request message and corresponding echo Reply message (available on IPv4 only). Each hop in the path uses an entry in the Record Route option. If possible, specify a *Count* that is equal to or greater than the number of hops between the source and destination. The *Count* must be a minimum of 1 and a maximum of 9.|
|/s \<Count\>|Specifies that the Internet timestamp option in the IP header is used to record the time of arrival for the echo Request message and corresponding echo Reply message for each hop. The *Count* must be a minimum of 1 and a maximum of 4. This is required for link-local destination addresses.|
|/j \<Hostlist\>|Specifies that the echo Request messages use the Loose Source Route option in the IP header with the set of intermediate destinations specified in *Hostlist* (available on IPv4 only). With loose source routing, successive intermediate destinations can be separated by one or multiple routers. The maximum number of addresses or names in the host list is 9. The host list is a series of IP addresses (in dotted decimal notation) separated by spaces.|
|/k \<Hostlist\>|Specifies that the echo Request messages use the Strict Source Route option in the IP header with the set of intermediate destinations specified in *Hostlist* (available on IPv4 only). With strict source routing, the next intermediate destination must be directly reachable (it must be a neighbor on an interface of the router). The maximum number of addresses or names in the host list is 9. The host list is a series of IP addresses (in dotted decimal notation) separated by spaces.|
|/w \<timeout\>|Specifies the amount of time, in milliseconds, to wait for the echo Reply message that corresponds to a given echo Request message to be received. If the echo Reply message is not received within the time-out, the "Request timed out" error message is displayed. The default time-out is 4000 (4 seconds).|
|/R|Specifies that the round-trip path is traced (available on IPv6 only).|
|/S \<Srcaddr\>|Specifies the source address to use (available on IPv6 only).|
|/4|Specifies that IPv4 is used to ping. This parameter is not required to identify the target host with an IPv4 address. It is only required to identify the target host by name.|
|/6|Specifies that IPv6 is used to ping. This parameter is not required to identify the target host with an IPv6 address. It is only required to identify the target host by name.|
|\<TargetName\>|Specifies the host name or IP address of the destination.|
|/?|Displays help at the command prompt.|

### Remarks

-   You can use **ping** to test both the computer name and the IP address of the computer. If pinging the IP address is successful, but pinging the computer name is not, you might have a name resolution problem. In this case, ensure that the computer name you are specifying can be resolved through the local Hosts file, by using Domain Name System (DNS) queries, or through NetBIOS name resolution techniques.
-   This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Examples

To shows **ping** command output:

```
C:\>ping example.microsoft.com
         pinging example.microsoft.com [192.168.239.132] with 32 bytes of data:
         Reply from 192.168.239.132: bytes=32 time=101ms TTL=124
         Reply from 192.168.239.132: bytes=32 time=100ms TTL=124
         Reply from 192.168.239.132: bytes=32 time=120ms TTL=124
         Reply from 192.168.239.132: bytes=32 time=120ms TTL=124
```

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


