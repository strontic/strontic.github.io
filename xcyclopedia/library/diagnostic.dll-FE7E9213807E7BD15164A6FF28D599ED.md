---
title: diagnostic.dll | Diagnostic Module
excerpt: What is diagnostic.dll?
---

# diagnostic.dll 

* File Path: `C:\Windows\system32\oobe\diagnostic.dll`
* Description: Diagnostic Module

## Hashes

Type | Hash
-- | --
MD5 | `FE7E9213807E7BD15164A6FF28D599ED`
SHA1 | `9224EFD559F550E432C0059B979950318DB5B6FA`
SHA256 | `EA64B80F44E4E168E05BC7ED2BE85C890E593B72598C71F34BF789A1E49C0CA5`
SHA384 | `9676B13303D18EA593C8793D477024C22E99DAFBED2C6022F417890F7C01139D7D7D41596521150DD18C3B0847AB7F5C`
SHA512 | `ECD41A8F41EEFD3F42D549C448F0B382909EE8673751D3C1FAB75C9D7508A2AEEF140A6D0146424BF30861FBBE0A4455550DF29527CDD2D39F2514D6E72CE783`
SSDEEP | `3072:qx02msdR22C2Avx2KU/Qhe12OvuGiHtz1Kssn6/1niBRxDXtl:qx0Psd0lpkK0Qhe12WuGqniBn`
IMP | `CAA60CB823BA7A924B34FF1E816B8A56`
PESHA1 | `5ACAB2581742D629F29A1545549B0290708DF242`
PE256 | `F27113367290282D40EC88A4E0A53B5DA7FB8FF72F3BBDFFB11A43F40410677F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Callback_Diagnostic_Unattend` | 64 (0x40) | Exported Function | 0x000000018000b4c0 | 0x0000b4c0
`public: int __cdecl CCountArray::GetInfo(unsigned int,unsigned long & __ptr64,unsigned long & __ptr64,unsigned long & __ptr64,unsigned long & __ptr64,unsigned short * __ptr64 & __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180014ee0 | 0x00014ee0
`public: int __cdecl CCountArray::IncrementCount(unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 119 (0x77) | Exported Function | 0x0000000180014d20 | 0x00014d20
`public: static unsigned long __cdecl CDiagConsumerAdaptorFactory::CreateInstance(class IDiagConsumer * __ptr64 * __ptr64)` | 68 (0x44) | Exported Function | 0x00000001800086a0 | 0x000086a0
`public: static unsigned long __cdecl CInstallSource::DetermineInstallImageType(struct _BLACKBOARD * __ptr64)` | 72 (0x48) | Exported Function | 0x00000001800050a0 | 0x000050a0
`public: static unsigned long __cdecl CInstallSource::DetermineInstallMedia(struct _BLACKBOARD * __ptr64)` | 73 (0x49) | Exported Function | 0x00000001800050e0 | 0x000050e0
`public: static unsigned long __cdecl CInstallSource::DetermineInstallMediaHashLabel(struct _BLACKBOARD * __ptr64)` | 74 (0x4a) | Exported Function | 0x00000001800051a0 | 0x000051a0
`public: static unsigned long __cdecl CInstallSource::DetermineInstallType(struct _BLACKBOARD * __ptr64)` | 75 (0x4b) | Exported Function | 0x0000000180005040 | 0x00005040
`public: class OldSystem & __ptr64 __cdecl OldSystem::operator=(class OldSystem const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x00000001800032a0 | 0x000032a0
`public: static unsigned long __cdecl CNewOS::GetWinImageArch(struct _BLACKBOARD * __ptr64)` | 117 (0x75) | Exported Function | 0x0000000180004810 | 0x00004810
`public: static unsigned short const * __ptr64 __cdecl CNewOS::GetLanguage(struct _BLACKBOARD * __ptr64)` | 100 (0x64) | Exported Function | 0x00000001800046d0 | 0x000046d0
`public: static void __cdecl CDiagConsumerAdaptorFactory::DeleteInstance(class IDiagConsumer * __ptr64)` | 69 (0x45) | Exported Function | 0x0000000180008870 | 0x00008870
`public: unsigned int __cdecl CCountArray::NumElements(void) __ptr64` | 144 (0x90) | Exported Function | 0x0000000180003200 | 0x00003200
`public: unsigned long __cdecl CExistingOS::GetDeviceDword(enum CExistingOS::eDeviceDword) __ptr64` | 91 (0x5b) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: unsigned long __cdecl CExistingOS::GetFailedInstallCount(void) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180004350 | 0x00004350
`public: unsigned long __cdecl CHardwareID::GetNumberOfCompatableIDs(void) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180002630 | 0x00002630
`public: unsigned long __cdecl CHardwareID::GetNumberOfHardwareIds(void) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180002620 | 0x00002620
`public: static unsigned short const * __ptr64 __cdecl CNewOS::GetEdition(struct _BLACKBOARD * __ptr64)` | 96 (0x60) | Exported Function | 0x0000000180004590 | 0x00004590
`public: class NewSystem & __ptr64 __cdecl NewSystem::operator=(class NewSystem const & __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x00000001800032a0 | 0x000032a0
`public: class MachineHardWare & __ptr64 __cdecl MachineHardWare::operator=(class MachineHardWare const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x0000000180003260 | 0x00003260
`public: class InstallData & __ptr64 __cdecl InstallData::operator=(class InstallData const & __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x00000001800032a0 | 0x000032a0
`public: __cdecl NewSystem::NewSystem(class NewSystem const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180003280 | 0x00003280
`public: __cdecl NewSystem::NewSystem(struct _BLACKBOARD * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180008e60 | 0x00008e60
`public: __cdecl NewSystem::~NewSystem(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180008ec0 | 0x00008ec0
`public: __cdecl OldSystem::OldSystem(class OldSystem const & __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x00000001800032c0 | 0x000032c0
`public: __cdecl OldSystem::OldSystem(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180009200 | 0x00009200
`public: __cdecl OldSystem::~OldSystem(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180009250 | 0x00009250
`public: class CAccessWMI & __ptr64 __cdecl CAccessWMI::operator=(class CAccessWMI const & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180001170 | 0x00001170
`public: class CCountArray & __ptr64 __cdecl CCountArray::operator=(class CCountArray const & __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180003210 | 0x00003210
`public: class CDiagConsumerAdaptorFactory & __ptr64 __cdecl CDiagConsumerAdaptorFactory::operator=(class CDiagConsumerAdaptorFactory && __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180003070 | 0x00003070
`public: class CDiagConsumerAdaptorFactory & __ptr64 __cdecl CDiagConsumerAdaptorFactory::operator=(class CDiagConsumerAdaptorFactory const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180003070 | 0x00003070
`public: class CExistingOS & __ptr64 __cdecl CExistingOS::operator=(class CExistingOS const & __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180002e80 | 0x00002e80
`public: class CHardwareID & __ptr64 __cdecl CHardwareID::operator=(class CHardwareID const & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180002660 | 0x00002660
`public: class CInstallSource & __ptr64 __cdecl CInstallSource::operator=(class CInstallSource const & __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180003010 | 0x00003010
`public: class CMoboAndProcInfo & __ptr64 __cdecl CMoboAndProcInfo::operator=(class CMoboAndProcInfo const & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x00000001800022b0 | 0x000022b0
`public: class CNewOS & __ptr64 __cdecl CNewOS::operator=(class CNewOS const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180002f90 | 0x00002f90
`public: class CSqmDiagConsumer & __ptr64 __cdecl CSqmDiagConsumer::operator=(class CSqmDiagConsumer const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180003140 | 0x00003140
`public: class IDiagConsumer & __ptr64 __cdecl IDiagConsumer::operator=(class IDiagConsumer const & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180003070 | 0x00003070
`public: unsigned long __cdecl CInstallSource::GetDeviceDword(enum CInstallSource::eDeviceDword) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180005890 | 0x00005890
`public: unsigned long __cdecl CMoboAndProcInfo::GetAvailPhysRAM(void) __ptr64` | 89 (0x59) | Exported Function | 0x00000001800021b0 | 0x000021b0
`public: unsigned long __cdecl CMoboAndProcInfo::GetNumberOfProcessors(void) __ptr64` | 105 (0x69) | Exported Function | 0x00000001800021c0 | 0x000021c0
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcAddressWidth(void) __ptr64` | 107 (0x6b) | Exported Function | 0x00000001800021d0 | 0x000021d0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::DoneReporting(unsigned short * __ptr64,unsigned long) __ptr64` | 79 (0x4f) | Exported Function | 0x00000001800077a0 | 0x000077a0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Initialize(unsigned long,struct _GUID * __ptr64) __ptr64` | 121 (0x79) | Exported Function | 0x00000001800067f0 | 0x000067f0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Set(unsigned long,unsigned long) __ptr64` | 152 (0x98) | Exported Function | 0x00000001800071c0 | 0x000071c0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Set(unsigned long,unsigned short * __ptr64) __ptr64` | 153 (0x99) | Exported Function | 0x0000000180007330 | 0x00007330
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Shutdown(void) __ptr64` | 156 (0x9c) | Exported Function | 0x00000001800085e0 | 0x000085e0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Submit(unsigned short * __ptr64,int) __ptr64` | 159 (0x9f) | Exported Function | 0x0000000180008010 | 0x00008010
`public: virtual void __cdecl InstallData::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x00000001800097e0 | 0x000097e0
`public: virtual void __cdecl InstallData::LogToFile(void) __ptr64` | 136 (0x88) | Exported Function | 0x0000000180004580 | 0x00004580
`public: virtual void __cdecl MachineHardWare::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 133 (0x85) | Exported Function | 0x0000000180008c50 | 0x00008c50
`public: virtual void __cdecl MachineHardWare::LogToFile(void) __ptr64` | 137 (0x89) | Exported Function | 0x0000000180008ac0 | 0x00008ac0
`public: virtual void __cdecl NewSystem::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 134 (0x86) | Exported Function | 0x0000000180008f70 | 0x00008f70
`public: virtual void __cdecl NewSystem::LogToFile(void) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180004580 | 0x00004580
`public: virtual void __cdecl OldSystem::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 135 (0x87) | Exported Function | 0x0000000180009310 | 0x00009310
`public: virtual void __cdecl OldSystem::LogToFile(void) __ptr64` | 139 (0x8b) | Exported Function | 0x0000000180004580 | 0x00004580
`public: void __cdecl CNewOS::GetNewOSVersionInformation(unsigned short * __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180004a20 | 0x00004a20
`RestoreIniValues` | 151 (0x97) | Exported Function | 0x000000018000bd20 | 0x0000bd20
`SetFromBlackBoard` | 154 (0x9a) | Exported Function | 0x00000001800123a0 | 0x000123a0
`public: virtual unsigned long __cdecl CSqmDiagConsumer::AddToStream(unsigned long,unsigned long,unsigned short * __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180007620 | 0x00007620
`public: __cdecl MachineHardWare::~MachineHardWare(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180008a00 | 0x00008a00
`public: virtual unsigned long __cdecl CSqmDiagConsumer::AddToStream(unsigned long,unsigned long,unsigned long) __ptr64` | 58 (0x3a) | Exported Function | 0x00000001800074a0 | 0x000074a0
`public: virtual int __cdecl NewSystem::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 124 (0x7c) | Exported Function | 0x0000000180008ef0 | 0x00008ef0
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcArchitecture(void) __ptr64` | 108 (0x6c) | Exported Function | 0x00000001800021e0 | 0x000021e0
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcessorSpeedInMHz(void) __ptr64` | 112 (0x70) | Exported Function | 0x0000000180002200 | 0x00002200
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcFamily(void) __ptr64` | 109 (0x6d) | Exported Function | 0x00000001800021f0 | 0x000021f0
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcStepping(void) __ptr64` | 110 (0x6e) | Exported Function | 0x0000000180002210 | 0x00002210
`public: unsigned long __cdecl CMoboAndProcInfo::GetTotalPhysRAM(void) __ptr64` | 116 (0x74) | Exported Function | 0x00000001800021a0 | 0x000021a0
`public: unsigned long __cdecl CNewOS::GetDeviceDword(enum CNewOS::eDeviceDword) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180004c90 | 0x00004c90
`public: unsigned long __cdecl CSqmDiagConsumer::Initialize(unsigned long,struct _GUID * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,int,unsigned long) __ptr64` | 120 (0x78) | Exported Function | 0x0000000180006cc0 | 0x00006cc0
`public: unsigned short const * __ptr64 * __ptr64 __cdecl CHardwareID::GetCompatibleIds(void) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180002650 | 0x00002650
`public: unsigned short const * __ptr64 * __ptr64 __cdecl CHardwareID::GetHardwareIds(void) __ptr64` | 98 (0x62) | Exported Function | 0x0000000180002640 | 0x00002640
`public: unsigned short const * __ptr64 __cdecl CExistingOS::GetDeviceString(enum CExistingOS::eDeviceString) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180004260 | 0x00004260
`public: unsigned short const * __ptr64 __cdecl CNewOS::GetDeviceString(enum CNewOS::eDeviceString) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180004c50 | 0x00004c50
`public: virtual __cdecl CMoboAndProcInfo::~CMoboAndProcInfo(void) __ptr64` | 27 (0x1b) | Exported Function | 0x00000001800024b0 | 0x000024b0
`public: virtual __cdecl CSqmDiagConsumer::~CSqmDiagConsumer(void) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800067b0 | 0x000067b0
`public: virtual __cdecl IDiagConsumer::~IDiagConsumer(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180003030 | 0x00003030
`public: virtual int __cdecl CSqmDiagConsumer::IsSubmitSuccessful(unsigned short * __ptr64) __ptr64` | 127 (0x7f) | Exported Function | 0x0000000180008440 | 0x00008440
`public: virtual int __cdecl InstallData::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 122 (0x7a) | Exported Function | 0x0000000180009760 | 0x00009760
`public: virtual int __cdecl MachineHardWare::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180008a40 | 0x00008a40
`public: virtual int __cdecl OldSystem::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 125 (0x7d) | Exported Function | 0x0000000180009290 | 0x00009290
`public: __cdecl MachineHardWare::MachineHardWare(void) __ptr64` | 17 (0x11) | Exported Function | 0x00000001800089b0 | 0x000089b0
`public: __cdecl MachineHardWare::MachineHardWare(class MachineHardWare const & __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180003230 | 0x00003230
`public: __cdecl InstallData::~InstallData(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180009730 | 0x00009730
`Module_Init_Diagnostic` | 142 (0x8e) | Exported Function | 0x000000018000ac30 | 0x0000ac30
`ObtainBucketingParamsFromBlackBoard` | 145 (0x91) | Exported Function | 0x00000001800115d0 | 0x000115d0
`ObtainBucketingParamsFromLogFile` | 146 (0x92) | Exported Function | 0x0000000180010700 | 0x00010700
`ObtainFilesToAttach` | 147 (0x93) | Exported Function | 0x0000000180011c60 | 0x00011c60
`private: bool __cdecl CNewOS::FindFilePathInAppDir(unsigned short * __ptr64,unsigned int,unsigned short const * __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x0000000180004d10 | 0x00004d10
`private: int __cdecl CCountArray::NewElement(unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x0000000180014b00 | 0x00014b00
`private: int __cdecl CInstallSource::IsInternal(void) __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180005410 | 0x00005410
`private: static int __cdecl CSqmDiagConsumer::InLHPlus(void)` | 118 (0x76) | Exported Function | 0x0000000180006150 | 0x00006150
`private: static int __cdecl CSqmDiagConsumer::SqmUploadCallBack(long,unsigned short const * __ptr64,unsigned long)` | 157 (0x9d) | Exported Function | 0x0000000180006460 | 0x00006460
`private: static int const CExistingOS::MAX_CHAR_SIZE` | 140 (0x8c) | Exported Function | 0x000000018001d370 | 0x0001d370
`private: static int const CNewOS::MAX_CHAR_SIZE` | 141 (0x8d) | Exported Function | 0x000000018001d370 | 0x0001d370
`private: static unsigned long __cdecl CSqmDiagConsumer::ProcessFailedUpload(unsigned short * __ptr64)` | 149 (0x95) | Exported Function | 0x00000001800061c0 | 0x000061c0
`private: static unsigned short * CNewOS::m_szEdition` | 165 (0xa5) | Exported Function | 0x0000000180029990 | 0x00029990
`private: static unsigned short * CNewOS::m_szLanguage` | 166 (0xa6) | Exported Function | 0x0000000180029890 | 0x00029890
`private: unsigned long __cdecl CExistingOS::GetSkuInfo(unsigned long * __ptr64) __ptr64` | 114 (0x72) | Exported Function | 0x0000000180003f00 | 0x00003f00
`private: void __cdecl CAccessWMI::LogFetchInfoError(unsigned short const * __ptr64,unsigned int) __ptr64` | 131 (0x83) | Exported Function | 0x0000000180001380 | 0x00001380
`private: void __cdecl CExistingOS::DetectBranch(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180003c00 | 0x00003c00
`g_Wdscore` | 164 (0xa4) | Exported Function | 0x0000000180029168 | 0x00029168
`private: void __cdecl CExistingOS::GetOEMInformation(void) __ptr64` | 106 (0x6a) | Exported Function | 0x00000001800039b0 | 0x000039b0
`g_Sqm` | 163 (0xa3) | Exported Function | 0x0000000180029028 | 0x00029028
`g_Kernel32` | 161 (0xa1) | Exported Function | 0x0000000180029030 | 0x00029030
`CallBack_DiagnosticDataGeneration` | 60 (0x3c) | Exported Function | 0x000000018000d040 | 0x0000d040
`CallBack_DiagnosticDataSend` | 61 (0x3d) | Exported Function | 0x000000018000dd60 | 0x0000dd60
`CallBack_EditionID` | 62 (0x3e) | Exported Function | 0x000000018000c240 | 0x0000c240
`CallBack_RestartSetup` | 63 (0x3f) | Exported Function | 0x000000018000b980 | 0x0000b980
`CollectAndSendDiagDataToSQM` | 65 (0x41) | Exported Function | 0x000000018000f3e0 | 0x0000f3e0
`CollectAndSendDiagDataToWatson` | 66 (0x42) | Exported Function | 0x000000018000fe80 | 0x0000fe80
`const CAccessWMI::``vftable'` | 50 (0x32) | Exported Function | 0x000000018001b138 | 0x0001b138
`const CMoboAndProcInfo::``vftable'` | 51 (0x33) | Exported Function | 0x000000018001b140 | 0x0001b140
`const CSqmDiagConsumer::``vftable'` | 52 (0x34) | Exported Function | 0x000000018001b290 | 0x0001b290
`const IDiagConsumer::``vftable'` | 53 (0x35) | Exported Function | 0x000000018001b2e0 | 0x0001b2e0
`const InstallData::``vftable'` | 54 (0x36) | Exported Function | 0x000000018001b230 | 0x0001b230
`const MachineHardWare::``vftable'` | 55 (0x37) | Exported Function | 0x000000018001b278 | 0x0001b278
`const NewSystem::``vftable'` | 56 (0x38) | Exported Function | 0x000000018001b260 | 0x0001b260
`const OldSystem::``vftable'` | 57 (0x39) | Exported Function | 0x000000018001b248 | 0x0001b248
`DiagnosticDataSendWorker` | 76 (0x4c) | Exported Function | 0x000000018000e600 | 0x0000e600
`DoWatsonReporting` | 78 (0x4e) | Exported Function | 0x0000000180011ef0 | 0x00011ef0
`g_DiagERApi` | 160 (0xa0) | Exported Function | 0x0000000180029170 | 0x00029170
`g_Shell32` | 162 (0xa2) | Exported Function | 0x0000000180029160 | 0x00029160
`SetFromFile` | 155 (0x9b) | Exported Function | 0x00000001800134d0 | 0x000134d0
`private: void __cdecl CExistingOS::GetSystemVersionDetails(void) __ptr64` | 115 (0x73) | Exported Function | 0x0000000180003820 | 0x00003820
`private: void __cdecl CHardwareID::EnumDevices(void) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180002920 | 0x00002920
`public: __cdecl CCountArray::~CCountArray(void) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180014a50 | 0x00014a50
`public: __cdecl CExistingOS::CExistingOS(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180003620 | 0x00003620
`public: __cdecl CExistingOS::~CExistingOS(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180003790 | 0x00003790
`public: __cdecl CHardwareID::CHardwareID(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180002690 | 0x00002690
`public: __cdecl CHardwareID::~CHardwareID(void) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180002830 | 0x00002830
`public: __cdecl CInstallSource::CInstallSource(struct _BLACKBOARD * __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180004ed0 | 0x00004ed0
`public: __cdecl CInstallSource::~CInstallSource(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180004580 | 0x00004580
`public: __cdecl CMoboAndProcInfo::CMoboAndProcInfo(class CMoboAndProcInfo const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180002220 | 0x00002220
`public: __cdecl CMoboAndProcInfo::CMoboAndProcInfo(void) __ptr64` | 8 (0x8) | Exported Function | 0x00000001800023a0 | 0x000023a0
`public: __cdecl CNewOS::CNewOS(struct _BLACKBOARD * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180004480 | 0x00004480
`public: __cdecl CNewOS::~CNewOS(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180004580 | 0x00004580
`public: __cdecl CSqmDiagConsumer::CSqmDiagConsumer(class CSqmDiagConsumer const & __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180003100 | 0x00003100
`public: __cdecl CSqmDiagConsumer::CSqmDiagConsumer(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180006780 | 0x00006780
`public: __cdecl IDiagConsumer::IDiagConsumer(class IDiagConsumer const & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180003050 | 0x00003050
`public: __cdecl IDiagConsumer::IDiagConsumer(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180003050 | 0x00003050
`public: __cdecl InstallData::InstallData(class InstallData const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x00000001800032e0 | 0x000032e0
`public: __cdecl InstallData::InstallData(struct _BLACKBOARD * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x00000001800096d0 | 0x000096d0
`public: __cdecl CCountArray::CCountArray(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180014a10 | 0x00014a10
`private: void __cdecl CHardwareID::DestroyArray(class ATL::CAtlArray<unsigned short const * __ptr64,class ATL::CElementTraits<unsigned short const * __ptr64> > * __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180002890 | 0x00002890
`public: __cdecl CAccessWMI::CAccessWMI(class CAccessWMI const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001120 | 0x00001120
`protected: void __cdecl CAccessWMI::LogErrorMessage(unsigned short const * __ptr64,unsigned long,enum tagLOG_SETUPLOG_SEVERITY) __ptr64` | 128 (0x80) | Exported Function | 0x00000001800012a0 | 0x000012a0
`private: void __cdecl CHardwareID::GetProperties(unsigned long,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,class ATL::CAtlArray<unsigned short const * __ptr64,class ATL::CElementTraits<unsigned short const * __ptr64> > * __ptr64) __ptr64` | 113 (0x71) | Exported Function | 0x0000000180002a50 | 0x00002a50
`private: void __cdecl CHardwareID::LogErrorMessage(unsigned short const * __ptr64,unsigned long) __ptr64` | 129 (0x81) | Exported Function | 0x0000000180002bf0 | 0x00002bf0
`private: void __cdecl CHardwareID::LogErrorMessageGLE(unsigned short const * __ptr64,unsigned long) __ptr64` | 130 (0x82) | Exported Function | 0x0000000180002cb0 | 0x00002cb0
`private: void __cdecl CMoboAndProcInfo::GetProcessorInfo(void) __ptr64` | 111 (0x6f) | Exported Function | 0x00000001800024e0 | 0x000024e0
`private: void __cdecl CNewOS::FillWithBranchDetails(unsigned short * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180004b00 | 0x00004b00
`private: void __cdecl CNewOS::FillWithBuildDate(unsigned short * __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180004a70 | 0x00004a70
`private: void __cdecl CNewOS::FillWithVersionAndBuildProperties(unsigned short * __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x0000000180004b90 | 0x00004b90
`private: void __cdecl CNewOS::GetNewOSDetails(void) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180004840 | 0x00004840
`ProcessDiagnosticDetails` | 148 (0x94) | Exported Function | 0x000000018000f250 | 0x0000f250
`protected: __cdecl CAccessWMI::CAccessWMI(unsigned short const * __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001240 | 0x00001240
`protected: bool __cdecl CAccessWMI::ConnectWMI(void) __ptr64` | 67 (0x43) | Exported Function | 0x0000000180001430 | 0x00001430
`protected: bool __cdecl CAccessWMI::ExecQuery(void) __ptr64` | 81 (0x51) | Exported Function | 0x00000001800016f0 | 0x000016f0
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,__int64 & __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x0000000180001a60 | 0x00001a60
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180001920 | 0x00001920
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned __int64) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180001b40 | 0x00001b40
`protected: virtual __cdecl CAccessWMI::~CAccessWMI(void) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001270 | 0x00001270
`protected: void __cdecl CAccessWMI::DisconnectWMI(void) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180001680 | 0x00001680
`protected: void __cdecl CAccessWMI::ResetWmiClassName(unsigned short const * __ptr64) __ptr64` | 150 (0x96) | Exported Function | 0x0000000180001110 | 0x00001110
`StartNetworking` | 158 (0x9e) | Exported Function | 0x0000000180013cf0 | 0x00013cf0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DIAGNOSTIC.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.450 (WinBuild.160101.0800)
* Product Version: 10.0.19041.450
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/ea64b80f44e4e168e05bc7ed2be85c890e593b72598c71f34bf789a1e49c0ca5/detection/


## Possible Misuse

*The following table contains possible examples of `diagnostic.dll` being misused. While `diagnostic.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `title: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cl_invocation.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Cl_invocation.yml) | `Description: Import the PowerShell Diagnostic CL_Invocation script and call SyncInvoke to launch an executable.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [CL_mutexverifiers.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/CL_mutexverifiers.yml) | `Description: Import the PowerShell Diagnostic CL_Mutexverifiers script and call runAfterCancelProcess to launch an executable.` | 



MIT License. Copyright (c) 2020 Strontic.


