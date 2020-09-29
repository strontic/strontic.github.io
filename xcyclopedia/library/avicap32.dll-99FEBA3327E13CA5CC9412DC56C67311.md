---
title: avicap32.dll | AVI Capture window class
excerpt: What is avicap32.dll?
---

# avicap32.dll 

* File Path: `C:\Windows\SysWOW64\avicap32.dll`
* Description: AVI Capture window class

## Hashes

Type | Hash
-- | --
MD5 | `99FEBA3327E13CA5CC9412DC56C67311`
SHA1 | `1608D14AEB084F7274B0C43F0675CEDA904CA9B2`
SHA256 | `6B55044F470B4E9649C7F941855FEB7E99B2FF6B34C211CA276CF45C634F97AD`
SHA384 | `3B427CD37AFD84C527BA906DD1E3A59A1CA22AE75687AB8CC877C7A1DB3738A7A327977F744237DB82839F27BD768B20`
SHA512 | `CDA15EB916B3823D748A5D214F18A69550E783C619E80630416049A68B7A0DE4DA3C6AB245009D1B654A8C03F6F029924A96C844B656C2CC555C41FAB57274FC`
SSDEEP | `1536:yVJ/TdAJgOAD/FXo4YMRhacit9tgFPTKay:yVRWJgOAjFXhZRhadPgFPO`
IMP | `0A42828B1FD6F66EA9C00D06DFEF96ED`
PESHA1 | `F946043F0AA0374D83EAD2FB19A9FB75E7C118DE`
PE256 | `CF1C2A1298C87F381BCD851EB6F294F932D399903B670D6AF657A7454CFB7D5F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AppCleanup` | 1 (0x1) | Exported Function | 0x1c30cde0 | 0x0000cde0
`capCreateCaptureWindowA` | 2 (0x2) | Exported Function | 0x1c302200 | 0x00002200
`capCreateCaptureWindowW` | 3 (0x3) | Exported Function | 0x1c3021a0 | 0x000021a0
`capGetDriverDescriptionA` | 4 (0x4) | Exported Function | 0x1c301e00 | 0x00001e00
`capGetDriverDescriptionW` | 5 (0x5) | Exported Function | 0x1c301dd0 | 0x00001dd0
`videoThunk32` | 6 (0x6) | Exported Function | 0x1c30d3a0 | 0x0000d3a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AVICAP32.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/6b55044f470b4e9649c7f941855feb7e99b2ff6b34c211ca276cf45c634f97ad/detection/


## Possible Misuse

*The following table contains possible examples of `avicap32.dll` being misused. While `avicap32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_m.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_m.yar) | $a1 = "AVICAP32.DLL" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


