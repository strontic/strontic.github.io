---
title: WSHTCPIP.DLL | Winsock2 Helper DLL (TL/IPv4)
excerpt: What is WSHTCPIP.DLL?
---

# WSHTCPIP.DLL 

* File Path: `C:\Windows\system32\WSHTCPIP.DLL`
* Description: Winsock2 Helper DLL (TL/IPv4)

## Hashes

Type | Hash
-- | --
MD5 | `39B42416F5597830FC51E310CA8D3726`
SHA1 | `5B8FA75D8AFB003950319500DC396C1A588AED9F`
SHA256 | `A59F24B003CB3459E458886DAB5C89AAEAE3540E4593D0B71C029B6F4420C94A`
SHA384 | `2700A9560D2034E5939E5D06A777C0735116A75FCDC69B02926FFC93A0D3186CD320071552B7FE8F1456A3A71ED43318`
SHA512 | `97808FAA5CFADCA7AAAD4335493E24D1864F1325415EAB2114E422C8C04402652A45B96E9D2A053945379730E5F7921A95596E28B683378BC77A0BACE2AA6E7A`
SSDEEP | `96:CgIl+RfwWCCxt3CpZbssOR9FpfeILj49iO3GowWrITrquGQA0HEWkDWwD:vi+Rfwmx2zu9FljLwiO3+JGQAvWkDWC`
IMP | `81AF26DA75B32F0CDF22D424213BB9A6`
PESHA1 | `253F5A0D74037CD01DF7DBC7782CC6D4C3C0CC12`
PE256 | `B88CB460AF6DD063656A070E6E62980C0D5DF3372E7BE9FAD79C413868477B67`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WSHJoinLeaf` | 11 | Exported Function
`WSHNotify` | 12 | Exported Function
`WSHGetWSAProtocolInfo` | 7 | Exported Function
`WSHIoctl` | 10 | Exported Function
`WSHSetSocketInformation` | 15 | Exported Function
`WSHStringToAddress` | 16 | Exported Function
`WSHOpenSocket` | 13 | Exported Function
`WSHOpenSocket2` | 14 | Exported Function
`WSHGetBroadcastSockaddr` | 3 | Exported Function
`WSHGetProviderGuid` | 4 | Exported Function
`WSHAddressToString` | 1 | Exported Function
`WSHEnumProtocols` | 2 | Exported Function
`WSHGetWildcardSockaddr` | 8 | Exported Function
`WSHGetWinsockMapping` | 9 | Exported Function
`WSHGetSockaddrType` | 5 | Exported Function
`WSHGetSocketInformation` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wshtcpip.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a59f24b003cb3459e458886dab5c89aaeae3540e4593d0b71c029b6f4420c94a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\WSHTCPIP.DLL](WSHTCPIP.DLL-725D26E089FE15C98C2211075F729CEC.md) | 35

## Possible Misuse

*The following table contains possible examples of `WSHTCPIP.DLL` being misused. While `WSHTCPIP.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "wshtcpip.WSHGetSocketInformation" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


