---
title: PATHPING.EXE | TCP/IP PathPing Command
excerpt: What is PATHPING.EXE?
---

# PATHPING.EXE 

* File Path: `C:\WINDOWS\SysWOW64\PATHPING.EXE`
* Description: TCP/IP PathPing Command

## Hashes

Type | Hash
-- | --
MD5 | `A0387C7955DC95CE0DA914C38AB86555`
SHA1 | `AC3B3651DE4C0D3E742A5FFAF2D59A11E3502C69`
SHA256 | `9100040C100737451E395762AC7DCD9868DE26D57AC8CF540395FBEE2B4EA2CE`
SHA384 | `52529BA38E84A8A98222FFC4302DE21A3F2E7204C731D0737DCFE8AB447270A220FDC74FDF2997EBCEFE3127E02AC644`
SHA512 | `565C576E324904BAF964A1F90BAC9C37FF000D939085DD654A0C196F6A26B0C5BF90D4B4A8948B88F28ABB7B7F43218B63AF9100DD5AE095D9BA6FB8FE2B2DFD`
SSDEEP | `384:Ae/Wzv9fRkRN/Ri/xbx+3jDH+JAvfFmHL7KrSWWAWVO:hWblwNZiBwLwHL7K+q`
IMP | `6B5049D4B4EA566C182DDF4E5F2F0247`
PESHA1 | `E9B4E91402D852D385AAF7981DE788EDB571E98A`
PE256 | `ED1B0CC4FA44D37EF023624F5CACCA43E5689071A7B936CEE2C7D69CAE0A2951`

## Runtime Data

### Usage (stdout):
```cmhg
--help is not a valid command option.

Usage: pathping [-g host-list] [-h maximum_hops] [-i address] [-n] 
                [-p period] [-q num_queries] [-w timeout] 
                [-4] [-6] target_name

Options:
    -g host-list     Loose source route along host-list.
    -h maximum_hops  Maximum number of hops to search for target.
    -i address       Use the specified source address. 
    -n               Do not resolve addresses to hostnames.
    -p period        Wait period milliseconds between pings.
    -q num_queries   Number of queries per hop.
    -w timeout       Wait timeout milliseconds for each reply.
    -4               Force using IPv4.
    -6               Force using IPv6.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\PATHPING.EXE |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pathping.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9100040c100737451e395762ac7dcd9868de26d57ac8cf540395fbee2b4ea2ce/detection


## Possible Misuse

*The following table contains possible examples of `PATHPING.EXE` being misused. While `PATHPING.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\pathping.exe' `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pathping

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Provides information about network latency and network loss at intermediate hops between a source and destination. This command sends multiple echo Request messages to each router between a source and destination, over a period of time, and then computes results based on the packets returned from each router. Because this command displays the degree of packet loss at any given router or link, you can determine which routers or subnets might be having network problems. Used without parameters, this command displays help.

> [!NOTE]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.
>
> Additionally, this command identifies which routers are on the path, same as using the [tracert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/tracert.md). Howevever, this command also sends pings periodically to all of the routers over a specified time period and computes statistics based on the number returned from each.

### Syntax

```
pathping [/n] [/h <maximumhops>] [/g <hostlist>] [/p <Period>] [/q <numqueries> [/w <timeout>] [/i <IPaddress>] [/4 <IPv4>] [/6 <IPv6>][<targetname>]
```

#### Parameters

| Parameter | Description |
|--|--|
| /n | Prevents **pathping** from attempting to resolve the IP addresses of intermediate routers to their names. This might expedite the display of **pathping** results. |
| /h `<maximumhops>` | Specifies the maximum number of hops in the path to search for the target (destination). The default is 30 hops. |
| /g `<hostlist>` | Specifies that the echo Request messages use the **Loose Source Route** option in the IP header with the set of intermediate destinations specified in *hostlist*. With loose source routing, successive intermediate destinations can be separated by one or multiple routers. The maximum number of addresses or names in the host list is **9**. The *hostlist* is a series of IP addresses (in dotted decimal notation) separated by spaces. |
| /p `<period>` | Specifies the number of milliseconds to wait between consecutive pings. The default is 250 milliseconds (1/4 second). This parameter sends individual pings to each intermediate hop. Because of this, the interval between two pings sent to the same hop is *period* multiplied by the number of hops. |
| /q `<numqueries>` | Specifies the number of echo Request messages sent to each router in the path. The default is 100 queries. |
| /w `<timeout>` | Specifies the number of milliseconds to wait for each reply. The default is 3000 milliseconds (3 seconds). This parameter sends multiple pings in parallel. Because of this, the amount of time specified in the *timeout* parameter isn't bounded by the amount of time specified in the *period* parameter for waiting between pings. |
| /i `<IPaddress>` | Specifies the source address. |
| /4 `<IPv4>` | Specifies that pathping uses IPv4 only. |
| /6 `<IPv6>` | Specifies that pathping uses IPv6 only. |
| `<targetname>` | Specifies the destination, which is identified either by IP address or host name. |
| /? | Displays help at the command prompt. |

##### Remarks

- All parameters are case-sensitive.

- To avoid network congestion and to minimize the effects of burst losses, pings should be sent at a sufficiently slow pace.

#### Example of the pathping command output

```
D:\>pathping /n contoso1
Tracing route to contoso1 [10.54.1.196]
over a maximum of 30 hops:
  0  172.16.87.35
  1  172.16.87.218
  2  192.168.52.1
  3  192.168.80.1
  4  10.54.247.14
  5  10.54.1.196
computing statistics for 125 seconds...
            Source to Here   This Node/Link
Hop  RTT    Lost/Sent = Pct  Lost/Sent = Pct  address
  0                                           172.16.87.35
                                0/ 100 =  0%   |
  1   41ms     0/ 100 =  0%     0/ 100 =  0%  172.16.87.218
                               13/ 100 = 13%   |
  2   22ms    16/ 100 = 16%     3/ 100 =  3%  192.168.52.1
                                0/ 100 =  0%   |
  3   24ms    13/ 100 = 13%     0/ 100 =  0%  192.168.80.1
                                0/ 100 =  0%   |
  4   21ms    14/ 100 = 14%     1/ 100 =  1%  10.54.247.14
                                0/ 100 =  0%   |
  5   24ms    13/ 100 = 13%     0/ 100 =  0%  10.54.1.196
Trace complete.
```

When **pathping** is run, the first results list the path. Next, a busy message is displayed for approximately 90 seconds (the time varies by hop count). During this time, information is gathered from all routers previously listed and from the links between them. At the end of this period, the test results are displayed.

In the above sample report, the **This Node/Link**, **Lost/Sent = Pct** and **address** columns show that the link between *172.16.87.218* and *192.168.52.1* is dropping 13% of the packets. The routers at hops 2 and 4 are also dropping packets addressed to them, but this loss doesn't affect their ability to forward traffic that isn't addressed to them.

The loss rates displayed for the links, identified as a vertical bar (**|**) in the **address** column, indicate link congestion that is causing the loss of packets that are being forwarded on the path. The loss rates displayed for routers (identified by their IP addresses) indicate that these routers might be overloaded.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [tracert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/tracert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


