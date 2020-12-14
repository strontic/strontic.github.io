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


