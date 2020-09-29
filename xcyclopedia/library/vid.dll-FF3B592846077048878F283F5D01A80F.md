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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`VidAdjustNestedTlbSize` | 1 (0x1) | Exported Function | 0x00000001800068c0 | 0x000068c0
`VidPrefetchDirectMapRanges` | 113 (0x71) | Exported Function | 0x000000018000a6a0 | 0x0000a6a0
`VidProtectMemoryBlockPages` | 114 (0x72) | Exported Function | 0x000000018000a740 | 0x0000a740
`VidQueryVaGpaRangeWorkingSetInfo` | 115 (0x73) | Exported Function | 0x000000018000a7d0 | 0x0000a7d0
`VidReadMemoryBlockPageRange` | 116 (0x74) | Exported Function | 0x000000018000a870 | 0x0000a870
`VidReadWriteMappedMemoryBlockPageRange` | 117 (0x75) | Exported Function | 0x000000018000a8c0 | 0x0000a8c0
`VidReadWriteMemoryBlockPageRange` | 118 (0x76) | Exported Function | 0x000000018000a9a0 | 0x0000a9a0
`VidRegisterApicEoiHandler` | 119 (0x77) | Exported Function | 0x0000000180003ee0 | 0x00003ee0
`VidRegisterCpuidHandler` | 120 (0x78) | Exported Function | 0x00000001800040d0 | 0x000040d0
`VidPhuPersistMemoryBlock` | 112 (0x70) | Exported Function | 0x000000018000a5c0 | 0x0000a5c0
`VidRegisterCpuidResult` | 121 (0x79) | Exported Function | 0x0000000180003c90 | 0x00003c90
`VidRegisterIoPortHandler` | 123 (0x7b) | Exported Function | 0x0000000180003250 | 0x00003250
`VidRegisterMsrHandler` | 124 (0x7c) | Exported Function | 0x0000000180004580 | 0x00004580
`VidRegisterTripleFaultHandler` | 125 (0x7d) | Exported Function | 0x0000000180004490 | 0x00004490
`VidReleaseEncryptionKeys` | 126 (0x7e) | Exported Function | 0x000000018000abc0 | 0x0000abc0
`VidReleasePages` | 127 (0x7f) | Exported Function | 0x000000018000ac40 | 0x0000ac40
`VidReservePages` | 128 (0x80) | Exported Function | 0x0000000180003760 | 0x00003760
`VidResetPartition` | 129 (0x81) | Exported Function | 0x0000000180004840 | 0x00004840
`VidResetPoisonedPage` | 130 (0x82) | Exported Function | 0x000000018000ad00 | 0x0000ad00
`VidRegisterExceptionHandler` | 122 (0x7a) | Exported Function | 0x000000018000ab20 | 0x0000ab20
`VidRestorePartitionState` | 131 (0x83) | Exported Function | 0x000000018000ad90 | 0x0000ad90
`VidPhuPersistGpaRange` | 111 (0x6f) | Exported Function | 0x000000018000a4e0 | 0x0000a4e0
`VidPhuFreePersistedData` | 109 (0x6d) | Exported Function | 0x000000018000a350 | 0x0000a350
`VidMapMemoryBlockPageRangeEx` | 91 (0x5b) | Exported Function | 0x0000000180001140 | 0x00001140
`VidMapVpStatePage` | 92 (0x5c) | Exported Function | 0x00000001800051d0 | 0x000051d0
`VidMarkPagePoisoned` | 93 (0x5d) | Exported Function | 0x0000000180009c10 | 0x00009c10
`VidMemReserveGetTarget` | 94 (0x5e) | Exported Function | 0x0000000180005280 | 0x00005280
`VidMemReservePagesAdd` | 95 (0x5f) | Exported Function | 0x0000000180009ca0 | 0x00009ca0
`VidMemReservePagesRelease` | 96 (0x60) | Exported Function | 0x0000000180009db0 | 0x00009db0
`VidMemReserveSetTarget` | 97 (0x61) | Exported Function | 0x00000001800053a0 | 0x000053a0
`VidMemXferConnectClose` | 98 (0x62) | Exported Function | 0x0000000180009e70 | 0x00009e70
`VidPhuOpenMemoryBlockFile` | 110 (0x6e) | Exported Function | 0x000000018000a3e0 | 0x0000a3e0
`VidMemXferConnectDisable` | 99 (0x63) | Exported Function | 0x0000000180009ef0 | 0x00009ef0
`VidMemXferConnectOpen` | 101 (0x65) | Exported Function | 0x000000018000a080 | 0x0000a080
`VidMemXferSendAsync` | 102 (0x66) | Exported Function | 0x000000018000a110 | 0x0000a110
`VidMessageSlotHandleAndGetNext` | 103 (0x67) | Exported Function | 0x00000001800010b0 | 0x000010b0
`VidMessageSlotMap` | 104 (0x68) | Exported Function | 0x0000000180004030 | 0x00004030
`VidOpenStatisticsHandle` | 105 (0x69) | Exported Function | 0x0000000180002360 | 0x00002360
`VidPhuBegin` | 106 (0x6a) | Exported Function | 0x000000018000a1b0 | 0x0000a1b0
`VidPhuCommit` | 107 (0x6b) | Exported Function | 0x000000018000a250 | 0x0000a250
`VidPhuEnd` | 108 (0x6c) | Exported Function | 0x000000018000a2d0 | 0x0000a2d0
`VidMemXferConnectEnable` | 100 (0x64) | Exported Function | 0x0000000180009f70 | 0x00009f70
`VidSavePartitionState` | 132 (0x84) | Exported Function | 0x000000018000ae60 | 0x0000ae60
`VidSchedulerAssistRestore` | 133 (0x85) | Exported Function | 0x000000018000af50 | 0x0000af50
`VidSchedulerAssistSave` | 134 (0x86) | Exported Function | 0x000000018000aff0 | 0x0000aff0
`VidTranslateGpa` | 158 (0x9e) | Exported Function | 0x00000001800054b0 | 0x000054b0
`VidTranslateGvaToGpa` | 159 (0x9f) | Exported Function | 0x00000001800012b0 | 0x000012b0
`VidTrimPartitionMemory` | 160 (0xa0) | Exported Function | 0x0000000180003fd0 | 0x00003fd0
`VidUnmapHvGlobalStatsPage` | 161 (0xa1) | Exported Function | 0x00000001800047a0 | 0x000047a0
`VidUnmapHvLocalStatsPage` | 162 (0xa2) | Exported Function | 0x0000000180004180 | 0x00004180
`VidUnmapHvRootStatsPage` | 163 (0xa3) | Exported Function | 0x000000018000ba00 | 0x0000ba00
`VidUnmapMemoryBlockPageRange` | 164 (0xa4) | Exported Function | 0x0000000180001230 | 0x00001230
`VidUnprotectMemoryBlockPages` | 165 (0xa5) | Exported Function | 0x000000018000bac0 | 0x0000bac0
`VidSuspendClear` | 157 (0x9d) | Exported Function | 0x000000018000b980 | 0x0000b980
`VidUnregisterCpuidResult` | 166 (0xa6) | Exported Function | 0x0000000180003e70 | 0x00003e70
`VidVsmCheckGpaPageVtlAccess` | 168 (0xa8) | Exported Function | 0x0000000180001520 | 0x00001520
`VidVsmEnableVpVtl` | 169 (0xa9) | Exported Function | 0x000000018000bb50 | 0x0000bb50
`VidVsmGetMemoryBlockProtections` | 170 (0xaa) | Exported Function | 0x000000018000bca0 | 0x0000bca0
`VidVsmGetPartitionConfig` | 171 (0xab) | Exported Function | 0x000000018000bde0 | 0x0000bde0
`VidVsmPrecommitMgmtVtlPageRange` | 172 (0xac) | Exported Function | 0x00000001800055e0 | 0x000055e0
`VidVsmQueryMemoryBlockProtections` | 173 (0xad) | Exported Function | 0x000000018000bef0 | 0x0000bef0
`VidVsmQueryProtectionsDirty` | 174 (0xae) | Exported Function | 0x000000018000bfd0 | 0x0000bfd0
`VidVsmSetMemoryBlockProtections` | 175 (0xaf) | Exported Function | 0x000000018000c060 | 0x0000c060
`VidUnregisterHandler` | 167 (0xa7) | Exported Function | 0x00000001800034e0 | 0x000034e0
`VidSuspendApply` | 156 (0x9c) | Exported Function | 0x000000018000b8f0 | 0x0000b8f0
`VidStopVirtualProcessor` | 155 (0x9b) | Exported Function | 0x0000000180004400 | 0x00004400
`VidStatsUnMapNuma` | 154 (0x9a) | Exported Function | 0x000000018000b860 | 0x0000b860
`VidSchedulerAssistSuspend` | 135 (0x87) | Exported Function | 0x000000018000b0b0 | 0x0000b0b0
`VidSetCpuGroupProperty` | 136 (0x88) | Exported Function | 0x000000018000b140 | 0x0000b140
`VidSetMailboxKey` | 137 (0x89) | Exported Function | 0x000000018000b200 | 0x0000b200
`VidSetMemoryBlockClientNotifications` | 138 (0x8a) | Exported Function | 0x0000000180002a90 | 0x00002a90
`VidSetMemoryBlockFlushAfterWrite` | 139 (0x8b) | Exported Function | 0x000000018000b2d0 | 0x0000b2d0
`VidSetMemoryBlockNotificationQueue` | 140 (0x8c) | Exported Function | 0x0000000180003a80 | 0x00003a80
`VidSetPartitionFriendlyName` | 141 (0x8d) | Exported Function | 0x0000000180003af0 | 0x00003af0
`VidSetPartitionProperty` | 142 (0x8e) | Exported Function | 0x00000001800036a0 | 0x000036a0
`VidSetPeerProcess` | 143 (0x8f) | Exported Function | 0x000000018000b370 | 0x0000b370
`VidSetSystemInformation` | 144 (0x90) | Exported Function | 0x000000018000b400 | 0x0000b400
`VidSetupMessageQueue` | 148 (0x94) | Exported Function | 0x0000000180004510 | 0x00004510
`VidSetVirtualProcessorState` | 145 (0x91) | Exported Function | 0x0000000180001010 | 0x00001010
`VidSetVirtualProcessorStateEx` | 146 (0x92) | Exported Function | 0x000000018000b530 | 0x0000b530
`VidSetVirtualProcessorXsaveState` | 147 (0x93) | Exported Function | 0x000000018000b5f0 | 0x0000b5f0
`VidSgxResetMemoryBlocks` | 149 (0x95) | Exported Function | 0x000000018000b760 | 0x0000b760
`VidStartVirtualProcessor` | 150 (0x96) | Exported Function | 0x0000000180003f60 | 0x00003f60
`VidStatsMap` | 151 (0x97) | Exported Function | 0x00000001800046f0 | 0x000046f0
`VidStatsMapNuma` | 152 (0x98) | Exported Function | 0x0000000180004630 | 0x00004630
`VidStatsUnMap` | 153 (0x99) | Exported Function | 0x000000018000b7e0 | 0x0000b7e0
`VidMapMemoryBlockPageRange` | 90 (0x5a) | Exported Function | 0x0000000180009b90 | 0x00009b90
`VidVsmSetPartitionConfig` | 176 (0xb0) | Exported Function | 0x000000018000c130 | 0x0000c130
`VidMapHypercallDoorbellPage` | 89 (0x59) | Exported Function | 0x0000000180009af0 | 0x00009af0
`VidMapHvLocalStatsPage` | 87 (0x57) | Exported Function | 0x0000000180003dc0 | 0x00003dc0
`VidDestroyGpaRange` | 24 (0x18) | Exported Function | 0x0000000180003450 | 0x00003450
`VidDestroyGpaRangeCheckSecure` | 25 (0x19) | Exported Function | 0x0000000180007440 | 0x00007440
`VidDestroyMemoryBlock` | 26 (0x1a) | Exported Function | 0x0000000180003d50 | 0x00003d50
`VidDestroyMemoryBlockReadWriteBuffers` | 27 (0x1b) | Exported Function | 0x0000000180007460 | 0x00007460
`VidDestroyMmioGpaDoorbell` | 28 (0x1c) | Exported Function | 0x0000000180004fd0 | 0x00004fd0
`VidDispatchVirtualProcessor` | 29 (0x1d) | Exported Function | 0x00000001800074e0 | 0x000074e0
`VidDllStatsGetPartitionCounters` | 30 (0x1e) | Exported Function | 0x0000000180002010 | 0x00002010
`VidDllStatsGetSharedBuffer` | 31 (0x1f) | Exported Function | 0x000000018000c200 | 0x0000c200
`VidDeletePartition` | 23 (0x17) | Exported Function | 0x0000000180001690 | 0x00001690
`VidDllStatsGetVmPerfRootInstance` | 32 (0x20) | Exported Function | 0x0000000180001fa0 | 0x00001fa0
`VidDmConsolidationDisable` | 34 (0x22) | Exported Function | 0x0000000180007780 | 0x00007780
`VidDmConsolidationEnable` | 35 (0x23) | Exported Function | 0x0000000180007800 | 0x00007800
`VidDmHotAdd` | 36 (0x24) | Exported Function | 0x00000001800078a0 | 0x000078a0
`VidDmHotAddUndo` | 37 (0x25) | Exported Function | 0x0000000180007980 | 0x00007980
`VidDmMemoryBlockQueryTopology` | 38 (0x26) | Exported Function | 0x0000000180007a30 | 0x00007a30
`VidDmSlpDisable` | 39 (0x27) | Exported Function | 0x0000000180007b80 | 0x00007b80
`VidDmSlpQuery` | 40 (0x28) | Exported Function | 0x0000000180007c00 | 0x00007c00
`VidDmSlpSetup` | 41 (0x29) | Exported Function | 0x0000000180007cf0 | 0x00007cf0
`VidDmBalloon` | 33 (0x21) | Exported Function | 0x00000001800075e0 | 0x000075e0
`VidDmSlpWaitForDisable` | 42 (0x2a) | Exported Function | 0x0000000180007e70 | 0x00007e70
`VidDeleteCpuGroup` | 22 (0x16) | Exported Function | 0x00000001800073b0 | 0x000073b0
`VidCreatePartition` | 20 (0x14) | Exported Function | 0x0000000180001980 | 0x00001980
`VidAllocateMemoryBlockReadWriteBuffers` | 2 (0x2) | Exported Function | 0x0000000180006980 | 0x00006980
`VidAssertVirtualProcessorInterrupt` | 3 (0x3) | Exported Function | 0x00000001800015e0 | 0x000015e0
`VidChangePartitionLifeState` | 4 (0x4) | Exported Function | 0x0000000180006a40 | 0x00006a40
`VidCheckForIoIntercept` | 5 (0x5) | Exported Function | 0x0000000180003550 | 0x00003550
`VidClearVirtualProcessorInterrupt` | 6 (0x6) | Exported Function | 0x0000000180002ba0 | 0x00002ba0
`VidCloneTemplateCreate` | 7 (0x7) | Exported Function | 0x0000000180006b00 | 0x00006b00
`VidCloneTemplateDestroy` | 8 (0x8) | Exported Function | 0x0000000180006bd0 | 0x00006bd0
`VidCloneTemplateDestroyDetached` | 9 (0x9) | Exported Function | 0x0000000180006c50 | 0x00006c50
`VidCreateVaGpaRange` | 21 (0x15) | Exported Function | 0x0000000180007240 | 0x00007240
`VidCloneTemplateDetach` | 10 (0xa) | Exported Function | 0x0000000180006d10 | 0x00006d10
`VidControlGpaAccessTracking` | 12 (0xc) | Exported Function | 0x0000000180004df0 | 0x00004df0
`VidCreateCpuGroup` | 13 (0xd) | Exported Function | 0x0000000180006df0 | 0x00006df0
`VidCreateDaxFileMemoryBlock` | 14 (0xe) | Exported Function | 0x0000000180006ea0 | 0x00006ea0
`VidCreateExoPartition` | 15 (0xf) | Exported Function | 0x00000001800070a0 | 0x000070a0
`VidCreateMemoryBlock` | 16 (0x10) | Exported Function | 0x0000000180003990 | 0x00003990
`VidCreateMemoryBlockGpaRange` | 17 (0x11) | Exported Function | 0x00000001800032e0 | 0x000032e0
`VidCreateMmioGpaDoorbell` | 18 (0x12) | Exported Function | 0x0000000180004ee0 | 0x00004ee0
`VidCreateMmioGpaRange` | 19 (0x13) | Exported Function | 0x00000001800035f0 | 0x000035f0
`VidCloseStatisticsHandle` | 11 (0xb) | Exported Function | 0x00000001800068a0 | 0x000068a0
`VidDmUnBalloon` | 43 (0x2b) | Exported Function | 0x0000000180007ef0 | 0x00007ef0
`VidDmWorkingSetModify` | 44 (0x2c) | Exported Function | 0x0000000180008090 | 0x00008090
`VidEncryptDecryptData` | 45 (0x2d) | Exported Function | 0x0000000180008170 | 0x00008170
`VidGetPartitionProperty` | 69 (0x45) | Exported Function | 0x00000001800023f0 | 0x000023f0
`VidGetProcessorTopology` | 70 (0x46) | Exported Function | 0x00000001800093a0 | 0x000093a0
`VidGetRootReferenceTime` | 71 (0x47) | Exported Function | 0x00000001800033e0 | 0x000033e0
`VidGetRpcSession` | 72 (0x48) | Exported Function | 0x00000001800094b0 | 0x000094b0
`VidGetSecurityCookie` | 73 (0x49) | Exported Function | 0x00000001800095b0 | 0x000095b0
`VidGetSystemInformation` | 74 (0x4a) | Exported Function | 0x00000001800042d0 | 0x000042d0
`VidGetSystemTopology` | 75 (0x4b) | Exported Function | 0x0000000180003840 | 0x00003840
`VidGetVirtualProcessorRunningStatus` | 76 (0x4c) | Exported Function | 0x0000000180002d80 | 0x00002d80
`VidGetPartitionIds` | 68 (0x44) | Exported Function | 0x0000000180009370 | 0x00009370
`VidGetVirtualProcessorState` | 77 (0x4d) | Exported Function | 0x0000000180001480 | 0x00001480
`VidGetVirtualProcessorXsaveState` | 79 (0x4f) | Exported Function | 0x0000000180009720 | 0x00009720
`VidGpaAccessTrackingDisable` | 80 (0x50) | Exported Function | 0x00000001800050d0 | 0x000050d0
`VidGpaAccessTrackingEnable` | 81 (0x51) | Exported Function | 0x0000000180005150 | 0x00005150
`VidHandleMessageAndGetNextMessage` | 82 (0x52) | Exported Function | 0x0000000180002c90 | 0x00002c90
`VidInitEncryptionKeys` | 83 (0x53) | Exported Function | 0x00000001800097e0 | 0x000097e0
`VidInjectSyntheticMachineCheckEvent` | 84 (0x54) | Exported Function | 0x0000000180009860 | 0x00009860
`VidInstallExoIntercept` | 85 (0x55) | Exported Function | 0x0000000180009960 | 0x00009960
`VidMapHvGlobalStatsPage` | 86 (0x56) | Exported Function | 0x0000000180004220 | 0x00004220
`VidGetVirtualProcessorStateEx` | 78 (0x4e) | Exported Function | 0x0000000180009660 | 0x00009660
`VidGetMemoryBlockProtectionBitmap` | 67 (0x43) | Exported Function | 0x00000001800092d0 | 0x000092d0
`VidGetIsolationLuid` | 66 (0x42) | Exported Function | 0x0000000180009250 | 0x00009250
`VidGetHvVpRuntime` | 65 (0x41) | Exported Function | 0x0000000180009140 | 0x00009140
`VidEpfRestore` | 46 (0x2e) | Exported Function | 0x00000001800082a0 | 0x000082a0
`VidEpfSave` | 47 (0x2f) | Exported Function | 0x00000001800083b0 | 0x000083b0
`VidEpfSuspendBegin` | 48 (0x30) | Exported Function | 0x0000000180008510 | 0x00008510
`VidEpfSuspendEnd` | 49 (0x31) | Exported Function | 0x0000000180008590 | 0x00008590
`VidExoAccessVaFault` | 50 (0x32) | Exported Function | 0x0000000180008610 | 0x00008610
`VidExoControlGpaAccessTracking` | 51 (0x33) | Exported Function | 0x00000001800086d0 | 0x000086d0
`VidExoGetLocalInterruptControllerState` | 52 (0x34) | Exported Function | 0x0000000180008780 | 0x00008780
`VidExoMapGpaRange` | 53 (0x35) | Exported Function | 0x00000001800088d0 | 0x000088d0
`VidExoSetLocalInterruptControllerState` | 54 (0x36) | Exported Function | 0x00000001800089a0 | 0x000089a0
`VidExoUnmapGpaRange` | 55 (0x37) | Exported Function | 0x0000000180008ad0 | 0x00008ad0
`VidFlushMemoryBlockMapping` | 56 (0x38) | Exported Function | 0x0000000180008b90 | 0x00008b90
`VidFlushMemoryBlockPageRange` | 57 (0x39) | Exported Function | 0x0000000180008c30 | 0x00008c30
`VidGetCpuGroupProperty` | 58 (0x3a) | Exported Function | 0x0000000180008ce0 | 0x00008ce0
`VidGetExoPartitionProperty` | 59 (0x3b) | Exported Function | 0x0000000180008db0 | 0x00008db0
`VidGetExoSystemInformation` | 60 (0x3c) | Exported Function | 0x0000000180005060 | 0x00005060
`VidGetHvLogicalProcessorCount` | 61 (0x3d) | Exported Function | 0x0000000180008e60 | 0x00008e60
`VidGetHvLogicalProcessorRuntime` | 62 (0x3e) | Exported Function | 0x0000000180008f20 | 0x00008f20
`VidGetHvMemoryBalance` | 63 (0x3f) | Exported Function | 0x0000000180009040 | 0x00009040
`VidGetHvPartitionId` | 64 (0x40) | Exported Function | 0x0000000180002c20 | 0x00002c20
`VidMapHvRootStatsPage` | 88 (0x58) | Exported Function | 0x0000000180009a20 | 0x00009a20
`VidWriteMemoryBlockPageRange` | 177 (0xb1) | Exported Function | 0x000000018000c1b0 | 0x0000c1b0


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


