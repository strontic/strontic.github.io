---
title: cliconfg.dll | SQL Client Configuration Utility DLL
excerpt: What is cliconfg.dll?
---

# cliconfg.dll 

* File Path: `C:\Windows\SysWOW64\cliconfg.dll`
* Description: SQL Client Configuration Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `5AE732C0CBD2DE4157BA6273579DB241`
SHA1 | `77724558F2B36644D9DBB228D5A6000BB26D6666`
SHA256 | `BB1C2BD6E5BF047077C0EE742CDAC75BC89F212C47610CF1B2F2F1755F0A4F8B`
SHA384 | `691297BC4283DC4B21617E88180FE7E2BCA354B6B4D0F6D6BABAE4C1FB497E026DDBE76A3AE80B5D8786341986A1D34B`
SHA512 | `46243CE749A2DB2D1965CC7AD783A84AA317B0E129B894AE2BAEC652AE18D7D4D7FD193F86610E9021DB979C9993C0958B60275EC05A0540BBB8973E4D79C536`
SSDEEP | `768:NrVe9TYPg/NGXIQgD78A5A/33EcLl3Je8yu9SDWCZ3PrIfd+8Ec:NBDgwXIFD78A5O3EchtC3PrIfd+f`
IMP | `53F65086939C218E4B0724487D136A40`
PESHA1 | `350BAC8DD26465D76DE963CF253E549D7B4EB844`
PE256 | `31F48031046FE93AF1582EEF89B52814610ACBC416E6FB4AA3D34CBF0D4968AA`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ClientConfigureAddEdit` | 2 (0x2) | Exported Function | 0x100096a0 | 0x000096a0
`CPlApplet` | 1 (0x1) | Exported Function | 0x100095d0 | 0x000095d0
`OnInitDialogMain` | 3 (0x3) | Exported Function | 0x10009ba0 | 0x00009ba0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cliconfg.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/bb1c2bd6e5bf047077c0ee742cdac75bc89f212c47610cf1b2f2f1755f0a4f8b/detection/


## Possible Misuse

*The following table contains possible examples of `cliconfg.dll` being misused. While `cliconfg.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


