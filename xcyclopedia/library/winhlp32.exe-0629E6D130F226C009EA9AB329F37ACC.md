---
title: winhlp32.exe | Windows Winhlp32 Stub
---

# winhlp32.exe 

* File Path: `C:\Windows\winhlp32.exe`
* Description: Windows Winhlp32 Stub

## Hashes

Type | Hash
-- | --
MD5 | `0629E6D130F226C009EA9AB329F37ACC`
SHA1 | `1529C6CF3265311B690992DC975443B35177BC7C`
SHA256 | `4FCE997BDD3475C42BA856D8C288FD4F9F91FD1370075AD7E0B11B1E71AE69CE`
SHA384 | `5ACC4C750A0CAC12E69E652967BAB059D050AC71533F4157176ABB3967D80D9D68A33DC57108BDC9AC5DB76FE0BB7563`
SHA512 | `A36F25CD5B79891F0CC5A8E85636CE4EF10C91EC6D6C7C0F5C5B622D0AF1F4F400C864D331CAFFAA8A51D9A2734777B5B9CE87CABB7667A9ACEAF8837E88C847`
SSDEEP | `192:ZomhYgSgGvZx5qdoth1Pdk7WneHWGhh4j8q05:L67gGnP7q7WneHWGhh44q`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINHLP32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `winhlp32.exe` being misused. While `winhlp32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_korplug_fast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_korplug_fast.yar) |         $s4 = "\\winhlp32.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


