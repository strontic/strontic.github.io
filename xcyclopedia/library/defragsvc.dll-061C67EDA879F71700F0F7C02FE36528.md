---
title: defragsvc.dll | Microsoft\Drive Optimizer
excerpt: What is defragsvc.dll?
---

# defragsvc.dll 

* File Path: `C:\Windows\system32\defragsvc.dll`
* Description: Microsoft\Drive Optimizer

## Hashes

Type | Hash
-- | --
MD5 | `061C67EDA879F71700F0F7C02FE36528`
SHA1 | `8C35C90751AB426E5EE5885D12E33A179DCA3F3F`
SHA256 | `F2D3F16BC2E462BB538916EEA2DC997EE8ED85B0DF8A6C2FCDB6A01F8B3DBEA7`
SHA384 | `C5B2D5B6286F1F8D66BF31E2448E256D0AFB7FCFF299F78C29319991F558621595F6ED2B51582A144821E6307FCD6C3C`
SHA512 | `89EF052A233539ED4DC8AB34595E61DA2D24071BA839636FB158404BDCF27A8C67B1F804D70579720C6F3157D95A7C7BD526695A3908008A317A8F48EEC13E61`
SSDEEP | `6144:U2xmagmvyAqLUIB8SJ1BfPeroXAkFOEro7AnoBACwWpFhFBei55YWTNE74LxI:U2OUIBnFOSoUoNwWpFki55Yeq4Lx`
IMP | `CCCFB1DC119B994AAD9B2E9DB72CD5B2`
PESHA1 | `338C76EDEF540B02DC5EA6E34563E267FE597254`
PE256 | `7B16C12162981DE6972917F4672A8AB662BABC0627E6DB9583DADF0A38EBBC53`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`ServiceMain` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: defragsvc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/f2d3f16bc2e462bb538916eea2dc997ee8ed85b0df8a6c2fcdb6a01f8b3dbea7/detection/


## Possible Misuse

*The following table contains possible examples of `defragsvc.dll` being misused. While `defragsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_industroyer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_industroyer.yar) | $s2 = "defragsvc" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


