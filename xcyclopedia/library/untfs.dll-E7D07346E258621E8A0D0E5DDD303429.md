---
title: untfs.dll | NTFS Utility DLL
excerpt: What is untfs.dll?
---

# untfs.dll 

* File Path: `C:\Windows\SysWOW64\untfs.dll`
* Description: NTFS Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `E7D07346E258621E8A0D0E5DDD303429`
SHA1 | `B6E6F8047B3EB59D9C250FBABAEBEA1504594295`
SHA256 | `E3E5BAD8F802A2811A912043E878BAE0F29BDDAED6D27DEC340F0D147534FABE`
SHA384 | `08B2FDFC231A2F94BB2F11E07FC5DC8F805E16A20415405437550244A0A3820097E45EFBEC075D2EAE71843C7AA13C1F`
SHA512 | `2FD124470EE0E4A90BCF1A0C36E08F8C65A176DA70985B736609CF66A512007C02C11660AC89AB3103FECF74CC768C53EBBF08260203BCAD9D55C1DEEDC53E69`
SSDEEP | `12288:wvf5B62TJxOivT0pumKPg4vvhfENGDtgPYco0/kQ:wvfnd1x7vT0puPg4vv9ENG5oj/k`
IMP | `C9767640961FDDF0566CEA4FD2554E39`
PESHA1 | `FFCF9FDB9780A47C37F011329757E9D963BDE936`
PE256 | `CFF875A81E065559D0CDF899895632A314B6368ABA466E723F0C9F5DFEC00771`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 156 (0x9c) | Exported Function | 0x44991cf0 | 0x00011cf0
`public: unsigned char __thiscall NTFS_INDEX_TREE::Save(class NTFS_FILE_RECORD_SEGMENT *)` | 144 (0x90) | Exported Function | 0x449b3980 | 0x00033980
`public: unsigned char __thiscall NTFS_LOG_FILE::CreateDataAttribute(class BIG_INT,unsigned long,class NTFS_BITMAP *)` | 54 (0x36) | Exported Function | 0x449b7000 | 0x00037000
`public: unsigned char __thiscall NTFS_LOG_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 85 (0x55) | Exported Function | 0x449b6f70 | 0x00036f70
`public: unsigned char __thiscall NTFS_MASTER_FILE_TABLE::AllocateFileRecordSegment(class BIG_INT *,unsigned char)` | 47 (0x2f) | Exported Function | 0x449b7da0 | 0x00037da0
`public: unsigned char __thiscall NTFS_MASTER_FILE_TABLE::Extend(unsigned long)` | 56 (0x38) | Exported Function | 0x449b8080 | 0x00038080
`public: unsigned char __thiscall NTFS_MFT_FILE::Flush(void)` | 58 (0x3a) | Exported Function | 0x449b8790 | 0x00038790
`public: unsigned char __thiscall NTFS_MFT_FILE::Initialize(enum FIX_LEVEL,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,class NTFS_ATTRIBUTE *)` | 86 (0x56) | Exported Function | 0x449b8260 | 0x00038260
`public: unsigned char __thiscall NTFS_MFT_INFO::Initialize(class BIG_INT,class NTFS_UPCASE_TABLE *,unsigned char,unsigned char,unsigned __int64)` | 87 (0x57) | Exported Function | 0x449b8f90 | 0x00038f90
`public: unsigned char __thiscall NTFS_MFT_INFO::Initialize(void)` | 88 (0x58) | Exported Function | 0x449b9040 | 0x00039040
`public: unsigned char __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 89 (0x59) | Exported Function | 0x449b94b0 | 0x000394b0
`public: unsigned char __thiscall NTFS_SA::CreateElementaryStructures(class NTFS_BITMAP *,unsigned long,unsigned long,unsigned long,unsigned long,class NUMBER_SET const *,unsigned char,unsigned char,unsigned char,unsigned char,unsigned char,unsigned long,class MESSAGE *,struct BIOS_PARAMETER_BLOCK *,class WSTRING const *,unsigned char)` | 55 (0x37) | Exported Function | 0x44995470 | 0x00015470
`public: unsigned char __thiscall NTFS_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *,class BIG_INT,class BIG_INT,unsigned long,unsigned char)` | 90 (0x5a) | Exported Function | 0x449cfe70 | 0x0004fe70
`public: unsigned char __thiscall NTFS_SA::QueryFrsFromPath(enum FIX_LEVEL,class WSTRING const *,class NTFS_MASTER_FILE_TABLE *,class NTFS_BITMAP *,class NTFS_FILE_RECORD_SEGMENT *,unsigned char *,unsigned char *)` | 120 (0x78) | Exported Function | 0x449d07e0 | 0x000507e0
`public: unsigned char __thiscall NTFS_SA::Read(class MESSAGE *)` | 132 (0x84) | Exported Function | 0x449d04b0 | 0x000504b0
`public: unsigned char __thiscall NTFS_SA::SetVolumeFlag(unsigned short,unsigned char *)` | 147 (0x93) | Exported Function | 0x449d1910 | 0x00051910
`public: unsigned char __thiscall NTFS_SA::TakeCensus(class NTFS_MASTER_FILE_TABLE *,unsigned long,struct NTFS_CENSUS_INFO *)` | 149 (0x95) | Exported Function | 0x449d1af0 | 0x00051af0
`public: unsigned char __thiscall NTFS_SA::WriteRemainingBootCode(void)` | 155 (0x9b) | Exported Function | 0x44995390 | 0x00015390
`public: unsigned char __thiscall NTFS_INDEX_TREE::ResetIterator(unsigned char)` | 140 (0x8c) | Exported Function | 0x449b5ef0 | 0x00035ef0
`public: unsigned char __thiscall NTFS_UPCASE_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 91 (0x5b) | Exported Function | 0x449ed760 | 0x0006d760
`public: unsigned char __thiscall NTFS_INDEX_TREE::ResetIterator(struct _INDEX_ENTRY const *,unsigned char)` | 141 (0x8d) | Exported Function | 0x449b5fd0 | 0x00035fd0
`public: unsigned char __thiscall NTFS_INDEX_TREE::QueryEntry(unsigned long,void *,unsigned long,struct _INDEX_ENTRY * *,class NTFS_INDEX_BUFFER * *,unsigned char *)` | 114 (0x72) | Exported Function | 0x449b36c0 | 0x000336c0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryFileSizes(class BIG_INT *,class BIG_INT *,unsigned char *)` | 118 (0x76) | Exported Function | 0x4499bd90 | 0x0001bd90
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *,unsigned long)` | 80 (0x50) | Exported Function | 0x449a0510 | 0x00020510
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 81 (0x51) | Exported Function | 0x449a0390 | 0x00020390
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 82 (0x52) | Exported Function | 0x449a0420 | 0x00020420
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(struct _FILE_RECORD_SEGMENT_HEADER *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 79 (0x4f) | Exported Function | 0x449a04b0 | 0x000204b0
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Prefetch(class BIG_INT,class BIG_INT)` | 105 (0x69) | Exported Function | 0x449a1ec0 | 0x00021ec0
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::QueryAttributeList(class NTFS_ATTRIBUTE_LIST *)` | 108 (0x6c) | Exported Function | 0x449a2250 | 0x00022250
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Read(class BIG_INT)` | 129 (0x81) | Exported Function | 0x449a1c30 | 0x00021c30
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadAgain(class BIG_INT)` | 134 (0x86) | Exported Function | 0x449a1d30 | 0x00021d30
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadAt(class BIG_INT)` | 135 (0x87) | Exported Function | 0x449a1c70 | 0x00021c70
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadNext(class BIG_INT)` | 137 (0x89) | Exported Function | 0x449a1c90 | 0x00021c90
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::SafeQueryAttribute(unsigned long,class NTFS_ATTRIBUTE *,class NTFS_ATTRIBUTE *,class WSTRING *)` | 143 (0x8f) | Exported Function | 0x449a2410 | 0x00022410
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Write(void)` | 153 (0x99) | Exported Function | 0x449a1d40 | 0x00021d40
`public: unsigned char __thiscall NTFS_INDEX_TREE::CopyIterator(class NTFS_INDEX_TREE *)` | 52 (0x34) | Exported Function | 0x449b63c0 | 0x000363c0
`public: unsigned char __thiscall NTFS_INDEX_TREE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,unsigned long,class NTFS_FILE_RECORD_SEGMENT *,class WSTRING const *)` | 84 (0x54) | Exported Function | 0x449b31f0 | 0x000331f0
`public: unsigned char __thiscall NTFS_INDEX_TREE::Initialize(unsigned long,class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,unsigned long,unsigned long,unsigned long,class WSTRING const *)` | 83 (0x53) | Exported Function | 0x449b34b0 | 0x000334b0
`public: unsigned char __thiscall NTFS_INDEX_TREE::InsertEntry(unsigned long,void *,struct _MFT_SEGMENT_REFERENCE,unsigned char)` | 96 (0x60) | Exported Function | 0x449b3730 | 0x00033730
`public: unsigned char __thiscall NTFS_INDEX_TREE::QueryFileReference(unsigned long,void *,unsigned long,struct _MFT_SEGMENT_REFERENCE *,unsigned char *)` | 117 (0x75) | Exported Function | 0x449b3610 | 0x00033610
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryDuplicatedInformation(struct _DUPLICATED_INFORMATION *)` | 113 (0x71) | Exported Function | 0x4499edc0 | 0x0001edc0
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(class NTFS_ATTRIBUTE *,unsigned __int64 *)` | 93 (0x5d) | Exported Function | 0x449ed3e0 | 0x0006d3e0
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(void)` | 94 (0x5e) | Exported Function | 0x449ed4f0 | 0x0006d4f0
`public: virtual __thiscall NTFS_SA::~NTFS_SA(void)` | 39 (0x27) | Exported Function | 0x449cfe30 | 0x0004fe30
`public: virtual __thiscall NTFS_UPCASE_FILE::~NTFS_UPCASE_FILE(void)` | 40 (0x28) | Exported Function | 0x44991640 | 0x00011640
`public: virtual __thiscall NTFS_UPCASE_TABLE::~NTFS_UPCASE_TABLE(void)` | 41 (0x29) | Exported Function | 0x449ed300 | 0x0006d300
`public: virtual __thiscall NTFS_VOLUME_FILE::~NTFS_VOLUME_FILE(void)` | 42 (0x2a) | Exported Function | 0x449efaa0 | 0x0006faa0
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::GrowSparse(class BIG_INT,class NTFS_BITMAP *,unsigned char)` | 63 (0x3f) | Exported Function | 0x4498a5e0 | 0x0000a5e0
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::InsertIntoFile(class NTFS_FILE_RECORD_SEGMENT *,class NTFS_BITMAP *)` | 97 (0x61) | Exported Function | 0x44989c50 | 0x00009c50
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::MakeNonresident(class NTFS_BITMAP *)` | 103 (0x67) | Exported Function | 0x44989fe0 | 0x00009fe0
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::Resize(class BIG_INT,class NTFS_BITMAP *)` | 142 (0x8e) | Exported Function | 0x4498a2f0 | 0x0000a2f0
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::SetSparse(class BIG_INT,class NTFS_BITMAP *,unsigned char)` | 146 (0x92) | Exported Function | 0x4498a4d0 | 0x0000a4d0
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::Write(void const *,class BIG_INT,unsigned long,unsigned long *,class NTFS_BITMAP *)` | 150 (0x96) | Exported Function | 0x4498ad60 | 0x0000ad60
`public: virtual unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Write(void)` | 152 (0x98) | Exported Function | 0x4499d910 | 0x0001d910
`public: virtual unsigned char __thiscall NTFS_FRS_STRUCTURE::Read(void)` | 130 (0x82) | Exported Function | 0x449a1b80 | 0x00021b80
`public: virtual unsigned char __thiscall NTFS_MFT_FILE::Read(void)` | 131 (0x83) | Exported Function | 0x449b8640 | 0x00038640
`public: virtual unsigned char __thiscall NTFS_SA::Read(void)` | 133 (0x85) | Exported Function | 0x449d1a90 | 0x00051a90
`public: void * __thiscall NTFS_FRS_STRUCTURE::GetNextAttributeRecord(void const *,class MESSAGE *,unsigned char *)` | 61 (0x3d) | Exported Function | 0x449a1f40 | 0x00021f40
`public: void __thiscall NTFS_CLUSTER_RUN::Relocate(class BIG_INT)` | 139 (0x8b) | Exported Function | 0x44991be0 | 0x00011be0
`Recover` | 167 (0xa7) | Exported Function | 0x44993c70 | 0x00013c70
`public: virtual __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::~NTFS_REFLECTED_MASTER_FILE_TABLE(void)` | 38 (0x26) | Exported Function | 0x44991640 | 0x00011640
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(unsigned short *,unsigned long)` | 92 (0x5c) | Exported Function | 0x449ed490 | 0x0006d490
`public: virtual __thiscall NTFS_MFT_INFO::~NTFS_MFT_INFO(void)` | 37 (0x25) | Exported Function | 0x449b8f60 | 0x00038f60
`public: virtual __thiscall NTFS_LOG_FILE::~NTFS_LOG_FILE(void)` | 35 (0x23) | Exported Function | 0x44991640 | 0x00011640
`public: unsigned char __thiscall NTFS_VOLUME_FILE::Initialize(class LOG_IO_DP_DRIVE *,class NTFS_MASTER_FILE_TABLE *,class NTFS_FILE_RECORD_SEGMENT *,class NTFS_INDEX_TREE *,struct _VOLUME_INFORMATION *,class WSTRING *,enum FIX_LEVEL)` | 95 (0x5f) | Exported Function | 0x449efad0 | 0x0006fad0
`public: unsigned long __thiscall NTFS_EXTENT_LIST::QueryNumberOfExtents(void)const ` | 124 (0x7c) | Exported Function | 0x449950b0 | 0x000150b0
`public: unsigned long __thiscall NTFS_SA::QueryClusterFactor(void)const ` | 110 (0x6e) | Exported Function | 0x449d1ad0 | 0x00051ad0
`public: unsigned short __thiscall NTFS_SA::QueryVolumeFlagsAndLabel(unsigned char *,unsigned char *,unsigned char *,class WSTRING *)` | 127 (0x7f) | Exported Function | 0x449d0c00 | 0x00050c00
`public: virtual __thiscall NTFS_ATTRIBUTE::~NTFS_ATTRIBUTE(void)` | 22 (0x16) | Exported Function | 0x44988f50 | 0x00008f50
`public: virtual __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::~NTFS_ATTRIBUTE_DEFINITION_TABLE(void)` | 23 (0x17) | Exported Function | 0x449887a0 | 0x000087a0
`public: virtual __thiscall NTFS_ATTRIBUTE_LIST::~NTFS_ATTRIBUTE_LIST(void)` | 24 (0x18) | Exported Function | 0x4498d370 | 0x0000d370
`public: virtual __thiscall NTFS_ATTRIBUTE_RECORD::~NTFS_ATTRIBUTE_RECORD(void)` | 25 (0x19) | Exported Function | 0x4498e540 | 0x0000e540
`public: virtual __thiscall NTFS_BAD_CLUSTER_FILE::~NTFS_BAD_CLUSTER_FILE(void)` | 26 (0x1a) | Exported Function | 0x44990a90 | 0x00010a90
`public: virtual __thiscall NTFS_BITMAP::~NTFS_BITMAP(void)` | 27 (0x1b) | Exported Function | 0x449b9c60 | 0x00039c60
`public: virtual __thiscall NTFS_BITMAP_FILE::~NTFS_BITMAP_FILE(void)` | 28 (0x1c) | Exported Function | 0x44991640 | 0x00011640
`public: virtual __thiscall NTFS_BOOT_FILE::~NTFS_BOOT_FILE(void)` | 29 (0x1d) | Exported Function | 0x44991640 | 0x00011640
`public: virtual __thiscall NTFS_CLUSTER_RUN::~NTFS_CLUSTER_RUN(void)` | 30 (0x1e) | Exported Function | 0x44991b40 | 0x00011b40
`public: virtual __thiscall NTFS_EXTENT_LIST::~NTFS_EXTENT_LIST(void)` | 31 (0x1f) | Exported Function | 0x44994070 | 0x00014070
`public: virtual __thiscall NTFS_FILE_RECORD_SEGMENT::~NTFS_FILE_RECORD_SEGMENT(void)` | 32 (0x20) | Exported Function | 0x44998350 | 0x00018350
`public: virtual __thiscall NTFS_FRS_STRUCTURE::~NTFS_FRS_STRUCTURE(void)` | 33 (0x21) | Exported Function | 0x449a0320 | 0x00020320
`public: virtual __thiscall NTFS_INDEX_TREE::~NTFS_INDEX_TREE(void)` | 34 (0x22) | Exported Function | 0x449b3060 | 0x00033060
`public: virtual __thiscall NTFS_MFT_FILE::~NTFS_MFT_FILE(void)` | 36 (0x24) | Exported Function | 0x449b81f0 | 0x000381f0
`SetOriginalVolumeName` | 145 (0x91) | Exported Function | 0x449920c0 | 0x000120c0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttributeListAttribute(class NTFS_ATTRIBUTE *,unsigned char *)` | 109 (0x6d) | Exported Function | 0x4499f7f0 | 0x0001f7f0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttribute(class NTFS_ATTRIBUTE *,unsigned char *,unsigned long,class WSTRING const *)` | 106 (0x6a) | Exported Function | 0x4499b8e0 | 0x0001b8e0
`public: __thiscall NTFS_EXTENT_LIST::NTFS_EXTENT_LIST(void)` | 10 (0xa) | Exported Function | 0x44994010 | 0x00014010
`public: __thiscall NTFS_FILE_RECORD_SEGMENT::NTFS_FILE_RECORD_SEGMENT(void)` | 11 (0xb) | Exported Function | 0x44998300 | 0x00018300
`public: __thiscall NTFS_FRS_STRUCTURE::NTFS_FRS_STRUCTURE(void)` | 12 (0xc) | Exported Function | 0x449a02d0 | 0x000202d0
`public: __thiscall NTFS_INDEX_TREE::NTFS_INDEX_TREE(void)` | 13 (0xd) | Exported Function | 0x449b2ff0 | 0x00032ff0
`public: __thiscall NTFS_LOG_FILE::NTFS_LOG_FILE(void)` | 14 (0xe) | Exported Function | 0x449b6f40 | 0x00036f40
`public: __thiscall NTFS_MFT_FILE::NTFS_MFT_FILE(void)` | 15 (0xf) | Exported Function | 0x449b8180 | 0x00038180
`public: __thiscall NTFS_MFT_INFO::NTFS_MFT_INFO(void)` | 16 (0x10) | Exported Function | 0x449b8eb0 | 0x00038eb0
`public: __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::NTFS_REFLECTED_MASTER_FILE_TABLE(void)` | 17 (0x11) | Exported Function | 0x449b9480 | 0x00039480
`public: __thiscall NTFS_SA::NTFS_SA(void)` | 18 (0x12) | Exported Function | 0x449cfd20 | 0x0004fd20
`public: __thiscall NTFS_UPCASE_FILE::NTFS_UPCASE_FILE(void)` | 19 (0x13) | Exported Function | 0x449ed730 | 0x0006d730
`public: __thiscall NTFS_UPCASE_TABLE::NTFS_UPCASE_TABLE(void)` | 20 (0x14) | Exported Function | 0x449ed2d0 | 0x0006d2d0
`public: __thiscall NTFS_VOLUME_FILE::NTFS_VOLUME_FILE(void)` | 21 (0x15) | Exported Function | 0x449efa70 | 0x0006fa70
`public: class BIG_INT __thiscall NTFS_ATTRIBUTE::QueryClustersAllocated(void)const ` | 111 (0x6f) | Exported Function | 0x4498c7b0 | 0x0000c7b0
`public: static struct _MFT_SEGMENT_REFERENCE __stdcall NTFS_MFT_INFO::QuerySegmentReference(void *)` | 126 (0x7e) | Exported Function | 0x44985910 | 0x00005910
`public: static unsigned char __stdcall NTFS_MFT_INFO::CompareDupInfo(void *,struct _FILE_NAME *)` | 48 (0x30) | Exported Function | 0x44985930 | 0x00005930
`public: static unsigned char __stdcall NTFS_MFT_INFO::CompareFileName(void *,unsigned long,struct _FILE_NAME *,unsigned short *)` | 49 (0x31) | Exported Function | 0x449b90a0 | 0x000390a0
`public: static unsigned char __stdcall NTFS_MFT_INFO::QueryFlags(void *,unsigned short)` | 119 (0x77) | Exported Function | 0x44985960 | 0x00005960
`public: __thiscall NTFS_CLUSTER_RUN::NTFS_CLUSTER_RUN(void)` | 9 (0x9) | Exported Function | 0x44991b00 | 0x00011b00
`public: static unsigned char __stdcall NTFS_SA::GetRootFrsIndex(enum FIX_LEVEL,class NTFS_MFT_FILE *,class NTFS_FILE_RECORD_SEGMENT *,class NTFS_INDEX_TREE *)` | 62 (0x3e) | Exported Function | 0x449c3db0 | 0x00043db0
`public: __thiscall NTFS_BOOT_FILE::NTFS_BOOT_FILE(void)` | 8 (0x8) | Exported Function | 0x44991810 | 0x00011810
`public: __thiscall NTFS_BITMAP::NTFS_BITMAP(void)` | 6 (0x6) | Exported Function | 0x449b9bf0 | 0x00039bf0
`ChkdskEx` | 157 (0x9d) | Exported Function | 0x449923c0 | 0x000123c0
`CreateFormatCorruptionRecordContext` | 158 (0x9e) | Exported Function | 0x44985980 | 0x00005980
`DeleteFormatCorruptionRecordContext` | 159 (0x9f) | Exported Function | 0x449859c0 | 0x000059c0
`Extend` | 160 (0xa0) | Exported Function | 0x44993e10 | 0x00013e10
`Format` | 161 (0xa1) | Exported Function | 0x449932e0 | 0x000132e0
`FormatCorruptionRecordA` | 162 (0xa2) | Exported Function | 0x449859f0 | 0x000059f0
`FormatCorruptionRecordW` | 163 (0xa3) | Exported Function | 0x44985a00 | 0x00005a00
`FormatEx` | 164 (0xa4) | Exported Function | 0x44993660 | 0x00013660
`GetFilesystemInformation` | 165 (0xa5) | Exported Function | 0x449930f0 | 0x000130f0
`NtfsUpcaseCompare` | 166 (0xa6) | Exported Function | 0x449ed5a0 | 0x0006d5a0
`private: static void __stdcall NTFS_MFT_INFO::ComputeDupInfoSignature(struct _DUPLICATED_INFORMATION *,unsigned char * const)` | 50 (0x32) | Exported Function | 0x449b9390 | 0x00039390
`private: static void __stdcall NTFS_MFT_INFO::ComputeFileNameSignature(unsigned long,struct _FILE_NAME *,unsigned char * const)` | 51 (0x33) | Exported Function | 0x449b9330 | 0x00039330
`public: __thiscall NTFS_ATTRIBUTE::NTFS_ATTRIBUTE(void)` | 1 (0x1) | Exported Function | 0x44988ef0 | 0x00008ef0
`public: __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::NTFS_ATTRIBUTE_DEFINITION_TABLE(void)` | 2 (0x2) | Exported Function | 0x44988770 | 0x00008770
`public: __thiscall NTFS_ATTRIBUTE_LIST::NTFS_ATTRIBUTE_LIST(void)` | 3 (0x3) | Exported Function | 0x4498d330 | 0x0000d330
`public: __thiscall NTFS_ATTRIBUTE_RECORD::NTFS_ATTRIBUTE_RECORD(void)` | 4 (0x4) | Exported Function | 0x4498e500 | 0x0000e500
`public: __thiscall NTFS_BAD_CLUSTER_FILE::NTFS_BAD_CLUSTER_FILE(void)` | 5 (0x5) | Exported Function | 0x44990a60 | 0x00010a60
`public: __thiscall NTFS_BITMAP_FILE::NTFS_BITMAP_FILE(void)` | 7 (0x7) | Exported Function | 0x44991610 | 0x00011610
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttributeByOrdinal(class NTFS_ATTRIBUTE *,unsigned char *,unsigned long,unsigned long)` | 107 (0x6b) | Exported Function | 0x4499c050 | 0x0001c050
`public: static unsigned char __stdcall NTFS_SA::IsDosName(struct _FILE_NAME const *)` | 100 (0x64) | Exported Function | 0x449d13b0 | 0x000513b0
`public: static unsigned long __stdcall NTFS_SA::QueryDefaultClustersPerIndexBuffer(class DP_DRIVE const *,unsigned long)` | 112 (0x70) | Exported Function | 0x449d1770 | 0x00051770
`public: unsigned char __thiscall NTFS_BOOT_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 71 (0x47) | Exported Function | 0x44991840 | 0x00011840
`public: unsigned char __thiscall NTFS_CLUSTER_RUN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,unsigned long)` | 72 (0x48) | Exported Function | 0x44991b70 | 0x00011b70
`public: unsigned char __thiscall NTFS_EXTENT_LIST::AddExtent(class BIG_INT,class BIG_INT,class BIG_INT)` | 43 (0x2b) | Exported Function | 0x449943a0 | 0x000143a0
`public: unsigned char __thiscall NTFS_EXTENT_LIST::Initialize(class BIG_INT,class BIG_INT)` | 73 (0x49) | Exported Function | 0x449940f0 | 0x000140f0
`public: unsigned char __thiscall NTFS_EXTENT_LIST::QueryExtent(unsigned long,class BIG_INT *,class BIG_INT *,class BIG_INT *)const ` | 115 (0x73) | Exported Function | 0x44994840 | 0x00014840
`public: unsigned char __thiscall NTFS_EXTENT_LIST::QueryLcnFromVcn(class BIG_INT,class BIG_INT *,class BIG_INT *)const ` | 121 (0x79) | Exported Function | 0x449948a0 | 0x000148a0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddFileNameAttribute(struct _FILE_NAME *)` | 44 (0x2c) | Exported Function | 0x4499b3c0 | 0x0001b3c0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptor(enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP *)` | 45 (0x2d) | Exported Function | 0x4499b4d0 | 0x0001b4d0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptorData(class NTFS_ATTRIBUTE *,void *,struct _SECURITY_ENTRY * *,unsigned long,enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP *,enum FIX_LEVEL)` | 46 (0x2e) | Exported Function | 0x4499b520 | 0x0001b520
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Create(struct _STANDARD_INFORMATION const *,unsigned short)` | 53 (0x35) | Exported Function | 0x44998870 | 0x00018870
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Flush(class NTFS_BITMAP *,class NTFS_INDEX_TREE *,unsigned char)` | 57 (0x39) | Exported Function | 0x4499d920 | 0x0001d920
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL)` | 74 (0x4a) | Exported Function | 0x44998590 | 0x00018590
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MASTER_FILE_TABLE *)` | 77 (0x4d) | Exported Function | 0x449983f0 | 0x000183f0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MFT_FILE *)` | 78 (0x4e) | Exported Function | 0x44998600 | 0x00018600
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,unsigned long,class NTFS_MASTER_FILE_TABLE *)` | 76 (0x4c) | Exported Function | 0x449984c0 | 0x000184c0
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class NTFS_FRS_STRUCTURE *,class NTFS_MASTER_FILE_TABLE *)` | 75 (0x4b) | Exported Function | 0x44998640 | 0x00018640
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::IsAttributePresent(unsigned long,class WSTRING const *,unsigned char)` | 99 (0x63) | Exported Function | 0x4499b7f0 | 0x0001b7f0
`public: unsigned char __thiscall NTFS_BITMAP_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 70 (0x46) | Exported Function | 0x44991650 | 0x00011650
`public: static unsigned char __stdcall NTFS_SA::IsNtfsName(struct _FILE_NAME const *)` | 102 (0x66) | Exported Function | 0x449d1340 | 0x00051340
`public: unsigned char __thiscall NTFS_BITMAP::WriteModified(class NTFS_ATTRIBUTE *,class NTFS_BITMAP *)` | 154 (0x9a) | Exported Function | 0x449b9e70 | 0x00039e70
`public: unsigned char __thiscall NTFS_BITMAP::IsFree(class BIG_INT,class BIG_INT)const ` | 101 (0x65) | Exported Function | 0x449ba2e0 | 0x0003a2e0
`public: static unsigned long __stdcall NTFS_SA::QuerySectorsInElementaryStructures(class DP_DRIVE *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned char)` | 125 (0x7d) | Exported Function | 0x44995180 | 0x00015180
`public: struct _ATTRIBUTE_LIST_ENTRY const * __thiscall NTFS_ATTRIBUTE_LIST::GetNextAttributeListEntry(struct _ATTRIBUTE_LIST_ENTRY const *)const ` | 60 (0x3c) | Exported Function | 0x4498dbd0 | 0x0000dbd0
`public: struct _INDEX_ENTRY const * __thiscall NTFS_INDEX_TREE::GetNext(unsigned long *,unsigned char *,unsigned char)` | 59 (0x3b) | Exported Function | 0x449b6370 | 0x00036370
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_EXTENT_LIST const *,class BIG_INT,class BIG_INT,unsigned long,class WSTRING const *,unsigned short)` | 64 (0x40) | Exported Function | 0x449890d0 | 0x000090d0
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,void const *,unsigned long,unsigned long,class WSTRING const *,unsigned short)` | 65 (0x41) | Exported Function | 0x44988ff0 | 0x00008ff0
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Prefetch(class BIG_INT,unsigned long)` | 104 (0x68) | Exported Function | 0x4498aac0 | 0x0000aac0
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Read(void *,class BIG_INT,unsigned long,unsigned long *)` | 128 (0x80) | Exported Function | 0x4498a700 | 0x0000a700
`public: unsigned char __thiscall NTFS_ATTRIBUTE::ReadWithAltExtents(void *,class BIG_INT,unsigned long,unsigned long *,class NTFS_EXTENT_LIST *)` | 138 (0x8a) | Exported Function | 0x4498a730 | 0x0000a730
`public: unsigned char __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *,unsigned char)` | 66 (0x42) | Exported Function | 0x449887b0 | 0x000087b0
`public: unsigned char __thiscall NTFS_ATTRIBUTE_LIST::QueryNextEntry(struct _ATTR_LIST_CURR_ENTRY *,unsigned long *,class BIG_INT *,struct _MFT_SEGMENT_REFERENCE *,unsigned short *,class WSTRING *)const ` | 123 (0x7b) | Exported Function | 0x4498db30 | 0x0000db30
`public: unsigned char __thiscall NTFS_ATTRIBUTE_LIST::ReadList(void)` | 136 (0x88) | Exported Function | 0x4498dd70 | 0x0000dd70
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::Initialize(class IO_DP_DRIVE *,void *)` | 67 (0x43) | Exported Function | 0x4498e610 | 0x0000e610
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::QueryExtentList(class NTFS_EXTENT_LIST *)const ` | 116 (0x74) | Exported Function | 0x44990680 | 0x00010680
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::QueryName(class WSTRING *)const ` | 122 (0x7a) | Exported Function | 0x44990540 | 0x00010540
`public: unsigned char __thiscall NTFS_BAD_CLUSTER_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 68 (0x44) | Exported Function | 0x44990ae0 | 0x00010ae0
`public: unsigned char __thiscall NTFS_BITMAP::Initialize(class BIG_INT,unsigned char,class LOG_IO_DP_DRIVE *,unsigned long,unsigned char)` | 69 (0x45) | Exported Function | 0x449b9ce0 | 0x00039ce0
`public: unsigned char __thiscall NTFS_BITMAP::IsAllocated(class BIG_INT,class BIG_INT)const ` | 98 (0x62) | Exported Function | 0x449ba370 | 0x0003a370
`public: unsigned char __thiscall NTFS_BITMAP::Write(class NTFS_ATTRIBUTE *,class NTFS_BITMAP *)` | 151 (0x97) | Exported Function | 0x449b9de0 | 0x00039de0
`SetWriteViewCacheVolumeName` | 148 (0x94) | Exported Function | 0x449921e0 | 0x000121e0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNTFS.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/e3e5bad8f802a2811a912043e878bae0f29bddaed6d27dec340f0d147534fabe/detection/





MIT License. Copyright (c) 2020 Strontic.


