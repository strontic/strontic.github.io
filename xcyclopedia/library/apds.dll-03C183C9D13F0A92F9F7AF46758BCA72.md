---
title: apds.dll | Microsoft Help Data Services Module
excerpt: What is apds.dll?
---

# apds.dll 

* File Path: `C:\Windows\SysWOW64\apds.dll`
* Description: Microsoft Help Data Services Module

## Hashes

Type | Hash
-- | --
MD5 | `03C183C9D13F0A92F9F7AF46758BCA72`
SHA1 | `6382B2E670FCE7F9F3BFFD26C67BF253BAC3D0FB`
SHA256 | `FCEAFA6A997F426A469522FCEDCE0A753D684B9970F15C449839F0E7A3E8E4C0`
SHA384 | `70D5903516D0E4134DF1659DD6361ED4B96B31D53DEE5CD16D5B8C7ED3BC5531932EEF955E60E1B839A90C5CCA211B13`
SHA512 | `0E72D7F214F045EABBEB06DBBE5AE95456C4C1A50BA76C2CE0D3CE8CF74BCE5AC975582BFF1888FA69010F87DF850174F716FE18E8717325648009DA9D85A4F1`
SSDEEP | `6144:ZEQddb/+yan8piAKg0EUmY4K/Aw+hRiQ:3Yyar+zF`
IMP | `33CAE5B4E2906358DE16E6F564362BAB`
PESHA1 | `A46970191EC9A48A83A470329F911EFBF8167F63`
PE256 | `00F590A625FAD147CD54BD59711AF98D2B8DBAA9CE9415D80F04FFC65F41E5CF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: APDS.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/fceafa6a997f426a469522fcedce0a753d684b9970f15c449839f0e7a3e8e4c0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\apds.dll](apds.dll-DF461ADCCD541185313F9439313D1EE1.md) | 52

## Possible Misuse

*The following table contains possible examples of `apds.dll` being misused. While `apds.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy.yar) | $s1 = "apds.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


