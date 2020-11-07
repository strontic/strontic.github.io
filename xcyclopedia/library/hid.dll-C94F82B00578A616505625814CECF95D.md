---
title: hid.dll | Hid User Library
excerpt: What is hid.dll?
---

# hid.dll 

* File Path: `C:\Windows\system32\hid.dll`
* Description: Hid User Library

## Hashes

Type | Hash
-- | --
MD5 | `C94F82B00578A616505625814CECF95D`
SHA1 | `4F4D08B4839142D68D9A3EF9269D31138DFB536D`
SHA256 | `6CC897B3F92A78E3C52EE71592F290865E29A67E4758C4D0D3687346E13E68F1`
SHA384 | `2BDACBB70A42FEE60DA91AEEA63B8FE75F90100A0BA9B71F845D1B89FDCBF1E210A90EE23055F15207EF4242EE907D5F`
SHA512 | `B71FE920A3EE6597CBD1D14305C76877571E06D6C0754B9676A7F1F4F28045A5706244BF6DFC92166B54BFEA2F2DBFB6B47C40E88D7C4617756EC5D77D4D3E81`
SSDEEP | `768:sBvf3Ew1OTNpmIIfR/jrNqEjWAZhqNWuon:yvfdORpmIIfd79qNWv`
IMP | `FB17CE605F50ADBF23B3346B82899635`
PESHA1 | `CD0BB038A6BAFFE1127AE0E009D0967152172446`
PE256 | `1739EA4EE8D1015EE83C85F45A32D62AAD5E6ECF1F000D9472BC77F1F3B85E91`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`HidD_FlushQueue` | 1 | Exported Function
`HidP_GetLinkCollectionNodes` | 25 | Exported Function
`HidP_GetScaledUsageValue` | 26 | Exported Function
`HidP_GetSpecificButtonCaps` | 27 | Exported Function
`HidP_GetSpecificValueCaps` | 28 | Exported Function
`HidP_GetUsages` | 31 | Exported Function
`HidP_GetUsagesEx` | 32 | Exported Function
`HidP_GetUsageValue` | 29 | Exported Function
`HidP_GetUsageValueArray` | 30 | Exported Function
`HidP_GetExtendedAttributes` | 24 | Exported Function
`HidP_GetValueCaps` | 33 | Exported Function
`HidP_MaxDataListLength` | 35 | Exported Function
`HidP_MaxUsageListLength` | 36 | Exported Function
`HidP_SetData` | 37 | Exported Function
`HidP_SetScaledUsageValue` | 38 | Exported Function
`HidP_SetUsages` | 41 | Exported Function
`HidP_SetUsageValue` | 39 | Exported Function
`HidP_SetUsageValueArray` | 40 | Exported Function
`HidP_TranslateUsagesToI8042ScanCodes` | 42 | Exported Function
`HidP_InitializeReportForID` | 34 | Exported Function
`HidP_GetData` | 23 | Exported Function
`HidP_GetCaps` | 22 | Exported Function
`HidP_GetButtonCaps` | 21 | Exported Function
`HidD_FreePreparsedData` | 2 | Exported Function
`HidD_GetAttributes` | 3 | Exported Function
`HidD_GetConfiguration` | 4 | Exported Function
`HidD_GetFeature` | 5 | Exported Function
`HidD_GetHidGuid` | 6 | Exported Function
`HidD_GetIndexedString` | 7 | Exported Function
`HidD_GetInputReport` | 8 | Exported Function
`HidD_GetManufacturerString` | 9 | Exported Function
`HidD_GetMsGenreDescriptor` | 10 | Exported Function
`HidD_GetNumInputBuffers` | 11 | Exported Function
`HidD_GetPhysicalDescriptor` | 12 | Exported Function
`HidD_GetPreparsedData` | 13 | Exported Function
`HidD_GetProductString` | 14 | Exported Function
`HidD_GetSerialNumberString` | 15 | Exported Function
`HidD_Hello` | 16 | Exported Function
`HidD_SetConfiguration` | 17 | Exported Function
`HidD_SetFeature` | 18 | Exported Function
`HidD_SetNumInputBuffers` | 19 | Exported Function
`HidD_SetOutputReport` | 20 | Exported Function
`HidP_UnsetUsages` | 43 | Exported Function
`HidP_UsageListDifference` | 44 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hid.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/6cc897b3f92a78e3c52ee71592f290865e29a67e4758c4d0d3687346e13e68f1/detection/


## Possible Misuse

*The following table contains possible examples of `hid.dll` being misused. While `hid.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s2 = "%s\\hid.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hidden_cobra.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hidden_cobra.yar) | $s2 = "%s\\hid.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


