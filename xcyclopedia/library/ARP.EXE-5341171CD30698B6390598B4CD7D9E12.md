---
title: ARP.EXE | TCP/IP Arp Command
excerpt: What is ARP.EXE?
---

# ARP.EXE 

* File Path: `C:\Windows\SysWOW64\ARP.EXE`
* Description: TCP/IP Arp Command

## Hashes

Type | Hash
-- | --
MD5 | `5341171CD30698B6390598B4CD7D9E12`
SHA1 | `F1E0BACA0D5CC6BB6127E6DE978645F6140CC584`
SHA256 | `C1A71BBB60FAB4B6AF35E9ACCF65D965738DB35E9CFD99BC5F9AE9728DC7CDC8`
SHA384 | `B56D92854D7C592E67BC07C2227CB9B335A9A159F317BAD92987BF1C604D4E100423E4893399167A1B52CCB3096BB63A`
SHA512 | `4658D4AB6C6E02C8E9067CDD9562DC545797FFAB0715B4299464BC691FE364D3C0FB83F7A3D548541FA37C529088A15E2753DF2490DB1BF0934B34B33D1042D1`
SSDEEP | `384:3JwkQCNIdIcUu3Nq3kzCSTHcwdIXzMTRGluYubYWSOmWbp6sb:3JwBmINTzCST8wdXTklu9bDzp6sb`

## Runtime Data

### Usage (stdout):
```cmhg

Displays and modifies the IP-to-Physical address translation tables used by
address resolution protocol (ARP).

ARP -s inet_addr eth_addr [if_addr]
ARP -d inet_addr [if_addr]
ARP -a [inet_addr] [-N if_addr] [-v]

  -a            Displays current ARP entries by interrogating the current
                protocol data.  If inet_addr is specified, the IP and Physical
                addresses for only the specified computer are displayed.  If
                more than one network interface uses ARP, entries for each ARP
                table are displayed.
  -g            Same as -a.
  -v            Displays current ARP entries in verbose mode.  All invalid 
                entries and entries on the loop-back interface will be shown.
  inet_addr     Specifies an internet address.
  -N if_addr    Displays the ARP entries for the network interface specified
                by if_addr.
  -d            Deletes the host specified by inet_addr. inet_addr may be 
                wildcarded with * to delete all hosts.
  -s            Adds the host and associates the Internet address inet_addr
                with the Physical address eth_addr.  The Physical address is
                given as 6 hexadecimal bytes separated by hyphens. The entry
                is permanent.
  eth_addr      Specifies a physical address.
  if_addr       If present, this specifies the Internet address of the
                interface whose address translation table should be modified.
                If not present, the first applicable interface will be used.
Example:
  > arp -s 157.55.85.212   00-aa-00-62-c6-09  .... Adds a static entry.
  > arp -a                                    .... Displays the arp table.

```

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: arp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ARP.EXE` being misused. While `ARP.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- arp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## arp

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays and modifies entries in the Address Resolution Protocol (ARP) cache. The ARP cache contains one or more tables that are used to store IP addresses and their resolved Ethernet or Token Ring physical addresses. There is a separate table for each Ethernet or Token Ring network adapter installed on your computer. Used without parameters, **arp** displays help information.

### Syntax

```
arp [/a [<inetaddr>] [/n <ifaceaddr>]] [/g [<inetaddr>] [-n <ifaceaddr>]] [/d <inetaddr> [<ifaceaddr>]] [/s <inetaddr> <etheraddr> [<ifaceaddr>]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `[/a [<inetaddr>] [/n <ifaceaddr>]` | Displays current arp cache tables for all interfaces. The **/n** parameter is case-sensitive. To display the arp cache entry for a specific IP address, use **arp /a** with the **inetaddr** parameter, where **inetaddr** is an IP address. If **inetaddr** is not specified, the first applicable interface is used. To display the arp cache table for a specific interface, use the **/n ifaceaddr** parameter in conjunction with the **/a** parameter where **inetaddr** is the IP address assigned to the interface. |
| `[/g [<inetaddr>] [/n <ifaceaddr>]` | Identical to **/a**. |
| `[/d <inetaddr> [<ifaceaddr>]` | Deletes an entry with a specific IP address, where **inetaddr** is the IP address. To delete an entry in a table for a specific interface, use the **ifaceaddr** parameter where **ifaceaddr** is the IP address assigned to the interface. To delete all entries, use the asterisk (*) wildcard character in place of **inetaddr**. |
| `[/s <inetaddr> <etheraddr> [<ifaceaddr>]` | Adds a static entry to the arp cache that resolves the IP address **inetaddr** to the physical address **etheraddr**. To add a static arp cache entry to the table for a specific interface, use the **ifaceaddr** parameter where **ifaceaddr** is an IP address assigned to the interface. |
| /? | Displays help at the command prompt. |

#### Remarks

- The IP addresses for **inetaddr** and **ifaceaddr** are expressed in dotted decimal notation.

- The physical address for **etheraddr** consists of six bytes expressed in hexadecimal notation and separated by hyphens (for example, 00-AA-00-4F-2A-9C).

- Entries added with the **/s** parameter are static and do not time out of the arp cache. The entries are removed if the TCP/IP protocol is stopped and started. To create permanent static arp cache entries, place the appropriate **arp** commands in a batch file and use Scheduled Tasks to run the batch file at startup.

### Examples

To display the arp cache tables for all interfaces, type:

```
arp /a
```

To display the arp cache table for the interface that is assigned the IP address *10.0.0.99*, type:

```
arp /a /n 10.0.0.99
```

To add a static arp cache entry that resolves the IP address *10.0.0.80* to the physical address *00-AA-00-4F-2A-9C*, type:

```
arp /s 10.0.0.80 00-AA-00-4F-2A-9C
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


