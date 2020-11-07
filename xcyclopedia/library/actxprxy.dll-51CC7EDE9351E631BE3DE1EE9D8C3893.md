---
title: actxprxy.dll | ActiveX Interface Marshaling Library
excerpt: What is actxprxy.dll?
---

# actxprxy.dll 

* File Path: `C:\Windows\system32\actxprxy.dll`
* Description: ActiveX Interface Marshaling Library

## Hashes

Type | Hash
-- | --
MD5 | `51CC7EDE9351E631BE3DE1EE9D8C3893`
SHA1 | `CB4A31CB46E80B8F7354DB641CC30EC27F645646`
SHA256 | `367C156557792C36E885DCB067EA2A8074A8CD664EDD1DF20E648351FF3919A1`
SHA384 | `7DF72B9DCC9A93BF8AEC11D6E84D254A8FF15C6FA3A6DE28EC9CBECA4A3591319A9C11F47827D7649D5D8EE4DE78DE11`
SHA512 | `32C1F98BDC88B97EEEC8922D6FDC1AC72672D7C7816309212AA919A601887251B963EAF6958CD82369B4CE7D7A44E5F48094FE265B0331545432E1F23BD70366`
SSDEEP | `6144:+0sHN16NxvghqmknQ4NoS4ce4H/wRkMzjYrR36g8tvirygxCxjP+D:djdIKRD`
IMP | `C340D0CE5BAB3FDB8250A589AD53130F`
PESHA1 | `9C4B4D9E4662AA57EBA1A970D0F2CA5D231DB943`
PE256 | `CCAFC335DA9AB897EFE3D56245CD726A495BF8DD95E715E2D835CBB0C8499A01`

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

* Original Filename: ActXPrxy.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/367c156557792c36e885dcb067ea2a8074a8cd664edd1df20e648351ff3919a1/detection/


## Possible Misuse

*The following table contains possible examples of `actxprxy.dll` being misused. While `actxprxy.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s0 = "actxprxy.GetProxyDllInfo" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s3 = "actxprxy.DllGetClassObject" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s5 = "actxprxy.DllRegisterServer" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s6 = "actxprxy.DllUnregisterServer" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


