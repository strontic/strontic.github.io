---
title: ieproxy.dll | IE ActiveX Interface Marshaling Library
excerpt: What is ieproxy.dll?
---

# ieproxy.dll 

* File Path: `C:\Windows\system32\ieproxy.dll`
* Description: IE ActiveX Interface Marshaling Library

## Hashes

Type | Hash
-- | --
MD5 | `101C71C5E05095746FA96EE133FEBDD9`
SHA1 | `67C0991DF8EC6AD8FF5D03F7328EE18FA8E3A775`
SHA256 | `9340D1116D4666F3846F1877C04731B3071CD05AFE1B380EA1C24D922CF87876`
SHA384 | `C7DAD88EE26F1E875C92B1710206D651CAE2E511B6561C23DBEA6CE80B1CF362ED60458D23A152DB51C9188D4086D6AA`
SHA512 | `A2C668B7E69D18DB71B4C18B66E090BBB23A340D7B4A6D07788F6544F64261860973F1AB1334A75AEFE64B493F84104817DBBDDA14E2185A0532F34F2E75956F`
SSDEEP | `6144:QJsmp51XYKQdF1rbhfVLjZm6+HrJEINHyrojdEZI58yfzKSSdm1NwBmqyaBa/EO2:dmp51GlcJEINHyrojdEZu11J`
IMP | `31468DC375BB32E78A84A4E125E0143B`
PESHA1 | `415BE7953AC6EEA0D578BE4D9A47321D82FAEB76`
PE256 | `1E29AC792089552F5EEFC35088454761A971EE8F26761682B0464FC277A91B48`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/57
* VirusTotal Link: https://www.virustotal.com/gui/file/9340d1116d4666f3846f1877c04731b3071cd05afe1b380ea1c24d922cf87876/detection/


## Possible Misuse

*The following table contains possible examples of `ieproxy.dll` being misused. While `ieproxy.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s2 = "ieproxy.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


