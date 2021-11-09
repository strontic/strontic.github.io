---
title: ARP.EXE | TCP/IP Arp Command
excerpt: What is ARP.EXE?
---

# ARP.EXE 

* File Path: `C:\WINDOWS\system32\ARP.EXE`
* Description: TCP/IP Arp Command

## Hashes

Type | Hash
-- | --
MD5 | `EDEB2C55DA5EB57E1091E2A50C569BAC`
SHA1 | `6D9AEF14B580AA828CDFB8D7BB8ED895410A8632`
SHA256 | `C9D31C0AD9959134C37139A106EF90D2FF492214FC583CFF6F4239CA8D80CD19`
SHA384 | `68F23D52BCC8D781CCB0D53CE937FCE0379892B8D9A7B64646B5E4667044A639973A1A824B8E18D81900FE8A99F61D6E`
SHA512 | `B4BC871D5A9A1B099B078075CE18FF49897A16EA9B1B23F4F6090535525185A381C5D02E4DA8055AB19B65E39B0B24CFB46FC54595F18B46DB623841EDA09133`
SSDEEP | `384:y5gwlC27QiTWXYm09ADkEvPmQI+zk8tOeILds2YxKKscBfK46SmjLEI5yMOWS+mW:y5blCJiiokZJTk9dBKscByVSmjH531`
IMP | `48A4D83E58F21E6758C9F94526FBB940`
PESHA1 | `286375BCBE1DE9A95F6357A1CE3DCDA40B976FDF`
PE256 | `450D0522012915E736C388B5256DAC6112AF5CCAE80F05DB0223D503EDCEF374`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\ARP.EXE |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: arp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/c9d31c0ad9959134c37139a106ef90d2ff492214fc583cff6f4239ca8d80cd19/detection


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


