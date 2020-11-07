---
title: vid.dll | Microsoft Hyper-V Virtualization Infrastructure Driver Library
excerpt: What is vid.dll?
---

# vid.dll 

* File Path: `C:\Windows\system32\vid.dll`
* Description: Microsoft Hyper-V Virtualization Infrastructure Driver Library

## Hashes

Type | Hash
-- | --
MD5 | `FF3B592846077048878F283F5D01A80F`
SHA1 | `14DFCB25A25ED46830C4F8F1A1D769F3164237BE`
SHA256 | `9EA2BF69C839E37B630B6DEC091A4510B3ACA5BF88BF36AB4D3BFF9EDAA6C796`
SHA384 | `D0246E417FFBDF4BE604353A26F2ECF0864DA745392C9BBA2F059DB06A8FE6BA68A981E079A6807471162E3942E2A4CD`
SHA512 | `E102D738F768971EF6CBEC7082871A0F82563A00BB2A9CF23C96A97B24ED362535A8D6A2CC73043310B5115514F6C0CDB23B80F1C41CC94F917D591A9F9413D6`
SSDEEP | `1536:yEzCZJ0u1Ul18sEzRfcvkQXuqyfHdS+RH2AkGh+1b6PY:yEzCL0fl18sWfcvkQg9S+0ANhmb6w`
IMP | `CBEAD74D3D3462A6DD0EF928DA2CD5A1`
PESHA1 | `9326D56F66C3F9E2FB5D448090A282F9D1C7191A`
PE256 | `6E1303D5CF6413D546C4C326E06E9080983DE217824C5E32D722E8818BDE8D62`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`VidAdjustNestedTlbSize` | 1 | Exported Function
`VidPrefetchDirectMapRanges` | 113 | Exported Function
`VidProtectMemoryBlockPages` | 114 | Exported Function
`VidQueryVaGpaRangeWorkingSetInfo` | 115 | Exported Function
`VidReadMemoryBlockPageRange` | 116 | Exported Function
`VidReadWriteMappedMemoryBlockPageRange` | 117 | Exported Function
`VidReadWriteMemoryBlockPageRange` | 118 | Exported Function
`VidRegisterApicEoiHandler` | 119 | Exported Function
`VidRegisterCpuidHandler` | 120 | Exported Function
`VidPhuPersistMemoryBlock` | 112 | Exported Function
`VidRegisterCpuidResult` | 121 | Exported Function
`VidRegisterIoPortHandler` | 123 | Exported Function
`VidRegisterMsrHandler` | 124 | Exported Function
`VidRegisterTripleFaultHandler` | 125 | Exported Function
`VidReleaseEncryptionKeys` | 126 | Exported Function
`VidReleasePages` | 127 | Exported Function
`VidReservePages` | 128 | Exported Function
`VidResetPartition` | 129 | Exported Function
`VidResetPoisonedPage` | 130 | Exported Function
`VidRegisterExceptionHandler` | 122 | Exported Function
`VidRestorePartitionState` | 131 | Exported Function
`VidPhuPersistGpaRange` | 111 | Exported Function
`VidPhuFreePersistedData` | 109 | Exported Function
`VidMapMemoryBlockPageRangeEx` | 91 | Exported Function
`VidMapVpStatePage` | 92 | Exported Function
`VidMarkPagePoisoned` | 93 | Exported Function
`VidMemReserveGetTarget` | 94 | Exported Function
`VidMemReservePagesAdd` | 95 | Exported Function
`VidMemReservePagesRelease` | 96 | Exported Function
`VidMemReserveSetTarget` | 97 | Exported Function
`VidMemXferConnectClose` | 98 | Exported Function
`VidPhuOpenMemoryBlockFile` | 110 | Exported Function
`VidMemXferConnectDisable` | 99 | Exported Function
`VidMemXferConnectOpen` | 101 | Exported Function
`VidMemXferSendAsync` | 102 | Exported Function
`VidMessageSlotHandleAndGetNext` | 103 | Exported Function
`VidMessageSlotMap` | 104 | Exported Function
`VidOpenStatisticsHandle` | 105 | Exported Function
`VidPhuBegin` | 106 | Exported Function
`VidPhuCommit` | 107 | Exported Function
`VidPhuEnd` | 108 | Exported Function
`VidMemXferConnectEnable` | 100 | Exported Function
`VidSavePartitionState` | 132 | Exported Function
`VidSchedulerAssistRestore` | 133 | Exported Function
`VidSchedulerAssistSave` | 134 | Exported Function
`VidTranslateGpa` | 158 | Exported Function
`VidTranslateGvaToGpa` | 159 | Exported Function
`VidTrimPartitionMemory` | 160 | Exported Function
`VidUnmapHvGlobalStatsPage` | 161 | Exported Function
`VidUnmapHvLocalStatsPage` | 162 | Exported Function
`VidUnmapHvRootStatsPage` | 163 | Exported Function
`VidUnmapMemoryBlockPageRange` | 164 | Exported Function
`VidUnprotectMemoryBlockPages` | 165 | Exported Function
`VidSuspendClear` | 157 | Exported Function
`VidUnregisterCpuidResult` | 166 | Exported Function
`VidVsmCheckGpaPageVtlAccess` | 168 | Exported Function
`VidVsmEnableVpVtl` | 169 | Exported Function
`VidVsmGetMemoryBlockProtections` | 170 | Exported Function
`VidVsmGetPartitionConfig` | 171 | Exported Function
`VidVsmPrecommitMgmtVtlPageRange` | 172 | Exported Function
`VidVsmQueryMemoryBlockProtections` | 173 | Exported Function
`VidVsmQueryProtectionsDirty` | 174 | Exported Function
`VidVsmSetMemoryBlockProtections` | 175 | Exported Function
`VidUnregisterHandler` | 167 | Exported Function
`VidSuspendApply` | 156 | Exported Function
`VidStopVirtualProcessor` | 155 | Exported Function
`VidStatsUnMapNuma` | 154 | Exported Function
`VidSchedulerAssistSuspend` | 135 | Exported Function
`VidSetCpuGroupProperty` | 136 | Exported Function
`VidSetMailboxKey` | 137 | Exported Function
`VidSetMemoryBlockClientNotifications` | 138 | Exported Function
`VidSetMemoryBlockFlushAfterWrite` | 139 | Exported Function
`VidSetMemoryBlockNotificationQueue` | 140 | Exported Function
`VidSetPartitionFriendlyName` | 141 | Exported Function
`VidSetPartitionProperty` | 142 | Exported Function
`VidSetPeerProcess` | 143 | Exported Function
`VidSetSystemInformation` | 144 | Exported Function
`VidSetupMessageQueue` | 148 | Exported Function
`VidSetVirtualProcessorState` | 145 | Exported Function
`VidSetVirtualProcessorStateEx` | 146 | Exported Function
`VidSetVirtualProcessorXsaveState` | 147 | Exported Function
`VidSgxResetMemoryBlocks` | 149 | Exported Function
`VidStartVirtualProcessor` | 150 | Exported Function
`VidStatsMap` | 151 | Exported Function
`VidStatsMapNuma` | 152 | Exported Function
`VidStatsUnMap` | 153 | Exported Function
`VidMapMemoryBlockPageRange` | 90 | Exported Function
`VidVsmSetPartitionConfig` | 176 | Exported Function
`VidMapHypercallDoorbellPage` | 89 | Exported Function
`VidMapHvLocalStatsPage` | 87 | Exported Function
`VidDestroyGpaRange` | 24 | Exported Function
`VidDestroyGpaRangeCheckSecure` | 25 | Exported Function
`VidDestroyMemoryBlock` | 26 | Exported Function
`VidDestroyMemoryBlockReadWriteBuffers` | 27 | Exported Function
`VidDestroyMmioGpaDoorbell` | 28 | Exported Function
`VidDispatchVirtualProcessor` | 29 | Exported Function
`VidDllStatsGetPartitionCounters` | 30 | Exported Function
`VidDllStatsGetSharedBuffer` | 31 | Exported Function
`VidDeletePartition` | 23 | Exported Function
`VidDllStatsGetVmPerfRootInstance` | 32 | Exported Function
`VidDmConsolidationDisable` | 34 | Exported Function
`VidDmConsolidationEnable` | 35 | Exported Function
`VidDmHotAdd` | 36 | Exported Function
`VidDmHotAddUndo` | 37 | Exported Function
`VidDmMemoryBlockQueryTopology` | 38 | Exported Function
`VidDmSlpDisable` | 39 | Exported Function
`VidDmSlpQuery` | 40 | Exported Function
`VidDmSlpSetup` | 41 | Exported Function
`VidDmBalloon` | 33 | Exported Function
`VidDmSlpWaitForDisable` | 42 | Exported Function
`VidDeleteCpuGroup` | 22 | Exported Function
`VidCreatePartition` | 20 | Exported Function
`VidAllocateMemoryBlockReadWriteBuffers` | 2 | Exported Function
`VidAssertVirtualProcessorInterrupt` | 3 | Exported Function
`VidChangePartitionLifeState` | 4 | Exported Function
`VidCheckForIoIntercept` | 5 | Exported Function
`VidClearVirtualProcessorInterrupt` | 6 | Exported Function
`VidCloneTemplateCreate` | 7 | Exported Function
`VidCloneTemplateDestroy` | 8 | Exported Function
`VidCloneTemplateDestroyDetached` | 9 | Exported Function
`VidCreateVaGpaRange` | 21 | Exported Function
`VidCloneTemplateDetach` | 10 | Exported Function
`VidControlGpaAccessTracking` | 12 | Exported Function
`VidCreateCpuGroup` | 13 | Exported Function
`VidCreateDaxFileMemoryBlock` | 14 | Exported Function
`VidCreateExoPartition` | 15 | Exported Function
`VidCreateMemoryBlock` | 16 | Exported Function
`VidCreateMemoryBlockGpaRange` | 17 | Exported Function
`VidCreateMmioGpaDoorbell` | 18 | Exported Function
`VidCreateMmioGpaRange` | 19 | Exported Function
`VidCloseStatisticsHandle` | 11 | Exported Function
`VidDmUnBalloon` | 43 | Exported Function
`VidDmWorkingSetModify` | 44 | Exported Function
`VidEncryptDecryptData` | 45 | Exported Function
`VidGetPartitionProperty` | 69 | Exported Function
`VidGetProcessorTopology` | 70 | Exported Function
`VidGetRootReferenceTime` | 71 | Exported Function
`VidGetRpcSession` | 72 | Exported Function
`VidGetSecurityCookie` | 73 | Exported Function
`VidGetSystemInformation` | 74 | Exported Function
`VidGetSystemTopology` | 75 | Exported Function
`VidGetVirtualProcessorRunningStatus` | 76 | Exported Function
`VidGetPartitionIds` | 68 | Exported Function
`VidGetVirtualProcessorState` | 77 | Exported Function
`VidGetVirtualProcessorXsaveState` | 79 | Exported Function
`VidGpaAccessTrackingDisable` | 80 | Exported Function
`VidGpaAccessTrackingEnable` | 81 | Exported Function
`VidHandleMessageAndGetNextMessage` | 82 | Exported Function
`VidInitEncryptionKeys` | 83 | Exported Function
`VidInjectSyntheticMachineCheckEvent` | 84 | Exported Function
`VidInstallExoIntercept` | 85 | Exported Function
`VidMapHvGlobalStatsPage` | 86 | Exported Function
`VidGetVirtualProcessorStateEx` | 78 | Exported Function
`VidGetMemoryBlockProtectionBitmap` | 67 | Exported Function
`VidGetIsolationLuid` | 66 | Exported Function
`VidGetHvVpRuntime` | 65 | Exported Function
`VidEpfRestore` | 46 | Exported Function
`VidEpfSave` | 47 | Exported Function
`VidEpfSuspendBegin` | 48 | Exported Function
`VidEpfSuspendEnd` | 49 | Exported Function
`VidExoAccessVaFault` | 50 | Exported Function
`VidExoControlGpaAccessTracking` | 51 | Exported Function
`VidExoGetLocalInterruptControllerState` | 52 | Exported Function
`VidExoMapGpaRange` | 53 | Exported Function
`VidExoSetLocalInterruptControllerState` | 54 | Exported Function
`VidExoUnmapGpaRange` | 55 | Exported Function
`VidFlushMemoryBlockMapping` | 56 | Exported Function
`VidFlushMemoryBlockPageRange` | 57 | Exported Function
`VidGetCpuGroupProperty` | 58 | Exported Function
`VidGetExoPartitionProperty` | 59 | Exported Function
`VidGetExoSystemInformation` | 60 | Exported Function
`VidGetHvLogicalProcessorCount` | 61 | Exported Function
`VidGetHvLogicalProcessorRuntime` | 62 | Exported Function
`VidGetHvMemoryBalance` | 63 | Exported Function
`VidGetHvPartitionId` | 64 | Exported Function
`VidMapHvRootStatsPage` | 88 | Exported Function
`VidWriteMemoryBlockPageRange` | 177 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vid.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/9ea2bf69c839e37b630b6dec091a4510b3aca5bf88bf36ab4d3bff9edaa6c796/detection/





MIT License. Copyright (c) 2020 Strontic.


