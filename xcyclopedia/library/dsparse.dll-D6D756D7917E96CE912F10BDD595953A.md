---
title: dsparse.dll | Active Directory Domain Services API
excerpt: What is dsparse.dll?
---

# dsparse.dll 

* File Path: `C:\Windows\system32\dsparse.dll`
* Description: Active Directory Domain Services API

## Hashes

Type | Hash
-- | --
MD5 | `D6D756D7917E96CE912F10BDD595953A`
SHA1 | `1D76FF6C41C0EAAA33B05F3CB376DC343BCDC310`
SHA256 | `7934D5D32AC18D26554A6C514CF695E9F10B68123D3EB95D75246EF3FB5CC68D`
SHA384 | `0D46C34D8F888A941B5E8C9DF7D46F219BB69AF0AB561DCDCF6695B8AA1DC59A1972423E4C94A52BC07BC2CDB9B83215`
SHA512 | `7128DA1E494CB1662C7C45FC5CF669C6EE977375DFCF69C34E563DC101749427FE0BA51BA28C16A485045D1155EC624309751F4A4EDF26B6DD3DAE17D1CE8DA6`
SSDEEP | `384:KadmLSxHsOVScBHhqgTsI0JPCmN29fPf0ns7JBzeFLC79Iq7tletze9YVBWRTW:K6WC7XB0JPO3Ms7JBawpDpYV0`
IMP | `9A9C4538A005317892C0CB85CB9685FE`
PESHA1 | `C1B238000699FC8F1BF693481A8D1A0B293D9C1B`
PE256 | `8A5C34E216FD1861E1C0A589796EF8BE37FB33B72C98DACAAEACD0E8CB81E0A3`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DsCrackSpn2A` | 1 (0x1) | Exported Function | 0x0000000180002680 | 0x00002680
`DsQuoteRdnValueW` | 18 (0x12) | Exported Function | 0x00000001800045d0 | 0x000045d0
`DsQuoteRdnValueA` | 17 (0x11) | Exported Function | 0x0000000180004440 | 0x00004440
`DsMakeSpnW` | 16 (0x10) | Exported Function | 0x0000000180003840 | 0x00003840
`DsMakeSpnA` | 15 (0xf) | Exported Function | 0x0000000180003610 | 0x00003610
`DsMakeSpn2W` | 14 (0xe) | Exported Function | 0x0000000180003320 | 0x00003320
`DsIsMangledRdnValueW` | 13 (0xd) | Exported Function | 0x0000000180004390 | 0x00004390
`DsIsMangledRdnValueA` | 12 (0xc) | Exported Function | 0x0000000180004310 | 0x00004310
`DsIsMangledDnW` | 11 (0xb) | Exported Function | 0x0000000180004290 | 0x00004290
`DsIsMangledDnA` | 10 (0xa) | Exported Function | 0x0000000180004220 | 0x00004220
`DsGetRdnW` | 9 (0x9) | Exported Function | 0x00000001800041b0 | 0x000041b0
`DsCrackUnquotedMangledRdnW` | 8 (0x8) | Exported Function | 0x0000000180004110 | 0x00004110
`DsCrackUnquotedMangledRdnA` | 7 (0x7) | Exported Function | 0x0000000180004080 | 0x00004080
`DsCrackSpnW` | 6 (0x6) | Exported Function | 0x00000001800030f0 | 0x000030f0
`DsCrackSpnA` | 5 (0x5) | Exported Function | 0x0000000180002db0 | 0x00002db0
`DsCrackSpn4W` | 4 (0x4) | Exported Function | 0x0000000180002b50 | 0x00002b50
`DsCrackSpn3W` | 3 (0x3) | Exported Function | 0x00000001800029e0 | 0x000029e0
`DsCrackSpn2W` | 2 (0x2) | Exported Function | 0x0000000180001010 | 0x00001010
`DsUnquoteRdnValueA` | 19 (0x13) | Exported Function | 0x0000000180004640 | 0x00004640
`DsUnquoteRdnValueW` | 20 (0x14) | Exported Function | 0x00000001800047d0 | 0x000047d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsparse.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/63
* VirusTotal Link: https://www.virustotal.com/gui/file/7934d5d32ac18d26554a6c514cf695e9f10b68123d3eb95d75246ef3fb5cc68d/detection/


## Possible Misuse

*The following table contains possible examples of `dsparse.dll` being misused. While `dsparse.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_office_dsparse_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_office_dsparse_dll_load.yml) | `description: Detects DSParse DLL being loaded by an Office Product` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_office_dsparse_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_office_dsparse_dll_load.yml) | `- '*\dsparse.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


