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
`public: __cdecl CBdeCfgLibraryLoader::CBdeCfgLibraryLoader(void) __ptr64` | 7 | Exported Function
`public: __cdecl CBdeCfgLibraryLoader::~CBdeCfgLibraryLoader(void) __ptr64` | 12 | Exported Function
`public: __cdecl CDriveConfiguration::CDriveConfiguration(class CDriveConfiguration const & __ptr64) __ptr64` | 8 | Exported Function
`public: __cdecl CBdeCfgLibraryLoader::CBdeCfgLibraryLoader(class CBdeCfgLibraryLoader const & __ptr64) __ptr64` | 6 | Exported Function
`public: __cdecl CBcdStore::CBcdStore(class CBcdStore && __ptr64) __ptr64` | 2 | Exported Function
`public: __cdecl CBcdStore::CBcdStore(class CBcdStore const & __ptr64) __ptr64` | 3 | Exported Function
`public: __cdecl CBcdWmiWrapper::CBcdWmiWrapper(class CBcdWmiWrapper const & __ptr64) __ptr64` | 5 | Exported Function
`public: bool __cdecl CDriveConfiguration::ActionRequiresMerge(void) __ptr64` | 22 | Exported Function
`public: bool __cdecl CDriveConfiguration::ActionRequiresShrink(void) __ptr64` | 23 | Exported Function
`public: bool __cdecl CDriveConfiguration::Initialized(void) __ptr64` | 94 | Exported Function
`public: bool __cdecl CDriveConfiguration::ActionRequiresCreate(void) __ptr64` | 21 | Exported Function
`public: __cdecl CDriveConfiguration::CDriveConfiguration(void) __ptr64` | 9 | Exported Function
`public: __cdecl CDriveConfiguration::~CDriveConfiguration(void) __ptr64` | 13 | Exported Function
`public: bool __cdecl CBdeCfgLibraryLoader::LibraryLoaded(void) __ptr64` | 96 | Exported Function
`private: static void __cdecl CDriveConfiguration::InitializeEntry(void * __ptr64)` | 90 | Exported Function
`private: void __cdecl CDriveConfiguration::Cleanup(void) __ptr64` | 64 | Exported Function
`protected: __cdecl CBcdStore::CBcdStore(void) __ptr64` | 1 | Exported Function
`private: static void __cdecl CDriveConfiguration::DriveConfigurationEntry(void * __ptr64)` | 69 | Exported Function
`private: long __cdecl CDriveConfiguration::Thread_Initialize(void) __ptr64` | 103 | Exported Function
`private: static void __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibraryEntry(void * __ptr64)` | 87 | Exported Function
`private: static void __cdecl CDriveConfiguration::CancelConfigurationEntry(void * __ptr64)` | 62 | Exported Function
`protected: long __cdecl CBcdWmiWrapper::InitializeInstance(struct IWbemServices * __ptr64,struct IWbemClassObject * __ptr64) __ptr64` | 92 | Exported Function
`protected: struct IWbemServices * __ptr64 __cdecl CBcdWmiWrapper::GetNamespace(void) __ptr64` | 75 | Exported Function
`protected: virtual __cdecl CBcdWmiWrapper::~CBcdWmiWrapper(void) __ptr64` | 11 | Exported Function
`protected: long __cdecl CBcdWmiWrapper::InitializeClass(unsigned short const * __ptr64) __ptr64` | 89 | Exported Function
`protected: __cdecl CBcdWmiWrapper::CBcdWmiWrapper(void) __ptr64` | 4 | Exported Function
`protected: long __cdecl CBcdWmiWrapper::CreateInParams(unsigned short const * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 67 | Exported Function
`protected: long __cdecl CBcdWmiWrapper::ExecuteMethod(unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 70 | Exported Function
`public: class CBcdStore & __ptr64 __cdecl CBcdStore::operator=(class CBcdStore && __ptr64) __ptr64` | 14 | Exported Function
`public: unsigned __int64 __cdecl CDriveConfiguration::GetShrinkSize(void) __ptr64` | 78 | Exported Function
`public: unsigned __int64 __cdecl CDriveConfiguration::GetTargetPartitionSize(void) __ptr64` | 83 | Exported Function
`public: unsigned long __cdecl CDriveConfiguration::GetNumberOfSteps(void) __ptr64` | 77 | Exported Function
`public: static long __cdecl CBcdStore::CreateClass(class CBcdStore * __ptr64 * __ptr64)` | 66 | Exported Function
`public: long __cdecl CDriveConfiguration::Initialize(struct _BDECFG_PARAMS const * __ptr64,struct _BDECFG_SIZE_REQUIREMENTS * __ptr64 const,class IConfigurationProgress * __ptr64) __ptr64` | 85 | Exported Function
`public: long __cdecl CDriveConfiguration::IsMergeTargetWinRE(int * __ptr64) __ptr64` | 95 | Exported Function
`public: long __cdecl CDriveConfiguration::QueryStepPercentComplete(unsigned long * __ptr64) __ptr64` | 99 | Exported Function
`public: unsigned short __cdecl CDriveConfiguration::GetTargetDriveLetter(void) __ptr64` | 81 | Exported Function
`public: virtual __cdecl CBcdStore::~CBcdStore(void) __ptr64` | 10 | Exported Function
`public: void __cdecl CBdeCfgLibraryLoader::Unload(void) __ptr64` | 104 | Exported Function
`public: unsigned short __cdecl CDriveConfiguration::GetNewDriveLetter(void) __ptr64` | 76 | Exported Function
`public: unsigned long __cdecl CDriveConfiguration::GetStepExecutionOrder(enum _BDECFG_STEP_ID) __ptr64` | 79 | Exported Function
`public: unsigned long __cdecl CDriveConfiguration::GetTargetDiskNumber(void) __ptr64` | 80 | Exported Function
`public: unsigned long __cdecl CDriveConfiguration::GetTargetPartitionNumber(void) __ptr64` | 82 | Exported Function
`public: enum BDECFG_ACTION_TYPE __cdecl CDriveConfiguration::GetActionType(void) __ptr64` | 72 | Exported Function
`public: long __cdecl CBcdStore::ExportSystemStore(unsigned short const * __ptr64) __ptr64` | 71 | Exported Function
`public: long __cdecl CBcdStore::ImportSystemStore(unsigned short const * __ptr64) __ptr64` | 84 | Exported Function
`public: class CDriveConfiguration & __ptr64 __cdecl CDriveConfiguration::operator=(class CDriveConfiguration const & __ptr64) __ptr64` | 18 | Exported Function
`public: class CBcdStore & __ptr64 __cdecl CBcdStore::operator=(class CBcdStore const & __ptr64) __ptr64` | 15 | Exported Function
`public: class CBcdWmiWrapper & __ptr64 __cdecl CBcdWmiWrapper::operator=(class CBcdWmiWrapper const & __ptr64) __ptr64` | 16 | Exported Function
`public: class CBdeCfgLibraryLoader & __ptr64 __cdecl CBdeCfgLibraryLoader::operator=(class CBdeCfgLibraryLoader const & __ptr64) __ptr64` | 17 | Exported Function
`public: long __cdecl CDriveConfiguration::ConfigureDrive(void) __ptr64` | 65 | Exported Function
`public: long __cdecl CDriveConfiguration::GetConfigurationResult(void) __ptr64` | 73 | Exported Function
`public: long __cdecl CDriveConfiguration::GetInitializationResult(void) __ptr64` | 74 | Exported Function
`public: long __cdecl CDriveConfiguration::CancelConfiguration(void) __ptr64` | 61 | Exported Function
`public: long __cdecl CBcdStore::OpenStore(unsigned short const * __ptr64,class CBcdStore * __ptr64 * __ptr64) __ptr64` | 98 | Exported Function
`public: long __cdecl CBcdStore::RemapObjectDevices(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 100 | Exported Function
`public: long __cdecl CBdeCfgLibraryLoader::Load(void) __ptr64` | 97 | Exported Function
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
`private: long __cdecl CBcdWmiWrapper::InitializeNamespace(void) __ptr64` | 93 | Exported Function
`BdeCfgUninitialize` | 60 | Exported Function
`BdeCfgRestart` | 57 | Exported Function
`BdeCfgSecureFormatPartition` | 58 | Exported Function
`BdeCfgShrinkSimpleVolume` | 59 | Exported Function
`private: long __cdecl CDriveConfiguration::InitializeFromParams(struct IVdsVolume * __ptr64) __ptr64` | 91 | Exported Function
`private: long __cdecl CDriveConfiguration::SetConfigurationStep(enum _BDECFG_STEP_ID) __ptr64` | 101 | Exported Function
`private: long __cdecl CDriveConfiguration::Thread_ConfigureDrive(void) __ptr64` | 102 | Exported Function
`private: long __cdecl CDriveConfiguration::DetectTargetDrive(struct IVdsVolume * __ptr64) __ptr64` | 68 | Exported Function
`private: long __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibrary(void) __ptr64` | 86 | Exported Function
`private: long __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibrary_Thread(void) __ptr64` | 88 | Exported Function
`private: long __cdecl CDriveConfiguration::CancelConfiguration_Thread(void) __ptr64` | 63 | Exported Function
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


