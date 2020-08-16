---
title: quickassist.exe | Quick Assist
---

# quickassist.exe 

* File Path: `C:\Windows\SysWOW64\quickassist.exe`
* Description: Quick Assist

## Screenshot

![quickassist.exe](screenshots/quickassist.exe-39AB5ED601B0C39DCE3B7D269847C944-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `F0F3390CF55DB6E7DA129BCE57EEE967`
SHA1 | `58E24C9C74FB0CF4C4FFBD20EE124979BFD8D9E9`
SHA256 | `023155542B86DC9E1DEDAADC2FCA0F5DE90153C529508C25C63A7E3B3FBA958C`
SHA384 | `D5F2E548ACCD7554D7EA5EB6017AC7A73C03E5497E94FD3BA93C741873BB38B07E42514776272BFCED94D769595D757A`
SHA512 | `910D3D877B368D375D41A2C1657295D7A792DC6BC0BD3C0568A9BCC66C345D38C8F25B00A0AC13B10E8C23429DA58416567C8AF6CE0249A9E87CD77C686ABDF8`
SSDEEP | `6144:Fv8MWXWlPSrhGwtSD+UCytmwa8QprGDYjeB+NYXW:Fv8MWXWlqrRkDqsYrUIeBvX`

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


