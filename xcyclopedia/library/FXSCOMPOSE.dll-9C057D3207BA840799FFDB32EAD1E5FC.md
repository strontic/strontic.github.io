---
title: FXSCOMPOSE.dll | Compose Form
excerpt: What is FXSCOMPOSE.dll?
---

# FXSCOMPOSE.dll 

* File Path: `C:\Windows\system32\FXSCOMPOSE.dll`
* Description: Compose Form

## Hashes

Type | Hash
-- | --
MD5 | `9C057D3207BA840799FFDB32EAD1E5FC`
SHA1 | `371395957E7C7F95A15345D4B6075CD4239CE0BB`
SHA256 | `0D42B67C099286350BDCBEEA9AEBDEDD3AA21716752163DC8A2D22A96BE1E75C`
SHA384 | `5972EB44AD2E10686DECB41ECFDAB0178D50E3461ECFD608245E769B364F17EE5809849154CB0BC3DAAFEE5F3D5B9E09`
SHA512 | `9A53D08530B14568E0DAC84C5A35895093A5DF783A0C422988E9A1AAF1CA619B65E69353894F0AC01F7B067B5108679DCE9A1873E0C6F5B6C8360191E7F0F16A`
SSDEEP | `6144:qn0mA6vaeg7+0VeejvA4VbF2EIB2Ymwzm/EVbLR+kc5If38+qpWM3LU8H8KJ5:MxA6valvA4VbF2E5YxsG+hIf3DM/8K7`
IMP | `F1F659EC0014DF35B7CAE85848B6B20F`
PESHA1 | `A817438180FE3A8B63DE9E88124DFB1982E4F7EC`
PE256 | `37FEBA34703F42AD2E334006ADFA7FF978FCFA811531F244D90A36E26F116021`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`HrInvokeAddressBook` | 10 | Exported Function
`HrInitComposeFormDll` | 9 | Exported Function
`HrInitAddressBook` | 8 | Exported Function
`HrNewFaxComposeUI` | 11 | Exported Function
`HrSelectEmailRecipient` | 14 | Exported Function
`HrNewTiffViewUIFromFile` | 13 | Exported Function
`HrNewFaxComposeUIFromFile` | 12 | Exported Function
`HrGetDraftsListViewInfo` | 7 | Exported Function
`HrAddressBookPreTranslateAccelerator` | 2 | Exported Function
`FaxComposeFreeBuffer` | 1 | Exported Function
`DllMain` | 15 | Exported Function
`HrDeInitAddressBook` | 3 | Exported Function
`HrFreeDraftsListViewInfo` | 6 | Exported Function
`HrFaxComposePreTranslateAccelerator` | 5 | Exported Function
`HrDeinitComposeFormDll` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Fxscompose.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/0d42b67c099286350bdcbeea9aebdedd3aa21716752163dc8a2d22a96be1e75c/detection/


## Possible Misuse

*The following table contains possible examples of `FXSCOMPOSE.dll` being misused. While `FXSCOMPOSE.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `"ServiceDll"= "%SystemRoot%\System32\FXSCOMPOSE.dll" (translated from hex)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


