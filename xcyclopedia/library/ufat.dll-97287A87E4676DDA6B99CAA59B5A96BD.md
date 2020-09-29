---
title: ufat.dll | FAT Utility DLL
excerpt: What is ufat.dll?
---

# ufat.dll 

* File Path: `C:\Windows\system32\ufat.dll`
* Description: FAT Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `97287A87E4676DDA6B99CAA59B5A96BD`
SHA1 | `EC49D9452BA7BA2A19DBE3F2025F102838331FBA`
SHA256 | `007383619C4C18964B679E3DBA7ECB208AD6AE85E4CE2E4A2CA093163750E92A`
SHA384 | `F989B02181A989180F3691FD4B178DC434E2750C56CDB089E73375ECBA774362611C6C2A50DBD2FBC3AC16D4331E4195`
SHA512 | `1023AC3733646B50BCFA73208E7C4D3F26E649E290464D2BAD643ECDD831FE7BF4A0B05112FFA3F978453F737BCCED07F4D95F988B48272F838AF8CCAA55D8D2`
SSDEEP | `3072:v1vEoQhrwNBVAiSmHQLbTjqmdTrGq7f6XNE0H+FtuXl84bOL:9vEoArg3wm4TjfNjs+c`
IMP | `F65DFB35363CEE20864CB76371DC8200`
PESHA1 | `A15E88E6E8798339AD1CF85750A1FADE2D8D9364`
PE256 | `16EB30038A3E44E30FB01FA2EFA66E745A4D93C29954852A9165938368D95A18`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 51 (0x33) | Exported Function | 0x0000000180002a00 | 0x00002a00
`public: unsigned char __cdecl FILEDIR::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long) __ptr64` | 27 (0x1b) | Exported Function | 0x00000001800179b0 | 0x000179b0
`public: unsigned char __cdecl REAL_FAT_SA::InitFATChkDirty(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180018350 | 0x00018350
`public: unsigned char __cdecl ROOTDIR::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,long) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018001dbc0 | 0x0001dbc0
`public: unsigned long __cdecl FAT::AllocChain(unsigned long,unsigned long * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x00000001800062b0 | 0x000062b0
`public: unsigned long __cdecl FAT::QueryAllocatedClusters(void)const __ptr64` | 33 (0x21) | Exported Function | 0x0000000180005b10 | 0x00005b10
`public: unsigned long __cdecl FAT::QueryLengthOfChain(unsigned long,unsigned long * __ptr64)const __ptr64` | 41 (0x29) | Exported Function | 0x0000000180005c40 | 0x00005c40
`public: unsigned long __cdecl FAT::QueryNthCluster(unsigned long,unsigned long)const __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180005bd0 | 0x00005bd0
`public: unsigned long __cdecl FAT_SA::QueryFileStartingCluster(class WSTRING const * __ptr64,class HMEM * __ptr64,class FATDIR * __ptr64 * __ptr64,unsigned char * __ptr64,class FAT_DIRENT * __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180008100 | 0x00008100
`public: unsigned long __cdecl REAL_FAT_SA::QueryFreeSectors(void)const __ptr64` | 38 (0x26) | Exported Function | 0x000000018001cb20 | 0x0001cb20
`public: unsigned short __cdecl EA_HEADER::QueryEaSetClusterNumber(unsigned short)const __ptr64` | 36 (0x24) | Exported Function | 0x0000000180002100 | 0x00002100
`public: virtual __cdecl CLUSTER_CHAIN::~CLUSTER_CHAIN(void) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800017f0 | 0x000017f0
`public: unsigned char __cdecl FATDIR::QueryLongName(long,class WSTRING * __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x00000001800078f0 | 0x000078f0
`public: virtual __cdecl EA_HEADER::~EA_HEADER(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180001e90 | 0x00001e90
`public: virtual __cdecl FAT_DIRENT::~FAT_DIRENT(void) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800068e0 | 0x000068e0
`public: virtual __cdecl FAT_SA::~FAT_SA(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180007b70 | 0x00007b70
`public: virtual __cdecl FILEDIR::~FILEDIR(void) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180017970 | 0x00017970
`public: virtual __cdecl REAL_FAT_SA::~REAL_FAT_SA(void) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180017da0 | 0x00017da0
`public: virtual __cdecl ROOTDIR::~ROOTDIR(void) __ptr64` | 16 (0x10) | Exported Function | 0x000000018001db70 | 0x0001db70
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Read(void) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180001b90 | 0x00001b90
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Write(void) __ptr64` | 50 (0x32) | Exported Function | 0x0000000180001c20 | 0x00001c20
`public: virtual unsigned char __cdecl EA_SET::Read(void) __ptr64` | 46 (0x2e) | Exported Function | 0x00000001800024f0 | 0x000024f0
`public: virtual unsigned char __cdecl REAL_FAT_SA::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180017e10 | 0x00017e10
`public: virtual unsigned char __cdecl REAL_FAT_SA::Read(class MESSAGE * __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018001b940 | 0x0001b940
`public: void * __ptr64 __cdecl FATDIR::SearchForDirEntry(class WSTRING const * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180007700 | 0x00007700
`public: virtual __cdecl EA_SET::~EA_SET(void) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800022b0 | 0x000022b0
`public: unsigned char __cdecl FAT_SA::QueryCensusAndRelocate(struct _CENSUS_REPORT * __ptr64,class INTSTACK * __ptr64,unsigned char * __ptr64) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180015c80 | 0x00015c80
`public: unsigned char __cdecl FAT_DIRENT::QueryName(class WSTRING * __ptr64)const __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180006950 | 0x00006950
`public: unsigned char __cdecl FAT_DIRENT::QueryLastWriteTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 40 (0x28) | Exported Function | 0x0000000180007010 | 0x00007010
`ChkdskEx` | 52 (0x34) | Exported Function | 0x0000000180003460 | 0x00003460
`Format` | 53 (0x35) | Exported Function | 0x00000001800043c0 | 0x000043c0
`FormatEx` | 54 (0x36) | Exported Function | 0x0000000180004d90 | 0x00004d90
`GetFilesystemInformation` | 55 (0x37) | Exported Function | 0x00000001800048e0 | 0x000048e0
`private: unsigned long __cdecl FAT::Index12(unsigned long)const __ptr64` | 20 (0x14) | Exported Function | 0x00000001800059f0 | 0x000059f0
`private: void __cdecl FAT::Set12(unsigned long,unsigned long) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180005a40 | 0x00005a40
`public: __cdecl CLUSTER_CHAIN::CLUSTER_CHAIN(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001780 | 0x00001780
`public: __cdecl EA_HEADER::EA_HEADER(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001e40 | 0x00001e40
`public: __cdecl EA_SET::EA_SET(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180002250 | 0x00002250
`public: __cdecl FAT_DIRENT::FAT_DIRENT(void) __ptr64` | 4 (0x4) | Exported Function | 0x00000001800068a0 | 0x000068a0
`public: __cdecl FAT_SA::FAT_SA(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180007b20 | 0x00007b20
`public: __cdecl FILEDIR::FILEDIR(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180017910 | 0x00017910
`public: __cdecl REAL_FAT_SA::REAL_FAT_SA(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180017c80 | 0x00017c80
`public: __cdecl ROOTDIR::ROOTDIR(void) __ptr64` | 8 (0x8) | Exported Function | 0x000000018001db10 | 0x0001db10
`public: struct _EA * __ptr64 __cdecl EA_SET::GetEa(unsigned long,long * __ptr64,unsigned char * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x00000001800025b0 | 0x000025b0
`public: unsigned char __cdecl CLUSTER_CHAIN::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001840 | 0x00001840
`public: unsigned char __cdecl EA_HEADER::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180001ec0 | 0x00001ec0
`public: unsigned char __cdecl EA_SET::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180002300 | 0x00002300
`public: unsigned char __cdecl FAT_DIRENT::Initialize(void * __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180006910 | 0x00006910
`public: unsigned char __cdecl FAT_DIRENT::Initialize(void * __ptr64,unsigned char) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180006930 | 0x00006930
`public: unsigned char __cdecl FAT_DIRENT::IsValidCreationTime(void)const __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180007190 | 0x00007190
`public: unsigned char __cdecl FAT_DIRENT::IsValidLastAccessTime(void)const __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180007360 | 0x00007360
`public: unsigned char __cdecl FAT_DIRENT::IsValidLastWriteTime(void)const __ptr64` | 32 (0x20) | Exported Function | 0x0000000180006ff0 | 0x00006ff0
`public: unsigned char __cdecl FAT_DIRENT::QueryCreationTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 35 (0x23) | Exported Function | 0x00000001800071b0 | 0x000071b0
`public: unsigned char __cdecl FAT_DIRENT::QueryLastAccessTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 39 (0x27) | Exported Function | 0x0000000180007380 | 0x00007380
`public: void __cdecl FAT::FreeChain(unsigned long) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180006710 | 0x00006710
`Recover` | 56 (0x38) | Exported Function | 0x0000000180005380 | 0x00005380


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UFAT.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/007383619c4c18964b679e3dba7ecb208ad6ae85e4ce2e4a2ca093163750e92a/detection/





MIT License. Copyright (c) 2020 Strontic.


