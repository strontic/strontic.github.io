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

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __thiscall NTFS_MFT_FILE::Flush(void)` | 58 | Exported Function
`public: unsigned char __thiscall NTFS_MASTER_FILE_TABLE::Extend(unsigned long)` | 56 | Exported Function
`public: unsigned char __thiscall NTFS_MFT_FILE::Initialize(enum FIX_LEVEL,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,class NTFS_ATTRIBUTE *)` | 86 | Exported Function
`public: unsigned char __thiscall NTFS_MFT_INFO::Initialize(void)` | 88 | Exported Function
`public: unsigned char __thiscall NTFS_MFT_INFO::Initialize(class BIG_INT,class NTFS_UPCASE_TABLE *,unsigned char,unsigned char,unsigned __int64)` | 87 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::Save(class NTFS_FILE_RECORD_SEGMENT *)` | 144 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::ResetIterator(unsigned char)` | 140 | Exported Function
`public: unsigned char __thiscall NTFS_LOG_FILE::CreateDataAttribute(class BIG_INT,unsigned long,class NTFS_BITMAP *)` | 54 | Exported Function
`public: unsigned char __thiscall NTFS_MASTER_FILE_TABLE::AllocateFileRecordSegment(class BIG_INT *,unsigned char)` | 47 | Exported Function
`public: unsigned char __thiscall NTFS_LOG_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 85 | Exported Function
`public: unsigned char __thiscall NTFS_SA::TakeCensus(class NTFS_MASTER_FILE_TABLE *,unsigned long,struct NTFS_CENSUS_INFO *)` | 149 | Exported Function
`public: unsigned char __thiscall NTFS_SA::SetVolumeFlag(unsigned short,unsigned char *)` | 147 | Exported Function
`public: unsigned char __thiscall NTFS_SA::WriteRemainingBootCode(void)` | 155 | Exported Function
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(class NTFS_ATTRIBUTE *,unsigned __int64 *)` | 93 | Exported Function
`public: unsigned char __thiscall NTFS_UPCASE_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 91 | Exported Function
`public: unsigned char __thiscall NTFS_SA::CreateElementaryStructures(class NTFS_BITMAP *,unsigned long,unsigned long,unsigned long,unsigned long,class NUMBER_SET const *,unsigned char,unsigned char,unsigned char,unsigned char,unsigned char,unsigned long,class MESSAGE *,struct BIOS_PARAMETER_BLOCK *,class WSTRING const *,unsigned char)` | 55 | Exported Function
`public: unsigned char __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 89 | Exported Function
`public: unsigned char __thiscall NTFS_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *,class BIG_INT,class BIG_INT,unsigned long,unsigned char)` | 90 | Exported Function
`public: unsigned char __thiscall NTFS_SA::Read(class MESSAGE *)` | 132 | Exported Function
`public: unsigned char __thiscall NTFS_SA::QueryFrsFromPath(enum FIX_LEVEL,class WSTRING const *,class NTFS_MASTER_FILE_TABLE *,class NTFS_BITMAP *,class NTFS_FILE_RECORD_SEGMENT *,unsigned char *,unsigned char *)` | 120 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::ResetIterator(struct _INDEX_ENTRY const *,unsigned char)` | 141 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Prefetch(class BIG_INT,class BIG_INT)` | 105 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(struct _FILE_RECORD_SEGMENT_HEADER *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 79 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::QueryAttributeList(class NTFS_ATTRIBUTE_LIST *)` | 108 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadAgain(class BIG_INT)` | 134 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Read(class BIG_INT)` | 129 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryFileSizes(class BIG_INT *,class BIG_INT *,unsigned char *)` | 118 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryDuplicatedInformation(struct _DUPLICATED_INFORMATION *)` | 113 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *,unsigned long)` | 80 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 82 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Initialize(class MEM *,class NTFS_ATTRIBUTE *,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE *)` | 81 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::Initialize(unsigned long,class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,unsigned long,unsigned long,unsigned long,class WSTRING const *)` | 83 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_BITMAP *,class NTFS_UPCASE_TABLE *,unsigned long,class NTFS_FILE_RECORD_SEGMENT *,class WSTRING const *)` | 84 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::InsertEntry(unsigned long,void *,struct _MFT_SEGMENT_REFERENCE,unsigned char)` | 96 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::QueryFileReference(unsigned long,void *,unsigned long,struct _MFT_SEGMENT_REFERENCE *,unsigned char *)` | 117 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::QueryEntry(unsigned long,void *,unsigned long,struct _INDEX_ENTRY * *,class NTFS_INDEX_BUFFER * *,unsigned char *)` | 114 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadNext(class BIG_INT)` | 137 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::ReadAt(class BIG_INT)` | 135 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::SafeQueryAttribute(unsigned long,class NTFS_ATTRIBUTE *,class NTFS_ATTRIBUTE *,class WSTRING *)` | 143 | Exported Function
`public: unsigned char __thiscall NTFS_INDEX_TREE::CopyIterator(class NTFS_INDEX_TREE *)` | 52 | Exported Function
`public: unsigned char __thiscall NTFS_FRS_STRUCTURE::Write(void)` | 153 | Exported Function
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(unsigned short *,unsigned long)` | 92 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::InsertIntoFile(class NTFS_FILE_RECORD_SEGMENT *,class NTFS_BITMAP *)` | 97 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::GrowSparse(class BIG_INT,class NTFS_BITMAP *,unsigned char)` | 63 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::MakeNonresident(class NTFS_BITMAP *)` | 103 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::SetSparse(class BIG_INT,class NTFS_BITMAP *,unsigned char)` | 146 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::Resize(class BIG_INT,class NTFS_BITMAP *)` | 142 | Exported Function
`public: virtual __thiscall NTFS_SA::~NTFS_SA(void)` | 39 | Exported Function
`public: virtual __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::~NTFS_REFLECTED_MASTER_FILE_TABLE(void)` | 38 | Exported Function
`public: virtual __thiscall NTFS_UPCASE_FILE::~NTFS_UPCASE_FILE(void)` | 40 | Exported Function
`public: virtual __thiscall NTFS_VOLUME_FILE::~NTFS_VOLUME_FILE(void)` | 42 | Exported Function
`public: virtual __thiscall NTFS_UPCASE_TABLE::~NTFS_UPCASE_TABLE(void)` | 41 | Exported Function
`public: void __thiscall NTFS_CLUSTER_RUN::Relocate(class BIG_INT)` | 139 | Exported Function
`public: void * __thiscall NTFS_FRS_STRUCTURE::GetNextAttributeRecord(void const *,class MESSAGE *,unsigned char *)` | 61 | Exported Function
`Recover` | 167 | Exported Function
`SetWriteViewCacheVolumeName` | 148 | Exported Function
`SetOriginalVolumeName` | 145 | Exported Function
`public: virtual unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Write(void)` | 152 | Exported Function
`public: virtual unsigned char __thiscall NTFS_ATTRIBUTE::Write(void const *,class BIG_INT,unsigned long,unsigned long *,class NTFS_BITMAP *)` | 150 | Exported Function
`public: virtual unsigned char __thiscall NTFS_FRS_STRUCTURE::Read(void)` | 130 | Exported Function
`public: virtual unsigned char __thiscall NTFS_SA::Read(void)` | 133 | Exported Function
`public: virtual unsigned char __thiscall NTFS_MFT_FILE::Read(void)` | 131 | Exported Function
`public: virtual __thiscall NTFS_MFT_INFO::~NTFS_MFT_INFO(void)` | 37 | Exported Function
`public: virtual __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::~NTFS_ATTRIBUTE_DEFINITION_TABLE(void)` | 23 | Exported Function
`public: virtual __thiscall NTFS_ATTRIBUTE::~NTFS_ATTRIBUTE(void)` | 22 | Exported Function
`public: virtual __thiscall NTFS_ATTRIBUTE_LIST::~NTFS_ATTRIBUTE_LIST(void)` | 24 | Exported Function
`public: virtual __thiscall NTFS_BAD_CLUSTER_FILE::~NTFS_BAD_CLUSTER_FILE(void)` | 26 | Exported Function
`public: virtual __thiscall NTFS_ATTRIBUTE_RECORD::~NTFS_ATTRIBUTE_RECORD(void)` | 25 | Exported Function
`public: unsigned char __thiscall NTFS_VOLUME_FILE::Initialize(class LOG_IO_DP_DRIVE *,class NTFS_MASTER_FILE_TABLE *,class NTFS_FILE_RECORD_SEGMENT *,class NTFS_INDEX_TREE *,struct _VOLUME_INFORMATION *,class WSTRING *,enum FIX_LEVEL)` | 95 | Exported Function
`public: unsigned char __thiscall NTFS_UPCASE_TABLE::Initialize(void)` | 94 | Exported Function
`public: unsigned long __thiscall NTFS_EXTENT_LIST::QueryNumberOfExtents(void)const ` | 124 | Exported Function
`public: unsigned short __thiscall NTFS_SA::QueryVolumeFlagsAndLabel(unsigned char *,unsigned char *,unsigned char *,class WSTRING *)` | 127 | Exported Function
`public: unsigned long __thiscall NTFS_SA::QueryClusterFactor(void)const ` | 110 | Exported Function
`public: virtual __thiscall NTFS_FRS_STRUCTURE::~NTFS_FRS_STRUCTURE(void)` | 33 | Exported Function
`public: virtual __thiscall NTFS_FILE_RECORD_SEGMENT::~NTFS_FILE_RECORD_SEGMENT(void)` | 32 | Exported Function
`public: virtual __thiscall NTFS_INDEX_TREE::~NTFS_INDEX_TREE(void)` | 34 | Exported Function
`public: virtual __thiscall NTFS_MFT_FILE::~NTFS_MFT_FILE(void)` | 36 | Exported Function
`public: virtual __thiscall NTFS_LOG_FILE::~NTFS_LOG_FILE(void)` | 35 | Exported Function
`public: virtual __thiscall NTFS_BITMAP_FILE::~NTFS_BITMAP_FILE(void)` | 28 | Exported Function
`public: virtual __thiscall NTFS_BITMAP::~NTFS_BITMAP(void)` | 27 | Exported Function
`public: virtual __thiscall NTFS_BOOT_FILE::~NTFS_BOOT_FILE(void)` | 29 | Exported Function
`public: virtual __thiscall NTFS_EXTENT_LIST::~NTFS_EXTENT_LIST(void)` | 31 | Exported Function
`public: virtual __thiscall NTFS_CLUSTER_RUN::~NTFS_CLUSTER_RUN(void)` | 30 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttributeListAttribute(class NTFS_ATTRIBUTE *,unsigned char *)` | 109 | Exported Function
`public: __thiscall NTFS_MFT_FILE::NTFS_MFT_FILE(void)` | 15 | Exported Function
`public: __thiscall NTFS_LOG_FILE::NTFS_LOG_FILE(void)` | 14 | Exported Function
`public: __thiscall NTFS_MFT_INFO::NTFS_MFT_INFO(void)` | 16 | Exported Function
`public: __thiscall NTFS_SA::NTFS_SA(void)` | 18 | Exported Function
`public: __thiscall NTFS_REFLECTED_MASTER_FILE_TABLE::NTFS_REFLECTED_MASTER_FILE_TABLE(void)` | 17 | Exported Function
`public: __thiscall NTFS_EXTENT_LIST::NTFS_EXTENT_LIST(void)` | 10 | Exported Function
`public: __thiscall NTFS_CLUSTER_RUN::NTFS_CLUSTER_RUN(void)` | 9 | Exported Function
`public: __thiscall NTFS_FILE_RECORD_SEGMENT::NTFS_FILE_RECORD_SEGMENT(void)` | 11 | Exported Function
`public: __thiscall NTFS_INDEX_TREE::NTFS_INDEX_TREE(void)` | 13 | Exported Function
`public: __thiscall NTFS_FRS_STRUCTURE::NTFS_FRS_STRUCTURE(void)` | 12 | Exported Function
`public: static unsigned char __stdcall NTFS_MFT_INFO::CompareFileName(void *,unsigned long,struct _FILE_NAME *,unsigned short *)` | 49 | Exported Function
`public: static unsigned char __stdcall NTFS_MFT_INFO::CompareDupInfo(void *,struct _FILE_NAME *)` | 48 | Exported Function
`public: static unsigned char __stdcall NTFS_MFT_INFO::QueryFlags(void *,unsigned short)` | 119 | Exported Function
`public: static unsigned char __stdcall NTFS_SA::IsDosName(struct _FILE_NAME const *)` | 100 | Exported Function
`public: static unsigned char __stdcall NTFS_SA::GetRootFrsIndex(enum FIX_LEVEL,class NTFS_MFT_FILE *,class NTFS_FILE_RECORD_SEGMENT *,class NTFS_INDEX_TREE *)` | 62 | Exported Function
`public: __thiscall NTFS_UPCASE_TABLE::NTFS_UPCASE_TABLE(void)` | 20 | Exported Function
`public: __thiscall NTFS_UPCASE_FILE::NTFS_UPCASE_FILE(void)` | 19 | Exported Function
`public: __thiscall NTFS_VOLUME_FILE::NTFS_VOLUME_FILE(void)` | 21 | Exported Function
`public: static struct _MFT_SEGMENT_REFERENCE __stdcall NTFS_MFT_INFO::QuerySegmentReference(void *)` | 126 | Exported Function
`public: class BIG_INT __thiscall NTFS_ATTRIBUTE::QueryClustersAllocated(void)const ` | 111 | Exported Function
`public: __thiscall NTFS_BOOT_FILE::NTFS_BOOT_FILE(void)` | 8 | Exported Function
`FormatCorruptionRecordA` | 162 | Exported Function
`Format` | 161 | Exported Function
`FormatCorruptionRecordW` | 163 | Exported Function
`GetFilesystemInformation` | 165 | Exported Function
`FormatEx` | 164 | Exported Function
`ChkdskEx` | 157 | Exported Function
`Chkdsk` | 156 | Exported Function
`CreateFormatCorruptionRecordContext` | 158 | Exported Function
`Extend` | 160 | Exported Function
`DeleteFormatCorruptionRecordContext` | 159 | Exported Function
`public: __thiscall NTFS_ATTRIBUTE_RECORD::NTFS_ATTRIBUTE_RECORD(void)` | 4 | Exported Function
`public: __thiscall NTFS_ATTRIBUTE_LIST::NTFS_ATTRIBUTE_LIST(void)` | 3 | Exported Function
`public: __thiscall NTFS_BAD_CLUSTER_FILE::NTFS_BAD_CLUSTER_FILE(void)` | 5 | Exported Function
`public: __thiscall NTFS_BITMAP_FILE::NTFS_BITMAP_FILE(void)` | 7 | Exported Function
`public: __thiscall NTFS_BITMAP::NTFS_BITMAP(void)` | 6 | Exported Function
`private: static void __stdcall NTFS_MFT_INFO::ComputeDupInfoSignature(struct _DUPLICATED_INFORMATION *,unsigned char * const)` | 50 | Exported Function
`NtfsUpcaseCompare` | 166 | Exported Function
`private: static void __stdcall NTFS_MFT_INFO::ComputeFileNameSignature(unsigned long,struct _FILE_NAME *,unsigned char * const)` | 51 | Exported Function
`public: __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::NTFS_ATTRIBUTE_DEFINITION_TABLE(void)` | 2 | Exported Function
`public: __thiscall NTFS_ATTRIBUTE::NTFS_ATTRIBUTE(void)` | 1 | Exported Function
`public: static unsigned char __stdcall NTFS_SA::IsNtfsName(struct _FILE_NAME const *)` | 102 | Exported Function
`public: unsigned char __thiscall NTFS_EXTENT_LIST::QueryLcnFromVcn(class BIG_INT,class BIG_INT *,class BIG_INT *)const ` | 121 | Exported Function
`public: unsigned char __thiscall NTFS_EXTENT_LIST::QueryExtent(unsigned long,class BIG_INT *,class BIG_INT *,class BIG_INT *)const ` | 115 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddFileNameAttribute(struct _FILE_NAME *)` | 44 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptorData(class NTFS_ATTRIBUTE *,void *,struct _SECURITY_ENTRY * *,unsigned long,enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP *,enum FIX_LEVEL)` | 46 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptor(enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP *)` | 45 | Exported Function
`public: unsigned char __thiscall NTFS_BOOT_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 71 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 70 | Exported Function
`public: unsigned char __thiscall NTFS_CLUSTER_RUN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class BIG_INT,unsigned long,unsigned long)` | 72 | Exported Function
`public: unsigned char __thiscall NTFS_EXTENT_LIST::Initialize(class BIG_INT,class BIG_INT)` | 73 | Exported Function
`public: unsigned char __thiscall NTFS_EXTENT_LIST::AddExtent(class BIG_INT,class BIG_INT,class BIG_INT)` | 43 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class NTFS_FRS_STRUCTURE *,class NTFS_MASTER_FILE_TABLE *)` | 75 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,unsigned long,class NTFS_MASTER_FILE_TABLE *)` | 76 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::IsAttributePresent(unsigned long,class WSTRING const *,unsigned char)` | 99 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttributeByOrdinal(class NTFS_ATTRIBUTE *,unsigned char *,unsigned long,unsigned long)` | 107 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::QueryAttribute(class NTFS_ATTRIBUTE *,unsigned char *,unsigned long,class WSTRING const *)` | 106 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Flush(class NTFS_BITMAP *,class NTFS_INDEX_TREE *,unsigned char)` | 57 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Create(struct _STANDARD_INFORMATION const *,unsigned short)` | 53 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL)` | 74 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MFT_FILE *)` | 78 | Exported Function
`public: unsigned char __thiscall NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MASTER_FILE_TABLE *)` | 77 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP::WriteModified(class NTFS_ATTRIBUTE *,class NTFS_BITMAP *)` | 154 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Prefetch(class BIG_INT,unsigned long)` | 104 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,void const *,unsigned long,unsigned long,class WSTRING const *,unsigned short)` | 65 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Read(void *,class BIG_INT,unsigned long,unsigned long *)` | 128 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_DEFINITION_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *,unsigned char)` | 66 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE::ReadWithAltExtents(void *,class BIG_INT,unsigned long,unsigned long *,class NTFS_EXTENT_LIST *)` | 138 | Exported Function
`public: static unsigned long __stdcall NTFS_SA::QuerySectorsInElementaryStructures(class DP_DRIVE *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned char)` | 125 | Exported Function
`public: static unsigned long __stdcall NTFS_SA::QueryDefaultClustersPerIndexBuffer(class DP_DRIVE const *,unsigned long)` | 112 | Exported Function
`public: struct _ATTRIBUTE_LIST_ENTRY const * __thiscall NTFS_ATTRIBUTE_LIST::GetNextAttributeListEntry(struct _ATTRIBUTE_LIST_ENTRY const *)const ` | 60 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE *,unsigned long,class NTFS_EXTENT_LIST const *,class BIG_INT,class BIG_INT,unsigned long,class WSTRING const *,unsigned short)` | 64 | Exported Function
`public: struct _INDEX_ENTRY const * __thiscall NTFS_INDEX_TREE::GetNext(unsigned long *,unsigned char *,unsigned char)` | 59 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP::Initialize(class BIG_INT,unsigned char,class LOG_IO_DP_DRIVE *,unsigned long,unsigned char)` | 69 | Exported Function
`public: unsigned char __thiscall NTFS_BAD_CLUSTER_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE *)` | 68 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP::IsAllocated(class BIG_INT,class BIG_INT)const ` | 98 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP::Write(class NTFS_ATTRIBUTE *,class NTFS_BITMAP *)` | 151 | Exported Function
`public: unsigned char __thiscall NTFS_BITMAP::IsFree(class BIG_INT,class BIG_INT)const ` | 101 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_LIST::ReadList(void)` | 136 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_LIST::QueryNextEntry(struct _ATTR_LIST_CURR_ENTRY *,unsigned long *,class BIG_INT *,struct _MFT_SEGMENT_REFERENCE *,unsigned short *,class WSTRING *)const ` | 123 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::Initialize(class IO_DP_DRIVE *,void *)` | 67 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::QueryName(class WSTRING *)const ` | 122 | Exported Function
`public: unsigned char __thiscall NTFS_ATTRIBUTE_RECORD::QueryExtentList(class NTFS_EXTENT_LIST *)const ` | 116 | Exported Function


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


