---
title: wdi.dll | Windows Diagnostic Infrastructure
excerpt: What is wdi.dll?
---

# wdi.dll 

* File Path: `C:\Windows\SysWOW64\wdi.dll`
* Description: Windows Diagnostic Infrastructure

## Hashes

Type | Hash
-- | --
MD5 | `7D326B235AB064FF70376F1D015CC084`
SHA1 | `3B394E93EF206D30FAFBF3202A5A63A4B6667580`
SHA256 | `404DDA0BDF9A6C1C61653CF7E965F504B3A3A3B662F88C906AAA19A9C3DF160C`
SHA384 | `503EE2021DC74DAD7B24B563C1D5E43801572C5E4C1EFBC5A8DFE6F622BB0B9D8B8CD64E4EC04595EEE37FA2812FB784`
SHA512 | `F33FACE04507EDD462B40DFD0771DA3F241374C99FC956DEF9678A05C15BF5F8C945579006AB250646120A7F983FE4A57B55C93BDF921142F6464BC74FEE2347`
SSDEEP | `1536:2xg+XurUE+dlamMsyhirFoNZ5MtDPQEInpF6qbTyuVKiRoTnd5Zatd2nZXBjVym4:2x5XXdMTsyhirFoNZ5MtDIBpFtvLASoy`
IMP | `D2C5AD65DE7676505E640AF8A127B32B`
PESHA1 | `0BE1B4095B645559310FE5AACD6812791B6DF517`
PE256 | `35F00977566C5D632AEB262F36CF5EB2F97A86C1A30F378AEA80D5AD34FB1F46`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 3 (0x3) | Exported Function | 0x100115b0 | 0x000115b0
`WdiGetQueuedResolutionId` | 30 (0x1e) | Exported Function | 0x1000e430 | 0x0000e430
`WdiGetQueuedResolutionName` | 31 (0x1f) | Exported Function | 0x1000e520 | 0x0000e520
`WdiGetQueuedResolutionPriority` | 32 (0x20) | Exported Function | 0x1000e780 | 0x0000e780
`WdiGetResult` | 33 (0x21) | Exported Function | 0x1000ca80 | 0x0000ca80
`WdiGetScenarioIcon` | 34 (0x22) | Exported Function | 0x1000e870 | 0x0000e870
`WdiGetScenarioInfo` | 35 (0x23) | Exported Function | 0x10006a20 | 0x00006a20
`WdiGetScenarioInstanceCreatedDate` | 36 (0x24) | Exported Function | 0x1000eab0 | 0x0000eab0
`WdiGetScenarioInstanceFilePath` | 37 (0x25) | Exported Function | 0x1000eba0 | 0x0000eba0
`WdiGetScenarioInstanceId` | 38 (0x26) | Exported Function | 0x1000ed90 | 0x0000ed90
`WdiGetScenarioInstances` | 39 (0x27) | Exported Function | 0x1000ee80 | 0x0000ee80
`WdiGetScenarioSourceName` | 40 (0x28) | Exported Function | 0x1000ef70 | 0x0000ef70
`WdiGetScenarioTypeName` | 41 (0x29) | Exported Function | 0x1000f1d0 | 0x0000f1d0
`WdiImpersonateClient` | 42 (0x2a) | Exported Function | 0x1000cb00 | 0x0000cb00
`WdiIsQueuedResolutionAdmin` | 43 (0x2b) | Exported Function | 0x1000f430 | 0x0000f430
`WdiLaunchQueuedResolution` | 44 (0x2c) | Exported Function | 0x1000f520 | 0x0000f520
`WdiOpenInstance` | 45 (0x2d) | Exported Function | 0x1000f630 | 0x0000f630
`WdipLaunchLocalHost` | 53 (0x35) | Exported Function | 0x10006cc0 | 0x00006cc0
`WdipLaunchRunDLLUserHost` | 2 (0x2) | Exported Function | 0x10011300 | 0x00011300
`WdiQueueCurrentResolution` | 46 (0x2e) | Exported Function | 0x1000cbe0 | 0x0000cbe0
`WdiResolve` | 47 (0x2f) | Exported Function | 0x1000f6e0 | 0x0000f6e0
`WdiRevertToSelf` | 48 (0x30) | Exported Function | 0x1000ccc0 | 0x0000ccc0
`WdiSetFeedback` | 49 (0x31) | Exported Function | 0x1000ccd0 | 0x0000ccd0
`WdiSetProblemDetectionResult` | 50 (0x32) | Exported Function | 0x10005f40 | 0x00005f40
`WdiGetQueuedResolutionExpirationDate` | 29 (0x1d) | Exported Function | 0x1000e330 | 0x0000e330
`WdiSetProgress` | 51 (0x33) | Exported Function | 0x1000cd80 | 0x0000cd80
`WdiGetQueuedResolutionAudience` | 28 (0x1c) | Exported Function | 0x1000e240 | 0x0000e240
`WdiGetParameterName` | 26 (0x1a) | Exported Function | 0x1000c940 | 0x0000c940
`DllGetClassObject` | 4 (0x4) | Exported Function | 0x100115d0 | 0x000115d0
`ServiceMain` | 1 (0x1) | Exported Function | 0x10006e70 | 0x00006e70
`WdiAddFileToInstance` | 5 (0x5) | Exported Function | 0x1000bff0 | 0x0000bff0
`WdiAddParameter` | 6 (0x6) | Exported Function | 0x10006030 | 0x00006030
`WdiCancel` | 7 (0x7) | Exported Function | 0x1000da80 | 0x0000da80
`WdiCloseInstance` | 8 (0x8) | Exported Function | 0x1000db40 | 0x0000db40
`WdiCreateInstance` | 9 (0x9) | Exported Function | 0x1000dca0 | 0x0000dca0
`WdiDeleteQueuedResolution` | 10 (0xa) | Exported Function | 0x1000ded0 | 0x0000ded0
`WdiDiagnose` | 11 (0xb) | Exported Function | 0x1000dfe0 | 0x0000dfe0
`WdiGetClientActivityId` | 12 (0xc) | Exported Function | 0x1000c1e0 | 0x0000c1e0
`WdiGetClientLCID` | 13 (0xd) | Exported Function | 0x1000c270 | 0x0000c270
`WdiGetDiagnosticModuleId` | 14 (0xe) | Exported Function | 0x10005ee0 | 0x00005ee0
`WdiGetEvent` | 15 (0xf) | Exported Function | 0x10005dc0 | 0x00005dc0
`WdiGetInstanceFilePath` | 16 (0x10) | Exported Function | 0x1000c310 | 0x0000c310
`WdiGetInstanceId` | 17 (0x11) | Exported Function | 0x1000c500 | 0x0000c500
`WdiGetLoggerSnapshotPath` | 18 (0x12) | Exported Function | 0x100054c0 | 0x000054c0
`WdiGetParameterByIndex` | 19 (0x13) | Exported Function | 0x10006ae0 | 0x00006ae0
`WdiGetParameterByName` | 20 (0x14) | Exported Function | 0x1000c590 | 0x0000c590
`WdiGetParameterCount` | 21 (0x15) | Exported Function | 0x1000c750 | 0x0000c750
`WdiGetParameterData` | 22 (0x16) | Exported Function | 0x10006b60 | 0x00006b60
`WdiGetParameterDataLength` | 23 (0x17) | Exported Function | 0x1000c820 | 0x0000c820
`WdiGetParameterDiagnosticModuleId` | 24 (0x18) | Exported Function | 0x1000c880 | 0x0000c880
`WdiGetParameterFlags` | 25 (0x19) | Exported Function | 0x1000c8e0 | 0x0000c8e0
`WdiGetProgress` | 27 (0x1b) | Exported Function | 0x1000e100 | 0x0000e100
`WdiSetResolution` | 52 (0x34) | Exported Function | 0x1000cec0 | 0x0000cec0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wdi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/404dda0bdf9a6c1c61653cf7e965f504b3a3a3b662f88c906aaa19a9c3df160c/detection/





MIT License. Copyright (c) 2020 Strontic.


