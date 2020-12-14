---
title: actxprxy.dll | ActiveX Interface Marshaling Library
excerpt: What is actxprxy.dll?
---

# actxprxy.dll 

* File Path: `C:\Windows\SysWOW64\actxprxy.dll`
* Description: ActiveX Interface Marshaling Library

## Hashes

Type | Hash
-- | --
MD5 | `4091996A2CFD78ED60F4E738741D16D8`
SHA1 | `ABDDCB3CF19880FA245780B1FF27F82776B24253`
SHA256 | `1F17BED77A3AA2492B7F8AE39C4EDEFD1A72EAADAFB7E0F5049AF9E3F7C02786`
SHA384 | `77B21286138E60415FFFC469E58C0FE573906417B4FC273CDBA3E5BB72C43CAAD46202D34079BF76B866C9C740124584`
SHA512 | `185D9DFCC764FB8E0961CAD7D3A65427BD178B0957A87ED038DB1D8154716C8BCBA45554BC1628D892D274ACC4D44678E3888FEC3ACEB46B7C6B8CAF53B74BA4`
SSDEEP | `3072:5r2LpdwA+7Ixa39lMkbz4H2geMQgjIYAcKO9QoM+yrSCsLrMdhauV6HUTqC5Vv/8:7ts9nJLbWNh4ghHrm`
IMP | `0330BF0501002589AE854F5731A4F40E`
PESHA1 | `802915F3484AC6C876A6621E02B65B7CD824B26C`
PE256 | `1F6D86087271A2624E90FC9BCA310ECDD251F062AFB1D001B1B2FB32354B6764`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllUnregisterServer` | 7 | Exported Function
`GetProxyDllInfo` | 3 | Exported Function
`DllRegisterServer` | 6 | Exported Function
`DllCanUnloadNow` | 4 | Exported Function
`DllGetClassObject` | 5 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/1f17bed77a3aa2492b7f8ae39c4edefd1a72eaadafb7e0f5049af9e3f7c02786/detection/


## Possible Misuse

*The following table contains possible examples of `actxprxy.dll` being misused. While `actxprxy.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s0 = "actxprxy.GetProxyDllInfo" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s3 = "actxprxy.DllGetClassObject" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s5 = "actxprxy.DllRegisterServer" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s6 = "actxprxy.DllUnregisterServer" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


