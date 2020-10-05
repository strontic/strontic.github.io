---
title: uexfat.dll | eXfat Utility DLL
excerpt: What is uexfat.dll?
---

# uexfat.dll 

* File Path: `C:\Windows\SysWOW64\uexfat.dll`
* Description: eXfat Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `130368524220F4839B1FAD9CA82DF770`
SHA1 | `ADD890C0154D258CDDB837056E54DA4D389DB153`
SHA256 | `745F587300052B4BD6D8A97DDCEBE7A0B3D99C3FC3D6534E664C1D7934FF0925`
SHA384 | `9089F3B1074D81DC4B2651504413EFC3C9A239BAC5E83B48122F910908FED6E7E29A12BC65178528B40D6F73A2FC753F`
SHA512 | `2F5AED775D1EDCB0ACE99C74604D103589C31A6516D3C0DAB8EBAFFD8529D69860DC31D275FB700488E8F526A74C27F3E1E2108F426CAE4FCBB23CAFB9E722BA`
SSDEEP | `1536:ATgauNe3Q6i8ixBhvj7DiFbq7xrkCt+0+YGPeIfY39lQvUA5iCbZo:AMaQe3Q68ja/PeIQ4vd5iCbm`
IMP | `C883999F4BF58E3F3E8E9E116D1DD80F`
PESHA1 | `5B924EA0706527A56900CB9578CF1E69B7A3EF12`
PE256 | `1F89707AC80717D5AFF690FC8565EE639B63FB147A22961F51CB83E5AD4882CD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned long __thiscall FAT::QueryAllocatedClusters(void)const ` | 23 | Exported Function
`public: unsigned long __thiscall FAT::AllocChain(class EXFATBITMAP *,unsigned long,unsigned long *)` | 11 | Exported Function
`public: unsigned long __thiscall FAT::QueryNthCluster(unsigned long,unsigned long)const ` | 26 | Exported Function
`public: unsigned long __thiscall FAT::QueryLengthOfChain(unsigned long,unsigned long *)const ` | 25 | Exported Function
`public: unsigned char __thiscall EXFAT_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *)` | 21 | Exported Function
`public: unsigned char __thiscall EXFAT_DIRENT::VerifyAndFixPhase2(class EXFATBITMAP *,class EXFATBITMAP *,class WSTRING *,unsigned char,unsigned char,unsigned char,enum FIX_LEVEL,unsigned char *,class MESSAGE *)` | 33 | Exported Function
`public: unsigned long __thiscall EXFAT_DIRENT::QueryStartingCluster(void)` | 27 | Exported Function
`public: unsigned char __thiscall EXFATDIR::Initialize(class HMEM *,class LOG_IO_DP_DRIVE *,class EXFAT_SA *,class FAT const *,unsigned long,unsigned __int64,unsigned char)` | 19 | Exported Function
`public: virtual __thiscall CLUSTER_CHAIN::~CLUSTER_CHAIN(void)` | 6 | Exported Function
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Write(void)` | 34 | Exported Function
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Read(void)` | 28 | Exported Function
`Recover` | 30 | Exported Function
`public: void __thiscall FAT::FreeChain(class EXFATBITMAP *,unsigned long)` | 16 | Exported Function
`public: virtual __thiscall EXFAT_SA::~EXFAT_SA(void)` | 9 | Exported Function
`public: virtual __thiscall EXFAT_DIRENT::~EXFAT_DIRENT(void)` | 8 | Exported Function
`public: virtual __thiscall EXFATDIR::~EXFATDIR(void)` | 7 | Exported Function
`public: virtual __thiscall EXFAT_VOL::~EXFAT_VOL(void)` | 10 | Exported Function
`public: unsigned char __thiscall EXFAT_DIRENT::SetStartingCluster(unsigned long)` | 32 | Exported Function
`public: __int64 __thiscall EXFAT_DIRENT::QueryFileSize(void)` | 24 | Exported Function
`GetFilesystemInformation` | 17 | Exported Function
`public: __thiscall EXFAT_DIRENT::EXFAT_DIRENT(void)` | 3 | Exported Function
`public: __thiscall CLUSTER_CHAIN::CLUSTER_CHAIN(void)` | 1 | Exported Function
`ChkdskEx` | 13 | Exported Function
`Chkdsk` | 12 | Exported Function
`FormatEx` | 15 | Exported Function
`Format` | 14 | Exported Function
`public: __thiscall EXFAT_SA::EXFAT_SA(void)` | 4 | Exported Function
`public: unsigned char __thiscall CLUSTER_CHAIN::WriteAndSkipBadSectors(void)` | 35 | Exported Function
`public: unsigned char __thiscall CLUSTER_CHAIN::ReadAndRecordBadSectors(class EXFATSECRUNBITMAP *)` | 29 | Exported Function
`public: unsigned char __thiscall EXFAT_DIRENT::SetFileSize(__int64)` | 31 | Exported Function
`public: unsigned char __thiscall EXFAT_DIRENT::Initialize(class EXFAT_SA *,void *,class EXFATDIR *,unsigned long)` | 20 | Exported Function
`public: __thiscall EXFATDIR::EXFATDIR(void)` | 2 | Exported Function
`public: __thiscall EXFAT_VOL::EXFAT_VOL(void)` | 5 | Exported Function
`public: unsigned char __thiscall CLUSTER_CHAIN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class EXFAT_SA *,class FAT const *,unsigned long,unsigned long,unsigned char)` | 18 | Exported Function
`public: enum FORMAT_ERROR_CODE __thiscall EXFAT_VOL::Initialize(class WSTRING const *,class MESSAGE *,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned char,unsigned char)` | 22 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UEXFAT.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/745f587300052b4bd6d8a97ddcebe7a0b3d99c3fc3d6534e664c1d7934ff0925/detection/





MIT License. Copyright (c) 2020 Strontic.


