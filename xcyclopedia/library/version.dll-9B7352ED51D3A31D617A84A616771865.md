---
title: version.dll | Version Checking and File Installation Libraries
excerpt: What is version.dll?
---

# version.dll 

* File Path: `C:\Windows\system32\version.dll`
* Description: Version Checking and File Installation Libraries

## Hashes

Type | Hash
-- | --
MD5 | `9B7352ED51D3A31D617A84A616771865`
SHA1 | `3671746821D0360F3A9700466036CCDC25A09EAE`
SHA256 | `D517B1461DCD733DDDE25CBC164CCE8DDD50611BA09BCA7D2B02518B4621385B`
SHA384 | `BAB140362467F9DF649845C8224DC7A2D649A08374DA127FB4D19F6284ACA5E10BD2581EA288BBD3467231C50CB42F14`
SHA512 | `21D835BA90AAFC4C41A5C794E40117FA22B745BB6D554F72799DBD680D3540BE9FDF1ACD65CFF216E780A46B53D73CBBB8B908F43DA22BDB2AA525F821BC3AD6`
SSDEEP | `768:crQak8mckVPxIiTCqMwwyg2ulzxAnvdI1P:crW8mckVPxIiTCqMwm2ulzxAnvaP`
IMP | `34340C2C4E9AA6EF6AD12BB695FC695B`
PESHA1 | `6842143ED9F58714AEA3BCFD4158A7B4E9A01746`
PE256 | `B0BEF8E5D3B98663FA5CCA7B6C1890137A0B959B7C7DBF1CF60FAC76808495A0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`VerInstallFileA` | 12 | Exported Function
`VerInstallFileW` | 13 | Exported Function
`VerFindFileA` | 10 | Exported Function
`VerFindFileW` | 11 | Exported Function
`VerQueryValueA` | 16 | Exported Function
`VerQueryValueW` | 17 | Exported Function
`VerLanguageNameA` | 14 | Exported Function
`VerLanguageNameW` | 15 | Exported Function
`GetFileVersionInfoW` | 9 | Exported Function
`GetFileVersionInfoExA` | 3 | Exported Function
`GetFileVersionInfoExW` | 4 | Exported Function
`GetFileVersionInfoA` | 1 | Exported Function
`GetFileVersionInfoByHandle` | 2 | Exported Function
`GetFileVersionInfoSizeExW` | 7 | Exported Function
`GetFileVersionInfoSizeW` | 8 | Exported Function
`GetFileVersionInfoSizeA` | 5 | Exported Function
`GetFileVersionInfoSizeExA` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VERSION.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/d517b1461dcd733ddde25cbc164cce8ddd50611ba09bca7d2b02518b4621385b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\version.dll](version.dll-D88DF43A86F4A7C1ED4138CCDACD43BF.md) | 58

## Possible Misuse

*The following table contains possible examples of `version.dll` being misused. While `version.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s4 = "VERSION.DLL" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


