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

Function Name | Ordinal | Type
-- | -- | --
`WerpSetReportApplicationIdentity` | 70 | Exported Function
`WerpSetQuickDumpType` | 69 | Exported Function
`WerpSetReportInformation` | 72 | Exported Function
`WerpSetReportFlags` | 71 | Exported Function
`WerpSetProcessTimelines` | 68 | Exported Function
`WerpSetExitListeners` | 141 | Exported Function
`WerpSetEventName` | 67 | Exported Function
`WerpSetIptEnabled` | 143 | Exported Function
`WerpSetIntegratorReportId` | 142 | Exported Function
`WerpSetTelemetryKernelParams` | 78 | Exported Function
`WerpSetTelemetryAppParams` | 77 | Exported Function
`WerpSetTtdStatus` | 145 | Exported Function
`WerpSetTelemetryServiceParams` | 79 | Exported Function
`WerpSetReportUploadContextToken` | 76 | Exported Function
`WerpSetReportNamespaceParameter` | 74 | Exported Function
`WerpSetReportIsFatal` | 73 | Exported Function
`WerpSetReportTime` | 75 | Exported Function
`WerpSetReportOption` | 144 | Exported Function
`WerpPromptUser` | 58 | Exported Function
`WerpOpenMachineQueue` | 57 | Exported Function
`WerpReportCancel` | 60 | Exported Function
`WerpPruneStore` | 59 | Exported Function
`WerpOpenMachineArchive` | 56 | Exported Function
`WerpIsTransportAvailable` | 54 | Exported Function
`WerpIsOnBattery` | 53 | Exported Function
`WerpLoadReportFromBuffer` | 55 | Exported Function
`WerpLoadReport` | 137 | Exported Function
`WerpSetCallBack` | 139 | Exported Function
`WerpSetAuxiliaryArchivePath` | 138 | Exported Function
`WerpSetDynamicParameter` | 66 | Exported Function
`WerpSetDefaultUserConsent` | 140 | Exported Function
`WerpRestartApplication` | 65 | Exported Function
`WerpReportSprintfParameter` | 62 | Exported Function
`WerpReportSetMaxProcessHoldMilliseconds` | 61 | Exported Function
`WerpResetTransientImageCacheStatistics` | 64 | Exported Function
`WerpReserveMachineQueueReportDir` | 63 | Exported Function
`WerStoreGetNextReportKey` | 110 | Exported Function
`WerStoreGetFirstReportKey` | 109 | Exported Function
`WerStoreGetSizeOnDisk` | 112 | Exported Function
`WerStoreGetReportCount` | 111 | Exported Function
`WerStoreClose` | 108 | Exported Function
`WerReportSetParameter` | 105 | Exported Function
`WerReportCreate` | 104 | Exported Function
`WerReportSubmit` | 107 | Exported Function
`WerReportSetUIOption` | 106 | Exported Function
`WerSysprepCleanup` | 1 | Exported Function
`WerStoreUploadReport` | 118 | Exported Function
`WerUnattendedSetup` | 3 | Exported Function
`WerSysprepGeneralize` | 2 | Exported Function
`WerStoreQueryReportMetadataV3` | 117 | Exported Function
`WerStorePurge` | 114 | Exported Function
`WerStoreOpen` | 113 | Exported Function
`WerStoreQueryReportMetadataV2` | 116 | Exported Function
`WerStoreQueryReportMetadataV1` | 115 | Exported Function
`WerpTraceDuration` | 86 | Exported Function
`WerpTraceAuxMemDumpStatistics` | 85 | Exported Function
`WerpTraceSnapshotStatistics` | 88 | Exported Function
`WerpTraceImageCacheStatistics` | 87 | Exported Function
`WerpSubmitReportFromStore` | 84 | Exported Function
`WerpStitchedMinidumpVmPostReadCallback` | 81 | Exported Function
`WerpShowUpsellUI` | 80 | Exported Function
`WerpStitchedMinidumpVmQueryCallback` | 83 | Exported Function
`WerpStitchedMinidumpVmPreReadCallback` | 82 | Exported Function
`WerReportAddDump` | 101 | Exported Function
`WerRemoveExcludedApplication` | 100 | Exported Function
`WerReportCloseHandle` | 103 | Exported Function
`WerReportAddFile` | 102 | Exported Function
`WerpWalkGatherBlocks` | 93 | Exported Function
`WerpTraceUnmappedVaRangesStatistics` | 90 | Exported Function
`WerpTraceStitchedDumpWriterStatistics` | 89 | Exported Function
`WerpValidateReportKey` | 92 | Exported Function
`WerpUnmapProcessViews` | 91 | Exported Function
`WerpIsDisabled` | 136 | Exported Function
`WerpCancelUpload` | 11 | Exported Function
`WerpAuxmdMapFile` | 129 | Exported Function
`WerpCloseStore` | 13 | Exported Function
`WerpCleanWer` | 12 | Exported Function
`WerpAuxmdInitialize` | 128 | Exported Function
`WerpAuxmdFree` | 125 | Exported Function
`WerpAuxmdDumpRegisteredBlocks` | 124 | Exported Function
`WerpAuxmdHashVaRanges` | 127 | Exported Function
`WerpAuxmdFreeCopyBuffer` | 126 | Exported Function
`WerpExtractReportFiles` | 131 | Exported Function
`WerpEnumerateStoreStart` | 18 | Exported Function
`WerpForceDeferredCollection` | 20 | Exported Function
`WerpFlushImageCache` | 19 | Exported Function
`WerpEnumerateStoreNext` | 17 | Exported Function
`WerpCreateMachineStore` | 14 | Exported Function
`WerpCreateIntegratorReportId` | 130 | Exported Function
`WerpDestroyWerString` | 16 | Exported Function
`WerpDeleteReport` | 15 | Exported Function
`WerpAddAppCompatData` | 4 | Exported Function
`WerFreeString` | 99 | Exported Function
`WerpAddFileBuffer` | 120 | Exported Function
`WerpAddFile` | 119 | Exported Function
`WerAddExcludedApplication` | 98 | Exported Function
`GetThreadWaitChain` | 95 | Exported Function
`CloseThreadWaitChainSession` | 94 | Exported Function
`RegisterWaitChainCOMCallback` | 97 | Exported Function
`OpenThreadWaitChainSession` | 96 | Exported Function
`WerpAddTerminationReason` | 122 | Exported Function
`WerpAddRegisteredMetadataToReport` | 9 | Exported Function
`WerpAuxmdDumpProcessImages` | 123 | Exported Function
`WerpArchiveReport` | 10 | Exported Function
`WerpAddRegisteredDumpsToReport` | 8 | Exported Function
`WerpAddIfRegisteredForAppLocalDump` | 5 | Exported Function
`WerpAddFileCallback` | 121 | Exported Function
`WerpAddRegisteredDataToReport` | 7 | Exported Function
`WerpAddMemoryBlock` | 6 | Exported Function
`WerpGetResponseId` | 42 | Exported Function
`WerpGetReportType` | 41 | Exported Function
`WerpGetStoreLocation` | 135 | Exported Function
`WerpGetSigParamByIndex` | 43 | Exported Function
`WerpGetReportTime` | 40 | Exported Function
`WerpGetReportId` | 37 | Exported Function
`WerpGetReportFlags` | 36 | Exported Function
`WerpGetReportSettings` | 39 | Exported Function
`WerpGetReportInformation` | 38 | Exported Function
`WerpGetWow64Process` | 50 | Exported Function
`WerpGetWerStringData` | 49 | Exported Function
`WerpInitializeImageCache` | 52 | Exported Function
`WerpHashApplicationParameters` | 51 | Exported Function
`WerpGetUploadTime` | 48 | Exported Function
`WerpGetStoreType` | 45 | Exported Function
`WerpGetStorePath` | 44 | Exported Function
`WerpGetUIParamByIndex` | 47 | Exported Function
`WerpGetTextFromReport` | 46 | Exported Function
`WerpGetFileByIndex` | 26 | Exported Function
`WerpGetExtendedDiagData` | 25 | Exported Function
`WerpGetIntegratorReportId` | 133 | Exported Function
`WerpGetFilePathByIndex` | 27 | Exported Function
`WerpGetEventType` | 24 | Exported Function
`WerpFreeUnmappedVaRanges` | 21 | Exported Function
`WerpFreeString` | 132 | Exported Function
`WerpGetDynamicParameter` | 23 | Exported Function
`WerpGetBucketId` | 22 | Exported Function
`WerpGetReportConsent` | 134 | Exported Function
`WerpGetPathOfWERTempDirectory` | 33 | Exported Function
`WerpGetReportFinalConsent` | 35 | Exported Function
`WerpGetReportCount` | 34 | Exported Function
`WerpGetNumSigParams` | 32 | Exported Function
`WerpGetLoadedModuleByIndex` | 29 | Exported Function
`WerpGetLegacyBucketId` | 28 | Exported Function
`WerpGetNumLoadedModules` | 31 | Exported Function
`WerpGetNumFiles` | 30 | Exported Function


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


