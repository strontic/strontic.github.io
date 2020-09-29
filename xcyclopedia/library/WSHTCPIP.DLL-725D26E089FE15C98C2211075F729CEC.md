---
title: WSHTCPIP.DLL | Winsock2 Helper DLL (TL/IPv4)
excerpt: What is WSHTCPIP.DLL?
---

# WSHTCPIP.DLL 

* File Path: `C:\Windows\SysWOW64\WSHTCPIP.DLL`
* Description: Winsock2 Helper DLL (TL/IPv4)

## Hashes

Type | Hash
-- | --
MD5 | `725D26E089FE15C98C2211075F729CEC`
SHA1 | `86EC33E74B2D28995E8C06FB206D1F207FF4FEAB`
SHA256 | `CAE5E201E8C45040953615664712BACC79080E1728EBEC6C5C3A90A110E3A5EF`
SHA384 | `4C9B27D625903F33489E64584ED417C9ED46EF44790A485401BF960484A519184BD3A52F78F9976FEF643065E01C11EB`
SHA512 | `8967242C28B123D9D2904601B4504AE6E90E70056E0C8AF8D30C128CE0D7F5C3D1E231D53235487ABB7B2E1CDD48E7F5D2BD299AA92E538D4B59EBF93E6465DE`
SSDEEP | `96:SyLLowoOsTx8D0O49NORCnPXqZKOtJQ0i2ITrqitHEWkDWwD:rmT6D03AKOE0F0ttkWkDWC`
IMP | `EAE9953694A44048A279034A8451A4A6`
PESHA1 | `C0B10DEF65FEB3320B0A6DA493EB466BDDB530C8`
PE256 | `AB9723A95408D386A5186BF8AA5C3D18382057664B8BD49D328F8A66228208E8`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WSHAddressToString` | 1 (0x1) | Exported Function | 0x53301bd0 | 0x00001bd0
`WSHEnumProtocols` | 2 (0x2) | Exported Function | 0x53301de0 | 0x00001de0
`WSHGetBroadcastSockaddr` | 3 (0x3) | Exported Function | 0x53301fb0 | 0x00001fb0
`WSHGetProviderGuid` | 4 (0x4) | Exported Function | 0x53302010 | 0x00002010
`WSHGetSockaddrType` | 5 (0x5) | Exported Function | 0x53302070 | 0x00002070
`WSHGetSocketInformation` | 6 (0x6) | Exported Function | 0x53302100 | 0x00002100
`WSHGetWildcardSockaddr` | 8 (0x8) | Exported Function | 0x533021b0 | 0x000021b0
`WSHGetWinsockMapping` | 9 (0x9) | Exported Function | 0x53302220 | 0x00002220
`WSHGetWSAProtocolInfo` | 7 (0x7) | Exported Function | 0x53302150 | 0x00002150
`WSHIoctl` | 10 (0xa) | Exported Function | 0x53302280 | 0x00002280
`WSHJoinLeaf` | 11 (0xb) | Exported Function | 0x53302290 | 0x00002290
`WSHNotify` | 12 (0xc) | Exported Function | 0x53302330 | 0x00002330
`WSHOpenSocket` | 14 (0xe) | Exported Function | 0x53302610 | 0x00002610
`WSHOpenSocket2` | 13 (0xd) | Exported Function | 0x53302380 | 0x00002380
`WSHSetSocketInformation` | 15 (0xf) | Exported Function | 0x53302640 | 0x00002640
`WSHStringToAddress` | 16 (0x10) | Exported Function | 0x53302670 | 0x00002670


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wshtcpip.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/cae5e201e8c45040953615664712bacc79080e1728ebec6c5c3a90a110e3a5ef/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WSHTCPIP.DLL](WSHTCPIP.DLL-39B42416F5597830FC51E310CA8D3726.md) | 35

## Possible Misuse

*The following table contains possible examples of `WSHTCPIP.DLL` being misused. While `WSHTCPIP.DLL` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "wshtcpip.WSHGetSocketInformation" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


