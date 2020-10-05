---
title: ifsutil.dll | IFS Utility DLL
excerpt: What is ifsutil.dll?
---

# ifsutil.dll 

* File Path: `C:\Windows\SysWOW64\ifsutil.dll`
* Description: IFS Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `F5EF2333425DF432607585DA7706EB4D`
SHA1 | `1F3AB9740BB9267365F190323D9A017E88506126`
SHA256 | `5C35628D65E1C5317468B47DD4C50C9A7DD38AB6C057BBB2648DF696FFFD72DD`
SHA384 | `EDAA7A46249F0A801A8D2F2EC87F05EEE4FE215B040BDCF42E4F99D1FAE610ED4087C2E2BAEDF9B9DE1F3B3DDE8845B6`
SHA512 | `42D9F5FB5FDF3EDEEF353CBABB8538BF3A2178FCE8F4D81E66211E3D5E47BDD9DCD6BAE090D27272460F416D90EDE0861C31E70D13DA15782A4F80031BADC2B6`
SSDEEP | `3072:z5O7ntOPEk+Xe8G5qLhxQE1kluODBU5AahTKbvs5OSrED2jeuFIHpjSgY8UyQnm:zIjtOV+XMcDQEalueU5AahTMvsDEDiJQ`
IMP | `9847E8A443E45D15880EE990BA8084C7`
PESHA1 | `5E32DFB0AC171F5DED85CD3FFC93727961FA79D7`
PE256 | `6B0DD67B28240F1084F78ABC4655B4B9167AF8737FD91340A12CB8FBDB55BB55`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __thiscall NUMBER_SET::RemoveAll(void)` | 275 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Subtract(class NUMBER_SET *,class NUMBER_SET *)` | 305 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Remove(class NUMBER_SET const *)` | 271 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Remove(class BIG_INT)` | 273 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Remove(class BIG_INT,class BIG_INT)` | 272 | Exported Function
`public: unsigned char __thiscall READ_CACHE::Initialize(class IO_DP_DRIVE *,unsigned long)` | 139 | Exported Function
`public: unsigned char __thiscall READ_MODIFY_WRITE_CACHE::Initialize(class IO_DP_DRIVE *,unsigned long,unsigned long,unsigned char,unsigned char)` | 140 | Exported Function
`public: unsigned char __thiscall READ_AHEAD_CACHE::Initialize(class IO_DP_DRIVE *,unsigned long,unsigned long)` | 138 | Exported Function
`public: unsigned char __thiscall POW_CACHE::Initialize(class IO_DP_DRIVE *)` | 137 | Exported Function
`public: unsigned char __thiscall POW_CACHE::Initialize(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long)` | 136 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Add(class NUMBER_SET const *)` | 43 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::CheckAndAdd(class BIG_INT,unsigned char *)` | 56 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Add(class BIG_INT,class BIG_INT)` | 44 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::SetIsSystemPartition(class WSTRING *,unsigned char)` | 292 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Add(class BIG_INT)` | 45 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Initialize(void)` | 135 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::QueryContainingRange(class BIG_INT,class BIG_INT *,class BIG_INT *)const ` | 190 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::Enumerate(unsigned char,class BIG_INT *,class BIG_INT *)const ` | 85 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::CheckAndRemove(class BIG_INT,unsigned char *)` | 58 | Exported Function
`public: unsigned char __thiscall NUMBER_SET::DoesIntersectSet(class BIG_INT,class BIG_INT)const ` | 77 | Exported Function
`public: unsigned char __thiscall VOL_LIODPDRV::ForceAutochk(unsigned char,unsigned long,unsigned long,unsigned short,class WSTRING const *)` | 89 | Exported Function
`public: unsigned char __thiscall VOL_LIODPDRV::Recover(class WSTRING const *,class MESSAGE *)` | 267 | Exported Function
`public: unsigned char __thiscall VOL_LIODPDRV::ChkDsk(enum FIX_LEVEL,class MESSAGE *,unsigned long,unsigned long,unsigned short,unsigned long *,class WSTRING const *)` | 63 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::RemoveAll(void)` | 276 | Exported Function
`public: unsigned char __thiscall TLINK::Initialize(unsigned short)` | 146 | Exported Function
`public: unsigned char __thiscall WRITEVIEW_CACHE::Initialize(class IO_DP_DRIVE *,class DRIVE_CACHE *,class WSTRING const *,unsigned short,unsigned char,unsigned char)` | 149 | Exported Function
`public: unsigned long __thiscall DIGRAPH::QueryNumChildren(unsigned long)const ` | 224 | Exported Function
`public: unsigned char __thiscall WRITE_ONCE_CACHE::Initialize(class IO_DP_DRIVE *,unsigned long,unsigned long,unsigned long)` | 150 | Exported Function
`public: unsigned char __thiscall VOL_LIODPDRV::SetFileSystemName(unsigned short const *)` | 290 | Exported Function
`public: unsigned char __thiscall VOL_LIODPDRV::SetVolumeLabelAndPrintFormatReport(class WSTRING const *,class MESSAGE *)` | 299 | Exported Function
`public: unsigned char __thiscall SNAPSHOT::QuerySnapshotDiffAreaVolume(class WSTRING *)` | 245 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::Add(class BIG_INT)` | 47 | Exported Function
`public: unsigned char __thiscall SNAPSHOT::CheckSnapshotPresence(void)` | 61 | Exported Function
`public: unsigned char __thiscall READ_WRITE_CACHE::Initialize(class IO_DP_DRIVE *,unsigned long,unsigned char)` | 141 | Exported Function
`public: unsigned char __thiscall SECRUN::Initialize(class MEM *,class IO_DP_DRIVE *,class BIG_INT,unsigned long)` | 142 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::CheckAndRemove(class BIG_INT,unsigned char *)` | 59 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::Initialize(void)` | 144 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::CheckAndAdd(class BIG_INT,unsigned char *)` | 57 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::Add(class SPARSE_SET const *)` | 46 | Exported Function
`public: unsigned char __thiscall SPARSE_SET::Check(class BIG_INT)` | 55 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::HardWrite(class BIG_INT,unsigned long,void *,unsigned char)` | 121 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::InvalidateVolume(void)` | 152 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::HardRead(class BIG_INT,unsigned long,void *)` | 120 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::DismountAndLock(void)` | 75 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::FlushCache(void)` | 88 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Lock(void)` | 171 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::PowForceAllocation(unsigned long,unsigned long,unsigned long *,enum DP_DRIVE::NwaType)` | 176 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::IssueDeleteNotification(unsigned __int64,unsigned long)` | 170 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::IsDax(void)` | 155 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::IsLocked(void)` | 161 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::WaitForWriteCompletion(class MESSAGE *)` | 312 | Exported Function
`public: unsigned char __thiscall FORMAT_SQM::Export(int)` | 86 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::WaitForUnit(class MESSAGE *)` | 311 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendSonyMSTestUnitReadyCmd(struct _SENSE_DATA *)` | 285 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SetPowTrackConfiguration(unsigned char)` | 295 | Exported Function
`public: unsigned char __thiscall INTSTACK::Push(class BIG_INT)` | 179 | Exported Function
`public: unsigned char __thiscall INTSTACK::ReverseCopy(class INTSTACK *)` | 278 | Exported Function
`public: unsigned char __thiscall INTSTACK::IsMember(class BIG_INT)const ` | 162 | Exported Function
`public: unsigned char __thiscall FORMAT_SQM::Initialize(class DP_DRIVE *,unsigned short const *,unsigned long,unsigned long)` | 127 | Exported Function
`public: unsigned char __thiscall INTSTACK::Initialize(void)` | 128 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::AddVolumeName(class WSTRING *,class WSTRING *)` | 51 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING *,class WSTRING *)` | 94 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::AddDriveName(class WSTRING *,class WSTRING *)` | 48 | Exported Function
`public: unsigned char __thiscall LOG_IO_DP_DRIVE::Initialize(void *,unsigned char)` | 129 | Exported Function
`public: unsigned char __thiscall LOG_IO_DP_DRIVE::SetSystemId(unsigned char)` | 297 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::QueryIsSystemPartition(class WSTRING *,unsigned char *)` | 211 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::QueryVolumeName(class WSTRING *,class WSTRING *)` | 260 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::QueryDriveName(class WSTRING *,class WSTRING *)` | 197 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING *,class WSTRING *,unsigned char *)` | 95 | Exported Function
`public: unsigned char __thiscall MOUNT_POINT_MAP::Initialize(void)` | 134 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::SqmExport(class WSTRING const *,unsigned char (__cdecl*)(void *,unsigned long,unsigned char,char *,...),void *)` | 303 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT)` | 307 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Read(class BIG_INT,unsigned long,void *)` | 264 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Prefetch(class BIG_INT,unsigned long)` | 177 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::QueryMemoryLimit(unsigned __int64 *,unsigned char *)` | 217 | Exported Function
`public: unsigned char __thiscall LOG_IO_DP_DRIVE::Initialize(class WSTRING const *,class MESSAGE *,unsigned char)` | 131 | Exported Function
`public: unsigned char __thiscall LOG_IO_DP_DRIVE::Initialize(class WSTRING const *,class WSTRING const *,class MESSAGE *,unsigned char)` | 130 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Write(class BIG_INT,unsigned long,void *)` | 313 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT,class NUMBER_SET *)` | 308 | Exported Function
`public: unsigned char __thiscall IO_DP_DRIVE::VerifyRead(class BIG_INT,unsigned long,void *)` | 309 | Exported Function
`public: unsigned long __thiscall DIGRAPH::QueryNumParents(unsigned long)const ` | 225 | Exported Function
`public: void __thiscall BIG_INT::Set(unsigned char,unsigned char const *)` | 286 | Exported Function
`public: void __thiscall DP_DRIVE::CloseDriveHandle(void)` | 65 | Exported Function
`public: void __thiscall BIG_INT::QueryCompressedInteger(unsigned char *,unsigned char *)const ` | 189 | Exported Function
`public: void * __thiscall TLINK::GetSortedNext(void *)` | 117 | Exported Function
`public: void * __thiscall TLINK::QueryDisjointRangeAndAssignBuffer(class BIG_INT *,unsigned short *,unsigned short *,void *,unsigned long,void *)` | 195 | Exported Function
`public: void __thiscall IO_DP_DRIVE::AdjustCacheSize(unsigned __int64 *,unsigned __int64 *)` | 53 | Exported Function
`public: void __thiscall IO_DP_DRIVE::QueryCacheSize(unsigned __int64 *,unsigned __int64 *)` | 183 | Exported Function
`public: void __thiscall INTSTACK::Pop(unsigned long)` | 175 | Exported Function
`public: void __thiscall DP_DRIVE::SetLastStatus(long)` | 293 | Exported Function
`public: void __thiscall DP_DRIVE::SetSectors(class BIG_INT)` | 296 | Exported Function
`public: void * __thiscall DP_DRIVE::QueryDriveHandle(void)const ` | 196 | Exported Function
`public: void * __thiscall IO_DP_DRIVE::QueryVerifyHandle(void)` | 258 | Exported Function
`public: void * __thiscall CANNED_SECURITY::GetCannedSecurityDescriptor(enum _CANNED_SECURITY_TYPE,unsigned long *)` | 98 | Exported Function
`public: virtual void __thiscall WRITEVIEW_CACHE::AdjustCacheSize(unsigned __int64 *,unsigned __int64 *)` | 54 | Exported Function
`public: virtual void __thiscall WRITEVIEW_CACHE::QueryCacheSize(unsigned __int64 *,unsigned __int64 *)` | 184 | Exported Function
`public: void * __thiscall TLINK::GetNext(void *)` | 109 | Exported Function
`public: void * __thiscall TLINK::GetSortedFirst(void)` | 116 | Exported Function
`public: void * __thiscall TLINK::GetFirst(void)` | 105 | Exported Function
`public: void * __thiscall IO_DP_DRIVE::SetVerifyHandle(void *)` | 298 | Exported Function
`public: void * __thiscall TLINK::GetBuffer(void *)` | 96 | Exported Function
`public: void __thiscall WRITEVIEW_CACHE::Delete(class WRITEVIEW_CACHE_ENTRY *)` | 69 | Exported Function
`public: void __thiscall WRITEVIEW_CACHE::Destroy(void)` | 73 | Exported Function
`public: void __thiscall TLINK::TraverseLinkList(void)` | 306 | Exported Function
`public: void __thiscall TLINK::ShellSort(void)` | 300 | Exported Function
`public: void __thiscall TLINK::Sort(void)` | 301 | Exported Function
`RegisterExtensionCallbacks` | 321 | Exported Function
`RestoreThreadExecutionState` | 322 | Exported Function
`public: void __thiscall WRITEVIEW_CACHE::Remove(class WRITEVIEW_CACHE_ENTRY *)` | 274 | Exported Function
`public: void __thiscall WRITEVIEW_CACHE::DestroyWrites(void)` | 74 | Exported Function
`public: void __thiscall WRITEVIEW_CACHE::Purge(class BIG_INT,unsigned long)` | 178 | Exported Function
`public: void __thiscall IO_DP_DRIVE::SetCache(class DRIVE_CACHE *)` | 288 | Exported Function
`public: void __thiscall IO_DP_DRIVE::SetIoErrorDisplayFlags(unsigned long)` | 291 | Exported Function
`public: void __thiscall IO_DP_DRIVE::QueryWriteUsage(unsigned __int64 *,unsigned __int64 *)` | 263 | Exported Function
`public: void __thiscall IO_DP_DRIVE::QueryReadAndVerifiedUsage(unsigned __int64 *,unsigned __int64 *)` | 235 | Exported Function
`public: void __thiscall IO_DP_DRIVE::QueryReadUsage(unsigned __int64 *,unsigned __int64 *)` | 237 | Exported Function
`public: void __thiscall SPARSE_SET::DumpHashTable(void)` | 79 | Exported Function
`public: void __thiscall TLINK::CheckLinkList(void)` | 60 | Exported Function
`public: void __thiscall NUMBER_SET::QueryDisjointRange(unsigned long,class BIG_INT *,class BIG_INT *)const ` | 194 | Exported Function
`public: void __thiscall MEDIA_TRACK_INFORMATION::Initialize(struct _TRACK_INFORMATION2 *)` | 132 | Exported Function
`public: void __thiscall MEDIA_TRACK_INFORMATION_SORTED_BY_SIZE::Initialize(class MEDIA_TRACK_INFORMATION *)` | 133 | Exported Function
`public: virtual __thiscall DP_DRIVE::~DP_DRIVE(void)` | 30 | Exported Function
`public: virtual __thiscall INTSTACK::~INTSTACK(void)` | 31 | Exported Function
`public: virtual __thiscall DIGRAPH::~DIGRAPH(void)` | 29 | Exported Function
`public: virtual __thiscall BLOCK_CACHE::~BLOCK_CACHE(void)` | 27 | Exported Function
`public: virtual __thiscall CANNED_SECURITY::~CANNED_SECURITY(void)` | 28 | Exported Function
`public: virtual __thiscall SECRUN::~SECRUN(void)` | 35 | Exported Function
`public: virtual __thiscall SPARSE_SET::~SPARSE_SET(void)` | 37 | Exported Function
`public: virtual __thiscall NUMBER_SET::~NUMBER_SET(void)` | 34 | Exported Function
`public: virtual __thiscall LOG_IO_DP_DRIVE::~LOG_IO_DP_DRIVE(void)` | 32 | Exported Function
`public: virtual __thiscall MOUNT_POINT_MAP::~MOUNT_POINT_MAP(void)` | 33 | Exported Function
`public: unsigned long __thiscall POW_CACHE::QuerySectorSize(void)` | 241 | Exported Function
`public: unsigned short * __thiscall SNAPSHOT::GetSnapshotGlobalDeviceName(void)` | 114 | Exported Function
`public: unsigned long __thiscall IO_DP_DRIVE::GetIoErrorDisplayFlags(void)const ` | 106 | Exported Function
`public: unsigned long __thiscall DP_DRIVE::QueryPhysicalSectorSize(void)` | 232 | Exported Function
`public: unsigned long __thiscall DP_DRIVE::QueryUdfMediaType(void)` | 257 | Exported Function
`public: unsigned short __thiscall TLINK::QuerySize(void)const ` | 244 | Exported Function
`public: unsigned short const * __thiscall VOL_LIODPDRV::GetFileSystemName(void)` | 104 | Exported Function
`public: unsigned short __thiscall TLINK::QueryMemberCount(void)const ` | 216 | Exported Function
`public: unsigned short * __thiscall SNAPSHOT::GetSnapshotNtDeviceName(void)` | 115 | Exported Function
`public: unsigned short __thiscall DP_DRIVE::QueryEccBlockSizeInSectors(void)` | 199 | Exported Function
`public: virtual unsigned char __thiscall SECRUN::Write(void)` | 314 | Exported Function
`public: virtual unsigned char __thiscall WRITEVIEW_CACHE::QueryMemoryLimit(unsigned __int64 *,unsigned char *)` | 218 | Exported Function
`public: virtual unsigned char __thiscall SECRUN::VerifyRead(unsigned char *)` | 310 | Exported Function
`public: virtual unsigned char __thiscall DP_DRIVE::QueryPartitionInfo(struct _PARTITION_INFORMATION_EX *)` | 231 | Exported Function
`public: virtual unsigned char __thiscall SECRUN::Read(void)` | 265 | Exported Function
`public: virtual void __thiscall BLOCK_CACHE::AdjustCacheSize(unsigned __int64 *,unsigned __int64 *)` | 52 | Exported Function
`public: virtual void __thiscall BLOCK_CACHE::QueryCacheSize(unsigned __int64 *,unsigned __int64 *)` | 182 | Exported Function
`public: virtual unsigned long __thiscall DP_DRIVE::QueryWriteBlockSize(void)const ` | 262 | Exported Function
`public: virtual unsigned char __thiscall WRITEVIEW_CACHE::SqmExport(unsigned char (__cdecl*)(void *,unsigned long,unsigned char,char *,...),void *)` | 304 | Exported Function
`public: virtual unsigned long __thiscall DP_DRIVE::QuerySectorSize(void)const ` | 240 | Exported Function
`public: virtual __thiscall WRITEVIEW_CACHE::~WRITEVIEW_CACHE(void)` | 41 | Exported Function
`public: virtual class BIG_INT __thiscall DP_DRIVE::QuerySectors(void)const ` | 242 | Exported Function
`public: virtual __thiscall VOL_LIODPDRV::~VOL_LIODPDRV(void)` | 40 | Exported Function
`public: virtual __thiscall SUPERAREA::~SUPERAREA(void)` | 38 | Exported Function
`public: virtual __thiscall TLINK::~TLINK(void)` | 39 | Exported Function
`public: virtual long __thiscall DP_DRIVE::QueryTierCount(unsigned long *)` | 250 | Exported Function
`public: virtual unsigned char __thiscall BLOCK_CACHE::SqmExport(unsigned char (__cdecl*)(void *,unsigned long,unsigned char,char *,...),void *)` | 302 | Exported Function
`public: virtual long __thiscall DP_DRIVE::QueryReadCacheSize(unsigned __int64 *)` | 236 | Exported Function
`public: virtual enum FORMAT_ERROR_CODE __thiscall VOL_LIODPDRV::WriteEntireDrive(class MESSAGE *,void *,unsigned long,unsigned int,unsigned int)` | 315 | Exported Function
`public: virtual long __thiscall DP_DRIVE::QueryDataRedundancyCount(unsigned long *,unsigned long *)` | 192 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendSonyMSRequestSenseCmd(struct _SENSE_DATA *)` | 284 | Exported Function
`public: static long __stdcall DP_DRIVE::QueryNtfsSupportInfo(void *,unsigned char *)` | 221 | Exported Function
`public: static long __stdcall SNAPSHOT::GetVolumeSnapshot(class WSTRING *,class SNAPSHOT * *)` | 119 | Exported Function
`public: static class SNAPSHOT * __stdcall SNAPSHOT::GetCurrentSnapshot(void)` | 99 | Exported Function
`public: enum FORMAT_ERROR_CODE __thiscall VOL_LIODPDRV::Format(class WSTRING const *,class MESSAGE *,unsigned long,unsigned long,unsigned long)` | 90 | Exported Function
`public: static class CANNED_SECURITY * __stdcall IFS_SYSTEM::GetCannedSecurity(void)` | 97 | Exported Function
`public: static unsigned char __stdcall AUTOREG::DeleteEntry(class WSTRING const *,class WSTRING const *,class WSTRING const *)` | 70 | Exported Function
`public: static unsigned char __stdcall AUTOREG::DeleteEntry(class WSTRING const *,unsigned char)` | 72 | Exported Function
`public: static unsigned char __stdcall AUTOREG::DeleteEntry(class WSTRING const *,class WSTRING const *)` | 71 | Exported Function
`public: static long __stdcall SUPERAREA::GenerateLabelNotification(class WSTRING const *,class WSTRING *,struct _FILE_FS_SIZE_INFORMATION *,struct _FILE_FS_VOLUME_INFORMATION *)` | 93 | Exported Function
`public: static unsigned char __stdcall AUTOREG::AddEntry(class WSTRING const *)` | 50 | Exported Function
`public: class IO_DP_DRIVE * __thiscall SUPERAREA::GetDrive(void)` | 103 | Exported Function
`public: class MEDIA_TRACK_INFORMATION * __thiscall MEDIA_TRACK_INFORMATION::CreateTrack(unsigned long,unsigned char)` | 68 | Exported Function
`public: class IO_DP_DRIVE * __thiscall SECRUN::GetDrive(void)` | 102 | Exported Function
`public: class BIG_INT __thiscall INTSTACK::Look(unsigned long)const ` | 172 | Exported Function
`public: class BIG_INT __thiscall NUMBER_SET::QueryNumber(class BIG_INT)const ` | 226 | Exported Function
`public: enum DRIVE_TYPE __thiscall DP_DRIVE::QueryDriveType(void)const ` | 198 | Exported Function
`public: enum FORMAT_ERROR_CODE __thiscall IO_DP_DRIVE::SetDaxAttribute(unsigned char)` | 289 | Exported Function
`public: enum _MEDIA_TYPE __thiscall DP_DRIVE::QueryRecommendedMediaType(void)const ` | 238 | Exported Function
`public: class MESSAGE * __thiscall IO_DP_DRIVE::GetMessageW(void)` | 107 | Exported Function
`public: class MESSAGE * __thiscall SUPERAREA::GetMessageW(void)` | 108 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::FileSetAttributes(class WSTRING const *,unsigned long,unsigned long *)` | 87 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::FormatScaleQuickFormatVerify(unsigned __int64,unsigned long *,unsigned long *,unsigned long *,unsigned __int64 *)` | 91 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::EnableVolumeUpgrade(class WSTRING const *)` | 84 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::EnableVolumeCompression(class WSTRING const *)` | 82 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::EnableVolumeIntegrity(class WSTRING const *,unsigned short)` | 83 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsThisNtfs(class BIG_INT,unsigned long,void *)` | 164 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsThisReFS(class BIG_INT,unsigned long,void *)` | 165 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsFileSystemEnabled(class WSTRING const *,unsigned char *)` | 159 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::FormatScaleTotalFreeClusters(unsigned __int64,unsigned __int64,unsigned long *,unsigned long *,unsigned __int64 *,unsigned __int64 *)` | 92 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsArcSystemPartition(class WSTRING const *,unsigned char *)` | 153 | Exported Function
`public: static unsigned char __stdcall AUTOREG::PushEntry(class WSTRING const *)` | 180 | Exported Function
`public: static unsigned char __stdcall DP_DRIVE::QueryFreeBlocksInLastTrack(void *,unsigned long *)` | 205 | Exported Function
`public: static unsigned char __stdcall AUTOREG::IsFrontEndPresent(class WSTRING const *,class WSTRING const *)` | 160 | Exported Function
`public: static unsigned char __stdcall AUTOREG::IsEntryPresent(class WSTRING const *)` | 157 | Exported Function
`public: static unsigned char __stdcall AUTOREG::IsEntryPresent(class WSTRING const *,class WSTRING const *)` | 156 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::DosDriveNameToNtDriveName(class WSTRING const *,class WSTRING *)` | 78 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::EnableFileSystem(class WSTRING const *)` | 81 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::DismountVolume(class WSTRING const *)` | 76 | Exported Function
`public: static unsigned char __stdcall DP_DRIVE::QueryMrwSupport(void *)` | 219 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::CheckValidSecurityDescriptor(unsigned long,struct _SECURITY_DESCRIPTOR *)` | 62 | Exported Function
`public: __thiscall BLOCK_CACHE::BLOCK_CACHE(void)` | 1 | Exported Function
`public: __thiscall CANNED_SECURITY::CANNED_SECURITY(void)` | 2 | Exported Function
`protected: unsigned char __thiscall VOL_LIODPDRV::Initialize(class WSTRING const *,class WSTRING const *,class SUPERAREA *,class MESSAGE *,unsigned char)` | 148 | Exported Function
`protected: enum FORMAT_ERROR_CODE __thiscall VOL_LIODPDRV::Initialize(class WSTRING const *,class SUPERAREA *,class MESSAGE *,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned short,unsigned char,unsigned int,unsigned char)` | 147 | Exported Function
`protected: unsigned char __thiscall SUPERAREA::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,unsigned long,class MESSAGE *)` | 145 | Exported Function
`public: __thiscall INTSTACK::INTSTACK(void)` | 6 | Exported Function
`public: __thiscall LOG_IO_DP_DRIVE::LOG_IO_DP_DRIVE(void)` | 7 | Exported Function
`public: __thiscall DP_DRIVE::DP_DRIVE(void)` | 5 | Exported Function
`public: __thiscall DIGRAPH::DIGRAPH(void)` | 3 | Exported Function
`public: __thiscall DIGRAPH_EDGE::DIGRAPH_EDGE(void)` | 4 | Exported Function
`InvalidateFve` | 318 | Exported Function
`NotifyFveAfterFormat` | 319 | Exported Function
`GetDefaultFileSystemIfs` | 317 | Exported Function
`_QueryPersistRegistryKeyValueWithFallback@12` | 320 | Exported Function
`_WritePersistRegistryKeyValue@24` | 323 | Exported Function
`protected: __thiscall SUPERAREA::SUPERAREA(void)` | 21 | Exported Function
`protected: __thiscall VOL_LIODPDRV::VOL_LIODPDRV(void)` | 23 | Exported Function
`private: virtual __thiscall SNAPSHOT::~SNAPSHOT(void)` | 36 | Exported Function
`private: __thiscall SNAPSHOT::SNAPSHOT(void)` | 19 | Exported Function
`private: long __thiscall SNAPSHOT::Initialize(unsigned short *)` | 143 | Exported Function
`public: __thiscall WRITE_ONCE_CACHE::WRITE_ONCE_CACHE(void)` | 26 | Exported Function
`public: __thiscall WRITEVIEW_CACHE::WRITEVIEW_CACHE(void)` | 24 | Exported Function
`public: __thiscall TLINK::TLINK(void)` | 22 | Exported Function
`public: __thiscall SECRUN::SECRUN(void)` | 18 | Exported Function
`public: __thiscall SPARSE_SET::SPARSE_SET(void)` | 20 | Exported Function
`public: class BIG_INT & __thiscall TLINK::GetData(void *)` | 101 | Exported Function
`public: class BIG_INT & __thiscall TLINK::GetNextDataSlot(void)` | 110 | Exported Function
`public: class BIG_INT & __thiscall TLINK::GetData(unsigned short)` | 100 | Exported Function
`public: __thiscall WRITEVIEW_CACHE_ENTRY::WRITEVIEW_CACHE_ENTRY(class WRITEVIEW_CACHE *,unsigned short)` | 25 | Exported Function
`public: __thiscall WRITEVIEW_CACHE_ENTRY::~WRITEVIEW_CACHE_ENTRY(void)` | 42 | Exported Function
`public: __thiscall NUMBER_SET::NUMBER_SET(void)` | 11 | Exported Function
`public: __thiscall POW_CACHE::POW_CACHE(void)` | 12 | Exported Function
`public: __thiscall MOUNT_POINT_TUPLE::MOUNT_POINT_TUPLE(void)` | 10 | Exported Function
`public: __thiscall MEDIA_TRACK_INFORMATION::MEDIA_TRACK_INFORMATION(void)` | 8 | Exported Function
`public: __thiscall MOUNT_POINT_MAP::MOUNT_POINT_MAP(void)` | 9 | Exported Function
`public: __thiscall READ_MODIFY_WRITE_CACHE::READ_MODIFY_WRITE_CACHE(void)` | 16 | Exported Function
`public: __thiscall READ_WRITE_CACHE::READ_WRITE_CACHE(void)` | 17 | Exported Function
`public: __thiscall READ_CACHE::READ_CACHE(void)` | 15 | Exported Function
`public: __thiscall POW_TRACK::POW_TRACK(void)` | 13 | Exported Function
`public: __thiscall READ_AHEAD_CACHE::READ_AHEAD_CACHE(void)` | 14 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsTotalDeviceFailure(long)` | 166 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryFirstBlockInLastNonEmptySession(unsigned long *)` | 202 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryFirstBlockInLastSession(unsigned long *)` | 203 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryDiscStatus(unsigned long *,unsigned long *)` | 193 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::IsThinlyProvisioned(void)` | 163 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::IsUdfMediaWritable(void)` | 167 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryID(class WSTRING *,class WSTRING const *)` | 210 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryID(struct _GUID *,class WSTRING const *)` | 209 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryHotPlugInfo(void)const ` | 208 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryFreeBlocksInLastTrack(unsigned long *)` | 204 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryHighestTrackAddress(unsigned long *)` | 207 | Exported Function
`public: unsigned char __thiscall DIGRAPH::RemoveEdge(unsigned long,unsigned long)` | 277 | Exported Function
`public: unsigned char __thiscall DIGRAPH::SearchForMatch(unsigned long,class BITVECTOR *,class NUMBER_SET *,unsigned char *,class BIG_INT *)` | 279 | Exported Function
`public: unsigned char __thiscall DIGRAPH::QueryParentsWithChildren(class NUMBER_SET *,unsigned long)const ` | 230 | Exported Function
`public: unsigned char __thiscall DIGRAPH::QueryChildren(unsigned long,class NUMBER_SET *)const ` | 186 | Exported Function
`public: unsigned char __thiscall DIGRAPH::QueryParents(unsigned long,class NUMBER_SET *)const ` | 229 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::InitializePowTrackConfiguration(unsigned char,unsigned char *)` | 151 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::IsBootCriticalVolume(void)` | 154 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::Initialize(class WSTRING const *,class WSTRING const *,class MESSAGE *,unsigned char,unsigned char)` | 125 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::CreateTrack(unsigned long,unsigned char,enum DP_DRIVE::NwaType)` | 67 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::Initialize(class WSTRING const *,class MESSAGE *,unsigned char,unsigned char)` | 126 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::ReadFormattableCapacity(unsigned char,unsigned long *,unsigned char *,unsigned long *)` | 266 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::ReinitializeDriveParameters(class MESSAGE *)` | 268 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryVolumeBounds(unsigned long *,unsigned long *)` | 259 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaSupportsBackgroundFormat(void)` | 255 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaSupportsQuickGrow(void)` | 256 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendSonyMSInquiryCmd(struct SONY_MS_INQUIRY_DATA *)` | 282 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendSonyMSModeSenseCmd(struct SONY_MS_MODE_SENSE_DATA *)` | 283 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendSonyMSFormatCmd(unsigned char)` | 281 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::ReinitiateBackgroundFormat(void)` | 269 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::SendPowLowLevelFormat(class MESSAGE *)` | 280 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryNextWritableAddress(unsigned long *,enum DP_DRIVE::NwaType)` | 220 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryOpenSessionBounds(unsigned long *,unsigned long *)` | 227 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryMediaByte(void)const ` | 215 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryLastRecordedAddress(unsigned long *)` | 213 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryLastWritableAddress(unsigned long *,enum DP_DRIVE::NwaType)` | 214 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaNeedsSparing(void)` | 253 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaNeedsVat(void)` | 254 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaNeedsLowLevelFormat(void)` | 252 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryRewritableMOSupport(void)` | 239 | Exported Function
`public: unsigned char __thiscall DP_DRIVE::QueryUdfMediaHasPow(void)` | 251 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryProcessorInformation(class DSTRING *,unsigned long *,unsigned __int64 *)` | 234 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryProcessPrivateMemory(void *,unsigned __int64 *)` | 233 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryNtfsVersion(unsigned char *,unsigned char *,class LOG_IO_DP_DRIVE *,void *)` | 223 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryFreeDiskSpace(class WSTRING const *,class BIG_INT *)` | 206 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryIsSystemUEFI(void)` | 212 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QuerySystemMemory(unsigned long *,unsigned __int64 *,unsigned __int64 *,unsigned __int64 *)` | 248 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QuerySystemVersion(class DSTRING *)` | 249 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryStorageDeviceProperty(void *,class DSTRING *,class DSTRING *,class DSTRING *,unsigned char *,unsigned char *)` | 247 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryServer(unsigned char *)` | 243 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryStorageAdapterProperty(void *,class DSTRING *,class DSTRING *)` | 246 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::NtDriveNameToDosDriveName(class WSTRING const *,class WSTRING *)` | 174 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryCanonicalNtDriveName(class WSTRING const *,class WSTRING *)` | 185 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::NtDeviceNameToDosDriveName(class WSTRING const *,class WSTRING *)` | 173 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsVolumeDirty(class WSTRING *,unsigned char *,unsigned char *,long *)` | 168 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::IsVolumeWriteable(class WSTRING *,unsigned char *,long *)` | 169 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryFileSystemName(class WSTRING const *,class WSTRING *,long *,class WSTRING *)` | 200 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryFileSystemNameByHandle(void *,class WSTRING *,long *,class WSTRING *)` | 201 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryCorruptionState(class WSTRING *,unsigned long *,unsigned char *,long *)` | 191 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryCluster(unsigned char *)` | 187 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryClusterFunctionalLevel(unsigned long *,unsigned long *)` | 188 | Exported Function
`public: static void __stdcall IFS_SYSTEM::QueryNtfsTime(union _LARGE_INTEGER *)` | 222 | Exported Function
`public: unsigned __int64 __thiscall BLOCK_CACHE::GetPerfFreq(void)` | 111 | Exported Function
`public: static void __stdcall IFS_SYSTEM::GetSystemTime(struct _TIME_FIELDS *)` | 118 | Exported Function
`public: static void __stdcall DRIVE_CACHE::GetPhaseSubPhase(unsigned short * *,unsigned short * *)` | 112 | Exported Function
`public: static void __stdcall DRIVE_CACHE::SetPhaseSubPhase(unsigned short *,unsigned short *)` | 294 | Exported Function
`public: unsigned char __thiscall DIGRAPH::EliminateCycles(class CONTAINER *,unsigned char *)` | 80 | Exported Function
`public: unsigned char __thiscall DIGRAPH::Initialize(unsigned long)` | 124 | Exported Function
`public: unsigned char __thiscall DIGRAPH::AddEdge(unsigned long,unsigned long)` | 49 | Exported Function
`public: unsigned char __thiscall BLOCK_CACHE::Initialize(class IO_DP_DRIVE *)` | 122 | Exported Function
`public: unsigned char __thiscall CANNED_SECURITY::Initialize(void)` | 123 | Exported Function
`public: static unsigned char __stdcall SNAPSHOT::IsFatalError(long)` | 158 | Exported Function
`public: static unsigned char __stdcall SNAPSHOT::ReleaseVolumeSnapshot(class SNAPSHOT *)` | 270 | Exported Function
`public: static unsigned char __stdcall SNAPSHOT::GetSnapshotErrorMessage(long,class WSTRING *)` | 113 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::QueryVolumeSize(class WSTRING const *,unsigned __int64 *)` | 261 | Exported Function
`public: static unsigned char __stdcall IFS_SYSTEM::WriteToFile(class WSTRING const *,void *,unsigned long,unsigned char)` | 316 | Exported Function
`public: static unsigned long __stdcall IFS_SYSTEM::QueryPageSize(void)` | 228 | Exported Function
`public: static unsigned long __stdcall SUPERAREA::ComputeVolId(unsigned long)` | 66 | Exported Function
`public: static unsigned char __stdcall WRITEVIEW_BACKINGSTORE::CleanupBackingStore(class WSTRING *)` | 64 | Exported Function
`public: static unsigned char __stdcall VOL_LIODPDRV::QueryAutochkTimeOut(unsigned long *)` | 181 | Exported Function
`public: static unsigned char __stdcall VOL_LIODPDRV::SetAutochkTimeOut(unsigned long)` | 287 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IFSUtil.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/5c35628d65e1c5317468b47dd4c50c9a7dd38ab6c057bbb2648df696fffd72dd/detection/





MIT License. Copyright (c) 2020 Strontic.


