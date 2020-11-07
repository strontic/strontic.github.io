---
title: ieproxy.dll | IE ActiveX Interface Marshaling Library
excerpt: What is ieproxy.dll?
---

# ieproxy.dll 

* File Path: `C:\Windows\SysWOW64\ieproxy.dll`
* Description: IE ActiveX Interface Marshaling Library

## Hashes

Type | Hash
-- | --
MD5 | `2600848B1049BDC76B0FF129EA484C03`
SHA1 | `8A43F1E21C39100225CF9F6C8B28D8ECDECAA187`
SHA256 | `1C7631FDF521ADCF721F46142BA906F6A3643F572DC4C3A51757345566482837`
SHA384 | `C686A3EFA85C964654BC2D2B338B077FEBC7A8FE54CB2E6D4302960B474FE4F75D869CBECF1B37A03827BA08F0EA401C`
SHA512 | `5AC64288CA221975D6E3BEB670FE0C32130F8F656E71D92FB99E75BFAA1E3B74BFD30989F091C83C30F19F0820343942E40EF0FB0FA122B5F5EB6516BDAD259E`
SSDEEP | `6144:e/ydlhMFJUINnir4jdUzsTr2uduAKkXU4:rn6JUINnir4jdUzY2Hkk`
IMP | `26DA6FB23B0239A485FF261944B2C583`
PESHA1 | `4094B7AD404D060AB95AC1AA290239EB813FF102`
PE256 | `61C1363917D8D5A1982C15E9330DE55CF32DA081CBF226D80FAB0DE6520868EE`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 4 | Exported Function
`DllGetClassObject` | 5 | Exported Function
`DllRegisterServer` | 6 | Exported Function
`DllUnregisterServer` | 7 | Exported Function
`GetProxyDllInfo` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ieproxy.dll
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.488 (WinBuild.160101.0800)
* Product Version: 11.00.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/1c7631fdf521adcf721f46142ba906f6a3643f572dc4c3a51757345566482837/detection/


## Possible Misuse

*The following table contains possible examples of `ieproxy.dll` being misused. While `ieproxy.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s2 = "ieproxy.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


