---
title: version.dll | Version Checking and File Installation Libraries
excerpt: What is version.dll?
---

# version.dll 

* File Path: `C:\Windows\SysWOW64\version.dll`
* Description: Version Checking and File Installation Libraries

## Hashes

Type | Hash
-- | --
MD5 | `D88DF43A86F4A7C1ED4138CCDACD43BF`
SHA1 | `E0CB860A97BC786E4B0168870DFBD87DAE761846`
SHA256 | `38554296445A91E68DBDB96D895D202F9A0A2E625EB28A6A589C2FD5325B2452`
SHA384 | `B95A14B2663EE7CECDBB72110B932798015B5DC316364EA746D23F56CEE1C68A249D9FDB1D13D2619A43D8F8C397A607`
SHA512 | `F13FFA3853C2EADBE6DFDEE7C3B70467B5AA6A5A9FADAB071176AEAB4EC5D22F693616C4D2BEAE7468D522F26BFBCA5B74594BF1B23A80130B071ABC98AAFC8B`
SSDEEP | `768:C6WhkiLS5Dqb9XrFDImckVPxIiTOC7xqMwwyJ2XlzxA3v9DCI1PgW:C6AkiLS5Dqb9imckVPxIiTLqMwT2Xlzu`
IMP | `950BA747DF1E77DF20CA4983A22E450B`
PESHA1 | `9845199E020B74BA6744DC5A7F978034C79904FC`
PE256 | `E06AA9DD84D1EEE466E97A950442DF88F707877BC3516C36EDBD643197392D1B`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/38554296445a91e68dbdb96d895d202f9a0a2e625eb28a6a589c2fd5325b2452/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\version.dll](version.dll-9B7352ED51D3A31D617A84A616771865.md) | 58

## Possible Misuse

*The following table contains possible examples of `version.dll` being misused. While `version.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s4 = "VERSION.DLL" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


