---
title: ufat.dll | FAT Utility DLL
excerpt: What is ufat.dll?
---

# ufat.dll 

* File Path: `C:\Windows\SysWOW64\ufat.dll`
* Description: FAT Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `BAC36499FB9B43234451D153E92B2225`
SHA1 | `7EC755BB5B2506EC5961EC422FCC54784B80D8AB`
SHA256 | `7B700C241115C71D272B277A8A343CC3F599C4A5F14BC0FFB7E6A84724AB7157`
SHA384 | `AE0A1A2AA0F9D382EA8E62906FFC939C57421A2584D19CADAF68BF4A4DA4F0AB9E1C5A14875397E17A0182B34FC04893`
SHA512 | `9031D3ED9A4D0DBDB960944699D780C83EEB2DC2564A5E1FE0A3C870AFBD95B082D1B9321FBF51A56BEE095D4C256E95B6D20336CFFD748AC60E34AAFF9DC99E`
SSDEEP | `3072:gJuqxZsI4PJngproaBJVVf5wukDcFRBURFm/r32fnHcz2jzwznjYG:tCuI4P5gproaBJVVfmukoFRBURIE`
IMP | `F456ED43752F0E9D0D1047A050F8C112`
PESHA1 | `A96D356BE2FBA001BB98724FAAA8C317290D52A0`
PE256 | `FB8B8AC55A404213B8B39385977A6453B1B0BE0B2C2C97040435BA5EC77C05F0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned long __thiscall FAT_SA::QueryFileStartingCluster(class WSTRING const *,class HMEM *,class FATDIR * *,unsigned char *,class FAT_DIRENT *)` | 37 | Exported Function
`public: unsigned long __thiscall FAT::QueryNthCluster(unsigned long,unsigned long)const ` | 44 | Exported Function
`public: unsigned long __thiscall FAT::QueryLengthOfChain(unsigned long,unsigned long *)const ` | 41 | Exported Function
`public: unsigned long __thiscall REAL_FAT_SA::QueryFreeSectors(void)const ` | 38 | Exported Function
`public: virtual __thiscall EA_HEADER::~EA_HEADER(void)` | 10 | Exported Function
`public: virtual __thiscall CLUSTER_CHAIN::~CLUSTER_CHAIN(void)` | 9 | Exported Function
`public: unsigned short __thiscall EA_HEADER::QueryEaSetClusterNumber(unsigned short)const ` | 36 | Exported Function
`public: unsigned char __thiscall FILEDIR::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long)` | 27 | Exported Function
`public: unsigned char __thiscall FATDIR::QueryLongName(long,class WSTRING *)` | 42 | Exported Function
`public: unsigned char __thiscall FAT_SA::QueryCensusAndRelocate(struct _CENSUS_REPORT *,class INTSTACK *,unsigned char *)` | 34 | Exported Function
`public: unsigned char __thiscall REAL_FAT_SA::InitFATChkDirty(class LOG_IO_DP_DRIVE *,class MESSAGE *)` | 21 | Exported Function
`public: unsigned long __thiscall FAT::QueryAllocatedClusters(void)const ` | 33 | Exported Function
`public: unsigned long __thiscall FAT::AllocChain(unsigned long,unsigned long *)` | 17 | Exported Function
`public: unsigned char __thiscall ROOTDIR::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,unsigned long,long)` | 29 | Exported Function
`public: virtual unsigned char __thiscall REAL_FAT_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *,unsigned char)` | 28 | Exported Function
`public: virtual unsigned char __thiscall EA_SET::Read(void)` | 46 | Exported Function
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Write(void)` | 50 | Exported Function
`public: virtual unsigned char __thiscall REAL_FAT_SA::Read(class MESSAGE *)` | 47 | Exported Function
`Recover` | 56 | Exported Function
`public: void __thiscall FAT::FreeChain(unsigned long)` | 18 | Exported Function
`public: void * __thiscall FATDIR::SearchForDirEntry(class WSTRING const *)` | 48 | Exported Function
`public: virtual __thiscall FAT_SA::~FAT_SA(void)` | 13 | Exported Function
`public: virtual __thiscall FAT_DIRENT::~FAT_DIRENT(void)` | 12 | Exported Function
`public: virtual __thiscall EA_SET::~EA_SET(void)` | 11 | Exported Function
`public: virtual __thiscall FILEDIR::~FILEDIR(void)` | 14 | Exported Function
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Read(void)` | 45 | Exported Function
`public: virtual __thiscall ROOTDIR::~ROOTDIR(void)` | 16 | Exported Function
`public: virtual __thiscall REAL_FAT_SA::~REAL_FAT_SA(void)` | 15 | Exported Function
`public: __thiscall EA_SET::EA_SET(void)` | 3 | Exported Function
`public: __thiscall EA_HEADER::EA_HEADER(void)` | 2 | Exported Function
`public: __thiscall CLUSTER_CHAIN::CLUSTER_CHAIN(void)` | 1 | Exported Function
`public: __thiscall FAT_DIRENT::FAT_DIRENT(void)` | 4 | Exported Function
`public: __thiscall REAL_FAT_SA::REAL_FAT_SA(void)` | 7 | Exported Function
`public: __thiscall FILEDIR::FILEDIR(void)` | 6 | Exported Function
`public: __thiscall FAT_SA::FAT_SA(void)` | 5 | Exported Function
`Format` | 53 | Exported Function
`ChkdskEx` | 52 | Exported Function
`Chkdsk` | 51 | Exported Function
`FormatEx` | 54 | Exported Function
`private: void __thiscall FAT::Set12(unsigned long,unsigned long)` | 49 | Exported Function
`private: unsigned long __thiscall FAT::Index12(unsigned long)const ` | 20 | Exported Function
`GetFilesystemInformation` | 55 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::IsValidLastWriteTime(void)const ` | 32 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::IsValidLastAccessTime(void)const ` | 31 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::IsValidCreationTime(void)const ` | 30 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::QueryCreationTime(union _LARGE_INTEGER *)const ` | 35 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::QueryName(class WSTRING *)const ` | 43 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::QueryLastWriteTime(union _LARGE_INTEGER *)const ` | 40 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::QueryLastAccessTime(union _LARGE_INTEGER *)const ` | 39 | Exported Function
`public: unsigned char __thiscall CLUSTER_CHAIN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 22 | Exported Function
`public: struct _EA * __thiscall EA_SET::GetEa(unsigned long,long *,unsigned char *)` | 19 | Exported Function
`public: __thiscall ROOTDIR::ROOTDIR(void)` | 8 | Exported Function
`public: unsigned char __thiscall EA_HEADER::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 23 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::Initialize(void *,unsigned char)` | 26 | Exported Function
`public: unsigned char __thiscall FAT_DIRENT::Initialize(void *)` | 25 | Exported Function
`public: unsigned char __thiscall EA_SET::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 24 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7b700c241115c71d272b277a8a343cc3f599c4a5f14bc0ffb7e6a84724ab7157/detection/





MIT License. Copyright (c) 2020 Strontic.


