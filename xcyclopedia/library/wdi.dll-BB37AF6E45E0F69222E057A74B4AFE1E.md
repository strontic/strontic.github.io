---
title: wdi.dll | Windows Diagnostic Infrastructure
excerpt: What is wdi.dll?
---

# wdi.dll 

* File Path: `C:\Windows\system32\wdi.dll`
* Description: Windows Diagnostic Infrastructure

## Hashes

Type | Hash
-- | --
MD5 | `BB37AF6E45E0F69222E057A74B4AFE1E`
SHA1 | `E6250B2107824B4398AE408925C10B7AF9799C99`
SHA256 | `4662064205BEC0DB7B10F1412E0A09A6E5E3B16DE443AEF7F79ACA3ACE24A51D`
SHA384 | `9BAACD22A17B2EE0916B984BF88F4954D492F13B39D83475492E4FA743EFBE934E527F6CE47E17154B15A05B0B4D28F6`
SHA512 | `C40D576B2AB066D50E30EDCF5EFFE58D1AAFB0C65F98F33174C06FDF0D234FAA367B2D11B67FFAB24C8AEEC21BF9E3A0F696814088EFC95438C550D31E7394E1`
SSDEEP | `1536:d6l6s8JTAZWsRHt/5oq3NWUC/xzYNK+UYJZyTN/rC/6xyc:4l6f8ZTHuUC/x7+NJIR/rGAyc`
IMP | `F5F0239F47BAC201511EE4D14D60CB60`
PESHA1 | `4DEB79B3612672D742633F9F2E23B9D175979292`
PE256 | `3412B9881364257911092BC98EC648F8CFAC584D0DFE5D65DE905BE14D36D99C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 3 (0x3) | Exported Function | 0x0000000180011ab0 | 0x00011ab0
`WdiGetQueuedResolutionId` | 30 (0x1e) | Exported Function | 0x000000018000e080 | 0x0000e080
`WdiGetQueuedResolutionName` | 31 (0x1f) | Exported Function | 0x000000018000e150 | 0x0000e150
`WdiGetQueuedResolutionPriority` | 32 (0x20) | Exported Function | 0x000000018000e430 | 0x0000e430
`WdiGetResult` | 33 (0x21) | Exported Function | 0x000000018000be20 | 0x0000be20
`WdiGetScenarioIcon` | 34 (0x22) | Exported Function | 0x000000018000e500 | 0x0000e500
`WdiGetScenarioInfo` | 35 (0x23) | Exported Function | 0x0000000180005090 | 0x00005090
`WdiGetScenarioInstanceCreatedDate` | 36 (0x24) | Exported Function | 0x000000018000e7c0 | 0x0000e7c0
`WdiGetScenarioInstanceFilePath` | 37 (0x25) | Exported Function | 0x000000018000e890 | 0x0000e890
`WdiGetScenarioInstanceId` | 38 (0x26) | Exported Function | 0x000000018000ead0 | 0x0000ead0
`WdiGetScenarioInstances` | 39 (0x27) | Exported Function | 0x000000018000eba0 | 0x0000eba0
`WdiGetScenarioSourceName` | 40 (0x28) | Exported Function | 0x000000018000ec80 | 0x0000ec80
`WdiGetScenarioTypeName` | 41 (0x29) | Exported Function | 0x000000018000ef60 | 0x0000ef60
`WdiImpersonateClient` | 42 (0x2a) | Exported Function | 0x000000018000beb0 | 0x0000beb0
`WdiIsQueuedResolutionAdmin` | 43 (0x2b) | Exported Function | 0x000000018000f240 | 0x0000f240
`WdiLaunchQueuedResolution` | 44 (0x2c) | Exported Function | 0x000000018000f310 | 0x0000f310
`WdiOpenInstance` | 45 (0x2d) | Exported Function | 0x000000018000f430 | 0x0000f430
`WdipLaunchLocalHost` | 53 (0x35) | Exported Function | 0x0000000180011c00 | 0x00011c00
`WdipLaunchRunDLLUserHost` | 2 (0x2) | Exported Function | 0x0000000180011790 | 0x00011790
`WdiQueueCurrentResolution` | 46 (0x2e) | Exported Function | 0x000000018000bf90 | 0x0000bf90
`WdiResolve` | 47 (0x2f) | Exported Function | 0x000000018000f4f0 | 0x0000f4f0
`WdiRevertToSelf` | 48 (0x30) | Exported Function | 0x000000018000c080 | 0x0000c080
`WdiSetFeedback` | 49 (0x31) | Exported Function | 0x000000018000c0a0 | 0x0000c0a0
`WdiSetProblemDetectionResult` | 50 (0x32) | Exported Function | 0x0000000180004080 | 0x00004080
`WdiGetQueuedResolutionExpirationDate` | 29 (0x1d) | Exported Function | 0x000000018000df90 | 0x0000df90
`WdiSetProgress` | 51 (0x33) | Exported Function | 0x000000018000c160 | 0x0000c160
`WdiGetQueuedResolutionAudience` | 28 (0x1c) | Exported Function | 0x000000018000dec0 | 0x0000dec0
`WdiGetParameterName` | 26 (0x1a) | Exported Function | 0x000000018000bcd0 | 0x0000bcd0
`DllGetClassObject` | 4 (0x4) | Exported Function | 0x0000000180011ad0 | 0x00011ad0
`ServiceMain` | 1 (0x1) | Exported Function | 0x000000018000a080 | 0x0000a080
`WdiAddFileToInstance` | 5 (0x5) | Exported Function | 0x000000018000b250 | 0x0000b250
`WdiAddParameter` | 6 (0x6) | Exported Function | 0x0000000180004180 | 0x00004180
`WdiCancel` | 7 (0x7) | Exported Function | 0x000000018000d560 | 0x0000d560
`WdiCloseInstance` | 8 (0x8) | Exported Function | 0x000000018000d630 | 0x0000d630
`WdiCreateInstance` | 9 (0x9) | Exported Function | 0x000000018000d800 | 0x0000d800
`WdiDeleteQueuedResolution` | 10 (0xa) | Exported Function | 0x000000018000db00 | 0x0000db00
`WdiDiagnose` | 11 (0xb) | Exported Function | 0x000000018000dc20 | 0x0000dc20
`WdiGetClientActivityId` | 12 (0xc) | Exported Function | 0x000000018000b480 | 0x0000b480
`WdiGetClientLCID` | 13 (0xd) | Exported Function | 0x000000018000b520 | 0x0000b520
`WdiGetDiagnosticModuleId` | 14 (0xe) | Exported Function | 0x0000000180004020 | 0x00004020
`WdiGetEvent` | 15 (0xf) | Exported Function | 0x0000000180003ef0 | 0x00003ef0
`WdiGetInstanceFilePath` | 16 (0x10) | Exported Function | 0x000000018000b5c0 | 0x0000b5c0
`WdiGetInstanceId` | 17 (0x11) | Exported Function | 0x000000018000b800 | 0x0000b800
`WdiGetLoggerSnapshotPath` | 18 (0x12) | Exported Function | 0x00000001800034e0 | 0x000034e0
`WdiGetParameterByIndex` | 19 (0x13) | Exported Function | 0x0000000180005170 | 0x00005170
`WdiGetParameterByName` | 20 (0x14) | Exported Function | 0x000000018000b8a0 | 0x0000b8a0
`WdiGetParameterCount` | 21 (0x15) | Exported Function | 0x000000018000bad0 | 0x0000bad0
`WdiGetParameterData` | 22 (0x16) | Exported Function | 0x0000000180005230 | 0x00005230
`WdiGetParameterDataLength` | 23 (0x17) | Exported Function | 0x000000018000bba0 | 0x0000bba0
`WdiGetParameterDiagnosticModuleId` | 24 (0x18) | Exported Function | 0x000000018000bc00 | 0x0000bc00
`WdiGetParameterFlags` | 25 (0x19) | Exported Function | 0x000000018000bc70 | 0x0000bc70
`WdiGetProgress` | 27 (0x1b) | Exported Function | 0x000000018000dd70 | 0x0000dd70
`WdiSetResolution` | 52 (0x34) | Exported Function | 0x000000018000c2b0 | 0x0000c2b0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wdi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/4662064205bec0db7b10f1412e0a09a6e5e3b16de443aef7f79aca3ace24a51d/detection/





MIT License. Copyright (c) 2020 Strontic.


