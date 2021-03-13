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
MD5 | `517FB5EA3CCDD04019936F2DB8782407`
SHA1 | `D21CF898CE3F4849F2B7691DEE78F47D74DC5021`
SHA256 | `927B2E0B365D53668A31BE9B20AD284239FAF3EDA57A991CA479BB1B14AF9941`
SHA384 | `54CA0BD34D9B08B689E630D2CD4326084F9337EDC32CEA355506710977AB753766F532FD201E6A268C61967AE8AC5F78`
SHA512 | `E96CC3DCE9A8E6730E44BF4EB13AEA9F334B915A1BA1D326F8F637E332C2422959DB82C8EF34722D033ED3E6554A44E596F58D50DDA141634B4FA594EDC8F909`
SSDEEP | `6144:4rt+X+KOk5HDcCTaEXHRDtaUdK22PbB+tb1VAO7ycY/3mZduvh:WU+Zk5jdTaEXHRDAUD2PbB+rVAOuc833`
IMP | `11E8AE0C5BCFD0E994EC39E1738B8D1B`
PESHA1 | `D4391ECBE0D1DD41F34CA7A5436AF0986D68950E`
PE256 | `2F6433737F166343416F656500B997A4B9499F0F23B37BE26C9C5C073AB536CA`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/927b2e0b365d53668a31be9b20ad284239faf3eda57a991ca479bb1b14af9941/detection/


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


