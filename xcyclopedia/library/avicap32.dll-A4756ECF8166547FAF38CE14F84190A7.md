---
title: avicap32.dll | AVI Capture window class
excerpt: What is avicap32.dll?
---

# avicap32.dll 

* File Path: `C:\Windows\system32\avicap32.dll`
* Description: AVI Capture window class

## Hashes

Type | Hash
-- | --
MD5 | `A4756ECF8166547FAF38CE14F84190A7`
SHA1 | `F0713CC76FED32CD83E0157291863B0B89EDA8A6`
SHA256 | `4EE9EBF7459DEFD5901E6635BDF8DD9FBCC58D59AFFF0B14BE43098130C16D8C`
SHA384 | `C7A63EADD3D7CD416C522E7AFC4D6888FADE8BD1C9857D348A63B6752A8C4526CD31B0B8EA80DE65BCA95B068B79D9BA`
SHA512 | `929ACE605FB9DC1D846AFBE7FBD5DB14D3E522132A957D8FFD3A397DA8D1F6071AC98DF8079EE35091C0AA8D21FE6F8583999D95234CF37F139036A739F819C7`
SSDEEP | `1536:T7Vx8Vz88RlRFm1QeasJ0yJjILeNOeAqFR0CziSarX/lNHF3k/V:38Vz8o/Fm1JNJJJjgeNOeAqFR0C/aTlc`
IMP | `33EFAC2848CEEB098D1C78AA6F27477A`
PESHA1 | `C5795D23E3757E277E3299D0FCE3C945CBBD91AF`
PE256 | `13D6F56A661999BCBB6D9F51B1D0416DA54EBAB32B6540CA62A95E6F241786FC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`AppCleanup` | 1 | Exported Function
`capCreateCaptureWindowA` | 2 | Exported Function
`capCreateCaptureWindowW` | 3 | Exported Function
`capGetDriverDescriptionA` | 4 | Exported Function
`capGetDriverDescriptionW` | 5 | Exported Function
`videoThunk32` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AVICAP32.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/4ee9ebf7459defd5901e6635bdf8dd9fbcc58d59afff0b14be43098130c16d8c/detection/


## Possible Misuse

*The following table contains possible examples of `avicap32.dll` being misused. While `avicap32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_m.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_m.yar) | $a1 = "AVICAP32.DLL" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


