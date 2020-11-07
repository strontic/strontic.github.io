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

Function Name | Ordinal | Type
-- | -- | --
`DsCrackSpn2A` | 1 | Exported Function
`DsQuoteRdnValueW` | 18 | Exported Function
`DsQuoteRdnValueA` | 17 | Exported Function
`DsMakeSpnW` | 16 | Exported Function
`DsMakeSpnA` | 15 | Exported Function
`DsMakeSpn2W` | 14 | Exported Function
`DsIsMangledRdnValueW` | 13 | Exported Function
`DsIsMangledRdnValueA` | 12 | Exported Function
`DsIsMangledDnW` | 11 | Exported Function
`DsIsMangledDnA` | 10 | Exported Function
`DsGetRdnW` | 9 | Exported Function
`DsCrackUnquotedMangledRdnW` | 8 | Exported Function
`DsCrackUnquotedMangledRdnA` | 7 | Exported Function
`DsCrackSpnW` | 6 | Exported Function
`DsCrackSpnA` | 5 | Exported Function
`DsCrackSpn4W` | 4 | Exported Function
`DsCrackSpn3W` | 3 | Exported Function
`DsCrackSpn2W` | 2 | Exported Function
`DsUnquoteRdnValueA` | 19 | Exported Function
`DsUnquoteRdnValueW` | 20 | Exported Function


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


