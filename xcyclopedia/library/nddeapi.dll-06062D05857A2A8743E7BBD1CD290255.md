---
title: nddeapi.dll | Network DDE Share Management APIs
excerpt: What is nddeapi.dll?
---

# nddeapi.dll 

* File Path: `C:\Windows\SysWOW64\nddeapi.dll`
* Description: Network DDE Share Management APIs

## Hashes

Type | Hash
-- | --
MD5 | `06062D05857A2A8743E7BBD1CD290255`
SHA1 | `D16CED9959AEA232DDFCD06450983FE2503261DA`
SHA256 | `CD842273A78BA121BE108A4FFA8D7BCF25823BB1872A859E8AF49D9D6CCFB880`
SHA384 | `C47E1B45ABEB9AB65A47B1E10E171F1FC69AADE18FB811348EC4FF25835C368F61D1EB45F7C08FFBD725371193D4F6CE`
SHA512 | `5673AC7C9A038E1950583EFE6CD464256A115674E298FCF788C5BE498E8891E59D6D1F4F96695B23B2E56473736144692158AEFB78FA8022486E92D75AEB503B`
SSDEEP | `192:KdnuaVyj+ka7Jq3ZR1IzDWVMGzW6yGKSIqR:K5yj+ka7JU1iWVMGzWy`
IMP | `E0BD3263FD5EA99B1D0C2F6F5194CC24`
PESHA1 | `18C55814792858DD2BABD7755F1AA3A169566CB1`
PE256 | `451CCDE4373B865C78B99F134705C6B4103A32FF16D3F456CBB7999FD6C64AB7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`NDdeShareEnumA` | 502 | Exported Function
`NDdeShareEnumW` | 602 | Exported Function
`NDdeShareGetInfoA` | 503 | Exported Function
`NDdeShareDelW` | 601 | Exported Function
`NDdeShareAddA` | 500 | Exported Function
`NDdeShareAddW` | 600 | Exported Function
`NDdeShareDelA` | 501 | Exported Function
`NDdeSpecialCommandW` | 608 | Exported Function
`NDdeTrustedShareEnumA` | 513 | Exported Function
`NDdeTrustedShareEnumW` | 613 | Exported Function
`NDdeSpecialCommandA` | 508 | Exported Function
`NDdeShareGetInfoW` | 603 | Exported Function
`NDdeShareSetInfoA` | 504 | Exported Function
`NDdeShareSetInfoW` | 604 | Exported Function
`NDdeGetTrustedShareA` | 511 | Exported Function
`NDdeGetTrustedShareW` | 611 | Exported Function
`NDdeIsValidAppTopicListA` | 507 | Exported Function
`NDdeGetShareSecurityW` | 609 | Exported Function
`NDdeGetErrorStringA` | 505 | Exported Function
`NDdeGetErrorStringW` | 605 | Exported Function
`NDdeGetShareSecurityA` | 509 | Exported Function
`NDdeSetShareSecurityW` | 610 | Exported Function
`NDdeSetTrustedShareA` | 512 | Exported Function
`NDdeSetTrustedShareW` | 612 | Exported Function
`NDdeSetShareSecurityA` | 510 | Exported Function
`NDdeIsValidAppTopicListW` | 607 | Exported Function
`NDdeIsValidShareNameA` | 506 | Exported Function
`NDdeIsValidShareNameW` | 606 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NDDEAPI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/cd842273a78ba121be108a4ffa8d7bcf25823bb1872a859e8af49d9d6ccfb880/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\nddeapi.dll](nddeapi.dll-1C054CD03325FA2EDD21911C5DD0200E.md) | 43

## Possible Misuse

*The following table contains possible examples of `nddeapi.dll` being misused. While `nddeapi.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_upatre_oct15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_upatre_oct15.yar) | $s1 = "nddeapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


