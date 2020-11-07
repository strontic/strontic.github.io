---
title: apds.dll | Microsoft Help Data Services Module
excerpt: What is apds.dll?
---

# apds.dll 

* File Path: `C:\Windows\system32\apds.dll`
* Description: Microsoft Help Data Services Module

## Hashes

Type | Hash
-- | --
MD5 | `DF461ADCCD541185313F9439313D1EE1`
SHA1 | `E580BC2D30802104AC593E3113C5ABCB7224982D`
SHA256 | `C233004C4739538F18E767B88D356224050E41EEAA20919D91F93D2BAF8BD5FE`
SHA384 | `964CB2271D700F9C626FB5B83243A4C177836D5BF3A968701FB25CBA7A3F2E106334BB21F4D2ACD7ED233CE7C1F6271A`
SHA512 | `F69747915029F151F94FF8F2726BE5F1A35CBB95B0FA2806DAAC55DD3F7862D2F867508FAFFD16B70BA6DFF282E3CF64C1892F33CE72BE770C0D8DFA00B95411`
SSDEEP | `6144:si4ywO9tUJ5nbzgSe5eB9iAKg0EUmY4K/Aw+ht:DdtUJ5n/a+n`
IMP | `5A5195EC7C12BB0DFF6FC30CB3150BD8`
PESHA1 | `604A19217AA502A2457F4AD7EC98F7A0D653A24B`
PE256 | `1633F5CCC669EBA8E76EDFE7F0B7F60517F91975B9D35E1ECD9EDA98AFAC8BE6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: APDS.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c233004c4739538f18e767b88d356224050e41eeaa20919d91f93d2baf8bd5fe/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\apds.dll](apds.dll-03C183C9D13F0A92F9F7AF46758BCA72.md) | 52

## Possible Misuse

*The following table contains possible examples of `apds.dll` being misused. While `apds.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy.yar) | $s1 = "apds.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


