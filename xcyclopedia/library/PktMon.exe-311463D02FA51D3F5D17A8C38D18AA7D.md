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
MD5 | `311463D02FA51D3F5D17A8C38D18AA7D`
SHA1 | `5D3AE356754E533474687D9E4E93A11E62B84771`
SHA256 | `4874D302422AD10827B3D58CE68DAAAB7E3B99D9CDB0850801F9A00105A4DF56`
SHA384 | `A97D4C3343B7D225D62B8DCC35E692A1F0B916ECB017206F48DED00478F2873B27D8B68699E003EC5880DC91B219DADC`
SHA512 | `C3C6A36BCBDDE7EFE0E25B8BC2302C4415566A87C221CE286BA6E66A8362DEAB2255ACC0D8379E619FA1A172165C90B9DBB44912E095F313241FE094894E8D25`
SSDEEP | `12288:W3f6vYvSTuT6BsC4fkdpzzOofk1UC4ziKenfeysjtY2UwTD:Kf6vYqTQ6BsVfkd0obxSeA2UwTD`
IMP | `2670408E64029DEF5C347AB06CFACCE6`
PESHA1 | `AC02690DD66AB5D9AA68319DA00D3BEDC16E5781`
PE256 | `0695C55349C735B0C8B1C859D7248659EFB85EA8FB165698A25D2C444E21E9B3`

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
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\PktMon.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PktMon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4874d302422ad10827b3d58ce68daaab7e3b99d9cdb0850801f9a00105a4df56/detection


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


