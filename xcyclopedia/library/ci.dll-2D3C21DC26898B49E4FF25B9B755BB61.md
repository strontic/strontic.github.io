---
title: ci.dll | Code Integrity Module
excerpt: What is ci.dll?
---

# ci.dll 

* File Path: `C:\Windows\system32\ci.dll`
* Description: Code Integrity Module

## Hashes

Type | Hash
-- | --
MD5 | `2D3C21DC26898B49E4FF25B9B755BB61`
SHA1 | `8D0C16E18F159CA46CF7EB3FD44874EC9F451E61`
SHA256 | `D11FEE6C6B606E008220A5AC1FAC1DF408AC682893F0ECC453C44AFF2BBDCE39`
SHA384 | `89B06C5266141C7907DE182A0C6595ACAC0BB1C223C428A4F5337290EF535D0B560464B607CA9C89EEFAE776C564210D`
SHA512 | `010DB550883A59BB8DCE71C0FA33A5A84F6CBFDF55B9D50B5497091245E802F7D362D7E2EE8A878EF487CCF74E9A70C569B5D82D4E7BF82F70C49C79458000C3`
SSDEEP | `12288:JoAXXpPmh46bby170h0z4A7mM1gbAkCPbu9EuV1sLXFP9fRba6Q:Jog5Pmh46k+WPa9EubIP9fRb+`
IMP | `A8ACB85055E7F5387B463AA8FC3E2BA5`
PESHA1 | `BB78CEFA2C6C2AE46BFE7B467064CD029F8FD6CB`
PE256 | `19538927B4CA854A61A6AFCC3BA69A91FCDA5851849064709D92C92F13D1CF6D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CiCheckSignedFile` | 4 (0x4) | Exported Function | 0x00000001c0044910 | 0x00044910
`CiFindPageHashesInCatalog` | 5 (0x5) | Exported Function | 0x00000001c00449d0 | 0x000449d0
`CiFindPageHashesInSignedFile` | 6 (0x6) | Exported Function | 0x00000001c0044a50 | 0x00044a50
`CiFreePolicyInfo` | 7 (0x7) | Exported Function | 0x00000001c0044a90 | 0x00044a90
`CiGetCertPublisherName` | 8 (0x8) | Exported Function | 0x00000001c005ff60 | 0x0005ff60
`CiGetPEInformation` | 9 (0x9) | Exported Function | 0x00000001c00447f0 | 0x000447f0
`CiInitialize` | 10 (0xa) | Exported Function | 0x00000001c0043130 | 0x00043130
`CiSetTrustedOriginClaimId` | 11 (0xb) | Exported Function | 0x00000001c0060320 | 0x00060320
`CiValidateFileObject` | 12 (0xc) | Exported Function | 0x00000001c0052dc0 | 0x00052dc0
`CiVerifyHashInCatalog` | 13 (0xd) | Exported Function | 0x00000001c0044890 | 0x00044890
`Ordinal1` | 1 (0x1) | Exported Function | 0x00000001c0053800 | 0x00053800
`Ordinal2` | 2 (0x2) | Exported Function | 0x00000001c005c110 | 0x0005c110
`Ordinal3` | 3 (0x3) | Exported Function | 0x00000001c005c360 | 0x0005c360


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ci.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d11fee6c6b606e008220a5ac1fac1df408ac682893f0ecc453c44aff2bbdce39/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\bcryptprimitives.dll](bcryptprimitives.dll-BE8C33CD5A83B698EEE876403CCC3929.md) | 35
[C:\Windows\system32\BioIso.exe](BioIso.exe-9B0B54FBAC17F4ADE9D0245889912694.md) | 33
[C:\Windows\system32\BioIso.exe](BioIso.exe-CA90DB02AAF23C6D9E81896B63913B85.md) | 36
[C:\Windows\system32\skci.dll](skci.dll-7E88E785DFD6D6A343770C1BADD19D2E.md) | 36

## Possible Misuse

*The following table contains possible examples of `ci.dll` being misused. While `ci.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s1 = "\\sysnative\\CI.dll" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $x2 = "\\sysnative\\CI.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $x3 = "\\SystemRoot\\system32\\CI.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2015_2426.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2015_2426.yar) | $s1 = "\\SystemRoot\\system32\\CI.dll" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2015_2426.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2015_2426.yar) | $s2 = "\\sysnative\\CI.dll" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


