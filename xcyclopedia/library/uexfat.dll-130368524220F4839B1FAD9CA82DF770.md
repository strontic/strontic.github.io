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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 12 (0xc) | Exported Function | 0x100037c0 | 0x000037c0
`public: unsigned char __thiscall EXFAT_SA::Initialize(class LOG_IO_DP_DRIVE *,class MESSAGE *)` | 21 (0x15) | Exported Function | 0x10005300 | 0x00005300
`public: unsigned char __thiscall EXFATDIR::Initialize(class HMEM *,class LOG_IO_DP_DRIVE *,class EXFAT_SA *,class FAT const *,unsigned long,unsigned __int64,unsigned char)` | 19 (0x13) | Exported Function | 0x1000f1d0 | 0x0000f1d0
`public: unsigned long __thiscall EXFAT_DIRENT::QueryStartingCluster(void)` | 27 (0x1b) | Exported Function | 0x1000fc50 | 0x0000fc50
`public: unsigned long __thiscall FAT::AllocChain(class EXFATBITMAP *,unsigned long,unsigned long *)` | 11 (0xb) | Exported Function | 0x100124e0 | 0x000124e0
`public: unsigned long __thiscall FAT::QueryAllocatedClusters(void)const ` | 23 (0x17) | Exported Function | 0x100122f0 | 0x000122f0
`public: unsigned long __thiscall FAT::QueryLengthOfChain(unsigned long,unsigned long *)const ` | 25 (0x19) | Exported Function | 0x10012360 | 0x00012360
`public: unsigned char __thiscall EXFAT_DIRENT::VerifyAndFixPhase2(class EXFATBITMAP *,class EXFATBITMAP *,class WSTRING *,unsigned char,unsigned char,unsigned char,enum FIX_LEVEL,unsigned char *,class MESSAGE *)` | 33 (0x21) | Exported Function | 0x10011060 | 0x00011060
`public: unsigned long __thiscall FAT::QueryNthCluster(unsigned long,unsigned long)const ` | 26 (0x1a) | Exported Function | 0x10012320 | 0x00012320
`public: virtual __thiscall EXFAT_DIRENT::~EXFAT_DIRENT(void)` | 8 (0x8) | Exported Function | 0x1000fb90 | 0x0000fb90
`public: virtual __thiscall EXFAT_SA::~EXFAT_SA(void)` | 9 (0x9) | Exported Function | 0x10005280 | 0x00005280
`public: virtual __thiscall EXFAT_VOL::~EXFAT_VOL(void)` | 10 (0xa) | Exported Function | 0x100048a0 | 0x000048a0
`public: virtual __thiscall EXFATDIR::~EXFATDIR(void)` | 7 (0x7) | Exported Function | 0x1000f1a0 | 0x0000f1a0
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Read(void)` | 28 (0x1c) | Exported Function | 0x10011d70 | 0x00011d70
`public: virtual unsigned char __thiscall CLUSTER_CHAIN::Write(void)` | 34 (0x22) | Exported Function | 0x10011f70 | 0x00011f70
`public: virtual __thiscall CLUSTER_CHAIN::~CLUSTER_CHAIN(void)` | 6 (0x6) | Exported Function | 0x10011aa0 | 0x00011aa0
`public: void __thiscall FAT::FreeChain(class EXFATBITMAP *,unsigned long)` | 16 (0x10) | Exported Function | 0x100126c0 | 0x000126c0
`public: unsigned char __thiscall EXFAT_DIRENT::SetStartingCluster(unsigned long)` | 32 (0x20) | Exported Function | 0x1000fc60 | 0x0000fc60
`public: unsigned char __thiscall EXFAT_DIRENT::Initialize(class EXFAT_SA *,void *,class EXFATDIR *,unsigned long)` | 20 (0x14) | Exported Function | 0x1000fbb0 | 0x0000fbb0
`ChkdskEx` | 13 (0xd) | Exported Function | 0x10003900 | 0x00003900
`Format` | 14 (0xe) | Exported Function | 0x10003f90 | 0x00003f90
`FormatEx` | 15 (0xf) | Exported Function | 0x100043f0 | 0x000043f0
`GetFilesystemInformation` | 17 (0x11) | Exported Function | 0x10004170 | 0x00004170
`public: __int64 __thiscall EXFAT_DIRENT::QueryFileSize(void)` | 24 (0x18) | Exported Function | 0x1000fc80 | 0x0000fc80
`public: __thiscall CLUSTER_CHAIN::CLUSTER_CHAIN(void)` | 1 (0x1) | Exported Function | 0x10011a60 | 0x00011a60
`public: unsigned char __thiscall EXFAT_DIRENT::SetFileSize(__int64)` | 31 (0x1f) | Exported Function | 0x1000fc90 | 0x0000fc90
`public: __thiscall EXFAT_DIRENT::EXFAT_DIRENT(void)` | 3 (0x3) | Exported Function | 0x1000fb60 | 0x0000fb60
`public: __thiscall EXFAT_VOL::EXFAT_VOL(void)` | 5 (0x5) | Exported Function | 0x10004870 | 0x00004870
`public: __thiscall EXFATDIR::EXFATDIR(void)` | 2 (0x2) | Exported Function | 0x1000f160 | 0x0000f160
`public: enum FORMAT_ERROR_CODE __thiscall EXFAT_VOL::Initialize(class WSTRING const *,class MESSAGE *,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned char,unsigned char)` | 22 (0x16) | Exported Function | 0x100048d0 | 0x000048d0
`public: unsigned char __thiscall CLUSTER_CHAIN::Initialize(class MEM *,class LOG_IO_DP_DRIVE *,class EXFAT_SA *,class FAT const *,unsigned long,unsigned long,unsigned char)` | 18 (0x12) | Exported Function | 0x10011ac0 | 0x00011ac0
`public: unsigned char __thiscall CLUSTER_CHAIN::ReadAndRecordBadSectors(class EXFATSECRUNBITMAP *)` | 29 (0x1d) | Exported Function | 0x10011de0 | 0x00011de0
`public: unsigned char __thiscall CLUSTER_CHAIN::WriteAndSkipBadSectors(void)` | 35 (0x23) | Exported Function | 0x10011fe0 | 0x00011fe0
`public: __thiscall EXFAT_SA::EXFAT_SA(void)` | 4 (0x4) | Exported Function | 0x100051c0 | 0x000051c0
`Recover` | 30 (0x1e) | Exported Function | 0x10004720 | 0x00004720


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


