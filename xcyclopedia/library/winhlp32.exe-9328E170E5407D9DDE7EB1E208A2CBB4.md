---
title: winhlp32.exe | Windows Winhlp32 Stub
excerpt: What is winhlp32.exe?
---

# winhlp32.exe 

* File Path: `C:\Windows\winhlp32.exe`
* Description: Windows Winhlp32 Stub

## Hashes

Type | Hash
-- | --
MD5 | `9328E170E5407D9DDE7EB1E208A2CBB4`
SHA1 | `547D3D0772FBF36FB29C2B472928EFF1FC76C176`
SHA256 | `B32AD4D55CD16563908C3AD06B38020FDC9679FBF1BF8EDFFE747EE4122AF62E`
SHA384 | `F01DE1AA7978D43894CC076C65AD43FB2F828D2F71320490308CD764769E716C2F189C0DB761A40C7A6FDD7F11B3B8A4`
SHA512 | `5F58B4F770812355031781FCBC9C976BF079B810094A20E187ABC9384DB480C78FC87C0F9FE539A18C9C4DE1BD500B2D7FB497852D67DD3EC41B53036C32DBD1`
SSDEEP | `96:Ch6sdQqe9JXOlPoj1L9A2DWPToOJ+XNHr+NtgTvDJvkMp84NEWaJeHWwZhh4xqo:CUGQLXO7DTdCxrItgTJkDWIeHWmhh4j`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINHLP32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `winhlp32.exe` being misused. While `winhlp32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_korplug_fast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_korplug_fast.yar) | $s4 = "\\winhlp32.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


