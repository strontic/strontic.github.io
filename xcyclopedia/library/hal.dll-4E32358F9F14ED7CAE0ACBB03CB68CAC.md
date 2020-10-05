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

Function Name | Ordinal | Type
-- | -- | --
`HalSetBusData` | 61 | Exported Function
`HalSetBusDataByOffset` | 62 | Exported Function
`HalSendSoftwareInterrupt` | 60 | Exported Function
`HalReturnToFirmware` | 58 | Exported Function
`HalSendNMI` | 59 | Exported Function
`HalSetDisplayParameters` | 63 | Exported Function
`HalSetRealTimeClock` | 67 | Exported Function
`HalStartDynamicProcessor` | 68 | Exported Function
`HalSetProfileInterval` | 66 | Exported Function
`HalSetEnvironmentVariable` | 64 | Exported Function
`HalSetEnvironmentVariableEx` | 65 | Exported Function
`HalRegisterDynamicProcessor` | 50 | Exported Function
`HalRegisterErrataCallbacks` | 51 | Exported Function
`HalReadDmaCounter` | 49 | Exported Function
`HalQueryMaximumProcessorCount` | 47 | Exported Function
`HalQueryRealTimeClock` | 48 | Exported Function
`HalReportResourceUsage` | 52 | Exported Function
`HalRequestIpiSpecifyVector` | 56 | Exported Function
`HalRequestSoftwareInterrupt` | 57 | Exported Function
`HalRequestIpi` | 55 | Exported Function
`HalRequestClockInterrupt` | 53 | Exported Function
`HalRequestDeferredRecoveryServiceInterrupt` | 54 | Exported Function
`HalStartNextProcessor` | 69 | Exported Function
`KeFlushWriteBuffer` | 84 | Exported Function
`KeQueryPerformanceCounter` | 85 | Exported Function
`KdHvComPortInUse` | 83 | Exported Function
`IoWritePartitionTable` | 81 | Exported Function
`KdComPortInUse` | 82 | Exported Function
`KeStallExecutionProcessor` | 86 | Exported Function
`x86BiosReadMemory` | 90 | Exported Function
`x86BiosWriteMemory` | 91 | Exported Function
`x86BiosFreeBuffer` | 89 | Exported Function
`x86BiosAllocateBuffer` | 87 | Exported Function
`x86BiosCall` | 88 | Exported Function
`HalTranslateBusAddress` | 73 | Exported Function
`HalWheaUpdateCmciPolicy` | 74 | Exported Function
`HalSystemVectorDispatchEntry` | 72 | Exported Function
`HalStartProfileInterrupt` | 70 | Exported Function
`HalStopProfileInterrupt` | 71 | Exported Function
`IoFlushAdapterBuffers` | 75 | Exported Function
`IoReadPartitionTable` | 79 | Exported Function
`IoSetPartitionInformation` | 80 | Exported Function
`IoMapTransfer` | 78 | Exported Function
`IoFreeAdapterChannel` | 76 | Exported Function
`IoFreeMapRegisters` | 77 | Exported Function
`HalQueryEnvironmentVariableInfoEx` | 46 | Exported Function
`HalDisplayString` | 15 | Exported Function
`HalDmaAllocateCrashDumpRegistersEx` | 16 | Exported Function
`HalDisableInterrupt` | 14 | Exported Function
`HalClearSoftwareInterrupt` | 12 | Exported Function
`HalConvertDeviceIdtToIrql` | 13 | Exported Function
`HalDmaFreeCrashDumpRegistersEx` | 17 | Exported Function
`HalFlushCommonBuffer` | 21 | Exported Function
`HalFreeCommonBuffer` | 22 | Exported Function
`HalEnumerateProcessors` | 20 | Exported Function
`HalEnableInterrupt` | 18 | Exported Function
`HalEnumerateEnvironmentVariablesEx` | 19 | Exported Function
`HalAllocateAdapterChannel` | 5 | Exported Function
`HalAllocateCommonBuffer` | 6 | Exported Function
`HalAdjustResourceList` | 3 | Exported Function
`HalAcpiGetTableEx` | 1 | Exported Function
`HalAcquireDisplayOwnership` | 2 | Exported Function
`HalAllocateCrashDumpRegisters` | 7 | Exported Function
`HalBugCheckSystem` | 10 | Exported Function
`HalCalibratePerformanceCounter` | 11 | Exported Function
`HalAssignSlotResources` | 9 | Exported Function
`HalAllocateHardwareCounters` | 8 | Exported Function
`HalAllProcessorsStarted` | 4 | Exported Function
`HalFreeHardwareCounters` | 23 | Exported Function
`HalInitializeOnResume` | 39 | Exported Function
`HalInitializeProcessor` | 40 | Exported Function
`HalInitializeBios` | 38 | Exported Function
`HalHandleMcheck` | 35 | Exported Function
`HalHandleNMI` | 36 | Exported Function
`HalInitSystem` | 37 | Exported Function
`HalProcessorIdle` | 44 | Exported Function
`HalQueryDisplayParameters` | 45 | Exported Function
`HalPerformEndOfInterrupt` | 43 | Exported Function
`HalIsHyperThreadingEnabled` | 41 | Exported Function
`HalMakeBeep` | 42 | Exported Function
`HalGetEnvironmentVariable` | 27 | Exported Function
`HalGetEnvironmentVariableEx` | 28 | Exported Function
`HalGetBusDataByOffset` | 26 | Exported Function
`HalGetAdapter` | 24 | Exported Function
`HalGetBusData` | 25 | Exported Function
`HalGetInterruptTargetInformation` | 29 | Exported Function
`HalGetProcessorIdByNtNumber` | 33 | Exported Function
`HalGetVectorInput` | 34 | Exported Function
`HalGetMessageRoutingInfo` | 32 | Exported Function
`HalGetInterruptVector` | 30 | Exported Function
`HalGetMemoryCachingRequirements` | 31 | Exported Function


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


