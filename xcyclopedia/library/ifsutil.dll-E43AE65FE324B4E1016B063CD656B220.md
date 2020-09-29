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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`GetDefaultFileSystemIfs` | 317 (0x13d) | Exported Function | 0x0000000180004440 | 0x00004440
`public: unsigned char __cdecl READ_MODIFY_WRITE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned char,unsigned char) __ptr64` | 140 (0x8c) | Exported Function | 0x000000018001afc0 | 0x0001afc0
`public: unsigned char __cdecl READ_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018001a330 | 0x0001a330
`public: unsigned char __cdecl READ_AHEAD_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long) __ptr64` | 138 (0x8a) | Exported Function | 0x000000018001a600 | 0x0001a600
`public: unsigned char __cdecl POW_CACHE::Initialize(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long) __ptr64` | 136 (0x88) | Exported Function | 0x000000018001ba10 | 0x0001ba10
`public: unsigned char __cdecl POW_CACHE::Initialize(class IO_DP_DRIVE * __ptr64) __ptr64` | 137 (0x89) | Exported Function | 0x000000018001bb20 | 0x0001bb20
`public: unsigned char __cdecl NUMBER_SET::Subtract(class NUMBER_SET * __ptr64,class NUMBER_SET * __ptr64) __ptr64` | 305 (0x131) | Exported Function | 0x000000018001a160 | 0x0001a160
`public: unsigned char __cdecl NUMBER_SET::RemoveAll(void) __ptr64` | 275 (0x113) | Exported Function | 0x0000000180008aa0 | 0x00008aa0
`public: unsigned char __cdecl READ_WRITE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned char) __ptr64` | 141 (0x8d) | Exported Function | 0x0000000180002ef0 | 0x00002ef0
`public: unsigned char __cdecl NUMBER_SET::Remove(class NUMBER_SET const * __ptr64) __ptr64` | 271 (0x10f) | Exported Function | 0x000000018001a070 | 0x0001a070
`public: unsigned char __cdecl NUMBER_SET::Remove(class BIG_INT) __ptr64` | 273 (0x111) | Exported Function | 0x000000018001a140 | 0x0001a140
`public: unsigned char __cdecl NUMBER_SET::QueryContainingRange(class BIG_INT,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 190 (0xbe) | Exported Function | 0x00000001800011c0 | 0x000011c0
`public: unsigned char __cdecl NUMBER_SET::Initialize(void) __ptr64` | 135 (0x87) | Exported Function | 0x0000000180003160 | 0x00003160
`public: unsigned char __cdecl NUMBER_SET::Enumerate(unsigned char,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 85 (0x55) | Exported Function | 0x0000000180019ee0 | 0x00019ee0
`public: unsigned char __cdecl NUMBER_SET::DoesIntersectSet(class BIG_INT,class BIG_INT)const __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180019e50 | 0x00019e50
`public: unsigned char __cdecl NUMBER_SET::CheckAndRemove(class BIG_INT,unsigned char * __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x0000000180019d40 | 0x00019d40
`public: unsigned char __cdecl NUMBER_SET::CheckAndAdd(class BIG_INT,unsigned char * __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x0000000180019bf0 | 0x00019bf0
`public: unsigned char __cdecl NUMBER_SET::Remove(class BIG_INT,class BIG_INT) __ptr64` | 272 (0x110) | Exported Function | 0x000000018001a0d0 | 0x0001a0d0
`public: unsigned char __cdecl NUMBER_SET::Add(class NUMBER_SET const * __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180019b00 | 0x00019b00
`public: unsigned char __cdecl SECRUN::Initialize(class MEM * __ptr64,class IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long) __ptr64` | 142 (0x8e) | Exported Function | 0x00000001800065e0 | 0x000065e0
`public: unsigned char __cdecl SNAPSHOT::QuerySnapshotDiffAreaVolume(class WSTRING * __ptr64) __ptr64` | 245 (0xf5) | Exported Function | 0x000000018001cf50 | 0x0001cf50
`public: unsigned long __cdecl DIGRAPH::QueryNumChildren(unsigned long)const __ptr64` | 224 (0xe0) | Exported Function | 0x00000001800130f0 | 0x000130f0
`public: unsigned char __cdecl WRITEVIEW_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,class DRIVE_CACHE * __ptr64,class WSTRING const * __ptr64,unsigned short,unsigned char,unsigned char) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180025ac0 | 0x00025ac0
`public: unsigned char __cdecl WRITE_ONCE_CACHE::Initialize(class IO_DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned long) __ptr64` | 150 (0x96) | Exported Function | 0x000000018001a950 | 0x0001a950
`public: unsigned char __cdecl VOL_LIODPDRV::SetVolumeLabelAndPrintFormatReport(class WSTRING const * __ptr64,class MESSAGE * __ptr64) __ptr64` | 299 (0x12b) | Exported Function | 0x00000001800236e0 | 0x000236e0
`public: unsigned char __cdecl VOL_LIODPDRV::SetFileSystemName(unsigned short const * __ptr64) __ptr64` | 290 (0x122) | Exported Function | 0x0000000180009910 | 0x00009910
`public: unsigned char __cdecl VOL_LIODPDRV::Recover(class WSTRING const * __ptr64,class MESSAGE * __ptr64) __ptr64` | 267 (0x10b) | Exported Function | 0x0000000180023600 | 0x00023600
`public: unsigned char __cdecl VOL_LIODPDRV::ForceAutochk(unsigned char,unsigned long,unsigned long,unsigned short,class WSTRING const * __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180022960 | 0x00022960
`public: unsigned char __cdecl SNAPSHOT::CheckSnapshotPresence(void) __ptr64` | 61 (0x3d) | Exported Function | 0x000000018001c9a0 | 0x0001c9a0
`public: unsigned char __cdecl VOL_LIODPDRV::ChkDsk(enum FIX_LEVEL,class MESSAGE * __ptr64,unsigned long,unsigned long,unsigned short,unsigned long * __ptr64,class WSTRING const * __ptr64) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180022650 | 0x00022650
`public: unsigned char __cdecl SPARSE_SET::RemoveAll(void) __ptr64` | 276 (0x114) | Exported Function | 0x000000018001d950 | 0x0001d950
`public: unsigned char __cdecl SPARSE_SET::Initialize(void) __ptr64` | 144 (0x90) | Exported Function | 0x000000018001d8e0 | 0x0001d8e0
`public: unsigned char __cdecl SPARSE_SET::CheckAndRemove(class BIG_INT,unsigned char * __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x000000018001d750 | 0x0001d750
`public: unsigned char __cdecl SPARSE_SET::CheckAndAdd(class BIG_INT,unsigned char * __ptr64) __ptr64` | 57 (0x39) | Exported Function | 0x000000018001d620 | 0x0001d620
`public: unsigned char __cdecl SPARSE_SET::Check(class BIG_INT) __ptr64` | 55 (0x37) | Exported Function | 0x000000018001d5b0 | 0x0001d5b0
`public: unsigned char __cdecl SPARSE_SET::Add(class SPARSE_SET const * __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x000000018001d410 | 0x0001d410
`public: unsigned char __cdecl SPARSE_SET::Add(class BIG_INT) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018001d490 | 0x0001d490
`public: unsigned char __cdecl TLINK::Initialize(unsigned short) __ptr64` | 146 (0x92) | Exported Function | 0x000000018001dbc0 | 0x0001dbc0
`public: unsigned char __cdecl NUMBER_SET::Add(class BIG_INT,class BIG_INT) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180019b60 | 0x00019b60
`public: unsigned char __cdecl NUMBER_SET::Add(class BIG_INT) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180019bd0 | 0x00019bd0
`public: unsigned char __cdecl MOUNT_POINT_MAP::SetIsSystemPartition(class WSTRING * __ptr64,unsigned char) __ptr64` | 292 (0x124) | Exported Function | 0x00000001800199c0 | 0x000199c0
`public: unsigned char __cdecl IO_DP_DRIVE::Lock(void) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180002690 | 0x00002690
`public: unsigned char __cdecl IO_DP_DRIVE::IssueDeleteNotification(unsigned __int64,unsigned long) __ptr64` | 170 (0xaa) | Exported Function | 0x00000001800027d0 | 0x000027d0
`public: unsigned char __cdecl IO_DP_DRIVE::IsLocked(void) __ptr64` | 161 (0xa1) | Exported Function | 0x000000018000e4f0 | 0x0000e4f0
`public: unsigned char __cdecl IO_DP_DRIVE::IsDax(void) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180009870 | 0x00009870
`public: unsigned char __cdecl IO_DP_DRIVE::InvalidateVolume(void) __ptr64` | 152 (0x98) | Exported Function | 0x00000001800142d0 | 0x000142d0
`public: unsigned char __cdecl IO_DP_DRIVE::HardWrite(class BIG_INT,unsigned long,void * __ptr64,unsigned char) __ptr64` | 121 (0x79) | Exported Function | 0x0000000180001cc0 | 0x00001cc0
`public: unsigned char __cdecl IO_DP_DRIVE::HardRead(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 120 (0x78) | Exported Function | 0x0000000180013e60 | 0x00013e60
`public: unsigned char __cdecl IO_DP_DRIVE::PowForceAllocation(unsigned long,unsigned long,unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 176 (0xb0) | Exported Function | 0x000000018001f600 | 0x0001f600
`public: unsigned char __cdecl IO_DP_DRIVE::FlushCache(void) __ptr64` | 88 (0x58) | Exported Function | 0x00000001800098d0 | 0x000098d0
`public: unsigned char __cdecl INTSTACK::ReverseCopy(class INTSTACK * __ptr64) __ptr64` | 278 (0x116) | Exported Function | 0x0000000180018fe0 | 0x00018fe0
`public: unsigned char __cdecl INTSTACK::Push(class BIG_INT) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180018f70 | 0x00018f70
`public: unsigned char __cdecl INTSTACK::IsMember(class BIG_INT)const __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180009370 | 0x00009370
`public: unsigned char __cdecl INTSTACK::Initialize(void) __ptr64` | 128 (0x80) | Exported Function | 0x0000000180008b00 | 0x00008b00
`public: unsigned char __cdecl FORMAT_SQM::Initialize(class DP_DRIVE * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long) __ptr64` | 127 (0x7f) | Exported Function | 0x0000000180002280 | 0x00002280
`public: unsigned char __cdecl FORMAT_SQM::Export(int) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180002db0 | 0x00002db0
`public: unsigned char __cdecl DP_DRIVE::WaitForWriteCompletion(class MESSAGE * __ptr64) __ptr64` | 312 (0x138) | Exported Function | 0x0000000180022490 | 0x00022490
`public: unsigned char __cdecl IO_DP_DRIVE::DismountAndLock(void) __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180013770 | 0x00013770
`public: unsigned char __cdecl IO_DP_DRIVE::Prefetch(class BIG_INT,unsigned long) __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180014570 | 0x00014570
`public: unsigned char __cdecl IO_DP_DRIVE::QueryMemoryLimit(unsigned __int64 * __ptr64,unsigned char * __ptr64) __ptr64` | 217 (0xd9) | Exported Function | 0x00000001800146e0 | 0x000146e0
`public: unsigned char __cdecl IO_DP_DRIVE::Read(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 264 (0x108) | Exported Function | 0x0000000180009160 | 0x00009160
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryVolumeName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 260 (0x104) | Exported Function | 0x00000001800198f0 | 0x000198f0
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryIsSystemPartition(class WSTRING * __ptr64,unsigned char * __ptr64) __ptr64` | 211 (0xd3) | Exported Function | 0x0000000180019830 | 0x00019830
`public: unsigned char __cdecl MOUNT_POINT_MAP::QueryDriveName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 197 (0xc5) | Exported Function | 0x0000000180019760 | 0x00019760
`public: unsigned char __cdecl MOUNT_POINT_MAP::Initialize(void) __ptr64` | 134 (0x86) | Exported Function | 0x00000001800196d0 | 0x000196d0
`public: unsigned char __cdecl MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING * __ptr64,class WSTRING * __ptr64,unsigned char * __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180019630 | 0x00019630
`public: unsigned char __cdecl MOUNT_POINT_MAP::GetAt(unsigned long,class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x00000001800195a0 | 0x000195a0
`public: unsigned char __cdecl MOUNT_POINT_MAP::AddVolumeName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x00000001800193b0 | 0x000193b0
`public: unsigned char __cdecl MOUNT_POINT_MAP::AddDriveName(class WSTRING * __ptr64,class WSTRING * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180019210 | 0x00019210
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::SetSystemId(unsigned char) __ptr64` | 297 (0x129) | Exported Function | 0x0000000180009390 | 0x00009390
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(void * __ptr64,unsigned char) __ptr64` | 129 (0x81) | Exported Function | 0x00000001800142a0 | 0x000142a0
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 130 (0x82) | Exported Function | 0x00000001800142b0 | 0x000142b0
`public: unsigned char __cdecl LOG_IO_DP_DRIVE::Initialize(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 131 (0x83) | Exported Function | 0x00000001800142c0 | 0x000142c0
`public: unsigned char __cdecl IO_DP_DRIVE::Write(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 313 (0x139) | Exported Function | 0x0000000180008150 | 0x00008150
`public: unsigned char __cdecl IO_DP_DRIVE::VerifyRead(class BIG_INT,unsigned long,void * __ptr64) __ptr64` | 309 (0x135) | Exported Function | 0x0000000180015760 | 0x00015760
`public: unsigned char __cdecl IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT,class NUMBER_SET * __ptr64) __ptr64` | 308 (0x134) | Exported Function | 0x0000000180015450 | 0x00015450
`public: unsigned char __cdecl IO_DP_DRIVE::Verify(class BIG_INT,class BIG_INT) __ptr64` | 307 (0x133) | Exported Function | 0x0000000180015300 | 0x00015300
`public: unsigned char __cdecl IO_DP_DRIVE::SqmExport(class WSTRING const * __ptr64,unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 303 (0x12f) | Exported Function | 0x0000000180014b20 | 0x00014b20
`public: unsigned long __cdecl DIGRAPH::QueryNumParents(unsigned long)const __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180013170 | 0x00013170
`public: unsigned char __cdecl DP_DRIVE::WaitForUnit(class MESSAGE * __ptr64) __ptr64` | 311 (0x137) | Exported Function | 0x0000000180022400 | 0x00022400
`public: unsigned long __cdecl DP_DRIVE::QueryPhysicalSectorSize(void) __ptr64` | 232 (0xe8) | Exported Function | 0x000000018000e540 | 0x0000e540
`public: unsigned long __cdecl IO_DP_DRIVE::GetIoErrorDisplayFlags(void)const __ptr64` | 106 (0x6a) | Exported Function | 0x000000018000e400 | 0x0000e400
`public: void __cdecl IO_DP_DRIVE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180014680 | 0x00014680
`public: void __cdecl IO_DP_DRIVE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180013740 | 0x00013740
`public: void __cdecl INTSTACK::Pop(unsigned long) __ptr64` | 175 (0xaf) | Exported Function | 0x0000000180018f20 | 0x00018f20
`public: void __cdecl DP_DRIVE::SetSectors(class BIG_INT) __ptr64` | 296 (0x128) | Exported Function | 0x0000000180014b00 | 0x00014b00
`public: void __cdecl DP_DRIVE::SetLastStatus(long) __ptr64` | 293 (0x125) | Exported Function | 0x000000018000e660 | 0x0000e660
`public: void __cdecl DP_DRIVE::CloseDriveHandle(void) __ptr64` | 65 (0x41) | Exported Function | 0x00000001800043f0 | 0x000043f0
`public: void __cdecl BIG_INT::Set(unsigned char,unsigned char const * __ptr64) __ptr64` | 286 (0x11e) | Exported Function | 0x0000000180008be0 | 0x00008be0
`public: void __cdecl IO_DP_DRIVE::QueryReadAndVerifiedUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 235 (0xeb) | Exported Function | 0x000000018000e550 | 0x0000e550
`public: void __cdecl BIG_INT::QueryCompressedInteger(unsigned char * __ptr64,unsigned char * __ptr64)const __ptr64` | 189 (0xbd) | Exported Function | 0x00000001800080f0 | 0x000080f0
`public: void * __ptr64 __cdecl TLINK::GetSortedNext(void * __ptr64) __ptr64` | 117 (0x75) | Exported Function | 0x000000018000e4d0 | 0x0000e4d0
`public: void * __ptr64 __cdecl TLINK::GetSortedFirst(void) __ptr64` | 116 (0x74) | Exported Function | 0x000000018000e4b0 | 0x0000e4b0
`public: void * __ptr64 __cdecl TLINK::GetNext(void * __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x000000018000e440 | 0x0000e440
`public: void * __ptr64 __cdecl TLINK::GetFirst(void) __ptr64` | 105 (0x69) | Exported Function | 0x000000018000e3e0 | 0x0000e3e0
`public: void * __ptr64 __cdecl TLINK::GetBuffer(void * __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x000000018000e370 | 0x0000e370
`public: void * __ptr64 __cdecl IO_DP_DRIVE::SetVerifyHandle(void * __ptr64) __ptr64` | 298 (0x12a) | Exported Function | 0x0000000180014b10 | 0x00014b10
`public: void * __ptr64 __cdecl IO_DP_DRIVE::QueryVerifyHandle(void) __ptr64` | 258 (0x102) | Exported Function | 0x00000001800149b0 | 0x000149b0
`public: void * __ptr64 __cdecl TLINK::QueryDisjointRangeAndAssignBuffer(class BIG_INT * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,void * __ptr64,unsigned long,void * __ptr64) __ptr64` | 195 (0xc3) | Exported Function | 0x000000018001dc40 | 0x0001dc40
`public: void * __ptr64 __cdecl DP_DRIVE::QueryDriveHandle(void)const __ptr64` | 196 (0xc4) | Exported Function | 0x000000018000e500 | 0x0000e500
`public: void __cdecl IO_DP_DRIVE::QueryReadUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 237 (0xed) | Exported Function | 0x000000018000e5a0 | 0x0000e5a0
`public: void __cdecl IO_DP_DRIVE::SetCache(class DRIVE_CACHE * __ptr64) __ptr64` | 288 (0x120) | Exported Function | 0x00000001800097d0 | 0x000097d0
`RegisterExtensionCallbacks` | 321 (0x141) | Exported Function | 0x0000000180015e20 | 0x00015e20
`QueryPersistRegistryKeyValueWithFallback` | 320 (0x140) | Exported Function | 0x000000018000e7e0 | 0x0000e7e0
`public: void __cdecl WRITEVIEW_CACHE::Remove(class WRITEVIEW_CACHE_ENTRY * __ptr64) __ptr64` | 274 (0x112) | Exported Function | 0x00000001800272c0 | 0x000272c0
`public: void __cdecl WRITEVIEW_CACHE::Purge(class BIG_INT,unsigned long) __ptr64` | 178 (0xb2) | Exported Function | 0x0000000180009980 | 0x00009980
`public: void __cdecl WRITEVIEW_CACHE::DestroyWrites(void) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180024c70 | 0x00024c70
`public: void __cdecl WRITEVIEW_CACHE::Destroy(void) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: void __cdecl WRITEVIEW_CACHE::Delete(class WRITEVIEW_CACHE_ENTRY * __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180024b00 | 0x00024b00
`public: void __cdecl IO_DP_DRIVE::QueryWriteUsage(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 263 (0x107) | Exported Function | 0x000000018000e600 | 0x0000e600
`public: void __cdecl TLINK::TraverseLinkList(void) __ptr64` | 306 (0x132) | Exported Function | 0x0000000180009980 | 0x00009980
`public: void __cdecl TLINK::ShellSort(void) __ptr64` | 300 (0x12c) | Exported Function | 0x000000018001dcb0 | 0x0001dcb0
`public: void __cdecl TLINK::CheckLinkList(void) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180009980 | 0x00009980
`public: void __cdecl SPARSE_SET::DumpHashTable(void) __ptr64` | 79 (0x4f) | Exported Function | 0x0000000180009980 | 0x00009980
`public: void __cdecl NUMBER_SET::QueryDisjointRange(unsigned long,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 194 (0xc2) | Exported Function | 0x0000000180019f30 | 0x00019f30
`public: void __cdecl MEDIA_TRACK_INFORMATION_SORTED_BY_SIZE::Initialize(class MEDIA_TRACK_INFORMATION * __ptr64) __ptr64` | 133 (0x85) | Exported Function | 0x000000018000e4e0 | 0x0000e4e0
`public: void __cdecl MEDIA_TRACK_INFORMATION::Initialize(struct _TRACK_INFORMATION2 * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x000000018001ea90 | 0x0001ea90
`public: void __cdecl IO_DP_DRIVE::SetIoErrorDisplayFlags(unsigned long) __ptr64` | 291 (0x123) | Exported Function | 0x000000018000e650 | 0x0000e650
`public: void __cdecl TLINK::Sort(void) __ptr64` | 301 (0x12d) | Exported Function | 0x000000018000e6e0 | 0x0000e6e0
`public: void * __ptr64 __cdecl CANNED_SECURITY::GetCannedSecurityDescriptor(enum _CANNED_SECURITY_TYPE,unsigned long * __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x00000001800090f0 | 0x000090f0
`public: virtual void __cdecl WRITEVIEW_CACHE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 184 (0xb8) | Exported Function | 0x0000000180026e50 | 0x00026e50
`public: virtual void __cdecl WRITEVIEW_CACHE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800244c0 | 0x000244c0
`public: virtual __cdecl SECRUN::~SECRUN(void) __ptr64` | 35 (0x23) | Exported Function | 0x00000001800063a0 | 0x000063a0
`public: virtual __cdecl NUMBER_SET::~NUMBER_SET(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180006bf0 | 0x00006bf0
`public: virtual __cdecl MOUNT_POINT_MAP::~MOUNT_POINT_MAP(void) __ptr64` | 33 (0x21) | Exported Function | 0x00000001800190f0 | 0x000190f0
`public: virtual __cdecl LOG_IO_DP_DRIVE::~LOG_IO_DP_DRIVE(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180013620 | 0x00013620
`public: virtual __cdecl INTSTACK::~INTSTACK(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180008b70 | 0x00008b70
`public: virtual __cdecl DP_DRIVE::~DP_DRIVE(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180005690 | 0x00005690
`public: virtual __cdecl DIGRAPH::~DIGRAPH(void) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800126a0 | 0x000126a0
`public: virtual __cdecl SPARSE_SET::~SPARSE_SET(void) __ptr64` | 37 (0x25) | Exported Function | 0x000000018001d360 | 0x0001d360
`public: virtual __cdecl CANNED_SECURITY::~CANNED_SECURITY(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180006a10 | 0x00006a10
`public: unsigned short const * __ptr64 __cdecl VOL_LIODPDRV::GetFileSystemName(void) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180023570 | 0x00023570
`public: unsigned short __cdecl TLINK::QuerySize(void)const __ptr64` | 244 (0xf4) | Exported Function | 0x000000018000e5f0 | 0x0000e5f0
`public: unsigned short __cdecl TLINK::QueryMemberCount(void)const __ptr64` | 216 (0xd8) | Exported Function | 0x000000018000e530 | 0x0000e530
`public: unsigned short __cdecl DP_DRIVE::QueryEccBlockSizeInSectors(void) __ptr64` | 199 (0xc7) | Exported Function | 0x000000018001fb50 | 0x0001fb50
`public: unsigned short * __ptr64 __cdecl SNAPSHOT::GetSnapshotNtDeviceName(void) __ptr64` | 115 (0x73) | Exported Function | 0x000000018001ca70 | 0x0001ca70
`public: unsigned short * __ptr64 __cdecl SNAPSHOT::GetSnapshotGlobalDeviceName(void) __ptr64` | 114 (0x72) | Exported Function | 0x000000018001ca50 | 0x0001ca50
`public: unsigned long __cdecl POW_CACHE::QuerySectorSize(void) __ptr64` | 241 (0xf1) | Exported Function | 0x000000018001bbe0 | 0x0001bbe0
`public: virtual __cdecl BLOCK_CACHE::~BLOCK_CACHE(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180010190 | 0x00010190
`public: virtual __cdecl SUPERAREA::~SUPERAREA(void) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180006380 | 0x00006380
`public: virtual __cdecl TLINK::~TLINK(void) __ptr64` | 39 (0x27) | Exported Function | 0x000000018001da90 | 0x0001da90
`public: virtual __cdecl VOL_LIODPDRV::~VOL_LIODPDRV(void) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180002220 | 0x00002220
`public: virtual void __cdecl BLOCK_CACHE::QueryCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 182 (0xb6) | Exported Function | 0x00000001800117c0 | 0x000117c0
`public: virtual void __cdecl BLOCK_CACHE::AdjustCacheSize(unsigned __int64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180010520 | 0x00010520
`public: virtual unsigned long __cdecl DP_DRIVE::QueryWriteBlockSize(void)const __ptr64` | 262 (0x106) | Exported Function | 0x00000001800149c0 | 0x000149c0
`public: virtual unsigned long __cdecl DP_DRIVE::QuerySectorSize(void)const __ptr64` | 240 (0xf0) | Exported Function | 0x0000000180008190 | 0x00008190
`public: virtual unsigned char __cdecl WRITEVIEW_CACHE::SqmExport(unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 304 (0x130) | Exported Function | 0x0000000180027330 | 0x00027330
`public: virtual unsigned char __cdecl WRITEVIEW_CACHE::QueryMemoryLimit(unsigned __int64 * __ptr64,unsigned char * __ptr64) __ptr64` | 218 (0xda) | Exported Function | 0x0000000180026e70 | 0x00026e70
`public: virtual unsigned char __cdecl SECRUN::Write(void) __ptr64` | 314 (0x13a) | Exported Function | 0x00000001800090a0 | 0x000090a0
`public: virtual unsigned char __cdecl SECRUN::VerifyRead(unsigned char * __ptr64) __ptr64` | 310 (0x136) | Exported Function | 0x000000018001c120 | 0x0001c120
`public: virtual unsigned char __cdecl SECRUN::Read(void) __ptr64` | 265 (0x109) | Exported Function | 0x00000001800092b0 | 0x000092b0
`public: virtual unsigned char __cdecl DP_DRIVE::QueryPartitionInfo(struct _PARTITION_INFORMATION_EX * __ptr64) __ptr64` | 231 (0xe7) | Exported Function | 0x0000000180009300 | 0x00009300
`public: virtual unsigned char __cdecl BLOCK_CACHE::SqmExport(unsigned char (__cdecl*)(void * __ptr64,unsigned long,unsigned char,char * __ptr64,...),void * __ptr64) __ptr64` | 302 (0x12e) | Exported Function | 0x0000000180011d60 | 0x00011d60
`public: virtual long __cdecl DP_DRIVE::QueryTierCount(unsigned long * __ptr64) __ptr64` | 250 (0xfa) | Exported Function | 0x0000000180004030 | 0x00004030
`public: virtual long __cdecl DP_DRIVE::QueryReadCacheSize(unsigned __int64 * __ptr64) __ptr64` | 236 (0xec) | Exported Function | 0x0000000180003e90 | 0x00003e90
`public: virtual long __cdecl DP_DRIVE::QueryDataRedundancyCount(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 192 (0xc0) | Exported Function | 0x00000001800091a0 | 0x000091a0
`public: virtual enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::WriteEntireDrive(class MESSAGE * __ptr64,void * __ptr64,unsigned long,unsigned int,unsigned int) __ptr64` | 315 (0x13b) | Exported Function | 0x00000001800239f0 | 0x000239f0
`public: virtual class BIG_INT __cdecl DP_DRIVE::QuerySectors(void)const __ptr64` | 242 (0xf2) | Exported Function | 0x0000000180008df0 | 0x00008df0
`public: virtual __cdecl WRITEVIEW_CACHE::~WRITEVIEW_CACHE(void) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180023fe0 | 0x00023fe0
`public: unsigned long __cdecl DP_DRIVE::QueryUdfMediaType(void) __ptr64` | 257 (0x101) | Exported Function | 0x0000000180020e40 | 0x00020e40
`RestoreThreadExecutionState` | 322 (0x142) | Exported Function | 0x0000000180023ce0 | 0x00023ce0
`public: unsigned char __cdecl DP_DRIVE::SetPowTrackConfiguration(unsigned char) __ptr64` | 295 (0x127) | Exported Function | 0x0000000180021de0 | 0x00021de0
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSRequestSenseCmd(struct _SENSE_DATA * __ptr64) __ptr64` | 284 (0x11c) | Exported Function | 0x000000018001c6d0 | 0x0001c6d0
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,unsigned char)` | 72 (0x48) | Exported Function | 0x000000018000ee50 | 0x0000ee50
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 70 (0x46) | Exported Function | 0x000000018000ebb0 | 0x0000ebb0
`public: static unsigned char __cdecl AUTOREG::DeleteEntry(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 71 (0x47) | Exported Function | 0x000000018000ee40 | 0x0000ee40
`public: static unsigned char __cdecl AUTOREG::AddEntry(class WSTRING const * __ptr64)` | 50 (0x32) | Exported Function | 0x000000018000eac0 | 0x0000eac0
`public: static long __cdecl SUPERAREA::GenerateLabelNotification(class WSTRING const * __ptr64,class WSTRING * __ptr64,struct _FILE_FS_SIZE_INFORMATION * __ptr64,struct _FILE_FS_VOLUME_INFORMATION * __ptr64)` | 93 (0x5d) | Exported Function | 0x0000000180004210 | 0x00004210
`public: static long __cdecl SNAPSHOT::GetVolumeSnapshot(class WSTRING * __ptr64,class SNAPSHOT * __ptr64 * __ptr64)` | 119 (0x77) | Exported Function | 0x000000018001ca90 | 0x0001ca90
`public: static long __cdecl DP_DRIVE::QueryNtfsSupportInfo(void * __ptr64,unsigned char * __ptr64)` | 221 (0xdd) | Exported Function | 0x0000000180005580 | 0x00005580
`public: static unsigned char __cdecl AUTOREG::IsEntryPresent(class WSTRING const * __ptr64)` | 157 (0x9d) | Exported Function | 0x000000018000f1c0 | 0x0000f1c0
`public: static class SNAPSHOT * __ptr64 __cdecl SNAPSHOT::GetCurrentSnapshot(void)` | 99 (0x63) | Exported Function | 0x000000018001ca20 | 0x0001ca20
`public: enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::Format(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned long,unsigned long,unsigned long) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180002b30 | 0x00002b30
`public: enum FORMAT_ERROR_CODE __cdecl IO_DP_DRIVE::SetDaxAttribute(unsigned char) __ptr64` | 289 (0x121) | Exported Function | 0x0000000180002910 | 0x00002910
`public: enum DRIVE_TYPE __cdecl DP_DRIVE::QueryDriveType(void)const __ptr64` | 198 (0xc6) | Exported Function | 0x000000018000e510 | 0x0000e510
`public: enum _MEDIA_TYPE __cdecl DP_DRIVE::QueryRecommendedMediaType(void)const __ptr64` | 238 (0xee) | Exported Function | 0x0000000180014820 | 0x00014820
`public: class MESSAGE * __ptr64 __cdecl SUPERAREA::GetMessageW(void) __ptr64` | 108 (0x6c) | Exported Function | 0x000000018000e420 | 0x0000e420
`public: class MESSAGE * __ptr64 __cdecl IO_DP_DRIVE::GetMessageW(void) __ptr64` | 107 (0x6b) | Exported Function | 0x000000018000e410 | 0x0000e410
`public: class MEDIA_TRACK_INFORMATION * __ptr64 __cdecl MEDIA_TRACK_INFORMATION::CreateTrack(unsigned long,unsigned char) __ptr64` | 68 (0x44) | Exported Function | 0x000000018000e280 | 0x0000e280
`public: static class CANNED_SECURITY * __ptr64 __cdecl IFS_SYSTEM::GetCannedSecurity(void)` | 97 (0x61) | Exported Function | 0x0000000180008040 | 0x00008040
`public: class IO_DP_DRIVE * __ptr64 __cdecl SUPERAREA::GetDrive(void) __ptr64` | 103 (0x67) | Exported Function | 0x000000018000e3d0 | 0x0000e3d0
`public: static unsigned char __cdecl AUTOREG::IsEntryPresent(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 156 (0x9c) | Exported Function | 0x000000018000f010 | 0x0000f010
`public: static unsigned char __cdecl AUTOREG::PushEntry(class WSTRING const * __ptr64)` | 180 (0xb4) | Exported Function | 0x000000018000f500 | 0x0000f500
`public: static unsigned char __cdecl IFS_SYSTEM::IsThisReFS(class BIG_INT,unsigned long,void * __ptr64)` | 165 (0xa5) | Exported Function | 0x0000000180016cb0 | 0x00016cb0
`public: static unsigned char __cdecl IFS_SYSTEM::IsThisNtfs(class BIG_INT,unsigned long,void * __ptr64)` | 164 (0xa4) | Exported Function | 0x0000000180016c90 | 0x00016c90
`public: static unsigned char __cdecl IFS_SYSTEM::IsFileSystemEnabled(class WSTRING const * __ptr64,unsigned char * __ptr64)` | 159 (0x9f) | Exported Function | 0x0000000180009930 | 0x00009930
`public: static unsigned char __cdecl IFS_SYSTEM::IsArcSystemPartition(class WSTRING const * __ptr64,unsigned char * __ptr64)` | 153 (0x99) | Exported Function | 0x0000000180016630 | 0x00016630
`public: static unsigned char __cdecl IFS_SYSTEM::FormatScaleTotalFreeClusters(unsigned __int64,unsigned __int64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64)` | 92 (0x5c) | Exported Function | 0x0000000180008cb0 | 0x00008cb0
`public: static unsigned char __cdecl IFS_SYSTEM::FormatScaleQuickFormatVerify(unsigned __int64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 91 (0x5b) | Exported Function | 0x0000000180008c60 | 0x00008c60
`public: static unsigned char __cdecl IFS_SYSTEM::FileSetAttributes(class WSTRING const * __ptr64,unsigned long,unsigned long * __ptr64)` | 87 (0x57) | Exported Function | 0x0000000180016500 | 0x00016500
`public: static unsigned char __cdecl AUTOREG::IsFrontEndPresent(class WSTRING const * __ptr64,class WSTRING const * __ptr64)` | 160 (0xa0) | Exported Function | 0x000000018000f2b0 | 0x0000f2b0
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeUpgrade(class WSTRING const * __ptr64)` | 84 (0x54) | Exported Function | 0x00000001800099d0 | 0x000099d0
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeCompression(class WSTRING const * __ptr64)` | 82 (0x52) | Exported Function | 0x00000001800160d0 | 0x000160d0
`public: static unsigned char __cdecl IFS_SYSTEM::EnableFileSystem(class WSTRING const * __ptr64)` | 81 (0x51) | Exported Function | 0x0000000180009990 | 0x00009990
`public: static unsigned char __cdecl IFS_SYSTEM::DosDriveNameToNtDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 78 (0x4e) | Exported Function | 0x0000000180009440 | 0x00009440
`public: static unsigned char __cdecl IFS_SYSTEM::DismountVolume(class WSTRING const * __ptr64)` | 76 (0x4c) | Exported Function | 0x0000000180015f70 | 0x00015f70
`public: static unsigned char __cdecl IFS_SYSTEM::CheckValidSecurityDescriptor(unsigned long,struct _SECURITY_DESCRIPTOR * __ptr64)` | 62 (0x3e) | Exported Function | 0x0000000180015f50 | 0x00015f50
`public: static unsigned char __cdecl DP_DRIVE::QueryMrwSupport(void * __ptr64)` | 219 (0xdb) | Exported Function | 0x0000000180014710 | 0x00014710
`public: static unsigned char __cdecl DP_DRIVE::QueryFreeBlocksInLastTrack(void * __ptr64,unsigned long * __ptr64)` | 205 (0xcd) | Exported Function | 0x0000000180020150 | 0x00020150
`public: static unsigned char __cdecl IFS_SYSTEM::EnableVolumeIntegrity(class WSTRING const * __ptr64,unsigned short)` | 83 (0x53) | Exported Function | 0x00000001800162a0 | 0x000162a0
`public: class IO_DP_DRIVE * __ptr64 __cdecl SECRUN::GetDrive(void) __ptr64` | 102 (0x66) | Exported Function | 0x000000018000e3c0 | 0x0000e3c0
`public: class BIG_INT __cdecl NUMBER_SET::QueryNumber(class BIG_INT)const __ptr64` | 226 (0xe2) | Exported Function | 0x0000000180019fe0 | 0x00019fe0
`public: class BIG_INT __cdecl INTSTACK::Look(unsigned long)const __ptr64` | 172 (0xac) | Exported Function | 0x0000000180018ee0 | 0x00018ee0
`public: __cdecl INTSTACK::INTSTACK(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180008b20 | 0x00008b20
`public: __cdecl DP_DRIVE::DP_DRIVE(void) __ptr64` | 5 (0x5) | Exported Function | 0x00000001800056d0 | 0x000056d0
`public: __cdecl DIGRAPH_EDGE::DIGRAPH_EDGE(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180012640 | 0x00012640
`public: __cdecl DIGRAPH::DIGRAPH(void) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800125c0 | 0x000125c0
`public: __cdecl CANNED_SECURITY::CANNED_SECURITY(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180006980 | 0x00006980
`public: __cdecl BLOCK_CACHE::BLOCK_CACHE(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180010000 | 0x00010000
`protected: unsigned char __cdecl VOL_LIODPDRV::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class SUPERAREA * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 148 (0x94) | Exported Function | 0x0000000180023590 | 0x00023590
`public: __cdecl LOG_IO_DP_DRIVE::LOG_IO_DP_DRIVE(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180004d20 | 0x00004d20
`protected: unsigned char __cdecl SUPERAREA::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class MESSAGE * __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x0000000180006590 | 0x00006590
`protected: __cdecl VOL_LIODPDRV::VOL_LIODPDRV(void) __ptr64` | 23 (0x17) | Exported Function | 0x00000001800021b0 | 0x000021b0
`protected: __cdecl SUPERAREA::SUPERAREA(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180006330 | 0x00006330
`private: virtual __cdecl SNAPSHOT::~SNAPSHOT(void) __ptr64` | 36 (0x24) | Exported Function | 0x000000018001c8e0 | 0x0001c8e0
`private: long __cdecl SNAPSHOT::Initialize(unsigned short * __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`private: __cdecl SNAPSHOT::SNAPSHOT(void) __ptr64` | 19 (0x13) | Exported Function | 0x000000018001c890 | 0x0001c890
`NotifyFveAfterFormat` | 319 (0x13f) | Exported Function | 0x0000000180008e40 | 0x00008e40
`InvalidateFve` | 318 (0x13e) | Exported Function | 0x0000000180009750 | 0x00009750
`protected: enum FORMAT_ERROR_CODE __cdecl VOL_LIODPDRV::Initialize(class WSTRING const * __ptr64,class SUPERAREA * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned short,unsigned char,unsigned int,unsigned char) __ptr64` | 147 (0x93) | Exported Function | 0x0000000180002090 | 0x00002090
`public: __cdecl MEDIA_TRACK_INFORMATION::MEDIA_TRACK_INFORMATION(void) __ptr64` | 8 (0x8) | Exported Function | 0x000000018001dde0 | 0x0001dde0
`public: __cdecl MOUNT_POINT_MAP::MOUNT_POINT_MAP(void) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180019020 | 0x00019020
`public: __cdecl MOUNT_POINT_TUPLE::MOUNT_POINT_TUPLE(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180019070 | 0x00019070
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetNextDataSlot(void) __ptr64` | 110 (0x6e) | Exported Function | 0x000000018001db90 | 0x0001db90
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetData(void * __ptr64) __ptr64` | 101 (0x65) | Exported Function | 0x000000018000e3b0 | 0x0000e3b0
`public: class BIG_INT & __ptr64 __cdecl TLINK::GetData(unsigned short) __ptr64` | 100 (0x64) | Exported Function | 0x000000018000e380 | 0x0000e380
`public: __cdecl WRITEVIEW_CACHE_ENTRY::~WRITEVIEW_CACHE_ENTRY(void) __ptr64` | 42 (0x2a) | Exported Function | 0x00000001800240e0 | 0x000240e0
`public: __cdecl WRITEVIEW_CACHE_ENTRY::WRITEVIEW_CACHE_ENTRY(class WRITEVIEW_CACHE * __ptr64,unsigned short) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180023e70 | 0x00023e70
`public: __cdecl WRITEVIEW_CACHE::WRITEVIEW_CACHE(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180023d40 | 0x00023d40
`public: __cdecl WRITE_ONCE_CACHE::WRITE_ONCE_CACHE(void) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018001a810 | 0x0001a810
`public: __cdecl TLINK::TLINK(void) __ptr64` | 22 (0x16) | Exported Function | 0x000000018001da40 | 0x0001da40
`public: __cdecl SPARSE_SET::SPARSE_SET(void) __ptr64` | 20 (0x14) | Exported Function | 0x000000018001d310 | 0x0001d310
`public: __cdecl SECRUN::SECRUN(void) __ptr64` | 18 (0x12) | Exported Function | 0x00000001800063d0 | 0x000063d0
`public: __cdecl READ_WRITE_CACHE::READ_WRITE_CACHE(void) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180002e30 | 0x00002e30
`public: __cdecl READ_MODIFY_WRITE_CACHE::READ_MODIFY_WRITE_CACHE(void) __ptr64` | 16 (0x10) | Exported Function | 0x000000018001aab0 | 0x0001aab0
`public: __cdecl READ_CACHE::READ_CACHE(void) __ptr64` | 15 (0xf) | Exported Function | 0x000000018001a220 | 0x0001a220
`public: __cdecl READ_AHEAD_CACHE::READ_AHEAD_CACHE(void) __ptr64` | 14 (0xe) | Exported Function | 0x000000018001a500 | 0x0001a500
`public: __cdecl POW_TRACK::POW_TRACK(void) __ptr64` | 13 (0xd) | Exported Function | 0x000000018001b540 | 0x0001b540
`public: __cdecl POW_CACHE::POW_CACHE(void) __ptr64` | 12 (0xc) | Exported Function | 0x000000018001b4f0 | 0x0001b4f0
`public: __cdecl NUMBER_SET::NUMBER_SET(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180006ba0 | 0x00006ba0
`public: static unsigned char __cdecl IFS_SYSTEM::IsTotalDeviceFailure(long)` | 166 (0xa6) | Exported Function | 0x0000000180017230 | 0x00017230
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSTestUnitReadyCmd(struct _SENSE_DATA * __ptr64) __ptr64` | 285 (0x11d) | Exported Function | 0x000000018001c760 | 0x0001c760
`public: static unsigned char __cdecl IFS_SYSTEM::IsVolumeDirty(class WSTRING * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 168 (0xa8) | Exported Function | 0x0000000180017260 | 0x00017260
`public: static unsigned char __cdecl IFS_SYSTEM::NtDeviceNameToDosDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 173 (0xad) | Exported Function | 0x0000000180017450 | 0x00017450
`public: unsigned char __cdecl DP_DRIVE::QueryID(struct _GUID * __ptr64,class WSTRING const * __ptr64) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180003390 | 0x00003390
`public: unsigned char __cdecl DP_DRIVE::QueryID(class WSTRING * __ptr64,class WSTRING const * __ptr64) __ptr64` | 210 (0xd2) | Exported Function | 0x00000001800146c0 | 0x000146c0
`public: unsigned char __cdecl DP_DRIVE::QueryHotPlugInfo(void)const __ptr64` | 208 (0xd0) | Exported Function | 0x000000018000e520 | 0x0000e520
`public: unsigned char __cdecl DP_DRIVE::QueryHighestTrackAddress(unsigned long * __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x00000001800202b0 | 0x000202b0
`public: unsigned char __cdecl DP_DRIVE::QueryFreeBlocksInLastTrack(unsigned long * __ptr64) __ptr64` | 204 (0xcc) | Exported Function | 0x0000000180020140 | 0x00020140
`public: unsigned char __cdecl DP_DRIVE::QueryFirstBlockInLastSession(unsigned long * __ptr64) __ptr64` | 203 (0xcb) | Exported Function | 0x0000000180020000 | 0x00020000
`public: unsigned char __cdecl DP_DRIVE::QueryFirstBlockInLastNonEmptySession(unsigned long * __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x000000018001fee0 | 0x0001fee0
`public: unsigned char __cdecl DP_DRIVE::QueryLastRecordedAddress(unsigned long * __ptr64) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180020340 | 0x00020340
`public: unsigned char __cdecl DP_DRIVE::QueryDiscStatus(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 193 (0xc1) | Exported Function | 0x000000018001fa60 | 0x0001fa60
`public: unsigned char __cdecl DP_DRIVE::IsThinlyProvisioned(void) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180009560 | 0x00009560
`public: unsigned char __cdecl DP_DRIVE::IsBootCriticalVolume(void) __ptr64` | 154 (0x9a) | Exported Function | 0x0000000180014420 | 0x00014420
`public: unsigned char __cdecl DP_DRIVE::InitializePowTrackConfiguration(unsigned char,unsigned char * __ptr64) __ptr64` | 151 (0x97) | Exported Function | 0x000000018001ebb0 | 0x0001ebb0
`public: unsigned char __cdecl DP_DRIVE::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char) __ptr64` | 125 (0x7d) | Exported Function | 0x0000000180013e90 | 0x00013e90
`public: unsigned char __cdecl DP_DRIVE::Initialize(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char) __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180004b60 | 0x00004b60
`public: unsigned char __cdecl DP_DRIVE::CreateTrack(unsigned long,unsigned char,enum DP_DRIVE::NwaType) __ptr64` | 67 (0x43) | Exported Function | 0x000000018001e400 | 0x0001e400
`public: unsigned char __cdecl DIGRAPH::SearchForMatch(unsigned long,class BITVECTOR * __ptr64,class NUMBER_SET * __ptr64,unsigned char * __ptr64,class BIG_INT * __ptr64) __ptr64` | 279 (0x117) | Exported Function | 0x0000000180013530 | 0x00013530
`public: unsigned char __cdecl DP_DRIVE::IsUdfMediaWritable(void) __ptr64` | 167 (0xa7) | Exported Function | 0x000000018001ecd0 | 0x0001ecd0
`public: unsigned char __cdecl DIGRAPH::RemoveEdge(unsigned long,unsigned long) __ptr64` | 277 (0x115) | Exported Function | 0x0000000180013450 | 0x00013450
`public: unsigned char __cdecl DP_DRIVE::QueryLastWritableAddress(unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 214 (0xd6) | Exported Function | 0x0000000180020490 | 0x00020490
`public: unsigned char __cdecl DP_DRIVE::QueryNextWritableAddress(unsigned long * __ptr64,enum DP_DRIVE::NwaType) __ptr64` | 220 (0xdc) | Exported Function | 0x0000000180020540 | 0x00020540
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSModeSenseCmd(struct SONY_MS_MODE_SENSE_DATA * __ptr64) __ptr64` | 283 (0x11b) | Exported Function | 0x000000018001c630 | 0x0001c630
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSInquiryCmd(struct SONY_MS_INQUIRY_DATA * __ptr64) __ptr64` | 282 (0x11a) | Exported Function | 0x000000018001c5a0 | 0x0001c5a0
`public: unsigned char __cdecl DP_DRIVE::SendSonyMSFormatCmd(unsigned char) __ptr64` | 281 (0x119) | Exported Function | 0x000000018001c500 | 0x0001c500
`public: unsigned char __cdecl DP_DRIVE::SendPowLowLevelFormat(class MESSAGE * __ptr64) __ptr64` | 280 (0x118) | Exported Function | 0x0000000180021c10 | 0x00021c10
`public: unsigned char __cdecl DP_DRIVE::ReinitiateBackgroundFormat(void) __ptr64` | 269 (0x10d) | Exported Function | 0x00000001800216f0 | 0x000216f0
`public: unsigned char __cdecl DP_DRIVE::ReinitializeDriveParameters(class MESSAGE * __ptr64) __ptr64` | 268 (0x10c) | Exported Function | 0x00000001800149d0 | 0x000149d0
`public: unsigned char __cdecl DP_DRIVE::ReadFormattableCapacity(unsigned char,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 266 (0x10a) | Exported Function | 0x00000001800211e0 | 0x000211e0
`public: unsigned char __cdecl DP_DRIVE::QueryMediaByte(void)const __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180009890 | 0x00009890
`public: unsigned char __cdecl DP_DRIVE::QueryVolumeBounds(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 259 (0x103) | Exported Function | 0x0000000180020e50 | 0x00020e50
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaSupportsBackgroundFormat(void) __ptr64` | 255 (0xff) | Exported Function | 0x0000000180020e00 | 0x00020e00
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsVat(void) __ptr64` | 254 (0xfe) | Exported Function | 0x0000000180020de0 | 0x00020de0
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsSparing(void) __ptr64` | 253 (0xfd) | Exported Function | 0x0000000180020dc0 | 0x00020dc0
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaNeedsLowLevelFormat(void) __ptr64` | 252 (0xfc) | Exported Function | 0x0000000180020db0 | 0x00020db0
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaHasPow(void) __ptr64` | 251 (0xfb) | Exported Function | 0x0000000180020d90 | 0x00020d90
`public: unsigned char __cdecl DP_DRIVE::QueryRewritableMOSupport(void) __ptr64` | 239 (0xef) | Exported Function | 0x0000000180014870 | 0x00014870
`public: unsigned char __cdecl DP_DRIVE::QueryOpenSessionBounds(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 227 (0xe3) | Exported Function | 0x00000001800206c0 | 0x000206c0
`public: unsigned char __cdecl DP_DRIVE::QueryUdfMediaSupportsQuickGrow(void) __ptr64` | 256 (0x100) | Exported Function | 0x0000000180020e10 | 0x00020e10
`public: unsigned char __cdecl DIGRAPH::QueryParentsWithChildren(class NUMBER_SET * __ptr64,unsigned long)const __ptr64` | 230 (0xe6) | Exported Function | 0x0000000180013330 | 0x00013330
`public: unsigned char __cdecl DIGRAPH::QueryParents(unsigned long,class NUMBER_SET * __ptr64)const __ptr64` | 229 (0xe5) | Exported Function | 0x0000000180013240 | 0x00013240
`public: unsigned char __cdecl DIGRAPH::QueryChildren(unsigned long,class NUMBER_SET * __ptr64)const __ptr64` | 186 (0xba) | Exported Function | 0x0000000180013020 | 0x00013020
`public: static unsigned char __cdecl IFS_SYSTEM::QuerySystemMemory(unsigned long * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64,unsigned __int64 * __ptr64)` | 248 (0xf8) | Exported Function | 0x00000001800187a0 | 0x000187a0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryStorageDeviceProperty(void * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64)` | 247 (0xf7) | Exported Function | 0x00000001800023b0 | 0x000023b0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryStorageAdapterProperty(void * __ptr64,class DSTRING * __ptr64,class DSTRING * __ptr64)` | 246 (0xf6) | Exported Function | 0x0000000180002530 | 0x00002530
`public: static unsigned char __cdecl IFS_SYSTEM::QueryServer(unsigned char * __ptr64)` | 243 (0xf3) | Exported Function | 0x0000000180007f70 | 0x00007f70
`public: static unsigned char __cdecl IFS_SYSTEM::QueryProcessPrivateMemory(void * __ptr64,unsigned __int64 * __ptr64)` | 233 (0xe9) | Exported Function | 0x0000000180018410 | 0x00018410
`public: static unsigned char __cdecl IFS_SYSTEM::QueryProcessorInformation(class DSTRING * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 234 (0xea) | Exported Function | 0x00000001800184e0 | 0x000184e0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryNtfsVersion(unsigned char * __ptr64,unsigned char * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,void * __ptr64)` | 223 (0xdf) | Exported Function | 0x0000000180005e60 | 0x00005e60
`public: static unsigned char __cdecl IFS_SYSTEM::QuerySystemVersion(class DSTRING * __ptr64)` | 249 (0xf9) | Exported Function | 0x00000001800188e0 | 0x000188e0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryIsSystemUEFI(void)` | 212 (0xd4) | Exported Function | 0x0000000180018220 | 0x00018220
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFileSystemNameByHandle(void * __ptr64,class WSTRING * __ptr64,long * __ptr64,class WSTRING * __ptr64)` | 201 (0xc9) | Exported Function | 0x0000000180017ec0 | 0x00017ec0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFileSystemName(class WSTRING const * __ptr64,class WSTRING * __ptr64,long * __ptr64,class WSTRING * __ptr64)` | 200 (0xc8) | Exported Function | 0x0000000180001fe0 | 0x00001fe0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCorruptionState(class WSTRING * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 191 (0xbf) | Exported Function | 0x0000000180017ca0 | 0x00017ca0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryClusterFunctionalLevel(unsigned long * __ptr64,unsigned long * __ptr64)` | 188 (0xbc) | Exported Function | 0x0000000180017b70 | 0x00017b70
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCluster(unsigned char * __ptr64)` | 187 (0xbb) | Exported Function | 0x0000000180017af0 | 0x00017af0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryCanonicalNtDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 185 (0xb9) | Exported Function | 0x00000001800179b0 | 0x000179b0
`public: static unsigned char __cdecl IFS_SYSTEM::NtDriveNameToDosDriveName(class WSTRING const * __ptr64,class WSTRING * __ptr64)` | 174 (0xae) | Exported Function | 0x00000001800176d0 | 0x000176d0
`public: static unsigned char __cdecl IFS_SYSTEM::QueryFreeDiskSpace(class WSTRING const * __ptr64,class BIG_INT * __ptr64)` | 206 (0xce) | Exported Function | 0x0000000180018160 | 0x00018160
`public: static unsigned char __cdecl IFS_SYSTEM::QueryVolumeSize(class WSTRING const * __ptr64,unsigned __int64 * __ptr64)` | 261 (0x105) | Exported Function | 0x0000000180018980 | 0x00018980
`public: static unsigned char __cdecl IFS_SYSTEM::WriteToFile(class WSTRING const * __ptr64,void * __ptr64,unsigned long,unsigned char)` | 316 (0x13c) | Exported Function | 0x0000000180018b50 | 0x00018b50
`public: static unsigned char __cdecl SNAPSHOT::GetSnapshotErrorMessage(long,class WSTRING * __ptr64)` | 113 (0x71) | Exported Function | 0x000000018001ca30 | 0x0001ca30
`public: unsigned char __cdecl DIGRAPH::Initialize(unsigned long) __ptr64` | 124 (0x7c) | Exported Function | 0x0000000180012f70 | 0x00012f70
`public: unsigned char __cdecl DIGRAPH::EliminateCycles(class CONTAINER * __ptr64,unsigned char * __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180012df0 | 0x00012df0
`public: unsigned char __cdecl DIGRAPH::AddEdge(unsigned long,unsigned long) __ptr64` | 49 (0x31) | Exported Function | 0x00000001800127c0 | 0x000127c0
`public: unsigned char __cdecl CANNED_SECURITY::Initialize(void) __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180007650 | 0x00007650
`public: unsigned char __cdecl BLOCK_CACHE::Initialize(class IO_DP_DRIVE * __ptr64) __ptr64` | 122 (0x7a) | Exported Function | 0x0000000180010ff0 | 0x00010ff0
`public: unsigned __int64 __cdecl BLOCK_CACHE::GetPerfFreq(void) __ptr64` | 111 (0x6f) | Exported Function | 0x000000018000e450 | 0x0000e450
`public: static void __cdecl IFS_SYSTEM::QueryNtfsTime(union _LARGE_INTEGER * __ptr64)` | 222 (0xde) | Exported Function | 0x00000001800098f0 | 0x000098f0
`public: static void __cdecl IFS_SYSTEM::GetSystemTime(struct _TIME_FIELDS * __ptr64)` | 118 (0x76) | Exported Function | 0x00000001800165f0 | 0x000165f0
`public: static void __cdecl DRIVE_CACHE::SetPhaseSubPhase(unsigned short * __ptr64,unsigned short * __ptr64)` | 294 (0x126) | Exported Function | 0x000000018000e670 | 0x0000e670
`public: static void __cdecl DRIVE_CACHE::GetPhaseSubPhase(unsigned short * __ptr64 * __ptr64,unsigned short * __ptr64 * __ptr64)` | 112 (0x70) | Exported Function | 0x000000018000e460 | 0x0000e460
`public: static unsigned long __cdecl SUPERAREA::ComputeVolId(unsigned long)` | 66 (0x42) | Exported Function | 0x0000000180008d70 | 0x00008d70
`public: static unsigned long __cdecl IFS_SYSTEM::QueryPageSize(void)` | 228 (0xe4) | Exported Function | 0x00000001800183b0 | 0x000183b0
`public: static unsigned char __cdecl WRITEVIEW_BACKINGSTORE::CleanupBackingStore(class WSTRING * __ptr64)` | 64 (0x40) | Exported Function | 0x00000001800246c0 | 0x000246c0
`public: static unsigned char __cdecl VOL_LIODPDRV::SetAutochkTimeOut(unsigned long)` | 287 (0x11f) | Exported Function | 0x0000000180023690 | 0x00023690
`public: static unsigned char __cdecl VOL_LIODPDRV::QueryAutochkTimeOut(unsigned long * __ptr64)` | 181 (0xb5) | Exported Function | 0x00000001800235f0 | 0x000235f0
`public: static unsigned char __cdecl SNAPSHOT::ReleaseVolumeSnapshot(class SNAPSHOT * __ptr64)` | 270 (0x10e) | Exported Function | 0x000000018001d070 | 0x0001d070
`public: static unsigned char __cdecl SNAPSHOT::IsFatalError(long)` | 158 (0x9e) | Exported Function | 0x000000018001cf10 | 0x0001cf10
`public: static unsigned char __cdecl IFS_SYSTEM::IsVolumeWriteable(class WSTRING * __ptr64,unsigned char * __ptr64,long * __ptr64)` | 169 (0xa9) | Exported Function | 0x00000001800173c0 | 0x000173c0
`WritePersistRegistryKeyValue` | 323 (0x143) | Exported Function | 0x000000018000e9f0 | 0x0000e9f0


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


