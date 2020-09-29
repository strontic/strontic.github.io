---
title: dmdskmgr.dll | Disk Management Snap-in Support Library
excerpt: What is dmdskmgr.dll?
---

# dmdskmgr.dll 

* File Path: `C:\Windows\system32\dmdskmgr.dll`
* Description: Disk Management Snap-in Support Library

## Hashes

Type | Hash
-- | --
MD5 | `D1796F22A9A2406BE67C2F6A7141B427`
SHA1 | `8628DA05FD7C7A4FF70EF0CD8DAA8473A333BD51`
SHA256 | `4870263136D1F6A667871B605762D8A3CB3AF8AF0BEC4B72D421E634EAEBC041`
SHA384 | `EA4E3309F23D4207E108B571559A17B857428C3CA5F2DBCB6FEAD2150E3F3218E3DF2358D43BC76182319EBBAD7ADD2E`
SHA512 | `6182A21D357357D060A501B6E45C40F41FDC8B33033062C1547FA06E3948B75A41758855A4877FAD822A6AE0DCDAE0EBE7E4E86B9E0190AF9EFCA01A580BC0B4`
SSDEEP | `3072:RDLZKGD6YRSF2h0gTgRqdgHAxEKiaA+r9lqUWT+tEU0VTvLEp9rxIJfEHp:9PDBSRgt1aOA+Bllm+tExVTD+WNK`
IMP | `9DB66A3EBAC18001E9057163DDAE8063`
PESHA1 | `894DDC4B154AAA72C206F16A93ABA01C5B6C39C1`
PE256 | `9683B8529C8C17BBE213D6CB4ECA13F423492E1DE02B076E5BD4ED062432A251`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CompareDiskNames` | 228 (0xe4) | Exported Function | 0x00000001800285f0 | 0x000285f0
`public: unsigned long __cdecl CDMNodeObj::GetNumMembers(void) __ptr64` | 111 (0x6f) | Exported Function | 0x0000000180008210 | 0x00008210
`public: unsigned long __cdecl CDMNodeObj::GetNumRegions(void) __ptr64` | 112 (0x70) | Exported Function | 0x000000018001f0d0 | 0x0001f0d0
`public: unsigned long __cdecl CDMNodeObj::GetPrimaryPartitionCount(void) __ptr64` | 123 (0x7b) | Exported Function | 0x000000018001f810 | 0x0001f810
`public: unsigned long __cdecl CTaskData::GetUIState(void) __ptr64` | 143 (0x8f) | Exported Function | 0x00000001800282d0 | 0x000282d0
`public: unsigned short * __ptr64 __cdecl CDataCache::FindDeviceInstanceId(__int64) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180012310 | 0x00012310
`public: virtual __cdecl CDataCache::~CDataCache(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180010bc0 | 0x00010bc0
`public: void __cdecl CContextMenu::DoDelete(__int64) __ptr64` | 36 (0x24) | Exported Function | 0x000000018000b330 | 0x0000b330
`public: void __cdecl CContextMenu::DoRevertToNT4(__int64,int) __ptr64` | 37 (0x25) | Exported Function | 0x000000018000d170 | 0x0000d170
`public: void __cdecl CContextMenu::PopUpInit(class CDMNodeObj * __ptr64,int & __ptr64,int & __ptr64,int) __ptr64` | 205 (0xcd) | Exported Function | 0x000000018000daf0 | 0x0000daf0
`public: void __cdecl CContextMenu::RefreshFileSys(__int64) __ptr64` | 210 (0xd2) | Exported Function | 0x000000018000f490 | 0x0000f490
`public: void __cdecl CDataCache::AddFileSystemInfoToCache(unsigned long,struct filesysteminfo * __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180011070 | 0x00011070
`public: void __cdecl CDataCache::AddFileSystemInfoToListAndMap(unsigned long,struct filesysteminfo * __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180011120 | 0x00011120
`public: void __cdecl CDataCache::AddLDMObjMapEntry(struct _LDM_OBJ_MAP_ENTRY * __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180008100 | 0x00008100
`public: void __cdecl CDataCache::AddRegionToVolumeMemberList(class CDMNodeObj * __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180011280 | 0x00011280
`public: void __cdecl CDataCache::AdjustRegionCountInLegendList(enum _REGIONTYPE,int,class CTaskData * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180011470 | 0x00011470
`public: void __cdecl CDataCache::AdjustVolumeCountInLegendList(enum _VOLUMELAYOUT,int,class CTaskData * __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800114d0 | 0x000114d0
`public: void __cdecl CDataCache::CreateDiskList(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180011530 | 0x00011530
`public: void __cdecl CDataCache::CreateShortDiskName(struct diskinfoex & __ptr64) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800119e0 | 0x000119e0
`public: void __cdecl CDataCache::CreateVolumeList(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180011be0 | 0x00011be0
`public: void __cdecl CDataCache::DeleteDiskGroupData(struct DISK_GROUP_DATA * __ptr64) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180011d60 | 0x00011d60
`public: void __cdecl CDataCache::DeleteEncapsulateData(struct ENCAPSULATE_DATA * __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180011d80 | 0x00011d80
`public: void __cdecl CDataCache::DeleteLists(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180011df0 | 0x00011df0
`public: void __cdecl CDataCache::DeleteRegionFromVolumeMemberList(class CDMNodeObj * __ptr64) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180012000 | 0x00012000
`public: void __cdecl CDataCache::EnumNTFSwithDriveLetter(int * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x00000001800120b0 | 0x000120b0
`public: void __cdecl CDataCache::FillDeviceInstanceId(unsigned short * __ptr64,unsigned short * __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x00000001800121c0 | 0x000121c0
`public: unsigned long __cdecl CDMNodeObj::GetMaxPartitionCount(void) __ptr64` | 107 (0x6b) | Exported Function | 0x000000018001eda0 | 0x0001eda0
`public: void __cdecl CDataCache::GetFileSystemTypes(unsigned long & __ptr64,struct ifilesysteminfo * __ptr64 * __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180012a70 | 0x00012a70
`public: unsigned long __cdecl CDMNodeObj::GetLogicalDriveCount(void) __ptr64` | 103 (0x67) | Exported Function | 0x000000018001eb80 | 0x0001eb80
`public: unsigned long __cdecl CDMNodeObj::GetDeviceType(void) __ptr64` | 68 (0x44) | Exported Function | 0x000000018001d370 | 0x0001d370
`public: int __cdecl CTaskData::IsEfi(void) __ptr64` | 169 (0xa9) | Exported Function | 0x0000000180028320 | 0x00028320
`public: int __cdecl CTaskData::IsLocalMachine(void) __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180028340 | 0x00028340
`public: int __cdecl CTaskData::IsNEC_98Server(void) __ptr64` | 182 (0xb6) | Exported Function | 0x0000000180028360 | 0x00028360
`public: int __cdecl CTaskData::IsNTServer(void) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180028380 | 0x00028380
`public: int __cdecl CTaskData::IsPostLonghornVdsVersion(void) __ptr64` | 187 (0xbb) | Exported Function | 0x00000001800283a0 | 0x000283a0
`public: int __cdecl CTaskData::IsPreLonghornVdsVersion(void) __ptr64` | 189 (0xbd) | Exported Function | 0x00000001800283c0 | 0x000283c0
`public: int __cdecl CTaskData::IsSecureSystemPartition(void) __ptr64` | 192 (0xc0) | Exported Function | 0x00000001800283e0 | 0x000283e0
`public: int __cdecl CTaskData::IsWolfpack(void) __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180028400 | 0x00028400
`public: int __cdecl CTaskData::SupportGpt(void) __ptr64` | 222 (0xde) | Exported Function | 0x00000001800285d0 | 0x000285d0
`public: long __cdecl CContextMenu::Command(long,struct IDataObject * __ptr64,__int64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180008e90 | 0x00008e90
`public: long __cdecl CContextMenu::ShowContextMenu(class CWnd * __ptr64,long,long,__int64) __ptr64` | 220 (0xdc) | Exported Function | 0x000000018000f720 | 0x0000f720
`public: long __cdecl CDMNodeObj::GetFlags(void) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018001e880 | 0x0001e880
`public: long __cdecl CDMNodeObj::GetVolumeFileSystemTypes(unsigned long & __ptr64,struct ilhfilesysteminfo * __ptr64 * __ptr64) __ptr64` | 148 (0x94) | Exported Function | 0x0000000180021cc0 | 0x00021cc0
`public: long __cdecl CDMNodeObj::IsConvertSuccess(int) __ptr64` | 159 (0x9f) | Exported Function | 0x00000001800222b0 | 0x000222b0
`public: long __cdecl CDMNodeObj::IsExtendedPartitionCreated(void) __ptr64` | 170 (0xaa) | Exported Function | 0x00000001800226d0 | 0x000226d0
`public: long __cdecl CDMNodeObj::IsVolumeArrived(__int64,enum _LAYOUT_TYPES) __ptr64` | 196 (0xc4) | Exported Function | 0x0000000180022fd0 | 0x00022fd0
`public: short __cdecl CDMNodeObj::GetIVolumeClientVersion(void) __ptr64` | 96 (0x60) | Exported Function | 0x000000018001e8b0 | 0x0001e8b0
`public: short __cdecl CTaskData::GetIVolumeClientVersion(void) __ptr64` | 97 (0x61) | Exported Function | 0x00000001800280b0 | 0x000280b0
`public: struct HWND__ * __ptr64 __cdecl CDMComponentData::GetMMCWindow(void) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180017420 | 0x00017420
`public: unsigned int __cdecl CDMNodeObj::GetIconId(int) __ptr64` | 98 (0x62) | Exported Function | 0x000000018001e8d0 | 0x0001e8d0
`public: unsigned long __cdecl CDataCache::GetDiskCount(void) __ptr64` | 78 (0x4e) | Exported Function | 0x00000001800081e0 | 0x000081e0
`public: unsigned long __cdecl CDataCache::GetVolumeCount(void) __ptr64` | 147 (0x93) | Exported Function | 0x0000000180008280 | 0x00008280
`public: unsigned long __cdecl CDMNodeObj::GetColorRef(void) __ptr64` | 63 (0x3f) | Exported Function | 0x000000018001d160 | 0x0001d160
`public: unsigned long __cdecl CDMNodeObj::GetDeviceAttributes(void) __ptr64` | 66 (0x42) | Exported Function | 0x000000018001d330 | 0x0001d330
`public: unsigned long __cdecl CDMNodeObj::GetDeviceState(void) __ptr64` | 67 (0x43) | Exported Function | 0x000000018001d350 | 0x0001d350
`public: unsigned long __cdecl CDMNodeObj::GetExtendedRegionColor(void) __ptr64` | 87 (0x57) | Exported Function | 0x000000018001daa0 | 0x0001daa0
`public: void __cdecl CDataCache::PopulateDiskGroupData(struct DISK_GROUP_DATA * __ptr64) __ptr64` | 206 (0xce) | Exported Function | 0x0000000180004480 | 0x00004480
`public: void __cdecl CDataCache::PopulateEncapsulateData(struct ENCAPSULATE_DATA * __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x0000000180013fe0 | 0x00013fe0
`public: void __cdecl CDataCache::SetDiskList(struct diskinfoex * __ptr64,unsigned long) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180014820 | 0x00014820
`public: void __cdecl CDMNodeObj::MarkDiskForLastVolume(class CDMNodeObj * __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x0000000180023150 | 0x00023150
`public: void __cdecl CDMNodeObj::MarkDisksForLastVolume(void) __ptr64` | 203 (0xcb) | Exported Function | 0x00000001800231e0 | 0x000231e0
`public: void __cdecl CDMNodeObj::RecalculateSpace(void) __ptr64` | 208 (0xd0) | Exported Function | 0x0000000180023530 | 0x00023530
`public: void __cdecl CDMNodeObj::SetFSId(__int64) __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180023610 | 0x00023610
`public: void __cdecl CDMSnapin::SetDescriptionBarText(__int64) __ptr64` | 212 (0xd4) | Exported Function | 0x000000018001b4a0 | 0x0001b4a0
`public: void __cdecl CDMSnapin::UpDateConsoleView(__int64) __ptr64` | 226 (0xe2) | Exported Function | 0x000000018001b890 | 0x0001b890
`public: void __cdecl CTaskData::EnumDisks(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180027100 | 0x00027100
`public: void __cdecl CTaskData::EnumNTFSwithDriveLetter(int * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180027120 | 0x00027120
`public: void __cdecl CTaskData::EnumVolumes(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180027140 | 0x00027140
`public: void __cdecl CTaskData::FilterCookiesBigEnoughForFTRepair(unsigned long & __ptr64,__int64 * __ptr64,__int64 * __ptr64 * __ptr64,__int64,class CDMNodeObj * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180027160 | 0x00027160
`public: void __cdecl CTaskData::FilterCookiesBigEnoughForRAID5Repair(unsigned long & __ptr64,__int64 * __ptr64,__int64 * __ptr64 * __ptr64,__int64,class CDMNodeObj * __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x00000001800273b0 | 0x000273b0
`public: void __cdecl CTaskData::FindDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800274a0 | 0x000274a0
`public: void __cdecl CTaskData::GetDiskCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64,int,unsigned long,int) __ptr64` | 70 (0x46) | Exported Function | 0x00000001800275a0 | 0x000275a0
`public: void __cdecl CTaskData::GetDiskCookiesForAddMirror(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x00000001800276a0 | 0x000276a0
`public: void __cdecl CTaskData::GetDiskCookiesForCreateVolume(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 72 (0x48) | Exported Function | 0x00000001800278d0 | 0x000278d0
`public: void __cdecl CTaskData::GetDiskCookiesForExtendVolume(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 73 (0x49) | Exported Function | 0x00000001800279f0 | 0x000279f0
`public: void __cdecl CTaskData::GetDiskCookiesForSig(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180027aa0 | 0x00027aa0
`public: void __cdecl CTaskData::GetDiskCookiesForUpgrade(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180027ba0 | 0x00027ba0
`public: void __cdecl CTaskData::GetDiskCookiesToEncap(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180027d00 | 0x00027d00
`public: void __cdecl CTaskData::GetDiskCookiesWithFreeSpace(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180027e00 | 0x00027e00
`public: void __cdecl CTaskData::GetDiskInfoFromVolCookie(__int64,int & __ptr64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64,unsigned long,int) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180027ed0 | 0x00027ed0
`public: void __cdecl CTaskData::GetDriveLetters(short & __ptr64,unsigned short * __ptr64 * __ptr64,unsigned short) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180028070 | 0x00028070
`public: void __cdecl CTaskData::GetFileSystemTypes(unsigned long & __ptr64,struct ifilesysteminfo * __ptr64 * __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180028090 | 0x00028090
`public: void __cdecl CTaskData::GetMinMaxPartitionSizes(__int64,__int64 & __ptr64,__int64 & __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x00000001800280d0 | 0x000280d0
`public: void __cdecl CTaskData::GetOtherDisksFromVolCookie(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 116 (0x74) | Exported Function | 0x00000001800280f0 | 0x000280f0
`public: void __cdecl CDMNodeObj::GetStorageType(class CString & __ptr64,int) __ptr64` | 142 (0x8e) | Exported Function | 0x00000001800214a0 | 0x000214a0
`public: void __cdecl CDMNodeObj::GetSizeString(class CString & __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180021220 | 0x00021220
`public: void __cdecl CDMNodeObj::GetSizeMB(__int64 & __ptr64) __ptr64` | 137 (0x89) | Exported Function | 0x00000001800211d0 | 0x000211d0
`public: void __cdecl CDMNodeObj::GetSize(__int64 & __ptr64,int) __ptr64` | 136 (0x88) | Exported Function | 0x0000000180021170 | 0x00021170
`public: void __cdecl CDataCache::SetDriveLetterInUse(unsigned short,int) __ptr64` | 214 (0xd6) | Exported Function | 0x0000000180014900 | 0x00014900
`public: void __cdecl CDataCache::SetVolumeList(struct volumeinfo * __ptr64,unsigned long,class CTaskData * __ptr64) __ptr64` | 219 (0xdb) | Exported Function | 0x0000000180014a00 | 0x00014a00
`public: void __cdecl CDMComponentData::AddRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180016ce0 | 0x00016ce0
`public: void __cdecl CDMComponentData::ChangeRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180016d40 | 0x00016d40
`public: void __cdecl CDMComponentData::DeleteRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180017080 | 0x00017080
`public: void __cdecl CDMComponentData::EmptyOcxViewData(class CDMScopeNode * __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180017250 | 0x00017250
`public: void __cdecl CDMComponentData::LoadData(class CDMScopeNode * __ptr64,long) __ptr64` | 200 (0xc8) | Exported Function | 0x0000000180017600 | 0x00017600
`public: void __cdecl CDMComponentData::RefreshDiskView(class CDMScopeNode * __ptr64) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180017b30 | 0x00017b30
`public: void __cdecl CDMComponentData::ReloadData(class CDMScopeNode * __ptr64) __ptr64` | 211 (0xd3) | Exported Function | 0x0000000180017c70 | 0x00017c70
`public: void __cdecl CDMComponentData::SetOcxViewType(class CDMScopeNode * __ptr64) __ptr64` | 216 (0xd8) | Exported Function | 0x0000000180017f60 | 0x00017f60
`public: void __cdecl CDMComponentData::SetOcxViewTypeForce(class CDMScopeNode * __ptr64) __ptr64` | 217 (0xd9) | Exported Function | 0x0000000180018030 | 0x00018030
`public: void __cdecl CDMComponentData::UIStateChange(class CDMScopeNode * __ptr64,unsigned long) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180018070 | 0x00018070
`public: int __cdecl CTaskData::IsAlpha(void) __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180028300 | 0x00028300
`public: void __cdecl CDMNodeObj::EnumDiskRegions(__int64 * __ptr64 * __ptr64,long & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x000000018001cf90 | 0x0001cf90
`public: void __cdecl CDMNodeObj::EnumVolumeMembers(__int64 * __ptr64 * __ptr64,long & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x000000018001d090 | 0x0001d090
`public: void __cdecl CDMNodeObj::GetDiskTypeName(class CString & __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x000000018001d720 | 0x0001d720
`public: void __cdecl CDMNodeObj::GetDriveLetter(unsigned short & __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x000000018001d940 | 0x0001d940
`public: void __cdecl CDMNodeObj::GetFileSystemLabel(class CString & __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x000000018001e420 | 0x0001e420
`public: void __cdecl CDMNodeObj::GetFileSystemName(class CString & __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x000000018001e520 | 0x0001e520
`public: void __cdecl CDMNodeObj::GetFileSystemSize(long & __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x000000018001e720 | 0x0001e720
`public: void __cdecl CDMNodeObj::GetLongName(class CString & __ptr64,int) __ptr64` | 104 (0x68) | Exported Function | 0x000000018001ebd0 | 0x0001ebd0
`public: void __cdecl CDMNodeObj::GetMaxAdjustedFreeSize(__int64 & __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x000000018001ed80 | 0x0001ed80
`public: void __cdecl CDMNodeObj::GetName(class CString & __ptr64) __ptr64` | 110 (0x6e) | Exported Function | 0x000000018001edc0 | 0x0001edc0
`public: void __cdecl CDMNodeObj::GetObjectId(__int64 & __ptr64) __ptr64` | 113 (0x71) | Exported Function | 0x000000018001f0e0 | 0x0001f0e0
`public: void __cdecl CDMNodeObj::GetPartitionStyleString(class CString & __ptr64,int) __ptr64` | 120 (0x78) | Exported Function | 0x000000018001f360 | 0x0001f360
`public: void __cdecl CDMNodeObj::GetShortName(class CString & __ptr64) __ptr64` | 134 (0x86) | Exported Function | 0x0000000180020f60 | 0x00020f60
`public: void __cdecl CDMNodeObj::EnumFirstVolumeMember(__int64 & __ptr64,long & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x000000018001d020 | 0x0001d020
`public: void __cdecl CTaskData::GetRegionColorStructPtr(struct _REGION_COLORS * __ptr64 * __ptr64,int & __ptr64) __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180008230 | 0x00008230
`public: int __cdecl CTaskData::HasNTFSwithDriveLetter(void) __ptr64` | 154 (0x9a) | Exported Function | 0x00000001800282e0 | 0x000282e0
`public: int __cdecl CTaskData::GetAssignedDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180027500 | 0x00027500
`public: class CString __cdecl CTaskData::GetServerName(void) __ptr64` | 133 (0x85) | Exported Function | 0x0000000180028290 | 0x00028290
`public: class CWnd * __ptr64 __cdecl CTaskData::GetOcxFrameCWndPtr(void) __ptr64` | 114 (0x72) | Exported Function | 0x0000000180008220 | 0x00008220
`public: enum _LAYOUT_TYPES __cdecl CDMNodeObj::GetLayoutType(void) __ptr64` | 101 (0x65) | Exported Function | 0x000000018001eb20 | 0x0001eb20
`public: enum _PARTITIONSTYLE __cdecl CDMNodeObj::GetPartitionStyle(void) __ptr64` | 119 (0x77) | Exported Function | 0x000000018001f340 | 0x0001f340
`public: enum _STORAGE_TYPES __cdecl CDMNodeObj::GetStorageType(void) __ptr64` | 141 (0x8d) | Exported Function | 0x00000001800213f0 | 0x000213f0
`public: int __cdecl CDataCache::FindCookieAndRemoveFromList(__int64,class CList<class CDMNodeObj * __ptr64,class CDMNodeObj * __ptr64> * __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x00000001800122d0 | 0x000122d0
`public: int __cdecl CDataCache::FindDiskPtrFromDiskId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x00000001800123a0 | 0x000123a0
`public: int __cdecl CDataCache::FindDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180012430 | 0x00012430
`public: int __cdecl CDataCache::FindFileSystem(__int64,struct filesysteminfo & __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180012510 | 0x00012510
`public: int __cdecl CDataCache::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 57 (0x39) | Exported Function | 0x00000001800125d0 | 0x000125d0
`public: int __cdecl CDataCache::FindRegionPtrOnDiskFromRegionId(class CDMNodeObj * __ptr64,__int64,class CDMNodeObj * __ptr64 * __ptr64,struct __POSITION * __ptr64 & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180012660 | 0x00012660
`public: int __cdecl CDataCache::GetBootPort(void) __ptr64` | 61 (0x3d) | Exported Function | 0x00000001800127e0 | 0x000127e0
`public: int __cdecl CDataCache::HasNTFSwithDriveLetter(void) __ptr64` | 153 (0x99) | Exported Function | 0x0000000180013710 | 0x00013710
`public: int __cdecl CDataCache::HasVMDisk(void) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180013780 | 0x00013780
`public: int __cdecl CDataCache::IsAlpha(void) __ptr64` | 157 (0x9d) | Exported Function | 0x00000001800137f0 | 0x000137f0
`public: int __cdecl CDataCache::IsDynamic1394(void) __ptr64` | 165 (0xa5) | Exported Function | 0x0000000180013800 | 0x00013800
`public: int __cdecl CDataCache::IsEfi(void) __ptr64` | 168 (0xa8) | Exported Function | 0x0000000180013820 | 0x00013820
`public: int __cdecl CDataCache::IsNEC_98Server(void) __ptr64` | 181 (0xb5) | Exported Function | 0x0000000180013830 | 0x00013830
`public: int __cdecl CDataCache::IsPersonalOrLapTopServer(void) __ptr64` | 185 (0xb9) | Exported Function | 0x0000000180013850 | 0x00013850
`public: int __cdecl CDataCache::IsPostLonghornVdsVersion(void) __ptr64` | 186 (0xba) | Exported Function | 0x0000000180013870 | 0x00013870
`public: int __cdecl CDataCache::IsPreLonghornVdsVersion(void) __ptr64` | 188 (0xbc) | Exported Function | 0x0000000180013890 | 0x00013890
`public: int __cdecl CDataCache::IsWolfpack(void) __ptr64` | 198 (0xc6) | Exported Function | 0x00000001800139f0 | 0x000139f0
`public: int __cdecl CDataCache::SupportGpt(void) __ptr64` | 221 (0xdd) | Exported Function | 0x0000000180014ac0 | 0x00014ac0
`public: int __cdecl CDataCache::SupportMirror(void) __ptr64` | 223 (0xdf) | Exported Function | 0x0000000180014ad0 | 0x00014ad0
`public: int __cdecl CDataCache::SupportRaid5(void) __ptr64` | 224 (0xe0) | Exported Function | 0x0000000180014ae0 | 0x00014ae0
`public: class CString __cdecl CDataCache::GetServerName(void) __ptr64` | 132 (0x84) | Exported Function | 0x0000000180008250 | 0x00008250
`public: int __cdecl CDMComponentData::GetScopeNodeForResultPane(__int64,class CDMScopeNode * __ptr64 * __ptr64) __ptr64` | 131 (0x83) | Exported Function | 0x0000000180017430 | 0x00017430
`public: class CDMNodeObj * __ptr64 __cdecl CTaskData::GetDMDataObjPtrFromId(__int64) __ptr64` | 65 (0x41) | Exported Function | 0x0000000180027550 | 0x00027550
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetParentVolumePtr(void) __ptr64` | 118 (0x76) | Exported Function | 0x000000018001f2d0 | 0x0001f2d0
`CookieSort` | 229 (0xe5) | Exported Function | 0x0000000180028690 | 0x00028690
`DllCanUnloadNow` | 230 (0xe6) | Exported Function | 0x0000000180004020 | 0x00004020
`DllGetClassObject` | 231 (0xe7) | Exported Function | 0x0000000180003c40 | 0x00003c40
`DllRegisterServer` | 232 (0xe8) | Exported Function | 0x0000000180018bd0 | 0x00018bd0
`GetPropertyPageData` | 124 (0x7c) | Exported Function | 0x0000000180012c90 | 0x00012c90
`IsRequestPending` | 190 (0xbe) | Exported Function | 0x00000001800138b0 | 0x000138b0
`LoadPropertyPageData` | 201 (0xc9) | Exported Function | 0x0000000180013a10 | 0x00013a10
`namecmp` | 233 (0xe9) | Exported Function | 0x00000001800287c0 | 0x000287c0
`protected: void __cdecl CDataCache::GetDiskCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180012880 | 0x00012880
`protected: void __cdecl CDataCache::GetDriveLetters(short & __ptr64,unsigned short * __ptr64 * __ptr64,unsigned short) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180012950 | 0x00012950
`protected: void __cdecl CDataCache::GetMinMaxPartitionSizes(__int64,__int64 & __ptr64,__int64 & __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180012ba0 | 0x00012ba0
`protected: void __cdecl CDataCache::GetVolumeCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x0000000180013640 | 0x00013640
`public: __cdecl CDataCache::CDataCache(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180010520 | 0x00010520
`public: __cdecl CDMNodeObj::~CDMNodeObj(void) __ptr64` | 2 (0x2) | Exported Function | 0x000000018001c740 | 0x0001c740
`public: __int64 __cdecl CDataCache::GetLastKnownState(__int64) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180012af0 | 0x00012af0
`public: __int64 __cdecl CDMNodeObj::GetLdmObjectId(void) __ptr64` | 102 (0x66) | Exported Function | 0x00000001800081f0 | 0x000081f0
`public: __int64 __cdecl CDMNodeObj::GetShrinkableSizeInMB(void) __ptr64` | 135 (0x87) | Exported Function | 0x0000000180021120 | 0x00021120
`public: __int64 __cdecl CDMNodeObj::GetStartOffset(void) __ptr64` | 139 (0x8b) | Exported Function | 0x0000000180021370 | 0x00021370
`public: __int64 __cdecl CDMNodeObj::GetUnallocSpace(int) __ptr64` | 144 (0x90) | Exported Function | 0x0000000180021b40 | 0x00021b40
`public: __int64 __cdecl CDMNodeObj::GetUsableContiguousSpaceInMB(void) __ptr64` | 145 (0x91) | Exported Function | 0x0000000180021c80 | 0x00021c80
`public: __int64 __cdecl CDMNodeObj::GetVolumeTotalSizeMB(void) __ptr64` | 151 (0x97) | Exported Function | 0x00000001800221b0 | 0x000221b0
`public: class CDMComponentData * __ptr64 __cdecl CDataCache::GetComponentData(void) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180012860 | 0x00012860
`public: class CDMNodeObj * __ptr64 __cdecl CDataCache::CreateNodeObjAndAddToMap(int,enum _NODEOBJ_TYPES,class CDataCache * __ptr64,void * __ptr64,__int64) __ptr64` | 27 (0x1b) | Exported Function | 0x00000001800115e0 | 0x000115e0
`public: class CDMNodeObj * __ptr64 __cdecl CDataCache::CreateRegionNodeObj(class CDMNodeObj * __ptr64,struct regioninfoex * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180011810 | 0x00011810
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetParentDiskPtr(void) __ptr64` | 117 (0x75) | Exported Function | 0x000000018001f200 | 0x0001f200
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetRegionByOffset(__int64) __ptr64` | 125 (0x7d) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: int __cdecl CDMNodeObj::CanHaveGPT(void) __ptr64` | 11 (0xb) | Exported Function | 0x000000018001c840 | 0x0001c840
`public: int __cdecl CDMNodeObj::ContainsActivePartition(void) __ptr64` | 14 (0xe) | Exported Function | 0x000000018001c8a0 | 0x0001c8a0
`public: int __cdecl CDMNodeObj::ContainsBootIniPartition(void) __ptr64` | 15 (0xf) | Exported Function | 0x000000018001c8e0 | 0x0001c8e0
`public: int __cdecl CDMNodeObj::IsDiskOffline(void) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180022590 | 0x00022590
`public: int __cdecl CDMNodeObj::IsDiskReadOnly(void) __ptr64` | 164 (0xa4) | Exported Function | 0x00000001800225d0 | 0x000225d0
`public: int __cdecl CDMNodeObj::IsEECoveredGPTDisk(void) __ptr64` | 166 (0xa6) | Exported Function | 0x0000000180022610 | 0x00022610
`public: int __cdecl CDMNodeObj::IsESPPartition(void) __ptr64` | 167 (0xa7) | Exported Function | 0x0000000180022640 | 0x00022640
`public: int __cdecl CDMNodeObj::IsFakeVolume(void) __ptr64` | 172 (0xac) | Exported Function | 0x0000000180022790 | 0x00022790
`public: int __cdecl CDMNodeObj::IsFirstFreeRegion(void) __ptr64` | 173 (0xad) | Exported Function | 0x00000001800227d0 | 0x000227d0
`public: int __cdecl CDMNodeObj::IsFreeSpaceFollowed(__int64) __ptr64` | 174 (0xae) | Exported Function | 0x00000001800228e0 | 0x000228e0
`public: int __cdecl CDMNodeObj::IsFTVolume(void) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180022740 | 0x00022740
`public: int __cdecl CDMNodeObj::IsHiddenRegion(void) __ptr64` | 175 (0xaf) | Exported Function | 0x0000000180022a10 | 0x00022a10
`public: int __cdecl CDMNodeObj::IsInFlux(void) __ptr64` | 176 (0xb0) | Exported Function | 0x0000000180022a40 | 0x00022a40
`public: int __cdecl CDMNodeObj::IsMbrEEPartition(void) __ptr64` | 178 (0xb2) | Exported Function | 0x0000000180022a60 | 0x00022a60
`public: int __cdecl CDMNodeObj::IsMember(class CDMNodeObj * __ptr64) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180022ac0 | 0x00022ac0
`public: int __cdecl CDMNodeObj::IsNEC_98Disk(void) __ptr64` | 180 (0xb4) | Exported Function | 0x0000000180022b60 | 0x00022b60
`public: int __cdecl CDMNodeObj::IsOemPartition(void) __ptr64` | 184 (0xb8) | Exported Function | 0x0000000180022c00 | 0x00022c00
`public: int __cdecl CDMNodeObj::IsRevertable(void) __ptr64` | 191 (0xbf) | Exported Function | 0x0000000180022cc0 | 0x00022cc0
`public: int __cdecl CDMNodeObj::IsSpacesProtectivePartition(void) __ptr64` | 193 (0xc1) | Exported Function | 0x0000000180022d90 | 0x00022d90
`public: int __cdecl CDMNodeObj::IsUnknownPartition(void) __ptr64` | 194 (0xc2) | Exported Function | 0x0000000180022e20 | 0x00022e20
`public: int __cdecl CDMNodeObj::IsUpgradeable(void) __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180022f70 | 0x00022f70
`public: int __cdecl CDMNodeObj::IsVolumeSimple(void) __ptr64` | 197 (0xc5) | Exported Function | 0x00000001800230b0 | 0x000230b0
`public: int __cdecl CDMNodeObj::OnlyContiguousExtendAllowed(void) __ptr64` | 204 (0xcc) | Exported Function | 0x00000001800232d0 | 0x000232d0
`public: int __cdecl CDMNodeObj::VolumeContainsActiveRegion(void) __ptr64` | 227 (0xe3) | Exported Function | 0x00000001800236e0 | 0x000236e0
`public: int __cdecl CDMScopeNodeCollection::GetScopeNode(__int64,class CDMScopeNode * __ptr64 * __ptr64) __ptr64` | 130 (0x82) | Exported Function | 0x0000000180015870 | 0x00015870
`public: int __cdecl CDMSnapin::GetResultPane(__int64,class CDMResultPane * __ptr64 * __ptr64) __ptr64` | 128 (0x80) | Exported Function | 0x000000018001a310 | 0x0001a310
`public: int __cdecl CTaskData::FindFileSystem(__int64,struct filesysteminfo & __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x00000001800274c0 | 0x000274c0
`public: int __cdecl CTaskData::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x00000001800274e0 | 0x000274e0
`public: int __cdecl CDMNodeObj::IsDiskEmpty(void) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180022410 | 0x00022410
`public: int __cdecl CDMNodeObj::IsCurrSystemVolume(void) __ptr64` | 161 (0xa1) | Exported Function | 0x0000000180022390 | 0x00022390
`public: int __cdecl CDMNodeObj::IsCurrBootVolume(void) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180022320 | 0x00022320
`public: int __cdecl CDMNodeObj::IsActive(void) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180022220 | 0x00022220
`public: int __cdecl CDMNodeObj::ContainsBootIniPartitionForWolfpack(void) __ptr64` | 16 (0x10) | Exported Function | 0x000000018001c940 | 0x0001c940
`public: int __cdecl CDMNodeObj::ContainsBootVolumesNumberChange(__int64,int * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x000000018001c9d0 | 0x0001c9d0
`public: int __cdecl CDMNodeObj::ContainsESPPartition(void) __ptr64` | 18 (0x12) | Exported Function | 0x000000018001ca70 | 0x0001ca70
`public: int __cdecl CDMNodeObj::ContainsFVEPartition(void) __ptr64` | 19 (0x13) | Exported Function | 0x000000018001cae0 | 0x0001cae0
`public: int __cdecl CDMNodeObj::ContainsLogicalDrvBootPartition(void) __ptr64` | 20 (0x14) | Exported Function | 0x000000018001cb20 | 0x0001cb20
`public: int __cdecl CDMNodeObj::ContainsPageFile(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018001cb70 | 0x0001cb70
`public: int __cdecl CDMNodeObj::ContainsRealSystemPartition(void) __ptr64` | 22 (0x16) | Exported Function | 0x000000018001cbb0 | 0x0001cbb0
`public: int __cdecl CDMNodeObj::ContainsSubDiskNeedResync(void) __ptr64` | 23 (0x17) | Exported Function | 0x000000018001cc30 | 0x0001cc30
`public: int __cdecl CDMNodeObj::ContainsSystemInformation(void) __ptr64` | 24 (0x18) | Exported Function | 0x000000018001cd60 | 0x0001cd60
`public: int __cdecl CDMNodeObj::ContainsSystemPartition(void) __ptr64` | 25 (0x19) | Exported Function | 0x000000018001cde0 | 0x0001cde0
`public: int __cdecl CDMNodeObj::EnhancedIsUpgradeable(class CTaskData * __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x000000018001ce20 | 0x0001ce20
`public: int __cdecl CDMNodeObj::GetDiskInfo(struct diskinfoex & __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x000000018001d390 | 0x0001d390
`public: int __cdecl CTaskData::GetBootPort(void) __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180027530 | 0x00027530
`public: int __cdecl CDMNodeObj::GetDiskSpec(struct diskspec & __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x000000018001d440 | 0x0001d440
`public: int __cdecl CDMNodeObj::GetExtraRegionStatus(class CString & __ptr64,int) __ptr64` | 88 (0x58) | Exported Function | 0x000000018001db00 | 0x0001db00
`public: int __cdecl CDMNodeObj::GetFileSystemType(void) __ptr64` | 92 (0x5c) | Exported Function | 0x000000018001e810 | 0x0001e810
`public: int __cdecl CDMNodeObj::GetImageNum(void) __ptr64` | 99 (0x63) | Exported Function | 0x000000018001e990 | 0x0001e990
`public: int __cdecl CDMNodeObj::GetOfflineReasonText(class CString & __ptr64) __ptr64` | 115 (0x73) | Exported Function | 0x000000018001f110 | 0x0001f110
`public: int __cdecl CDMNodeObj::GetPatternRef(void) __ptr64` | 121 (0x79) | Exported Function | 0x000000018001f710 | 0x0001f710
`public: int __cdecl CDMNodeObj::GetPort(void) __ptr64` | 122 (0x7a) | Exported Function | 0x000000018001f7f0 | 0x0001f7f0
`public: int __cdecl CDMNodeObj::GetRegionInfo(struct regioninfoex & __ptr64) __ptr64` | 127 (0x7f) | Exported Function | 0x000000018001f8e0 | 0x0001f8e0
`public: int __cdecl CDMNodeObj::GetResultStringArray(class CStringArray & __ptr64) __ptr64` | 129 (0x81) | Exported Function | 0x0000000180020e80 | 0x00020e80
`public: int __cdecl CDMNodeObj::GetStatus(void) __ptr64` | 140 (0x8c) | Exported Function | 0x00000001800213b0 | 0x000213b0
`public: int __cdecl CDMNodeObj::GetVolumeInfo(struct volumeinfo & __ptr64) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180021d30 | 0x00021d30
`public: int __cdecl CDMNodeObj::GetVolumeStatus(class CString & __ptr64) __ptr64` | 150 (0x96) | Exported Function | 0x0000000180021da0 | 0x00021da0
`public: int __cdecl CDMNodeObj::HasExtendedPartition(void) __ptr64` | 152 (0x98) | Exported Function | 0x0000000180022200 | 0x00022200
`public: int __cdecl CDMNodeObj::GetDiskStatus(class CString & __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x000000018001d480 | 0x0001d480
`public: void __cdecl CTaskData::SetUIState(unsigned long) __ptr64` | 218 (0xda) | Exported Function | 0x00000001800284a0 | 0x000284a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dmdskmgr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/4870263136d1f6a667871b605762d8a3cb3af8af0bec4b72d421e634eaebc041/detection/





MIT License. Copyright (c) 2020 Strontic.


