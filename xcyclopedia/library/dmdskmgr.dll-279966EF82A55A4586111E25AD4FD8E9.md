---
title: dmdskmgr.dll | Disk Management Snap-in Support Library
excerpt: What is dmdskmgr.dll?
---

# dmdskmgr.dll 

* File Path: `C:\Windows\SysWOW64\dmdskmgr.dll`
* Description: Disk Management Snap-in Support Library

## Hashes

Type | Hash
-- | --
MD5 | `279966EF82A55A4586111E25AD4FD8E9`
SHA1 | `DC243451798D1A69EC30E6913FC363302EAA4E62`
SHA256 | `F8871CE55482621B94895498FF742E22D5867AD1CA9CE063A3A44854BAC97081`
SHA384 | `5777F26142B872E22D81CE42349994480BD614B5147085DADCDE763C153B36CB5E0E34CB55CA4ACE45E2115129F2872C`
SHA512 | `49343D512E7CD3FB82F99763B986080052761D09FCB69179D3D3DED2B048A19BEDCEE8CD81A04070754F0E86F5C20F61D0CCFCDCD7FEA13B3EC42CC358B9E652`
SSDEEP | `3072:lsVKUcfgTz32zplYgeZvtrJHgP7w2dteJUutVVTZHZJX86vKxkJNEqBq/:WH2SUcNWP7revVTZxvpBo`
IMP | `5A038FF6E968BDB47EB5CA35F76774E6`
PESHA1 | `3C00E45AC27DFC18797D3E1F55EC587E6922896A`
PE256 | `815A71419C7424B150A7C20A624AC12B6BC170AE4F5BB4DA5D5FBE6B829E874A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CompareDiskNames` | 228 (0xe4) | Exported Function | 0x656a6520 | 0x00026520
`public: unsigned long __thiscall CDMNodeObj::GetNumMembers(void)` | 111 (0x6f) | Exported Function | 0x6568dd10 | 0x0000dd10
`public: unsigned long __thiscall CDMNodeObj::GetNumRegions(void)` | 112 (0x70) | Exported Function | 0x65697bd0 | 0x00017bd0
`public: unsigned long __thiscall CDMNodeObj::GetPrimaryPartitionCount(void)` | 123 (0x7b) | Exported Function | 0x6569fb40 | 0x0001fb40
`public: unsigned long __thiscall CTaskData::GetUIState(void)` | 143 (0x8f) | Exported Function | 0x656a6300 | 0x00026300
`public: unsigned short * __thiscall CDataCache::FindDeviceInstanceId(__int64)` | 51 (0x33) | Exported Function | 0x65696000 | 0x00016000
`public: virtual __thiscall CDataCache::~CDataCache(void)` | 3 (0x3) | Exported Function | 0x65694be0 | 0x00014be0
`public: void __thiscall CContextMenu::DoDelete(long)` | 36 (0x24) | Exported Function | 0x656905f0 | 0x000105f0
`public: void __thiscall CContextMenu::DoRevertToNT4(long,int)` | 37 (0x25) | Exported Function | 0x65691cf0 | 0x00011cf0
`public: void __thiscall CContextMenu::PopUpInit(class CDMNodeObj *,int &,int &,int)` | 205 (0xcd) | Exported Function | 0x656924d0 | 0x000124d0
`public: void __thiscall CContextMenu::RefreshFileSys(long)` | 210 (0xd2) | Exported Function | 0x65693c80 | 0x00013c80
`public: void __thiscall CDataCache::AddFileSystemInfoToCache(unsigned long,struct filesysteminfo *)` | 4 (0x4) | Exported Function | 0x65695210 | 0x00015210
`public: void __thiscall CDataCache::AddFileSystemInfoToListAndMap(unsigned long,struct filesysteminfo *)` | 5 (0x5) | Exported Function | 0x65695290 | 0x00015290
`public: void __thiscall CDataCache::AddLDMObjMapEntry(struct _LDM_OBJ_MAP_ENTRY *)` | 6 (0x6) | Exported Function | 0x6568dc70 | 0x0000dc70
`public: void __thiscall CDataCache::AddRegionToVolumeMemberList(class CDMNodeObj *)` | 7 (0x7) | Exported Function | 0x65695320 | 0x00015320
`public: void __thiscall CDataCache::AdjustRegionCountInLegendList(enum _REGIONTYPE,int,class CTaskData *)` | 9 (0x9) | Exported Function | 0x65695440 | 0x00015440
`public: void __thiscall CDataCache::AdjustVolumeCountInLegendList(enum _VOLUMELAYOUT,int,class CTaskData *)` | 10 (0xa) | Exported Function | 0x656954f0 | 0x000154f0
`public: void __thiscall CDataCache::CreateDiskList(void)` | 26 (0x1a) | Exported Function | 0x656955e0 | 0x000155e0
`public: void __thiscall CDataCache::CreateShortDiskName(struct diskinfoex &)` | 29 (0x1d) | Exported Function | 0x656958a0 | 0x000158a0
`public: void __thiscall CDataCache::CreateVolumeList(void)` | 30 (0x1e) | Exported Function | 0x65695a00 | 0x00015a00
`public: void __thiscall CDataCache::DeleteDiskGroupData(struct DISK_GROUP_DATA *)` | 31 (0x1f) | Exported Function | 0x6568df00 | 0x0000df00
`public: void __thiscall CDataCache::DeleteEncapsulateData(struct ENCAPSULATE_DATA *)` | 32 (0x20) | Exported Function | 0x65695b30 | 0x00015b30
`public: void __thiscall CDataCache::DeleteLists(void)` | 33 (0x21) | Exported Function | 0x65695b90 | 0x00015b90
`public: void __thiscall CDataCache::DeleteRegionFromVolumeMemberList(class CDMNodeObj *)` | 34 (0x22) | Exported Function | 0x65695d60 | 0x00015d60
`public: void __thiscall CDataCache::EnumNTFSwithDriveLetter(int *,unsigned short * *)` | 43 (0x2b) | Exported Function | 0x65695df0 | 0x00015df0
`public: void __thiscall CDataCache::FillDeviceInstanceId(unsigned short *,unsigned short *)` | 47 (0x2f) | Exported Function | 0x65695ef0 | 0x00015ef0
`public: unsigned long __thiscall CDMNodeObj::GetMaxPartitionCount(void)` | 107 (0x6b) | Exported Function | 0x6569f460 | 0x0001f460
`public: void __thiscall CDataCache::GetFileSystemTypes(unsigned long &,struct ifilesysteminfo * *)` | 93 (0x5d) | Exported Function | 0x65696500 | 0x00016500
`public: unsigned long __thiscall CDMNodeObj::GetLogicalDriveCount(void)` | 103 (0x67) | Exported Function | 0x6569f2d0 | 0x0001f2d0
`public: unsigned long __thiscall CDMNodeObj::GetDeviceType(void)` | 68 (0x44) | Exported Function | 0x6569e130 | 0x0001e130
`public: int __thiscall CTaskData::IsEfi(void)` | 169 (0xa9) | Exported Function | 0x656a6340 | 0x00026340
`public: int __thiscall CTaskData::IsLocalMachine(void)` | 177 (0xb1) | Exported Function | 0x656a6350 | 0x00026350
`public: int __thiscall CTaskData::IsNEC_98Server(void)` | 182 (0xb6) | Exported Function | 0x656a6360 | 0x00026360
`public: int __thiscall CTaskData::IsNTServer(void)` | 183 (0xb7) | Exported Function | 0x656a6380 | 0x00026380
`public: int __thiscall CTaskData::IsPostLonghornVdsVersion(void)` | 187 (0xbb) | Exported Function | 0x656a6390 | 0x00026390
`public: int __thiscall CTaskData::IsPreLonghornVdsVersion(void)` | 189 (0xbd) | Exported Function | 0x656a63b0 | 0x000263b0
`public: int __thiscall CTaskData::IsSecureSystemPartition(void)` | 192 (0xc0) | Exported Function | 0x656a63d0 | 0x000263d0
`public: int __thiscall CTaskData::IsWolfpack(void)` | 199 (0xc7) | Exported Function | 0x656a63f0 | 0x000263f0
`public: int __thiscall CTaskData::SupportGpt(void)` | 222 (0xde) | Exported Function | 0x656a6510 | 0x00026510
`public: long __thiscall CContextMenu::Command(long,struct IDataObject *,long)` | 13 (0xd) | Exported Function | 0x6568e970 | 0x0000e970
`public: long __thiscall CContextMenu::ShowContextMenu(class CWnd *,long,long,long)` | 220 (0xdc) | Exported Function | 0x65693e30 | 0x00013e30
`public: long __thiscall CDMNodeObj::GetFlags(void)` | 95 (0x5f) | Exported Function | 0x6569eff0 | 0x0001eff0
`public: long __thiscall CDMNodeObj::GetVolumeFileSystemTypes(unsigned long &,struct ilhfilesysteminfo * *)` | 148 (0x94) | Exported Function | 0x656a1590 | 0x00021590
`public: long __thiscall CDMNodeObj::IsConvertSuccess(int)` | 159 (0x9f) | Exported Function | 0x656a1a10 | 0x00021a10
`public: long __thiscall CDMNodeObj::IsExtendedPartitionCreated(void)` | 170 (0xaa) | Exported Function | 0x656a1d50 | 0x00021d50
`public: long __thiscall CDMNodeObj::IsVolumeArrived(__int64,enum _LAYOUT_TYPES)` | 196 (0xc4) | Exported Function | 0x656a24c0 | 0x000224c0
`public: short __thiscall CDMNodeObj::GetIVolumeClientVersion(void)` | 96 (0x60) | Exported Function | 0x6569f020 | 0x0001f020
`public: short __thiscall CTaskData::GetIVolumeClientVersion(void)` | 97 (0x61) | Exported Function | 0x656a6160 | 0x00026160
`public: struct HWND__ * __thiscall CDMComponentData::GetMMCWindow(void)` | 105 (0x69) | Exported Function | 0x65699b00 | 0x00019b00
`public: unsigned int __thiscall CDMNodeObj::GetIconId(int)` | 98 (0x62) | Exported Function | 0x6569f040 | 0x0001f040
`public: unsigned long __thiscall CDataCache::GetDiskCount(void)` | 78 (0x4e) | Exported Function | 0x6568dce0 | 0x0000dce0
`public: unsigned long __thiscall CDataCache::GetVolumeCount(void)` | 147 (0x93) | Exported Function | 0x6568dd80 | 0x0000dd80
`public: unsigned long __thiscall CDMNodeObj::GetColorRef(void)` | 63 (0x3f) | Exported Function | 0x6569df80 | 0x0001df80
`public: unsigned long __thiscall CDMNodeObj::GetDeviceAttributes(void)` | 66 (0x42) | Exported Function | 0x6569e0f0 | 0x0001e0f0
`public: unsigned long __thiscall CDMNodeObj::GetDeviceState(void)` | 67 (0x43) | Exported Function | 0x6569e110 | 0x0001e110
`public: unsigned long __thiscall CDMNodeObj::GetExtendedRegionColor(void)` | 87 (0x57) | Exported Function | 0x6569e6c0 | 0x0001e6c0
`public: void __thiscall CDataCache::PopulateDiskGroupData(struct DISK_GROUP_DATA *)` | 206 (0xce) | Exported Function | 0x65689960 | 0x00009960
`public: void __thiscall CDataCache::PopulateEncapsulateData(struct ENCAPSULATE_DATA *)` | 207 (0xcf) | Exported Function | 0x65697440 | 0x00017440
`public: void __thiscall CDataCache::SetDiskList(struct diskinfoex *,unsigned long)` | 213 (0xd5) | Exported Function | 0x65697a00 | 0x00017a00
`public: void __thiscall CDMNodeObj::MarkDiskForLastVolume(class CDMNodeObj *)` | 202 (0xca) | Exported Function | 0x656a25d0 | 0x000225d0
`public: void __thiscall CDMNodeObj::MarkDisksForLastVolume(void)` | 203 (0xcb) | Exported Function | 0x656a2650 | 0x00022650
`public: void __thiscall CDMNodeObj::RecalculateSpace(void)` | 208 (0xd0) | Exported Function | 0x656a2890 | 0x00022890
`public: void __thiscall CDMNodeObj::SetFSId(__int64)` | 215 (0xd7) | Exported Function | 0x656a2930 | 0x00022930
`public: void __thiscall CDMSnapin::SetDescriptionBarText(long)` | 212 (0xd4) | Exported Function | 0x6569ca10 | 0x0001ca10
`public: void __thiscall CDMSnapin::UpDateConsoleView(long)` | 226 (0xe2) | Exported Function | 0x6569ccc0 | 0x0001ccc0
`public: void __thiscall CTaskData::EnumDisks(unsigned long &,long * *)` | 41 (0x29) | Exported Function | 0x656a5310 | 0x00025310
`public: void __thiscall CTaskData::EnumNTFSwithDriveLetter(int *,unsigned short * *)` | 44 (0x2c) | Exported Function | 0x656a5330 | 0x00025330
`public: void __thiscall CTaskData::EnumVolumes(unsigned long &,long * *)` | 46 (0x2e) | Exported Function | 0x656a5350 | 0x00025350
`public: void __thiscall CTaskData::FilterCookiesBigEnoughForFTRepair(unsigned long &,long *,long * *,__int64,class CDMNodeObj *)` | 48 (0x30) | Exported Function | 0x656a5370 | 0x00025370
`public: void __thiscall CTaskData::FilterCookiesBigEnoughForRAID5Repair(unsigned long &,long *,long * *,__int64,class CDMNodeObj *)` | 49 (0x31) | Exported Function | 0x656a5570 | 0x00025570
`public: void __thiscall CTaskData::FindDriveLetter(__int64,unsigned short &)` | 54 (0x36) | Exported Function | 0x656a5650 | 0x00025650
`public: void __thiscall CTaskData::GetDiskCookies(unsigned long &,long * *,int,unsigned long,int)` | 70 (0x46) | Exported Function | 0x656a5730 | 0x00025730
`public: void __thiscall CTaskData::GetDiskCookiesForAddMirror(long,unsigned long &,long * *)` | 71 (0x47) | Exported Function | 0x656a5830 | 0x00025830
`public: void __thiscall CTaskData::GetDiskCookiesForCreateVolume(unsigned long &,long * *)` | 72 (0x48) | Exported Function | 0x656a5a30 | 0x00025a30
`public: void __thiscall CTaskData::GetDiskCookiesForExtendVolume(long,unsigned long &,long * *)` | 73 (0x49) | Exported Function | 0x656a5b60 | 0x00025b60
`public: void __thiscall CTaskData::GetDiskCookiesForSig(unsigned long &,long * *)` | 74 (0x4a) | Exported Function | 0x656a5be0 | 0x00025be0
`public: void __thiscall CTaskData::GetDiskCookiesForUpgrade(unsigned long &,long * *)` | 75 (0x4b) | Exported Function | 0x656a5cc0 | 0x00025cc0
`public: void __thiscall CTaskData::GetDiskCookiesToEncap(unsigned long &,long * *)` | 76 (0x4c) | Exported Function | 0x656a5e20 | 0x00025e20
`public: void __thiscall CTaskData::GetDiskCookiesWithFreeSpace(unsigned long &,long * *)` | 77 (0x4d) | Exported Function | 0x656a5f40 | 0x00025f40
`public: void __thiscall CTaskData::GetDiskInfoFromVolCookie(long,int &,unsigned long &,long * *,unsigned long,int)` | 80 (0x50) | Exported Function | 0x656a6010 | 0x00026010
`public: void __thiscall CTaskData::GetDriveLetters(short &,unsigned short * *,unsigned short)` | 86 (0x56) | Exported Function | 0x656a6120 | 0x00026120
`public: void __thiscall CTaskData::GetFileSystemTypes(unsigned long &,struct ifilesysteminfo * *)` | 94 (0x5e) | Exported Function | 0x656a6140 | 0x00026140
`public: void __thiscall CTaskData::GetMinMaxPartitionSizes(long,__int64 &,__int64 &)` | 109 (0x6d) | Exported Function | 0x656a6180 | 0x00026180
`public: void __thiscall CTaskData::GetOtherDisksFromVolCookie(long,unsigned long &,long * *)` | 116 (0x74) | Exported Function | 0x656a61a0 | 0x000261a0
`public: void __thiscall CDMNodeObj::GetStorageType(class CString &,int)` | 142 (0x8e) | Exported Function | 0x656a1040 | 0x00021040
`public: void __thiscall CDMNodeObj::GetSizeString(class CString &)` | 138 (0x8a) | Exported Function | 0x656a0e40 | 0x00020e40
`public: void __thiscall CDMNodeObj::GetSizeMB(__int64 &)` | 137 (0x89) | Exported Function | 0x656a0df0 | 0x00020df0
`public: void __thiscall CDMNodeObj::GetSize(__int64 &,int)` | 136 (0x88) | Exported Function | 0x656a0d70 | 0x00020d70
`public: void __thiscall CDataCache::SetDriveLetterInUse(unsigned short,int)` | 214 (0xd6) | Exported Function | 0x65697aa0 | 0x00017aa0
`public: void __thiscall CDataCache::SetVolumeList(struct volumeinfo *,unsigned long,class CTaskData *)` | 219 (0xdb) | Exported Function | 0x65697b60 | 0x00017b60
`public: void __thiscall CDMComponentData::AddRow(class CDMScopeNode *,long)` | 8 (0x8) | Exported Function | 0x65699630 | 0x00019630
`public: void __thiscall CDMComponentData::ChangeRow(class CDMScopeNode *,long)` | 12 (0xc) | Exported Function | 0x65699670 | 0x00019670
`public: void __thiscall CDMComponentData::DeleteRow(class CDMScopeNode *,long)` | 35 (0x23) | Exported Function | 0x65699890 | 0x00019890
`public: void __thiscall CDMComponentData::EmptyOcxViewData(class CDMScopeNode *)` | 38 (0x26) | Exported Function | 0x656999d0 | 0x000199d0
`public: void __thiscall CDMComponentData::LoadData(class CDMScopeNode *,long)` | 200 (0xc8) | Exported Function | 0x65699c30 | 0x00019c30
`public: void __thiscall CDMComponentData::RefreshDiskView(class CDMScopeNode *)` | 209 (0xd1) | Exported Function | 0x65699fd0 | 0x00019fd0
`public: void __thiscall CDMComponentData::ReloadData(class CDMScopeNode *)` | 211 (0xd3) | Exported Function | 0x6569a0b0 | 0x0001a0b0
`public: void __thiscall CDMComponentData::SetOcxViewType(class CDMScopeNode *)` | 216 (0xd8) | Exported Function | 0x6569a300 | 0x0001a300
`public: void __thiscall CDMComponentData::SetOcxViewTypeForce(class CDMScopeNode *)` | 217 (0xd9) | Exported Function | 0x6569a390 | 0x0001a390
`public: void __thiscall CDMComponentData::UIStateChange(class CDMScopeNode *,unsigned long)` | 225 (0xe1) | Exported Function | 0x6569a3c0 | 0x0001a3c0
`public: int __thiscall CTaskData::IsAlpha(void)` | 158 (0x9e) | Exported Function | 0x656a6320 | 0x00026320
`public: void __thiscall CDMNodeObj::EnumDiskRegions(long * *,long &)` | 40 (0x28) | Exported Function | 0x6569de10 | 0x0001de10
`public: void __thiscall CDMNodeObj::EnumVolumeMembers(long * *,long &)` | 45 (0x2d) | Exported Function | 0x6569dee0 | 0x0001dee0
`public: void __thiscall CDMNodeObj::GetDiskTypeName(class CString &)` | 83 (0x53) | Exported Function | 0x6569e3f0 | 0x0001e3f0
`public: void __thiscall CDMNodeObj::GetDriveLetter(unsigned short &)` | 84 (0x54) | Exported Function | 0x6569e550 | 0x0001e550
`public: void __thiscall CDMNodeObj::GetFileSystemLabel(class CString &)` | 89 (0x59) | Exported Function | 0x6569ec50 | 0x0001ec50
`public: void __thiscall CDMNodeObj::GetFileSystemName(class CString &)` | 90 (0x5a) | Exported Function | 0x6569ed30 | 0x0001ed30
`public: void __thiscall CDMNodeObj::GetFileSystemSize(long &)` | 91 (0x5b) | Exported Function | 0x6569ee90 | 0x0001ee90
`public: void __thiscall CDMNodeObj::GetLongName(class CString &,int)` | 104 (0x68) | Exported Function | 0x6569f300 | 0x0001f300
`public: void __thiscall CDMNodeObj::GetMaxAdjustedFreeSize(__int64 &)` | 106 (0x6a) | Exported Function | 0x6569f420 | 0x0001f420
`public: void __thiscall CDMNodeObj::GetName(class CString &)` | 110 (0x6e) | Exported Function | 0x6569f480 | 0x0001f480
`public: void __thiscall CDMNodeObj::GetObjectId(__int64 &)` | 113 (0x71) | Exported Function | 0x6569f670 | 0x0001f670
`public: void __thiscall CDMNodeObj::GetPartitionStyleString(class CString &,int)` | 120 (0x78) | Exported Function | 0x6569f8a0 | 0x0001f8a0
`public: void __thiscall CDMNodeObj::GetShortName(class CString &)` | 134 (0x86) | Exported Function | 0x656a0be0 | 0x00020be0
`public: void __thiscall CDMNodeObj::EnumFirstVolumeMember(long &,long &)` | 42 (0x2a) | Exported Function | 0x6569de70 | 0x0001de70
`public: void __thiscall CTaskData::GetRegionColorStructPtr(struct _REGION_COLORS * *,int &)` | 126 (0x7e) | Exported Function | 0x6568dd30 | 0x0000dd30
`public: int __thiscall CTaskData::HasNTFSwithDriveLetter(void)` | 154 (0x9a) | Exported Function | 0x656a6310 | 0x00026310
`public: int __thiscall CTaskData::GetAssignedDriveLetter(long,unsigned short &)` | 60 (0x3c) | Exported Function | 0x656a56b0 | 0x000256b0
`public: class CString __thiscall CTaskData::GetServerName(void)` | 133 (0x85) | Exported Function | 0x656a62d0 | 0x000262d0
`public: class CWnd * __thiscall CTaskData::GetOcxFrameCWndPtr(void)` | 114 (0x72) | Exported Function | 0x6568dd20 | 0x0000dd20
`public: enum _LAYOUT_TYPES __thiscall CDMNodeObj::GetLayoutType(void)` | 101 (0x65) | Exported Function | 0x6569f280 | 0x0001f280
`public: enum _PARTITIONSTYLE __thiscall CDMNodeObj::GetPartitionStyle(void)` | 119 (0x77) | Exported Function | 0x6569f880 | 0x0001f880
`public: enum _STORAGE_TYPES __thiscall CDMNodeObj::GetStorageType(void)` | 141 (0x8d) | Exported Function | 0x656a0fc0 | 0x00020fc0
`public: int __thiscall CDataCache::FindCookieAndRemoveFromList(long,class CList<class CDMNodeObj *,class CDMNodeObj *> *)` | 50 (0x32) | Exported Function | 0x65695fc0 | 0x00015fc0
`public: int __thiscall CDataCache::FindDiskPtrFromDiskId(__int64,class CDMNodeObj * *)` | 52 (0x34) | Exported Function | 0x65696060 | 0x00016060
`public: int __thiscall CDataCache::FindDriveLetter(__int64,unsigned short &)` | 53 (0x35) | Exported Function | 0x656960d0 | 0x000160d0
`public: int __thiscall CDataCache::FindFileSystem(__int64,struct filesysteminfo &)` | 55 (0x37) | Exported Function | 0x65696190 | 0x00016190
`public: int __thiscall CDataCache::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * *)` | 57 (0x39) | Exported Function | 0x65696200 | 0x00016200
`public: int __thiscall CDataCache::FindRegionPtrOnDiskFromRegionId(class CDMNodeObj *,__int64,class CDMNodeObj * *,struct __POSITION * &)` | 59 (0x3b) | Exported Function | 0x65696260 | 0x00016260
`public: int __thiscall CDataCache::GetBootPort(void)` | 61 (0x3d) | Exported Function | 0x65696330 | 0x00016330
`public: int __thiscall CDataCache::HasNTFSwithDriveLetter(void)` | 153 (0x99) | Exported Function | 0x65696f30 | 0x00016f30
`public: int __thiscall CDataCache::HasVMDisk(void)` | 155 (0x9b) | Exported Function | 0x65696f70 | 0x00016f70
`public: int __thiscall CDataCache::IsAlpha(void)` | 157 (0x9d) | Exported Function | 0x65696fb0 | 0x00016fb0
`public: int __thiscall CDataCache::IsDynamic1394(void)` | 165 (0xa5) | Exported Function | 0x65696fc0 | 0x00016fc0
`public: int __thiscall CDataCache::IsEfi(void)` | 168 (0xa8) | Exported Function | 0x65696fd0 | 0x00016fd0
`public: int __thiscall CDataCache::IsNEC_98Server(void)` | 181 (0xb5) | Exported Function | 0x65696fe0 | 0x00016fe0
`public: int __thiscall CDataCache::IsPersonalOrLapTopServer(void)` | 185 (0xb9) | Exported Function | 0x65696ff0 | 0x00016ff0
`public: int __thiscall CDataCache::IsPostLonghornVdsVersion(void)` | 186 (0xba) | Exported Function | 0x65697000 | 0x00017000
`public: int __thiscall CDataCache::IsPreLonghornVdsVersion(void)` | 188 (0xbc) | Exported Function | 0x65697010 | 0x00017010
`public: int __thiscall CDataCache::IsWolfpack(void)` | 198 (0xc6) | Exported Function | 0x656970f0 | 0x000170f0
`public: int __thiscall CDataCache::SupportGpt(void)` | 221 (0xdd) | Exported Function | 0x65697bd0 | 0x00017bd0
`public: int __thiscall CDataCache::SupportMirror(void)` | 223 (0xdf) | Exported Function | 0x65697be0 | 0x00017be0
`public: int __thiscall CDataCache::SupportRaid5(void)` | 224 (0xe0) | Exported Function | 0x65697bf0 | 0x00017bf0
`public: class CString __thiscall CDataCache::GetServerName(void)` | 132 (0x84) | Exported Function | 0x6568dd50 | 0x0000dd50
`public: int __thiscall CDMComponentData::GetScopeNodeForResultPane(long,class CDMScopeNode * *)` | 131 (0x83) | Exported Function | 0x65699b40 | 0x00019b40
`public: class CDMNodeObj * __thiscall CTaskData::GetDMDataObjPtrFromId(__int64)` | 65 (0x41) | Exported Function | 0x656a56f0 | 0x000256f0
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetParentVolumePtr(void)` | 118 (0x76) | Exported Function | 0x6569f820 | 0x0001f820
`CookieSort` | 229 (0xe5) | Exported Function | 0x656a6580 | 0x00026580
`DllCanUnloadNow` | 230 (0xe6) | Exported Function | 0x656896c0 | 0x000096c0
`DllGetClassObject` | 231 (0xe7) | Exported Function | 0x656894b0 | 0x000094b0
`DllRegisterServer` | 232 (0xe8) | Exported Function | 0x6569ab10 | 0x0001ab10
`GetPropertyPageData` | 124 (0x7c) | Exported Function | 0x65696740 | 0x00016740
`IsRequestPending` | 190 (0xbe) | Exported Function | 0x65697020 | 0x00017020
`LoadPropertyPageData` | 201 (0xc9) | Exported Function | 0x65697100 | 0x00017100
`namecmp` | 233 (0xe9) | Exported Function | 0x656a6660 | 0x00026660
`protected: void __thiscall CDataCache::GetDiskCookies(unsigned long &,long * *)` | 69 (0x45) | Exported Function | 0x656963b0 | 0x000163b0
`protected: void __thiscall CDataCache::GetDriveLetters(short &,unsigned short * *,unsigned short)` | 85 (0x55) | Exported Function | 0x65696440 | 0x00016440
`protected: void __thiscall CDataCache::GetMinMaxPartitionSizes(long,__int64 &,__int64 &)` | 108 (0x6c) | Exported Function | 0x656965e0 | 0x000165e0
`protected: void __thiscall CDataCache::GetVolumeCookies(unsigned long &,long * *)` | 146 (0x92) | Exported Function | 0x65696ea0 | 0x00016ea0
`public: __int64 __thiscall CDataCache::GetLastKnownState(__int64)` | 100 (0x64) | Exported Function | 0x65696550 | 0x00016550
`public: __int64 __thiscall CDMNodeObj::GetLdmObjectId(void)` | 102 (0x66) | Exported Function | 0x6568dcf0 | 0x0000dcf0
`public: __int64 __thiscall CDMNodeObj::GetShrinkableSizeInMB(void)` | 135 (0x87) | Exported Function | 0x656a0d20 | 0x00020d20
`public: __int64 __thiscall CDMNodeObj::GetStartOffset(void)` | 139 (0x8b) | Exported Function | 0x656a0f50 | 0x00020f50
`public: __int64 __thiscall CDMNodeObj::GetUnallocSpace(int)` | 144 (0x90) | Exported Function | 0x656a13f0 | 0x000213f0
`public: __int64 __thiscall CDMNodeObj::GetUsableContiguousSpaceInMB(void)` | 145 (0x91) | Exported Function | 0x656a1550 | 0x00021550
`public: __int64 __thiscall CDMNodeObj::GetVolumeTotalSizeMB(void)` | 151 (0x97) | Exported Function | 0x656a18d0 | 0x000218d0
`public: __thiscall CDataCache::CDataCache(void)` | 1 (0x1) | Exported Function | 0x65694790 | 0x00014790
`public: __thiscall CDMNodeObj::~CDMNodeObj(void)` | 2 (0x2) | Exported Function | 0x6569d720 | 0x0001d720
`public: class CDMComponentData * __thiscall CDataCache::GetComponentData(void)` | 64 (0x40) | Exported Function | 0x65696390 | 0x00016390
`public: class CDMNodeObj * __thiscall CDataCache::CreateNodeObjAndAddToMap(int,enum _NODEOBJ_TYPES,class CDataCache *,void *,__int64)` | 27 (0x1b) | Exported Function | 0x65695650 | 0x00015650
`public: class CDMNodeObj * __thiscall CDataCache::CreateRegionNodeObj(class CDMNodeObj *,struct regioninfoex *)` | 28 (0x1c) | Exported Function | 0x656957a0 | 0x000157a0
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetParentDiskPtr(void)` | 117 (0x75) | Exported Function | 0x6569f770 | 0x0001f770
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetRegionByOffset(__int64)` | 125 (0x7d) | Exported Function | 0x6569fb90 | 0x0001fb90
`public: int __thiscall CDMNodeObj::CanHaveGPT(void)` | 11 (0xb) | Exported Function | 0x6569d880 | 0x0001d880
`public: int __thiscall CDMNodeObj::ContainsActivePartition(void)` | 14 (0xe) | Exported Function | 0x6569d8c0 | 0x0001d8c0
`public: int __thiscall CDMNodeObj::ContainsBootIniPartition(void)` | 15 (0xf) | Exported Function | 0x6569d8f0 | 0x0001d8f0
`public: int __thiscall CDMNodeObj::IsDiskOffline(void)` | 163 (0xa3) | Exported Function | 0x656a1c50 | 0x00021c50
`public: int __thiscall CDMNodeObj::IsDiskReadOnly(void)` | 164 (0xa4) | Exported Function | 0x656a1c80 | 0x00021c80
`public: int __thiscall CDMNodeObj::IsEECoveredGPTDisk(void)` | 166 (0xa6) | Exported Function | 0x656a1cc0 | 0x00021cc0
`public: int __thiscall CDMNodeObj::IsESPPartition(void)` | 167 (0xa7) | Exported Function | 0x656a1ce0 | 0x00021ce0
`public: int __thiscall CDMNodeObj::IsFakeVolume(void)` | 172 (0xac) | Exported Function | 0x656a1df0 | 0x00021df0
`public: int __thiscall CDMNodeObj::IsFirstFreeRegion(void)` | 173 (0xad) | Exported Function | 0x656a1e30 | 0x00021e30
`public: int __thiscall CDMNodeObj::IsFreeSpaceFollowed(__int64)` | 174 (0xae) | Exported Function | 0x656a1f30 | 0x00021f30
`public: int __thiscall CDMNodeObj::IsFTVolume(void)` | 171 (0xab) | Exported Function | 0x656a1da0 | 0x00021da0
`public: int __thiscall CDMNodeObj::IsHiddenRegion(void)` | 175 (0xaf) | Exported Function | 0x656a2010 | 0x00022010
`public: int __thiscall CDMNodeObj::IsInFlux(void)` | 176 (0xb0) | Exported Function | 0x656a2030 | 0x00022030
`public: int __thiscall CDMNodeObj::IsMbrEEPartition(void)` | 178 (0xb2) | Exported Function | 0x656a2040 | 0x00022040
`public: int __thiscall CDMNodeObj::IsMember(class CDMNodeObj *)` | 179 (0xb3) | Exported Function | 0x656a2090 | 0x00022090
`public: int __thiscall CDMNodeObj::IsNEC_98Disk(void)` | 180 (0xb4) | Exported Function | 0x656a2110 | 0x00022110
`public: int __thiscall CDMNodeObj::IsOemPartition(void)` | 184 (0xb8) | Exported Function | 0x656a21a0 | 0x000221a0
`public: int __thiscall CDMNodeObj::IsRevertable(void)` | 191 (0xbf) | Exported Function | 0x656a2250 | 0x00022250
`public: int __thiscall CDMNodeObj::IsSpacesProtectivePartition(void)` | 193 (0xc1) | Exported Function | 0x656a22e0 | 0x000222e0
`public: int __thiscall CDMNodeObj::IsUnknownPartition(void)` | 194 (0xc2) | Exported Function | 0x656a2350 | 0x00022350
`public: int __thiscall CDMNodeObj::IsUpgradeable(void)` | 195 (0xc3) | Exported Function | 0x656a2450 | 0x00022450
`public: int __thiscall CDMNodeObj::IsVolumeSimple(void)` | 197 (0xc5) | Exported Function | 0x656a2560 | 0x00022560
`public: int __thiscall CDMNodeObj::OnlyContiguousExtendAllowed(void)` | 204 (0xcc) | Exported Function | 0x656a2700 | 0x00022700
`public: int __thiscall CDMNodeObj::VolumeContainsActiveRegion(void)` | 227 (0xe3) | Exported Function | 0x656a29f0 | 0x000229f0
`public: int __thiscall CDMScopeNodeCollection::GetScopeNode(long,class CDMScopeNode * *)` | 130 (0x82) | Exported Function | 0x65698740 | 0x00018740
`public: int __thiscall CDMSnapin::GetResultPane(long,class CDMResultPane * *)` | 128 (0x80) | Exported Function | 0x6569bd30 | 0x0001bd30
`public: int __thiscall CTaskData::FindFileSystem(__int64,struct filesysteminfo &)` | 56 (0x38) | Exported Function | 0x656a5670 | 0x00025670
`public: int __thiscall CTaskData::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * *)` | 58 (0x3a) | Exported Function | 0x656a5690 | 0x00025690
`public: int __thiscall CDMNodeObj::IsDiskEmpty(void)` | 162 (0xa2) | Exported Function | 0x656a1b10 | 0x00021b10
`public: int __thiscall CDMNodeObj::IsCurrSystemVolume(void)` | 161 (0xa1) | Exported Function | 0x656a1ab0 | 0x00021ab0
`public: int __thiscall CDMNodeObj::IsCurrBootVolume(void)` | 160 (0xa0) | Exported Function | 0x656a1a60 | 0x00021a60
`public: int __thiscall CDMNodeObj::IsActive(void)` | 156 (0x9c) | Exported Function | 0x656a1980 | 0x00021980
`public: int __thiscall CDMNodeObj::ContainsBootIniPartitionForWolfpack(void)` | 16 (0x10) | Exported Function | 0x6569d930 | 0x0001d930
`public: int __thiscall CDMNodeObj::ContainsBootVolumesNumberChange(__int64,int *)` | 17 (0x11) | Exported Function | 0x6569d9a0 | 0x0001d9a0
`public: int __thiscall CDMNodeObj::ContainsESPPartition(void)` | 18 (0x12) | Exported Function | 0x6569da20 | 0x0001da20
`public: int __thiscall CDMNodeObj::ContainsFVEPartition(void)` | 19 (0x13) | Exported Function | 0x6569da90 | 0x0001da90
`public: int __thiscall CDMNodeObj::ContainsLogicalDrvBootPartition(void)` | 20 (0x14) | Exported Function | 0x6569dac0 | 0x0001dac0
`public: int __thiscall CDMNodeObj::ContainsPageFile(void)` | 21 (0x15) | Exported Function | 0x6569db00 | 0x0001db00
`public: int __thiscall CDMNodeObj::ContainsRealSystemPartition(void)` | 22 (0x16) | Exported Function | 0x6569db30 | 0x0001db30
`public: int __thiscall CDMNodeObj::ContainsSubDiskNeedResync(void)` | 23 (0x17) | Exported Function | 0x6569db90 | 0x0001db90
`public: int __thiscall CDMNodeObj::ContainsSystemInformation(void)` | 24 (0x18) | Exported Function | 0x6569dc70 | 0x0001dc70
`public: int __thiscall CDMNodeObj::ContainsSystemPartition(void)` | 25 (0x19) | Exported Function | 0x6569dcc0 | 0x0001dcc0
`public: int __thiscall CDMNodeObj::EnhancedIsUpgradeable(class CTaskData *)` | 39 (0x27) | Exported Function | 0x6569dcf0 | 0x0001dcf0
`public: int __thiscall CDMNodeObj::GetDiskInfo(struct diskinfoex &)` | 79 (0x4f) | Exported Function | 0x6569e150 | 0x0001e150
`public: int __thiscall CTaskData::GetBootPort(void)` | 62 (0x3e) | Exported Function | 0x656a56e0 | 0x000256e0
`public: int __thiscall CDMNodeObj::GetDiskSpec(struct diskspec &)` | 81 (0x51) | Exported Function | 0x6569e190 | 0x0001e190
`public: int __thiscall CDMNodeObj::GetExtraRegionStatus(class CString &,int)` | 88 (0x58) | Exported Function | 0x6569e700 | 0x0001e700
`public: int __thiscall CDMNodeObj::GetFileSystemType(void)` | 92 (0x5c) | Exported Function | 0x6569ef90 | 0x0001ef90
`public: int __thiscall CDMNodeObj::GetImageNum(void)` | 99 (0x63) | Exported Function | 0x6569f110 | 0x0001f110
`public: int __thiscall CDMNodeObj::GetOfflineReasonText(class CString &)` | 115 (0x73) | Exported Function | 0x6569f6b0 | 0x0001f6b0
`public: int __thiscall CDMNodeObj::GetPatternRef(void)` | 121 (0x79) | Exported Function | 0x6569fa90 | 0x0001fa90
`public: int __thiscall CDMNodeObj::GetPort(void)` | 122 (0x7a) | Exported Function | 0x6569fb20 | 0x0001fb20
`public: int __thiscall CDMNodeObj::GetRegionInfo(struct regioninfoex &)` | 127 (0x7f) | Exported Function | 0x6569fbe0 | 0x0001fbe0
`public: int __thiscall CDMNodeObj::GetResultStringArray(class CStringArray &)` | 129 (0x81) | Exported Function | 0x656a0b60 | 0x00020b60
`public: int __thiscall CDMNodeObj::GetStatus(void)` | 140 (0x8c) | Exported Function | 0x656a0f90 | 0x00020f90
`public: int __thiscall CDMNodeObj::GetVolumeInfo(struct volumeinfo &)` | 149 (0x95) | Exported Function | 0x656a15d0 | 0x000215d0
`public: int __thiscall CDMNodeObj::GetVolumeStatus(class CString &)` | 150 (0x96) | Exported Function | 0x656a1610 | 0x00021610
`public: int __thiscall CDMNodeObj::HasExtendedPartition(void)` | 152 (0x98) | Exported Function | 0x656a1920 | 0x00021920
`public: int __thiscall CDMNodeObj::GetDiskStatus(class CString &)` | 82 (0x52) | Exported Function | 0x6569e1e0 | 0x0001e1e0
`public: void __thiscall CTaskData::SetUIState(unsigned long)` | 218 (0xda) | Exported Function | 0x656a6450 | 0x00026450


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/f8871ce55482621b94895498ff742e22d5867ad1ca9ce063a3a44854bac97081/detection/





MIT License. Copyright (c) 2020 Strontic.


