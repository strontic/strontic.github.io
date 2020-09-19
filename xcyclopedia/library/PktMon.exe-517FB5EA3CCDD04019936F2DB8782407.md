---
title: PktMon.exe | Packet Monitor
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


## Possible Misuse

*The following table contains possible examples of `PktMon.exe` being misused. While `PktMon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pcap_drivers.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_pcap_drivers.yml) | `          - '*pktmon*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `Name: Pktmon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `  - Command: pktmon.exe start --etw` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `    Description: Will start a packet capture and store log file as PktMon.etl. Use pktmon.exe stop` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `  - Command: pktmon.exe filter add -p 445` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `  - Path: c:\windows\system32\pktmon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pktmon.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pktmon.yml) | `  - Path: c:\windows\syswow64\pktmon.exe` | 



MIT License. Copyright (c) 2020 Strontic.


