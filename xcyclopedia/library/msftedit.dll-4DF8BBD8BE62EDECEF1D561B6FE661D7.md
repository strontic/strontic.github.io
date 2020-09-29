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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_DisableOleinitCheck@0` | 8 (0x8) | Exported Function | 0x1011d600 | 0x0011d600
`SetCustomTextOutHandlerEx` | 11 (0xb) | Exported Function | 0x1011d630 | 0x0011d630
`RichEditWndProc` | 13 (0xd) | Exported Function | 0x101e6e10 | 0x001e6e10
`RichEditANSIWndProc` | 9 (0x9) | Exported Function | 0x101e6dc0 | 0x001e6dc0
`RichEdit10ANSIWndProc` | 10 (0xa) | Exported Function | 0x101e6d30 | 0x001e6d30
`MathTranslate` | 19 (0x13) | Exported Function | 0x101afea0 | 0x001afea0
`MathBuildUp` | 17 (0x11) | Exported Function | 0x101afbf0 | 0x001afbf0
`MathBuildDown` | 18 (0x12) | Exported Function | 0x101afb80 | 0x001afb80
`IID_ITextServices2` | 25 (0x19) | Exported Function | 0x1001a528 | 0x0001a528
`IID_ITextServices` | 5 (0x5) | Exported Function | 0x1001a538 | 0x0001a538
`IID_ITextHost2` | 7 (0x7) | Exported Function | 0x10017eac | 0x00017eac
`SetTextServicesDpiCalculationOverride` | 36 (0x24) | Exported Function | 0x1011d660 | 0x0011d660
`IID_ITextHost` | 6 (0x6) | Exported Function | 0x1002ec88 | 0x0002ec88
`IID_IRicheditWindowlessAccessibility` | 32 (0x20) | Exported Function | 0x1001a508 | 0x0001a508
`IID_IRicheditUiaOverrides` | 33 (0x21) | Exported Function | 0x1002ec58 | 0x0002ec58
`IID_IRicheditUiaNotificationOverrides` | 37 (0x25) | Exported Function | 0x10017364 | 0x00017364
`IID_IRichEditOleCallback` | 3 (0x3) | Exported Function | 0x1001a460 | 0x0001a460
`IID_IRichEditOle` | 2 (0x2) | Exported Function | 0x1001a470 | 0x0001a470
`GetMathAlphanumericCode` | 21 (0x15) | Exported Function | 0x101a78a0 | 0x001a78a0
`GetMathAlphanumeric` | 22 (0x16) | Exported Function | 0x101a7570 | 0x001a7570
`DllGetVersion` | 12 (0xc) | Exported Function | 0x101e7f30 | 0x001e7f30
`DllGetActivationFactory` | 26 (0x1a) | Exported Function | 0x1004d840 | 0x0004d840
`CreateTextServices` | 4 (0x4) | Exported Function | 0x10068400 | 0x00068400
`IID_ITextDocument2` | 24 (0x18) | Exported Function | 0x1001a430 | 0x0001a430
`ShutdownTextServices` | 35 (0x23) | Exported Function | 0x1005be30 | 0x0005be30


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

*The following table contains possible examples of `msftedit.dll` being misused. While `msftedit.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poseidon_group.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poseidon_group.yar) | $s0 = "{\\*\\generator Msftedit 5.41." ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


