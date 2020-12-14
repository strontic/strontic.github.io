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
MD5 | `21A491ECAB4340C7E6B6A805405BA1B5`
SHA1 | `A511B97672EE1C05566261F4D35DCC90A0129782`
SHA256 | `5A5E71245F9FC0D109452FE867192CEAE3CFE7803950EAB2F4E0A7BDA8677DD4`
SHA384 | `5EA888E15E0298182FE0859BDF42C8904D9F7C3ABFCAA6B7384F69F12577309BCA1CA2225B1C80CBD20BC0FF81490994`
SHA512 | `9E01F02564602E38A5C6BD6F972CBD9574D99ABC5DD2379A1D1073196FE30D9AF19A2439C6C9F0D7AA51ABBE1E65ECEC53FC83722EAF3882EA1752731D4B0EC1`
SSDEEP | `1536:yGfEpBuoiTpD/r5CFfk7nVGMTwH+f4J7YWojB9fE5SZVqKwdUn2qfMp:CmtTduk7VGMTwH+6UWojB9Vm3+3fc`
IMP | `D5EBB7E1938F5C766EEEFA65BF1A291C`
PESHA1 | `FEEE09027EA7BE4D440E170FC5BADED997D823E5`
PE256 | `3C35C1FD8D6837D10B7CFBA6A254738E28AC96B796CED33624CC09F7A0105A83`

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
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\PktMon.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


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
* File Version: 10.0.17763.1490 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1490
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `PktMon.exe` being misused. While `PktMon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pcap_drivers.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_pcap_drivers.yml) | `- '*pktmon*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `Name: Pktmon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Command: pktmon.exe start --etw` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `Description: Will start a packet capture and store log file as PktMon.etl. Use pktmon.exe stop` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Command: pktmon.exe filter add -p 445` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Path: c:\windows\system32\pktmon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `- Path: c:\windows\syswow64\pktmon.exe` | 



MIT License. Copyright (c) 2020 Strontic.


