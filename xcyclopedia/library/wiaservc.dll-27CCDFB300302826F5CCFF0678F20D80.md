---
title: wiaservc.dll | Still Image Devices Service
excerpt: What is wiaservc.dll?
---

# wiaservc.dll 

* File Path: `C:\Windows\system32\wiaservc.dll`
* Description: Still Image Devices Service

## Hashes

Type | Hash
-- | --
MD5 | `27CCDFB300302826F5CCFF0678F20D80`
SHA1 | `59DBEA485C6003842728CD83373A89BC276537DC`
SHA256 | `84816CB7033FDEDA560E03995C254577E5BB23E15C7C03FB68074C2E60F31B66`
SHA384 | `13323C7586C76675FAC6A352279CA37DE76B4A286C95CBE98144D5DC6308292F319692634434AB0842093A5550E1CF15`
SHA512 | `5838C7CB9388E7F49234EEF746F427021AD9E9CBF719FBC74ED9523CEF92BDD695E2864B0A79527F4269D8BE862152CD9A2C0B90331F4C743F151798CCADB965`
SSDEEP | `6144:9FEFmkHj9sEFAnNQSIxLawUMuQ0E9GgcxlcxJL6XPWlFArVEr61DAmh+Pw8VFlge:YmquLNSawpu9E9GJ2WsFAZXpp3`
IMP | `76F3002B0273C7DA64BC826D20BD1071`
PESHA1 | `9BD85EA8541A3AECED99FFCD3AF9F65991EF331F`
PE256 | `19BD8B43BD4FD318F87C4A715256CEC956D8D042727C4808551381EB82D7D194`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`wiasSetValidFlag` | 39 | Exported Function
`wiasSetPropertyAttributes` | 38 | Exported Function
`wiasSetPropChanged` | 37 | Exported Function
`wiasSetValidListFloat` | 40 | Exported Function
`wiasSetValidListStr` | 43 | Exported Function
`wiasSetValidListLong` | 42 | Exported Function
`wiasSetValidListGuid` | 41 | Exported Function
`wiasReadPropLong` | 32 | Exported Function
`wiasReadPropGuid` | 31 | Exported Function
`wiasReadPropFloat` | 30 | Exported Function
`wiasReadPropStr` | 33 | Exported Function
`wiasSetItemPropNames` | 36 | Exported Function
`wiasSetItemPropAttribs` | 35 | Exported Function
`wiasSendEndOfPage` | 34 | Exported Function
`wiasWritePropBin` | 53 | Exported Function
`wiasWritePageBufToStream` | 52 | Exported Function
`wiasWritePageBufToFile` | 51 | Exported Function
`wiasWritePropFloat` | 54 | Exported Function
`wiasWritePropStr` | 57 | Exported Function
`wiasWritePropLong` | 56 | Exported Function
`wiasWritePropGuid` | 55 | Exported Function
`wiasUpdateScanRect` | 46 | Exported Function
`wiasSetValidRangeLong` | 45 | Exported Function
`wiasSetValidRangeFloat` | 44 | Exported Function
`wiasUpdateValidFormat` | 47 | Exported Function
`wiasWriteMultiple` | 50 | Exported Function
`wiasWriteBufToFile` | 49 | Exported Function
`wiasValidateItemProperties` | 48 | Exported Function
`wiasReadPropBin` | 29 | Exported Function
`wiasDownSampleBuffer` | 10 | Exported Function
`wiasDebugTrace` | 9 | Exported Function
`wiasDebugError` | 8 | Exported Function
`wiasFormatArgs` | 11 | Exported Function
`wiasGetChangedValueGuid` | 14 | Exported Function
`wiasGetChangedValueFloat` | 13 | Exported Function
`wiasFreePropContext` | 12 | Exported Function
`ServiceMain` | 1 | Exported Function
`DllUnregisterServer` | 3 | Exported Function
`DllRegisterServer` | 2 | Exported Function
`wiasCreateChildAppItem` | 4 | Exported Function
`wiasCreatePropContext` | 7 | Exported Function
`wiasCreateLogInstance` | 6 | Exported Function
`wiasCreateDrvItem` | 5 | Exported Function
`wiasIsPropChanged` | 24 | Exported Function
`wiasGetRootItem` | 23 | Exported Function
`wiasGetPropertyAttributes` | 22 | Exported Function
`wiasParseEndorserString` | 25 | Exported Function
`wiasReadMultiple` | 28 | Exported Function
`wiasQueueEvent` | 27 | Exported Function
`wiasPrintDebugHResult` | 26 | Exported Function
`wiasGetChildrenContexts` | 17 | Exported Function
`wiasGetChangedValueStr` | 16 | Exported Function
`wiasGetChangedValueLong` | 15 | Exported Function
`wiasGetContextFromName` | 18 | Exported Function
`wiasGetItemType` | 21 | Exported Function
`wiasGetImageInformation` | 20 | Exported Function
`wiasGetDrvItem` | 19 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WIASERVC.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/84816cb7033fdeda560e03995c254577e5bb23e15c7c03fb68074c2e60f31b66/detection/


## Possible Misuse

*The following table contains possible examples of `wiaservc.dll` being misused. While `wiaservc.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s2 = "%SystemRoot%\\System32\\wiaservc.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_derusbi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_derusbi.yar) | $x1 = "%SystemRoot%\\System32\\wiaservc.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


