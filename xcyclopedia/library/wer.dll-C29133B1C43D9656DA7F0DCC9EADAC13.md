---
title: wer.dll | Windows Error Reporting DLL
excerpt: What is wer.dll?
---

# wer.dll 

* File Path: `C:\Windows\SysWOW64\wer.dll`
* Description: Windows Error Reporting DLL

## Hashes

Type | Hash
-- | --
MD5 | `C29133B1C43D9656DA7F0DCC9EADAC13`
SHA1 | `D24CF7B558EBCD21AB2BB497B14BCA831BB95192`
SHA256 | `390D49D1BDAC820F6C81F0554FA540FFC488B7BBC96420AE6A73CBBC33C45FF4`
SHA384 | `E70388D5BDC08F852DDE1AEC341E7A606DA7AF0F8E7CD30CB6548E8BE3107A97939BBCFC4E820FD1EF778ADFF160F844`
SHA512 | `CC6F5DF3C4F238113FAF169F0B6219B05972C32E24AE36CEAEDF3873CC9B2CA13232AD9461DA9B9ABD45336205273269DD37D6E808C16D29708541C2152CE2E0`
SSDEEP | `12288:q/TnmwA0SCACwjPla7wvl1XBKPrVvHr5rduMM2n+nj7lOAA7dGjnq/utVa7Wh9Vv:qTmwfSCtwpa7q1XBSrVwHnj5Ov7dniVp`
IMP | `BF660163C387FA39D89FEF2BB304765A`
PESHA1 | `5D74E75572D45C6D92A8DE6FE53579C082B21CAA`
PE256 | `1A7F3D7295DE7D9D72A2528E231C1F2F6DBB25F96812D8D777D35436E7331943`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CloseThreadWaitChainSession` | 94 (0x5e) | Exported Function | 0x1001cf50 | 0x0001cf50
`WerpSetExitListeners` | 141 (0x8d) | Exported Function | 0x10027550 | 0x00027550
`WerpSetIntegratorReportId` | 142 (0x8e) | Exported Function | 0x10024430 | 0x00024430
`WerpSetIptEnabled` | 143 (0x8f) | Exported Function | 0x100243c0 | 0x000243c0
`WerpSetProcessTimelines` | 68 (0x44) | Exported Function | 0x10025210 | 0x00025210
`WerpSetQuickDumpType` | 69 (0x45) | Exported Function | 0x100272a0 | 0x000272a0
`WerpSetReportApplicationIdentity` | 70 (0x46) | Exported Function | 0x10025040 | 0x00025040
`WerpSetEventName` | 67 (0x43) | Exported Function | 0x10023380 | 0x00023380
`WerpSetReportFlags` | 71 (0x47) | Exported Function | 0x100233e0 | 0x000233e0
`WerpSetReportIsFatal` | 73 (0x49) | Exported Function | 0x10027240 | 0x00027240
`WerpSetReportNamespaceParameter` | 74 (0x4a) | Exported Function | 0x10024bc0 | 0x00024bc0
`WerpSetReportOption` | 144 (0x90) | Exported Function | 0x100271c0 | 0x000271c0
`WerpSetReportTime` | 75 (0x4b) | Exported Function | 0x10020f00 | 0x00020f00
`WerpSetReportUploadContextToken` | 76 (0x4c) | Exported Function | 0x10021df0 | 0x00021df0
`WerpSetTelemetryAppParams` | 77 (0x4d) | Exported Function | 0x100250b0 | 0x000250b0
`WerpSetReportInformation` | 72 (0x48) | Exported Function | 0x100220f0 | 0x000220f0
`WerpSetTelemetryKernelParams` | 78 (0x4e) | Exported Function | 0x100251b0 | 0x000251b0
`WerpSetDynamicParameter` | 66 (0x42) | Exported Function | 0x10021e80 | 0x00021e80
`WerpSetCallBack` | 139 (0x8b) | Exported Function | 0x10022180 | 0x00022180
`WerpIsTransportAvailable` | 54 (0x36) | Exported Function | 0x10021900 | 0x00021900
`WerpLoadReport` | 137 (0x89) | Exported Function | 0x10020540 | 0x00020540
`WerpLoadReportFromBuffer` | 55 (0x37) | Exported Function | 0x10020570 | 0x00020570
`WerpOpenMachineArchive` | 56 (0x38) | Exported Function | 0x1001f920 | 0x0001f920
`WerpOpenMachineQueue` | 57 (0x39) | Exported Function | 0x1001f5f0 | 0x0001f5f0
`WerpPromptUser` | 58 (0x3a) | Exported Function | 0x10022400 | 0x00022400
`WerpSetDefaultUserConsent` | 140 (0x8c) | Exported Function | 0x100246a0 | 0x000246a0
`WerpPruneStore` | 59 (0x3b) | Exported Function | 0x10024880 | 0x00024880
`WerpReportSetMaxProcessHoldMilliseconds` | 61 (0x3d) | Exported Function | 0x100275c0 | 0x000275c0
`WerpReportSprintfParameter` | 62 (0x3e) | Exported Function | 0x10024e70 | 0x00024e70
`WerpReserveMachineQueueReportDir` | 63 (0x3f) | Exported Function | 0x10024c40 | 0x00024c40
`WerpResetTransientImageCacheStatistics` | 64 (0x40) | Exported Function | 0x10027df0 | 0x00027df0
`WerpRestartApplication` | 65 (0x41) | Exported Function | 0x10022ca0 | 0x00022ca0
`WerpSetAuxiliaryArchivePath` | 138 (0x8a) | Exported Function | 0x10024ea0 | 0x00024ea0
`WerpReportCancel` | 60 (0x3c) | Exported Function | 0x100241c0 | 0x000241c0
`WerpSetTelemetryServiceParams` | 79 (0x4f) | Exported Function | 0x10025130 | 0x00025130
`WerpSetTtdStatus` | 145 (0x91) | Exported Function | 0x10027300 | 0x00027300
`WerpShowUpsellUI` | 80 (0x50) | Exported Function | 0x10023f50 | 0x00023f50
`WerReportSetUIOption` | 106 (0x6a) | Exported Function | 0x1001e4b0 | 0x0001e4b0
`WerReportSubmit` | 107 (0x6b) | Exported Function | 0x1001e550 | 0x0001e550
`WerStoreClose` | 108 (0x6c) | Exported Function | 0x10025fd0 | 0x00025fd0
`WerStoreGetFirstReportKey` | 109 (0x6d) | Exported Function | 0x10026050 | 0x00026050
`WerStoreGetNextReportKey` | 110 (0x6e) | Exported Function | 0x10026160 | 0x00026160
`WerStoreGetReportCount` | 111 (0x6f) | Exported Function | 0x10026300 | 0x00026300
`WerReportSetParameter` | 105 (0x69) | Exported Function | 0x1001e0d0 | 0x0001e0d0
`WerStoreGetSizeOnDisk` | 112 (0x70) | Exported Function | 0x10026310 | 0x00026310
`WerStorePurge` | 114 (0x72) | Exported Function | 0x10024940 | 0x00024940
`WerStoreQueryReportMetadataV1` | 115 (0x73) | Exported Function | 0x100263a0 | 0x000263a0
`WerStoreQueryReportMetadataV2` | 116 (0x74) | Exported Function | 0x10026730 | 0x00026730
`WerStoreQueryReportMetadataV3` | 117 (0x75) | Exported Function | 0x10026b60 | 0x00026b60
`WerStoreUploadReport` | 118 (0x76) | Exported Function | 0x10026f50 | 0x00026f50
`WerSysprepCleanup` | 1 (0x1) | Exported Function | 0x1001eeb0 | 0x0001eeb0
`WerStoreOpen` | 113 (0x71) | Exported Function | 0x10025e40 | 0x00025e40
`WerReportCreate` | 104 (0x68) | Exported Function | 0x1001d9a0 | 0x0001d9a0
`WerReportCloseHandle` | 103 (0x67) | Exported Function | 0x1001e7e0 | 0x0001e7e0
`WerReportAddFile` | 102 (0x66) | Exported Function | 0x1001e310 | 0x0001e310
`WerpStitchedMinidumpVmPostReadCallback` | 81 (0x51) | Exported Function | 0x10028b50 | 0x00028b50
`WerpStitchedMinidumpVmPreReadCallback` | 82 (0x52) | Exported Function | 0x10028c80 | 0x00028c80
`WerpStitchedMinidumpVmQueryCallback` | 83 (0x53) | Exported Function | 0x100283a0 | 0x000283a0
`WerpSubmitReportFromStore` | 84 (0x54) | Exported Function | 0x10020600 | 0x00020600
`WerpTraceAuxMemDumpStatistics` | 85 (0x55) | Exported Function | 0x10025820 | 0x00025820
`WerpTraceDuration` | 86 (0x56) | Exported Function | 0x10025ad0 | 0x00025ad0
`WerpTraceImageCacheStatistics` | 87 (0x57) | Exported Function | 0x10025930 | 0x00025930
`WerpTraceSnapshotStatistics` | 88 (0x58) | Exported Function | 0x10025490 | 0x00025490
`WerpTraceStitchedDumpWriterStatistics` | 89 (0x59) | Exported Function | 0x10025ac0 | 0x00025ac0
`WerpTraceUnmappedVaRangesStatistics` | 90 (0x5a) | Exported Function | 0x100257a0 | 0x000257a0
`WerpUnmapProcessViews` | 91 (0x5b) | Exported Function | 0x10025270 | 0x00025270
`WerpValidateReportKey` | 92 (0x5c) | Exported Function | 0x10024d70 | 0x00024d70
`WerpWalkGatherBlocks` | 93 (0x5d) | Exported Function | 0x10023c40 | 0x00023c40
`WerRemoveExcludedApplication` | 100 (0x64) | Exported Function | 0x1001ebf0 | 0x0001ebf0
`WerReportAddDump` | 101 (0x65) | Exported Function | 0x1001e680 | 0x0001e680
`WerpIsOnBattery` | 53 (0x35) | Exported Function | 0x10024b20 | 0x00024b20
`WerSysprepGeneralize` | 2 (0x2) | Exported Function | 0x1001ed40 | 0x0001ed40
`WerpIsDisabled` | 136 (0x88) | Exported Function | 0x10024250 | 0x00024250
`WerpHashApplicationParameters` | 51 (0x33) | Exported Function | 0x10024f10 | 0x00024f10
`WerpAuxmdFree` | 125 (0x7d) | Exported Function | 0x10029ec0 | 0x00029ec0
`WerpAuxmdFreeCopyBuffer` | 126 (0x7e) | Exported Function | 0x10029e90 | 0x00029e90
`WerpAuxmdHashVaRanges` | 127 (0x7f) | Exported Function | 0x10029b70 | 0x00029b70
`WerpAuxmdInitialize` | 128 (0x80) | Exported Function | 0x10029dc0 | 0x00029dc0
`WerpAuxmdMapFile` | 129 (0x81) | Exported Function | 0x10029d40 | 0x00029d40
`WerpCancelUpload` | 11 (0xb) | Exported Function | 0x10022570 | 0x00022570
`WerpAuxmdDumpRegisteredBlocks` | 124 (0x7c) | Exported Function | 0x10029a50 | 0x00029a50
`WerpCleanWer` | 12 (0xc) | Exported Function | 0x100214d0 | 0x000214d0
`WerpCreateIntegratorReportId` | 130 (0x82) | Exported Function | 0x100245e0 | 0x000245e0
`WerpCreateMachineStore` | 14 (0xe) | Exported Function | 0x1001f4a0 | 0x0001f4a0
`WerpDeleteReport` | 15 (0xf) | Exported Function | 0x100205a0 | 0x000205a0
`WerpDestroyWerString` | 16 (0x10) | Exported Function | 0x1001ff90 | 0x0001ff90
`WerpEnumerateStoreNext` | 17 (0x11) | Exported Function | 0x10020030 | 0x00020030
`WerpEnumerateStoreStart` | 18 (0x12) | Exported Function | 0x1001ffd0 | 0x0001ffd0
`WerpCloseStore` | 13 (0xd) | Exported Function | 0x10020170 | 0x00020170
`WerpExtractReportFiles` | 131 (0x83) | Exported Function | 0x10022940 | 0x00022940
`WerpAuxmdDumpProcessImages` | 123 (0x7b) | Exported Function | 0x100294f0 | 0x000294f0
`WerpAddTerminationReason` | 122 (0x7a) | Exported Function | 0x1001f340 | 0x0001f340
`GetThreadWaitChain` | 95 (0x5f) | Exported Function | 0x1001cfb0 | 0x0001cfb0
`OpenThreadWaitChainSession` | 96 (0x60) | Exported Function | 0x1001ce90 | 0x0001ce90
`RegisterWaitChainCOMCallback` | 97 (0x61) | Exported Function | 0x1001cdf0 | 0x0001cdf0
`WerAddExcludedApplication` | 98 (0x62) | Exported Function | 0x1001ea80 | 0x0001ea80
`WerFreeString` | 99 (0x63) | Exported Function | 0x10025e30 | 0x00025e30
`WerpAddAppCompatData` | 4 (0x4) | Exported Function | 0x10022600 | 0x00022600
`WerpArchiveReport` | 10 (0xa) | Exported Function | 0x10023f80 | 0x00023f80
`WerpAddFile` | 119 (0x77) | Exported Function | 0x10021a90 | 0x00021a90
`WerpAddFileCallback` | 121 (0x79) | Exported Function | 0x10021bf0 | 0x00021bf0
`WerpAddIfRegisteredForAppLocalDump` | 5 (0x5) | Exported Function | 0x10023570 | 0x00023570
`WerpAddMemoryBlock` | 6 (0x6) | Exported Function | 0x10021ca0 | 0x00021ca0
`WerpAddRegisteredDataToReport` | 7 (0x7) | Exported Function | 0x100239b0 | 0x000239b0
`WerpAddRegisteredDumpsToReport` | 8 (0x8) | Exported Function | 0x10023850 | 0x00023850
`WerpAddRegisteredMetadataToReport` | 9 (0x9) | Exported Function | 0x10023720 | 0x00023720
`WerpAddFileBuffer` | 120 (0x78) | Exported Function | 0x10021b40 | 0x00021b40
`WerpFlushImageCache` | 19 (0x13) | Exported Function | 0x10027cf0 | 0x00027cf0
`WerpForceDeferredCollection` | 20 (0x14) | Exported Function | 0x10025c40 | 0x00025c40
`WerpFreeString` | 132 (0x84) | Exported Function | 0x10024670 | 0x00024670
`WerpGetReportInformation` | 38 (0x26) | Exported Function | 0x10022090 | 0x00022090
`WerpGetReportSettings` | 39 (0x27) | Exported Function | 0x10024320 | 0x00024320
`WerpGetReportTime` | 40 (0x28) | Exported Function | 0x10020e40 | 0x00020e40
`WerpGetReportType` | 41 (0x29) | Exported Function | 0x100223a0 | 0x000223a0
`WerpGetResponseId` | 42 (0x2a) | Exported Function | 0x10020dc0 | 0x00020dc0
`WerpGetSigParamByIndex` | 43 (0x2b) | Exported Function | 0x10020cf0 | 0x00020cf0
`WerpGetReportId` | 37 (0x25) | Exported Function | 0x10024500 | 0x00024500
`WerpGetStoreLocation` | 135 (0x87) | Exported Function | 0x100221e0 | 0x000221e0
`WerpGetStoreType` | 45 (0x2d) | Exported Function | 0x100222f0 | 0x000222f0
`WerpGetTextFromReport` | 46 (0x2e) | Exported Function | 0x10022020 | 0x00022020
`WerpGetUIParamByIndex` | 47 (0x2f) | Exported Function | 0x10020d60 | 0x00020d60
`WerpGetUploadTime` | 48 (0x30) | Exported Function | 0x10020ea0 | 0x00020ea0
`WerpGetWerStringData` | 49 (0x31) | Exported Function | 0x1001ff70 | 0x0001ff70
`WerpGetWow64Process` | 50 (0x32) | Exported Function | 0x10024810 | 0x00024810
`WerpGetStorePath` | 44 (0x2c) | Exported Function | 0x1001f940 | 0x0001f940
`WerpGetReportFlags` | 36 (0x24) | Exported Function | 0x10023440 | 0x00023440
`WerpGetReportFinalConsent` | 35 (0x23) | Exported Function | 0x10022510 | 0x00022510
`WerpGetReportCount` | 34 (0x22) | Exported Function | 0x100200e0 | 0x000200e0
`WerpFreeUnmappedVaRanges` | 21 (0x15) | Exported Function | 0x10025460 | 0x00025460
`WerpGetBucketId` | 22 (0x16) | Exported Function | 0x10020f60 | 0x00020f60
`WerpGetDynamicParameter` | 23 (0x17) | Exported Function | 0x10021f40 | 0x00021f40
`WerpGetEventType` | 24 (0x18) | Exported Function | 0x10020c30 | 0x00020c30
`WerpGetExtendedDiagData` | 25 (0x19) | Exported Function | 0x10023cf0 | 0x00023cf0
`WerpGetFileByIndex` | 26 (0x1a) | Exported Function | 0x100213f0 | 0x000213f0
`WerpGetFilePathByIndex` | 27 (0x1b) | Exported Function | 0x10021290 | 0x00021290
`WerpGetIntegratorReportId` | 133 (0x85) | Exported Function | 0x10024490 | 0x00024490
`WerpGetLegacyBucketId` | 28 (0x1c) | Exported Function | 0x10021080 | 0x00021080
`WerpGetLoadedModuleByIndex` | 29 (0x1d) | Exported Function | 0x10021340 | 0x00021340
`WerpGetNumFiles` | 30 (0x1e) | Exported Function | 0x100211a0 | 0x000211a0
`WerpGetNumLoadedModules` | 31 (0x1f) | Exported Function | 0x10021230 | 0x00021230
`WerpGetNumSigParams` | 32 (0x20) | Exported Function | 0x10020c90 | 0x00020c90
`WerpGetPathOfWERTempDirectory` | 33 (0x21) | Exported Function | 0x1001fb80 | 0x0001fb80
`WerpGetReportConsent` | 134 (0x86) | Exported Function | 0x10022430 | 0x00022430
`WerpInitializeImageCache` | 52 (0x34) | Exported Function | 0x10027db0 | 0x00027db0
`WerUnattendedSetup` | 3 (0x3) | Exported Function | 0x1001ef80 | 0x0001ef80


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wer.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/390d49d1bdac820f6c81f0554fa540ffc488b7bbc96420ae6a73cbbc33c45ff4/detection/





MIT License. Copyright (c) 2020 Strontic.


