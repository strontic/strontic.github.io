---
title: quickassist.exe | Quick Assist
---

# quickassist.exe 

* File Path: `C:\Windows\system32\quickassist.exe`
* Description: Quick Assist

## Hashes

Type | Hash
-- | --
MD5 | `39AB5ED601B0C39DCE3B7D269847C944`
SHA1 | `B13914A7207F2ED60F229FD2FDECDA9AD3F2EC78`
SHA256 | `F3FF9DB4C29E460735FFA8E9B0882A27BA5AC67351CD2ADEA759E496D8BA918A`
SHA384 | `3E0B54D31F45FA314BFC25823B72358D98AB5190B1B8383569EA90F66AD850BA911DBC540A8D851050C173437A42069B`
SHA512 | `C95644E0C5255E36FFF2A67641DBD2235EFE2268ACC8F3BC6DFBE81A7A4FFC90FD99D2003C27D809FA0516CDE63D68F2DD2EC94DEB52870E82660D768F9A3DE0`
SSDEEP | `12288:CKyWgF3B0YvjxtdsTR8ZgOoqR+GizpAG:CKyWgfjxjsKZCq4/`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: QuickAssist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `quickassist.exe` being misused. While `quickassist.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) |       $s1 = "QuickAssist.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) |       $s4 = "name=\"QuickAssist\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


