---
title: netid.dll | System Control Panel Applet; Network ID Page
excerpt: What is netid.dll?
---

# netid.dll 

* File Path: `C:\Windows\SysWOW64\netid.dll`
* Description: System Control Panel Applet; Network ID Page

## Hashes

Type | Hash
-- | --
MD5 | `1A40C5F9793BA5471AC61BF17B4395BB`
SHA1 | `FC185F33837EC6C3F1839AC353FD2A346B4566FA`
SHA256 | `77001BC53B170A0693A04A1C940622C8229A470BA9F8BF489F8AD598CAAABE73`
SHA384 | `F2488036D42583F678960654AD9934F2BD63B6CB0FFB22BFD1532FC34A6E739CE8CB90BDBFD03C1285BD9AA587D273D5`
SHA512 | `CFA6F8FB0FB1061703E1C8B56CBC59A55B229B0644E28D8EBBAC0CF30BF5FBF515104214F1CDAB94EC4E29E05CB4085AAE59B828201C20BF1CE23BD105E606CE`
SSDEEP | `3072:1+Y4nIRf2PuP5mis1vZkxQ5y/qs22Fb+:1XAPmSvZkxQ0f22N+`
IMP | `F36603C505E915471975CCA5C701168C`
PESHA1 | `2D6F83EFFF796674AEBA582D314338A457F81260`
PE256 | `3458FB71E14F352ACF64FDEA5C3A1428342332B677005D1DF0A111F3219AA6F0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ShowDcNotFoundErrorDialog` | 2 | Exported Function
`CreateNetIDPropertyPage` | 1 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/77001bc53b170a0693a04a1c940622c8229a470ba9f8bf489f8ad598caaabe73/detection/


## Possible Misuse

*The following table contains possible examples of `netid.dll` being misused. While `netid.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s2 = "$gotsunos = ($line =~ /program version netid     address             service         owner/ );" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "program version netid     address             service         owner" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


