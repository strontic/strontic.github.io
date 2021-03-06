﻿---
title: quickassist.exe | Quick Assist
excerpt: What is quickassist.exe?
---

# quickassist.exe 

* File Path: `C:\WINDOWS\SysWOW64\quickassist.exe`
* Description: Quick Assist

## Screenshot

![quickassist.exe](screenshots/quickassist.exe-39AB5ED601B0C39DCE3B7D269847C944-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `C7A80E4F54289F7B0A51CAC386DB068D`
SHA1 | `23F01504312DA414FA8ED10364D523EFCB248DB8`
SHA256 | `5A64A20EF47220F4D9F74CC0E695EBA855A9895BA4C808E2FD3AFE92FBA40B4A`
SHA384 | `3589D87C2DAA1D58C19EE95D968479CBF13B8EA0909A194E7D93DE21221050EF832BED5314B0D8EE8BAABB5F07DD5EE9`
SHA512 | `8C855310FDBBF33618A635932940C69919200F19D4FEFD46AA7705C964CEE86047C471DE9B18188F96EC44DD3BDE5D32E9B1667D118EF478ADED5671A8C63C27`
SSDEEP | `6144:wFGsqMBRc2KlxBZn7HTEDiNLA57VllbK5WTdDDzLJXthun:UGsqMTKtZfEDiNLA571u5A91XO`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: QuickAssist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `quickassist.exe` being misused. While `quickassist.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s1 = "QuickAssist.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s4 = "name=\"QuickAssist\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


