---
title: untfs.dll | NTFS Utility DLL
excerpt: What is untfs.dll?
---

# untfs.dll 

* File Path: `C:\Windows\system32\untfs.dll`
* Description: NTFS Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `1ADD711580A8145B1C229FA49D45E5D8`
SHA1 | `D697831FA5BDFE17F70FB31D811825817C2D28D5`
SHA256 | `0A4CE1B7ED9E7DF96FAF45F83ED1C30D2DA7B33E7D7A02FAEA1D5B9481E5EAC8`
SHA384 | `AAB9B92E4190A381B1230F13C5EF7CF52F7907FF5C3F753DDE0FC2C78CD0BA68F7FDAFAB0EF91CF944113F0542AF1C53`
SHA512 | `1E10DC65E589F1D39A10D4CA635CEE631B880C6B162CA41C7010F129B971C88F993312C9322C7610D1A47B730AA3E9F7A5124365CE06D670CD5AF12879587124`
SSDEEP | `6144:ChALFMA92noDEjgnLFMi0FqInT+ro0Hf1Z/hLNgtagERtbQck58su03n0gudN0TW:zKnOYgL6FxTQo0Umfy58qktM+bfBLG`
IMP | `71D14EA646846084074E24324292EF7D`
PESHA1 | `ECBF9029185ABE211165C5F7AF71061AF6EBBED1`
PE256 | `038381CCA63EB9893F0AFA180BD947D50040D758E75604AFF831C6EBCF5E7D5D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __cdecl NTFS_MFT_FILE::Flush(void) __ptr64` | 58 | Exported Function
`public: unsigned char __cdecl NTFS_MASTER_FILE_TABLE::Extend(unsigned long) __ptr64` | 56 | Exported Function
`public: unsigned char __cdecl NTFS_MFT_FILE::Initialize(enum FIX_LEVEL,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,class NTFS_ATTRIBUTE * __ptr64) __ptr64` | 86 | Exported Function
`public: unsigned char __cdecl NTFS_MFT_INFO::Initialize(void) __ptr64` | 88 | Exported Function
`public: unsigned char __cdecl NTFS_MFT_INFO::Initialize(class BIG_INT,class NTFS_UPCASE_TABLE * __ptr64,unsigned char,unsigned char,unsigned __int64) __ptr64` | 87 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::Save(class NTFS_FILE_RECORD_SEGMENT * __ptr64) __ptr64` | 144 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::ResetIterator(unsigned char) __ptr64` | 140 | Exported Function
`public: unsigned char __cdecl NTFS_LOG_FILE::CreateDataAttribute(class BIG_INT,unsigned long,class NTFS_BITMAP * __ptr64) __ptr64` | 54 | Exported Function
`public: unsigned char __cdecl NTFS_MASTER_FILE_TABLE::AllocateFileRecordSegment(class BIG_INT * __ptr64,unsigned char) __ptr64` | 47 | Exported Function
`public: unsigned char __cdecl NTFS_LOG_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 85 | Exported Function
`public: unsigned char __cdecl NTFS_SA::TakeCensus(class NTFS_MASTER_FILE_TABLE * __ptr64,unsigned long,struct NTFS_CENSUS_INFO * __ptr64) __ptr64` | 149 | Exported Function
`public: unsigned char __cdecl NTFS_SA::SetVolumeFlag(unsigned short,unsigned char * __ptr64) __ptr64` | 147 | Exported Function
`public: unsigned char __cdecl NTFS_SA::WriteRemainingBootCode(void) __ptr64` | 155 | Exported Function
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(class NTFS_ATTRIBUTE * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 93 | Exported Function
`public: unsigned char __cdecl NTFS_UPCASE_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 91 | Exported Function
`public: unsigned char __cdecl NTFS_SA::CreateElementaryStructures(class NTFS_BITMAP * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,class NUMBER_SET const * __ptr64,unsigned char,unsigned char,unsigned char,unsigned char,unsigned char,unsigned long,class MESSAGE * __ptr64,struct BIOS_PARAMETER_BLOCK * __ptr64,class WSTRING const * __ptr64,unsigned char) __ptr64` | 55 | Exported Function
`public: unsigned char __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 89 | Exported Function
`public: unsigned char __cdecl NTFS_SA::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64,class BIG_INT,class BIG_INT,unsigned long,unsigned char) __ptr64` | 90 | Exported Function
`public: unsigned char __cdecl NTFS_SA::Read(class MESSAGE * __ptr64) __ptr64` | 132 | Exported Function
`public: unsigned char __cdecl NTFS_SA::QueryFrsFromPath(enum FIX_LEVEL,class WSTRING const * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64,class NTFS_BITMAP * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64) __ptr64` | 120 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::ResetIterator(struct _INDEX_ENTRY const * __ptr64,unsigned char) __ptr64` | 141 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Prefetch(class BIG_INT,class BIG_INT) __ptr64` | 105 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(struct _FILE_RECORD_SEGMENT_HEADER * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 79 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::QueryAttributeList(class NTFS_ATTRIBUTE_LIST * __ptr64) __ptr64` | 108 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadAgain(class BIG_INT) __ptr64` | 134 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Read(class BIG_INT) __ptr64` | 129 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryFileSizes(class BIG_INT * __ptr64,class BIG_INT * __ptr64,unsigned char * __ptr64) __ptr64` | 118 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryDuplicatedInformation(struct _DUPLICATED_INFORMATION * __ptr64) __ptr64` | 113 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64,unsigned long) __ptr64` | 80 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 82 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 81 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::Initialize(unsigned long,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,unsigned long,unsigned long,unsigned long,class WSTRING const * __ptr64) __ptr64` | 83 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,unsigned long,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class WSTRING const * __ptr64) __ptr64` | 84 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::InsertEntry(unsigned long,void * __ptr64,struct _MFT_SEGMENT_REFERENCE,unsigned char) __ptr64` | 96 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::QueryFileReference(unsigned long,void * __ptr64,unsigned long,struct _MFT_SEGMENT_REFERENCE * __ptr64,unsigned char * __ptr64) __ptr64` | 117 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::QueryEntry(unsigned long,void * __ptr64,unsigned long,struct _INDEX_ENTRY * __ptr64 * __ptr64,class NTFS_INDEX_BUFFER * __ptr64 * __ptr64,unsigned char * __ptr64) __ptr64` | 114 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadNext(class BIG_INT) __ptr64` | 137 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadAt(class BIG_INT) __ptr64` | 135 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::SafeQueryAttribute(unsigned long,class NTFS_ATTRIBUTE * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class WSTRING * __ptr64) __ptr64` | 143 | Exported Function
`public: unsigned char __cdecl NTFS_INDEX_TREE::CopyIterator(class NTFS_INDEX_TREE * __ptr64) __ptr64` | 52 | Exported Function
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Write(void) __ptr64` | 153 | Exported Function
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(unsigned short * __ptr64,unsigned long) __ptr64` | 92 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::InsertIntoFile(class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 97 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::GrowSparse(class BIG_INT,class NTFS_BITMAP * __ptr64,unsigned char) __ptr64` | 63 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::MakeNonresident(class NTFS_BITMAP * __ptr64) __ptr64` | 103 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::SetSparse(class BIG_INT,class NTFS_BITMAP * __ptr64,unsigned char) __ptr64` | 146 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::Resize(class BIG_INT,class NTFS_BITMAP * __ptr64) __ptr64` | 142 | Exported Function
`public: virtual __cdecl NTFS_SA::~NTFS_SA(void) __ptr64` | 39 | Exported Function
`public: virtual __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::~NTFS_REFLECTED_MASTER_FILE_TABLE(void) __ptr64` | 38 | Exported Function
`public: virtual __cdecl NTFS_UPCASE_FILE::~NTFS_UPCASE_FILE(void) __ptr64` | 40 | Exported Function
`public: virtual __cdecl NTFS_VOLUME_FILE::~NTFS_VOLUME_FILE(void) __ptr64` | 42 | Exported Function
`public: virtual __cdecl NTFS_UPCASE_TABLE::~NTFS_UPCASE_TABLE(void) __ptr64` | 41 | Exported Function
`public: void __cdecl NTFS_CLUSTER_RUN::Relocate(class BIG_INT) __ptr64` | 139 | Exported Function
`public: void * __ptr64 __cdecl NTFS_FRS_STRUCTURE::GetNextAttributeRecord(void const * __ptr64,class MESSAGE * __ptr64,unsigned char * __ptr64) __ptr64` | 61 | Exported Function
`Recover` | 167 | Exported Function
`SetWriteViewCacheVolumeName` | 148 | Exported Function
`SetOriginalVolumeName` | 145 | Exported Function
`public: virtual unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Write(void) __ptr64` | 152 | Exported Function
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::Write(void const * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 150 | Exported Function
`public: virtual unsigned char __cdecl NTFS_FRS_STRUCTURE::Read(void) __ptr64` | 130 | Exported Function
`public: virtual unsigned char __cdecl NTFS_SA::Read(void) __ptr64` | 133 | Exported Function
`public: virtual unsigned char __cdecl NTFS_MFT_FILE::Read(void) __ptr64` | 131 | Exported Function
`public: virtual __cdecl NTFS_MFT_INFO::~NTFS_MFT_INFO(void) __ptr64` | 37 | Exported Function
`public: virtual __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::~NTFS_ATTRIBUTE_DEFINITION_TABLE(void) __ptr64` | 23 | Exported Function
`public: virtual __cdecl NTFS_ATTRIBUTE::~NTFS_ATTRIBUTE(void) __ptr64` | 22 | Exported Function
`public: virtual __cdecl NTFS_ATTRIBUTE_LIST::~NTFS_ATTRIBUTE_LIST(void) __ptr64` | 24 | Exported Function
`public: virtual __cdecl NTFS_BAD_CLUSTER_FILE::~NTFS_BAD_CLUSTER_FILE(void) __ptr64` | 26 | Exported Function
`public: virtual __cdecl NTFS_ATTRIBUTE_RECORD::~NTFS_ATTRIBUTE_RECORD(void) __ptr64` | 25 | Exported Function
`public: unsigned char __cdecl NTFS_VOLUME_FILE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_INDEX_TREE * __ptr64,struct _VOLUME_INFORMATION * __ptr64,class WSTRING * __ptr64,enum FIX_LEVEL) __ptr64` | 95 | Exported Function
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(void) __ptr64` | 94 | Exported Function
`public: unsigned long __cdecl NTFS_EXTENT_LIST::QueryNumberOfExtents(void)const __ptr64` | 124 | Exported Function
`public: unsigned short __cdecl NTFS_SA::QueryVolumeFlagsAndLabel(unsigned char * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64,class WSTRING * __ptr64) __ptr64` | 127 | Exported Function
`public: unsigned long __cdecl NTFS_SA::QueryClusterFactor(void)const __ptr64` | 110 | Exported Function
`public: virtual __cdecl NTFS_FRS_STRUCTURE::~NTFS_FRS_STRUCTURE(void) __ptr64` | 33 | Exported Function
`public: virtual __cdecl NTFS_FILE_RECORD_SEGMENT::~NTFS_FILE_RECORD_SEGMENT(void) __ptr64` | 32 | Exported Function
`public: virtual __cdecl NTFS_INDEX_TREE::~NTFS_INDEX_TREE(void) __ptr64` | 34 | Exported Function
`public: virtual __cdecl NTFS_MFT_FILE::~NTFS_MFT_FILE(void) __ptr64` | 36 | Exported Function
`public: virtual __cdecl NTFS_LOG_FILE::~NTFS_LOG_FILE(void) __ptr64` | 35 | Exported Function
`public: virtual __cdecl NTFS_BITMAP_FILE::~NTFS_BITMAP_FILE(void) __ptr64` | 28 | Exported Function
`public: virtual __cdecl NTFS_BITMAP::~NTFS_BITMAP(void) __ptr64` | 27 | Exported Function
`public: virtual __cdecl NTFS_BOOT_FILE::~NTFS_BOOT_FILE(void) __ptr64` | 29 | Exported Function
`public: virtual __cdecl NTFS_EXTENT_LIST::~NTFS_EXTENT_LIST(void) __ptr64` | 31 | Exported Function
`public: virtual __cdecl NTFS_CLUSTER_RUN::~NTFS_CLUSTER_RUN(void) __ptr64` | 30 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttributeListAttribute(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64) __ptr64` | 109 | Exported Function
`public: __cdecl NTFS_MFT_FILE::NTFS_MFT_FILE(void) __ptr64` | 15 | Exported Function
`public: __cdecl NTFS_LOG_FILE::NTFS_LOG_FILE(void) __ptr64` | 14 | Exported Function
`public: __cdecl NTFS_MFT_INFO::NTFS_MFT_INFO(void) __ptr64` | 16 | Exported Function
`public: __cdecl NTFS_SA::NTFS_SA(void) __ptr64` | 18 | Exported Function
`public: __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::NTFS_REFLECTED_MASTER_FILE_TABLE(void) __ptr64` | 17 | Exported Function
`public: __cdecl NTFS_EXTENT_LIST::NTFS_EXTENT_LIST(void) __ptr64` | 10 | Exported Function
`public: __cdecl NTFS_CLUSTER_RUN::NTFS_CLUSTER_RUN(void) __ptr64` | 9 | Exported Function
`public: __cdecl NTFS_FILE_RECORD_SEGMENT::NTFS_FILE_RECORD_SEGMENT(void) __ptr64` | 11 | Exported Function
`public: __cdecl NTFS_INDEX_TREE::NTFS_INDEX_TREE(void) __ptr64` | 13 | Exported Function
`public: __cdecl NTFS_FRS_STRUCTURE::NTFS_FRS_STRUCTURE(void) __ptr64` | 12 | Exported Function
`public: static unsigned char __cdecl NTFS_MFT_INFO::CompareFileName(void * __ptr64,unsigned long,struct _FILE_NAME * __ptr64,unsigned short * __ptr64)` | 49 | Exported Function
`public: static unsigned char __cdecl NTFS_MFT_INFO::CompareDupInfo(void * __ptr64,struct _FILE_NAME * __ptr64)` | 48 | Exported Function
`public: static unsigned char __cdecl NTFS_MFT_INFO::QueryFlags(void * __ptr64,unsigned short)` | 119 | Exported Function
`public: static unsigned char __cdecl NTFS_SA::IsDosName(struct _FILE_NAME const * __ptr64)` | 100 | Exported Function
`public: static unsigned char __cdecl NTFS_SA::GetRootFrsIndex(enum FIX_LEVEL,class NTFS_MFT_FILE * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_INDEX_TREE * __ptr64)` | 62 | Exported Function
`public: __cdecl NTFS_UPCASE_TABLE::NTFS_UPCASE_TABLE(void) __ptr64` | 20 | Exported Function
`public: __cdecl NTFS_UPCASE_FILE::NTFS_UPCASE_FILE(void) __ptr64` | 19 | Exported Function
`public: __cdecl NTFS_VOLUME_FILE::NTFS_VOLUME_FILE(void) __ptr64` | 21 | Exported Function
`public: static struct _MFT_SEGMENT_REFERENCE __cdecl NTFS_MFT_INFO::QuerySegmentReference(void * __ptr64)` | 126 | Exported Function
`public: class BIG_INT __cdecl NTFS_ATTRIBUTE::QueryClustersAllocated(void)const __ptr64` | 111 | Exported Function
`public: __cdecl NTFS_BOOT_FILE::NTFS_BOOT_FILE(void) __ptr64` | 8 | Exported Function
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
`public: __cdecl NTFS_ATTRIBUTE_RECORD::NTFS_ATTRIBUTE_RECORD(void) __ptr64` | 4 | Exported Function
`public: __cdecl NTFS_ATTRIBUTE_LIST::NTFS_ATTRIBUTE_LIST(void) __ptr64` | 3 | Exported Function
`public: __cdecl NTFS_BAD_CLUSTER_FILE::NTFS_BAD_CLUSTER_FILE(void) __ptr64` | 5 | Exported Function
`public: __cdecl NTFS_BITMAP_FILE::NTFS_BITMAP_FILE(void) __ptr64` | 7 | Exported Function
`public: __cdecl NTFS_BITMAP::NTFS_BITMAP(void) __ptr64` | 6 | Exported Function
`private: static void __cdecl NTFS_MFT_INFO::ComputeDupInfoSignature(struct _DUPLICATED_INFORMATION * __ptr64,unsigned char * __ptr64 const)` | 50 | Exported Function
`NtfsUpcaseCompare` | 166 | Exported Function
`private: static void __cdecl NTFS_MFT_INFO::ComputeFileNameSignature(unsigned long,struct _FILE_NAME * __ptr64,unsigned char * __ptr64 const)` | 51 | Exported Function
`public: __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::NTFS_ATTRIBUTE_DEFINITION_TABLE(void) __ptr64` | 2 | Exported Function
`public: __cdecl NTFS_ATTRIBUTE::NTFS_ATTRIBUTE(void) __ptr64` | 1 | Exported Function
`public: static unsigned char __cdecl NTFS_SA::IsNtfsName(struct _FILE_NAME const * __ptr64)` | 102 | Exported Function
`public: unsigned char __cdecl NTFS_EXTENT_LIST::QueryLcnFromVcn(class BIG_INT,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 121 | Exported Function
`public: unsigned char __cdecl NTFS_EXTENT_LIST::QueryExtent(unsigned long,class BIG_INT * __ptr64,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 115 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddFileNameAttribute(struct _FILE_NAME * __ptr64) __ptr64` | 44 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptorData(class NTFS_ATTRIBUTE * __ptr64,void * __ptr64,struct _SECURITY_ENTRY * __ptr64 * __ptr64,unsigned long,enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP * __ptr64,enum FIX_LEVEL) __ptr64` | 46 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptor(enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP * __ptr64) __ptr64` | 45 | Exported Function
`public: unsigned char __cdecl NTFS_BOOT_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 71 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 70 | Exported Function
`public: unsigned char __cdecl NTFS_CLUSTER_RUN::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,unsigned long) __ptr64` | 72 | Exported Function
`public: unsigned char __cdecl NTFS_EXTENT_LIST::Initialize(class BIG_INT,class BIG_INT) __ptr64` | 73 | Exported Function
`public: unsigned char __cdecl NTFS_EXTENT_LIST::AddExtent(class BIG_INT,class BIG_INT,class BIG_INT) __ptr64` | 43 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class NTFS_FRS_STRUCTURE * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 75 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,unsigned long,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 76 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::IsAttributePresent(unsigned long,class WSTRING const * __ptr64,unsigned char) __ptr64` | 99 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttributeByOrdinal(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long) __ptr64` | 107 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttribute(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64,unsigned long,class WSTRING const * __ptr64) __ptr64` | 106 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Flush(class NTFS_BITMAP * __ptr64,class NTFS_INDEX_TREE * __ptr64,unsigned char) __ptr64` | 57 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Create(struct _STANDARD_INFORMATION const * __ptr64,unsigned short) __ptr64` | 53 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL) __ptr64` | 74 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MFT_FILE * __ptr64) __ptr64` | 78 | Exported Function
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 77 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP::WriteModified(class NTFS_ATTRIBUTE * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 154 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Prefetch(class BIG_INT,unsigned long) __ptr64` | 104 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,void const * __ptr64,unsigned long,unsigned long,class WSTRING const * __ptr64,unsigned short) __ptr64` | 65 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Read(void * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64) __ptr64` | 128 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64,unsigned char) __ptr64` | 66 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE::ReadWithAltExtents(void * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64,class NTFS_EXTENT_LIST * __ptr64) __ptr64` | 138 | Exported Function
`public: static unsigned long __cdecl NTFS_SA::QuerySectorsInElementaryStructures(class DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned char)` | 125 | Exported Function
`public: static unsigned long __cdecl NTFS_SA::QueryDefaultClustersPerIndexBuffer(class DP_DRIVE const * __ptr64,unsigned long)` | 112 | Exported Function
`public: struct _ATTRIBUTE_LIST_ENTRY const * __ptr64 __cdecl NTFS_ATTRIBUTE_LIST::GetNextAttributeListEntry(struct _ATTRIBUTE_LIST_ENTRY const * __ptr64)const __ptr64` | 60 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_EXTENT_LIST const * __ptr64,class BIG_INT,class BIG_INT,unsigned long,class WSTRING const * __ptr64,unsigned short) __ptr64` | 64 | Exported Function
`public: struct _INDEX_ENTRY const * __ptr64 __cdecl NTFS_INDEX_TREE::GetNext(unsigned long * __ptr64,unsigned char * __ptr64,unsigned char) __ptr64` | 59 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP::Initialize(class BIG_INT,unsigned char,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,unsigned char) __ptr64` | 69 | Exported Function
`public: unsigned char __cdecl NTFS_BAD_CLUSTER_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 68 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP::IsAllocated(class BIG_INT,class BIG_INT)const __ptr64` | 98 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP::Write(class NTFS_ATTRIBUTE * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 151 | Exported Function
`public: unsigned char __cdecl NTFS_BITMAP::IsFree(class BIG_INT,class BIG_INT)const __ptr64` | 101 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_LIST::ReadList(void) __ptr64` | 136 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_LIST::QueryNextEntry(struct _ATTR_LIST_CURR_ENTRY * __ptr64,unsigned long * __ptr64,class BIG_INT * __ptr64,struct _MFT_SEGMENT_REFERENCE * __ptr64,unsigned short * __ptr64,class WSTRING * __ptr64)const __ptr64` | 123 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::Initialize(class IO_DP_DRIVE * __ptr64,void * __ptr64) __ptr64` | 67 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::QueryName(class WSTRING * __ptr64)const __ptr64` | 122 | Exported Function
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::QueryExtentList(class NTFS_EXTENT_LIST * __ptr64)const __ptr64` | 116 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/0a4ce1b7ed9e7df96faf45f83ed1c30d2da7b33e7d7a02faea1d5b9481e5eac8/detection/





MIT License. Copyright (c) 2020 Strontic.


