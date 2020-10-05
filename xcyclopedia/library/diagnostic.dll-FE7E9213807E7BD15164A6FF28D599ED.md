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

Function Name | Ordinal | Type
-- | -- | --
`public: static unsigned long __cdecl CInstallSource::DetermineInstallMedia(struct _BLACKBOARD * __ptr64)` | 73 | Exported Function
`public: static unsigned long __cdecl CInstallSource::DetermineInstallImageType(struct _BLACKBOARD * __ptr64)` | 72 | Exported Function
`public: static unsigned long __cdecl CInstallSource::DetermineInstallMediaHashLabel(struct _BLACKBOARD * __ptr64)` | 74 | Exported Function
`public: static unsigned long __cdecl CNewOS::GetWinImageArch(struct _BLACKBOARD * __ptr64)` | 117 | Exported Function
`public: static unsigned long __cdecl CInstallSource::DetermineInstallType(struct _BLACKBOARD * __ptr64)` | 75 | Exported Function
`public: class OldSystem & __ptr64 __cdecl OldSystem::operator=(class OldSystem const & __ptr64) __ptr64` | 49 | Exported Function
`public: class NewSystem & __ptr64 __cdecl NewSystem::operator=(class NewSystem const & __ptr64) __ptr64` | 48 | Exported Function
`public: int __cdecl CCountArray::GetInfo(unsigned int,unsigned long & __ptr64,unsigned long & __ptr64,unsigned long & __ptr64,unsigned long & __ptr64,unsigned short * __ptr64 & __ptr64) __ptr64` | 99 | Exported Function
`public: static unsigned long __cdecl CDiagConsumerAdaptorFactory::CreateInstance(class IDiagConsumer * __ptr64 * __ptr64)` | 68 | Exported Function
`public: int __cdecl CCountArray::IncrementCount(unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 119 | Exported Function
`public: unsigned long __cdecl CHardwareID::GetNumberOfCompatableIDs(void) __ptr64` | 103 | Exported Function
`public: unsigned long __cdecl CExistingOS::GetFailedInstallCount(void) __ptr64` | 97 | Exported Function
`public: unsigned long __cdecl CHardwareID::GetNumberOfHardwareIds(void) __ptr64` | 104 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetAvailPhysRAM(void) __ptr64` | 89 | Exported Function
`public: unsigned long __cdecl CInstallSource::GetDeviceDword(enum CInstallSource::eDeviceDword) __ptr64` | 92 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl CNewOS::GetLanguage(struct _BLACKBOARD * __ptr64)` | 100 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl CNewOS::GetEdition(struct _BLACKBOARD * __ptr64)` | 96 | Exported Function
`public: static void __cdecl CDiagConsumerAdaptorFactory::DeleteInstance(class IDiagConsumer * __ptr64)` | 69 | Exported Function
`public: unsigned long __cdecl CExistingOS::GetDeviceDword(enum CExistingOS::eDeviceDword) __ptr64` | 91 | Exported Function
`public: unsigned int __cdecl CCountArray::NumElements(void) __ptr64` | 144 | Exported Function
`public: class MachineHardWare & __ptr64 __cdecl MachineHardWare::operator=(class MachineHardWare const & __ptr64) __ptr64` | 47 | Exported Function
`public: __cdecl OldSystem::OldSystem(void) __ptr64` | 21 | Exported Function
`public: __cdecl OldSystem::OldSystem(class OldSystem const & __ptr64) __ptr64` | 20 | Exported Function
`public: __cdecl OldSystem::~OldSystem(void) __ptr64` | 34 | Exported Function
`public: class CCountArray & __ptr64 __cdecl CCountArray::operator=(class CCountArray const & __ptr64) __ptr64` | 36 | Exported Function
`public: class CAccessWMI & __ptr64 __cdecl CAccessWMI::operator=(class CAccessWMI const & __ptr64) __ptr64` | 35 | Exported Function
`public: __cdecl MachineHardWare::~MachineHardWare(void) __ptr64` | 32 | Exported Function
`public: __cdecl MachineHardWare::MachineHardWare(void) __ptr64` | 17 | Exported Function
`public: __cdecl NewSystem::NewSystem(class NewSystem const & __ptr64) __ptr64` | 18 | Exported Function
`public: __cdecl NewSystem::~NewSystem(void) __ptr64` | 33 | Exported Function
`public: __cdecl NewSystem::NewSystem(struct _BLACKBOARD * __ptr64) __ptr64` | 19 | Exported Function
`public: class CNewOS & __ptr64 __cdecl CNewOS::operator=(class CNewOS const & __ptr64) __ptr64` | 43 | Exported Function
`public: class CMoboAndProcInfo & __ptr64 __cdecl CMoboAndProcInfo::operator=(class CMoboAndProcInfo const & __ptr64) __ptr64` | 42 | Exported Function
`public: class CSqmDiagConsumer & __ptr64 __cdecl CSqmDiagConsumer::operator=(class CSqmDiagConsumer const & __ptr64) __ptr64` | 44 | Exported Function
`public: class InstallData & __ptr64 __cdecl InstallData::operator=(class InstallData const & __ptr64) __ptr64` | 46 | Exported Function
`public: class IDiagConsumer & __ptr64 __cdecl IDiagConsumer::operator=(class IDiagConsumer const & __ptr64) __ptr64` | 45 | Exported Function
`public: class CDiagConsumerAdaptorFactory & __ptr64 __cdecl CDiagConsumerAdaptorFactory::operator=(class CDiagConsumerAdaptorFactory const & __ptr64) __ptr64` | 38 | Exported Function
`public: class CDiagConsumerAdaptorFactory & __ptr64 __cdecl CDiagConsumerAdaptorFactory::operator=(class CDiagConsumerAdaptorFactory && __ptr64) __ptr64` | 37 | Exported Function
`public: class CExistingOS & __ptr64 __cdecl CExistingOS::operator=(class CExistingOS const & __ptr64) __ptr64` | 39 | Exported Function
`public: class CInstallSource & __ptr64 __cdecl CInstallSource::operator=(class CInstallSource const & __ptr64) __ptr64` | 41 | Exported Function
`public: class CHardwareID & __ptr64 __cdecl CHardwareID::operator=(class CHardwareID const & __ptr64) __ptr64` | 40 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetNumberOfProcessors(void) __ptr64` | 105 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Submit(unsigned short * __ptr64,int) __ptr64` | 159 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Shutdown(void) __ptr64` | 156 | Exported Function
`public: virtual void __cdecl InstallData::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 132 | Exported Function
`public: virtual void __cdecl MachineHardWare::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 133 | Exported Function
`public: virtual void __cdecl InstallData::LogToFile(void) __ptr64` | 136 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::DoneReporting(unsigned short * __ptr64,unsigned long) __ptr64` | 79 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::AddToStream(unsigned long,unsigned long,unsigned short * __ptr64) __ptr64` | 59 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Initialize(unsigned long,struct _GUID * __ptr64) __ptr64` | 121 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Set(unsigned long,unsigned short * __ptr64) __ptr64` | 153 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::Set(unsigned long,unsigned long) __ptr64` | 152 | Exported Function
`RestoreIniValues` | 151 | Exported Function
`public: void __cdecl CNewOS::GetNewOSVersionInformation(unsigned short * __ptr64) __ptr64` | 102 | Exported Function
`SetFromBlackBoard` | 154 | Exported Function
`StartNetworking` | 158 | Exported Function
`SetFromFile` | 155 | Exported Function
`public: virtual void __cdecl NewSystem::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 134 | Exported Function
`public: virtual void __cdecl MachineHardWare::LogToFile(void) __ptr64` | 137 | Exported Function
`public: virtual void __cdecl NewSystem::LogToFile(void) __ptr64` | 138 | Exported Function
`public: virtual void __cdecl OldSystem::LogToFile(void) __ptr64` | 139 | Exported Function
`public: virtual void __cdecl OldSystem::LogToBB(struct _BLACKBOARD * __ptr64) __ptr64` | 135 | Exported Function
`public: virtual unsigned long __cdecl CSqmDiagConsumer::AddToStream(unsigned long,unsigned long,unsigned long) __ptr64` | 58 | Exported Function
`public: unsigned long __cdecl CNewOS::GetDeviceDword(enum CNewOS::eDeviceDword) __ptr64` | 93 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetTotalPhysRAM(void) __ptr64` | 116 | Exported Function
`public: unsigned long __cdecl CSqmDiagConsumer::Initialize(unsigned long,struct _GUID * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,int,unsigned long) __ptr64` | 120 | Exported Function
`public: unsigned short const * __ptr64 * __ptr64 __cdecl CHardwareID::GetHardwareIds(void) __ptr64` | 98 | Exported Function
`public: unsigned short const * __ptr64 * __ptr64 __cdecl CHardwareID::GetCompatibleIds(void) __ptr64` | 90 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcArchitecture(void) __ptr64` | 108 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcAddressWidth(void) __ptr64` | 107 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcessorSpeedInMHz(void) __ptr64` | 112 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcStepping(void) __ptr64` | 110 | Exported Function
`public: unsigned long __cdecl CMoboAndProcInfo::GetProcFamily(void) __ptr64` | 109 | Exported Function
`public: virtual int __cdecl InstallData::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 122 | Exported Function
`public: virtual int __cdecl CSqmDiagConsumer::IsSubmitSuccessful(unsigned short * __ptr64) __ptr64` | 127 | Exported Function
`public: virtual int __cdecl MachineHardWare::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 123 | Exported Function
`public: virtual int __cdecl OldSystem::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 125 | Exported Function
`public: virtual int __cdecl NewSystem::IsAlreadyProcessed(struct _BLACKBOARD * __ptr64) __ptr64` | 124 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CNewOS::GetDeviceString(enum CNewOS::eDeviceString) __ptr64` | 95 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CExistingOS::GetDeviceString(enum CExistingOS::eDeviceString) __ptr64` | 94 | Exported Function
`public: virtual __cdecl CMoboAndProcInfo::~CMoboAndProcInfo(void) __ptr64` | 27 | Exported Function
`public: virtual __cdecl IDiagConsumer::~IDiagConsumer(void) __ptr64` | 30 | Exported Function
`public: virtual __cdecl CSqmDiagConsumer::~CSqmDiagConsumer(void) __ptr64` | 29 | Exported Function
`private: int __cdecl CCountArray::NewElement(unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 143 | Exported Function
`private: bool __cdecl CNewOS::FindFilePathInAppDir(unsigned short * __ptr64,unsigned int,unsigned short const * __ptr64) __ptr64` | 88 | Exported Function
`private: int __cdecl CInstallSource::IsInternal(void) __ptr64` | 126 | Exported Function
`private: static int __cdecl CSqmDiagConsumer::SqmUploadCallBack(long,unsigned short const * __ptr64,unsigned long)` | 157 | Exported Function
`private: static int __cdecl CSqmDiagConsumer::InLHPlus(void)` | 118 | Exported Function
`Module_Init_Diagnostic` | 142 | Exported Function
`g_Wdscore` | 164 | Exported Function
`ObtainBucketingParamsFromBlackBoard` | 145 | Exported Function
`ObtainFilesToAttach` | 147 | Exported Function
`ObtainBucketingParamsFromLogFile` | 146 | Exported Function
`private: void __cdecl CAccessWMI::LogFetchInfoError(unsigned short const * __ptr64,unsigned int) __ptr64` | 131 | Exported Function
`private: unsigned long __cdecl CExistingOS::GetSkuInfo(unsigned long * __ptr64) __ptr64` | 114 | Exported Function
`private: void __cdecl CExistingOS::DetectBranch(void) __ptr64` | 71 | Exported Function
`private: void __cdecl CExistingOS::GetSystemVersionDetails(void) __ptr64` | 115 | Exported Function
`private: void __cdecl CExistingOS::GetOEMInformation(void) __ptr64` | 106 | Exported Function
`private: static int const CNewOS::MAX_CHAR_SIZE` | 141 | Exported Function
`private: static int const CExistingOS::MAX_CHAR_SIZE` | 140 | Exported Function
`private: static unsigned long __cdecl CSqmDiagConsumer::ProcessFailedUpload(unsigned short * __ptr64)` | 149 | Exported Function
`private: static unsigned short * CNewOS::m_szLanguage` | 166 | Exported Function
`private: static unsigned short * CNewOS::m_szEdition` | 165 | Exported Function
`g_Sqm` | 163 | Exported Function
`CollectAndSendDiagDataToWatson` | 66 | Exported Function
`CollectAndSendDiagDataToSQM` | 65 | Exported Function
`const CAccessWMI::``vftable'` | 50 | Exported Function
`const CSqmDiagConsumer::``vftable'` | 52 | Exported Function
`const CMoboAndProcInfo::``vftable'` | 51 | Exported Function
`CallBack_DiagnosticDataGeneration` | 60 | Exported Function
`Callback_Diagnostic_Unattend` | 64 | Exported Function
`CallBack_DiagnosticDataSend` | 61 | Exported Function
`CallBack_RestartSetup` | 63 | Exported Function
`CallBack_EditionID` | 62 | Exported Function
`DoWatsonReporting` | 78 | Exported Function
`DiagnosticDataSendWorker` | 76 | Exported Function
`g_DiagERApi` | 160 | Exported Function
`g_Shell32` | 162 | Exported Function
`g_Kernel32` | 161 | Exported Function
`const InstallData::``vftable'` | 54 | Exported Function
`const IDiagConsumer::``vftable'` | 53 | Exported Function
`const MachineHardWare::``vftable'` | 55 | Exported Function
`const OldSystem::``vftable'` | 57 | Exported Function
`const NewSystem::``vftable'` | 56 | Exported Function
`private: void __cdecl CHardwareID::DestroyArray(class ATL::CAtlArray<unsigned short const * __ptr64,class ATL::CElementTraits<unsigned short const * __ptr64> > * __ptr64) __ptr64` | 70 | Exported Function
`public: __cdecl CInstallSource::CInstallSource(struct _BLACKBOARD * __ptr64) __ptr64` | 6 | Exported Function
`public: __cdecl CHardwareID::~CHardwareID(void) __ptr64` | 25 | Exported Function
`public: __cdecl CInstallSource::~CInstallSource(void) __ptr64` | 26 | Exported Function
`public: __cdecl CMoboAndProcInfo::CMoboAndProcInfo(void) __ptr64` | 8 | Exported Function
`public: __cdecl CMoboAndProcInfo::CMoboAndProcInfo(class CMoboAndProcInfo const & __ptr64) __ptr64` | 7 | Exported Function
`public: __cdecl CCountArray::~CCountArray(void) __ptr64` | 23 | Exported Function
`public: __cdecl CCountArray::CCountArray(void) __ptr64` | 3 | Exported Function
`public: __cdecl CExistingOS::CExistingOS(void) __ptr64` | 4 | Exported Function
`public: __cdecl CHardwareID::CHardwareID(void) __ptr64` | 5 | Exported Function
`public: __cdecl CExistingOS::~CExistingOS(void) __ptr64` | 24 | Exported Function
`public: __cdecl InstallData::InstallData(class InstallData const & __ptr64) __ptr64` | 14 | Exported Function
`public: __cdecl IDiagConsumer::IDiagConsumer(void) __ptr64` | 13 | Exported Function
`public: __cdecl InstallData::InstallData(struct _BLACKBOARD * __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl MachineHardWare::MachineHardWare(class MachineHardWare const & __ptr64) __ptr64` | 16 | Exported Function
`public: __cdecl InstallData::~InstallData(void) __ptr64` | 31 | Exported Function
`public: __cdecl CNewOS::~CNewOS(void) __ptr64` | 28 | Exported Function
`public: __cdecl CNewOS::CNewOS(struct _BLACKBOARD * __ptr64) __ptr64` | 9 | Exported Function
`public: __cdecl CSqmDiagConsumer::CSqmDiagConsumer(class CSqmDiagConsumer const & __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl IDiagConsumer::IDiagConsumer(class IDiagConsumer const & __ptr64) __ptr64` | 12 | Exported Function
`public: __cdecl CSqmDiagConsumer::CSqmDiagConsumer(void) __ptr64` | 11 | Exported Function
`public: __cdecl CAccessWMI::CAccessWMI(class CAccessWMI const & __ptr64) __ptr64` | 2 | Exported Function
`private: void __cdecl CNewOS::FillWithBuildDate(unsigned short * __ptr64) __ptr64` | 86 | Exported Function
`private: void __cdecl CNewOS::FillWithBranchDetails(unsigned short * __ptr64) __ptr64` | 85 | Exported Function
`private: void __cdecl CNewOS::FillWithVersionAndBuildProperties(unsigned short * __ptr64) __ptr64` | 87 | Exported Function
`ProcessDiagnosticDetails` | 148 | Exported Function
`private: void __cdecl CNewOS::GetNewOSDetails(void) __ptr64` | 101 | Exported Function
`private: void __cdecl CHardwareID::GetProperties(unsigned long,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,class ATL::CAtlArray<unsigned short const * __ptr64,class ATL::CElementTraits<unsigned short const * __ptr64> > * __ptr64) __ptr64` | 113 | Exported Function
`private: void __cdecl CHardwareID::EnumDevices(void) __ptr64` | 80 | Exported Function
`private: void __cdecl CHardwareID::LogErrorMessage(unsigned short const * __ptr64,unsigned long) __ptr64` | 129 | Exported Function
`private: void __cdecl CMoboAndProcInfo::GetProcessorInfo(void) __ptr64` | 111 | Exported Function
`private: void __cdecl CHardwareID::LogErrorMessageGLE(unsigned short const * __ptr64,unsigned long) __ptr64` | 130 | Exported Function
`protected: virtual __cdecl CAccessWMI::~CAccessWMI(void) __ptr64` | 22 | Exported Function
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned __int64) __ptr64` | 84 | Exported Function
`protected: void __cdecl CAccessWMI::DisconnectWMI(void) __ptr64` | 77 | Exported Function
`protected: void __cdecl CAccessWMI::ResetWmiClassName(unsigned short const * __ptr64) __ptr64` | 150 | Exported Function
`protected: void __cdecl CAccessWMI::LogErrorMessage(unsigned short const * __ptr64,unsigned long,enum tagLOG_SETUPLOG_SEVERITY) __ptr64` | 128 | Exported Function
`protected: bool __cdecl CAccessWMI::ConnectWMI(void) __ptr64` | 67 | Exported Function
`protected: __cdecl CAccessWMI::CAccessWMI(unsigned short const * __ptr64) __ptr64` | 1 | Exported Function
`protected: bool __cdecl CAccessWMI::ExecQuery(void) __ptr64` | 81 | Exported Function
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 82 | Exported Function
`protected: bool __cdecl CAccessWMI::FetchInfo(unsigned short const * __ptr64,__int64 & __ptr64) __ptr64` | 83 | Exported Function


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


