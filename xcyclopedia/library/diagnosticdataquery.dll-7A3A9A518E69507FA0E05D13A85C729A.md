---
title: diagnosticdataquery.dll | Microsoft Windows Diagnostic data Helper API
excerpt: What is diagnosticdataquery.dll?
---

# diagnosticdataquery.dll 

* File Path: `C:\Windows\system32\diagnosticdataquery.dll`
* Description: Microsoft Windows Diagnostic data Helper API

## Hashes

Type | Hash
-- | --
MD5 | `7A3A9A518E69507FA0E05D13A85C729A`
SHA1 | `A15A8ECE8D95EDFABC6E6188DE10BCE10464B5D6`
SHA256 | `B4E33A516EFD14B1D719E149959FF3C8D1CBCF7C8128D4CEF164A685B3A3FAC6`
SHA384 | `6659C7518EA5DA697F7F2CDC988195E1755689F89B94C629D31B06F0A5BB92949155C886260B61BA2DC76D6791918E85`
SHA512 | `3FFB56E5B21FDFD1FA07417E5FB9688783D661473FECD8643A7CCFC924BD1B97B4F8FC8BD42CAA9A72A7192E970C2697297A7643C150E00262356A18B7DBC69C`
SSDEEP | `1536:qjGUoy9YeKvw9BsCPcRe/mpKKX7sn4asDRqVrjckL9q0O3P:byowfsCPcRe/mpKKLsn4asDRqVrjrRhq`
IMP | `A48853BD12994188BBB5D558ED96C168`
PESHA1 | `4E1E83596B446F3693A45C830D461BA2BD0D610F`
PE256 | `6F568E15D6E0F255B174C7AA2DCAE28D706D465EE70C00A459F82E0B743BFF7C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DdqCancelDiagnosticRecordOperation` | 1 (0x1) | Exported Function | 0x0000000180004e90 | 0x00004e90
`DdqGetDiagnosticRecordProducerAtIndex` | 21 (0x15) | Exported Function | 0x0000000180004800 | 0x00004800
`DdqGetDiagnosticRecordProducerCategories` | 22 (0x16) | Exported Function | 0x0000000180004850 | 0x00004850
`DdqGetDiagnosticRecordProducerCount` | 23 (0x17) | Exported Function | 0x0000000180004680 | 0x00004680
`DdqGetDiagnosticRecordProducers` | 24 (0x18) | Exported Function | 0x0000000180004690 | 0x00004690
`DdqGetDiagnosticRecordStats` | 25 (0x19) | Exported Function | 0x00000001800042f0 | 0x000042f0
`DdqGetDiagnosticRecordSummary` | 26 (0x1a) | Exported Function | 0x0000000180005460 | 0x00005460
`DdqGetDiagnosticRecordTagDistribution` | 27 (0x1b) | Exported Function | 0x0000000180005290 | 0x00005290
`DdqGetDiagnosticReport` | 28 (0x1c) | Exported Function | 0x0000000180004f30 | 0x00004f30
`DdqGetDiagnosticReportAtIndex` | 29 (0x1d) | Exported Function | 0x0000000180005190 | 0x00005190
`DdqGetDiagnosticReportCount` | 30 (0x1e) | Exported Function | 0x0000000180004680 | 0x00004680
`DdqGetDiagnosticReportStoreReportCount` | 31 (0x1f) | Exported Function | 0x0000000180004dd0 | 0x00004dd0
`DdqGetSessionAccessLevel` | 32 (0x20) | Exported Function | 0x00000001800041a0 | 0x000041a0
`DdqGetTranscriptConfiguration` | 33 (0x21) | Exported Function | 0x00000001800055e0 | 0x000055e0
`DdqIsDiagnosticRecordSampledIn` | 34 (0x22) | Exported Function | 0x0000000180004a20 | 0x00004a20
`DdqSetTranscriptConfiguration` | 35 (0x23) | Exported Function | 0x0000000180005530 | 0x00005530
`DdqGetDiagnosticRecordPayload` | 20 (0x14) | Exported Function | 0x00000001800043d0 | 0x000043d0
`UtcSendTraceLogging` | 36 (0x24) | Exported Function | 0x0000000180005690 | 0x00005690
`DdqGetDiagnosticRecordPage` | 19 (0x13) | Exported Function | 0x0000000180004b30 | 0x00004b30
`DdqGetDiagnosticRecordLocaleTagCount` | 17 (0x11) | Exported Function | 0x0000000180004680 | 0x00004680
`DdqCloseSession` | 2 (0x2) | Exported Function | 0x0000000180004110 | 0x00004110
`DdqCreateSession` | 3 (0x3) | Exported Function | 0x0000000180004020 | 0x00004020
`DdqExtractDiagnosticReport` | 4 (0x4) | Exported Function | 0x00000001800051c0 | 0x000051c0
`DdqFreeDiagnosticRecordLocaleTags` | 5 (0x5) | Exported Function | 0x0000000180004590 | 0x00004590
`DdqFreeDiagnosticRecordPage` | 6 (0x6) | Exported Function | 0x0000000180004c60 | 0x00004c60
`DdqFreeDiagnosticRecordProducerCategories` | 7 (0x7) | Exported Function | 0x0000000180004950 | 0x00004950
`DdqFreeDiagnosticRecordProducers` | 8 (0x8) | Exported Function | 0x0000000180004780 | 0x00004780
`DdqFreeDiagnosticReport` | 9 (0x9) | Exported Function | 0x0000000180005030 | 0x00005030
`DdqGetDiagnosticDataAccessLevelAllowed` | 10 (0xa) | Exported Function | 0x0000000180004260 | 0x00004260
`DdqGetDiagnosticRecordAtIndex` | 11 (0xb) | Exported Function | 0x0000000180004d40 | 0x00004d40
`DdqGetDiagnosticRecordBinaryDistribution` | 12 (0xc) | Exported Function | 0x0000000180005370 | 0x00005370
`DdqGetDiagnosticRecordCategoryAtIndex` | 13 (0xd) | Exported Function | 0x00000001800049d0 | 0x000049d0
`DdqGetDiagnosticRecordCategoryCount` | 14 (0xe) | Exported Function | 0x0000000180004680 | 0x00004680
`DdqGetDiagnosticRecordCount` | 15 (0xf) | Exported Function | 0x0000000180004680 | 0x00004680
`DdqGetDiagnosticRecordLocaleTagAtIndex` | 16 (0x10) | Exported Function | 0x0000000180004620 | 0x00004620
`DdqGetDiagnosticRecordLocaleTags` | 18 (0x12) | Exported Function | 0x0000000180004490 | 0x00004490
`UtcSendTraceLogging2` | 37 (0x25) | Exported Function | 0x00000001800057a0 | 0x000057a0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: diagnosticdataquery.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/b4e33a516efd14b1d719e149959ff3c8d1cbcf7c8128d4cef164a685b3a3fac6/detection/





MIT License. Copyright (c) 2020 Strontic.


