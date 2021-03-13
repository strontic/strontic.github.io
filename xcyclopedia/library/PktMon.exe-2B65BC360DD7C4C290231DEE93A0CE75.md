---
title: PktMon.exe | Packet Monitor
excerpt: What is PktMon.exe?
---

# PktMon.exe 

* File Path: `C:\WINDOWS\system32\PktMon.exe`
* Description: Packet Monitor

## Hashes

Type | Hash
-- | --
MD5 | `2B65BC360DD7C4C290231DEE93A0CE75`
SHA1 | `8A758206BE69385E418E3633970556EE16B167F9`
SHA256 | `395364BAE8EB95FE58397F4B408A1D8BC3205529A375B979409DD9FD0E26A00C`
SHA384 | `91158EE37D5976E479E96A0195869FA26B417934A83319D45D826B1A8730825DCAFE14B96F4EAF2FE46D9707EDAA2F94`
SHA512 | `D2760181E94847A47A4ECAEDE288D12C82BD25EB05FE57881FF1DDDDBDECD106D21DEBC9A8E9399A36D8A3944E8D57BB11FA8CD082FAAA531AF2300AAD46C5D3`
SSDEEP | `3072:uJEmhfWDN/2qhND+jvMEXAxzkFD2D/o2Kwa5wGz+R4dx:5md4R2qhND+jEvxzkFaZs+Rw`

## Runtime Data

### Usage (stdout):
```cmhg
pktmon { filter | comp | reset | start | stop } [OPTIONS | help]
    Monitor internal packet propagation and packet drop reports.

Commands
    filter     Manage packet filters.
    comp       Manage registered components.

    reset      Reset counters to zero.
    start      Start packet monitoring.
    stop       Stop monitoring.
    format     Convert log file to text.
    unload     Unload PktMon driver.

help
    Show help text for a command.


```

### Usage (stderr):
```cmhg
Unknown command '-help'. See pktmon  help.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PktMon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `PktMon.exe` being misused. While `PktMon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pcap_drivers.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_pcap_drivers.yml) | `- '*pktmon*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `Name: Pktmon.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Command: pktmon.exe start --etw`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `Description: Will start a packet capture and store log file as PktMon.etl. Use pktmon.exe stop`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Command: pktmon.exe filter add -p 445`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Path: c:\windows\system32\pktmon.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Path: c:\windows\syswow64\pktmon.exe`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pktmon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows 10, Azure Stack HCI, Azure Stack Hub, Azure

Packet Monitor (Pktmon) is an in-box, cross-component network diagnostics tool for Windows. It can be used for packet capture, drop detection, filtering, and counting. Pktmon is especially helpful in virtualization scenarios such as container networking and SDN, because it provides visibility within the networking stack.

### Syntax

```
pktmon { filter | comp | reset | counters | format | list | start | stop | pcapng | unload | help } [options]
```

#### Commands

| **Command** | **Description** |
| --------- | ----------- |
| [pktmon filter](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-filter.md) | Manage packet filters. |
| [pktmon comp](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-comp.md) | Manage registered components. |
| [pktmon reset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-reset.md) | Reset counters to zero. |
| [pktmon counters](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-counters.md) | Query packet counters. |
| [pktmon format](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-format.md) | Convert log file to text. |
| [pktmon list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-list.md) | List all active components. |
| [pktmon start](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-start.md) | Start packet monitoring. |
| pktmon stop | Stop packet monitoring. |
| [pktmon pcapng](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-pcapng.md) | Convert log file to pcapng format. |
| [pktmon unload](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-unload.md) | Unload pktmon driver. |
| pktmon help | Displays a short summary of subcommands. |

### Additional References

- [Packet Monitor overview](/windows-server/networking/technologies/pktmon/pktmon)
- [Pktmon support for Microsoft Network Monitor (Netmon)](/windows-server/networking/technologies/pktmon/pktmon-netmon-support)

---



MIT License. Copyright (c) 2020-2021 Strontic.


