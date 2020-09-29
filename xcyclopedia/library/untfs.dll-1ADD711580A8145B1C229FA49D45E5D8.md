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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 156 (0x9c) | Exported Function | 0x000000018000e770 | 0x0000e770
`public: unsigned char __cdecl NTFS_INDEX_TREE::Save(class NTFS_FILE_RECORD_SEGMENT * __ptr64) __ptr64` | 144 (0x90) | Exported Function | 0x0000000180035050 | 0x00035050
`public: unsigned char __cdecl NTFS_LOG_FILE::CreateDataAttribute(class BIG_INT,unsigned long,class NTFS_BITMAP * __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180039220 | 0x00039220
`public: unsigned char __cdecl NTFS_LOG_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180039200 | 0x00039200
`public: unsigned char __cdecl NTFS_MASTER_FILE_TABLE::AllocateFileRecordSegment(class BIG_INT * __ptr64,unsigned char) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018003a2c0 | 0x0003a2c0
`public: unsigned char __cdecl NTFS_MASTER_FILE_TABLE::Extend(unsigned long) __ptr64` | 56 (0x38) | Exported Function | 0x000000018003a570 | 0x0003a570
`public: unsigned char __cdecl NTFS_MFT_FILE::Flush(void) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018003ad40 | 0x0003ad40
`public: unsigned char __cdecl NTFS_MFT_FILE::Initialize(enum FIX_LEVEL,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,class NTFS_ATTRIBUTE * __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x000000018003a780 | 0x0003a780
`public: unsigned char __cdecl NTFS_MFT_INFO::Initialize(class BIG_INT,class NTFS_UPCASE_TABLE * __ptr64,unsigned char,unsigned char,unsigned __int64) __ptr64` | 87 (0x57) | Exported Function | 0x000000018003b5f0 | 0x0003b5f0
`public: unsigned char __cdecl NTFS_MFT_INFO::Initialize(void) __ptr64` | 88 (0x58) | Exported Function | 0x000000018003b6e0 | 0x0003b6e0
`public: unsigned char __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x000000018003bd10 | 0x0003bd10
`public: unsigned char __cdecl NTFS_SA::CreateElementaryStructures(class NTFS_BITMAP * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,class NUMBER_SET const * __ptr64,unsigned char,unsigned char,unsigned char,unsigned char,unsigned char,unsigned long,class MESSAGE * __ptr64,struct BIOS_PARAMETER_BLOCK * __ptr64,class WSTRING const * __ptr64,unsigned char) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180012440 | 0x00012440
`public: unsigned char __cdecl NTFS_SA::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64,class BIG_INT,class BIG_INT,unsigned long,unsigned char) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180056540 | 0x00056540
`public: unsigned char __cdecl NTFS_SA::QueryFrsFromPath(enum FIX_LEVEL,class WSTRING const * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64,class NTFS_BITMAP * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64) __ptr64` | 120 (0x78) | Exported Function | 0x00000001800570e0 | 0x000570e0
`public: unsigned char __cdecl NTFS_SA::Read(class MESSAGE * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x0000000180056d10 | 0x00056d10
`public: unsigned char __cdecl NTFS_SA::SetVolumeFlag(unsigned short,unsigned char * __ptr64) __ptr64` | 147 (0x93) | Exported Function | 0x00000001800584f0 | 0x000584f0
`public: unsigned char __cdecl NTFS_SA::TakeCensus(class NTFS_MASTER_FILE_TABLE * __ptr64,unsigned long,struct NTFS_CENSUS_INFO * __ptr64) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180058790 | 0x00058790
`public: unsigned char __cdecl NTFS_SA::WriteRemainingBootCode(void) __ptr64` | 155 (0x9b) | Exported Function | 0x00000001800122f0 | 0x000122f0
`public: unsigned char __cdecl NTFS_INDEX_TREE::ResetIterator(unsigned char) __ptr64` | 140 (0x8c) | Exported Function | 0x0000000180037ed0 | 0x00037ed0
`public: unsigned char __cdecl NTFS_UPCASE_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x000000018007ac20 | 0x0007ac20
`public: unsigned char __cdecl NTFS_INDEX_TREE::ResetIterator(struct _INDEX_ENTRY const * __ptr64,unsigned char) __ptr64` | 141 (0x8d) | Exported Function | 0x0000000180037fd0 | 0x00037fd0
`public: unsigned char __cdecl NTFS_INDEX_TREE::QueryEntry(unsigned long,void * __ptr64,unsigned long,struct _INDEX_ENTRY * __ptr64 * __ptr64,class NTFS_INDEX_BUFFER * __ptr64 * __ptr64,unsigned char * __ptr64) __ptr64` | 114 (0x72) | Exported Function | 0x0000000180034c60 | 0x00034c60
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryFileSizes(class BIG_INT * __ptr64,class BIG_INT * __ptr64,unsigned char * __ptr64) __ptr64` | 118 (0x76) | Exported Function | 0x00000001800198e0 | 0x000198e0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64,unsigned long) __ptr64` | 80 (0x50) | Exported Function | 0x000000018001f210 | 0x0001f210
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x000000018001f030 | 0x0001f030
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(class MEM * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x000000018001f0e0 | 0x0001f0e0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Initialize(struct _FILE_RECORD_SEGMENT_HEADER * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class BIG_INT,unsigned long,unsigned long,class BIG_INT,unsigned long,class NTFS_UPCASE_TABLE * __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x000000018001f190 | 0x0001f190
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Prefetch(class BIG_INT,class BIG_INT) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180020e80 | 0x00020e80
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::QueryAttributeList(class NTFS_ATTRIBUTE_LIST * __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180021200 | 0x00021200
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Read(class BIG_INT) __ptr64` | 129 (0x81) | Exported Function | 0x0000000180020bd0 | 0x00020bd0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadAgain(class BIG_INT) __ptr64` | 134 (0x86) | Exported Function | 0x0000000180020c90 | 0x00020c90
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadAt(class BIG_INT) __ptr64` | 135 (0x87) | Exported Function | 0x0000000180020bd0 | 0x00020bd0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::ReadNext(class BIG_INT) __ptr64` | 137 (0x89) | Exported Function | 0x0000000180020bf0 | 0x00020bf0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::SafeQueryAttribute(unsigned long,class NTFS_ATTRIBUTE * __ptr64,class NTFS_ATTRIBUTE * __ptr64,class WSTRING * __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x00000001800214f0 | 0x000214f0
`public: unsigned char __cdecl NTFS_FRS_STRUCTURE::Write(void) __ptr64` | 153 (0x99) | Exported Function | 0x0000000180020ca0 | 0x00020ca0
`public: unsigned char __cdecl NTFS_INDEX_TREE::CopyIterator(class NTFS_INDEX_TREE * __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180038420 | 0x00038420
`public: unsigned char __cdecl NTFS_INDEX_TREE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,unsigned long,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class WSTRING const * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x00000001800345b0 | 0x000345b0
`public: unsigned char __cdecl NTFS_INDEX_TREE::Initialize(unsigned long,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_BITMAP * __ptr64,class NTFS_UPCASE_TABLE * __ptr64,unsigned long,unsigned long,unsigned long,class WSTRING const * __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x0000000180034970 | 0x00034970
`public: unsigned char __cdecl NTFS_INDEX_TREE::InsertEntry(unsigned long,void * __ptr64,struct _MFT_SEGMENT_REFERENCE,unsigned char) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180034d20 | 0x00034d20
`public: unsigned char __cdecl NTFS_INDEX_TREE::QueryFileReference(unsigned long,void * __ptr64,unsigned long,struct _MFT_SEGMENT_REFERENCE * __ptr64,unsigned char * __ptr64) __ptr64` | 117 (0x75) | Exported Function | 0x0000000180034b80 | 0x00034b80
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryDuplicatedInformation(struct _DUPLICATED_INFORMATION * __ptr64) __ptr64` | 113 (0x71) | Exported Function | 0x000000018001d540 | 0x0001d540
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(class NTFS_ATTRIBUTE * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x000000018007a7b0 | 0x0007a7b0
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(void) __ptr64` | 94 (0x5e) | Exported Function | 0x000000018007a920 | 0x0007a920
`public: virtual __cdecl NTFS_SA::~NTFS_SA(void) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180056490 | 0x00056490
`public: virtual __cdecl NTFS_UPCASE_FILE::~NTFS_UPCASE_FILE(void) __ptr64` | 40 (0x28) | Exported Function | 0x000000018000df90 | 0x0000df90
`public: virtual __cdecl NTFS_UPCASE_TABLE::~NTFS_UPCASE_TABLE(void) __ptr64` | 41 (0x29) | Exported Function | 0x000000018007a680 | 0x0007a680
`public: virtual __cdecl NTFS_VOLUME_FILE::~NTFS_VOLUME_FILE(void) __ptr64` | 42 (0x2a) | Exported Function | 0x000000018007d350 | 0x0007d350
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::GrowSparse(class BIG_INT,class NTFS_BITMAP * __ptr64,unsigned char) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180006d50 | 0x00006d50
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::InsertIntoFile(class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180006360 | 0x00006360
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::MakeNonresident(class NTFS_BITMAP * __ptr64) __ptr64` | 103 (0x67) | Exported Function | 0x00000001800067a0 | 0x000067a0
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::Resize(class BIG_INT,class NTFS_BITMAP * __ptr64) __ptr64` | 142 (0x8e) | Exported Function | 0x0000000180006aa0 | 0x00006aa0
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::SetSparse(class BIG_INT,class NTFS_BITMAP * __ptr64,unsigned char) __ptr64` | 146 (0x92) | Exported Function | 0x0000000180006c50 | 0x00006c50
`public: virtual unsigned char __cdecl NTFS_ATTRIBUTE::Write(void const * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 150 (0x96) | Exported Function | 0x00000001800073b0 | 0x000073b0
`public: virtual unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Write(void) __ptr64` | 152 (0x98) | Exported Function | 0x000000018001b9a0 | 0x0001b9a0
`public: virtual unsigned char __cdecl NTFS_FRS_STRUCTURE::Read(void) __ptr64` | 130 (0x82) | Exported Function | 0x0000000180020b20 | 0x00020b20
`public: virtual unsigned char __cdecl NTFS_MFT_FILE::Read(void) __ptr64` | 131 (0x83) | Exported Function | 0x000000018003abc0 | 0x0003abc0
`public: virtual unsigned char __cdecl NTFS_SA::Read(void) __ptr64` | 133 (0x85) | Exported Function | 0x0000000180058720 | 0x00058720
`public: void * __ptr64 __cdecl NTFS_FRS_STRUCTURE::GetNextAttributeRecord(void const * __ptr64,class MESSAGE * __ptr64,unsigned char * __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180020ec0 | 0x00020ec0
`public: void __cdecl NTFS_CLUSTER_RUN::Relocate(class BIG_INT) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018000e630 | 0x0000e630
`Recover` | 167 (0xa7) | Exported Function | 0x0000000180010c60 | 0x00010c60
`public: virtual __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::~NTFS_REFLECTED_MASTER_FILE_TABLE(void) __ptr64` | 38 (0x26) | Exported Function | 0x000000018000df90 | 0x0000df90
`public: unsigned char __cdecl NTFS_UPCASE_TABLE::Initialize(unsigned short * __ptr64,unsigned long) __ptr64` | 92 (0x5c) | Exported Function | 0x000000018007a890 | 0x0007a890
`public: virtual __cdecl NTFS_MFT_INFO::~NTFS_MFT_INFO(void) __ptr64` | 37 (0x25) | Exported Function | 0x000000018003b5a0 | 0x0003b5a0
`public: virtual __cdecl NTFS_LOG_FILE::~NTFS_LOG_FILE(void) __ptr64` | 35 (0x23) | Exported Function | 0x000000018000df90 | 0x0000df90
`public: unsigned char __cdecl NTFS_VOLUME_FILE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_INDEX_TREE * __ptr64,struct _VOLUME_INFORMATION * __ptr64,class WSTRING * __ptr64,enum FIX_LEVEL) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018007d390 | 0x0007d390
`public: unsigned long __cdecl NTFS_EXTENT_LIST::QueryNumberOfExtents(void)const __ptr64` | 124 (0x7c) | Exported Function | 0x0000000180011f70 | 0x00011f70
`public: unsigned long __cdecl NTFS_SA::QueryClusterFactor(void)const __ptr64` | 110 (0x6e) | Exported Function | 0x0000000180058770 | 0x00058770
`public: unsigned short __cdecl NTFS_SA::QueryVolumeFlagsAndLabel(unsigned char * __ptr64,unsigned char * __ptr64,unsigned char * __ptr64,class WSTRING * __ptr64) __ptr64` | 127 (0x7f) | Exported Function | 0x0000000180057570 | 0x00057570
`public: virtual __cdecl NTFS_ATTRIBUTE::~NTFS_ATTRIBUTE(void) __ptr64` | 22 (0x16) | Exported Function | 0x00000001800054f0 | 0x000054f0
`public: virtual __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::~NTFS_ATTRIBUTE_DEFINITION_TABLE(void) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180004a70 | 0x00004a70
`public: virtual __cdecl NTFS_ATTRIBUTE_LIST::~NTFS_ATTRIBUTE_LIST(void) __ptr64` | 24 (0x18) | Exported Function | 0x00000001800095a0 | 0x000095a0
`public: virtual __cdecl NTFS_ATTRIBUTE_RECORD::~NTFS_ATTRIBUTE_RECORD(void) __ptr64` | 25 (0x19) | Exported Function | 0x000000018000a980 | 0x0000a980
`public: virtual __cdecl NTFS_BAD_CLUSTER_FILE::~NTFS_BAD_CLUSTER_FILE(void) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018000d170 | 0x0000d170
`public: virtual __cdecl NTFS_BITMAP::~NTFS_BITMAP(void) __ptr64` | 27 (0x1b) | Exported Function | 0x000000018003c620 | 0x0003c620
`public: virtual __cdecl NTFS_BITMAP_FILE::~NTFS_BITMAP_FILE(void) __ptr64` | 28 (0x1c) | Exported Function | 0x000000018000df90 | 0x0000df90
`public: virtual __cdecl NTFS_BOOT_FILE::~NTFS_BOOT_FILE(void) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018000df90 | 0x0000df90
`public: virtual __cdecl NTFS_CLUSTER_RUN::~NTFS_CLUSTER_RUN(void) __ptr64` | 30 (0x1e) | Exported Function | 0x000000018000e580 | 0x0000e580
`public: virtual __cdecl NTFS_EXTENT_LIST::~NTFS_EXTENT_LIST(void) __ptr64` | 31 (0x1f) | Exported Function | 0x00000001800111c0 | 0x000111c0
`public: virtual __cdecl NTFS_FILE_RECORD_SEGMENT::~NTFS_FILE_RECORD_SEGMENT(void) __ptr64` | 32 (0x20) | Exported Function | 0x00000001800153c0 | 0x000153c0
`public: virtual __cdecl NTFS_FRS_STRUCTURE::~NTFS_FRS_STRUCTURE(void) __ptr64` | 33 (0x21) | Exported Function | 0x000000018001ef90 | 0x0001ef90
`public: virtual __cdecl NTFS_INDEX_TREE::~NTFS_INDEX_TREE(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180034380 | 0x00034380
`public: virtual __cdecl NTFS_MFT_FILE::~NTFS_MFT_FILE(void) __ptr64` | 36 (0x24) | Exported Function | 0x000000018003a700 | 0x0003a700
`SetOriginalVolumeName` | 145 (0x91) | Exported Function | 0x000000018000ec70 | 0x0000ec70
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttributeListAttribute(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x000000018001e120 | 0x0001e120
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttribute(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64,unsigned long,class WSTRING const * __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180019380 | 0x00019380
`public: __cdecl NTFS_EXTENT_LIST::NTFS_EXTENT_LIST(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180011120 | 0x00011120
`public: __cdecl NTFS_FILE_RECORD_SEGMENT::NTFS_FILE_RECORD_SEGMENT(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180015340 | 0x00015340
`public: __cdecl NTFS_FRS_STRUCTURE::NTFS_FRS_STRUCTURE(void) __ptr64` | 12 (0xc) | Exported Function | 0x000000018001ef20 | 0x0001ef20
`public: __cdecl NTFS_INDEX_TREE::NTFS_INDEX_TREE(void) __ptr64` | 13 (0xd) | Exported Function | 0x00000001800342e0 | 0x000342e0
`public: __cdecl NTFS_LOG_FILE::NTFS_LOG_FILE(void) __ptr64` | 14 (0xe) | Exported Function | 0x00000001800391c0 | 0x000391c0
`public: __cdecl NTFS_MFT_FILE::NTFS_MFT_FILE(void) __ptr64` | 15 (0xf) | Exported Function | 0x000000018003a670 | 0x0003a670
`public: __cdecl NTFS_MFT_INFO::NTFS_MFT_INFO(void) __ptr64` | 16 (0x10) | Exported Function | 0x000000018003b4a0 | 0x0003b4a0
`public: __cdecl NTFS_REFLECTED_MASTER_FILE_TABLE::NTFS_REFLECTED_MASTER_FILE_TABLE(void) __ptr64` | 17 (0x11) | Exported Function | 0x000000018003bcd0 | 0x0003bcd0
`public: __cdecl NTFS_SA::NTFS_SA(void) __ptr64` | 18 (0x12) | Exported Function | 0x00000001800563c0 | 0x000563c0
`public: __cdecl NTFS_UPCASE_FILE::NTFS_UPCASE_FILE(void) __ptr64` | 19 (0x13) | Exported Function | 0x000000018007abe0 | 0x0007abe0
`public: __cdecl NTFS_UPCASE_TABLE::NTFS_UPCASE_TABLE(void) __ptr64` | 20 (0x14) | Exported Function | 0x000000018007a630 | 0x0007a630
`public: __cdecl NTFS_VOLUME_FILE::NTFS_VOLUME_FILE(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018007d300 | 0x0007d300
`public: class BIG_INT __cdecl NTFS_ATTRIBUTE::QueryClustersAllocated(void)const __ptr64` | 111 (0x6f) | Exported Function | 0x0000000180008ae0 | 0x00008ae0
`public: static struct _MFT_SEGMENT_REFERENCE __cdecl NTFS_MFT_INFO::QuerySegmentReference(void * __ptr64)` | 126 (0x7e) | Exported Function | 0x0000000180001800 | 0x00001800
`public: static unsigned char __cdecl NTFS_MFT_INFO::CompareDupInfo(void * __ptr64,struct _FILE_NAME * __ptr64)` | 48 (0x30) | Exported Function | 0x0000000180001810 | 0x00001810
`public: static unsigned char __cdecl NTFS_MFT_INFO::CompareFileName(void * __ptr64,unsigned long,struct _FILE_NAME * __ptr64,unsigned short * __ptr64)` | 49 (0x31) | Exported Function | 0x000000018003b750 | 0x0003b750
`public: static unsigned char __cdecl NTFS_MFT_INFO::QueryFlags(void * __ptr64,unsigned short)` | 119 (0x77) | Exported Function | 0x0000000180001840 | 0x00001840
`public: __cdecl NTFS_CLUSTER_RUN::NTFS_CLUSTER_RUN(void) __ptr64` | 9 (0x9) | Exported Function | 0x000000018000e530 | 0x0000e530
`public: static unsigned char __cdecl NTFS_SA::GetRootFrsIndex(enum FIX_LEVEL,class NTFS_MFT_FILE * __ptr64,class NTFS_FILE_RECORD_SEGMENT * __ptr64,class NTFS_INDEX_TREE * __ptr64)` | 62 (0x3e) | Exported Function | 0x0000000180047bf0 | 0x00047bf0
`public: __cdecl NTFS_BOOT_FILE::NTFS_BOOT_FILE(void) __ptr64` | 8 (0x8) | Exported Function | 0x000000018000e210 | 0x0000e210
`public: __cdecl NTFS_BITMAP::NTFS_BITMAP(void) __ptr64` | 6 (0x6) | Exported Function | 0x000000018003c590 | 0x0003c590
`ChkdskEx` | 157 (0x9d) | Exported Function | 0x000000018000f130 | 0x0000f130
`CreateFormatCorruptionRecordContext` | 158 (0x9e) | Exported Function | 0x0000000180001850 | 0x00001850
`DeleteFormatCorruptionRecordContext` | 159 (0x9f) | Exported Function | 0x00000001800018b0 | 0x000018b0
`Extend` | 160 (0xa0) | Exported Function | 0x0000000180010e80 | 0x00010e80
`Format` | 161 (0xa1) | Exported Function | 0x0000000180010210 | 0x00010210
`FormatCorruptionRecordA` | 162 (0xa2) | Exported Function | 0x00000001800018e0 | 0x000018e0
`FormatCorruptionRecordW` | 163 (0xa3) | Exported Function | 0x00000001800018f0 | 0x000018f0
`FormatEx` | 164 (0xa4) | Exported Function | 0x0000000180010610 | 0x00010610
`GetFilesystemInformation` | 165 (0xa5) | Exported Function | 0x000000018000ffe0 | 0x0000ffe0
`NtfsUpcaseCompare` | 166 (0xa6) | Exported Function | 0x000000018007aa10 | 0x0007aa10
`private: static void __cdecl NTFS_MFT_INFO::ComputeDupInfoSignature(struct _DUPLICATED_INFORMATION * __ptr64,unsigned char * __ptr64 const)` | 50 (0x32) | Exported Function | 0x000000018003bb80 | 0x0003bb80
`private: static void __cdecl NTFS_MFT_INFO::ComputeFileNameSignature(unsigned long,struct _FILE_NAME * __ptr64,unsigned char * __ptr64 const)` | 51 (0x33) | Exported Function | 0x000000018003bad0 | 0x0003bad0
`public: __cdecl NTFS_ATTRIBUTE::NTFS_ATTRIBUTE(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180005470 | 0x00005470
`public: __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::NTFS_ATTRIBUTE_DEFINITION_TABLE(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180004a30 | 0x00004a30
`public: __cdecl NTFS_ATTRIBUTE_LIST::NTFS_ATTRIBUTE_LIST(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180009540 | 0x00009540
`public: __cdecl NTFS_ATTRIBUTE_RECORD::NTFS_ATTRIBUTE_RECORD(void) __ptr64` | 4 (0x4) | Exported Function | 0x000000018000a930 | 0x0000a930
`public: __cdecl NTFS_BAD_CLUSTER_FILE::NTFS_BAD_CLUSTER_FILE(void) __ptr64` | 5 (0x5) | Exported Function | 0x000000018000d130 | 0x0000d130
`public: __cdecl NTFS_BITMAP_FILE::NTFS_BITMAP_FILE(void) __ptr64` | 7 (0x7) | Exported Function | 0x000000018000df50 | 0x0000df50
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::QueryAttributeByOrdinal(class NTFS_ATTRIBUTE * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180019c60 | 0x00019c60
`public: static unsigned char __cdecl NTFS_SA::IsDosName(struct _FILE_NAME const * __ptr64)` | 100 (0x64) | Exported Function | 0x0000000180057f40 | 0x00057f40
`public: static unsigned long __cdecl NTFS_SA::QueryDefaultClustersPerIndexBuffer(class DP_DRIVE const * __ptr64,unsigned long)` | 112 (0x70) | Exported Function | 0x0000000180058290 | 0x00058290
`public: unsigned char __cdecl NTFS_BOOT_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x000000018000e250 | 0x0000e250
`public: unsigned char __cdecl NTFS_CLUSTER_RUN::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class BIG_INT,unsigned long,unsigned long) __ptr64` | 72 (0x48) | Exported Function | 0x000000018000e5b0 | 0x0000e5b0
`public: unsigned char __cdecl NTFS_EXTENT_LIST::AddExtent(class BIG_INT,class BIG_INT,class BIG_INT) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180011680 | 0x00011680
`public: unsigned char __cdecl NTFS_EXTENT_LIST::Initialize(class BIG_INT,class BIG_INT) __ptr64` | 73 (0x49) | Exported Function | 0x00000001800112b0 | 0x000112b0
`public: unsigned char __cdecl NTFS_EXTENT_LIST::QueryExtent(unsigned long,class BIG_INT * __ptr64,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 115 (0x73) | Exported Function | 0x0000000180011880 | 0x00011880
`public: unsigned char __cdecl NTFS_EXTENT_LIST::QueryLcnFromVcn(class BIG_INT,class BIG_INT * __ptr64,class BIG_INT * __ptr64)const __ptr64` | 121 (0x79) | Exported Function | 0x00000001800118e0 | 0x000118e0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddFileNameAttribute(struct _FILE_NAME * __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180018c60 | 0x00018c60
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptor(enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP * __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180018e00 | 0x00018e00
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::AddSecurityDescriptorData(class NTFS_ATTRIBUTE * __ptr64,void * __ptr64,struct _SECURITY_ENTRY * __ptr64 * __ptr64,unsigned long,enum _CANNED_SECURITY_TYPE,class NTFS_BITMAP * __ptr64,enum FIX_LEVEL) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180018e80 | 0x00018e80
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Create(struct _STANDARD_INFORMATION const * __ptr64,unsigned short) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180015ab0 | 0x00015ab0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Flush(class NTFS_BITMAP * __ptr64,class NTFS_INDEX_TREE * __ptr64,unsigned char) __ptr64` | 57 (0x39) | Exported Function | 0x000000018001b9b0 | 0x0001b9b0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL) __ptr64` | 74 (0x4a) | Exported Function | 0x00000001800156c0 | 0x000156c0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180015490 | 0x00015490
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,class NTFS_MFT_FILE * __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180015790 | 0x00015790
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class BIG_INT,unsigned long,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x00000001800155a0 | 0x000155a0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::Initialize(enum FIX_LEVEL,class NTFS_FRS_STRUCTURE * __ptr64,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x00000001800157c0 | 0x000157c0
`public: unsigned char __cdecl NTFS_FILE_RECORD_SEGMENT::IsAttributePresent(unsigned long,class WSTRING const * __ptr64,unsigned char) __ptr64` | 99 (0x63) | Exported Function | 0x00000001800191c0 | 0x000191c0
`public: unsigned char __cdecl NTFS_BITMAP_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x000000018000dfb0 | 0x0000dfb0
`public: static unsigned char __cdecl NTFS_SA::IsNtfsName(struct _FILE_NAME const * __ptr64)` | 102 (0x66) | Exported Function | 0x0000000180057ed0 | 0x00057ed0
`public: unsigned char __cdecl NTFS_BITMAP::WriteModified(class NTFS_ATTRIBUTE * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 154 (0x9a) | Exported Function | 0x000000018003c910 | 0x0003c910
`public: unsigned char __cdecl NTFS_BITMAP::IsFree(class BIG_INT,class BIG_INT)const __ptr64` | 101 (0x65) | Exported Function | 0x000000018003cd20 | 0x0003cd20
`public: static unsigned long __cdecl NTFS_SA::QuerySectorsInElementaryStructures(class DP_DRIVE * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned char)` | 125 (0x7d) | Exported Function | 0x00000001800120d0 | 0x000120d0
`public: struct _ATTRIBUTE_LIST_ENTRY const * __ptr64 __cdecl NTFS_ATTRIBUTE_LIST::GetNextAttributeListEntry(struct _ATTRIBUTE_LIST_ENTRY const * __ptr64)const __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180009ee0 | 0x00009ee0
`public: struct _INDEX_ENTRY const * __ptr64 __cdecl NTFS_INDEX_TREE::GetNext(unsigned long * __ptr64,unsigned char * __ptr64,unsigned char) __ptr64` | 59 (0x3b) | Exported Function | 0x00000001800383c0 | 0x000383c0
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,class NTFS_EXTENT_LIST const * __ptr64,class BIG_INT,class BIG_INT,unsigned long,class WSTRING const * __ptr64,unsigned short) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180005740 | 0x00005740
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Initialize(class LOG_IO_DP_DRIVE * __ptr64,unsigned long,void const * __ptr64,unsigned long,unsigned long,class WSTRING const * __ptr64,unsigned short) __ptr64` | 65 (0x41) | Exported Function | 0x00000001800055d0 | 0x000055d0
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Prefetch(class BIG_INT,unsigned long) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180007180 | 0x00007180
`public: unsigned char __cdecl NTFS_ATTRIBUTE::Read(void * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64) __ptr64` | 128 (0x80) | Exported Function | 0x0000000180006e10 | 0x00006e10
`public: unsigned char __cdecl NTFS_ATTRIBUTE::ReadWithAltExtents(void * __ptr64,class BIG_INT,unsigned long,unsigned long * __ptr64,class NTFS_EXTENT_LIST * __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180006e40 | 0x00006e40
`public: unsigned char __cdecl NTFS_ATTRIBUTE_DEFINITION_TABLE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64,unsigned char) __ptr64` | 66 (0x42) | Exported Function | 0x0000000180004a90 | 0x00004a90
`public: unsigned char __cdecl NTFS_ATTRIBUTE_LIST::QueryNextEntry(struct _ATTR_LIST_CURR_ENTRY * __ptr64,unsigned long * __ptr64,class BIG_INT * __ptr64,struct _MFT_SEGMENT_REFERENCE * __ptr64,unsigned short * __ptr64,class WSTRING * __ptr64)const __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180009e40 | 0x00009e40
`public: unsigned char __cdecl NTFS_ATTRIBUTE_LIST::ReadList(void) __ptr64` | 136 (0x88) | Exported Function | 0x000000018000a080 | 0x0000a080
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::Initialize(class IO_DP_DRIVE * __ptr64,void * __ptr64) __ptr64` | 67 (0x43) | Exported Function | 0x000000018000aac0 | 0x0000aac0
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::QueryExtentList(class NTFS_EXTENT_LIST * __ptr64)const __ptr64` | 116 (0x74) | Exported Function | 0x000000018000ccd0 | 0x0000ccd0
`public: unsigned char __cdecl NTFS_ATTRIBUTE_RECORD::QueryName(class WSTRING * __ptr64)const __ptr64` | 122 (0x7a) | Exported Function | 0x000000018000cbe0 | 0x0000cbe0
`public: unsigned char __cdecl NTFS_BAD_CLUSTER_FILE::Initialize(enum FIX_LEVEL,class NTFS_MASTER_FILE_TABLE * __ptr64) __ptr64` | 68 (0x44) | Exported Function | 0x000000018000d200 | 0x0000d200
`public: unsigned char __cdecl NTFS_BITMAP::Initialize(class BIG_INT,unsigned char,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,unsigned char) __ptr64` | 69 (0x45) | Exported Function | 0x000000018003c6e0 | 0x0003c6e0
`public: unsigned char __cdecl NTFS_BITMAP::IsAllocated(class BIG_INT,class BIG_INT)const __ptr64` | 98 (0x62) | Exported Function | 0x000000018003cda0 | 0x0003cda0
`public: unsigned char __cdecl NTFS_BITMAP::Write(class NTFS_ATTRIBUTE * __ptr64,class NTFS_BITMAP * __ptr64) __ptr64` | 151 (0x97) | Exported Function | 0x000000018003c850 | 0x0003c850
`SetWriteViewCacheVolumeName` | 148 (0x94) | Exported Function | 0x000000018000ee50 | 0x0000ee50


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


