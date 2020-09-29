---
title: winprint.dll | Windows Print Processor DLL
excerpt: What is winprint.dll?
---

# winprint.dll 

* File Path: `C:\Windows\system32\spool\prtprocs\x64\winprint.dll`
* Description: Windows Print Processor DLL

## Hashes

Type | Hash
-- | --
MD5 | `C871C667D837EF087F25F60611151985`
SHA1 | `B7DE0085AC517637057C562B9A29A9F53A64F7DE`
SHA256 | `C2459FC380BE114ED9D32310BCF31097389E46D13938E80C6A0E73D22E1B45C9`
SHA384 | `67172E4FC7C85ADB0480A18FFC34C8AB26166FB961C29401690E7FD4FE1D4E3BDB1839FF7196012BE4CCE6FA495636BC`
SHA512 | `E42D0F89AC5F089247082C288F449FDFED1E31A6C1ED456EFDEBDE02B561082713B171BE12BD99E466C8AD27294AA8E5E54B21F1BDD3D3889E47A8E870A2AA8C`
SSDEEP | `768:JA2SXV1ZWUl1ZqlOKAvGNnuVCj83wmFfh8eWjpwy4467YMlzIP69KBO6Ek:G2SJfl1ZqlOKAvGNnuVCjAZFf2RkYMFU`
IMP | `799E59190C67D88DAFF9AF7F3EB63090`
PESHA1 | `7862FCD13CDE51B04E0555939EB87C89512C69A7`
PE256 | `EBFC0132DDB3BB5C7AFD5B32D193432D014B69CBE0DE610C662F5F74B28FBF1C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ClosePrintProcessor` | 1 (0x1) | Exported Function | 0x00000001800035b0 | 0x000035b0
`ControlPrintProcessor` | 2 (0x2) | Exported Function | 0x00000001800036f0 | 0x000036f0
`DllMain` | 3 (0x3) | Exported Function | 0x0000000180001ea0 | 0x00001ea0
`EnumPrintProcessorDatatypesW` | 4 (0x4) | Exported Function | 0x0000000180001010 | 0x00001010
`GetPrintProcessorCapabilities` | 5 (0x5) | Exported Function | 0x0000000180003790 | 0x00003790
`OpenPrintProcessor` | 6 (0x6) | Exported Function | 0x00000001800038a0 | 0x000038a0
`PrintDocumentOnPrintProcessor` | 7 (0x7) | Exported Function | 0x0000000180003db0 | 0x00003db0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winprint.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/c2459fc380be114ed9d32310bcf31097389e46d13938e80c6a0e73d22e1b45c9/detection/


## Possible Misuse

*The following table contains possible examples of `winprint.dll` being misused. While `winprint.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [2020_Q2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2020_Q2/README.adoc) | `C:\Windows\System32\spool\prtprocs\x64\winprint.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


