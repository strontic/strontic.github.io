---
title: MsCtfMonitor.dll | MsCtfMonitor DLL
excerpt: What is MsCtfMonitor.dll?
---

# MsCtfMonitor.dll 

* File Path: `C:\Windows\system32\MsCtfMonitor.dll`
* Description: MsCtfMonitor DLL

## Hashes

Type | Hash
-- | --
MD5 | `3B7C928681C98C6CF44DA5EE7EE92AF8`
SHA1 | `5C9185C15FCF22FC8DF5A71CD75B73094E6D54A5`
SHA256 | `71B11EC18954B3BA6E48581CF1AF69029438E760EA2550EB963A4FF89E396F96`
SHA384 | `44BFF158866C9F6A7885D912ECAB5AD9F51BDBD0C253787AD7AF1A4F4625186AF7FB988AF9598EE093063FC12E6C64F1`
SHA512 | `62249398DC833E582B4F07AA781A4E55EFAD3BD3CCA7D5DBCC6426BD67ADD55A3371E433455123BAF447B248478E6D2D569B4413BA9AE0AFC6501CA0B65F71D7`
SSDEEP | `1536:fbFoCFE+N5fGYzsy7wBemJLiVAUDuoWv6hng/1mGS5QpPnnd/1mtM2i8H:fBoZQ37wAmJLiT2kQkQhnnDUM2r`
IMP | `06EDB9209B964ABE61CD9B6942DEA085`
PESHA1 | `1C30BF18FD8DADD6252817114D42010E4F040EA2`
PE256 | `4E48673F772933367CE69BE6AF585D934EAF14C079B60B494A455D1931183FC0`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x000000018000fb10 | 0x0000fb10
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x00000001800070d0 | 0x000070d0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x000000018000fb30 | 0x0000fb30
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x000000018000fd50 | 0x0000fd50
`DoMsCtfMonitor` | 5 (0x5) | Exported Function | 0x00000001800033f0 | 0x000033f0
`InitLocalMsCtfMonitor` | 6 (0x6) | Exported Function | 0x0000000180010260 | 0x00010260
`UninitLocalMsCtfMonitor` | 7 (0x7) | Exported Function | 0x0000000180010350 | 0x00010350


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsCtfMonitor.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/71b11ec18954b3ba6e48581cf1af69029438e760ea2550eb963a4ff89e396f96/detection/


## Possible Misuse

*The following table contains possible examples of `MsCtfMonitor.dll` being misused. While `MsCtfMonitor.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `1D56BAB28793E3AB96E390F09F02425E52E28FFC` \| MsCtfMonitor.dll \| Amavaldo injector             \| Win32/Spy.Amavaldo.U trojan            \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `B761D9216C00F5E2871DE16AE157DE13C6283B5D` \| MsCtfMonitor     \| Amavaldo banking trojan       \| Win32/Spy.Amavaldo.N trojan            \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `- `%LocalAppData%\%RAND%\MsCtfMonitor[.dll]`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


