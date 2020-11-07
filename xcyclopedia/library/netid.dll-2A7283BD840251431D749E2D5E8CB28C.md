---
title: netid.dll | System Control Panel Applet; Network ID Page
excerpt: What is netid.dll?
---

# netid.dll 

* File Path: `C:\Windows\system32\netid.dll`
* Description: System Control Panel Applet; Network ID Page

## Hashes

Type | Hash
-- | --
MD5 | `2A7283BD840251431D749E2D5E8CB28C`
SHA1 | `FF5E6132C92C4CBE91E7A21A5E6616CCDE5D2D09`
SHA256 | `81B352D2C1D792D4BE00D351E0EC9CB67907D1BB4DB53CA17E7DB036BB653CC9`
SHA384 | `E9F318E834347D561F0568DA5C1D3DA7084D3B4EFFAD44493B2129A38AE712212BC4BF6CC263061A4E97F244987F442E`
SHA512 | `F4003983616B418AB6BE1FF7548911CC36F2A8CBAB91666CAFE91A5FE726DE3319EC761E83F0EE084FE3E5CB106834EC54E123641C9A89427AE8D1B6CAFC6D1A`
SSDEEP | `3072:mHdApfY+x9ooW5P8B8e6K2n5BU4wKmZT3+dP6v7NFn2jqwh:mHdApw+x9I5P8B8ekBU4wK4bR72j`
IMP | `D58D33EC1C072FD3255D20F3C5EC4584`
PESHA1 | `8022FBE95829E9DAE7B6FF628002BE1138839B61`
PE256 | `941C7A1D36508F3E108AE9DB2C8F4BCC259A65C4D2D877A36ECDD4873817DDA9`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CreateNetIDPropertyPage` | 1 | Exported Function
`ShowDcNotFoundErrorDialog` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netid.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/81b352d2c1d792d4be00d351e0ec9cb67907d1bb4db53ca17e7db036bb653cc9/detection/


## Possible Misuse

*The following table contains possible examples of `netid.dll` being misused. While `netid.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s2 = "$gotsunos = ($line =~ /program version netid     address             service         owner/ );" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "program version netid     address             service         owner" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


