---
title: nddeapi.dll | Network DDE Share Management APIs
excerpt: What is nddeapi.dll?
---

# nddeapi.dll 

* File Path: `C:\Windows\system32\nddeapi.dll`
* Description: Network DDE Share Management APIs

## Hashes

Type | Hash
-- | --
MD5 | `1C054CD03325FA2EDD21911C5DD0200E`
SHA1 | `94A657AE4D402EA95A5C50B78AAF6C7C8CF848C5`
SHA256 | `F814BF38AE4F27451BB94ED407E4D686B954E603A1419EB9B8DEFC79F69627F1`
SHA384 | `7354962225C508C88A111BD30BDADFA63D638D061296470CBDB9EC75515D10B8001D34B0F99D127B7627AEEBDFAE1695`
SHA512 | `BED882CDB290EB4079F594B20A7812D71140E4845A8C4A0F5D8D94ED56ACCF44B27BA34979E997C579F467B87413495FE1994129A2E45EF0EFB586C29F9AC46E`
SSDEEP | `96:FnMexiZUNpk2Qo6y0mWHeM/uOXXDioSS4lrjEWUGwbGwWWwJKSDyAAt1BZEVLD:FxTTiy0m+juOnR14l0WVMGzW6yG`
IMP | `5C317B4785C1C3CE395F95788FB0F892`
PESHA1 | `20C59CB0D48753D0055A76D298B944BC55AED659`
PE256 | `DC2F395DA1132DAFC31A5F471A523649593C6D8BC7BFB35BE8FC426F0A26E35C`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/f814bf38ae4f27451bb94ed407e4d686b954e603a1419eb9b8defc79f69627f1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\osuninst.dll](osuninst.dll-F3F8126DF4983A2A1EE8F83AA8F4764F.md) | 50
[C:\Windows\SysWOW64\nddeapi.dll](nddeapi.dll-06062D05857A2A8743E7BBD1CD290255.md) | 43

## Possible Misuse

*The following table contains possible examples of `nddeapi.dll` being misused. While `nddeapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_upatre_oct15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_upatre_oct15.yar) | $s1 = "nddeapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


