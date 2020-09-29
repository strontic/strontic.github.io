---
title: hal.dll | Hardware Abstraction Layer DLL
excerpt: What is hal.dll?
---

# hal.dll 

* File Path: `C:\Windows\system32\hal.dll`
* Description: Hardware Abstraction Layer DLL

## Hashes

Type | Hash
-- | --
MD5 | `4E32358F9F14ED7CAE0ACBB03CB68CAC`
SHA1 | `CE6A1F1582D038CBE9886BD45683DAFF2C969CA6`
SHA256 | `0967D74BEFF2B081F3394932D70023CD6013FBA9E032E47C43837860238C4DAD`
SHA384 | `A3F1182DB572B6F182BAB5D9E4A7B1B527BBF8D58972A92BBA888CFC16878561C181C5DA90A97E31188749EFD9BCB78A`
SHA512 | `349CE5797C1BE3B8F59303A49FF32138C8163FDFF9F20614B8A7940F6C7ED5DE4A6ACD8751DF1772EACF952272ABF61867547116D050D11C94CBF358B70F0EE0`
SSDEEP | `384:pkqP8+N5nC+k6yIwws9sCSWu2kWu8hDBRJlwuAzXulGswUm:Li+aITs75h1PIzrp`
IMP | `n/a`
PESHA1 | `B7132B09625AD52571C0C1D03DA7F8185081548B`
PE256 | `971FE367E613C98C6282771F75D2386CDF369F5F9CBD4F5F81BAF9A969D5131C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`HalAcpiGetTableEx` | 1 (0x1) | Exported Function | ntoskrnl.HalAcpiGetTableEx | 0x000033d0
`HalSetProfileInterval` | 66 (0x42) | Exported Function | ntoskrnl.HalSetProfileInterval | 0x00004215
`HalSetEnvironmentVariableEx` | 65 (0x41) | Exported Function | ntoskrnl.HalSetEnvironmentVariableEx | 0x000041da
`HalSetEnvironmentVariable` | 64 (0x40) | Exported Function | ntoskrnl.HalSetEnvironmentVariable | 0x0000419b
`HalSetDisplayParameters` | 63 (0x3f) | Exported Function | ntoskrnl.HalSetDisplayParameters | 0x00004160
`HalSetBusDataByOffset` | 62 (0x3e) | Exported Function | ntoskrnl.HalSetBusDataByOffset | 0x00004129
`HalSetBusData` | 61 (0x3d) | Exported Function | ntoskrnl.HalSetBusData | 0x000040fc
`HalSendSoftwareInterrupt` | 60 (0x3c) | Exported Function | ntoskrnl.HalSendSoftwareInterrupt | 0x000040cc
`HalSendNMI` | 59 (0x3b) | Exported Function | ntoskrnl.HalSendNMI | 0x0000409f
`HalReturnToFirmware` | 58 (0x3a) | Exported Function | ntoskrnl.HalReturnToFirmware | 0x00004077
`HalRequestSoftwareInterrupt` | 57 (0x39) | Exported Function | ntoskrnl.HalRequestSoftwareInterrupt | 0x0000403e
`HalRequestIpiSpecifyVector` | 56 (0x38) | Exported Function | ntoskrnl.HalRequestIpiSpecifyVector | 0x00003ffe
`HalRequestIpi` | 55 (0x37) | Exported Function | ntoskrnl.HalRequestIpi | 0x00003fcc
`HalRequestDeferredRecoveryServiceInterrupt` | 54 (0x36) | Exported Function | ntoskrnl.HalRequestDeferredRecoveryServiceInterrupt | 0x00003f8a
`HalRequestClockInterrupt` | 53 (0x35) | Exported Function | ntoskrnl.HalRequestClockInterrupt | 0x00003f3d
`HalReportResourceUsage` | 52 (0x34) | Exported Function | ntoskrnl.HalReportResourceUsage | 0x00003f04
`HalRegisterErrataCallbacks` | 51 (0x33) | Exported Function | ntoskrnl.HalRegisterErrataCallbacks | 0x00003ec9
`HalRegisterDynamicProcessor` | 50 (0x32) | Exported Function | ntoskrnl.HalRegisterDynamicProcessor | 0x00003e89
`HalReadDmaCounter` | 49 (0x31) | Exported Function | ntoskrnl.HalReadDmaCounter | 0x00003e52
`HalQueryRealTimeClock` | 48 (0x30) | Exported Function | ntoskrnl.HalQueryRealTimeClock | 0x00003e21
`HalSetRealTimeClock` | 67 (0x43) | Exported Function | ntoskrnl.HalSetRealTimeClock | 0x00004248
`HalQueryMaximumProcessorCount` | 47 (0x2f) | Exported Function | ntoskrnl.HalQueryMaximumProcessorCount | 0x00003de4
`HalStartDynamicProcessor` | 68 (0x44) | Exported Function | ntoskrnl.HalStartDynamicProcessor | 0x0000427e
`HalStartProfileInterrupt` | 70 (0x46) | Exported Function | ntoskrnl.HalStartProfileInterrupt | 0x000042ee
`x86BiosFreeBuffer` | 89 (0x59) | Exported Function | ntoskrnl.x86BiosFreeBuffer | 0x000046c0
`x86BiosCall` | 88 (0x58) | Exported Function | ntoskrnl.x86BiosCall | 0x00004699
`x86BiosAllocateBuffer` | 87 (0x57) | Exported Function | ntoskrnl.x86BiosAllocateBuffer | 0x0000466e
`KeStallExecutionProcessor` | 86 (0x56) | Exported Function | ntoskrnl.KeStallExecutionProcessor | 0x00004635
`KeQueryPerformanceCounter` | 85 (0x55) | Exported Function | ntoskrnl.KeQueryPerformanceCounter | 0x000045f8
`KeFlushWriteBuffer` | 84 (0x54) | Exported Function | ntoskrnl.KeFlushWriteBuffer | 0x000045c2
`KdHvComPortInUse` | 83 (0x53) | Exported Function | ntoskrnl.KdHvComPortInUse | 0x00004595
`KdComPortInUse` | 82 (0x52) | Exported Function | ntoskrnl.KdComPortInUse | 0x0000456c
`IoWritePartitionTable` | 81 (0x51) | Exported Function | ntoskrnl.IoWritePartitionTable | 0x0000453e
`IoSetPartitionInformation` | 80 (0x50) | Exported Function | ntoskrnl.IoSetPartitionInformation | 0x00004505
`IoReadPartitionTable` | 79 (0x4f) | Exported Function | ntoskrnl.IoReadPartitionTable | 0x000044cd
`IoMapTransfer` | 78 (0x4e) | Exported Function | ntoskrnl.IoMapTransfer | 0x000044a1
`IoFreeMapRegisters` | 77 (0x4d) | Exported Function | ntoskrnl.IoFreeMapRegisters | 0x00004477
`IoFreeAdapterChannel` | 76 (0x4c) | Exported Function | ntoskrnl.IoFreeAdapterChannel | 0x00004446
`IoFlushAdapterBuffers` | 75 (0x4b) | Exported Function | ntoskrnl.IoFlushAdapterBuffers | 0x00004412
`HalWheaUpdateCmciPolicy` | 74 (0x4a) | Exported Function | ntoskrnl.HalWheaUpdateCmciPolicy | 0x000043db
`HalTranslateBusAddress` | 73 (0x49) | Exported Function | ntoskrnl.HalTranslateBusAddress | 0x000043a3
`HalSystemVectorDispatchEntry` | 72 (0x48) | Exported Function | ntoskrnl.HalSystemVectorDispatchEntry | 0x00004366
`HalStopProfileInterrupt` | 71 (0x47) | Exported Function | ntoskrnl.HalStopProfileInterrupt | 0x00004328
`HalStartNextProcessor` | 69 (0x45) | Exported Function | ntoskrnl.HalStartNextProcessor | 0x000042b6
`x86BiosReadMemory` | 90 (0x5a) | Exported Function | ntoskrnl.x86BiosReadMemory | 0x000046ed
`HalQueryEnvironmentVariableInfoEx` | 46 (0x2e) | Exported Function | ntoskrnl.HalQueryEnvironmentVariableInfoEx | 0x00003d9b
`HalProcessorIdle` | 44 (0x2c) | Exported Function | ntoskrnl.HalProcessorIdle | 0x00003d22
`HalEnumerateProcessors` | 20 (0x14) | Exported Function | ntoskrnl.HalEnumerateProcessors | 0x00003840
`HalEnumerateEnvironmentVariablesEx` | 19 (0x13) | Exported Function | ntoskrnl.HalEnumerateEnvironmentVariablesEx | 0x000037fd
`HalEnableInterrupt` | 18 (0x12) | Exported Function | ntoskrnl.HalEnableInterrupt | 0x000037be
`HalDmaFreeCrashDumpRegistersEx` | 17 (0x11) | Exported Function | ntoskrnl.HalDmaFreeCrashDumpRegistersEx | 0x00003783
`HalDmaAllocateCrashDumpRegistersEx` | 16 (0x10) | Exported Function | ntoskrnl.HalDmaAllocateCrashDumpRegistersEx | 0x00003738
`HalDisplayString` | 15 (0xf) | Exported Function | ntoskrnl.HalDisplayString | 0x000036fb
`HalDisableInterrupt` | 14 (0xe) | Exported Function | ntoskrnl.HalDisableInterrupt | 0x000036cd
`HalConvertDeviceIdtToIrql` | 13 (0xd) | Exported Function | ntoskrnl.HalConvertDeviceIdtToIrql | 0x00003696
`HalClearSoftwareInterrupt` | 12 (0xc) | Exported Function | ntoskrnl.HalClearSoftwareInterrupt | 0x00003659
`HalCalibratePerformanceCounter` | 11 (0xb) | Exported Function | ntoskrnl.HalCalibratePerformanceCounter | 0x00003617
`HalBugCheckSystem` | 10 (0xa) | Exported Function | ntoskrnl.HalBugCheckSystem | 0x000035dd
`HalAssignSlotResources` | 9 (0x9) | Exported Function | ntoskrnl.HalAssignSlotResources | 0x000035ab
`HalAllProcessorsStarted` | 4 (0x4) | Exported Function | ntoskrnl.HalAllProcessorsStarted | 0x00003477
`HalAllocateHardwareCounters` | 8 (0x8) | Exported Function | ntoskrnl.HalAllocateHardwareCounters | 0x0000356f
`HalAllocateCrashDumpRegisters` | 7 (0x7) | Exported Function | ntoskrnl.HalAllocateCrashDumpRegisters | 0x0000352c
`HalAllocateCommonBuffer` | 6 (0x6) | Exported Function | ntoskrnl.HalAllocateCommonBuffer | 0x000034ed
`HalAllocateAdapterChannel` | 5 (0x5) | Exported Function | ntoskrnl.HalAllocateAdapterChannel | 0x000034b2
`HalAdjustResourceList` | 3 (0x3) | Exported Function | ntoskrnl.HalAdjustResourceList | 0x00003440
`HalAcquireDisplayOwnership` | 2 (0x2) | Exported Function | ntoskrnl.HalAcquireDisplayOwnership | 0x00003406
`HalFlushCommonBuffer` | 21 (0x15) | Exported Function | ntoskrnl.HalFlushCommonBuffer | 0x00003875
`HalQueryDisplayParameters` | 45 (0x2d) | Exported Function | ntoskrnl.HalQueryDisplayParameters | 0x00003d56
`HalFreeCommonBuffer` | 22 (0x16) | Exported Function | ntoskrnl.HalFreeCommonBuffer | 0x000038a7
`HalGetAdapter` | 24 (0x18) | Exported Function | ntoskrnl.HalGetAdapter | 0x0000390b
`HalPerformEndOfInterrupt` | 43 (0x2b) | Exported Function | ntoskrnl.HalPerformEndOfInterrupt | 0x00003cef
`HalMakeBeep` | 42 (0x2a) | Exported Function | ntoskrnl.HalMakeBeep | 0x00003cc1
`HalIsHyperThreadingEnabled` | 41 (0x29) | Exported Function | ntoskrnl.HalIsHyperThreadingEnabled | 0x00003c91
`HalInitSystem` | 37 (0x25) | Exported Function | ntoskrnl.HalInitSystem | 0x00003bc6
`HalInitializeProcessor` | 40 (0x28) | Exported Function | ntoskrnl.HalInitializeProcessor | 0x00003c56
`HalInitializeOnResume` | 39 (0x27) | Exported Function | ntoskrnl.HalInitializeOnResume | 0x00003c20
`HalInitializeBios` | 38 (0x26) | Exported Function | ntoskrnl.HalInitializeBios | 0x00003bef
`HalHandleNMI` | 36 (0x24) | Exported Function | ntoskrnl.HalHandleNMI | 0x00003ba2
`HalHandleMcheck` | 35 (0x23) | Exported Function | ntoskrnl.HalHandleMcheck | 0x00003b7c
`HalGetVectorInput` | 34 (0x22) | Exported Function | ntoskrnl.HalGetVectorInput | 0x00003b51
`HalGetProcessorIdByNtNumber` | 33 (0x21) | Exported Function | ntoskrnl.HalGetProcessorIdByNtNumber | 0x00003b1a
`HalGetMessageRoutingInfo` | 32 (0x20) | Exported Function | ntoskrnl.HalGetMessageRoutingInfo | 0x00003adc
`HalGetMemoryCachingRequirements` | 31 (0x1f) | Exported Function | ntoskrnl.HalGetMemoryCachingRequirements | 0x00003a9a
`HalGetInterruptVector` | 30 (0x1e) | Exported Function | ntoskrnl.HalGetInterruptVector | 0x00003a5b
`HalGetInterruptTargetInformation` | 29 (0x1d) | Exported Function | ntoskrnl.HalGetInterruptTargetInformation | 0x00003a1b
`HalGetEnvironmentVariableEx` | 28 (0x1c) | Exported Function | ntoskrnl.HalGetEnvironmentVariableEx | 0x000039d5
`HalGetEnvironmentVariable` | 27 (0x1b) | Exported Function | ntoskrnl.HalGetEnvironmentVariable | 0x00003996
`HalGetBusDataByOffset` | 26 (0x1a) | Exported Function | ntoskrnl.HalGetBusDataByOffset | 0x0000395d
`HalGetBusData` | 25 (0x19) | Exported Function | ntoskrnl.HalGetBusData | 0x00003930
`HalFreeHardwareCounters` | 23 (0x17) | Exported Function | ntoskrnl.HalFreeHardwareCounters | 0x000038dc
`x86BiosWriteMemory` | 91 (0x5b) | Exported Function | ntoskrnl.x86BiosWriteMemory | 0x0000471b


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hal.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/0967d74beff2b081f3394932d70023cd6013fba9e032e47c43837860238c4dad/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\DriverStore\FileRepository\wvmbus.inf_amd64_a8256b0fba59b299\vmbuspipe.dll](vmbuspipe.dll-8A1F3DD3A28B62699EBA45271A7397EA.md) | 44
[C:\Windows\system32\vmbuspipe.dll](vmbuspipe.dll-8A1F3DD3A28B62699EBA45271A7397EA.md) | 44

## Possible Misuse

*The following table contains possible examples of `hal.dll` being misused. While `hal.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $HAL = "HAL.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_stuxnet.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_stuxnet.yar) | $s1 = "\\SystemRoot\\System32\\hal.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s3 = "HAL.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s4 = "HAL.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s0 = "HAL.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


