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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BdeCfgCalculateSizeRequirements` | 24 (0x18) | Exported Function | 0x0000000180008730 | 0x00008730
`public: bool __cdecl CDriveConfiguration::ActionRequiresMerge(void) __ptr64` | 22 (0x16) | Exported Function | 0x000000018000e970 | 0x0000e970
`public: bool __cdecl CDriveConfiguration::ActionRequiresCreate(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018000e950 | 0x0000e950
`public: bool __cdecl CBdeCfgLibraryLoader::LibraryLoaded(void) __ptr64` | 96 (0x60) | Exported Function | 0x000000018000ce70 | 0x0000ce70
`public: __cdecl CDriveConfiguration::~CDriveConfiguration(void) __ptr64` | 13 (0xd) | Exported Function | 0x000000018000e8b0 | 0x0000e8b0
`public: __cdecl CDriveConfiguration::CDriveConfiguration(void) __ptr64` | 9 (0x9) | Exported Function | 0x000000018000e840 | 0x0000e840
`public: __cdecl CDriveConfiguration::CDriveConfiguration(class CDriveConfiguration const & __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001200 | 0x00001200
`public: __cdecl CBdeCfgLibraryLoader::~CBdeCfgLibraryLoader(void) __ptr64` | 12 (0xc) | Exported Function | 0x000000018000ce00 | 0x0000ce00
`public: __cdecl CBdeCfgLibraryLoader::CBdeCfgLibraryLoader(void) __ptr64` | 7 (0x7) | Exported Function | 0x000000018000cdc0 | 0x0000cdc0
`public: __cdecl CBdeCfgLibraryLoader::CBdeCfgLibraryLoader(class CBdeCfgLibraryLoader const & __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001010 | 0x00001010
`public: __cdecl CBcdWmiWrapper::CBcdWmiWrapper(class CBcdWmiWrapper const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180001050 | 0x00001050
`public: __cdecl CBcdStore::CBcdStore(class CBcdStore const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001190 | 0x00001190
`public: bool __cdecl CDriveConfiguration::ActionRequiresShrink(void) __ptr64` | 23 (0x17) | Exported Function | 0x000000018000e940 | 0x0000e940
`public: __cdecl CBcdStore::CBcdStore(class CBcdStore && __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001190 | 0x00001190
`protected: struct IWbemServices * __ptr64 __cdecl CBcdWmiWrapper::GetNamespace(void) __ptr64` | 75 (0x4b) | Exported Function | 0x00000001800093c0 | 0x000093c0
`protected: long __cdecl CBcdWmiWrapper::InitializeInstance(struct IWbemServices * __ptr64,struct IWbemClassObject * __ptr64) __ptr64` | 92 (0x5c) | Exported Function | 0x00000001800091b0 | 0x000091b0
`protected: long __cdecl CBcdWmiWrapper::InitializeClass(unsigned short const * __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180009110 | 0x00009110
`protected: long __cdecl CBcdWmiWrapper::ExecuteMethod(unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x00000001800094b0 | 0x000094b0
`protected: long __cdecl CBcdWmiWrapper::CreateInParams(unsigned short const * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800093d0 | 0x000093d0
`protected: __cdecl CBcdWmiWrapper::CBcdWmiWrapper(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180008f30 | 0x00008f30
`protected: __cdecl CBcdStore::CBcdStore(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001150 | 0x00001150
`private: void __cdecl CDriveConfiguration::Cleanup(void) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180010100 | 0x00010100
`private: static void __cdecl CDriveConfiguration::InitializeEntry(void * __ptr64)` | 90 (0x5a) | Exported Function | 0x000000018000f510 | 0x0000f510
`private: static void __cdecl CDriveConfiguration::DriveConfigurationEntry(void * __ptr64)` | 69 (0x45) | Exported Function | 0x000000018000edf0 | 0x0000edf0
`private: static void __cdecl CDriveConfiguration::CancelConfigurationEntry(void * __ptr64)` | 62 (0x3e) | Exported Function | 0x000000018000ebd0 | 0x0000ebd0
`protected: virtual __cdecl CBcdWmiWrapper::~CBcdWmiWrapper(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180008f60 | 0x00008f60
`public: bool __cdecl CDriveConfiguration::Initialized(void) __ptr64` | 94 (0x5e) | Exported Function | 0x00000001800011d0 | 0x000011d0
`public: class CBcdStore & __ptr64 __cdecl CBcdStore::operator=(class CBcdStore && __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180001090 | 0x00001090
`public: class CBcdStore & __ptr64 __cdecl CBcdStore::operator=(class CBcdStore const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180001090 | 0x00001090
`public: unsigned short __cdecl CDriveConfiguration::GetTargetDriveLetter(void) __ptr64` | 81 (0x51) | Exported Function | 0x000000018000e9c0 | 0x0000e9c0
`public: unsigned short __cdecl CDriveConfiguration::GetNewDriveLetter(void) __ptr64` | 76 (0x4c) | Exported Function | 0x000000018000ea60 | 0x0000ea60
`public: unsigned long __cdecl CDriveConfiguration::GetTargetPartitionNumber(void) __ptr64` | 82 (0x52) | Exported Function | 0x000000018000ea20 | 0x0000ea20
`public: unsigned long __cdecl CDriveConfiguration::GetTargetDiskNumber(void) __ptr64` | 80 (0x50) | Exported Function | 0x000000018000e9f0 | 0x0000e9f0
`public: unsigned long __cdecl CDriveConfiguration::GetStepExecutionOrder(enum _BDECFG_STEP_ID) __ptr64` | 79 (0x4f) | Exported Function | 0x000000018000eb00 | 0x0000eb00
`public: unsigned long __cdecl CDriveConfiguration::GetNumberOfSteps(void) __ptr64` | 77 (0x4d) | Exported Function | 0x000000018000eb60 | 0x0000eb60
`public: unsigned __int64 __cdecl CDriveConfiguration::GetTargetPartitionSize(void) __ptr64` | 83 (0x53) | Exported Function | 0x000000018000e990 | 0x0000e990
`public: unsigned __int64 __cdecl CDriveConfiguration::GetShrinkSize(void) __ptr64` | 78 (0x4e) | Exported Function | 0x000000018000ea50 | 0x0000ea50
`public: static long __cdecl CBcdStore::CreateClass(class CBcdStore * __ptr64 * __ptr64)` | 66 (0x42) | Exported Function | 0x0000000180009b40 | 0x00009b40
`public: long __cdecl CDriveConfiguration::QueryStepPercentComplete(unsigned long * __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x000000018000ed60 | 0x0000ed60
`public: long __cdecl CDriveConfiguration::IsMergeTargetWinRE(int * __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018000ea90 | 0x0000ea90
`public: long __cdecl CDriveConfiguration::Initialize(struct _BDECFG_PARAMS const * __ptr64,struct _BDECFG_SIZE_REQUIREMENTS * __ptr64 const,class IConfigurationProgress * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x000000018000f480 | 0x0000f480
`public: long __cdecl CDriveConfiguration::GetInitializationResult(void) __ptr64` | 74 (0x4a) | Exported Function | 0x00000001800011e0 | 0x000011e0
`public: long __cdecl CDriveConfiguration::GetConfigurationResult(void) __ptr64` | 73 (0x49) | Exported Function | 0x00000001800011f0 | 0x000011f0
`public: long __cdecl CDriveConfiguration::ConfigureDrive(void) __ptr64` | 65 (0x41) | Exported Function | 0x000000018000eba0 | 0x0000eba0
`public: long __cdecl CDriveConfiguration::CancelConfiguration(void) __ptr64` | 61 (0x3d) | Exported Function | 0x000000018000ed30 | 0x0000ed30
`public: long __cdecl CBdeCfgLibraryLoader::Load(void) __ptr64` | 97 (0x61) | Exported Function | 0x000000018000ce80 | 0x0000ce80
`public: long __cdecl CBcdStore::RemapObjectDevices(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180009bf0 | 0x00009bf0
`public: long __cdecl CBcdStore::OpenStore(unsigned short const * __ptr64,class CBcdStore * __ptr64 * __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x0000000180009880 | 0x00009880
`public: long __cdecl CBcdStore::ImportSystemStore(unsigned short const * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180009760 | 0x00009760
`public: long __cdecl CBcdStore::ExportSystemStore(unsigned short const * __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180009640 | 0x00009640
`public: enum BDECFG_ACTION_TYPE __cdecl CDriveConfiguration::GetActionType(void) __ptr64` | 72 (0x48) | Exported Function | 0x000000018000e980 | 0x0000e980
`public: class CDriveConfiguration & __ptr64 __cdecl CDriveConfiguration::operator=(class CDriveConfiguration const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180001200 | 0x00001200
`public: class CBdeCfgLibraryLoader & __ptr64 __cdecl CBdeCfgLibraryLoader::operator=(class CBdeCfgLibraryLoader const & __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180001010 | 0x00001010
`public: class CBcdWmiWrapper & __ptr64 __cdecl CBcdWmiWrapper::operator=(class CBcdWmiWrapper const & __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180001090 | 0x00001090
`private: static void __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibraryEntry(void * __ptr64)` | 87 (0x57) | Exported Function | 0x000000018000d010 | 0x0000d010
`private: long __cdecl CDriveConfiguration::Thread_Initialize(void) __ptr64` | 103 (0x67) | Exported Function | 0x000000018000f550 | 0x0000f550
`private: long __cdecl CDriveConfiguration::Thread_ConfigureDrive(void) __ptr64` | 102 (0x66) | Exported Function | 0x000000018000eec0 | 0x0000eec0
`private: long __cdecl CDriveConfiguration::SetConfigurationStep(enum _BDECFG_STEP_ID) __ptr64` | 101 (0x65) | Exported Function | 0x000000018000ee30 | 0x0000ee30
`BdeCfgInitialize` | 49 (0x31) | Exported Function | 0x0000000180001350 | 0x00001350
`BdeCfgGetVolumeFromId` | 48 (0x30) | Exported Function | 0x00000001800014d0 | 0x000014d0
`BdeCfgGetVolumeDriveLetter` | 47 (0x2f) | Exported Function | 0x0000000180006c60 | 0x00006c60
`BdeCfgGetVolumeDisk` | 46 (0x2e) | Exported Function | 0x0000000180001570 | 0x00001570
`BdeCfgGetNtfsVolumeSize` | 45 (0x2d) | Exported Function | 0x00000001800031c0 | 0x000031c0
`BdeCfgGetMaxShrinkSize` | 44 (0x2c) | Exported Function | 0x00000001800023b0 | 0x000023b0
`BdeCfgGetDeviceNameFromVolume` | 43 (0x2b) | Exported Function | 0x0000000180001e20 | 0x00001e20
`BdeCfgGetBootVolume` | 42 (0x2a) | Exported Function | 0x0000000180005320 | 0x00005320
`BdeCfgFindVolumeWithProp` | 41 (0x29) | Exported Function | 0x0000000180002390 | 0x00002390
`BdeCfgFindVolumeWithName` | 40 (0x28) | Exported Function | 0x0000000180002370 | 0x00002370
`BdeCfgFindRecoveryPartitionGPT` | 39 (0x27) | Exported Function | 0x0000000180005b90 | 0x00005b90
`BdeCfgFindLargestUnallocatedExtent` | 38 (0x26) | Exported Function | 0x00000001800038f0 | 0x000038f0
`BdeCfgFindGPTRecoveryPartitionCandidate` | 37 (0x25) | Exported Function | 0x0000000180005f80 | 0x00005f80
`BdeCfgFindCandidateVolumes` | 36 (0x24) | Exported Function | 0x0000000180003c90 | 0x00003c90
`BdeCfgFindBasicVolumeExtent` | 35 (0x23) | Exported Function | 0x00000001800025d0 | 0x000025d0
`BdeCfgDisableWinRE` | 34 (0x22) | Exported Function | 0x00000001800064e0 | 0x000064e0
`BdeCfgDetectWinREVolumeName` | 33 (0x21) | Exported Function | 0x0000000180007510 | 0x00007510
`BdeCfgDetectWinRESize` | 32 (0x20) | Exported Function | 0x0000000180006510 | 0x00006510
`BdeCfgCreateWinREPartitionGPT` | 31 (0x1f) | Exported Function | 0x0000000180005730 | 0x00005730
`BdeCfgCountGPTPartitions` | 30 (0x1e) | Exported Function | 0x00000001800055f0 | 0x000055f0
`BdeCfgCleanupOldBootFiles` | 29 (0x1d) | Exported Function | 0x0000000180007e60 | 0x00007e60
`BdeCfgCheckVolumeAsCandidate` | 28 (0x1c) | Exported Function | 0x00000001800049f0 | 0x000049f0
`BdeCfgCheckGPTRecoveryPartition` | 27 (0x1b) | Exported Function | 0x0000000180005dc0 | 0x00005dc0
`BdeCfgCheckAndGetBootVolume` | 26 (0x1a) | Exported Function | 0x0000000180005250 | 0x00005250
`BdeCfgCanCreateActivePartOnDisk` | 25 (0x19) | Exported Function | 0x0000000180003a30 | 0x00003a30
`BdeCfgIsDiskConfiguredForBitLocker` | 50 (0x32) | Exported Function | 0x0000000180005950 | 0x00005950
`public: virtual __cdecl CBcdStore::~CBcdStore(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180001180 | 0x00001180
`BdeCfgIsElevated` | 51 (0x33) | Exported Function | 0x00000001800063d0 | 0x000063d0
`BdeCfgLoadErrorString` | 53 (0x35) | Exported Function | 0x0000000180008ab0 | 0x00008ab0
`private: long __cdecl CDriveConfiguration::InitializeFromParams(struct IVdsVolume * __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x000000018000f710 | 0x0000f710
`private: long __cdecl CDriveConfiguration::DetectTargetDrive(struct IVdsVolume * __ptr64) __ptr64` | 68 (0x44) | Exported Function | 0x000000018000fc90 | 0x0000fc90
`private: long __cdecl CDriveConfiguration::CancelConfiguration_Thread(void) __ptr64` | 63 (0x3f) | Exported Function | 0x000000018000ec20 | 0x0000ec20
`private: long __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibrary_Thread(void) __ptr64` | 88 (0x58) | Exported Function | 0x000000018000d0b0 | 0x0000d0b0
`private: long __cdecl CBdeCfgLibraryLoader::InitializeAndHoldLibrary(void) __ptr64` | 86 (0x56) | Exported Function | 0x000000018000cfe0 | 0x0000cfe0
`private: long __cdecl CBcdWmiWrapper::InitializeNamespace(void) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180008fd0 | 0x00008fd0
`const CBcdWmiWrapper::``vftable'` | 20 (0x14) | Exported Function | 0x0000000180012010 | 0x00012010
`const CBcdStore::``vftable'` | 19 (0x13) | Exported Function | 0x0000000180012010 | 0x00012010
`BdeCfgUninitialize` | 60 (0x3c) | Exported Function | 0x0000000180001490 | 0x00001490
`BdeCfgShrinkSimpleVolume` | 59 (0x3b) | Exported Function | 0x0000000180002440 | 0x00002440
`BdeCfgSecureFormatPartition` | 58 (0x3a) | Exported Function | 0x0000000180002f60 | 0x00002f60
`BdeCfgRestart` | 57 (0x39) | Exported Function | 0x0000000180006360 | 0x00006360
`BdeCfgMoveWinRE` | 56 (0x38) | Exported Function | 0x0000000180005580 | 0x00005580
`BdeCfgMigrateBootHive` | 55 (0x37) | Exported Function | 0x0000000180008030 | 0x00008030
`BdeCfgLogWarning` | 114 (0x72) | Exported Function | 0x000000018000d360 | 0x0000d360
`BdeCfgLogInit` | 113 (0x71) | Exported Function | 0x000000018000e2f0 | 0x0000e2f0
`BdeCfgLogFoundUnallocatedExtent` | 112 (0x70) | Exported Function | 0x000000018000da90 | 0x0000da90
`BdeCfgLogFailedTarget` | 111 (0x6f) | Exported Function | 0x000000018000d540 | 0x0000d540
`BdeCfgLogError` | 110 (0x6e) | Exported Function | 0x000000018000d130 | 0x0000d130
`BdeCfgLogEnumExtent` | 109 (0x6d) | Exported Function | 0x000000018000e2c0 | 0x0000e2c0
`BdeCfgLogDetectedWinRE` | 108 (0x6c) | Exported Function | 0x000000018000e0c0 | 0x0000e0c0
`BdeCfgLogCommandLineParams` | 107 (0x6b) | Exported Function | 0x000000018000dad0 | 0x0000dad0
`BdeCfgLogClose` | 106 (0x6a) | Exported Function | 0x000000018000e330 | 0x0000e330
`BdeCfgLogCandidateDrive` | 105 (0x69) | Exported Function | 0x000000018000d790 | 0x0000d790
`BdeCfgLoadResourceString` | 54 (0x36) | Exported Function | 0x0000000180008c40 | 0x00008c40
`BdeCfgIsWinREOnOSVolume` | 52 (0x34) | Exported Function | 0x0000000180005a20 | 0x00005a20
`public: void __cdecl CBdeCfgLibraryLoader::Unload(void) __ptr64` | 104 (0x68) | Exported Function | 0x000000018000cf80 | 0x0000cf80


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


