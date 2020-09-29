---
title: wer.dll | Windows Error Reporting DLL
excerpt: What is wer.dll?
---

# wer.dll 

* File Path: `C:\Windows\system32\wer.dll`
* Description: Windows Error Reporting DLL

## Hashes

Type | Hash
-- | --
MD5 | `2C007A738EC5417F013B5E2B2384ED8D`
SHA1 | `F300E79CE406FCA2F3BF9189F55E58BD8BE3D7C5`
SHA256 | `9C78371A5DB35EFFC16AC34E217A47A27C280D5C1A6C5E6F7441B133B26ADFAA`
SHA384 | `ED7A2DB251A41DBEED747903D18165DC1EFC92C5BF391EBA6F2A587D5C70D951A9DD53CD66A06828543645C1DE4515BC`
SHA512 | `5B8E3B74E9A45F875749A7DE805EA9AACDDC9ABD6AFDB72C47438DDC14B50E3B2E986FBE4A053F9FE57A9752BEA923398E6A83CECDADCB21F3DA85FDEEB93575`
SSDEEP | `12288:VpwMfTv024dAN0xKo9ttC4lasd6efWrrs2nPqw8FU7D9PN:Vp3b8LdAN0xKovlaA68Wr5qFFU7DhN`
IMP | `94BF2D4D42A4CA3AFAE63E8E2E000DED`
PESHA1 | `E300907C5AAFB9B0BB0EE6B179562A2824B89C09`
PE256 | `EC7CCA29C26804F5BBBD3543F1F0CA85001B7C9C41E45DAE825050040B4D4319`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CloseThreadWaitChainSession` | 94 (0x5e) | Exported Function | 0x000000018005c4d0 | 0x0005c4d0
`WerpSetExitListeners` | 141 (0x8d) | Exported Function | 0x0000000180065ca0 | 0x00065ca0
`WerpSetIntegratorReportId` | 142 (0x8e) | Exported Function | 0x0000000180065d30 | 0x00065d30
`WerpSetIptEnabled` | 143 (0x8f) | Exported Function | 0x0000000180065da0 | 0x00065da0
`WerpSetProcessTimelines` | 68 (0x44) | Exported Function | 0x00000001800625a0 | 0x000625a0
`WerpSetQuickDumpType` | 69 (0x45) | Exported Function | 0x0000000180062610 | 0x00062610
`WerpSetReportApplicationIdentity` | 70 (0x46) | Exported Function | 0x0000000180062680 | 0x00062680
`WerpSetEventName` | 67 (0x43) | Exported Function | 0x0000000180062530 | 0x00062530
`WerpSetReportFlags` | 71 (0x47) | Exported Function | 0x00000001800626f0 | 0x000626f0
`WerpSetReportIsFatal` | 73 (0x49) | Exported Function | 0x00000001800627e0 | 0x000627e0
`WerpSetReportNamespaceParameter` | 74 (0x4a) | Exported Function | 0x0000000180062850 | 0x00062850
`WerpSetReportOption` | 144 (0x90) | Exported Function | 0x0000000180065e20 | 0x00065e20
`WerpSetReportTime` | 75 (0x4b) | Exported Function | 0x0000000180062940 | 0x00062940
`WerpSetReportUploadContextToken` | 76 (0x4c) | Exported Function | 0x00000001800629b0 | 0x000629b0
`WerpSetTelemetryAppParams` | 77 (0x4d) | Exported Function | 0x0000000180062a60 | 0x00062a60
`WerpSetReportInformation` | 72 (0x48) | Exported Function | 0x0000000180062750 | 0x00062750
`WerpSetTelemetryKernelParams` | 78 (0x4e) | Exported Function | 0x0000000180062af0 | 0x00062af0
`WerpSetDynamicParameter` | 66 (0x42) | Exported Function | 0x0000000180062430 | 0x00062430
`WerpSetCallBack` | 139 (0x8b) | Exported Function | 0x0000000180065a20 | 0x00065a20
`WerpIsTransportAvailable` | 54 (0x36) | Exported Function | 0x0000000180013950 | 0x00013950
`WerpLoadReport` | 137 (0x89) | Exported Function | 0x0000000180065970 | 0x00065970
`WerpLoadReportFromBuffer` | 55 (0x37) | Exported Function | 0x0000000180061450 | 0x00061450
`WerpOpenMachineArchive` | 56 (0x38) | Exported Function | 0x0000000180061670 | 0x00061670
`WerpOpenMachineQueue` | 57 (0x39) | Exported Function | 0x0000000180013770 | 0x00013770
`WerpPromptUser` | 58 (0x3a) | Exported Function | 0x0000000180061680 | 0x00061680
`WerpSetDefaultUserConsent` | 140 (0x8c) | Exported Function | 0x0000000180065a90 | 0x00065a90
`WerpPruneStore` | 59 (0x3b) | Exported Function | 0x00000001800616f0 | 0x000616f0
`WerpReportSetMaxProcessHoldMilliseconds` | 61 (0x3d) | Exported Function | 0x0000000180061840 | 0x00061840
`WerpReportSprintfParameter` | 62 (0x3e) | Exported Function | 0x00000001800618a0 | 0x000618a0
`WerpReserveMachineQueueReportDir` | 63 (0x3f) | Exported Function | 0x0000000180061990 | 0x00061990
`WerpResetTransientImageCacheStatistics` | 64 (0x40) | Exported Function | 0x0000000180065f60 | 0x00065f60
`WerpRestartApplication` | 65 (0x41) | Exported Function | 0x0000000180061bb0 | 0x00061bb0
`WerpSetAuxiliaryArchivePath` | 138 (0x8a) | Exported Function | 0x00000001800659a0 | 0x000659a0
`WerpReportCancel` | 60 (0x3c) | Exported Function | 0x00000001800617a0 | 0x000617a0
`WerpSetTelemetryServiceParams` | 79 (0x4f) | Exported Function | 0x0000000180062b50 | 0x00062b50
`WerpSetTtdStatus` | 145 (0x91) | Exported Function | 0x0000000180065ec0 | 0x00065ec0
`WerpShowUpsellUI` | 80 (0x50) | Exported Function | 0x0000000180062c00 | 0x00062c00
`WerReportSetUIOption` | 106 (0x6a) | Exported Function | 0x000000018005ddf0 | 0x0005ddf0
`WerReportSubmit` | 107 (0x6b) | Exported Function | 0x000000018005deb0 | 0x0005deb0
`WerStoreClose` | 108 (0x6c) | Exported Function | 0x00000001800638e0 | 0x000638e0
`WerStoreGetFirstReportKey` | 109 (0x6d) | Exported Function | 0x0000000180063970 | 0x00063970
`WerStoreGetNextReportKey` | 110 (0x6e) | Exported Function | 0x0000000180063ac0 | 0x00063ac0
`WerStoreGetReportCount` | 111 (0x6f) | Exported Function | 0x0000000180063c90 | 0x00063c90
`WerReportSetParameter` | 105 (0x69) | Exported Function | 0x000000018005dbe0 | 0x0005dbe0
`WerStoreGetSizeOnDisk` | 112 (0x70) | Exported Function | 0x0000000180063ca0 | 0x00063ca0
`WerStorePurge` | 114 (0x72) | Exported Function | 0x0000000180063f30 | 0x00063f30
`WerStoreQueryReportMetadataV1` | 115 (0x73) | Exported Function | 0x0000000180064180 | 0x00064180
`WerStoreQueryReportMetadataV2` | 116 (0x74) | Exported Function | 0x0000000180064560 | 0x00064560
`WerStoreQueryReportMetadataV3` | 117 (0x75) | Exported Function | 0x00000001800649d0 | 0x000649d0
`WerStoreUploadReport` | 118 (0x76) | Exported Function | 0x0000000180064e70 | 0x00064e70
`WerSysprepCleanup` | 1 (0x1) | Exported Function | 0x000000018005cfc0 | 0x0005cfc0
`WerStoreOpen` | 113 (0x71) | Exported Function | 0x0000000180063d40 | 0x00063d40
`WerReportCreate` | 104 (0x68) | Exported Function | 0x000000018003ba50 | 0x0003ba50
`WerReportCloseHandle` | 103 (0x67) | Exported Function | 0x00000001800130b0 | 0x000130b0
`WerReportAddFile` | 102 (0x66) | Exported Function | 0x000000018005daa0 | 0x0005daa0
`WerpStitchedMinidumpVmPostReadCallback` | 81 (0x51) | Exported Function | 0x0000000180015b70 | 0x00015b70
`WerpStitchedMinidumpVmPreReadCallback` | 82 (0x52) | Exported Function | 0x0000000180015900 | 0x00015900
`WerpStitchedMinidumpVmQueryCallback` | 83 (0x53) | Exported Function | 0x00000001800555d0 | 0x000555d0
`WerpSubmitReportFromStore` | 84 (0x54) | Exported Function | 0x0000000180012010 | 0x00012010
`WerpTraceAuxMemDumpStatistics` | 85 (0x55) | Exported Function | 0x0000000180062c50 | 0x00062c50
`WerpTraceDuration` | 86 (0x56) | Exported Function | 0x0000000180062da0 | 0x00062da0
`WerpTraceImageCacheStatistics` | 87 (0x57) | Exported Function | 0x0000000180062f90 | 0x00062f90
`WerpTraceSnapshotStatistics` | 88 (0x58) | Exported Function | 0x0000000180063220 | 0x00063220
`WerpTraceStitchedDumpWriterStatistics` | 89 (0x59) | Exported Function | 0x0000000180055640 | 0x00055640
`WerpTraceUnmappedVaRangesStatistics` | 90 (0x5a) | Exported Function | 0x0000000180063600 | 0x00063600
`WerpUnmapProcessViews` | 91 (0x5b) | Exported Function | 0x0000000180043240 | 0x00043240
`WerpValidateReportKey` | 92 (0x5c) | Exported Function | 0x00000001800636d0 | 0x000636d0
`WerpWalkGatherBlocks` | 93 (0x5d) | Exported Function | 0x000000018004d2e0 | 0x0004d2e0
`WerRemoveExcludedApplication` | 100 (0x64) | Exported Function | 0x000000018005d700 | 0x0005d700
`WerReportAddDump` | 101 (0x65) | Exported Function | 0x000000018005d8b0 | 0x0005d8b0
`WerpIsOnBattery` | 53 (0x35) | Exported Function | 0x00000001800611d0 | 0x000611d0
`WerSysprepGeneralize` | 2 (0x2) | Exported Function | 0x000000018005d080 | 0x0005d080
`WerpIsDisabled` | 136 (0x88) | Exported Function | 0x0000000180065880 | 0x00065880
`WerpHashApplicationParameters` | 51 (0x33) | Exported Function | 0x0000000180061090 | 0x00061090
`WerpAuxmdFree` | 125 (0x7d) | Exported Function | 0x000000018004a2f0 | 0x0004a2f0
`WerpAuxmdFreeCopyBuffer` | 126 (0x7e) | Exported Function | 0x0000000180066520 | 0x00066520
`WerpAuxmdHashVaRanges` | 127 (0x7f) | Exported Function | 0x0000000180039e20 | 0x00039e20
`WerpAuxmdInitialize` | 128 (0x80) | Exported Function | 0x0000000180066560 | 0x00066560
`WerpAuxmdMapFile` | 129 (0x81) | Exported Function | 0x0000000180066690 | 0x00066690
`WerpCancelUpload` | 11 (0xb) | Exported Function | 0x000000018005f1e0 | 0x0005f1e0
`WerpAuxmdDumpRegisteredBlocks` | 124 (0x7c) | Exported Function | 0x0000000180043a60 | 0x00043a60
`WerpCleanWer` | 12 (0xc) | Exported Function | 0x000000018005f280 | 0x0005f280
`WerpCreateIntegratorReportId` | 130 (0x82) | Exported Function | 0x0000000180065430 | 0x00065430
`WerpCreateMachineStore` | 14 (0xe) | Exported Function | 0x000000018004da90 | 0x0004da90
`WerpDeleteReport` | 15 (0xf) | Exported Function | 0x000000018005f560 | 0x0005f560
`WerpDestroyWerString` | 16 (0x10) | Exported Function | 0x00000001800512f0 | 0x000512f0
`WerpEnumerateStoreNext` | 17 (0x11) | Exported Function | 0x0000000180035460 | 0x00035460
`WerpEnumerateStoreStart` | 18 (0x12) | Exported Function | 0x000000018004f660 | 0x0004f660
`WerpCloseStore` | 13 (0xd) | Exported Function | 0x000000018005f4d0 | 0x0005f4d0
`WerpExtractReportFiles` | 131 (0x83) | Exported Function | 0x00000001800654d0 | 0x000654d0
`WerpAuxmdDumpProcessImages` | 123 (0x7b) | Exported Function | 0x0000000180014af0 | 0x00014af0
`WerpAddTerminationReason` | 122 (0x7a) | Exported Function | 0x0000000180034c90 | 0x00034c90
`GetThreadWaitChain` | 95 (0x5f) | Exported Function | 0x000000018005c560 | 0x0005c560
`OpenThreadWaitChainSession` | 96 (0x60) | Exported Function | 0x000000018005c760 | 0x0005c760
`RegisterWaitChainCOMCallback` | 97 (0x61) | Exported Function | 0x000000018005c880 | 0x0005c880
`WerAddExcludedApplication` | 98 (0x62) | Exported Function | 0x000000018005d510 | 0x0005d510
`WerFreeString` | 99 (0x63) | Exported Function | 0x00000001800638d0 | 0x000638d0
`WerpAddAppCompatData` | 4 (0x4) | Exported Function | 0x000000018005e380 | 0x0005e380
`WerpArchiveReport` | 10 (0xa) | Exported Function | 0x000000018005eed0 | 0x0005eed0
`WerpAddFile` | 119 (0x77) | Exported Function | 0x0000000180065150 | 0x00065150
`WerpAddFileCallback` | 121 (0x79) | Exported Function | 0x0000000180065330 | 0x00065330
`WerpAddIfRegisteredForAppLocalDump` | 5 (0x5) | Exported Function | 0x000000018005e7f0 | 0x0005e7f0
`WerpAddMemoryBlock` | 6 (0x6) | Exported Function | 0x000000018005e9e0 | 0x0005e9e0
`WerpAddRegisteredDataToReport` | 7 (0x7) | Exported Function | 0x0000000180043fa0 | 0x00043fa0
`WerpAddRegisteredDumpsToReport` | 8 (0x8) | Exported Function | 0x000000018005ebb0 | 0x0005ebb0
`WerpAddRegisteredMetadataToReport` | 9 (0x9) | Exported Function | 0x000000018005ed70 | 0x0005ed70
`WerpAddFileBuffer` | 120 (0x78) | Exported Function | 0x0000000180065230 | 0x00065230
`WerpFlushImageCache` | 19 (0x13) | Exported Function | 0x000000018004f7d0 | 0x0004f7d0
`WerpForceDeferredCollection` | 20 (0x14) | Exported Function | 0x000000018005f5d0 | 0x0005f5d0
`WerpFreeString` | 132 (0x84) | Exported Function | 0x0000000180065590 | 0x00065590
`WerpGetReportInformation` | 38 (0x26) | Exported Function | 0x0000000180060a10 | 0x00060a10
`WerpGetReportSettings` | 39 (0x27) | Exported Function | 0x0000000180060a80 | 0x00060a80
`WerpGetReportTime` | 40 (0x28) | Exported Function | 0x0000000180060b30 | 0x00060b30
`WerpGetReportType` | 41 (0x29) | Exported Function | 0x0000000180060ba0 | 0x00060ba0
`WerpGetResponseId` | 42 (0x2a) | Exported Function | 0x0000000180060c10 | 0x00060c10
`WerpGetSigParamByIndex` | 43 (0x2b) | Exported Function | 0x0000000180060cb0 | 0x00060cb0
`WerpGetReportId` | 37 (0x25) | Exported Function | 0x00000001800513e0 | 0x000513e0
`WerpGetStoreLocation` | 135 (0x87) | Exported Function | 0x0000000180065750 | 0x00065750
`WerpGetStoreType` | 45 (0x2d) | Exported Function | 0x0000000180060d40 | 0x00060d40
`WerpGetTextFromReport` | 46 (0x2e) | Exported Function | 0x0000000180060e10 | 0x00060e10
`WerpGetUIParamByIndex` | 47 (0x2f) | Exported Function | 0x0000000180060e90 | 0x00060e90
`WerpGetUploadTime` | 48 (0x30) | Exported Function | 0x0000000180060f60 | 0x00060f60
`WerpGetWerStringData` | 49 (0x31) | Exported Function | 0x0000000180060fe0 | 0x00060fe0
`WerpGetWow64Process` | 50 (0x32) | Exported Function | 0x0000000180061000 | 0x00061000
`WerpGetStorePath` | 44 (0x2c) | Exported Function | 0x00000001800396b0 | 0x000396b0
`WerpGetReportFlags` | 36 (0x24) | Exported Function | 0x0000000180060980 | 0x00060980
`WerpGetReportFinalConsent` | 35 (0x23) | Exported Function | 0x0000000180060910 | 0x00060910
`WerpGetReportCount` | 34 (0x22) | Exported Function | 0x0000000180060870 | 0x00060870
`WerpFreeUnmappedVaRanges` | 21 (0x15) | Exported Function | 0x000000018005f800 | 0x0005f800
`WerpGetBucketId` | 22 (0x16) | Exported Function | 0x000000018005f9b0 | 0x0005f9b0
`WerpGetDynamicParameter` | 23 (0x17) | Exported Function | 0x000000018005fb00 | 0x0005fb00
`WerpGetEventType` | 24 (0x18) | Exported Function | 0x000000018005fc10 | 0x0005fc10
`WerpGetExtendedDiagData` | 25 (0x19) | Exported Function | 0x000000018005fc90 | 0x0005fc90
`WerpGetFileByIndex` | 26 (0x1a) | Exported Function | 0x000000018005ff40 | 0x0005ff40
`WerpGetFilePathByIndex` | 27 (0x1b) | Exported Function | 0x0000000180060060 | 0x00060060
`WerpGetIntegratorReportId` | 133 (0x85) | Exported Function | 0x00000001800655c0 | 0x000655c0
`WerpGetLegacyBucketId` | 28 (0x1c) | Exported Function | 0x0000000180060140 | 0x00060140
`WerpGetLoadedModuleByIndex` | 29 (0x1d) | Exported Function | 0x0000000180060290 | 0x00060290
`WerpGetNumFiles` | 30 (0x1e) | Exported Function | 0x0000000180060360 | 0x00060360
`WerpGetNumLoadedModules` | 31 (0x1f) | Exported Function | 0x0000000180060400 | 0x00060400
`WerpGetNumSigParams` | 32 (0x20) | Exported Function | 0x0000000180060470 | 0x00060470
`WerpGetPathOfWERTempDirectory` | 33 (0x21) | Exported Function | 0x00000001800604f0 | 0x000604f0
`WerpGetReportConsent` | 134 (0x86) | Exported Function | 0x0000000180065630 | 0x00065630
`WerpInitializeImageCache` | 52 (0x34) | Exported Function | 0x0000000180065f20 | 0x00065f20
`WerUnattendedSetup` | 3 (0x3) | Exported Function | 0x000000018005d1a0 | 0x0005d1a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wer.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/9c78371a5db35effc16ac34e217a47a27c280d5c1a6c5e6f7441b133b26adfaa/detection/





MIT License. Copyright (c) 2020 Strontic.


