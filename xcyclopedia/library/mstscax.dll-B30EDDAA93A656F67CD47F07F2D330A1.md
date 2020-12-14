---
title: mstscax.dll | Remote Desktop Services ActiveX Client
excerpt: What is mstscax.dll?
---

# mstscax.dll 

* File Path: `C:\Windows\system32\mstscax.dll`
* Description: Remote Desktop Services ActiveX Client

## Hashes

Type | Hash
-- | --
MD5 | `B30EDDAA93A656F67CD47F07F2D330A1`
SHA1 | `56DFE19350AA044898AA0A5ABB37D719DC42416C`
SHA256 | `6FB26DE0A8EC9DCBC9400CB2E2964032306D982F55031A13CF882A7FEB3CB12F`
SHA384 | `91119B241EEA139D412A3E373ABF8DABB2DF42F40298D78FC27D81C51D55B0AC4C1F93C6E79D676A1583EB3839D290BB`
SHA512 | `1212326D1DEC9E3FB6FA83EE8D3A7133007447C46C7DA7295E75331AFFAFFAE55DDD96F1874B83293D27C33F5B4F58337A50DC1EF49DB9FAE2BEB871010E5D4E`
SSDEEP | `196608:spUBV3RLfHBJqHBCr+y+qc71PRB6JW6WKAkImBc7zQYmjBZDrA34ILdqd7iTVSTK:spUBV3RLfhJqH4r+y+qc7JRB6JW6Wxk8`
IMP | `6FAC62E2EF8E82FA5604DE8F0E77DD7A`
PESHA1 | `51F6829EC4CBDB6833D8D709B497B1E04BE4AD2E`
PE256 | `96B75FE7EB98F9245F79A557D0EFAB3BE64A15109582903E02172E96BEBFB54D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 8 | Exported Function
`DllLogoffClaimsToken` | 7 | Exported Function
`DllSetAuthProperties` | 9 | Exported Function
`DllUnregisterServer` | 11 | Exported Function
`DllSetClaimsToken` | 10 | Exported Function
`DllGetTscCtlVer` | 6 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllCancelAuthentication` | 2 | Exported Function
`DllDeleteSavedCreds` | 3 | Exported Function
`DllGetClassObject` | 5 | Exported Function
`DllGetClaimsToken` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mstscax.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/6fb26de0a8ec9dcbc9400cb2e2964032306d982f55031a13cf882a7feb3cb12f/detection/


## Possible Misuse

*The following table contains possible examples of `mstscax.dll` being misused. While `mstscax.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file MSTSCAX.DLL" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


