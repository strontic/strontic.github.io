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

Function Name | Ordinal | Type
-- | -- | --
`public: void __cdecl CContextMenu::PopUpInit(class CDMNodeObj * __ptr64,int & __ptr64,int & __ptr64,int) __ptr64` | 205 | Exported Function
`public: void __cdecl CContextMenu::DoRevertToNT4(__int64,int) __ptr64` | 37 | Exported Function
`public: void __cdecl CContextMenu::DoDelete(__int64) __ptr64` | 36 | Exported Function
`public: void __cdecl CContextMenu::RefreshFileSys(__int64) __ptr64` | 210 | Exported Function
`public: void __cdecl CDataCache::AddLDMObjMapEntry(struct _LDM_OBJ_MAP_ENTRY * __ptr64) __ptr64` | 6 | Exported Function
`public: void __cdecl CDataCache::AddFileSystemInfoToListAndMap(unsigned long,struct filesysteminfo * __ptr64) __ptr64` | 5 | Exported Function
`public: void __cdecl CDataCache::AddFileSystemInfoToCache(unsigned long,struct filesysteminfo * __ptr64) __ptr64` | 4 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetNumRegions(void) __ptr64` | 112 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetNumMembers(void) __ptr64` | 111 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetMaxPartitionCount(void) __ptr64` | 107 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetPrimaryPartitionCount(void) __ptr64` | 123 | Exported Function
`public: virtual __cdecl CDataCache::~CDataCache(void) __ptr64` | 3 | Exported Function
`public: unsigned short * __ptr64 __cdecl CDataCache::FindDeviceInstanceId(__int64) __ptr64` | 51 | Exported Function
`public: unsigned long __cdecl CTaskData::GetUIState(void) __ptr64` | 143 | Exported Function
`public: void __cdecl CDataCache::AddRegionToVolumeMemberList(class CDMNodeObj * __ptr64) __ptr64` | 7 | Exported Function
`public: void __cdecl CDataCache::EnumNTFSwithDriveLetter(int * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 43 | Exported Function
`public: void __cdecl CDataCache::DeleteRegionFromVolumeMemberList(class CDMNodeObj * __ptr64) __ptr64` | 34 | Exported Function
`public: void __cdecl CDataCache::DeleteLists(void) __ptr64` | 33 | Exported Function
`public: void __cdecl CDataCache::FillDeviceInstanceId(unsigned short * __ptr64,unsigned short * __ptr64) __ptr64` | 47 | Exported Function
`public: void __cdecl CDataCache::PopulateEncapsulateData(struct ENCAPSULATE_DATA * __ptr64) __ptr64` | 207 | Exported Function
`public: void __cdecl CDataCache::PopulateDiskGroupData(struct DISK_GROUP_DATA * __ptr64) __ptr64` | 206 | Exported Function
`public: void __cdecl CDataCache::GetFileSystemTypes(unsigned long & __ptr64,struct ifilesysteminfo * __ptr64 * __ptr64) __ptr64` | 93 | Exported Function
`public: void __cdecl CDataCache::CreateDiskList(void) __ptr64` | 26 | Exported Function
`public: void __cdecl CDataCache::AdjustVolumeCountInLegendList(enum _VOLUMELAYOUT,int,class CTaskData * __ptr64) __ptr64` | 10 | Exported Function
`public: void __cdecl CDataCache::AdjustRegionCountInLegendList(enum _REGIONTYPE,int,class CTaskData * __ptr64) __ptr64` | 9 | Exported Function
`public: void __cdecl CDataCache::CreateShortDiskName(struct diskinfoex & __ptr64) __ptr64` | 29 | Exported Function
`public: void __cdecl CDataCache::DeleteEncapsulateData(struct ENCAPSULATE_DATA * __ptr64) __ptr64` | 32 | Exported Function
`public: void __cdecl CDataCache::DeleteDiskGroupData(struct DISK_GROUP_DATA * __ptr64) __ptr64` | 31 | Exported Function
`public: void __cdecl CDataCache::CreateVolumeList(void) __ptr64` | 30 | Exported Function
`public: int __cdecl CTaskData::SupportGpt(void) __ptr64` | 222 | Exported Function
`public: int __cdecl CTaskData::IsWolfpack(void) __ptr64` | 199 | Exported Function
`public: int __cdecl CTaskData::IsSecureSystemPartition(void) __ptr64` | 192 | Exported Function
`public: long __cdecl CContextMenu::Command(long,struct IDataObject * __ptr64,__int64) __ptr64` | 13 | Exported Function
`public: long __cdecl CDMNodeObj::GetVolumeFileSystemTypes(unsigned long & __ptr64,struct ilhfilesysteminfo * __ptr64 * __ptr64) __ptr64` | 148 | Exported Function
`public: long __cdecl CDMNodeObj::GetFlags(void) __ptr64` | 95 | Exported Function
`public: long __cdecl CContextMenu::ShowContextMenu(class CWnd * __ptr64,long,long,__int64) __ptr64` | 220 | Exported Function
`public: int __cdecl CTaskData::IsLocalMachine(void) __ptr64` | 177 | Exported Function
`public: int __cdecl CTaskData::IsEfi(void) __ptr64` | 169 | Exported Function
`public: int __cdecl CTaskData::IsAlpha(void) __ptr64` | 158 | Exported Function
`public: int __cdecl CTaskData::IsNEC_98Server(void) __ptr64` | 182 | Exported Function
`public: int __cdecl CTaskData::IsPreLonghornVdsVersion(void) __ptr64` | 189 | Exported Function
`public: int __cdecl CTaskData::IsPostLonghornVdsVersion(void) __ptr64` | 187 | Exported Function
`public: int __cdecl CTaskData::IsNTServer(void) __ptr64` | 183 | Exported Function
`public: long __cdecl CDMNodeObj::IsConvertSuccess(int) __ptr64` | 159 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetDeviceAttributes(void) __ptr64` | 66 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetColorRef(void) __ptr64` | 63 | Exported Function
`public: unsigned long __cdecl CDataCache::GetVolumeCount(void) __ptr64` | 147 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetDeviceState(void) __ptr64` | 67 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetLogicalDriveCount(void) __ptr64` | 103 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetExtendedRegionColor(void) __ptr64` | 87 | Exported Function
`public: unsigned long __cdecl CDMNodeObj::GetDeviceType(void) __ptr64` | 68 | Exported Function
`public: short __cdecl CDMNodeObj::GetIVolumeClientVersion(void) __ptr64` | 96 | Exported Function
`public: long __cdecl CDMNodeObj::IsVolumeArrived(__int64,enum _LAYOUT_TYPES) __ptr64` | 196 | Exported Function
`public: long __cdecl CDMNodeObj::IsExtendedPartitionCreated(void) __ptr64` | 170 | Exported Function
`public: short __cdecl CTaskData::GetIVolumeClientVersion(void) __ptr64` | 97 | Exported Function
`public: unsigned long __cdecl CDataCache::GetDiskCount(void) __ptr64` | 78 | Exported Function
`public: unsigned int __cdecl CDMNodeObj::GetIconId(int) __ptr64` | 98 | Exported Function
`public: struct HWND__ * __ptr64 __cdecl CDMComponentData::GetMMCWindow(void) __ptr64` | 105 | Exported Function
`public: void __cdecl CTaskData::EnumNTFSwithDriveLetter(int * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 44 | Exported Function
`public: void __cdecl CTaskData::EnumDisks(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 41 | Exported Function
`public: void __cdecl CDMSnapin::UpDateConsoleView(__int64) __ptr64` | 226 | Exported Function
`public: void __cdecl CTaskData::EnumVolumes(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 46 | Exported Function
`public: void __cdecl CTaskData::FindDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 54 | Exported Function
`public: void __cdecl CTaskData::FilterCookiesBigEnoughForRAID5Repair(unsigned long & __ptr64,__int64 * __ptr64,__int64 * __ptr64 * __ptr64,__int64,class CDMNodeObj * __ptr64) __ptr64` | 49 | Exported Function
`public: void __cdecl CTaskData::FilterCookiesBigEnoughForFTRepair(unsigned long & __ptr64,__int64 * __ptr64,__int64 * __ptr64 * __ptr64,__int64,class CDMNodeObj * __ptr64) __ptr64` | 48 | Exported Function
`public: void __cdecl CDMNodeObj::MarkDiskForLastVolume(class CDMNodeObj * __ptr64) __ptr64` | 202 | Exported Function
`public: void __cdecl CDMNodeObj::GetStorageType(class CString & __ptr64,int) __ptr64` | 142 | Exported Function
`public: void __cdecl CDMNodeObj::GetSizeString(class CString & __ptr64) __ptr64` | 138 | Exported Function
`public: void __cdecl CDMNodeObj::MarkDisksForLastVolume(void) __ptr64` | 203 | Exported Function
`public: void __cdecl CDMSnapin::SetDescriptionBarText(__int64) __ptr64` | 212 | Exported Function
`public: void __cdecl CDMNodeObj::SetFSId(__int64) __ptr64` | 215 | Exported Function
`public: void __cdecl CDMNodeObj::RecalculateSpace(void) __ptr64` | 208 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64,int,unsigned long,int) __ptr64` | 70 | Exported Function
`public: void __cdecl CTaskData::GetFileSystemTypes(unsigned long & __ptr64,struct ifilesysteminfo * __ptr64 * __ptr64) __ptr64` | 94 | Exported Function
`public: void __cdecl CTaskData::GetDriveLetters(short & __ptr64,unsigned short * __ptr64 * __ptr64,unsigned short) __ptr64` | 86 | Exported Function
`public: void __cdecl CTaskData::GetDiskInfoFromVolCookie(__int64,int & __ptr64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64,unsigned long,int) __ptr64` | 80 | Exported Function
`public: void __cdecl CTaskData::GetMinMaxPartitionSizes(__int64,__int64 & __ptr64,__int64 & __ptr64) __ptr64` | 109 | Exported Function
`public: void __cdecl CTaskData::SetUIState(unsigned long) __ptr64` | 218 | Exported Function
`public: void __cdecl CTaskData::GetRegionColorStructPtr(struct _REGION_COLORS * __ptr64 * __ptr64,int & __ptr64) __ptr64` | 126 | Exported Function
`public: void __cdecl CTaskData::GetOtherDisksFromVolCookie(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 116 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesForExtendVolume(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 73 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesForCreateVolume(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 72 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesForAddMirror(__int64,unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 71 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesForSig(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 74 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesWithFreeSpace(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 77 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesToEncap(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 76 | Exported Function
`public: void __cdecl CTaskData::GetDiskCookiesForUpgrade(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 75 | Exported Function
`public: void __cdecl CDMComponentData::ReloadData(class CDMScopeNode * __ptr64) __ptr64` | 211 | Exported Function
`public: void __cdecl CDMComponentData::RefreshDiskView(class CDMScopeNode * __ptr64) __ptr64` | 209 | Exported Function
`public: void __cdecl CDMComponentData::LoadData(class CDMScopeNode * __ptr64,long) __ptr64` | 200 | Exported Function
`public: void __cdecl CDMComponentData::SetOcxViewType(class CDMScopeNode * __ptr64) __ptr64` | 216 | Exported Function
`public: void __cdecl CDMNodeObj::EnumDiskRegions(__int64 * __ptr64 * __ptr64,long & __ptr64) __ptr64` | 40 | Exported Function
`public: void __cdecl CDMComponentData::UIStateChange(class CDMScopeNode * __ptr64,unsigned long) __ptr64` | 225 | Exported Function
`public: void __cdecl CDMComponentData::SetOcxViewTypeForce(class CDMScopeNode * __ptr64) __ptr64` | 217 | Exported Function
`public: void __cdecl CDataCache::SetVolumeList(struct volumeinfo * __ptr64,unsigned long,class CTaskData * __ptr64) __ptr64` | 219 | Exported Function
`public: void __cdecl CDataCache::SetDriveLetterInUse(unsigned short,int) __ptr64` | 214 | Exported Function
`public: void __cdecl CDataCache::SetDiskList(struct diskinfoex * __ptr64,unsigned long) __ptr64` | 213 | Exported Function
`public: void __cdecl CDMComponentData::AddRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 8 | Exported Function
`public: void __cdecl CDMComponentData::EmptyOcxViewData(class CDMScopeNode * __ptr64) __ptr64` | 38 | Exported Function
`public: void __cdecl CDMComponentData::DeleteRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 35 | Exported Function
`public: void __cdecl CDMComponentData::ChangeRow(class CDMScopeNode * __ptr64,__int64) __ptr64` | 12 | Exported Function
`public: void __cdecl CDMNodeObj::EnumFirstVolumeMember(__int64 & __ptr64,long & __ptr64) __ptr64` | 42 | Exported Function
`public: void __cdecl CDMNodeObj::GetObjectId(__int64 & __ptr64) __ptr64` | 113 | Exported Function
`public: void __cdecl CDMNodeObj::GetName(class CString & __ptr64) __ptr64` | 110 | Exported Function
`public: void __cdecl CDMNodeObj::GetMaxAdjustedFreeSize(__int64 & __ptr64) __ptr64` | 106 | Exported Function
`public: void __cdecl CDMNodeObj::GetPartitionStyleString(class CString & __ptr64,int) __ptr64` | 120 | Exported Function
`public: void __cdecl CDMNodeObj::GetSizeMB(__int64 & __ptr64) __ptr64` | 137 | Exported Function
`public: void __cdecl CDMNodeObj::GetSize(__int64 & __ptr64,int) __ptr64` | 136 | Exported Function
`public: void __cdecl CDMNodeObj::GetShortName(class CString & __ptr64) __ptr64` | 134 | Exported Function
`public: void __cdecl CDMNodeObj::GetDriveLetter(unsigned short & __ptr64) __ptr64` | 84 | Exported Function
`public: void __cdecl CDMNodeObj::GetDiskTypeName(class CString & __ptr64) __ptr64` | 83 | Exported Function
`public: void __cdecl CDMNodeObj::EnumVolumeMembers(__int64 * __ptr64 * __ptr64,long & __ptr64) __ptr64` | 45 | Exported Function
`public: void __cdecl CDMNodeObj::GetFileSystemLabel(class CString & __ptr64) __ptr64` | 89 | Exported Function
`public: void __cdecl CDMNodeObj::GetLongName(class CString & __ptr64,int) __ptr64` | 104 | Exported Function
`public: void __cdecl CDMNodeObj::GetFileSystemSize(long & __ptr64) __ptr64` | 91 | Exported Function
`public: void __cdecl CDMNodeObj::GetFileSystemName(class CString & __ptr64) __ptr64` | 90 | Exported Function
`public: int __cdecl CTaskData::HasNTFSwithDriveLetter(void) __ptr64` | 154 | Exported Function
`public: int __cdecl CDataCache::FindFileSystem(__int64,struct filesysteminfo & __ptr64) __ptr64` | 55 | Exported Function
`public: int __cdecl CDataCache::FindDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 53 | Exported Function
`public: int __cdecl CDataCache::FindDiskPtrFromDiskId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 52 | Exported Function
`public: int __cdecl CDataCache::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 57 | Exported Function
`public: int __cdecl CDataCache::HasNTFSwithDriveLetter(void) __ptr64` | 153 | Exported Function
`public: int __cdecl CDataCache::GetBootPort(void) __ptr64` | 61 | Exported Function
`public: int __cdecl CDataCache::FindRegionPtrOnDiskFromRegionId(class CDMNodeObj * __ptr64,__int64,class CDMNodeObj * __ptr64 * __ptr64,struct __POSITION * __ptr64 & __ptr64) __ptr64` | 59 | Exported Function
`public: class CWnd * __ptr64 __cdecl CTaskData::GetOcxFrameCWndPtr(void) __ptr64` | 114 | Exported Function
`public: class CString __cdecl CTaskData::GetServerName(void) __ptr64` | 133 | Exported Function
`public: class CString __cdecl CDataCache::GetServerName(void) __ptr64` | 132 | Exported Function
`public: enum _LAYOUT_TYPES __cdecl CDMNodeObj::GetLayoutType(void) __ptr64` | 101 | Exported Function
`public: int __cdecl CDataCache::FindCookieAndRemoveFromList(__int64,class CList<class CDMNodeObj * __ptr64,class CDMNodeObj * __ptr64> * __ptr64) __ptr64` | 50 | Exported Function
`public: enum _STORAGE_TYPES __cdecl CDMNodeObj::GetStorageType(void) __ptr64` | 141 | Exported Function
`public: enum _PARTITIONSTYLE __cdecl CDMNodeObj::GetPartitionStyle(void) __ptr64` | 119 | Exported Function
`public: int __cdecl CDataCache::HasVMDisk(void) __ptr64` | 155 | Exported Function
`public: int __cdecl CDataCache::SupportMirror(void) __ptr64` | 223 | Exported Function
`public: int __cdecl CDataCache::SupportGpt(void) __ptr64` | 221 | Exported Function
`public: int __cdecl CDataCache::IsWolfpack(void) __ptr64` | 198 | Exported Function
`public: int __cdecl CDataCache::SupportRaid5(void) __ptr64` | 224 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsActivePartition(void) __ptr64` | 14 | Exported Function
`public: int __cdecl CDMNodeObj::CanHaveGPT(void) __ptr64` | 11 | Exported Function
`public: int __cdecl CDMComponentData::GetScopeNodeForResultPane(__int64,class CDMScopeNode * __ptr64 * __ptr64) __ptr64` | 131 | Exported Function
`public: int __cdecl CDataCache::IsEfi(void) __ptr64` | 168 | Exported Function
`public: int __cdecl CDataCache::IsDynamic1394(void) __ptr64` | 165 | Exported Function
`public: int __cdecl CDataCache::IsAlpha(void) __ptr64` | 157 | Exported Function
`public: int __cdecl CDataCache::IsNEC_98Server(void) __ptr64` | 181 | Exported Function
`public: int __cdecl CDataCache::IsPreLonghornVdsVersion(void) __ptr64` | 188 | Exported Function
`public: int __cdecl CDataCache::IsPostLonghornVdsVersion(void) __ptr64` | 186 | Exported Function
`public: int __cdecl CDataCache::IsPersonalOrLapTopServer(void) __ptr64` | 185 | Exported Function
`protected: void __cdecl CDataCache::GetDiskCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 69 | Exported Function
`namecmp` | 233 | Exported Function
`LoadPropertyPageData` | 201 | Exported Function
`protected: void __cdecl CDataCache::GetDriveLetters(short & __ptr64,unsigned short * __ptr64 * __ptr64,unsigned short) __ptr64` | 85 | Exported Function
`public: __cdecl CDataCache::CDataCache(void) __ptr64` | 1 | Exported Function
`protected: void __cdecl CDataCache::GetVolumeCookies(unsigned long & __ptr64,__int64 * __ptr64 * __ptr64) __ptr64` | 146 | Exported Function
`protected: void __cdecl CDataCache::GetMinMaxPartitionSizes(__int64,__int64 & __ptr64,__int64 & __ptr64) __ptr64` | 108 | Exported Function
`DllCanUnloadNow` | 230 | Exported Function
`CookieSort` | 229 | Exported Function
`CompareDiskNames` | 228 | Exported Function
`DllGetClassObject` | 231 | Exported Function
`IsRequestPending` | 190 | Exported Function
`GetPropertyPageData` | 124 | Exported Function
`DllRegisterServer` | 232 | Exported Function
`public: __cdecl CDMNodeObj::~CDMNodeObj(void) __ptr64` | 2 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CDataCache::CreateRegionNodeObj(class CDMNodeObj * __ptr64,struct regioninfoex * __ptr64) __ptr64` | 28 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CDataCache::CreateNodeObjAndAddToMap(int,enum _NODEOBJ_TYPES,class CDataCache * __ptr64,void * __ptr64,__int64) __ptr64` | 27 | Exported Function
`public: class CDMComponentData * __ptr64 __cdecl CDataCache::GetComponentData(void) __ptr64` | 64 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetParentDiskPtr(void) __ptr64` | 117 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CTaskData::GetDMDataObjPtrFromId(__int64) __ptr64` | 65 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetRegionByOffset(__int64) __ptr64` | 125 | Exported Function
`public: class CDMNodeObj * __ptr64 __cdecl CDMNodeObj::GetParentVolumePtr(void) __ptr64` | 118 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetShrinkableSizeInMB(void) __ptr64` | 135 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetLdmObjectId(void) __ptr64` | 102 | Exported Function
`public: __int64 __cdecl CDataCache::GetLastKnownState(__int64) __ptr64` | 100 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetStartOffset(void) __ptr64` | 139 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetVolumeTotalSizeMB(void) __ptr64` | 151 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetUsableContiguousSpaceInMB(void) __ptr64` | 145 | Exported Function
`public: __int64 __cdecl CDMNodeObj::GetUnallocSpace(int) __ptr64` | 144 | Exported Function
`public: int __cdecl CDMNodeObj::IsFTVolume(void) __ptr64` | 171 | Exported Function
`public: int __cdecl CDMNodeObj::IsFreeSpaceFollowed(__int64) __ptr64` | 174 | Exported Function
`public: int __cdecl CDMNodeObj::IsFirstFreeRegion(void) __ptr64` | 173 | Exported Function
`public: int __cdecl CDMNodeObj::IsHiddenRegion(void) __ptr64` | 175 | Exported Function
`public: int __cdecl CDMNodeObj::IsMember(class CDMNodeObj * __ptr64) __ptr64` | 179 | Exported Function
`public: int __cdecl CDMNodeObj::IsMbrEEPartition(void) __ptr64` | 178 | Exported Function
`public: int __cdecl CDMNodeObj::IsInFlux(void) __ptr64` | 176 | Exported Function
`public: int __cdecl CDMNodeObj::IsDiskOffline(void) __ptr64` | 163 | Exported Function
`public: int __cdecl CDMNodeObj::IsDiskEmpty(void) __ptr64` | 162 | Exported Function
`public: int __cdecl CDMNodeObj::IsCurrSystemVolume(void) __ptr64` | 161 | Exported Function
`public: int __cdecl CDMNodeObj::IsDiskReadOnly(void) __ptr64` | 164 | Exported Function
`public: int __cdecl CDMNodeObj::IsFakeVolume(void) __ptr64` | 172 | Exported Function
`public: int __cdecl CDMNodeObj::IsESPPartition(void) __ptr64` | 167 | Exported Function
`public: int __cdecl CDMNodeObj::IsEECoveredGPTDisk(void) __ptr64` | 166 | Exported Function
`public: int __cdecl CDMNodeObj::IsNEC_98Disk(void) __ptr64` | 180 | Exported Function
`public: int __cdecl CDMSnapin::GetResultPane(__int64,class CDMResultPane * __ptr64 * __ptr64) __ptr64` | 128 | Exported Function
`public: int __cdecl CDMScopeNodeCollection::GetScopeNode(__int64,class CDMScopeNode * __ptr64 * __ptr64) __ptr64` | 130 | Exported Function
`public: int __cdecl CDMNodeObj::VolumeContainsActiveRegion(void) __ptr64` | 227 | Exported Function
`public: int __cdecl CTaskData::FindFileSystem(__int64,struct filesysteminfo & __ptr64) __ptr64` | 56 | Exported Function
`public: int __cdecl CTaskData::GetBootPort(void) __ptr64` | 62 | Exported Function
`public: int __cdecl CTaskData::GetAssignedDriveLetter(__int64,unsigned short & __ptr64) __ptr64` | 60 | Exported Function
`public: int __cdecl CTaskData::FindRegionPtrFromRegionId(__int64,class CDMNodeObj * __ptr64 * __ptr64) __ptr64` | 58 | Exported Function
`public: int __cdecl CDMNodeObj::IsSpacesProtectivePartition(void) __ptr64` | 193 | Exported Function
`public: int __cdecl CDMNodeObj::IsRevertable(void) __ptr64` | 191 | Exported Function
`public: int __cdecl CDMNodeObj::IsOemPartition(void) __ptr64` | 184 | Exported Function
`public: int __cdecl CDMNodeObj::IsUnknownPartition(void) __ptr64` | 194 | Exported Function
`public: int __cdecl CDMNodeObj::OnlyContiguousExtendAllowed(void) __ptr64` | 204 | Exported Function
`public: int __cdecl CDMNodeObj::IsVolumeSimple(void) __ptr64` | 197 | Exported Function
`public: int __cdecl CDMNodeObj::IsUpgradeable(void) __ptr64` | 195 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsSystemInformation(void) __ptr64` | 24 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsSubDiskNeedResync(void) __ptr64` | 23 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsRealSystemPartition(void) __ptr64` | 22 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsSystemPartition(void) __ptr64` | 25 | Exported Function
`public: int __cdecl CDMNodeObj::GetDiskSpec(struct diskspec & __ptr64) __ptr64` | 81 | Exported Function
`public: int __cdecl CDMNodeObj::GetDiskInfo(struct diskinfoex & __ptr64) __ptr64` | 79 | Exported Function
`public: int __cdecl CDMNodeObj::EnhancedIsUpgradeable(class CTaskData * __ptr64) __ptr64` | 39 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsBootVolumesNumberChange(__int64,int * __ptr64) __ptr64` | 17 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsBootIniPartitionForWolfpack(void) __ptr64` | 16 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsBootIniPartition(void) __ptr64` | 15 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsESPPartition(void) __ptr64` | 18 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsPageFile(void) __ptr64` | 21 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsLogicalDrvBootPartition(void) __ptr64` | 20 | Exported Function
`public: int __cdecl CDMNodeObj::ContainsFVEPartition(void) __ptr64` | 19 | Exported Function
`public: int __cdecl CDMNodeObj::GetDiskStatus(class CString & __ptr64) __ptr64` | 82 | Exported Function
`public: int __cdecl CDMNodeObj::GetVolumeInfo(struct volumeinfo & __ptr64) __ptr64` | 149 | Exported Function
`public: int __cdecl CDMNodeObj::GetStatus(void) __ptr64` | 140 | Exported Function
`public: int __cdecl CDMNodeObj::GetResultStringArray(class CStringArray & __ptr64) __ptr64` | 129 | Exported Function
`public: int __cdecl CDMNodeObj::GetVolumeStatus(class CString & __ptr64) __ptr64` | 150 | Exported Function
`public: int __cdecl CDMNodeObj::IsCurrBootVolume(void) __ptr64` | 160 | Exported Function
`public: int __cdecl CDMNodeObj::IsActive(void) __ptr64` | 156 | Exported Function
`public: int __cdecl CDMNodeObj::HasExtendedPartition(void) __ptr64` | 152 | Exported Function
`public: int __cdecl CDMNodeObj::GetImageNum(void) __ptr64` | 99 | Exported Function
`public: int __cdecl CDMNodeObj::GetFileSystemType(void) __ptr64` | 92 | Exported Function
`public: int __cdecl CDMNodeObj::GetExtraRegionStatus(class CString & __ptr64,int) __ptr64` | 88 | Exported Function
`public: int __cdecl CDMNodeObj::GetOfflineReasonText(class CString & __ptr64) __ptr64` | 115 | Exported Function
`public: int __cdecl CDMNodeObj::GetRegionInfo(struct regioninfoex & __ptr64) __ptr64` | 127 | Exported Function
`public: int __cdecl CDMNodeObj::GetPort(void) __ptr64` | 122 | Exported Function
`public: int __cdecl CDMNodeObj::GetPatternRef(void) __ptr64` | 121 | Exported Function


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


