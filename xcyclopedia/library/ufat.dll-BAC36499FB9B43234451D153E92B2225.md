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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 51 (0x33) | Exported Function | 0x44903390 | 0x00003390
`public: unsigned char __thiscall FILEDIR::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long)` | 27 (0x1b) | Exported Function | 0x44913660 | 0x00013660
`public: unsigned char __thiscall REAL_FAT_SA::InitFATChkDirty(class LOG_IO_DP_DRIVE *,class MESSAGE *)` | 21 (0x15) | Exported Function | 0x44913ed0 | 0x00013ed0
`public: unsigned char __thiscall ROOTDIR::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,unsigned long,long)` | 29 (0x1d) | Exported Function | 0x44918740 | 0x00018740
`public: unsigned long __thiscall FAT::AllocChain(unsigned long,unsigned long *)` | 17 (0x11) | Exported Function | 0x449062a0 | 0x000062a0
`public: unsigned long __thiscall FAT::QueryAllocatedClusters(void)const ` | 33 (0x21) | Exported Function | 0x44905f40 | 0x00005f40
`public: unsigned long __thiscall FAT::QueryLengthOfChain(unsigned long,unsigned long *)const ` | 41 (0x29) | Exported Function | 0x44905fd0 | 0x00005fd0
`public: unsigned long __thiscall FAT::QueryNthCluster(unsigned long,unsigned long)const ` | 44 (0x2c) | Exported Function | 0x44905f90 | 0x00005f90
`public: unsigned long __thiscall FAT_SA::QueryFileStartingCluster(class WSTRING const *,class HMEM *,class FATDIR * *,unsigned char *,class FAT_DIRENT *)` | 37 (0x25) | Exported Function | 0x449077f0 | 0x000077f0
`public: unsigned long __thiscall REAL_FAT_SA::QueryFreeSectors(void)const ` | 38 (0x26) | Exported Function | 0x44917b20 | 0x00017b20
`public: unsigned short __thiscall EA_HEADER::QueryEaSetClusterNumber(unsigned short)const ` | 36 (0x24) | Exported Function | 0x44902d50 | 0x00002d50
`public: virtual __thiscall CLUSTER_CHAIN::~CLUSTER_CHAIN(void)` | 9 (0x9) | Exported Function | 0x449026c0 | 0x000026c0
`public: unsigned char __thiscall FATDIR::QueryLongName(long,class WSTRING *)` | 42 (0x2a) | Exported Function | 0x44907200 | 0x00007200
`public: virtual __thiscall EA_HEADER::~EA_HEADER(void)` | 10 (0xa) | Exported Function | 0x44902bd0 | 0x00002bd0
`public: virtual __thiscall FAT_DIRENT::~FAT_DIRENT(void)` | 12 (0xc) | Exported Function | 0x44906540 | 0x00006540
`public: virtual __thiscall FAT_SA::~FAT_SA(void)` | 13 (0xd) | Exported Function | 0x449073a0 | 0x000073a0
`public: virtual __thiscall FILEDIR::~FILEDIR(void)` | 14 (0xe) | Exported Function | 0x44913630 | 0x00013630
`public: virtual __thiscall REAL_FAT_SA::~REAL_FAT_SA(void)` | 15 (0xf) | Exported Function | 0x449139f0 | 0x000139f0
`public: virtual __thiscall ROOTDIR::~ROOTDIR(void)` | 16 (0x10) | Exported Function | 0x44918710 | 0x00018710
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Read(void)` | 45 (0x2d) | Exported Function | 0x44902990 | 0x00002990
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Write(void)` | 50 (0x32) | Exported Function | 0x44902a10 | 0x00002a10
`public: virtual unsigned char __thiscall EA_SET::Read(void)` | 46 (0x2e) | Exported Function | 0x44902fd0 | 0x00002fd0
`public: virtual unsigned char __thiscall REAL_FAT_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *,unsigned char)` | 28 (0x1c) | Exported Function | 0x44913a30 | 0x00013a30
`public: virtual unsigned char __thiscall REAL_FAT_SA::Read(class MESSAGE *)` | 47 (0x2f) | Exported Function | 0x44916b00 | 0x00016b00
`public: void * __thiscall FATDIR::SearchForDirEntry(class WSTRING const *)` | 48 (0x30) | Exported Function | 0x449070a0 | 0x000070a0
`public: virtual __thiscall EA_SET::~EA_SET(void)` | 11 (0xb) | Exported Function | 0x44902e50 | 0x00002e50
`public: unsigned char __thiscall FAT_SA::QueryCensusAndRelocate(struct _CENSUS_REPORT *,class INTSTACK *,unsigned char *)` | 34 (0x22) | Exported Function | 0x449124c0 | 0x000124c0
`public: unsigned char __thiscall FAT_DIRENT::QueryName(class WSTRING *)const ` | 43 (0x2b) | Exported Function | 0x449065a0 | 0x000065a0
`public: unsigned char __thiscall FAT_DIRENT::QueryLastWriteTime(union _LARGE_INTEGER *)const ` | 40 (0x28) | Exported Function | 0x44906aa0 | 0x00006aa0
`ChkdskEx` | 52 (0x34) | Exported Function | 0x44903c80 | 0x00003c80
`Format` | 53 (0x35) | Exported Function | 0x44904a00 | 0x00004a00
`FormatEx` | 54 (0x36) | Exported Function | 0x44905350 | 0x00005350
`GetFilesystemInformation` | 55 (0x37) | Exported Function | 0x44904e80 | 0x00004e80
`private: unsigned long __thiscall FAT::Index12(unsigned long)const ` | 20 (0x14) | Exported Function | 0x44905e70 | 0x00005e70
`private: void __thiscall FAT::Set12(unsigned long,unsigned long)` | 49 (0x31) | Exported Function | 0x44905eb0 | 0x00005eb0
`public: __thiscall CLUSTER_CHAIN::CLUSTER_CHAIN(void)` | 1 (0x1) | Exported Function | 0x44902670 | 0x00002670
`public: __thiscall EA_HEADER::EA_HEADER(void)` | 2 (0x2) | Exported Function | 0x44902ba0 | 0x00002ba0
`public: __thiscall EA_SET::EA_SET(void)` | 3 (0x3) | Exported Function | 0x44902e10 | 0x00002e10
`public: __thiscall FAT_DIRENT::FAT_DIRENT(void)` | 4 (0x4) | Exported Function | 0x44906510 | 0x00006510
`public: __thiscall FAT_SA::FAT_SA(void)` | 5 (0x5) | Exported Function | 0x44907370 | 0x00007370
`public: __thiscall FILEDIR::FILEDIR(void)` | 6 (0x6) | Exported Function | 0x449135f0 | 0x000135f0
`public: __thiscall REAL_FAT_SA::REAL_FAT_SA(void)` | 7 (0x7) | Exported Function | 0x44913810 | 0x00013810
`public: __thiscall ROOTDIR::ROOTDIR(void)` | 8 (0x8) | Exported Function | 0x449186d0 | 0x000186d0
`public: struct _EA * __thiscall EA_SET::GetEa(unsigned long,long *,unsigned char *)` | 19 (0x13) | Exported Function | 0x44903010 | 0x00003010
`public: unsigned char __thiscall CLUSTER_CHAIN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 22 (0x16) | Exported Function | 0x449026f0 | 0x000026f0
`public: unsigned char __thiscall EA_HEADER::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 23 (0x17) | Exported Function | 0x44902bf0 | 0x00002bf0
`public: unsigned char __thiscall EA_SET::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class FAT_SA *,class FAT const *,unsigned long,unsigned long)` | 24 (0x18) | Exported Function | 0x44902e80 | 0x00002e80
`public: unsigned char __thiscall FAT_DIRENT::Initialize(void *)` | 25 (0x19) | Exported Function | 0x44906560 | 0x00006560
`public: unsigned char __thiscall FAT_DIRENT::Initialize(void *,unsigned char)` | 26 (0x1a) | Exported Function | 0x44906580 | 0x00006580
`public: unsigned char __thiscall FAT_DIRENT::IsValidCreationTime(void)const ` | 30 (0x1e) | Exported Function | 0x44906bc0 | 0x00006bc0
`public: unsigned char __thiscall FAT_DIRENT::IsValidLastAccessTime(void)const ` | 31 (0x1f) | Exported Function | 0x44906d40 | 0x00006d40
`public: unsigned char __thiscall FAT_DIRENT::IsValidLastWriteTime(void)const ` | 32 (0x20) | Exported Function | 0x44906a80 | 0x00006a80
`public: unsigned char __thiscall FAT_DIRENT::QueryCreationTime(union _LARGE_INTEGER *)const ` | 35 (0x23) | Exported Function | 0x44906be0 | 0x00006be0
`public: unsigned char __thiscall FAT_DIRENT::QueryLastAccessTime(union _LARGE_INTEGER *)const ` | 39 (0x27) | Exported Function | 0x44906d60 | 0x00006d60
`public: void __thiscall FAT::FreeChain(unsigned long)` | 18 (0x12) | Exported Function | 0x44906430 | 0x00006430
`Recover` | 56 (0x38) | Exported Function | 0x44905910 | 0x00005910


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


