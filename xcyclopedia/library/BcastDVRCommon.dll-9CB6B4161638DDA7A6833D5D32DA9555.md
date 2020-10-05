---
title: BcastDVRCommon.dll | Windows Runtime BcastDVRCommon DLL
excerpt: What is BcastDVRCommon.dll?
---

# BcastDVRCommon.dll 

* File Path: `C:\Windows\system32\BcastDVRCommon.dll`
* Description: Windows Runtime BcastDVRCommon DLL

## Hashes

Type | Hash
-- | --
MD5 | `9CB6B4161638DDA7A6833D5D32DA9555`
SHA1 | `73F37518154A407A181BA17A806ADB8F48EC9EAE`
SHA256 | `89FEC964ABB4806EF591A89E2690CD0AC616DD862B6419E9200FE90769845FC3`
SHA384 | `A1D0B6A93EBB8DAE89ECC6A264C3EA38791B62A44F0716158C1594B2F9DB8229B6F5FA2A470980DD9B16D5F56CDB094B`
SHA512 | `1DFB33ADC3BE8C1E977B64BDBAE9ECE42251BC5A4E19A87061DA91C0ECED616BC5EC8D485826C4859BA1C4C1ACF0AD8B7A67C52DF7CF5C524B6B95AA94836828`
SSDEEP | `6144:9qY/aWik4/sDshiBhX4vx/T4hOfJcQvxVPIRqWujBFs:X/V0yshiUThhwqxo`
IMP | `722AC420F955671302378677BA1497B3`
PESHA1 | `784536A6A9CA3530D66C505AE910FC65B793F808`
PE256 | `5B9898586874F8FF0AEC1969414ED69B24221D3646C3CD119C618BCCE8C958C0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: __cdecl BcastDVR_OutputDebug::BcastDVR_OutputDebug(char const * __ptr64) __ptr64` | 1 | Exported Function
`public: __cdecl Windows::Media::Capture::Internal::ImpersonateHelper::ImpersonateHelper(void) __ptr64` | 2 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::SetDefaultPlugIn(struct HKEY__ * __ptr64,struct _GUID const & __ptr64)` | 83 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetPlugInPackageFullName(struct _GUID const & __ptr64,class Windows::Internal::String * __ptr64)` | 42 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::RegisterCallingPlugIn(struct HKEY__ * __ptr64,struct HSTRING__ * __ptr64,struct HSTRING__ * __ptr64,struct _GUID const & __ptr64)` | 82 | Exported Function
`public: __cdecl Windows::Media::Capture::Internal::ImpersonateHelper::~ImpersonateHelper(void) __ptr64` | 3 | Exported Function
`public: static unsigned long __cdecl BcastDVRLogProviderBase::GetErrorHistoryCount(void)` | 25 | Exported Function
`public: static unsigned long __cdecl BcastDVRLogProviderBase::GetFormattedErrorHistory(class Windows::Internal::String * __ptr64)` | 26 | Exported Function
`public: static long __cdecl BcastDVRLogProviderBase::MostRecentErrorInHistory(void)` | 59 | Exported Function
`public: long __cdecl Windows::Media::Capture::Internal::ImpersonateHelper::ImpersonateDefaultUser(void) __ptr64` | 44 | Exported Function
`public: long __cdecl Windows::Media::Capture::Internal::ImpersonateHelper::ImpersonateUser(struct Windows::System::IUser * __ptr64) __ptr64` | 45 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegSetStringValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,char const * __ptr64,char const * __ptr64)` | 81 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegSetStringValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,class Windows::Internal::String * __ptr64)` | 80 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegSetQwordValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned __int64)` | 79 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegSetBinaryValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned char const * __ptr64,unsigned long)` | 77 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegSetDwordValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long)` | 78 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::CleanupObsoletePlugIns(struct HKEY__ * __ptr64)` | 8 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetDefaultPlugIn(struct HKEY__ * __ptr64,struct _GUID * __ptr64)` | 24 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetPlugInInfo(struct HKEY__ * __ptr64,struct _GUID const & __ptr64,class Windows::Internal::String * __ptr64,class Windows::Internal::String * __ptr64,class Windows::Internal::String * __ptr64)` | 41 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetCallersSebEventId(struct _GUID * __ptr64)` | 23 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetBroadcastSebEventIds(unsigned long * __ptr64,struct _GUID * __ptr64 * __ptr64)` | 21 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::PlugInUtility::GetCallersPlugInInfo(struct HKEY__ * __ptr64,struct _GUID const & __ptr64,class Windows::Internal::String * __ptr64,class Windows::Internal::String * __ptr64)` | 22 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,unsigned short const * __ptr64) __ptr64` | 70 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,void * __ptr64) __ptr64` | 69 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,unsigned long) __ptr64` | 67 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,unsigned char) __ptr64` | 64 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,unsigned int) __ptr64` | 66 | Exported Function
`unsigned short const * __ptr64 __cdecl Windows::Media::Capture::Internal::GameDVRUtility::MapConstantToString(unsigned short const * __ptr64 * __ptr64 const,unsigned long,unsigned long,unsigned long,unsigned long)` | 58 | Exported Function
`void __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegGetStringValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,class Windows::Internal::String * __ptr64)` | 76 | Exported Function
`void __cdecl Windows::Media::Capture::Internal::PlugInUtility::FreeBroadcastSebEventIds(struct _GUID * __ptr64 * __ptr64)` | 18 | Exported Function
`void __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegGetQwordValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned __int64,unsigned __int64 * __ptr64)` | 75 | Exported Function
`void __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetOSVersionString(class Windows::Internal::String * __ptr64)` | 40 | Exported Function
`void __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RegGetDwordValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long * __ptr64)` | 74 | Exported Function
`public: static void __cdecl BcastDVRLogProviderBase::LogErrorEx(long,char const * __ptr64,char const * __ptr64,int,char const * __ptr64,char const * __ptr64,bool)` | 57 | Exported Function
`public: static void __cdecl BcastDVRLogProviderBase::Printf(bool,bool,char const * __ptr64,char const * __ptr64,int,unsigned short const * __ptr64,...)` | 72 | Exported Function
`public: static void __cdecl BcastDVRLogProviderBase::LogError(long,char const * __ptr64,char const * __ptr64,int,bool)` | 56 | Exported Function
`public: static void __cdecl BcastDVR_OutputDebug::Initialize(unsigned short const * __ptr64,enum BcastDVR_OutputDebug_TraceToFileType,unsigned short const * __ptr64)` | 46 | Exported Function
`public: static void __cdecl BcastDVR_OutputDebug::Uninitialize(void)` | 84 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::OutputString(void) __ptr64` | 60 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,int) __ptr64` | 65 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,unsigned __int64) __ptr64` | 71 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,double) __ptr64` | 68 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintHRESULT(long) __ptr64` | 62 | Exported Function
`public: void __cdecl BcastDVR_OutputDebug::PrintType(char const * __ptr64,char const * __ptr64) __ptr64` | 63 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::EnvironmentManager::GetBroadcastPlugInRegistryPathFromSebEventIdString(unsigned short const * __ptr64,class Windows::Internal::String * __ptr64)` | 20 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::EnvironmentManager::GetKnownFolderSubFolder(struct _GUID const & __ptr64,unsigned short const * __ptr64,class Windows::Internal::String * __ptr64)` | 39 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::EnvironmentManager::GetBroadcastPlugInRegistryPathFromSebEventId(struct _GUID const & __ptr64,class Windows::Internal::String * __ptr64)` | 19 | Exported Function
`GetPreviewSharedMemoryWriter` | 88 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::EnvironmentManager::AppendPath(class Windows::Internal::String const & __ptr64,class Windows::Internal::String const & __ptr64,class Windows::Internal::String * __ptr64)` | 5 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::EnvironmentManager::GetUserGameDVRConfigFolderPath(class Windows::Internal::String * __ptr64,unsigned short const * __ptr64)` | 43 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::CloseDuplicatedHandles(unsigned long,unsigned long,void * __ptr64 * __ptr64 const)` | 10 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetGuidFromGuidString(unsigned short const * __ptr64,struct _GUID * __ptr64)` | 27 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::CloseDuplicatedHandle(unsigned long,void * __ptr64)` | 9 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::CalcPreviewVideoBufferDataSize(unsigned long,unsigned long,unsigned long * __ptr64)` | 6 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::CalcPreviewVideoFrameDataSize(unsigned long,unsigned long,unsigned long * __ptr64)` | 7 | Exported Function
`CreateMetadataManagerInstance` | 13 | Exported Function
`CreateMetadataManagerInstanceForAppId` | 14 | Exported Function
`CreateCallerManagerInstanceForAppId` | 12 | Exported Function
`ActiveMetadataManagerInstances` | 4 | Exported Function
`CreateCallerManagerInstance` | 11 | Exported Function
`CreateMetadataManagerInstanceFromJson` | 15 | Exported Function
`GetBroadcastSharedMemoryWriter` | 86 | Exported Function
`GetPreviewSharedMemoryReader` | 87 | Exported Function
`GetBroadcastSharedMemoryReader` | 85 | Exported Function
`FireCallerManagerEvent` | 16 | Exported Function
`FireCallerManagerEventForAppId` | 17 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonDouble(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,double)` | 50 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonGuid(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,struct _GUID)` | 51 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonDateTime(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,struct Windows::Foundation::DateTime)` | 49 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonArray(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,struct Windows::Foundation::Collections::IVector<struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64 * __ptr64)` | 47 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonBoolean(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char)` | 48 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonNumber(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,__int64)` | 52 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::PrintGuid(struct _GUID,class Windows::Internal::String * __ptr64)` | 61 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::RecreateStorageFile(struct Windows::Storage::IStorageFile * __ptr64,struct Windows::Storage::IStorageFile * __ptr64 * __ptr64)` | 73 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertNamedJsonEnumBitfields(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned __int64,unsigned short const * __ptr64 const * __ptr64,int)` | 55 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonObject(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonObject * __ptr64 * __ptr64)` | 53 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::InsertJsonString(struct Windows::Data::Json::IJsonValueStatics * __ptr64,struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,struct HSTRING__ * __ptr64)` | 54 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetIUserSID(struct Windows::System::IUser * __ptr64,class Windows::Internal::String * __ptr64)` | 31 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonArray(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,struct Windows::Foundation::Collections::IVector<struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64 * __ptr64)` | 32 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetHKeyCurrentUserForIUser(struct Windows::System::IUser * __ptr64,struct HKEY__ * __ptr64 * __ptr64)` | 30 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetGuidStringFromGuid(struct _GUID const & __ptr64,bool,class Windows::Internal::String * __ptr64)` | 28 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetHKeyCurrentUserForDefaultUser(struct HKEY__ * __ptr64 * __ptr64)` | 29 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonBoolean(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64)` | 33 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonNumber(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,__int64 * __ptr64)` | 37 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonString(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,class Windows::Internal::String * __ptr64)` | 38 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonGuid(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,struct _GUID * __ptr64)` | 36 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonDateTime(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,struct Windows::Foundation::DateTime * __ptr64)` | 34 | Exported Function
`long __cdecl Windows::Media::Capture::Internal::GameDVRUtility::GetJsonDouble(struct Windows::Foundation::Collections::IMap<struct HSTRING__ * __ptr64,struct Windows::Data::Json::IJsonValue * __ptr64> * __ptr64,struct HSTRING__ * __ptr64,unsigned char * __ptr64,double * __ptr64)` | 35 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BcastDVRCommon.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/89fec964abb4806ef591a89e2690cd0ac616dd862b6419e9200fe90769845fc3/detection/





MIT License. Copyright (c) 2020 Strontic.


