﻿---
title: appmgmts.dll | Software installation Service
excerpt: What is appmgmts.dll?
---

# appmgmts.dll 

* File Path: `C:\Windows\system32\appmgmts.dll`
* Description: Software installation Service

## Hashes

Type | Hash
-- | --
MD5 | `23A64FAEBC3E565537D8A54BC2791F9A`
SHA1 | `C4AEB128FADB77DE2945D8659F852D7E69C90B1A`
SHA256 | `0F142FA2669BA775C0A253CBEC8AD81632135B28221C464DDE49BC58BE9689C3`
SHA384 | `77D583F5DAFE5EE9BA4375B3FA6A6B8706027B538CAA3DD59427412B41CB58E3B18F01F705810CE4FAD187D971E6128D`
SHA512 | `5DA392AC3760EC6901720C9F23E435910857F173247925AC68E4C3DDBB104E81D558234E95255ECE10E821FB12909C9E1609F3A2ADE538475A94E3CA62A02CCC`
SSDEEP | `6144:wwLeph/gEOaZdDutBG4nH7mAspk1AkXj6kA:VLep6EOIuGV22kXuT`
IMP | `3F5AD0429209DDFA97214E92C9924088`
PESHA1 | `5FAF556DE58DB1F9573C89020B4E525157C4D081`
PE256 | `D18B151C6B60DD485EBE252AE9DFBEF2BE6662AC679099CDE73765ACC12919D5`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`GenerateGroupPolicy` | 13 | Exported Function
`IID_IClassAdmin` | 14 | Exported Function
`DllCanUnloadNow` | 11 | Exported Function
`DllGetClassObject` | 12 | Exported Function
`ProcessGroupPolicyObjectsEx` | 15 | Exported Function
`ReleasePackageInfo` | 18 | Exported Function
`ServiceMain` | 19 | Exported Function
`ReleaseAppCategoryInfoList` | 16 | Exported Function
`ReleasePackageDetail` | 17 | Exported Function
`CsUnregisterAppCategory` | 10 | Exported Function
`CsGetAppCategories` | 4 | Exported Function
`CsGetClassAccess` | 5 | Exported Function
`CsCreateClassStore` | 2 | Exported Function
`CsEnumApps` | 3 | Exported Function
`CsGetClassStore` | 6 | Exported Function
`CsServerGetClassStore` | 9 | Exported Function
`CsSetOptions` | 1 | Exported Function
`CsGetClassStorePath` | 7 | Exported Function
`CsRegisterAppCategory` | 8 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: appmgmts.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/0f142fa2669ba775c0a253cbec8ad81632135b28221c464dde49bc58be9689c3/detection/


## Possible Misuse

*The following table contains possible examples of `appmgmts.dll` being misused. While `appmgmts.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $z5 = "\\appmgmts.dll" fullword ascii /* score: '11.0' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


