---
title: PktMon.exe | Packet Monitor
---

# PktMon.exe 

* File Path: `C:\windows\system32\PktMon.exe`
* Description: Packet Monitor

## Hashes

Type | Hash
-- | --
MD5 | `7D0C5B06AC93C8F6078D7B1873D61E64`
SHA1 | `9795F2BD164CCEF159A3E83358380172E9B5DB82`
SHA256 | `A54FC1D12215A624B124AECE0C9C47491B4E3974339C5A395A4AA1C5F4FBB65B`
SHA384 | `78E7FE4D2FC36AE6A15C766F3667A25E09114F6325EFAFB993D51772827CD0DAF7A0BA16245C6BEF57F157687297FF13`
SHA512 | `429D9F49FA0C4242D96DDDB03FAE68350D7BFF02DD8D32D7B40741AC473F7F9CC45D7B03A6F61474DDB6BF07D388914AA91512DE87C4B2609B5283388C802E7E`
SSDEEP | `1536:3BPUgMpBfGzVRwaiYvcDn1W/jQO/415Kt7mjExeFZzuDpTSUn2qfOz:eRE3T9cD1W/jQOm5Kt7m18DI+3fU`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Unknown command '-help'. See pktmon  help.

```

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `PktMon.exe` being misused. While `PktMon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_pcap_drivers.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_pcap_drivers.yml) | `          - '*pktmon*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


