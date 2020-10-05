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

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned long __cdecl FAT_SA::QueryFileStartingCluster(class WSTRING const * __ptr64,class HMEM * __ptr64,class FATDIR * __ptr64 * __ptr64,unsigned char * __ptr64,class FAT_DIRENT * __ptr64) __ptr64` | 37 | Exported Function
`public: unsigned long __cdecl FAT::QueryNthCluster(unsigned long,unsigned long)const __ptr64` | 44 | Exported Function
`public: unsigned long __cdecl FAT::QueryLengthOfChain(unsigned long,unsigned long * __ptr64)const __ptr64` | 41 | Exported Function
`public: unsigned long __cdecl REAL_FAT_SA::QueryFreeSectors(void)const __ptr64` | 38 | Exported Function
`public: virtual __cdecl EA_HEADER::~EA_HEADER(void) __ptr64` | 10 | Exported Function
`public: virtual __cdecl CLUSTER_CHAIN::~CLUSTER_CHAIN(void) __ptr64` | 9 | Exported Function
`public: unsigned short __cdecl EA_HEADER::QueryEaSetClusterNumber(unsigned short)const __ptr64` | 36 | Exported Function
`public: unsigned char __cdecl FILEDIR::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long) __ptr64` | 27 | Exported Function
`public: unsigned char __cdecl FATDIR::QueryLongName(long,class WSTRING * __ptr64) __ptr64` | 42 | Exported Function
`public: unsigned char __cdecl FAT_SA::QueryCensusAndRelocate(struct _CENSUS_REPORT * __ptr64,class INTSTACK * __ptr64,unsigned char * __ptr64) __ptr64` | 34 | Exported Function
`public: unsigned char __cdecl REAL_FAT_SA::InitFATChkDirty(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64) __ptr64` | 21 | Exported Function
`public: unsigned long __cdecl FAT::QueryAllocatedClusters(void)const __ptr64` | 33 | Exported Function
`public: unsigned long __cdecl FAT::AllocChain(unsigned long,unsigned long * __ptr64) __ptr64` | 17 | Exported Function
`public: unsigned char __cdecl ROOTDIR::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,unsigned long,long) __ptr64` | 29 | Exported Function
`public: virtual unsigned char __cdecl REAL_FAT_SA::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64,unsigned char) __ptr64` | 28 | Exported Function
`public: virtual unsigned char __cdecl EA_SET::Read(void) __ptr64` | 46 | Exported Function
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Write(void) __ptr64` | 50 | Exported Function
`public: virtual unsigned char __cdecl REAL_FAT_SA::Read(class MESSAGE * __ptr64) __ptr64` | 47 | Exported Function
`Recover` | 56 | Exported Function
`public: void __cdecl FAT::FreeChain(unsigned long) __ptr64` | 18 | Exported Function
`public: void * __ptr64 __cdecl FATDIR::SearchForDirEntry(class WSTRING const * __ptr64) __ptr64` | 48 | Exported Function
`public: virtual __cdecl FAT_SA::~FAT_SA(void) __ptr64` | 13 | Exported Function
`public: virtual __cdecl FAT_DIRENT::~FAT_DIRENT(void) __ptr64` | 12 | Exported Function
`public: virtual __cdecl EA_SET::~EA_SET(void) __ptr64` | 11 | Exported Function
`public: virtual __cdecl FILEDIR::~FILEDIR(void) __ptr64` | 14 | Exported Function
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Read(void) __ptr64` | 45 | Exported Function
`public: virtual __cdecl ROOTDIR::~ROOTDIR(void) __ptr64` | 16 | Exported Function
`public: virtual __cdecl REAL_FAT_SA::~REAL_FAT_SA(void) __ptr64` | 15 | Exported Function
`public: __cdecl EA_SET::EA_SET(void) __ptr64` | 3 | Exported Function
`public: __cdecl EA_HEADER::EA_HEADER(void) __ptr64` | 2 | Exported Function
`public: __cdecl CLUSTER_CHAIN::CLUSTER_CHAIN(void) __ptr64` | 1 | Exported Function
`public: __cdecl FAT_DIRENT::FAT_DIRENT(void) __ptr64` | 4 | Exported Function
`public: __cdecl REAL_FAT_SA::REAL_FAT_SA(void) __ptr64` | 7 | Exported Function
`public: __cdecl FILEDIR::FILEDIR(void) __ptr64` | 6 | Exported Function
`public: __cdecl FAT_SA::FAT_SA(void) __ptr64` | 5 | Exported Function
`Format` | 53 | Exported Function
`ChkdskEx` | 52 | Exported Function
`Chkdsk` | 51 | Exported Function
`FormatEx` | 54 | Exported Function
`private: void __cdecl FAT::Set12(unsigned long,unsigned long) __ptr64` | 49 | Exported Function
`private: unsigned long __cdecl FAT::Index12(unsigned long)const __ptr64` | 20 | Exported Function
`GetFilesystemInformation` | 55 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::IsValidLastWriteTime(void)const __ptr64` | 32 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::IsValidLastAccessTime(void)const __ptr64` | 31 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::IsValidCreationTime(void)const __ptr64` | 30 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::QueryCreationTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 35 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::QueryName(class WSTRING * __ptr64)const __ptr64` | 43 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::QueryLastWriteTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 40 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::QueryLastAccessTime(union _LARGE_INTEGER * __ptr64)const __ptr64` | 39 | Exported Function
`public: unsigned char __cdecl CLUSTER_CHAIN::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 22 | Exported Function
`public: struct _EA * __ptr64 __cdecl EA_SET::GetEa(unsigned long,long * __ptr64,unsigned char * __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl ROOTDIR::ROOTDIR(void) __ptr64` | 8 | Exported Function
`public: unsigned char __cdecl EA_HEADER::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 23 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::Initialize(void * __ptr64,unsigned char) __ptr64` | 26 | Exported Function
`public: unsigned char __cdecl FAT_DIRENT::Initialize(void * __ptr64) __ptr64` | 25 | Exported Function
`public: unsigned char __cdecl EA_SET::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class FAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long) __ptr64` | 24 | Exported Function


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


