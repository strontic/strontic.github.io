---
title: vdsutil.dll | Virtual Disk Service Utility Library
excerpt: What is vdsutil.dll?
---

# vdsutil.dll 

* File Path: `C:\Windows\system32\vdsutil.dll`
* Description: Virtual Disk Service Utility Library

## Hashes

Type | Hash
-- | --
MD5 | `76AF404E20F4B396D82001220727F4FE`
SHA1 | `65276AA51D544C0F51F681ACC46D5DC0EAFCAA44`
SHA256 | `25B7B84CA889E78F6DBDDFE02EF7B4F0D680C24C28EEB7C78FF83185FDFA1F35`
SHA384 | `F0BEDECB7104035C0C68F08C6E6F2D24C39C456A20A09EF58D72FACE1C0A95A31FAB4B84D0F0CE295375DC4533B322F3`
SHA512 | `73ECB47CCC0EF64B598B6D7B8E52AABEEFAEEB5211FDC3DCFFBB3961EBCDBD0BFA23A10AC4C4DB0DFFA64B6151B4F2A7871662C16103F310F3C0677D4294FCA8`
SSDEEP | `3072:2S2bv9tuzyKcCsmV8E808V5liwi3fvpVfh6zGvLrDoHABu:kvuzbcCsmV8E808Vhi3Xh9oHAB`
IMP | `1D0AB1D5907706F9CE265CB98B5F26DF`
PESHA1 | `FF9D36E19AC8C07D347EFE852BAB35F0F7E6E4ED`
PE256 | `ACC518F2876397C3149DF88A1A252BC17A9C2D83618EEFE1B9F65AF3551134F6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual long __cdecl CPrvEnumObject::Skip(unsigned long) __ptr64` | 91 | Exported Function
`public: virtual long __cdecl CPrvEnumObject::Reset(void) __ptr64` | 84 | Exported Function
`public: virtual long __cdecl CPrvEnumObject::Next(unsigned long,struct IUnknown * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 69 | Exported Function
`public: virtual long __cdecl CVdsAsyncObjectBase::Cancel(void) __ptr64` | 39 | Exported Function
`public: void * __ptr64 __cdecl CVdsHandleImpl<-1>::operator=(void * __ptr64) __ptr64` | 26 | Exported Function
`public: void * __ptr64 __cdecl CRtlListIter::GetEntryPointer(void) __ptr64` | 51 | Exported Function
`public: virtual long __cdecl CVdsAsyncObjectBase::QueryStatus(long * __ptr64,unsigned long * __ptr64) __ptr64` | 76 | Exported Function
`public: unsigned long __cdecl CVdsPnPNotificationBase::Initialize(void) __ptr64` | 57 | Exported Function
`public: struct HWND__ * __ptr64 __cdecl CVdsPnPNotificationBase::GetWindowHandle(void) __ptr64` | 54 | Exported Function
`public: static void __cdecl CVdsAsyncObjectBase::Uninitialize(void)` | 92 | Exported Function
`public: unsigned long __cdecl CVdsPnPNotificationBase::Register(struct _NotificationListeningRequest * __ptr64,unsigned long) __ptr64` | 77 | Exported Function
`public: virtual long __cdecl CPrvEnumObject::Clone(struct IEnumVdsObject * __ptr64 * __ptr64) __ptr64` | 41 | Exported Function
`public: virtual __cdecl CRtlMap::~CRtlMap(void) __ptr64` | 18 | Exported Function
`public: unsigned long __cdecl CVdsPnPNotificationBase::RegisterHandle(void * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 78 | Exported Function
`public: void __cdecl CPrvEnumObject::Clear(void) __ptr64` | 40 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::SetOutput(struct _VDS_ASYNC_OUTPUT) __ptr64` | 87 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::SetCompletionStatus(long,unsigned long) __ptr64` | 86 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::DisallowCancel(void) __ptr64` | 45 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::SetOutputType(enum _VDS_ASYNC_OUTPUT_TYPE) __ptr64` | 88 | Exported Function
`public: void __cdecl CVdsPnPNotificationBase::Uninitialize(void) __ptr64` | 93 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::ZeroAsyncOut(void) __ptr64` | 99 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::Signal(void) __ptr64` | 90 | Exported Function
`public: void __cdecl CRtlList::Remove(class CRtlListIter & __ptr64) __ptr64` | 80 | Exported Function
`public: void __cdecl CRtlList::``default constructor closure'(void) __ptr64` | 30 | Exported Function
`public: void __cdecl CPrvEnumObject::SetPositionToLast(void) __ptr64` | 89 | Exported Function
`public: void __cdecl CRtlList::RemoveAll(void) __ptr64` | 82 | Exported Function
`public: void __cdecl CVdsAsyncObjectBase::AllowCancel(void) __ptr64` | 34 | Exported Function
`public: void __cdecl CRtlMap::RemoveAll(int) __ptr64` | 83 | Exported Function
`public: void __cdecl CRtlMap::``default constructor closure'(void) __ptr64` | 31 | Exported Function
`public: static unsigned long __cdecl CVdsAsyncObjectBase::Initialize(void)` | 56 | Exported Function
`public: int __cdecl CRtlList::InsertTail(class CRtlEntry & __ptr64) __ptr64` | 63 | Exported Function
`public: int __cdecl CRtlList::InsertPointer(class CRtlListIter & __ptr64,void * __ptr64) __ptr64` | 62 | Exported Function
`public: int __cdecl CRtlList::InsertHeadPointer(void * __ptr64) __ptr64` | 61 | Exported Function
`public: int __cdecl CRtlList::InsertTailPointer(void * __ptr64) __ptr64` | 64 | Exported Function
`public: int __cdecl CRtlMap::FindPtr(class CRtlEntry & __ptr64,class CRtlEntry * __ptr64 * __ptr64) __ptr64` | 49 | Exported Function
`public: int __cdecl CRtlMap::Find(class CRtlEntry & __ptr64,class CRtlEntry * __ptr64) __ptr64` | 48 | Exported Function
`public: int __cdecl CRtlListIter::IsDone(void) __ptr64` | 67 | Exported Function
`public: class CRtlMapIter & __ptr64 __cdecl CRtlMapIter::Next(void) __ptr64` | 71 | Exported Function
`public: class CRtlListIter __cdecl CRtlList::End(void) __ptr64` | 47 | Exported Function
`public: class CRtlListIter __cdecl CRtlList::Begin(void) __ptr64` | 37 | Exported Function
`public: class CRtlMapIter __cdecl CRtlMap::Begin(void) __ptr64` | 38 | Exported Function
`public: int __cdecl CRtlList::InsertHead(class CRtlEntry & __ptr64) __ptr64` | 60 | Exported Function
`public: int __cdecl CRtlList::Insert(class CRtlListIter & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 58 | Exported Function
`public: enum _VDS_ASYNC_OUTPUT_TYPE __cdecl CVdsAsyncObjectBase::GetOutputType(void) __ptr64` | 53 | Exported Function
`public: int __cdecl CRtlMap::Insert(class CRtlEntry & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 59 | Exported Function
`public: long __cdecl CVdsAsyncObjectBase::WaitImpl(long * __ptr64) __ptr64` | 97 | Exported Function
`public: long __cdecl CPrvEnumObject::Append(struct IUnknown * __ptr64) __ptr64` | 35 | Exported Function
`public: long __cdecl CGlobalResource::Initialize(void) __ptr64` | 55 | Exported Function
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Attach(struct tagVARIANT * __ptr64) __ptr64` | 36 | Exported Function
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Reset(void) __ptr64` | 85 | Exported Function
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Next(struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 72 | Exported Function
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Detach(void) __ptr64` | 44 | Exported Function
`public: int __cdecl CRtlSharedLock::CurrentThreadIsWriter(void) __ptr64` | 43 | Exported Function
`public: int __cdecl CRtlMap::Remove(class CRtlEntry & __ptr64) __ptr64` | 81 | Exported Function
`public: int __cdecl CRtlMap::InsertUnique(class CRtlEntry & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 65 | Exported Function
`public: int __cdecl CVdsAsyncObjectBase::IsCancelRequested(void) __ptr64` | 66 | Exported Function
`public: int __cdecl CVdsTraceSettings::m_NoDebuggerLogging(void) __ptr64` | 101 | Exported Function
`public: int __cdecl CVdsTraceSettings::m_ExtraLogging(void) __ptr64` | 100 | Exported Function
`public: int __cdecl CVdsAsyncObjectBase::IsFinished(void) __ptr64` | 68 | Exported Function
`public: void __cdecl CVdsPnPNotificationBase::Unregister(struct _NotificationListeningRequest * __ptr64) __ptr64` | 94 | Exported Function
`VdsWmiCopyToVariantByteArray` | 219 | Exported Function
`VdsWmiCopyFromVariantByteArray` | 218 | Exported Function
`VdsWmiConnectToNamespace` | 217 | Exported Function
`VdsWmiCreateClassInstance` | 220 | Exported Function
`VdsWmiGetBoolFromInstance` | 223 | Exported Function
`VdsWmiFindInstanceOfClass` | 222 | Exported Function
`VdsWmiCreateVariantArray` | 221 | Exported Function
`VdsTraceExHelper` | 212 | Exported Function
`VdsTraceEx` | 211 | Exported Function
`VdsTrace` | 210 | Exported Function
`VdsTraceExW` | 213 | Exported Function
`VdsWmiCallMethod` | 216 | Exported Function
`VdsTraceW` | 215 | Exported Function
`VdsTraceExWHelper` | 214 | Exported Function
`VdsWmiGetByteFromInstance` | 224 | Exported Function
`VdsWmiSetStringInInstance` | 234 | Exported Function
`VdsWmiSetObjectInInstance` | 233 | Exported Function
`VdsWmiSetByteInInstance` | 232 | Exported Function
`VdsWmiSetUlongInInstance` | 235 | Exported Function
`WriteBootCode` | 238 | Exported Function
`WaitForRundownProtectionRelease` | 237 | Exported Function
`VdsWmiSetUlonglongInInstance` | 236 | Exported Function
`VdsWmiGetObjectFromInstance` | 227 | Exported Function
`VdsWmiGetMethodArgumentObject` | 226 | Exported Function
`VdsWmiGetByteInVariantByteArray` | 225 | Exported Function
`VdsWmiGetObjectInVariantObjectArray` | 228 | Exported Function
`VdsWmiSetBoolInInstance` | 231 | Exported Function
`VdsWmiGetUlonglongFromInstance` | 230 | Exported Function
`VdsWmiGetUlongFromInstance` | 229 | Exported Function
`VdsIscsiSetIpAddressInInstance` | 209 | Exported Function
`SetDiskLayout` | 189 | Exported Function
`RundownCompleted` | 188 | Exported Function
`RemoveTempVolumeName` | 187 | Exported Function
`StartReferenceHistory` | 190 | Exported Function
`UnregisterProvider` | 193 | Exported Function
`UnInitializeGlobalResouce` | 192 | Exported Function
`StopReferenceHistory` | 191 | Exported Function
`QueryVolPersistentState` | 182 | Exported Function
`QueryObjects` | 181 | Exported Function
`public: void __cdecl CVdsPnPNotificationBase::UnregisterHandle(void * __ptr64) __ptr64` | 95 | Exported Function
`RegisterProvider` | 184 | Exported Function
`RemoveEventSource` | 186 | Exported Function
`ReleaseRundownProtection` | 185 | Exported Function
`ReInitializeRundownProtection` | 183 | Exported Function
`VdsAllocateEmptyString` | 194 | Exported Function
`VdsIscsiGetIpAddressFromInstance` | 204 | Exported Function
`VdsIscsiCheckEqualIpAddress` | 203 | Exported Function
`VdsIscsiCacheSessionDevices` | 202 | Exported Function
`VdsIscsiIpAddressToIpsecId` | 205 | Exported Function
`VdsIscsiIsIscsiLun` | 208 | Exported Function
`VdsIscsiIpsecIdToIpAddress` | 207 | Exported Function
`VdsIscsiIpAddressToString` | 206 | Exported Function
`VdsDisableCOMFatalExceptionHandling` | 197 | Exported Function
`VdsAssert` | 196 | Exported Function
`VdsAllocateString` | 195 | Exported Function
`VdsDoesDiskHaveArcPath` | 198 | Exported Function
`VdsInitializeCriticalSection` | 201 | Exported Function
`VdsHeapFree` | 200 | Exported Function
`VdsHeapAlloc` | 199 | Exported Function
`GetMediaGeometry` | 141 | Exported Function
`GetIsRemovable` | 140 | Exported Function
`GetInterfaceDetailData` | 139 | Exported Function
`GetMediaGeometryEx` | 142 | Exported Function
`GetStorageAccessAlignmentProperty` | 145 | Exported Function
`GetRegistryValue` | 144 | Exported Function
`GetPartitionInformation` | 143 | Exported Function
`GetFMIFSEnableCompressionRoutine` | 133 | Exported Function
`GetFileSystemRecognitionName` | 138 | Exported Function
`GetDiskRedundancyCount` | 132 | Exported Function
`GetFMIFSFormatEx2Routine` | 134 | Exported Function
`GetFMIFSQueryDeviceInfoByHandle` | 137 | Exported Function
`GetFMIFSQueryDeviceInfo` | 136 | Exported Function
`GetFMIFSGetDefaultFilesystemRoutine` | 135 | Exported Function
`GetSystemVolumeHandle` | 146 | Exported Function
`InvalidateDiskCache` | 156 | Exported Function
`InitializeSecurityDescriptorHelper` | 155 | Exported Function
`InitializeRundownProtection` | 154 | Exported Function
`IoctlMountmgrQueryPointsDevicePath` | 157 | Exported Function
`IsDiskClustered` | 160 | Exported Function
`IsDeviceFullyInstalled` | 159 | Exported Function
`IsClientSKU` | 158 | Exported Function
`GetVolumeName` | 149 | Exported Function
`GetVolumeGuidPathnames` | 148 | Exported Function
`GetVolumeDiskExtentInfo` | 147 | Exported Function
`GetVolumePath` | 150 | Exported Function
`GuidToString` | 153 | Exported Function
`GetVolumeUniqueId` | 152 | Exported Function
`GetVolumeSize` | 151 | Exported Function
`GetDiskOfflineReason` | 131 | Exported Function
`DeleteNetworkShare` | 111 | Exported Function
`DeleteBcdObjects` | 110 | Exported Function
`CreateDeviceInfoSet` | 109 | Exported Function
`DllMain` | 112 | Exported Function
`GetBootFromDiskNumber` | 115 | Exported Function
`GetBootDiskNumber` | 114 | Exported Function
`GarbageCollectDriveLetters` | 113 | Exported Function
`AllocateAndGetVolumePathName` | 104 | Exported Function
`AddEventSource` | 103 | Exported Function
`AcquireRundownProtection` | 102 | Exported Function
`AssignTempVolumeName` | 105 | Exported Function
`CoFreeStringArray` | 108 | Exported Function
`BootBackedByWim` | 107 | Exported Function
`BacksBootVolume` | 106 | Exported Function
`GetBootVolumeHandle` | 116 | Exported Function
`GetDeviceRegistryPropertyByInfo` | 126 | Exported Function
`GetDeviceNumber` | 125 | Exported Function
`GetDeviceName` | 124 | Exported Function
`GetDeviceRegistryPropertyByInst` | 127 | Exported Function
`GetDiskLayout` | 130 | Exported Function
`GetDiskIdentifiers` | 129 | Exported Function
`GetDiskFlags` | 128 | Exported Function
`GetDeviceId` | 119 | Exported Function
`GetDeviceAndMediaType` | 118 | Exported Function
`GetDefaultAlignment` | 117 | Exported Function
`GetDeviceLocation` | 120 | Exported Function
`GetDeviceManufacturerInfo` | 123 | Exported Function
`GetDeviceLocationPath` | 122 | Exported Function
`GetDeviceLocationEx` | 121 | Exported Function
`IsDiskCurrentStateReadOnly` | 161 | Exported Function
`public: __cdecl CVdsCallTracer::CVdsCallTracer(unsigned long,char const * __ptr64) __ptr64` | 8 | Exported Function
`public: __cdecl CVdsAsyncObjectBase::~CVdsAsyncObjectBase(void) __ptr64` | 20 | Exported Function
`public: __cdecl CVdsAsyncObjectBase::CVdsAsyncObjectBase(void) __ptr64` | 7 | Exported Function
`public: __cdecl CVdsCallTracer::~CVdsCallTracer(void) __ptr64` | 21 | Exported Function
`public: __cdecl CVdsHandleImpl<-1>::CVdsHandleImpl<-1>(void) __ptr64` | 1 | Exported Function
`public: __cdecl CVdsCriticalSection::~CVdsCriticalSection(void) __ptr64` | 22 | Exported Function
`public: __cdecl CVdsCriticalSection::CVdsCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 9 | Exported Function
`public: __cdecl CRtlList::CRtlList(void (__cdecl*)(class CRtlEntry * __ptr64)) __ptr64` | 4 | Exported Function
`public: __cdecl CPrvEnumObject::~CPrvEnumObject(void) __ptr64` | 16 | Exported Function
`public: __cdecl CPrvEnumObject::CPrvEnumObject(void) __ptr64` | 3 | Exported Function
`public: __cdecl CRtlList::~CRtlList(void) __ptr64` | 17 | Exported Function
`public: __cdecl CRtlSharedLock::~CRtlSharedLock(void) __ptr64` | 19 | Exported Function
`public: __cdecl CRtlSharedLock::CRtlSharedLock(void) __ptr64` | 6 | Exported Function
`public: __cdecl CRtlMap::CRtlMap(unsigned long,void (__cdecl*)(class CRtlEntry * __ptr64),void (__cdecl*)(class CRtlEntry * __ptr64)) __ptr64` | 5 | Exported Function
`public: __cdecl CVdsHandleImpl<-1>::operator void * __ptr64(void) __ptr64` | 29 | Exported Function
`public: class CRtlEntry * __ptr64 __cdecl CRtlListIter::GetEntry(void) __ptr64` | 50 | Exported Function
`public: bool __cdecl CVdsHandleImpl<-1>::operator==(void * __ptr64)const __ptr64` | 28 | Exported Function
`public: __cdecl CVdsWmiVariantObjectArrayEnum::~CVdsWmiVariantObjectArrayEnum(void) __ptr64` | 25 | Exported Function
`public: class CRtlList & __ptr64 __cdecl CRtlList::operator=(class CRtlList & __ptr64) __ptr64` | 27 | Exported Function
`public: class CRtlListIter & __ptr64 __cdecl CRtlListIter::Prev(void) __ptr64` | 75 | Exported Function
`public: class CRtlListIter & __ptr64 __cdecl CRtlListIter::Next(void) __ptr64` | 70 | Exported Function
`public: class CRtlListEntry * __ptr64 __cdecl CRtlListIter::GetNode(void) __ptr64` | 52 | Exported Function
`public: __cdecl CVdsPnPNotificationBase::~CVdsPnPNotificationBase(void) __ptr64` | 23 | Exported Function
`public: __cdecl CVdsPnPNotificationBase::CVdsPnPNotificationBase(void) __ptr64` | 10 | Exported Function
`public: __cdecl CVdsHandleImpl<-1>::~CVdsHandleImpl<-1>(void) __ptr64` | 14 | Exported Function
`public: __cdecl CVdsTraceSettings::CVdsTraceSettings(void) __ptr64` | 11 | Exported Function
`public: __cdecl CVdsWmiVariantObjectArrayEnum::CVdsWmiVariantObjectArrayEnum(void) __ptr64` | 13 | Exported Function
`public: __cdecl CVdsUnlockIt::~CVdsUnlockIt(void) __ptr64` | 24 | Exported Function
`public: __cdecl CVdsUnlockIt::CVdsUnlockIt(long & __ptr64) __ptr64` | 12 | Exported Function
`public: __cdecl CGlobalResource::~CGlobalResource(void) __ptr64` | 15 | Exported Function
`IsWinPE` | 171 | Exported Function
`IsVdsLoggingEnabled` | 170 | Exported Function
`IsRunningOnAMD64` | 169 | Exported Function
`LockDismountVolume` | 172 | Exported Function
`LogEvent` | 175 | Exported Function
`LogError` | 174 | Exported Function
`LockVolume` | 173 | Exported Function
`IsEfiFirmware` | 164 | Exported Function
`IsDriveLetter` | 163 | Exported Function
`IsDiskReadOnly` | 162 | Exported Function
`IsLocalComputer` | 165 | Exported Function
`IsRamDrive` | 168 | Exported Function
`IsNoAutoMount` | 167 | Exported Function
`IsMediaPresent` | 166 | Exported Function
`LogInfo` | 176 | Exported Function
`private: void __cdecl CRtlSharedLock::AcquireWrite(void) __ptr64` | 33 | Exported Function
`private: void __cdecl CRtlSharedLock::AcquireRead(void) __ptr64` | 32 | Exported Function
`private: unsigned long __cdecl CVdsPnPNotificationBase::NotificationThread(void * __ptr64) __ptr64` | 73 | Exported Function
`private: void __cdecl CRtlSharedLock::Downgrade(void) __ptr64` | 46 | Exported Function
`public: __cdecl CGlobalResource::CGlobalResource(void) __ptr64` | 2 | Exported Function
`private: void __cdecl CRtlSharedLock::Upgrade(void) __ptr64` | 96 | Exported Function
`private: void __cdecl CRtlSharedLock::Release(void) __ptr64` | 79 | Exported Function
`MountVolume` | 179 | Exported Function
`MirrorBcdObjects` | 178 | Exported Function
`LogWarning` | 177 | Exported Function
`OpenDevice` | 180 | Exported Function
`private: unsigned long __cdecl CVdsPnPNotificationBase::CreateListenThread(void) __ptr64` | 42 | Exported Function
`private: static unsigned long __cdecl CVdsPnPNotificationBase::NotificationThreadEntry(void * __ptr64)` | 74 | Exported Function
`private: static __int64 __cdecl CVdsPnPNotificationBase::WindowProcEntry(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 98 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vdsutil.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/25b7b84ca889e78f6dbddfe02ef7b4f0d680c24c28eeb7c78ff83185fdfa1f35/detection/





MIT License. Copyright (c) 2020 Strontic.


