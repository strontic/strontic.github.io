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
MD5 | `478018D0678600FA89BD62E1818412A4`
SHA1 | `DE9FD408BB340AA30169C8FB0CF47D20AC4E4BDB`
SHA256 | `D7A5E957EFF4DCE4712C0D9E9D465D803EBF47401DD1AB3BB5DDCDBD15D02C90`
SHA384 | `00F2634D5A4FAE287BE173313343B6D6EF843349EE266EE044ADC8EE0E01B4F8263FBB93233C78556CD48D409EDFD8FE`
SHA512 | `A072B240BDD7D8886BD391D3D844E19087F02ED026299800E85A838168C59E62AD6A3BDFC1C60CAFA9C884432761EEF36B32AE7656796CE35BBC5E1EE604BB99`
SSDEEP | `12288:AKufX4evUvhWD7CM00ZnhDzPU0S6OnQ84xpXCy5rX30gGjcmu:AKufXFMsD7C9YnZzPUlsIMrX32cf`
IMP | `281A85FDC75D91205287F2F638B4CDE1`
PESHA1 | `8F903A13C507FACE1D8FD60F7CD5AFCD07A7AE92`
PE256 | `DFC3909CD18DA1456FCA0BBDDD789AF946F5BBD93E4572A883B879A6DB11EC5D`

## Runtime Data

### Usage (stdout):
```cmhg
pktmon <command> [OPTIONS | help]
    Advanced packet capture and event collection.

Commands
    filter     Manage packet filters.
    list       List packet processing components.

    start      Start packet capture and event collection.
    stop       Stop data collection.
    status     Query current status.
    unload     Unload PktMon driver.

    counters   Display current packet counters.
    reset      Reset packet counters to zero.

    etl2txt    Convert log file to text format.
    etl2pcap   Convert log file to pcapng format.
    hex2pkt    Decode packet in hexadecimal format.

    help       Show help text for specific command.
               Example: pktmon start help


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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PktMon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.906 (WinBuild.160101.0800)
* Product Version: 10.0.19041.906
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d7a5e957eff4dce4712c0d9e9d465d803ebf47401dd1ab3bb5ddcdbd15d02c90/detection


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


