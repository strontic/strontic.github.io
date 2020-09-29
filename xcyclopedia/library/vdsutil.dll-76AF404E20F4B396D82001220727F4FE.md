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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcquireRundownProtection` | 102 (0x66) | Exported Function | 0x0000000180001520 | 0x00001520
`public: unsigned long __cdecl CVdsPnPNotificationBase::Initialize(void) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180009330 | 0x00009330
`public: unsigned long __cdecl CVdsPnPNotificationBase::Register(struct _NotificationListeningRequest * __ptr64,unsigned long) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180009780 | 0x00009780
`public: unsigned long __cdecl CVdsPnPNotificationBase::RegisterHandle(void * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x00000001800099c0 | 0x000099c0
`public: virtual __cdecl CRtlMap::~CRtlMap(void) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180010c00 | 0x00010c00
`public: virtual long __cdecl CPrvEnumObject::Clone(struct IEnumVdsObject * __ptr64 * __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x00000001800023d0 | 0x000023d0
`public: virtual long __cdecl CPrvEnumObject::Next(unsigned long,struct IUnknown * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x00000001800021d0 | 0x000021d0
`public: virtual long __cdecl CPrvEnumObject::Reset(void) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180002370 | 0x00002370
`public: virtual long __cdecl CPrvEnumObject::Skip(unsigned long) __ptr64` | 91 (0x5b) | Exported Function | 0x00000001800022d0 | 0x000022d0
`public: virtual long __cdecl CVdsAsyncObjectBase::Cancel(void) __ptr64` | 39 (0x27) | Exported Function | 0x00000001800029c0 | 0x000029c0
`public: virtual long __cdecl CVdsAsyncObjectBase::QueryStatus(long * __ptr64,unsigned long * __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180002ae0 | 0x00002ae0
`public: void * __ptr64 __cdecl CRtlListIter::GetEntryPointer(void) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180011270 | 0x00011270
`public: void * __ptr64 __cdecl CVdsHandleImpl<-1>::operator=(void * __ptr64) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018000da90 | 0x0000da90
`public: void __cdecl CPrvEnumObject::Clear(void) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180002110 | 0x00002110
`public: void __cdecl CPrvEnumObject::SetPositionToLast(void) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180001370 | 0x00001370
`public: void __cdecl CRtlList::``default constructor closure'(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180001070 | 0x00001070
`public: void __cdecl CRtlList::Remove(class CRtlListIter & __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180011510 | 0x00011510
`public: void __cdecl CRtlList::RemoveAll(void) __ptr64` | 82 (0x52) | Exported Function | 0x00000001800115b0 | 0x000115b0
`public: void __cdecl CRtlMap::``default constructor closure'(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180001050 | 0x00001050
`public: void __cdecl CRtlMap::RemoveAll(int) __ptr64` | 83 (0x53) | Exported Function | 0x0000000180010f60 | 0x00010f60
`public: void __cdecl CVdsAsyncObjectBase::AllowCancel(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180001400 | 0x00001400
`public: void __cdecl CVdsAsyncObjectBase::DisallowCancel(void) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180001410 | 0x00001410
`public: void __cdecl CVdsAsyncObjectBase::SetCompletionStatus(long,unsigned long) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180002920 | 0x00002920
`public: void __cdecl CVdsAsyncObjectBase::SetOutput(struct _VDS_ASYNC_OUTPUT) __ptr64` | 87 (0x57) | Exported Function | 0x00000001800013c0 | 0x000013c0
`public: void __cdecl CVdsAsyncObjectBase::SetOutputType(enum _VDS_ASYNC_OUTPUT_TYPE) __ptr64` | 88 (0x58) | Exported Function | 0x00000001800013b0 | 0x000013b0
`public: void __cdecl CVdsAsyncObjectBase::Signal(void) __ptr64` | 90 (0x5a) | Exported Function | 0x00000001800027e0 | 0x000027e0
`public: struct HWND__ * __ptr64 __cdecl CVdsPnPNotificationBase::GetWindowHandle(void) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180009b20 | 0x00009b20
`public: static void __cdecl CVdsAsyncObjectBase::Uninitialize(void)` | 92 (0x5c) | Exported Function | 0x0000000180002760 | 0x00002760
`public: static unsigned long __cdecl CVdsAsyncObjectBase::Initialize(void)` | 56 (0x38) | Exported Function | 0x0000000180002670 | 0x00002670
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Reset(void) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180010a40 | 0x00010a40
`public: class CRtlMapIter & __ptr64 __cdecl CRtlMapIter::Next(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180010b50 | 0x00010b50
`public: class CRtlMapIter __cdecl CRtlMap::Begin(void) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180010c40 | 0x00010c40
`public: enum _VDS_ASYNC_OUTPUT_TYPE __cdecl CVdsAsyncObjectBase::GetOutputType(void) __ptr64` | 53 (0x35) | Exported Function | 0x00000001800013e0 | 0x000013e0
`public: int __cdecl CRtlList::Insert(class CRtlListIter & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x00000001800113d0 | 0x000113d0
`public: int __cdecl CRtlList::InsertHead(class CRtlEntry & __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x00000001800113b0 | 0x000113b0
`public: int __cdecl CRtlList::InsertHeadPointer(void * __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180011430 | 0x00011430
`public: int __cdecl CRtlList::InsertPointer(class CRtlListIter & __ptr64,void * __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180011470 | 0x00011470
`public: int __cdecl CRtlList::InsertTail(class CRtlEntry & __ptr64) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180011410 | 0x00011410
`public: int __cdecl CRtlList::InsertTailPointer(void * __ptr64) __ptr64` | 64 (0x40) | Exported Function | 0x00000001800114d0 | 0x000114d0
`public: int __cdecl CRtlListIter::IsDone(void) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800112e0 | 0x000112e0
`public: int __cdecl CRtlMap::Find(class CRtlEntry & __ptr64,class CRtlEntry * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180010de0 | 0x00010de0
`public: int __cdecl CRtlMap::FindPtr(class CRtlEntry & __ptr64,class CRtlEntry * __ptr64 * __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180010e70 | 0x00010e70
`public: void __cdecl CVdsAsyncObjectBase::ZeroAsyncOut(void) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180001420 | 0x00001420
`public: int __cdecl CRtlMap::Insert(class CRtlEntry & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180010c80 | 0x00010c80
`public: int __cdecl CRtlMap::Remove(class CRtlEntry & __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x0000000180010ef0 | 0x00010ef0
`public: int __cdecl CRtlSharedLock::CurrentThreadIsWriter(void) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180001190 | 0x00001190
`public: int __cdecl CVdsAsyncObjectBase::IsCancelRequested(void) __ptr64` | 66 (0x42) | Exported Function | 0x00000001800013f0 | 0x000013f0
`public: int __cdecl CVdsAsyncObjectBase::IsFinished(void) __ptr64` | 68 (0x44) | Exported Function | 0x0000000180002870 | 0x00002870
`public: int __cdecl CVdsTraceSettings::m_ExtraLogging(void) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180001040 | 0x00001040
`public: int __cdecl CVdsTraceSettings::m_NoDebuggerLogging(void) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180001030 | 0x00001030
`public: long __cdecl CGlobalResource::Initialize(void) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180011b80 | 0x00011b80
`public: long __cdecl CPrvEnumObject::Append(struct IUnknown * __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x00000001800020a0 | 0x000020a0
`public: long __cdecl CVdsAsyncObjectBase::WaitImpl(long * __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180002a10 | 0x00002a10
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Attach(struct tagVARIANT * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x00000001800108a0 | 0x000108a0
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Detach(void) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180010880 | 0x00010880
`public: long __cdecl CVdsWmiVariantObjectArrayEnum::Next(struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180010960 | 0x00010960
`public: int __cdecl CRtlMap::InsertUnique(class CRtlEntry & __ptr64,class CRtlEntry & __ptr64) __ptr64` | 65 (0x41) | Exported Function | 0x0000000180010d40 | 0x00010d40
`public: void __cdecl CVdsPnPNotificationBase::Uninitialize(void) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180009440 | 0x00009440
`public: void __cdecl CVdsPnPNotificationBase::Unregister(struct _NotificationListeningRequest * __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180009890 | 0x00009890
`public: void __cdecl CVdsPnPNotificationBase::UnregisterHandle(void * __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180009aa0 | 0x00009aa0
`VdsTraceEx` | 211 (0xd3) | Exported Function | 0x0000000180001940 | 0x00001940
`VdsTraceExHelper` | 212 (0xd4) | Exported Function | 0x0000000180001970 | 0x00001970
`VdsTraceExW` | 213 (0xd5) | Exported Function | 0x0000000180001b30 | 0x00001b30
`VdsTraceExWHelper` | 214 (0xd6) | Exported Function | 0x0000000180001b60 | 0x00001b60
`VdsTraceW` | 215 (0xd7) | Exported Function | 0x0000000180001af0 | 0x00001af0
`VdsWmiCallMethod` | 216 (0xd8) | Exported Function | 0x0000000180010040 | 0x00010040
`VdsWmiConnectToNamespace` | 217 (0xd9) | Exported Function | 0x000000018000f3d0 | 0x0000f3d0
`VdsWmiCopyFromVariantByteArray` | 218 (0xda) | Exported Function | 0x000000018000fdb0 | 0x0000fdb0
`VdsWmiCopyToVariantByteArray` | 219 (0xdb) | Exported Function | 0x0000000180010740 | 0x00010740
`VdsWmiCreateClassInstance` | 220 (0xdc) | Exported Function | 0x0000000180010180 | 0x00010180
`VdsWmiCreateVariantArray` | 221 (0xdd) | Exported Function | 0x00000001800106c0 | 0x000106c0
`VdsWmiFindInstanceOfClass` | 222 (0xde) | Exported Function | 0x000000018000fbb0 | 0x0000fbb0
`VdsTrace` | 210 (0xd2) | Exported Function | 0x0000000180001900 | 0x00001900
`VdsWmiGetBoolFromInstance` | 223 (0xdf) | Exported Function | 0x000000018000f700 | 0x0000f700
`VdsWmiGetByteInVariantByteArray` | 225 (0xe1) | Exported Function | 0x000000018000fa50 | 0x0000fa50
`VdsWmiGetMethodArgumentObject` | 226 (0xe2) | Exported Function | 0x000000018000ff40 | 0x0000ff40
`VdsWmiGetObjectFromInstance` | 227 (0xe3) | Exported Function | 0x000000018000f7d0 | 0x0000f7d0
`VdsWmiGetObjectInVariantObjectArray` | 228 (0xe4) | Exported Function | 0x000000018000f8a0 | 0x0000f8a0
`VdsWmiGetUlongFromInstance` | 229 (0xe5) | Exported Function | 0x000000018000f5a0 | 0x0000f5a0
`VdsWmiGetUlonglongFromInstance` | 230 (0xe6) | Exported Function | 0x000000018000f4d0 | 0x0000f4d0
`VdsWmiSetBoolInInstance` | 231 (0xe7) | Exported Function | 0x0000000180010460 | 0x00010460
`VdsWmiSetByteInInstance` | 232 (0xe8) | Exported Function | 0x00000001800103c0 | 0x000103c0
`VdsWmiSetObjectInInstance` | 233 (0xe9) | Exported Function | 0x00000001800105f0 | 0x000105f0
`VdsWmiSetStringInInstance` | 234 (0xea) | Exported Function | 0x0000000180010520 | 0x00010520
`VdsWmiSetUlongInInstance` | 235 (0xeb) | Exported Function | 0x0000000180010320 | 0x00010320
`VdsWmiSetUlonglongInInstance` | 236 (0xec) | Exported Function | 0x0000000180010220 | 0x00010220
`VdsWmiGetByteFromInstance` | 224 (0xe0) | Exported Function | 0x000000018000f650 | 0x0000f650
`public: class CRtlListIter __cdecl CRtlList::End(void) __ptr64` | 47 (0x2f) | Exported Function | 0x0000000180011390 | 0x00011390
`VdsIscsiSetIpAddressInInstance` | 209 (0xd1) | Exported Function | 0x000000018000e5a0 | 0x0000e5a0
`VdsIscsiIpsecIdToIpAddress` | 207 (0xcf) | Exported Function | 0x000000018000e120 | 0x0000e120
`QueryObjects` | 181 (0xb5) | Exported Function | 0x0000000180009260 | 0x00009260
`QueryVolPersistentState` | 182 (0xb6) | Exported Function | 0x000000018000d970 | 0x0000d970
`RegisterProvider` | 184 (0xb8) | Exported Function | 0x00000001800035d0 | 0x000035d0
`ReInitializeRundownProtection` | 183 (0xb7) | Exported Function | 0x0000000180001500 | 0x00001500
`ReleaseRundownProtection` | 185 (0xb9) | Exported Function | 0x0000000180001550 | 0x00001550
`RemoveEventSource` | 186 (0xba) | Exported Function | 0x0000000180003b40 | 0x00003b40
`RemoveTempVolumeName` | 187 (0xbb) | Exported Function | 0x0000000180007df0 | 0x00007df0
`RundownCompleted` | 188 (0xbc) | Exported Function | 0x0000000180001510 | 0x00001510
`SetDiskLayout` | 189 (0xbd) | Exported Function | 0x0000000180005550 | 0x00005550
`StartReferenceHistory` | 190 (0xbe) | Exported Function | 0x00000001800014d0 | 0x000014d0
`StopReferenceHistory` | 191 (0xbf) | Exported Function | 0x00000001800014e0 | 0x000014e0
`UnInitializeGlobalResouce` | 192 (0xc0) | Exported Function | 0x0000000180011c00 | 0x00011c00
`VdsIscsiIsIscsiLun` | 208 (0xd0) | Exported Function | 0x000000018000f070 | 0x0000f070
`UnregisterProvider` | 193 (0xc1) | Exported Function | 0x00000001800037b0 | 0x000037b0
`VdsAllocateString` | 195 (0xc3) | Exported Function | 0x0000000180001f80 | 0x00001f80
`VdsAssert` | 196 (0xc4) | Exported Function | 0x0000000180001740 | 0x00001740
`VdsDisableCOMFatalExceptionHandling` | 197 (0xc5) | Exported Function | 0x000000018000c770 | 0x0000c770
`VdsDoesDiskHaveArcPath` | 198 (0xc6) | Exported Function | 0x000000018000c340 | 0x0000c340
`VdsHeapAlloc` | 199 (0xc7) | Exported Function | 0x0000000180001ea0 | 0x00001ea0
`VdsHeapFree` | 200 (0xc8) | Exported Function | 0x0000000180001ec0 | 0x00001ec0
`VdsInitializeCriticalSection` | 201 (0xc9) | Exported Function | 0x0000000180001e50 | 0x00001e50
`VdsIscsiCacheSessionDevices` | 202 (0xca) | Exported Function | 0x000000018000eb70 | 0x0000eb70
`VdsIscsiCheckEqualIpAddress` | 203 (0xcb) | Exported Function | 0x000000018000e890 | 0x0000e890
`VdsIscsiGetIpAddressFromInstance` | 204 (0xcc) | Exported Function | 0x000000018000e260 | 0x0000e260
`VdsIscsiIpAddressToIpsecId` | 205 (0xcd) | Exported Function | 0x000000018000df20 | 0x0000df20
`VdsIscsiIpAddressToString` | 206 (0xce) | Exported Function | 0x000000018000dd00 | 0x0000dd00
`VdsAllocateEmptyString` | 194 (0xc2) | Exported Function | 0x0000000180001ef0 | 0x00001ef0
`public: class CRtlListIter __cdecl CRtlList::Begin(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180011340 | 0x00011340
`public: class CRtlListIter & __ptr64 __cdecl CRtlListIter::Prev(void) __ptr64` | 75 (0x4b) | Exported Function | 0x00000001800112c0 | 0x000112c0
`public: class CRtlListIter & __ptr64 __cdecl CRtlListIter::Next(void) __ptr64` | 70 (0x46) | Exported Function | 0x00000001800112a0 | 0x000112a0
`GetFileSystemRecognitionName` | 138 (0x8a) | Exported Function | 0x000000018000d490 | 0x0000d490
`GetFMIFSEnableCompressionRoutine` | 133 (0x85) | Exported Function | 0x0000000180011c90 | 0x00011c90
`GetFMIFSFormatEx2Routine` | 134 (0x86) | Exported Function | 0x0000000180011c70 | 0x00011c70
`GetFMIFSGetDefaultFilesystemRoutine` | 135 (0x87) | Exported Function | 0x0000000180011cb0 | 0x00011cb0
`GetFMIFSQueryDeviceInfo` | 136 (0x88) | Exported Function | 0x0000000180011cf0 | 0x00011cf0
`GetFMIFSQueryDeviceInfoByHandle` | 137 (0x89) | Exported Function | 0x0000000180011cd0 | 0x00011cd0
`GetInterfaceDetailData` | 139 (0x8b) | Exported Function | 0x00000001800050b0 | 0x000050b0
`GetIsRemovable` | 140 (0x8c) | Exported Function | 0x0000000180005620 | 0x00005620
`GetMediaGeometry` | 141 (0x8d) | Exported Function | 0x0000000180005be0 | 0x00005be0
`GetMediaGeometryEx` | 142 (0x8e) | Exported Function | 0x0000000180005cb0 | 0x00005cb0
`GetPartitionInformation` | 143 (0x8f) | Exported Function | 0x00000001800077d0 | 0x000077d0
`GetRegistryValue` | 144 (0x90) | Exported Function | 0x000000018000a080 | 0x0000a080
`GetDiskRedundancyCount` | 132 (0x84) | Exported Function | 0x000000018000d6d0 | 0x0000d6d0
`GetStorageAccessAlignmentProperty` | 145 (0x91) | Exported Function | 0x0000000180006c80 | 0x00006c80
`GetVolumeDiskExtentInfo` | 147 (0x93) | Exported Function | 0x00000001800053e0 | 0x000053e0
`GetVolumeGuidPathnames` | 148 (0x94) | Exported Function | 0x000000018000cf40 | 0x0000cf40
`GetVolumeName` | 149 (0x95) | Exported Function | 0x0000000180007880 | 0x00007880
`GetVolumePath` | 150 (0x96) | Exported Function | 0x000000018000ca20 | 0x0000ca20
`GetVolumeSize` | 151 (0x97) | Exported Function | 0x00000001800046c0 | 0x000046c0
`GetVolumeUniqueId` | 152 (0x98) | Exported Function | 0x000000018000c810 | 0x0000c810
`GuidToString` | 153 (0x99) | Exported Function | 0x0000000180009160 | 0x00009160
`InitializeRundownProtection` | 154 (0x9a) | Exported Function | 0x00000001800014f0 | 0x000014f0
`InitializeSecurityDescriptorHelper` | 155 (0x9b) | Exported Function | 0x0000000180004330 | 0x00004330
`InvalidateDiskCache` | 156 (0x9c) | Exported Function | 0x000000018000d3b0 | 0x0000d3b0
`IoctlMountmgrQueryPointsDevicePath` | 157 (0x9d) | Exported Function | 0x000000018000cba0 | 0x0000cba0
`IsClientSKU` | 158 (0x9e) | Exported Function | 0x000000018000d800 | 0x0000d800
`GetSystemVolumeHandle` | 146 (0x92) | Exported Function | 0x000000018000a4b0 | 0x0000a4b0
`IsDeviceFullyInstalled` | 159 (0x9f) | Exported Function | 0x0000000180007540 | 0x00007540
`GetDiskOfflineReason` | 131 (0x83) | Exported Function | 0x0000000180008720 | 0x00008720
`GetDiskIdentifiers` | 129 (0x81) | Exported Function | 0x0000000180002f80 | 0x00002f80
`AddEventSource` | 103 (0x67) | Exported Function | 0x0000000180003900 | 0x00003900
`AllocateAndGetVolumePathName` | 104 (0x68) | Exported Function | 0x0000000180007b30 | 0x00007b30
`AssignTempVolumeName` | 105 (0x69) | Exported Function | 0x0000000180007cb0 | 0x00007cb0
`BacksBootVolume` | 106 (0x6a) | Exported Function | 0x000000018000d8d0 | 0x0000d8d0
`BootBackedByWim` | 107 (0x6b) | Exported Function | 0x000000018000d920 | 0x0000d920
`CoFreeStringArray` | 108 (0x6c) | Exported Function | 0x0000000180008e00 | 0x00008e00
`CreateDeviceInfoSet` | 109 (0x6d) | Exported Function | 0x0000000180007640 | 0x00007640
`DeleteBcdObjects` | 110 (0x6e) | Exported Function | 0x000000018000b890 | 0x0000b890
`DeleteNetworkShare` | 111 (0x6f) | Exported Function | 0x0000000180007f60 | 0x00007f60
`DllMain` | 112 (0x70) | Exported Function | 0x0000000180003410 | 0x00003410
`GarbageCollectDriveLetters` | 113 (0x71) | Exported Function | 0x0000000180008100 | 0x00008100
`GetBootDiskNumber` | 114 (0x72) | Exported Function | 0x000000018000a980 | 0x0000a980
`GetDiskLayout` | 130 (0x82) | Exported Function | 0x0000000180005240 | 0x00005240
`GetBootFromDiskNumber` | 115 (0x73) | Exported Function | 0x000000018000ab80 | 0x0000ab80
`GetDefaultAlignment` | 117 (0x75) | Exported Function | 0x000000018000a280 | 0x0000a280
`GetDeviceAndMediaType` | 118 (0x76) | Exported Function | 0x0000000180005790 | 0x00005790
`GetDeviceId` | 119 (0x77) | Exported Function | 0x0000000180004f50 | 0x00004f50
`GetDeviceLocation` | 120 (0x78) | Exported Function | 0x0000000180006560 | 0x00006560
`GetDeviceLocationEx` | 121 (0x79) | Exported Function | 0x0000000180006890 | 0x00006890
`GetDeviceLocationPath` | 122 (0x7a) | Exported Function | 0x0000000180006280 | 0x00006280
`GetDeviceManufacturerInfo` | 123 (0x7b) | Exported Function | 0x0000000180006e80 | 0x00006e80
`GetDeviceName` | 124 (0x7c) | Exported Function | 0x0000000180004df0 | 0x00004df0
`GetDeviceNumber` | 125 (0x7d) | Exported Function | 0x0000000180004ae0 | 0x00004ae0
`GetDeviceRegistryPropertyByInfo` | 126 (0x7e) | Exported Function | 0x0000000180007180 | 0x00007180
`GetDeviceRegistryPropertyByInst` | 127 (0x7f) | Exported Function | 0x00000001800073d0 | 0x000073d0
`GetDiskFlags` | 128 (0x80) | Exported Function | 0x0000000180008580 | 0x00008580
`GetBootVolumeHandle` | 116 (0x74) | Exported Function | 0x000000018000a6f0 | 0x0000a6f0
`WaitForRundownProtectionRelease` | 237 (0xed) | Exported Function | 0x00000001800015b0 | 0x000015b0
`IsDiskClustered` | 160 (0xa0) | Exported Function | 0x00000001800082f0 | 0x000082f0
`IsDiskReadOnly` | 162 (0xa2) | Exported Function | 0x0000000180004cb0 | 0x00004cb0
`public: __cdecl CPrvEnumObject::~CPrvEnumObject(void) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180001290 | 0x00001290
`public: __cdecl CRtlList::CRtlList(void (__cdecl*)(class CRtlEntry * __ptr64)) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180011300 | 0x00011300
`public: __cdecl CRtlList::~CRtlList(void) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180011320 | 0x00011320
`public: __cdecl CRtlMap::CRtlMap(unsigned long,void (__cdecl*)(class CRtlEntry * __ptr64),void (__cdecl*)(class CRtlEntry * __ptr64)) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180010ba0 | 0x00010ba0
`public: __cdecl CRtlSharedLock::CRtlSharedLock(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001090 | 0x00001090
`public: __cdecl CRtlSharedLock::~CRtlSharedLock(void) __ptr64` | 19 (0x13) | Exported Function | 0x00000001800010d0 | 0x000010d0
`public: __cdecl CVdsAsyncObjectBase::CVdsAsyncObjectBase(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180002570 | 0x00002570
`public: __cdecl CVdsAsyncObjectBase::~CVdsAsyncObjectBase(void) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180002600 | 0x00002600
`public: __cdecl CVdsCallTracer::CVdsCallTracer(unsigned long,char const * __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001d20 | 0x00001d20
`public: __cdecl CVdsCallTracer::~CVdsCallTracer(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180001d60 | 0x00001d60
`public: __cdecl CVdsCriticalSection::CVdsCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800011c0 | 0x000011c0
`public: __cdecl CVdsCriticalSection::~CVdsCriticalSection(void) __ptr64` | 22 (0x16) | Exported Function | 0x00000001800011f0 | 0x000011f0
`public: __cdecl CPrvEnumObject::CPrvEnumObject(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001210 | 0x00001210
`public: __cdecl CVdsHandleImpl<-1>::CVdsHandleImpl<-1>(void) __ptr64` | 1 (0x1) | Exported Function | 0x000000018000daf0 | 0x0000daf0
`public: __cdecl CVdsHandleImpl<-1>::~CVdsHandleImpl<-1>(void) __ptr64` | 14 (0xe) | Exported Function | 0x000000018000da40 | 0x0000da40
`public: __cdecl CVdsPnPNotificationBase::CVdsPnPNotificationBase(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180001460 | 0x00001460
`public: __cdecl CVdsPnPNotificationBase::~CVdsPnPNotificationBase(void) __ptr64` | 23 (0x17) | Exported Function | 0x00000001800014a0 | 0x000014a0
`public: __cdecl CVdsTraceSettings::CVdsTraceSettings(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180001d80 | 0x00001d80
`public: __cdecl CVdsUnlockIt::CVdsUnlockIt(long & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180001440 | 0x00001440
`public: __cdecl CVdsUnlockIt::~CVdsUnlockIt(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180001450 | 0x00001450
`public: __cdecl CVdsWmiVariantObjectArrayEnum::CVdsWmiVariantObjectArrayEnum(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180010860 | 0x00010860
`public: __cdecl CVdsWmiVariantObjectArrayEnum::~CVdsWmiVariantObjectArrayEnum(void) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180010880 | 0x00010880
`public: bool __cdecl CVdsHandleImpl<-1>::operator==(void * __ptr64)const __ptr64` | 28 (0x1c) | Exported Function | 0x000000018000da80 | 0x0000da80
`public: class CRtlEntry * __ptr64 __cdecl CRtlListIter::GetEntry(void) __ptr64` | 50 (0x32) | Exported Function | 0x0000000180011240 | 0x00011240
`public: class CRtlList & __ptr64 __cdecl CRtlList::operator=(class CRtlList & __ptr64) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180011630 | 0x00011630
`public: class CRtlListEntry * __ptr64 __cdecl CRtlListIter::GetNode(void) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180011220 | 0x00011220
`public: __cdecl CVdsHandleImpl<-1>::operator void * __ptr64(void) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018000dae0 | 0x0000dae0
`IsDiskCurrentStateReadOnly` | 161 (0xa1) | Exported Function | 0x0000000180004ba0 | 0x00004ba0
`public: __cdecl CGlobalResource::~CGlobalResource(void) __ptr64` | 15 (0xf) | Exported Function | 0x00000001800014e0 | 0x000014e0
`private: void __cdecl CRtlSharedLock::Upgrade(void) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180001150 | 0x00001150
`IsDriveLetter` | 163 (0xa3) | Exported Function | 0x000000018000a030 | 0x0000a030
`IsEfiFirmware` | 164 (0xa4) | Exported Function | 0x0000000180008da0 | 0x00008da0
`IsLocalComputer` | 165 (0xa5) | Exported Function | 0x0000000180004070 | 0x00004070
`IsMediaPresent` | 166 (0xa6) | Exported Function | 0x0000000180005700 | 0x00005700
`IsNoAutoMount` | 167 (0xa7) | Exported Function | 0x0000000180008c80 | 0x00008c80
`IsRamDrive` | 168 (0xa8) | Exported Function | 0x0000000180004950 | 0x00004950
`IsRunningOnAMD64` | 169 (0xa9) | Exported Function | 0x000000018000d890 | 0x0000d890
`IsVdsLoggingEnabled` | 170 (0xaa) | Exported Function | 0x0000000180004050 | 0x00004050
`IsWinPE` | 171 (0xab) | Exported Function | 0x0000000180008be0 | 0x00008be0
`LockDismountVolume` | 172 (0xac) | Exported Function | 0x0000000180008f90 | 0x00008f90
`LockVolume` | 173 (0xad) | Exported Function | 0x0000000180008ea0 | 0x00008ea0
`LogError` | 174 (0xae) | Exported Function | 0x0000000180003d30 | 0x00003d30
`public: __cdecl CGlobalResource::CGlobalResource(void) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800117c0 | 0x000117c0
`LogEvent` | 175 (0xaf) | Exported Function | 0x0000000180003c20 | 0x00003c20
`LogWarning` | 177 (0xb1) | Exported Function | 0x0000000180003e40 | 0x00003e40
`MirrorBcdObjects` | 178 (0xb2) | Exported Function | 0x000000018000bce0 | 0x0000bce0
`MountVolume` | 179 (0xb3) | Exported Function | 0x0000000180009080 | 0x00009080
`OpenDevice` | 180 (0xb4) | Exported Function | 0x0000000180004790 | 0x00004790
`private: static __int64 __cdecl CVdsPnPNotificationBase::WindowProcEntry(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 98 (0x62) | Exported Function | 0x0000000180009e00 | 0x00009e00
`private: static unsigned long __cdecl CVdsPnPNotificationBase::NotificationThreadEntry(void * __ptr64)` | 74 (0x4a) | Exported Function | 0x0000000180009b30 | 0x00009b30
`private: unsigned long __cdecl CVdsPnPNotificationBase::CreateListenThread(void) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180009550 | 0x00009550
`private: unsigned long __cdecl CVdsPnPNotificationBase::NotificationThread(void * __ptr64) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180009b90 | 0x00009b90
`private: void __cdecl CRtlSharedLock::AcquireRead(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180001110 | 0x00001110
`private: void __cdecl CRtlSharedLock::AcquireWrite(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180001130 | 0x00001130
`private: void __cdecl CRtlSharedLock::Downgrade(void) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180001170 | 0x00001170
`private: void __cdecl CRtlSharedLock::Release(void) __ptr64` | 79 (0x4f) | Exported Function | 0x00000001800010f0 | 0x000010f0
`LogInfo` | 176 (0xb0) | Exported Function | 0x0000000180003f50 | 0x00003f50
`WriteBootCode` | 238 (0xee) | Exported Function | 0x00000001800088e0 | 0x000088e0


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


