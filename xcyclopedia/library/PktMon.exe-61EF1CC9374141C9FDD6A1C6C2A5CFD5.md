---
title: PktMon.exe | Packet Monitor
excerpt: What is PktMon.exe?
---

# PktMon.exe 

* File Path: `C:\Windows\system32\PktMon.exe`
* Description: Packet Monitor

## Hashes

Type | Hash
-- | --
MD5 | `61EF1CC9374141C9FDD6A1C6C2A5CFD5`
SHA1 | `A6588ACF9CE1FD85E37619C4E5B0003EF8AC19B4`
SHA256 | `4714B03FFA5C666572A4AB6B04310A6CA654C3C1C68EDD3696088C238628BBB6`
SHA384 | `E1A6907A1CAADEAF37D018209641C17A06ADBED8854548DF74AB19D41D73379537B3326078FC8BFA048F4952323C7041`
SHA512 | `C64A8770AECE1D48B2D8FEAFCF8B4C2571769DE230BDADD99E5932D556896479021872B754BA37DFF5A985E7811D1542352F22DE06E752E2391C2CFFEAD4DBBB`
SSDEEP | `6144:479vuP6FiiJ33RyDqE2Hhpm5HVOFis83FKjQ0Auk//cYHJRF5JAiIN:Gc64iJnEDqE2HhpAHEis83sQ0AuuccJG`
IMP | `11E8AE0C5BCFD0E994EC39E1738B8D1B`
PESHA1 | `30454E0D37CC435CF63EE94B140F5AC263FF2783`
PE256 | `B445FAC4CC816AC4F8A51A8E3E1F12C99AA4A89E209EE5E3347F5AA40C4BBE72`

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
    pcapng     Convert log file to pcapng format.
    unload     Unload PktMon driver.

help
    Show help text for a command.


```

### Usage (stderr):
```cmhg
Unknown command '--help'. See pktmon  help.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\PktMon.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PktMon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.662 (WinBuild.160101.0800)
* Product Version: 10.0.19041.662
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/4714b03ffa5c666572a4ab6b04310a6ca654c3c1c68edd3696088c238628bbb6/detection


## Possible Misuse

*The following table contains possible examples of `PktMon.exe` being misused. While `PktMon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pcap_drivers.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_pcap_drivers.yml) | `- 'pktmon'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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

>Applies to: Windows Server 2022, Windows Server 2019, Windows 10, Azure Stack HCI, Azure Stack Hub, Azure

Packet Monitor (Pktmon) is an in-box, cross-component network diagnostics tool for Windows. It can be used for advanced packet capture and event collection, drop detection, filtering, and counting. Pktmon is especially helpful in virtualization scenarios such as container networking and SDN, because it provides visibility within the networking stack.

### Syntax

```
pktmon { filter | list | start | stop | status | unload | counters | reset | etl2txt | etl2pcap | hex2pkt | help } [options]
```

#### Commands

| **Command** | **Description** |
| --------- | ----------- |
| [pktmon filter](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-filter.md) | Manage packet filters. |
| [pktmon list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-list.md) | List packet processing components. |
| [pktmon start](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-start.md) | Start packet capture and event collection. |
| pktmon stop | Stop data collection. |
| pktmon status | Query current status. |
| [pktmon unload](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-unload.md) | Unload PktMon driver. |
| [pktmon counters](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-counters.md) | Display current packet counters. |
| [pktmon reset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-reset.md) | Reset packet counters to zero. |
| [pktmon etl2txt](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-format.md) | Convert log file to text format. |
| [pktmon etl2pcap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/pktmon-pcapng.md) | Convert log file to pcapng format. |
| pktmon hex2pkt | Decode packet in hexadecimal format. |
| pktmon help | Show help text for specific command. |

### Additional References

- [Packet Monitor overview](../../networking/technologies/pktmon/pktmon.md)
- [Pktmon support for Microsoft Network Monitor (Netmon)](../../networking/technologies/pktmon/pktmon-netmon-support.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


