---
title: hid.dll | Hid User Library
excerpt: What is hid.dll?
---

# hid.dll 

* File Path: `C:\Windows\SysWOW64\hid.dll`
* Description: Hid User Library

## Hashes

Type | Hash
-- | --
MD5 | `2062CFA1E8BCB61ECA1733B3217414D9`
SHA1 | `0B8F0DE43041457ED4494FEF1E06154F9E25ECCD`
SHA256 | `221809F408D8AFBF0BB45D2B1E44D506001780959DC0C8BF264C54BAB3BF864D`
SHA384 | `115EDEB62D4C1D0C4F923E9ABDE2367D4021BE767A177ADB77179531C67159744C2BA2A5BBB5C1D7ECE83E1301CDCD01`
SHA512 | `9F8B46F94B72F0D5058900EE48286874EEEF58C1E467A3E913A8FD7B25D5F9FDFAE43298ABA3C0B620F8CB4912A5A72A4F579C1D7486D7C87B320F05A4510DE2`
SSDEEP | `384:TWbJ2vbl/fXXb0XzhVFSD/RikqUEtawAjaazrO3iL2t/LV5d7ouWbYbqoWYUW0:TwytQXzzaik9EUHjzrWiL29LV7nW2qK`
IMP | `D180BC7C3303DBB2AF3402FD84A91FBB`
PESHA1 | `261C3E02F3CCB733100245BBB5E960BF0C0BECA6`
PE256 | `D7B1CA712E66329E0300F86930BF762DB0F6DFA89BFDD5990993F765F3DCE5AD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`HidP_GetUsagesEx` | 32 | Exported Function
`HidP_GetUsages` | 31 | Exported Function
`HidP_GetUsageValue` | 29 | Exported Function
`HidP_GetValueCaps` | 33 | Exported Function
`HidP_GetUsageValueArray` | 30 | Exported Function
`HidP_GetSpecificValueCaps` | 28 | Exported Function
`HidP_GetExtendedAttributes` | 24 | Exported Function
`HidP_GetData` | 23 | Exported Function
`HidP_GetLinkCollectionNodes` | 25 | Exported Function
`HidP_GetSpecificButtonCaps` | 27 | Exported Function
`HidP_GetScaledUsageValue` | 26 | Exported Function
`HidP_SetUsageValueArray` | 40 | Exported Function
`HidP_SetUsageValue` | 39 | Exported Function
`HidP_TranslateUsagesToI8042ScanCodes` | 42 | Exported Function
`HidP_UsageListDifference` | 44 | Exported Function
`HidP_UnsetUsages` | 43 | Exported Function
`HidP_SetUsages` | 41 | Exported Function
`HidP_MaxDataListLength` | 35 | Exported Function
`HidP_InitializeReportForID` | 34 | Exported Function
`HidP_MaxUsageListLength` | 36 | Exported Function
`HidP_SetScaledUsageValue` | 38 | Exported Function
`HidP_SetData` | 37 | Exported Function
`HidD_GetInputReport` | 8 | Exported Function
`HidD_GetIndexedString` | 7 | Exported Function
`HidD_GetManufacturerString` | 9 | Exported Function
`HidD_GetNumInputBuffers` | 11 | Exported Function
`HidD_GetMsGenreDescriptor` | 10 | Exported Function
`HidD_GetHidGuid` | 6 | Exported Function
`HidD_FreePreparsedData` | 2 | Exported Function
`HidD_FlushQueue` | 1 | Exported Function
`HidD_GetAttributes` | 3 | Exported Function
`HidD_GetFeature` | 5 | Exported Function
`HidD_GetConfiguration` | 4 | Exported Function
`HidD_SetNumInputBuffers` | 19 | Exported Function
`HidD_SetFeature` | 18 | Exported Function
`HidD_SetOutputReport` | 20 | Exported Function
`HidP_GetCaps` | 22 | Exported Function
`HidP_GetButtonCaps` | 21 | Exported Function
`HidD_SetConfiguration` | 17 | Exported Function
`HidD_GetPreparsedData` | 13 | Exported Function
`HidD_GetPhysicalDescriptor` | 12 | Exported Function
`HidD_GetProductString` | 14 | Exported Function
`HidD_Hello` | 16 | Exported Function
`HidD_GetSerialNumberString` | 15 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hid.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/221809f408d8afbf0bb45d2b1e44d506001780959dc0c8bf264c54bab3bf864d/detection/


## Possible Misuse

*The following table contains possible examples of `hid.dll` being misused. While `hid.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s2 = "%s\\hid.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hidden_cobra.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hidden_cobra.yar) | $s2 = "%s\\hid.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


