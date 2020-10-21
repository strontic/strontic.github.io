---
title: BdeHdCfgLib.dll | Windows BitLocker Drive Preparation Tool
excerpt: What is BdeHdCfgLib.dll?
---

# BdeHdCfgLib.dll 

* File Path: `C:\Windows\system32\BdeHdCfgLib.dll`
* Description: Windows BitLocker Drive Preparation Tool

## Hashes

Type | Hash
-- | --
MD5 | `9B63D322781AEF98D429AECE09249F8B`
SHA1 | `74D128407FB29302024C527DF578B1A4D4A4EEF1`
SHA256 | `D9A66A8F558BF99B70A5990A3A9FE37618A27EBC537C3D19B13115C5D35DCDAF`
SHA384 | `131CCEF132804C5416D633BD77E4DAFC2E9E808CE640FB03FD60044D3243024461394AE7DBE28EADFBD996335F4E0685`
SHA512 | `12B883C171320AC10354AC0634A86E45A1E56730EC596448F9C0BF98706F1B3DA06A2619BE18CC311568E3DE67CE4741C7E8965C9A46EC65167F2F8E1978C1BC`
SSDEEP | `1536:HKysfgWgkNxt/9XJ4D53DdQzWMFYdFDAPc68gOtbAhJnt0nxPWv7ECsa6S2Zqrz:qX/UTkedAE68cJnt0nxuB6SGq`
IMP | `C47FC13A9F0F57FC9C581929114D90E4`
PESHA1 | `0476DA38FADBEE4AF3961AAD227AB07C82EDA1C3`
PE256 | `A6637EB5C843C60F6BFA18E136858E12D0367E9FE8243EB7318B697EF1088E11`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CBdeCfgLibraryLoader` | 7 | Exported Function
`public: __cdecl CBdeCfgLibraryLoader::~CBdeCfgLibraryLoader(void) __ptr64` | 12 | Exported Function
`CDriveConfiguration` | 8 | Exported Function
`CBdeCfgLibraryLoader` | 6 | Exported Function
`CBcdStore` | 2 | Exported Function
`CBcdStore` | 3 | Exported Function
`CBcdWmiWrapper` | 5 | Exported Function
`ActionRequiresMerge` | 22 | Exported Function
`ActionRequiresShrink` | 23 | Exported Function
`Initialized` | 94 | Exported Function
`ActionRequiresCreate` | 21 | Exported Function
`CDriveConfiguration` | 9 | Exported Function
`public: __cdecl CDriveConfiguration::~CDriveConfiguration(void) __ptr64` | 13 | Exported Function
`LibraryLoaded` | 96 | Exported Function
`InitializeEntry` | 90 | Exported Function
`Cleanup` | 64 | Exported Function
`CBcdStore` | 1 | Exported Function
`DriveConfigurationEntry` | 69 | Exported Function
`Thread_Initialize` | 103 | Exported Function
`InitializeAndHoldLibraryEntry` | 87 | Exported Function
`CancelConfigurationEntry` | 62 | Exported Function
`InitializeInstance` | 92 | Exported Function
`GetNamespace` | 75 | Exported Function
`protected: virtual __cdecl CBcdWmiWrapper::~CBcdWmiWrapper(void) __ptr64` | 11 | Exported Function
`InitializeClass` | 89 | Exported Function
`CBcdWmiWrapper` | 4 | Exported Function
`CreateInParams` | 67 | Exported Function
`ExecuteMethod` | 70 | Exported Function
`operator` | 14 | Exported Function
`GetShrinkSize` | 78 | Exported Function
`GetTargetPartitionSize` | 83 | Exported Function
`GetNumberOfSteps` | 77 | Exported Function
`CreateClass` | 66 | Exported Function
`Initialize` | 85 | Exported Function
`IsMergeTargetWinRE` | 95 | Exported Function
`QueryStepPercentComplete` | 99 | Exported Function
`GetTargetDriveLetter` | 81 | Exported Function
`public: virtual __cdecl CBcdStore::~CBcdStore(void) __ptr64` | 10 | Exported Function
`Unload` | 104 | Exported Function
`GetNewDriveLetter` | 76 | Exported Function
`GetStepExecutionOrder` | 79 | Exported Function
`GetTargetDiskNumber` | 80 | Exported Function
`GetTargetPartitionNumber` | 82 | Exported Function
`GetActionType` | 72 | Exported Function
`ExportSystemStore` | 71 | Exported Function
`ImportSystemStore` | 84 | Exported Function
`operator` | 18 | Exported Function
`operator` | 15 | Exported Function
`operator` | 16 | Exported Function
`operator` | 17 | Exported Function
`ConfigureDrive` | 65 | Exported Function
`GetConfigurationResult` | 73 | Exported Function
`GetInitializationResult` | 74 | Exported Function
`CancelConfiguration` | 61 | Exported Function
`OpenStore` | 98 | Exported Function
`RemapObjectDevices` | 100 | Exported Function
`Load` | 97 | Exported Function
`BdeCfgGetBootVolume` | 42 | Exported Function
`BdeCfgGetDeviceNameFromVolume` | 43 | Exported Function
`BdeCfgGetMaxShrinkSize` | 44 | Exported Function
`BdeCfgFindVolumeWithProp` | 41 | Exported Function
`BdeCfgFindLargestUnallocatedExtent` | 38 | Exported Function
`BdeCfgFindRecoveryPartitionGPT` | 39 | Exported Function
`BdeCfgFindVolumeWithName` | 40 | Exported Function
`BdeCfgInitialize` | 49 | Exported Function
`BdeCfgIsDiskConfiguredForBitLocker` | 50 | Exported Function
`BdeCfgIsElevated` | 51 | Exported Function
`BdeCfgGetVolumeFromId` | 48 | Exported Function
`BdeCfgGetNtfsVolumeSize` | 45 | Exported Function
`BdeCfgGetVolumeDisk` | 46 | Exported Function
`BdeCfgGetVolumeDriveLetter` | 47 | Exported Function
`BdeCfgCheckVolumeAsCandidate` | 28 | Exported Function
`BdeCfgCleanupOldBootFiles` | 29 | Exported Function
`BdeCfgCountGPTPartitions` | 30 | Exported Function
`BdeCfgCheckGPTRecoveryPartition` | 27 | Exported Function
`BdeCfgCalculateSizeRequirements` | 24 | Exported Function
`BdeCfgCanCreateActivePartOnDisk` | 25 | Exported Function
`BdeCfgCheckAndGetBootVolume` | 26 | Exported Function
`BdeCfgFindBasicVolumeExtent` | 35 | Exported Function
`BdeCfgFindCandidateVolumes` | 36 | Exported Function
`BdeCfgFindGPTRecoveryPartitionCandidate` | 37 | Exported Function
`BdeCfgDisableWinRE` | 34 | Exported Function
`BdeCfgCreateWinREPartitionGPT` | 31 | Exported Function
`BdeCfgDetectWinRESize` | 32 | Exported Function
`BdeCfgDetectWinREVolumeName` | 33 | Exported Function
`BdeCfgIsWinREOnOSVolume` | 52 | Exported Function
`const CBcdStore::``vftable'` | 19 | Exported Function
`const CBcdWmiWrapper::``vftable'` | 20 | Exported Function
`InitializeNamespace` | 93 | Exported Function
`BdeCfgUninitialize` | 60 | Exported Function
`BdeCfgRestart` | 57 | Exported Function
`BdeCfgSecureFormatPartition` | 58 | Exported Function
`BdeCfgShrinkSimpleVolume` | 59 | Exported Function
`InitializeFromParams` | 91 | Exported Function
`SetConfigurationStep` | 101 | Exported Function
`Thread_ConfigureDrive` | 102 | Exported Function
`DetectTargetDrive` | 68 | Exported Function
`InitializeAndHoldLibrary` | 86 | Exported Function
`InitializeAndHoldLibrary_Thread` | 88 | Exported Function
`CancelConfiguration_Thread` | 63 | Exported Function
`BdeCfgLogCommandLineParams` | 107 | Exported Function
`BdeCfgLogDetectedWinRE` | 108 | Exported Function
`BdeCfgLogEnumExtent` | 109 | Exported Function
`BdeCfgLogClose` | 106 | Exported Function
`BdeCfgLoadErrorString` | 53 | Exported Function
`BdeCfgLoadResourceString` | 54 | Exported Function
`BdeCfgLogCandidateDrive` | 105 | Exported Function
`BdeCfgLogWarning` | 114 | Exported Function
`BdeCfgMigrateBootHive` | 55 | Exported Function
`BdeCfgMoveWinRE` | 56 | Exported Function
`BdeCfgLogInit` | 113 | Exported Function
`BdeCfgLogError` | 110 | Exported Function
`BdeCfgLogFailedTarget` | 111 | Exported Function
`BdeCfgLogFoundUnallocatedExtent` | 112 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BdeHdCfgLib.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d9a66a8f558bf99b70a5990a3a9fe37618a27ebc537c3d19b13115c5d35dcdaf/detection/





MIT License. Copyright (c) 2020 Strontic.


