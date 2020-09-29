---
title: diagnosticdataquery.dll | Microsoft Windows Diagnostic data Helper API
excerpt: What is diagnosticdataquery.dll?
---

# diagnosticdataquery.dll 

* File Path: `C:\Windows\SysWOW64\diagnosticdataquery.dll`
* Description: Microsoft Windows Diagnostic data Helper API

## Hashes

Type | Hash
-- | --
MD5 | `D5729BBC33EAC82C1D8489EB3811F439`
SHA1 | `F87DE78C2E8B4BDB67C02F07D97F12FB140DFCFE`
SHA256 | `050AFA84E2CD1C2BCE741F64F5AC68573BD6656AE509A440A784DBF1F44BF303`
SHA384 | `3C08C58AC6C9E2AD066B70712ED478448AE10283EDBEFBAEF18F283F0C24534C9C488B4ED145FCC31A7A320D7E14579E`
SHA512 | `DEBA04099E42A820DB75D27F26E123FBD5B626BAD8C44A4B75795E6052370A61B9753A0BA1EEB3601E017CA14E79BD3EAC913DE7C8043039BB96B5431FACD8B8`
SSDEEP | `768:D19YOFeGmy/eFhT4SS7cd3303h4wg53T:D19leGmL4STHYh4t53`
IMP | `99CC85852E572A9CCEB41EB74ABABC7E`
PESHA1 | `714D9F2C7C2A14DED1E3DA27918E0D2AE62002E0`
PE256 | `058CA12ADC1947B4008D3A690342369F093251329A23A617BFE5086BA9D2342B`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DdqCancelDiagnosticRecordOperation` | 1 (0x1) | Exported Function | 0x100050a0 | 0x000050a0
`DdqGetDiagnosticRecordProducerAtIndex` | 21 (0x15) | Exported Function | 0x10004c50 | 0x00004c50
`DdqGetDiagnosticRecordProducerCategories` | 22 (0x16) | Exported Function | 0x10004ca0 | 0x00004ca0
`DdqGetDiagnosticRecordProducerCount` | 23 (0x17) | Exported Function | 0x10004b30 | 0x00004b30
`DdqGetDiagnosticRecordProducers` | 24 (0x18) | Exported Function | 0x10004b50 | 0x00004b50
`DdqGetDiagnosticRecordStats` | 25 (0x19) | Exported Function | 0x100048b0 | 0x000048b0
`DdqGetDiagnosticRecordSummary` | 26 (0x1a) | Exported Function | 0x10005490 | 0x00005490
`DdqGetDiagnosticRecordTagDistribution` | 27 (0x1b) | Exported Function | 0x10005370 | 0x00005370
`DdqGetDiagnosticReport` | 28 (0x1c) | Exported Function | 0x10005120 | 0x00005120
`DdqGetDiagnosticReportAtIndex` | 29 (0x1d) | Exported Function | 0x100052b0 | 0x000052b0
`DdqGetDiagnosticReportCount` | 30 (0x1e) | Exported Function | 0x10004b30 | 0x00004b30
`DdqGetDiagnosticReportStoreReportCount` | 31 (0x1f) | Exported Function | 0x10005020 | 0x00005020
`DdqGetSessionAccessLevel` | 32 (0x20) | Exported Function | 0x10004790 | 0x00004790
`DdqGetTranscriptConfiguration` | 33 (0x21) | Exported Function | 0x100055a0 | 0x000055a0
`DdqIsDiagnosticRecordSampledIn` | 34 (0x22) | Exported Function | 0x10004df0 | 0x00004df0
`DdqSetTranscriptConfiguration` | 35 (0x23) | Exported Function | 0x10005520 | 0x00005520
`DdqGetDiagnosticRecordPayload` | 20 (0x14) | Exported Function | 0x10004940 | 0x00004940
`UtcSendTraceLogging` | 37 (0x25) | Exported Function | 0x10005620 | 0x00005620
`DdqGetDiagnosticRecordPage` | 19 (0x13) | Exported Function | 0x10004e90 | 0x00004e90
`DdqGetDiagnosticRecordLocaleTagCount` | 17 (0x11) | Exported Function | 0x10004b30 | 0x00004b30
`DdqCloseSession` | 2 (0x2) | Exported Function | 0x10004700 | 0x00004700
`DdqCreateSession` | 3 (0x3) | Exported Function | 0x10004640 | 0x00004640
`DdqExtractDiagnosticReport` | 4 (0x4) | Exported Function | 0x100052e0 | 0x000052e0
`DdqFreeDiagnosticRecordLocaleTags` | 5 (0x5) | Exported Function | 0x10004a80 | 0x00004a80
`DdqFreeDiagnosticRecordPage` | 6 (0x6) | Exported Function | 0x10004f50 | 0x00004f50
`DdqFreeDiagnosticRecordProducerCategories` | 7 (0x7) | Exported Function | 0x10004d50 | 0x00004d50
`DdqFreeDiagnosticRecordProducers` | 8 (0x8) | Exported Function | 0x10004c00 | 0x00004c00
`DdqFreeDiagnosticReport` | 9 (0x9) | Exported Function | 0x100051d0 | 0x000051d0
`DdqGetDiagnosticDataAccessLevelAllowed` | 10 (0xa) | Exported Function | 0x10004830 | 0x00004830
`DdqGetDiagnosticRecordAtIndex` | 11 (0xb) | Exported Function | 0x10004fd0 | 0x00004fd0
`DdqGetDiagnosticRecordBinaryDistribution` | 12 (0xc) | Exported Function | 0x10005400 | 0x00005400
`DdqGetDiagnosticRecordCategoryAtIndex` | 13 (0xd) | Exported Function | 0x10004da0 | 0x00004da0
`DdqGetDiagnosticRecordCategoryCount` | 14 (0xe) | Exported Function | 0x10004b30 | 0x00004b30
`DdqGetDiagnosticRecordCount` | 15 (0xf) | Exported Function | 0x10004b30 | 0x00004b30
`DdqGetDiagnosticRecordLocaleTagAtIndex` | 16 (0x10) | Exported Function | 0x10004ae0 | 0x00004ae0
`DdqGetDiagnosticRecordLocaleTags` | 18 (0x12) | Exported Function | 0x100049d0 | 0x000049d0
`UtcSendTraceLogging2` | 36 (0x24) | Exported Function | 0x100056d0 | 0x000056d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: diagnosticdataquery.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/050afa84e2cd1c2bce741f64f5ac68573bd6656ae509a440a784dbf1f44bf303/detection/





MIT License. Copyright (c) 2020 Strontic.


