---
title: msftedit.dll | Rich Text Edit Control, v8.5
excerpt: What is msftedit.dll?
---

# msftedit.dll 

* File Path: `C:\Windows\system32\msftedit.dll`
* Description: Rich Text Edit Control, v8.5

## Hashes

Type | Hash
-- | --
MD5 | `FBCFB50A84127894401D092630689C44`
SHA1 | `8D9EB2C9799F6041BBB5DEE21C90D06E357E7A18`
SHA256 | `6732067774628D4376D5BB7D1830C445D0F518FE85DA2A5554ADB8812F4B09C3`
SHA384 | `2AB2DA640943AA2B8D1DFBB925F1E5C1354C000A54CC62489F118A0680D946AAD4C7D676BF54442D165B67755C890A6D`
SHA512 | `19E12EE39F670E80A74667B7E1ED03742D85898DB318697A05C2D9C87D40664C5FBD71C4EDEF2A02901E49D96F330246679AF10B54510C3CF39D2C0E124055B6`
SSDEEP | `49152:N5sRTbCVxzq/d1M/Blp0fMe5ASN3gXs65OFNI9A1EjV0EDNM4tbdQCsIpO7RLNkn:Aqq/yzSNWstX1KJF`
IMP | `15F6F66350D256C59197E983DF2DAA6A`
PESHA1 | `41CB8B3C9FD732E0190B42B41A37C0CD9452D980`
PE256 | `9239D16905C7F94E2966B49C5056F64BFB08D209FA521F8DE5C301AADE2BE952`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CreateTextServices` | 4 | Exported Function
`SetCustomTextOutHandlerEx` | 11 | Exported Function
`RichEditWndProc` | 13 | Exported Function
`RichEditANSIWndProc` | 9 | Exported Function
`RichEdit10ANSIWndProc` | 10 | Exported Function
`MathTranslate` | 19 | Exported Function
`MathBuildUp` | 17 | Exported Function
`MathBuildDown` | 18 | Exported Function
`IID_ITextServices2` | 25 | Exported Function
`IID_ITextServices` | 5 | Exported Function
`IID_ITextHost2` | 7 | Exported Function
`SetTextServicesDpiCalculationOverride` | 36 | Exported Function
`IID_ITextHost` | 6 | Exported Function
`IID_IRicheditWindowlessAccessibility` | 32 | Exported Function
`IID_IRicheditUiaOverrides` | 33 | Exported Function
`IID_IRicheditUiaNotificationOverrides` | 37 | Exported Function
`IID_IRichEditOleCallback` | 3 | Exported Function
`IID_IRichEditOle` | 2 | Exported Function
`GetMathAlphanumericCode` | 21 | Exported Function
`GetMathAlphanumeric` | 22 | Exported Function
`DllGetVersion` | 12 | Exported Function
`DllGetActivationFactory` | 26 | Exported Function
`DisableOleinitCheck` | 8 | Exported Function
`IID_ITextDocument2` | 24 | Exported Function
`ShutdownTextServices` | 35 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsftEdit.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6732067774628d4376d5bb7d1830c445d0f518fe85da2a5554adb8812f4b09c3/detection/


## Possible Misuse

*The following table contains possible examples of `msftedit.dll` being misused. While `msftedit.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poseidon_group.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poseidon_group.yar) | $s0 = "{\\*\\generator Msftedit 5.41." ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


