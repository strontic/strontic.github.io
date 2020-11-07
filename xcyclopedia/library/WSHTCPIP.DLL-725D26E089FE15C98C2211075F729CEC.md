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

Function Name | Ordinal | Type
-- | -- | --
`WSHAddressToString` | 1 | Exported Function
`WSHEnumProtocols` | 2 | Exported Function
`WSHGetBroadcastSockaddr` | 3 | Exported Function
`WSHGetProviderGuid` | 4 | Exported Function
`WSHGetSockaddrType` | 5 | Exported Function
`WSHGetSocketInformation` | 6 | Exported Function
`WSHGetWildcardSockaddr` | 8 | Exported Function
`WSHGetWinsockMapping` | 9 | Exported Function
`WSHGetWSAProtocolInfo` | 7 | Exported Function
`WSHIoctl` | 10 | Exported Function
`WSHJoinLeaf` | 11 | Exported Function
`WSHNotify` | 12 | Exported Function
`WSHOpenSocket` | 14 | Exported Function
`WSHOpenSocket2` | 13 | Exported Function
`WSHSetSocketInformation` | 15 | Exported Function
`WSHStringToAddress` | 16 | Exported Function


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


