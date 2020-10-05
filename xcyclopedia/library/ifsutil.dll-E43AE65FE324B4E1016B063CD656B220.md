---
title: ifsutil.dll | IFS Utility DLL
excerpt: What is ifsutil.dll?
---

# ifsutil.dll 

* File Path: `C:\Windows\system32\ifsutil.dll`
* Description: IFS Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `E43AE65FE324B4E1016B063CD656B220`
SHA1 | `0C286885023068DCA971FB82834825C83E9C33E4`
SHA256 | `D59CC1123EF29D5FA7C0356A845B16E3FBFB681638C182C902283852C4AF3188`
SHA384 | `02C1B54DF6D709216F12A60A6042FDEAE19E9941CAE30F4F5EA79B9D9E5DD537E615041921D67A622EEE4589BD65990E`
SHA512 | `DE0CAFBF8961588E42907B647D1FECB0F86BCB299939DCA124CA6489AD549777C99EDD9DAE6D917508E29461F5C1087436D29DD597EBD29225FB552E2A04DABE`
SSDEEP | `3072:fzmtmZQd2mkiP8xIBsXa/fsJOfrbPv+79DfMNfgudbHnsR9vT5m6PG4fBM8xOjoF:LmtMQdKiU3acJOfr7v+7d0RJTAvxDF`
IMP | `6BF5710DFD8EADAF925E48746F08A0CB`
PESHA1 | `82D6115151762938869EBF048047B4EB6C77829E`
PE256 | `F09C2F5ABA6F38C6BEBA3234CF5D124B822C0AD09A5A1DF4CFC86FFEB4BDCD64`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __cdecl POW_CACHE::Initialize(class IO_DP_DRIVE * __ptr64) __ptr64` | 137 | Exported Function
`public: unsigned char __cdecl POW_CACHE::Initialize(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long) __ptr64` | 136 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Subtract(class NUMBER_SET * __ptr64,class NUMBER_SET * __ptr64) __ptr64` | 305 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Remove(class NUMBER_SET const * __ptr64) __ptr64` | 271 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::RemoveAll(void) __ptr64` | 275 | Exported Function
`public: unsigned char __cdecl READ_WRITE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned char) __ptr64` | 141 | Exported Function
`public: unsigned char __cdecl SECRUN::Initialize(class MEM * __ptr64,class IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long) __ptr64` | 142 | Exported Function
`public: unsigned char __cdecl READ_MODIFY_WRITE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned char,unsigned char) __ptr64` | 140 | Exported Function
`public: unsigned char __cdecl READ_AHEAD_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long) __ptr64` | 138 | Exported Function
`public: unsigned char __cdecl READ_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long) __ptr64` | 139 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::CheckAndRemove(class BIG_INT,unsigned char * __ptr64) __ptr64` | 58 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::DoesIntersectSet(class BIG_INT,class BIG_INT)const __ptr64` | 77 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::CheckAndAdd(class BIG_INT,unsigned char * __ptr64) __ptr64` | 56 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Add(class BIG_INT,class BIG_INT) __ptr64` | 44 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Add(class NUMBER_SET const * __ptr64) __ptr64` | 43 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Remove(class BIG_INT) __ptr64` | 273 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Remove(class BIG_INT,class BIG_INT) __ptr64` | 272 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::QueryContainingRange(class BIG_INT,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 190 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Enumerate(unsigned char,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 85 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Initialize(void) __ptr64` | 135 | Exported Function
`public: unsigned char __cdecl VOL_LIODPDRV::SetFileSystemName(unsigned short const * __ptr64) __ptr64` | 290 | Exported Function
`public: unsigned char __cdecl VOL_LIODPDRV::SetVolumeLabelAndPrintFormatReport(class WSTRING const * __ptr64,class MESSAGE * __ptr64) __ptr64` | 299 | Exported Function
`public: unsigned char __cdecl VOL_LIODPDRV::Recover(class WSTRING const * __ptr64,class MESSAGE * __ptr64) __ptr64` | 267 | Exported Function
`public: unsigned char __cdecl VOL_LIODPDRV::ChkDsk(enum FIX_LEVEL,class MESSAGE * __ptr64,unsigned long,unsigned long,unsigned short,unsigned long * __ptr64,class WSTRING const * __ptr64) __ptr64` | 63 | Exported Function
`public: unsigned char __cdecl VOL_LIODPDRV::ForceAutochk(unsigned char,unsigned long,unsigned long,unsigned short,class WSTRING const * __ptr64) __ptr64` | 89 | Exported Function
`public: unsigned long __cdecl DIGRAPH::QueryNumParents(unsigned long)const __ptr64` | 225 | Exported Function
`public: unsigned long __cdecl DP_DRIVE::QueryPhysicalSectorSize(void) __ptr64` | 232 | Exported Function
`public: unsigned long __cdecl DIGRAPH::QueryNumChildren(unsigned long)const __ptr64` | 224 | Exported Function
`public: unsigned char __cdecl WRITE_ONCE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned long) __ptr64` | 150 | Exported Function
`public: unsigned char __cdecl WRITEVIEW_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,class DRIVE_CACHE * __ptr64,class WSTRING const * __ptr64,unsigned short,unsigned char,unsigned char) __ptr64` | 149 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::Add(class SPARSE_SET const * __ptr64) __ptr64` | 46 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::Check(class BIG_INT) __ptr64` | 55 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::Add(class BIG_INT) __ptr64` | 47 | Exported Function
`public: unsigned char __cdecl SNAPSHOT::CheckSnapshotPresence(void) __ptr64` | 61 | Exported Function
`public: unsigned char __cdecl SNAPSHOT::QuerySnapshotDiffAreaVolume(class WSTRING * __ptr64) __ptr64` | 245 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::RemoveAll(void) __ptr64` | 276 | Exported Function
`public: unsigned char __cdecl TLINK::Initialize(unsigned short) __ptr64` | 146 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::Initialize(void) __ptr64` | 144 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::CheckAndAdd(class BIG_INT,unsigned char * __ptr64) __ptr64` | 57 | Exported Function
`public: unsigned char __cdecl SPARSE_SET::CheckAndRemove(class BIG_INT,unsigned char * __ptr64) __ptr64` | 59 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::IsDax(void) __ptr64` | 155 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::IsLocked(void) __ptr64` | 161 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::InvalidateVolume(void) __ptr64` | 152 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::HardRead(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 120 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::HardWrite(class BIG_INT,unsigned long,void * __ptr64,unsigned char) __ptr64` | 121 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Prefetch(class BIG_INT,unsigned long) __ptr64` | 177 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::QueryMemoryLimit(unsigned __int64 * __ptr64,unsigned char * __ptr64) __ptr64` | 217 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::PowForceAllocation(unsigned long,unsigned long,unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 176 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::IssueDeleteNotification(unsigned __int64,unsigned long) __ptr64` | 170 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Lock(void) __ptr64` | 171 | Exported Function
`public: unsigned char __cdecl FORMAT_SQM::Initialize(class DP_DRIVE * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long) __ptr64` | 127 | Exported Function
`public: unsigned char __cdecl INTSTACK::Initialize(void) __ptr64` | 128 | Exported Function
`public: unsigned char __cdecl FORMAT_SQM::Export(int) __ptr64` | 86 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::WaitForUnit(class MESSAGE * __ptr64) __ptr64` | 311 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::WaitForWriteCompletion(class MESSAGE * __ptr64) __ptr64` | 312 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::DismountAndLock(void) __ptr64` | 75 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::FlushCache(void) __ptr64` | 88 | Exported Function
`public: unsigned char __cdecl INTSTACK::ReverseCopy(class INTSTACK * __ptr64) __ptr64` | 278 | Exported Function
`public: unsigned char __cdecl INTSTACK::IsMember(class BIG_INT)const __ptr64` | 162 | Exported Function
`public: unsigned char __cdecl INTSTACK::Push(class BIG_INT) __ptr64` | 179 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING * __ptr64,class WSTRING * __ptr64,unsigned char * __ptr64) __ptr64` | 95 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::Initialize(void) __ptr64` | 134 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 94 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::AddDriveName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 48 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::AddVolumeName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 51 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::SetIsSystemPartition(class WSTRING * __ptr64,unsigned char) __ptr64` | 292 | Exported Function
`public: unsigned char __cdecl NUMBER_SET::Add(class BIG_INT) __ptr64` | 45 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryVolumeName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 260 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryDriveName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 197 | Exported Function
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryIsSystemPartition(class WSTRING * __ptr64,unsigned char * __ptr64) __ptr64` | 211 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT,class NUMBER_SET * __ptr64) __ptr64` | 308 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::VerifyRead(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 309 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT) __ptr64` | 307 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Read(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 264 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::SqmExport(class WSTRING const * __ptr64,unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 303 | Exported Function
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(void * __ptr64,unsigned char) __ptr64` | 129 | Exported Function
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::SetSystemId(unsigned char) __ptr64` | 297 | Exported Function
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 130 | Exported Function
`public: unsigned char __cdecl IO_DP_DRIVE::Write(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 313 | Exported Function
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 131 | Exported Function
`public: unsigned long __cdecl DP_DRIVE::QueryUdfMediaType(void) __ptr64` | 257 | Exported Function
`public: void __cdecl DP_DRIVE::SetLastStatus(long) __ptr64` | 293 | Exported Function
`public: void __cdecl DP_DRIVE::SetSectors(class BIG_INT) __ptr64` | 296 | Exported Function
`public: void __cdecl DP_DRIVE::CloseDriveHandle(void) __ptr64` | 65 | Exported Function
`public: void __cdecl BIG_INT::QueryCompressedInteger(unsigned char * __ptr64,unsigned char * __ptr64)const __ptr64` | 189 | Exported Function
`public: void __cdecl BIG_INT::Set(unsigned char,unsigned char const * __ptr64) __ptr64` | 286 | Exported Function
`public: void __cdecl IO_DP_DRIVE::QueryReadAndVerifiedUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 235 | Exported Function
`public: void __cdecl IO_DP_DRIVE::QueryReadUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 237 | Exported Function
`public: void __cdecl IO_DP_DRIVE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 183 | Exported Function
`public: void __cdecl INTSTACK::Pop(unsigned long) __ptr64` | 175 | Exported Function
`public: void __cdecl IO_DP_DRIVE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 53 | Exported Function
`public: void * __ptr64 __cdecl IO_DP_DRIVE::SetVerifyHandle(void * __ptr64) __ptr64` | 298 | Exported Function
`public: void * __ptr64 __cdecl TLINK::GetBuffer(void * __ptr64) __ptr64` | 96 | Exported Function
`public: void * __ptr64 __cdecl IO_DP_DRIVE::QueryVerifyHandle(void) __ptr64` | 258 | Exported Function
`public: void * __ptr64 __cdecl CANNED_SECURITY::GetCannedSecurityDescriptor(enum _CANNED_SECURITY_TYPE,unsigned long * __ptr64) __ptr64` | 98 | Exported Function
`public: void * __ptr64 __cdecl DP_DRIVE::QueryDriveHandle(void)const __ptr64` | 196 | Exported Function
`public: void * __ptr64 __cdecl TLINK::GetSortedNext(void * __ptr64) __ptr64` | 117 | Exported Function
`public: void * __ptr64 __cdecl TLINK::QueryDisjointRangeAndAssignBuffer(class BIG_INT * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,void * __ptr64,unsigned long,void * __ptr64) __ptr64` | 195 | Exported Function
`public: void * __ptr64 __cdecl TLINK::GetSortedFirst(void) __ptr64` | 116 | Exported Function
`public: void * __ptr64 __cdecl TLINK::GetFirst(void) __ptr64` | 105 | Exported Function
`public: void * __ptr64 __cdecl TLINK::GetNext(void * __ptr64) __ptr64` | 109 | Exported Function
`public: void __cdecl WRITEVIEW_CACHE::DestroyWrites(void) __ptr64` | 74 | Exported Function
`public: void __cdecl WRITEVIEW_CACHE::Purge(class BIG_INT,unsigned long) __ptr64` | 178 | Exported Function
`public: void __cdecl WRITEVIEW_CACHE::Destroy(void) __ptr64` | 73 | Exported Function
`public: void __cdecl TLINK::TraverseLinkList(void) __ptr64` | 306 | Exported Function
`public: void __cdecl WRITEVIEW_CACHE::Delete(class WRITEVIEW_CACHE_ENTRY * __ptr64) __ptr64` | 69 | Exported Function
`RestoreThreadExecutionState` | 322 | Exported Function
`WritePersistRegistryKeyValue` | 323 | Exported Function
`RegisterExtensionCallbacks` | 321 | Exported Function
`public: void __cdecl WRITEVIEW_CACHE::Remove(class WRITEVIEW_CACHE_ENTRY * __ptr64) __ptr64` | 274 | Exported Function
`QueryPersistRegistryKeyValueWithFallback` | 320 | Exported Function
`public: void __cdecl MEDIA_TRACK_INFORMATION::Initialize(struct _TRACK_INFORMATION2 * __ptr64) __ptr64` | 132 | Exported Function
`public: void __cdecl MEDIA_TRACK_INFORMATION_SORTED_BY_SIZE::Initialize(class MEDIA_TRACK_INFORMATION * __ptr64) __ptr64` | 133 | Exported Function
`public: void __cdecl IO_DP_DRIVE::SetIoErrorDisplayFlags(unsigned long) __ptr64` | 291 | Exported Function
`public: void __cdecl IO_DP_DRIVE::QueryWriteUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 263 | Exported Function
`public: void __cdecl IO_DP_DRIVE::SetCache(class DRIVE_CACHE * __ptr64) __ptr64` | 288 | Exported Function
`public: void __cdecl TLINK::ShellSort(void) __ptr64` | 300 | Exported Function
`public: void __cdecl TLINK::Sort(void) __ptr64` | 301 | Exported Function
`public: void __cdecl TLINK::CheckLinkList(void) __ptr64` | 60 | Exported Function
`public: void __cdecl NUMBER_SET::QueryDisjointRange(unsigned long,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 194 | Exported Function
`public: void __cdecl SPARSE_SET::DumpHashTable(void) __ptr64` | 79 | Exported Function
`public: virtual __cdecl LOG_IO_DP_DRIVE::~LOG_IO_DP_DRIVE(void) __ptr64` | 32 | Exported Function
`public: virtual __cdecl MOUNT_POINT_MAP::~MOUNT_POINT_MAP(void) __ptr64` | 33 | Exported Function
`public: virtual __cdecl INTSTACK::~INTSTACK(void) __ptr64` | 31 | Exported Function
`public: virtual __cdecl DIGRAPH::~DIGRAPH(void) __ptr64` | 29 | Exported Function
`public: virtual __cdecl DP_DRIVE::~DP_DRIVE(void) __ptr64` | 30 | Exported Function
`public: virtual __cdecl SUPERAREA::~SUPERAREA(void) __ptr64` | 38 | Exported Function
`public: virtual __cdecl TLINK::~TLINK(void) __ptr64` | 39 | Exported Function
`public: virtual __cdecl SPARSE_SET::~SPARSE_SET(void) __ptr64` | 37 | Exported Function
`public: virtual __cdecl NUMBER_SET::~NUMBER_SET(void) __ptr64` | 34 | Exported Function
`public: virtual __cdecl SECRUN::~SECRUN(void) __ptr64` | 35 | Exported Function
`public: unsigned short * __ptr64 __cdecl SNAPSHOT::GetSnapshotNtDeviceName(void) __ptr64` | 115 | Exported Function
`public: unsigned short __cdecl DP_DRIVE::QueryEccBlockSizeInSectors(void) __ptr64` | 199 | Exported Function
`public: unsigned short * __ptr64 __cdecl SNAPSHOT::GetSnapshotGlobalDeviceName(void) __ptr64` | 114 | Exported Function
`public: unsigned long __cdecl IO_DP_DRIVE::GetIoErrorDisplayFlags(void)const __ptr64` | 106 | Exported Function
`public: unsigned long __cdecl POW_CACHE::QuerySectorSize(void) __ptr64` | 241 | Exported Function
`public: virtual __cdecl BLOCK_CACHE::~BLOCK_CACHE(void) __ptr64` | 27 | Exported Function
`public: virtual __cdecl CANNED_SECURITY::~CANNED_SECURITY(void) __ptr64` | 28 | Exported Function
`public: unsigned short const * __ptr64 __cdecl VOL_LIODPDRV::GetFileSystemName(void) __ptr64` | 104 | Exported Function
`public: unsigned short __cdecl TLINK::QueryMemberCount(void)const __ptr64` | 216 | Exported Function
`public: unsigned short __cdecl TLINK::QuerySize(void)const __ptr64` | 244 | Exported Function
`public: virtual unsigned char __cdecl WRITEVIEW_CACHE::SqmExport(unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 304 | Exported Function
`public: virtual unsigned long __cdecl DP_DRIVE::QuerySectorSize(void)const __ptr64` | 240 | Exported Function
`public: virtual unsigned char __cdecl WRITEVIEW_CACHE::QueryMemoryLimit(unsigned __int64 * __ptr64,unsigned char * __ptr64) __ptr64` | 218 | Exported Function
`public: virtual unsigned char __cdecl SECRUN::VerifyRead(unsigned char * __ptr64) __ptr64` | 310 | Exported Function
`public: virtual unsigned char __cdecl SECRUN::Write(void) __ptr64` | 314 | Exported Function
`public: virtual void __cdecl WRITEVIEW_CACHE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 54 | Exported Function
`public: virtual void __cdecl WRITEVIEW_CACHE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 184 | Exported Function
`public: virtual void __cdecl BLOCK_CACHE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 182 | Exported Function
`public: virtual unsigned long __cdecl DP_DRIVE::QueryWriteBlockSize(void)const __ptr64` | 262 | Exported Function
`public: virtual void __cdecl BLOCK_CACHE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 52 | Exported Function
`public: virtual enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::WriteEntireDrive(class MESSAGE * __ptr64,void * __ptr64,unsigned long,unsigned int,unsigned int) __ptr64` | 315 | Exported Function
`public: virtual long __cdecl DP_DRIVE::QueryDataRedundancyCount(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 192 | Exported Function
`public: virtual class BIG_INT __cdecl DP_DRIVE::QuerySectors(void)const __ptr64` | 242 | Exported Function
`public: virtual __cdecl VOL_LIODPDRV::~VOL_LIODPDRV(void) __ptr64` | 40 | Exported Function
`public: virtual __cdecl WRITEVIEW_CACHE::~WRITEVIEW_CACHE(void) __ptr64` | 41 | Exported Function
`public: virtual unsigned char __cdecl DP_DRIVE::QueryPartitionInfo(struct _PARTITION_INFORMATION_EX * __ptr64) __ptr64` | 231 | Exported Function
`public: virtual unsigned char __cdecl SECRUN::Read(void) __ptr64` | 265 | Exported Function
`public: virtual unsigned char __cdecl BLOCK_CACHE::SqmExport(unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 302 | Exported Function
`public: virtual long __cdecl DP_DRIVE::QueryReadCacheSize(unsigned __int64 * __ptr64) __ptr64` | 236 | Exported Function
`public: virtual long __cdecl DP_DRIVE::QueryTierCount(unsigned long * __ptr64) __ptr64` | 250 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SetPowTrackConfiguration(unsigned char) __ptr64` | 295 | Exported Function
`public: static long __cdecl SUPERAREA::GenerateLabelNotification(class WSTRING const * __ptr64,class WSTRING * __ptr64,struct _FILE_FS_SIZE_INFORMATION * __ptr64,struct _FILE_FS_VOLUME_INFORMATION * __ptr64)` | 93 | Exported Function
`public: static unsigned char __cdecl AUTOREG::AddEntry(class WSTRING const * __ptr64)` | 50 | Exported Function
`public: static long __cdecl SNAPSHOT::GetVolumeSnapshot(class WSTRING * __ptr64,class SNAPSHOT * __ptr64 * __ptr64)` | 119 | Exported Function
`public: static class SNAPSHOT * __ptr64 __cdecl SNAPSHOT::GetCurrentSnapshot(void)` | 99 | Exported Function
`public: static long __cdecl DP_DRIVE::QueryNtfsSupportInfo(void * __ptr64,unsigned char * __ptr64)` | 221 | Exported Function
`public: static unsigned char __cdecl AUTOREG::IsEntryPresent(class WSTRING const * __ptr64)` | 157 | Exported Function
`public: static unsigned char __cdecl AUTOREG::IsEntryPresent(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 156 | Exported Function
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,unsigned char)` | 72 | Exported Function
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 71 | Exported Function
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 70 | Exported Function
`public: class MESSAGE * __ptr64 __cdecl IO_DP_DRIVE::GetMessageW(void) __ptr64` | 107 | Exported Function
`public: class MESSAGE * __ptr64 __cdecl SUPERAREA::GetMessageW(void) __ptr64` | 108 | Exported Function
`public: class MEDIA_TRACK_INFORMATION * __ptr64 __cdecl MEDIA_TRACK_INFORMATION::CreateTrack(unsigned long,unsigned char) __ptr64` | 68 | Exported Function
`public: class IO_DP_DRIVE * __ptr64 __cdecl SECRUN::GetDrive(void) __ptr64` | 102 | Exported Function
`public: class IO_DP_DRIVE * __ptr64 __cdecl SUPERAREA::GetDrive(void) __ptr64` | 103 | Exported Function
`public: enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::Format(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned long,unsigned long,unsigned long) __ptr64` | 90 | Exported Function
`public: static class CANNED_SECURITY * __ptr64 __cdecl IFS_SYSTEM::GetCannedSecurity(void)` | 97 | Exported Function
`public: enum FORMAT_ERROR_CODE __cdecl IO_DP_DRIVE::SetDaxAttribute(unsigned char) __ptr64` | 289 | Exported Function
`public: enum _MEDIA_TYPE __cdecl DP_DRIVE::QueryRecommendedMediaType(void)const __ptr64` | 238 | Exported Function
`public: enum DRIVE_TYPE __cdecl DP_DRIVE::QueryDriveType(void)const __ptr64` | 198 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::FormatScaleTotalFreeClusters(unsigned __int64,unsigned __int64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64)` | 92 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsArcSystemPartition(class WSTRING const * __ptr64,unsigned char * __ptr64)` | 153 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::FormatScaleQuickFormatVerify(unsigned __int64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 91 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeUpgrade(class WSTRING const * __ptr64)` | 84 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::FileSetAttributes(class WSTRING const * __ptr64,unsigned long,unsigned long * __ptr64)` | 87 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsTotalDeviceFailure(long)` | 166 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsVolumeDirty(class WSTRING * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 168 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsThisReFS(class BIG_INT,unsigned long,void * __ptr64)` | 165 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsFileSystemEnabled(class WSTRING const * __ptr64,unsigned char * __ptr64)` | 159 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsThisNtfs(class BIG_INT,unsigned long,void * __ptr64)` | 164 | Exported Function
`public: static unsigned char __cdecl DP_DRIVE::QueryMrwSupport(void * __ptr64)` | 219 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::CheckValidSecurityDescriptor(unsigned long,struct _SECURITY_DESCRIPTOR * __ptr64)` | 62 | Exported Function
`public: static unsigned char __cdecl DP_DRIVE::QueryFreeBlocksInLastTrack(void * __ptr64,unsigned long * __ptr64)` | 205 | Exported Function
`public: static unsigned char __cdecl AUTOREG::IsFrontEndPresent(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 160 | Exported Function
`public: static unsigned char __cdecl AUTOREG::PushEntry(class WSTRING const * __ptr64)` | 180 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeCompression(class WSTRING const * __ptr64)` | 82 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeIntegrity(class WSTRING const * __ptr64,unsigned short)` | 83 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::EnableFileSystem(class WSTRING const * __ptr64)` | 81 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::DismountVolume(class WSTRING const * __ptr64)` | 76 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::DosDriveNameToNtDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 78 | Exported Function
`public: __cdecl DIGRAPH::DIGRAPH(void) __ptr64` | 3 | Exported Function
`public: __cdecl DIGRAPH_EDGE::DIGRAPH_EDGE(void) __ptr64` | 4 | Exported Function
`public: __cdecl CANNED_SECURITY::CANNED_SECURITY(void) __ptr64` | 2 | Exported Function
`protected: unsigned char __cdecl VOL_LIODPDRV::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class SUPERAREA * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 148 | Exported Function
`public: __cdecl BLOCK_CACHE::BLOCK_CACHE(void) __ptr64` | 1 | Exported Function
`public: __cdecl MEDIA_TRACK_INFORMATION::MEDIA_TRACK_INFORMATION(void) __ptr64` | 8 | Exported Function
`public: __cdecl MOUNT_POINT_MAP::MOUNT_POINT_MAP(void) __ptr64` | 9 | Exported Function
`public: __cdecl LOG_IO_DP_DRIVE::LOG_IO_DP_DRIVE(void) __ptr64` | 7 | Exported Function
`public: __cdecl DP_DRIVE::DP_DRIVE(void) __ptr64` | 5 | Exported Function
`public: __cdecl INTSTACK::INTSTACK(void) __ptr64` | 6 | Exported Function
`private: __cdecl SNAPSHOT::SNAPSHOT(void) __ptr64` | 19 | Exported Function
`private: long __cdecl SNAPSHOT::Initialize(unsigned short * __ptr64) __ptr64` | 143 | Exported Function
`NotifyFveAfterFormat` | 319 | Exported Function
`GetDefaultFileSystemIfs` | 317 | Exported Function
`InvalidateFve` | 318 | Exported Function
`protected: enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::Initialize(class WSTRING const * __ptr64,class SUPERAREA * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned short,unsigned char,unsigned int,unsigned char) __ptr64` | 147 | Exported Function
`protected: unsigned char __cdecl SUPERAREA::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class MESSAGE * __ptr64) __ptr64` | 145 | Exported Function
`protected: __cdecl VOL_LIODPDRV::VOL_LIODPDRV(void) __ptr64` | 23 | Exported Function
`private: virtual __cdecl SNAPSHOT::~SNAPSHOT(void) __ptr64` | 36 | Exported Function
`protected: __cdecl SUPERAREA::SUPERAREA(void) __ptr64` | 21 | Exported Function
`public: __cdecl WRITEVIEW_CACHE_ENTRY::WRITEVIEW_CACHE_ENTRY(class WRITEVIEW_CACHE * __ptr64,unsigned short) __ptr64` | 25 | Exported Function
`public: __cdecl WRITEVIEW_CACHE_ENTRY::~WRITEVIEW_CACHE_ENTRY(void) __ptr64` | 42 | Exported Function
`public: __cdecl WRITEVIEW_CACHE::WRITEVIEW_CACHE(void) __ptr64` | 24 | Exported Function
`public: __cdecl TLINK::TLINK(void) __ptr64` | 22 | Exported Function
`public: __cdecl WRITE_ONCE_CACHE::WRITE_ONCE_CACHE(void) __ptr64` | 26 | Exported Function
`public: class BIG_INT __cdecl INTSTACK::Look(unsigned long)const __ptr64` | 172 | Exported Function
`public: class BIG_INT __cdecl NUMBER_SET::QueryNumber(class BIG_INT)const __ptr64` | 226 | Exported Function
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetNextDataSlot(void) __ptr64` | 110 | Exported Function
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetData(unsigned short) __ptr64` | 100 | Exported Function
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetData(void * __ptr64) __ptr64` | 101 | Exported Function
`public: __cdecl POW_TRACK::POW_TRACK(void) __ptr64` | 13 | Exported Function
`public: __cdecl READ_AHEAD_CACHE::READ_AHEAD_CACHE(void) __ptr64` | 14 | Exported Function
`public: __cdecl POW_CACHE::POW_CACHE(void) __ptr64` | 12 | Exported Function
`public: __cdecl MOUNT_POINT_TUPLE::MOUNT_POINT_TUPLE(void) __ptr64` | 10 | Exported Function
`public: __cdecl NUMBER_SET::NUMBER_SET(void) __ptr64` | 11 | Exported Function
`public: __cdecl SECRUN::SECRUN(void) __ptr64` | 18 | Exported Function
`public: __cdecl SPARSE_SET::SPARSE_SET(void) __ptr64` | 20 | Exported Function
`public: __cdecl READ_WRITE_CACHE::READ_WRITE_CACHE(void) __ptr64` | 17 | Exported Function
`public: __cdecl READ_CACHE::READ_CACHE(void) __ptr64` | 15 | Exported Function
`public: __cdecl READ_MODIFY_WRITE_CACHE::READ_MODIFY_WRITE_CACHE(void) __ptr64` | 16 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::IsVolumeWriteable(class WSTRING * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 169 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryFreeBlocksInLastTrack(unsigned long * __ptr64) __ptr64` | 204 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryHighestTrackAddress(unsigned long * __ptr64) __ptr64` | 207 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryFirstBlockInLastSession(unsigned long * __ptr64) __ptr64` | 203 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryDiscStatus(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 193 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryFirstBlockInLastNonEmptySession(unsigned long * __ptr64) __ptr64` | 202 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryLastRecordedAddress(unsigned long * __ptr64) __ptr64` | 213 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryLastWritableAddress(unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 214 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryID(struct _GUID * __ptr64,class WSTRING const * __ptr64) __ptr64` | 209 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryHotPlugInfo(void)const __ptr64` | 208 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryID(class WSTRING * __ptr64,class WSTRING const * __ptr64) __ptr64` | 210 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::CreateTrack(unsigned long,unsigned char,enum DP_DRIVE::NwaType) __ptr64` | 67 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::Initialize(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char) __ptr64` | 126 | Exported Function
`public: unsigned char __cdecl DIGRAPH::SearchForMatch(unsigned long,class BITVECTOR * __ptr64,class NUMBER_SET * __ptr64,unsigned char * __ptr64,class BIG_INT * __ptr64) __ptr64` | 279 | Exported Function
`public: unsigned char __cdecl DIGRAPH::QueryParentsWithChildren(class NUMBER_SET * __ptr64,unsigned long)const __ptr64` | 230 | Exported Function
`public: unsigned char __cdecl DIGRAPH::RemoveEdge(unsigned long,unsigned long) __ptr64` | 277 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::IsThinlyProvisioned(void) __ptr64` | 163 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::IsUdfMediaWritable(void) __ptr64` | 167 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::IsBootCriticalVolume(void) __ptr64` | 154 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char) __ptr64` | 125 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::InitializePowTrackConfiguration(unsigned char,unsigned char * __ptr64) __ptr64` | 151 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::ReinitiateBackgroundFormat(void) __ptr64` | 269 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendPowLowLevelFormat(class MESSAGE * __ptr64) __ptr64` | 280 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::ReinitializeDriveParameters(class MESSAGE * __ptr64) __ptr64` | 268 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryVolumeBounds(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 259 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::ReadFormattableCapacity(unsigned char,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 266 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSRequestSenseCmd(struct _SENSE_DATA * __ptr64) __ptr64` | 284 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSTestUnitReadyCmd(struct _SENSE_DATA * __ptr64) __ptr64` | 285 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSModeSenseCmd(struct SONY_MS_MODE_SENSE_DATA * __ptr64) __ptr64` | 283 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSFormatCmd(unsigned char) __ptr64` | 281 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSInquiryCmd(struct SONY_MS_INQUIRY_DATA * __ptr64) __ptr64` | 282 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryRewritableMOSupport(void) __ptr64` | 239 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaHasPow(void) __ptr64` | 251 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryOpenSessionBounds(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 227 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryMediaByte(void)const __ptr64` | 215 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryNextWritableAddress(unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 220 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaSupportsBackgroundFormat(void) __ptr64` | 255 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaSupportsQuickGrow(void) __ptr64` | 256 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsVat(void) __ptr64` | 254 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsLowLevelFormat(void) __ptr64` | 252 | Exported Function
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsSparing(void) __ptr64` | 253 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryServer(unsigned char * __ptr64)` | 243 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryStorageAdapterProperty(void * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64)` | 246 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryProcessPrivateMemory(void * __ptr64,unsigned __int64 * __ptr64)` | 233 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryNtfsVersion(unsigned char * __ptr64,unsigned char * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,void * __ptr64)` | 223 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryProcessorInformation(class DSTRING * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 234 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryVolumeSize(class WSTRING const * __ptr64,unsigned __int64 * __ptr64)` | 261 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::WriteToFile(class WSTRING const * __ptr64,void * __ptr64,unsigned long,unsigned char)` | 316 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QuerySystemVersion(class DSTRING * __ptr64)` | 249 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryStorageDeviceProperty(void * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64)` | 247 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QuerySystemMemory(unsigned long * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64)` | 248 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCluster(unsigned char * __ptr64)` | 187 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryClusterFunctionalLevel(unsigned long * __ptr64,unsigned long * __ptr64)` | 188 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCanonicalNtDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 185 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::NtDeviceNameToDosDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 173 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::NtDriveNameToDosDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 174 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFreeDiskSpace(class WSTRING const * __ptr64,class BIG_INT * __ptr64)` | 206 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryIsSystemUEFI(void)` | 212 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFileSystemNameByHandle(void * __ptr64,class WSTRING * __ptr64,long * __ptr64,class WSTRING * __ptr64)` | 201 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCorruptionState(class WSTRING * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 191 | Exported Function
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFileSystemName(class WSTRING const * __ptr64,class WSTRING * __ptr64,long * __ptr64,class WSTRING * __ptr64)` | 200 | Exported Function
`public: unsigned char __cdecl BLOCK_CACHE::Initialize(class IO_DP_DRIVE * __ptr64) __ptr64` | 122 | Exported Function
`public: unsigned char __cdecl CANNED_SECURITY::Initialize(void) __ptr64` | 123 | Exported Function
`public: unsigned __int64 __cdecl BLOCK_CACHE::GetPerfFreq(void) __ptr64` | 111 | Exported Function
`public: static void __cdecl IFS_SYSTEM::GetSystemTime(struct _TIME_FIELDS * __ptr64)` | 118 | Exported Function
`public: static void __cdecl IFS_SYSTEM::QueryNtfsTime(union _LARGE_INTEGER * __ptr64)` | 222 | Exported Function
`public: unsigned char __cdecl DIGRAPH::QueryChildren(unsigned long,class NUMBER_SET * __ptr64)const __ptr64` | 186 | Exported Function
`public: unsigned char __cdecl DIGRAPH::QueryParents(unsigned long,class NUMBER_SET * __ptr64)const __ptr64` | 229 | Exported Function
`public: unsigned char __cdecl DIGRAPH::Initialize(unsigned long) __ptr64` | 124 | Exported Function
`public: unsigned char __cdecl DIGRAPH::AddEdge(unsigned long,unsigned long) __ptr64` | 49 | Exported Function
`public: unsigned char __cdecl DIGRAPH::EliminateCycles(class CONTAINER * __ptr64,unsigned char * __ptr64) __ptr64` | 80 | Exported Function
`public: static unsigned char __cdecl VOL_LIODPDRV::QueryAutochkTimeOut(unsigned long * __ptr64)` | 181 | Exported Function
`public: static unsigned char __cdecl VOL_LIODPDRV::SetAutochkTimeOut(unsigned long)` | 287 | Exported Function
`public: static unsigned char __cdecl SNAPSHOT::ReleaseVolumeSnapshot(class SNAPSHOT * __ptr64)` | 270 | Exported Function
`public: static unsigned char __cdecl SNAPSHOT::GetSnapshotErrorMessage(long,class WSTRING * __ptr64)` | 113 | Exported Function
`public: static unsigned char __cdecl SNAPSHOT::IsFatalError(long)` | 158 | Exported Function
`public: static void __cdecl DRIVE_CACHE::GetPhaseSubPhase(unsigned short * __ptr64 * __ptr64,unsigned short * __ptr64 * __ptr64)` | 112 | Exported Function
`public: static void __cdecl DRIVE_CACHE::SetPhaseSubPhase(unsigned short * __ptr64,unsigned short * __ptr64)` | 294 | Exported Function
`public: static unsigned long __cdecl SUPERAREA::ComputeVolId(unsigned long)` | 66 | Exported Function
`public: static unsigned char __cdecl WRITEVIEW_BACKINGSTORE::CleanupBackingStore(class WSTRING * __ptr64)` | 64 | Exported Function
`public: static unsigned long __cdecl IFS_SYSTEM::QueryPageSize(void)` | 228 | Exported Function


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d59cc1123ef29d5fa7c0356a845b16e3fbfb681638c182c902283852c4af3188/detection/





MIT License. Copyright (c) 2020 Strontic.


