---
title: TSpkg.dll | Web Service Security Package
excerpt: What is TSpkg.dll?
---

# TSpkg.dll 

* File Path: `C:\Windows\SysWOW64\TSpkg.dll`
* Description: Web Service Security Package

## Hashes

Type | Hash
-- | --
MD5 | `1641118D4A2F221CE79DF2772AF8026E`
SHA1 | `C84F10DF9AEC8868ED94B012542569037E04DCF8`
SHA256 | `40F3FFCC134DB81BF54AD0AFB4A9FED95C28B5D1A8E5A7A18DE6CBB0DB075CB7`
SHA384 | `1AB012B2E7EA09A9E29BEEBC422F81645837047FFC53439631AB5FCA7111164FF7CA51696A08152C1E147F12CB3D1B23`
SHA512 | `0D2D523A169195AE819595453B206698567C738E00C332B54A1BB4311F214A9281E46AC8D49687398E48F6D9EE45E03BDCCBBE9E019E7AA2788AC9989F67174B`
SSDEEP | `3072:I4VVla0dDc3diWqsFUbEfmroR7wMUQRIzfk3JlDP3+QPa6G/:I4VVUkcUzlbEOcR7GQMfk3bu/`
IMP | `CDA55BC95CEC682DB8C3A67C6AB5C96D`
PESHA1 | `64D2E3618639B55027BD5CB7BA50006CC1923A40`
PE256 | `1CC9D0FB1B29D6409A1DF087210A2EC9D68BB478618BBFBD68F7CE42CD24EA95`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SpLsaModeInitialize` | 1 (0x1) | Exported Function | 0x10003bd0 | 0x00003bd0
`SpUserModeInitialize` | 2 (0x2) | Exported Function | 0x10012e30 | 0x00012e30


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSpkg.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/40f3ffcc134db81bf54ad0afb4a9fed95c28b5d1a8e5a7a18de6cbb0db075cb7/detection/


## Possible Misuse

*The following table contains possible examples of `TSpkg.dll` being misused. While `TSpkg.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s6 = "tspkg!TSGlobalCredTable" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $s5 = "sekurlsa::tspkg" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


