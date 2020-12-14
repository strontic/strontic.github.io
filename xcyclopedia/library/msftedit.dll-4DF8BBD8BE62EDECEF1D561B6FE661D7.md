---
title: msftedit.dll | Rich Text Edit Control, v8.5
excerpt: What is msftedit.dll?
---

# msftedit.dll 

* File Path: `C:\Windows\SysWOW64\msftedit.dll`
* Description: Rich Text Edit Control, v8.5

## Hashes

Type | Hash
-- | --
MD5 | `4DF8BBD8BE62EDECEF1D561B6FE661D7`
SHA1 | `444BDD20681650563E20893CFEE3A8DFC441CEEC`
SHA256 | `ACB6D3251EFA255F732650092153874CB4FF72DF2E2CFDFA036310BF7A513EA1`
SHA384 | `11C8A881B46CF6A7E2268564BE85CD19B4CB03F83AA8A58A354E15451C51700F0CD5B334C768B1263D103F733FACA151`
SHA512 | `99D989525821CA761609A07698455C7D310D02E8EFEDF14AD874AEE6B41A2D0F976B7C9C9FF823A96A4726D6754F2294ACE2AA2C9978A037497D419CEF94E3E2`
SSDEEP | `49152:AYVzbDGZJwyN0cTBVDu5zj1tgCj9+OpB1jlpUpFWON9SH4oZa1bJxDd2JA5qS8zk:JzbsxN0cBVD0zj1jj9BHF3nON9SHOxnW`
IMP | `07F3B0DB6A77DAB18FC9278B18318E44`
PESHA1 | `CB8746693BB8FEE5D5787C378A2185CA741A806D`
PE256 | `EF6DFFF1F2457ACE741E756116C16DA5193861E2A0D7A1C697385C9D59B983C2`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MathBuildDown` | 18 | Exported Function
`MathBuildUp` | 17 | Exported Function
`MathTranslate` | 19 | Exported Function
`IID_ITextHost2` | 7 | Exported Function
`IID_ITextServices` | 5 | Exported Function
`IID_ITextServices2` | 25 | Exported Function
`SetCustomTextOutHandlerEx` | 11 | Exported Function
`SetTextServicesDpiCalculationOverride` | 36 | Exported Function
`ShutdownTextServices` | 35 | Exported Function
`RichEdit10ANSIWndProc` | 10 | Exported Function
`RichEditANSIWndProc` | 9 | Exported Function
`RichEditWndProc` | 13 | Exported Function
`IID_ITextHost` | 6 | Exported Function
`DllGetVersion` | 12 | Exported Function
`GetMathAlphanumeric` | 22 | Exported Function
`GetMathAlphanumericCode` | 21 | Exported Function
`_DisableOleinitCheck@0` | 8 | Exported Function
`CreateTextServices` | 4 | Exported Function
`DllGetActivationFactory` | 26 | Exported Function
`IID_IRicheditUiaOverrides` | 33 | Exported Function
`IID_IRicheditWindowlessAccessibility` | 32 | Exported Function
`IID_ITextDocument2` | 24 | Exported Function
`IID_IRichEditOle` | 2 | Exported Function
`IID_IRichEditOleCallback` | 3 | Exported Function
`IID_IRicheditUiaNotificationOverrides` | 37 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/acb6d3251efa255f732650092153874cb4ff72df2e2cfdfa036310bf7a513ea1/detection/


## Possible Misuse

*The following table contains possible examples of `msftedit.dll` being misused. While `msftedit.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poseidon_group.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poseidon_group.yar) | $s0 = "{\\*\\generator Msftedit 5.41." ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


