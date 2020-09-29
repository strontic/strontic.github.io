---
title: reseteng.dll | Microsoft Windows Reset Engine
excerpt: What is reseteng.dll?
---

# reseteng.dll 

* File Path: `C:\Windows\system32\reseteng.dll`
* Description: Microsoft Windows Reset Engine

## Hashes

Type | Hash
-- | --
MD5 | `F1DF62DFAFE8537CCA2E7C7601EA8188`
SHA1 | `7B09E93E7C9BD0008CF93FB0B33E798EB1ACA146`
SHA256 | `315B8C49747B51FADBFF702C7C94544AEB5ADA66F7899865691F184F89DBB6C9`
SHA384 | `545DC83FFFA2874ECFFEB7F5A39610657878AD0CB6D11328765678E1A5B63FC78C2D21AE67E88168721D976926323BE2`
SHA512 | `5B45AA658B710C576080FF7A9E2179C9DBBA0AEAA5B68434747B6BF3D808CA4880CBC1A738AA60C9455C63CECDB1788BF1820DC90A773DD82DF78C205EBC37E9`
SSDEEP | `24576:KKeCyPPHN7vsSW1LEgJmdEJvURoMosUbp:KKeCylodJmWJvqA`
IMP | `4B9E2631D81054582EB6E6A7D8EB0B2B`
PESHA1 | `9BBEF5FBBBE47509EC25AEF67CDEB89A3EF24A8C`
PE256 | `30D0A8F69AC1654D3EDE16456C5EF7409E022D3FDB4391E6A4A8502166EADE18`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`RjvApplyData` | 1 (0x1) | Exported Function | 0x0000000180005a60 | 0x00005a60
`RjvLogSuccessEntryPoint` | 29 (0x1d) | Exported Function | 0x0000000180009d70 | 0x00009d70
`RjvOfflineCleanup` | 30 (0x1e) | Exported Function | 0x00000001800093e0 | 0x000093e0
`RjvPDeleteFilesFromVolumeBeforeWimApply` | 31 (0x1f) | Exported Function | 0x00000001800227d0 | 0x000227d0
`RjvPEraseVolume` | 32 (0x20) | Exported Function | 0x00000001800238e0 | 0x000238e0
`RjvPolicyAllowsReset` | 33 (0x21) | Exported Function | 0x0000000180003d60 | 0x00003d60
`RjvPostApplyDataEntryPoint` | 34 (0x22) | Exported Function | 0x000000018000a380 | 0x0000a380
`RjvPreApplyDataEntryPoint` | 35 (0x23) | Exported Function | 0x000000018000a0f0 | 0x0000a0f0
`RjvPrepareForReset` | 36 (0x24) | Exported Function | 0x0000000180004d40 | 0x00004d40
`RjvReInitializeEngine` | 37 (0x25) | Exported Function | 0x00000001800029f0 | 0x000029f0
`RjvRePartitionSystemDisk` | 38 (0x26) | Exported Function | 0x000000018000d0e0 | 0x0000d0e0
`RjvLogFailureEntryPoint` | 28 (0x1c) | Exported Function | 0x0000000180009f80 | 0x00009f80
`RjvRePartitionSystemDiskEx` | 39 (0x27) | Exported Function | 0x000000018000d430 | 0x0000d430
`RjvSaveState` | 41 (0x29) | Exported Function | 0x0000000180009200 | 0x00009200
`RjvSendCancelEvent` | 42 (0x2a) | Exported Function | 0x0000000180003550 | 0x00003550
`RjvSetCloudRecInfo` | 43 (0x2b) | Exported Function | 0x000000018000d020 | 0x0000d020
`RjvStageBasicReset` | 44 (0x2c) | Exported Function | 0x0000000180009960 | 0x00009960
`RjvStartLogging` | 45 (0x2d) | Exported Function | 0x0000000180002150 | 0x00002150
`RjvStopLogging` | 46 (0x2e) | Exported Function | 0x0000000180002300 | 0x00002300
`RjvSysResetErrBasicEntryPoint` | 47 (0x2f) | Exported Function | 0x000000018000a520 | 0x0000a520
`RjvSysResetErrFactoryEntryPoint` | 48 (0x30) | Exported Function | 0x000000018000a4a0 | 0x0000a4a0
`RjvTestFunction` | 49 (0x31) | Exported Function | 0x000000018000cfb0 | 0x0000cfb0
`RjvUndoPrepareForReset` | 50 (0x32) | Exported Function | 0x00000001800052d0 | 0x000052d0
`RjvRollBack` | 40 (0x28) | Exported Function | 0x0000000180006260 | 0x00006260
`RjvLoadState` | 27 (0x1b) | Exported Function | 0x0000000180008e80 | 0x00008e80
`RjvIsCloudRec` | 26 (0x1a) | Exported Function | 0x000000018000d010 | 0x0000d010
`RjvInitializeSystemPartitionInfo` | 25 (0x19) | Exported Function | 0x000000018000d2b0 | 0x0000d2b0
`RjvApplyDataEntryPoint` | 2 (0x2) | Exported Function | 0x000000018000a040 | 0x0000a040
`RjvBareMetalResetAvailable` | 3 (0x3) | Exported Function | 0x0000000180003950 | 0x00003950
`RjvBasicReset` | 4 (0x4) | Exported Function | 0x00000001800053d0 | 0x000053d0
`RjvBasicResetChecks` | 5 (0x5) | Exported Function | 0x0000000180004180 | 0x00004180
`RjvCheckBattery` | 6 (0x6) | Exported Function | 0x0000000180007e30 | 0x00007e30
`RjvCheckBitLocker` | 7 (0x7) | Exported Function | 0x0000000180007fa0 | 0x00007fa0
`RjvCheckDiskSpace` | 8 (0x8) | Exported Function | 0x00000001800080e0 | 0x000080e0
`RjvCheckOsHealth` | 9 (0x9) | Exported Function | 0x0000000180008390 | 0x00008390
`RjvCheckWinRE` | 10 (0xa) | Exported Function | 0x0000000180007640 | 0x00007640
`RjvCleanup` | 11 (0xb) | Exported Function | 0x0000000180006020 | 0x00006020
`RjvCommitReset` | 12 (0xc) | Exported Function | 0x0000000180009b90 | 0x00009b90
`RjvCreateSuccessTaskEntryPoint` | 13 (0xd) | Exported Function | 0x0000000180009d00 | 0x00009d00
`RjvDelayedCleanup` | 14 (0xe) | Exported Function | 0x00000001800063d0 | 0x000063d0
`RjvDelayedCleanupEntryPoint` | 15 (0xf) | Exported Function | 0x0000000180009d60 | 0x00009d60
`RjvFactoryImageAvailable` | 16 (0x10) | Exported Function | 0x0000000180003650 | 0x00003650
`RjvFactoryReset` | 17 (0x11) | Exported Function | 0x0000000180005640 | 0x00005640
`RjvFactoryResetChecks` | 18 (0x12) | Exported Function | 0x0000000180004570 | 0x00004570
`RjvFinalize` | 19 (0x13) | Exported Function | 0x0000000180009cb0 | 0x00009cb0
`RjvGenerateImageBasedBMRConfigData` | 20 (0x14) | Exported Function | 0x0000000180007600 | 0x00007600
`RjvGenerateReconstructionBMRConfigData` | 21 (0x15) | Exported Function | 0x0000000180007620 | 0x00007620
`RjvGetCloudRecInfo` | 22 (0x16) | Exported Function | 0x000000018000d080 | 0x0000d080
`RjvGetVolumeInfo` | 23 (0x17) | Exported Function | 0x0000000180008960 | 0x00008960
`RjvInitializeEngine` | 24 (0x18) | Exported Function | 0x0000000180002360 | 0x00002360
`RjvUninitializeEngine` | 51 (0x33) | Exported Function | 0x0000000180003480 | 0x00003480
`RjvVerifySystemDiskInfo` | 52 (0x34) | Exported Function | 0x0000000180004a10 | 0x00004a10


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reseteng.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/315b8c49747b51fadbff702c7c94544aeb5ada66f7899865691f184f89dbb6c9/detection/





MIT License. Copyright (c) 2020 Strontic.


