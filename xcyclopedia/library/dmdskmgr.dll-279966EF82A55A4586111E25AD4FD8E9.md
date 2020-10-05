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

Function Name | Ordinal | Type
-- | -- | --
`public: void __thiscall CContextMenu::PopUpInit(class CDMNodeObj *,int &,int &,int)` | 205 | Exported Function
`public: void __thiscall CContextMenu::DoRevertToNT4(long,int)` | 37 | Exported Function
`public: void __thiscall CContextMenu::DoDelete(long)` | 36 | Exported Function
`public: void __thiscall CContextMenu::RefreshFileSys(long)` | 210 | Exported Function
`public: void __thiscall CDataCache::AddLDMObjMapEntry(struct _LDM_OBJ_MAP_ENTRY *)` | 6 | Exported Function
`public: void __thiscall CDataCache::AddFileSystemInfoToListAndMap(unsigned long,struct filesysteminfo *)` | 5 | Exported Function
`public: void __thiscall CDataCache::AddFileSystemInfoToCache(unsigned long,struct filesysteminfo *)` | 4 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetNumRegions(void)` | 112 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetNumMembers(void)` | 111 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetMaxPartitionCount(void)` | 107 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetPrimaryPartitionCount(void)` | 123 | Exported Function
`public: virtual __thiscall CDataCache::~CDataCache(void)` | 3 | Exported Function
`public: unsigned short * __thiscall CDataCache::FindDeviceInstanceId(__int64)` | 51 | Exported Function
`public: unsigned long __thiscall CTaskData::GetUIState(void)` | 143 | Exported Function
`public: void __thiscall CDataCache::AddRegionToVolumeMemberList(class CDMNodeObj *)` | 7 | Exported Function
`public: void __thiscall CDataCache::EnumNTFSwithDriveLetter(int *,unsigned short * *)` | 43 | Exported Function
`public: void __thiscall CDataCache::DeleteRegionFromVolumeMemberList(class CDMNodeObj *)` | 34 | Exported Function
`public: void __thiscall CDataCache::DeleteLists(void)` | 33 | Exported Function
`public: void __thiscall CDataCache::FillDeviceInstanceId(unsigned short *,unsigned short *)` | 47 | Exported Function
`public: void __thiscall CDataCache::PopulateEncapsulateData(struct ENCAPSULATE_DATA *)` | 207 | Exported Function
`public: void __thiscall CDataCache::PopulateDiskGroupData(struct DISK_GROUP_DATA *)` | 206 | Exported Function
`public: void __thiscall CDataCache::GetFileSystemTypes(unsigned long &,struct ifilesysteminfo * *)` | 93 | Exported Function
`public: void __thiscall CDataCache::CreateDiskList(void)` | 26 | Exported Function
`public: void __thiscall CDataCache::AdjustVolumeCountInLegendList(enum _VOLUMELAYOUT,int,class CTaskData *)` | 10 | Exported Function
`public: void __thiscall CDataCache::AdjustRegionCountInLegendList(enum _REGIONTYPE,int,class CTaskData *)` | 9 | Exported Function
`public: void __thiscall CDataCache::CreateShortDiskName(struct diskinfoex &)` | 29 | Exported Function
`public: void __thiscall CDataCache::DeleteEncapsulateData(struct ENCAPSULATE_DATA *)` | 32 | Exported Function
`public: void __thiscall CDataCache::DeleteDiskGroupData(struct DISK_GROUP_DATA *)` | 31 | Exported Function
`public: void __thiscall CDataCache::CreateVolumeList(void)` | 30 | Exported Function
`public: int __thiscall CTaskData::SupportGpt(void)` | 222 | Exported Function
`public: int __thiscall CTaskData::IsWolfpack(void)` | 199 | Exported Function
`public: int __thiscall CTaskData::IsSecureSystemPartition(void)` | 192 | Exported Function
`public: long __thiscall CContextMenu::Command(long,struct IDataObject *,long)` | 13 | Exported Function
`public: long __thiscall CDMNodeObj::GetVolumeFileSystemTypes(unsigned long &,struct ilhfilesysteminfo * *)` | 148 | Exported Function
`public: long __thiscall CDMNodeObj::GetFlags(void)` | 95 | Exported Function
`public: long __thiscall CContextMenu::ShowContextMenu(class CWnd *,long,long,long)` | 220 | Exported Function
`public: int __thiscall CTaskData::IsLocalMachine(void)` | 177 | Exported Function
`public: int __thiscall CTaskData::IsEfi(void)` | 169 | Exported Function
`public: int __thiscall CTaskData::IsAlpha(void)` | 158 | Exported Function
`public: int __thiscall CTaskData::IsNEC_98Server(void)` | 182 | Exported Function
`public: int __thiscall CTaskData::IsPreLonghornVdsVersion(void)` | 189 | Exported Function
`public: int __thiscall CTaskData::IsPostLonghornVdsVersion(void)` | 187 | Exported Function
`public: int __thiscall CTaskData::IsNTServer(void)` | 183 | Exported Function
`public: long __thiscall CDMNodeObj::IsConvertSuccess(int)` | 159 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetDeviceAttributes(void)` | 66 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetColorRef(void)` | 63 | Exported Function
`public: unsigned long __thiscall CDataCache::GetVolumeCount(void)` | 147 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetDeviceState(void)` | 67 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetLogicalDriveCount(void)` | 103 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetExtendedRegionColor(void)` | 87 | Exported Function
`public: unsigned long __thiscall CDMNodeObj::GetDeviceType(void)` | 68 | Exported Function
`public: short __thiscall CDMNodeObj::GetIVolumeClientVersion(void)` | 96 | Exported Function
`public: long __thiscall CDMNodeObj::IsVolumeArrived(__int64,enum _LAYOUT_TYPES)` | 196 | Exported Function
`public: long __thiscall CDMNodeObj::IsExtendedPartitionCreated(void)` | 170 | Exported Function
`public: short __thiscall CTaskData::GetIVolumeClientVersion(void)` | 97 | Exported Function
`public: unsigned long __thiscall CDataCache::GetDiskCount(void)` | 78 | Exported Function
`public: unsigned int __thiscall CDMNodeObj::GetIconId(int)` | 98 | Exported Function
`public: struct HWND__ * __thiscall CDMComponentData::GetMMCWindow(void)` | 105 | Exported Function
`public: void __thiscall CTaskData::EnumNTFSwithDriveLetter(int *,unsigned short * *)` | 44 | Exported Function
`public: void __thiscall CTaskData::EnumDisks(unsigned long &,long * *)` | 41 | Exported Function
`public: void __thiscall CDMSnapin::UpDateConsoleView(long)` | 226 | Exported Function
`public: void __thiscall CTaskData::EnumVolumes(unsigned long &,long * *)` | 46 | Exported Function
`public: void __thiscall CTaskData::FindDriveLetter(__int64,unsigned short &)` | 54 | Exported Function
`public: void __thiscall CTaskData::FilterCookiesBigEnoughForRAID5Repair(unsigned long &,long *,long * *,__int64,class CDMNodeObj *)` | 49 | Exported Function
`public: void __thiscall CTaskData::FilterCookiesBigEnoughForFTRepair(unsigned long &,long *,long * *,__int64,class CDMNodeObj *)` | 48 | Exported Function
`public: void __thiscall CDMNodeObj::MarkDiskForLastVolume(class CDMNodeObj *)` | 202 | Exported Function
`public: void __thiscall CDMNodeObj::GetStorageType(class CString &,int)` | 142 | Exported Function
`public: void __thiscall CDMNodeObj::GetSizeString(class CString &)` | 138 | Exported Function
`public: void __thiscall CDMNodeObj::MarkDisksForLastVolume(void)` | 203 | Exported Function
`public: void __thiscall CDMSnapin::SetDescriptionBarText(long)` | 212 | Exported Function
`public: void __thiscall CDMNodeObj::SetFSId(__int64)` | 215 | Exported Function
`public: void __thiscall CDMNodeObj::RecalculateSpace(void)` | 208 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookies(unsigned long &,long * *,int,unsigned long,int)` | 70 | Exported Function
`public: void __thiscall CTaskData::GetFileSystemTypes(unsigned long &,struct ifilesysteminfo * *)` | 94 | Exported Function
`public: void __thiscall CTaskData::GetDriveLetters(short &,unsigned short * *,unsigned short)` | 86 | Exported Function
`public: void __thiscall CTaskData::GetDiskInfoFromVolCookie(long,int &,unsigned long &,long * *,unsigned long,int)` | 80 | Exported Function
`public: void __thiscall CTaskData::GetMinMaxPartitionSizes(long,__int64 &,__int64 &)` | 109 | Exported Function
`public: void __thiscall CTaskData::SetUIState(unsigned long)` | 218 | Exported Function
`public: void __thiscall CTaskData::GetRegionColorStructPtr(struct _REGION_COLORS * *,int &)` | 126 | Exported Function
`public: void __thiscall CTaskData::GetOtherDisksFromVolCookie(long,unsigned long &,long * *)` | 116 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesForExtendVolume(long,unsigned long &,long * *)` | 73 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesForCreateVolume(unsigned long &,long * *)` | 72 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesForAddMirror(long,unsigned long &,long * *)` | 71 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesForSig(unsigned long &,long * *)` | 74 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesWithFreeSpace(unsigned long &,long * *)` | 77 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesToEncap(unsigned long &,long * *)` | 76 | Exported Function
`public: void __thiscall CTaskData::GetDiskCookiesForUpgrade(unsigned long &,long * *)` | 75 | Exported Function
`public: void __thiscall CDMComponentData::ReloadData(class CDMScopeNode *)` | 211 | Exported Function
`public: void __thiscall CDMComponentData::RefreshDiskView(class CDMScopeNode *)` | 209 | Exported Function
`public: void __thiscall CDMComponentData::LoadData(class CDMScopeNode *,long)` | 200 | Exported Function
`public: void __thiscall CDMComponentData::SetOcxViewType(class CDMScopeNode *)` | 216 | Exported Function
`public: void __thiscall CDMNodeObj::EnumDiskRegions(long * *,long &)` | 40 | Exported Function
`public: void __thiscall CDMComponentData::UIStateChange(class CDMScopeNode *,unsigned long)` | 225 | Exported Function
`public: void __thiscall CDMComponentData::SetOcxViewTypeForce(class CDMScopeNode *)` | 217 | Exported Function
`public: void __thiscall CDataCache::SetVolumeList(struct volumeinfo *,unsigned long,class CTaskData *)` | 219 | Exported Function
`public: void __thiscall CDataCache::SetDriveLetterInUse(unsigned short,int)` | 214 | Exported Function
`public: void __thiscall CDataCache::SetDiskList(struct diskinfoex *,unsigned long)` | 213 | Exported Function
`public: void __thiscall CDMComponentData::AddRow(class CDMScopeNode *,long)` | 8 | Exported Function
`public: void __thiscall CDMComponentData::EmptyOcxViewData(class CDMScopeNode *)` | 38 | Exported Function
`public: void __thiscall CDMComponentData::DeleteRow(class CDMScopeNode *,long)` | 35 | Exported Function
`public: void __thiscall CDMComponentData::ChangeRow(class CDMScopeNode *,long)` | 12 | Exported Function
`public: void __thiscall CDMNodeObj::EnumFirstVolumeMember(long &,long &)` | 42 | Exported Function
`public: void __thiscall CDMNodeObj::GetObjectId(__int64 &)` | 113 | Exported Function
`public: void __thiscall CDMNodeObj::GetName(class CString &)` | 110 | Exported Function
`public: void __thiscall CDMNodeObj::GetMaxAdjustedFreeSize(__int64 &)` | 106 | Exported Function
`public: void __thiscall CDMNodeObj::GetPartitionStyleString(class CString &,int)` | 120 | Exported Function
`public: void __thiscall CDMNodeObj::GetSizeMB(__int64 &)` | 137 | Exported Function
`public: void __thiscall CDMNodeObj::GetSize(__int64 &,int)` | 136 | Exported Function
`public: void __thiscall CDMNodeObj::GetShortName(class CString &)` | 134 | Exported Function
`public: void __thiscall CDMNodeObj::GetDriveLetter(unsigned short &)` | 84 | Exported Function
`public: void __thiscall CDMNodeObj::GetDiskTypeName(class CString &)` | 83 | Exported Function
`public: void __thiscall CDMNodeObj::EnumVolumeMembers(long * *,long &)` | 45 | Exported Function
`public: void __thiscall CDMNodeObj::GetFileSystemLabel(class CString &)` | 89 | Exported Function
`public: void __thiscall CDMNodeObj::GetLongName(class CString &,int)` | 104 | Exported Function
`public: void __thiscall CDMNodeObj::GetFileSystemSize(long &)` | 91 | Exported Function
`public: void __thiscall CDMNodeObj::GetFileSystemName(class CString &)` | 90 | Exported Function
`public: int __thiscall CTaskData::HasNTFSwithDriveLetter(void)` | 154 | Exported Function
`public: int __thiscall CDataCache::FindFileSystem(__int64,struct filesysteminfo &)` | 55 | Exported Function
`public: int __thiscall CDataCache::FindDriveLetter(__int64,unsigned short &)` | 53 | Exported Function
`public: int __thiscall CDataCache::FindDiskPtrFromDiskId(__int64,class CDMNodeObj * *)` | 52 | Exported Function
`public: int __thiscall CDataCache::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * *)` | 57 | Exported Function
`public: int __thiscall CDataCache::HasNTFSwithDriveLetter(void)` | 153 | Exported Function
`public: int __thiscall CDataCache::GetBootPort(void)` | 61 | Exported Function
`public: int __thiscall CDataCache::FindRegionPtrOnDiskFromRegionId(class CDMNodeObj *,__int64,class CDMNodeObj * *,struct __POSITION * &)` | 59 | Exported Function
`public: class CWnd * __thiscall CTaskData::GetOcxFrameCWndPtr(void)` | 114 | Exported Function
`public: class CString __thiscall CTaskData::GetServerName(void)` | 133 | Exported Function
`public: class CString __thiscall CDataCache::GetServerName(void)` | 132 | Exported Function
`public: enum _LAYOUT_TYPES __thiscall CDMNodeObj::GetLayoutType(void)` | 101 | Exported Function
`public: int __thiscall CDataCache::FindCookieAndRemoveFromList(long,class CList<class CDMNodeObj *,class CDMNodeObj *> *)` | 50 | Exported Function
`public: enum _STORAGE_TYPES __thiscall CDMNodeObj::GetStorageType(void)` | 141 | Exported Function
`public: enum _PARTITIONSTYLE __thiscall CDMNodeObj::GetPartitionStyle(void)` | 119 | Exported Function
`public: int __thiscall CDataCache::HasVMDisk(void)` | 155 | Exported Function
`public: int __thiscall CDataCache::SupportMirror(void)` | 223 | Exported Function
`public: int __thiscall CDataCache::SupportGpt(void)` | 221 | Exported Function
`public: int __thiscall CDataCache::IsWolfpack(void)` | 198 | Exported Function
`public: int __thiscall CDataCache::SupportRaid5(void)` | 224 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsActivePartition(void)` | 14 | Exported Function
`public: int __thiscall CDMNodeObj::CanHaveGPT(void)` | 11 | Exported Function
`public: int __thiscall CDMComponentData::GetScopeNodeForResultPane(long,class CDMScopeNode * *)` | 131 | Exported Function
`public: int __thiscall CDataCache::IsEfi(void)` | 168 | Exported Function
`public: int __thiscall CDataCache::IsDynamic1394(void)` | 165 | Exported Function
`public: int __thiscall CDataCache::IsAlpha(void)` | 157 | Exported Function
`public: int __thiscall CDataCache::IsNEC_98Server(void)` | 181 | Exported Function
`public: int __thiscall CDataCache::IsPreLonghornVdsVersion(void)` | 188 | Exported Function
`public: int __thiscall CDataCache::IsPostLonghornVdsVersion(void)` | 186 | Exported Function
`public: int __thiscall CDataCache::IsPersonalOrLapTopServer(void)` | 185 | Exported Function
`protected: void __thiscall CDataCache::GetDiskCookies(unsigned long &,long * *)` | 69 | Exported Function
`namecmp` | 233 | Exported Function
`LoadPropertyPageData` | 201 | Exported Function
`protected: void __thiscall CDataCache::GetDriveLetters(short &,unsigned short * *,unsigned short)` | 85 | Exported Function
`public: __int64 __thiscall CDataCache::GetLastKnownState(__int64)` | 100 | Exported Function
`protected: void __thiscall CDataCache::GetVolumeCookies(unsigned long &,long * *)` | 146 | Exported Function
`protected: void __thiscall CDataCache::GetMinMaxPartitionSizes(long,__int64 &,__int64 &)` | 108 | Exported Function
`DllCanUnloadNow` | 230 | Exported Function
`CookieSort` | 229 | Exported Function
`CompareDiskNames` | 228 | Exported Function
`DllGetClassObject` | 231 | Exported Function
`IsRequestPending` | 190 | Exported Function
`GetPropertyPageData` | 124 | Exported Function
`DllRegisterServer` | 232 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetLdmObjectId(void)` | 102 | Exported Function
`public: class CDMNodeObj * __thiscall CDataCache::CreateRegionNodeObj(class CDMNodeObj *,struct regioninfoex *)` | 28 | Exported Function
`public: class CDMNodeObj * __thiscall CDataCache::CreateNodeObjAndAddToMap(int,enum _NODEOBJ_TYPES,class CDataCache *,void *,__int64)` | 27 | Exported Function
`public: class CDMComponentData * __thiscall CDataCache::GetComponentData(void)` | 64 | Exported Function
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetParentDiskPtr(void)` | 117 | Exported Function
`public: class CDMNodeObj * __thiscall CTaskData::GetDMDataObjPtrFromId(__int64)` | 65 | Exported Function
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetRegionByOffset(__int64)` | 125 | Exported Function
`public: class CDMNodeObj * __thiscall CDMNodeObj::GetParentVolumePtr(void)` | 118 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetUnallocSpace(int)` | 144 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetStartOffset(void)` | 139 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetShrinkableSizeInMB(void)` | 135 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetUsableContiguousSpaceInMB(void)` | 145 | Exported Function
`public: __thiscall CDMNodeObj::~CDMNodeObj(void)` | 2 | Exported Function
`public: __thiscall CDataCache::CDataCache(void)` | 1 | Exported Function
`public: __int64 __thiscall CDMNodeObj::GetVolumeTotalSizeMB(void)` | 151 | Exported Function
`public: int __thiscall CDMNodeObj::IsFTVolume(void)` | 171 | Exported Function
`public: int __thiscall CDMNodeObj::IsFreeSpaceFollowed(__int64)` | 174 | Exported Function
`public: int __thiscall CDMNodeObj::IsFirstFreeRegion(void)` | 173 | Exported Function
`public: int __thiscall CDMNodeObj::IsHiddenRegion(void)` | 175 | Exported Function
`public: int __thiscall CDMNodeObj::IsMember(class CDMNodeObj *)` | 179 | Exported Function
`public: int __thiscall CDMNodeObj::IsMbrEEPartition(void)` | 178 | Exported Function
`public: int __thiscall CDMNodeObj::IsInFlux(void)` | 176 | Exported Function
`public: int __thiscall CDMNodeObj::IsDiskOffline(void)` | 163 | Exported Function
`public: int __thiscall CDMNodeObj::IsDiskEmpty(void)` | 162 | Exported Function
`public: int __thiscall CDMNodeObj::IsCurrSystemVolume(void)` | 161 | Exported Function
`public: int __thiscall CDMNodeObj::IsDiskReadOnly(void)` | 164 | Exported Function
`public: int __thiscall CDMNodeObj::IsFakeVolume(void)` | 172 | Exported Function
`public: int __thiscall CDMNodeObj::IsESPPartition(void)` | 167 | Exported Function
`public: int __thiscall CDMNodeObj::IsEECoveredGPTDisk(void)` | 166 | Exported Function
`public: int __thiscall CDMNodeObj::IsNEC_98Disk(void)` | 180 | Exported Function
`public: int __thiscall CDMSnapin::GetResultPane(long,class CDMResultPane * *)` | 128 | Exported Function
`public: int __thiscall CDMScopeNodeCollection::GetScopeNode(long,class CDMScopeNode * *)` | 130 | Exported Function
`public: int __thiscall CDMNodeObj::VolumeContainsActiveRegion(void)` | 227 | Exported Function
`public: int __thiscall CTaskData::FindFileSystem(__int64,struct filesysteminfo &)` | 56 | Exported Function
`public: int __thiscall CTaskData::GetBootPort(void)` | 62 | Exported Function
`public: int __thiscall CTaskData::GetAssignedDriveLetter(long,unsigned short &)` | 60 | Exported Function
`public: int __thiscall CTaskData::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * *)` | 58 | Exported Function
`public: int __thiscall CDMNodeObj::IsSpacesProtectivePartition(void)` | 193 | Exported Function
`public: int __thiscall CDMNodeObj::IsRevertable(void)` | 191 | Exported Function
`public: int __thiscall CDMNodeObj::IsOemPartition(void)` | 184 | Exported Function
`public: int __thiscall CDMNodeObj::IsUnknownPartition(void)` | 194 | Exported Function
`public: int __thiscall CDMNodeObj::OnlyContiguousExtendAllowed(void)` | 204 | Exported Function
`public: int __thiscall CDMNodeObj::IsVolumeSimple(void)` | 197 | Exported Function
`public: int __thiscall CDMNodeObj::IsUpgradeable(void)` | 195 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsSystemInformation(void)` | 24 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsSubDiskNeedResync(void)` | 23 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsRealSystemPartition(void)` | 22 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsSystemPartition(void)` | 25 | Exported Function
`public: int __thiscall CDMNodeObj::GetDiskSpec(struct diskspec &)` | 81 | Exported Function
`public: int __thiscall CDMNodeObj::GetDiskInfo(struct diskinfoex &)` | 79 | Exported Function
`public: int __thiscall CDMNodeObj::EnhancedIsUpgradeable(class CTaskData *)` | 39 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsBootVolumesNumberChange(__int64,int *)` | 17 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsBootIniPartitionForWolfpack(void)` | 16 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsBootIniPartition(void)` | 15 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsESPPartition(void)` | 18 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsPageFile(void)` | 21 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsLogicalDrvBootPartition(void)` | 20 | Exported Function
`public: int __thiscall CDMNodeObj::ContainsFVEPartition(void)` | 19 | Exported Function
`public: int __thiscall CDMNodeObj::GetDiskStatus(class CString &)` | 82 | Exported Function
`public: int __thiscall CDMNodeObj::GetVolumeInfo(struct volumeinfo &)` | 149 | Exported Function
`public: int __thiscall CDMNodeObj::GetStatus(void)` | 140 | Exported Function
`public: int __thiscall CDMNodeObj::GetResultStringArray(class CStringArray &)` | 129 | Exported Function
`public: int __thiscall CDMNodeObj::GetVolumeStatus(class CString &)` | 150 | Exported Function
`public: int __thiscall CDMNodeObj::IsCurrBootVolume(void)` | 160 | Exported Function
`public: int __thiscall CDMNodeObj::IsActive(void)` | 156 | Exported Function
`public: int __thiscall CDMNodeObj::HasExtendedPartition(void)` | 152 | Exported Function
`public: int __thiscall CDMNodeObj::GetImageNum(void)` | 99 | Exported Function
`public: int __thiscall CDMNodeObj::GetFileSystemType(void)` | 92 | Exported Function
`public: int __thiscall CDMNodeObj::GetExtraRegionStatus(class CString &,int)` | 88 | Exported Function
`public: int __thiscall CDMNodeObj::GetOfflineReasonText(class CString &)` | 115 | Exported Function
`public: int __thiscall CDMNodeObj::GetRegionInfo(struct regioninfoex &)` | 127 | Exported Function
`public: int __thiscall CDMNodeObj::GetPort(void)` | 122 | Exported Function
`public: int __thiscall CDMNodeObj::GetPatternRef(void)` | 121 | Exported Function


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


