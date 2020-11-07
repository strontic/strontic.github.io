---
title: pstorec.dll | Deprecated Protected Storage COM interfaces
excerpt: What is pstorec.dll?
---

# pstorec.dll 

* File Path: `C:\Windows\SysWOW64\pstorec.dll`
* Description: Deprecated Protected Storage COM interfaces

## Hashes

Type | Hash
-- | --
MD5 | `07C04745324D02193A39D9DED5DD00AC`
SHA1 | `2F6AA266FF2B2A306632EFF0817A40436679A2C3`
SHA256 | `BE6C7371C0A3FCA146EB497C9EE48FE96536877A0C7CECC13C128463F76A3FA0`
SHA384 | `298507FCE4B1B5E1F723F586D580F6ECB3EE0BD3D2DC4D82DACFD53F149BE18019498D055897A12C3069BA25EA22D4B1`
SHA512 | `486C98BD66120FB30D3D79C755189A65A57C1C581345A8C157D2EBE683711889B36F8946857514244C534C82B0CA73145B6496E123B2B1B5ADF572BA13AA5723`
SSDEEP | `192:Obz5mA7Lz4hafWSvwaWBessEQL6gqyz5sqAxzwNr:Obzrz4cfWSvwaW0seLPj6qA5w`
IMP | `701F34FD39FCB9DC8B06438007BB8490`
PESHA1 | `D49E9E9D814F0F168CA091BA7F67B0F51B77A3BE`
PE256 | `176C39970EC05CF29D54D1BBB19490D170801929B4D073239E7BB972DA1B28E0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`PStoreCreateInstance` | 5 | Exported Function
`PStoreEnumProviders` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pstorec.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/be6c7371c0a3fca146eb497c9ee48fe96536877a0c7cecc13c128463f76a3fa0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\pstorec.dll](pstorec.dll-7A68CDCA2338FB226FBC61925791BCE7.md) | 58

## Possible Misuse

*The following table contains possible examples of `pstorec.dll` being misused. While `pstorec.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $x6 = "Unable to obtain handle to PStoreCreateInstance in pstorec.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


