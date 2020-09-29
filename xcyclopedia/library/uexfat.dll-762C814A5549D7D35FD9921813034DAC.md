---
title: uexfat.dll | eXfat Utility DLL
excerpt: What is uexfat.dll?
---

# uexfat.dll 

* File Path: `C:\Windows\system32\uexfat.dll`
* Description: eXfat Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `762C814A5549D7D35FD9921813034DAC`
SHA1 | `ECB80E9C5C17B2FA19FD92F8D9CF9168E65DD9F6`
SHA256 | `4D7BA5F8BD7AED196B07EA2317840DD1E687D97C2E0E8518E121FC17532FA7B3`
SHA384 | `21F962F5AD420FED92C616311AE0BEA2A65068321BA4D5ECE2351BB58C504F4E78F3582E709A89FA907417CB53128A48`
SHA512 | `6F62ABBF5764AF5BF0945134695B79033D9BA47F0E7A08EB51FCFA4652FA33FFA0D823EFD00098FAE1F09E7640D182C992DA932B4AABE650A1B587ACF9C7E947`
SSDEEP | `1536:S7e77Jt1u3we8lANeMcAibkAjqhPl46TywcQSKOIhy4rS/QZcSOJHHTgaAvXZznk:SK8NNqkHX4oy38z+QEHMaopznUdSPw`
IMP | `517EA161AD3D95BEE87BCC469981C362`
PESHA1 | `B4BE1D43E112F30DC1F82695A437CAA0AF633FCF`
PE256 | `9941940A7D2AF0F92AB2024D261A2A34BFA9EA57173F71CB5ADFA4CACAEAA6A6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`Chkdsk` | 12 (0xc) | Exported Function | 0x0000000180001460 | 0x00001460
`public: unsigned char __cdecl EXFAT_SA::Initialize(class LOG_IO_DP_DRIVE * __ptr64,class MESSAGE * __ptr64) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180003640 | 0x00003640
`public: unsigned char __cdecl EXFATDIR::Initialize(class HMEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class EXFAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned __int64,unsigned char) __ptr64` | 19 (0x13) | Exported Function | 0x000000018000f620 | 0x0000f620
`public: unsigned long __cdecl EXFAT_DIRENT::QueryStartingCluster(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180010480 | 0x00010480
`public: unsigned long __cdecl FAT::AllocChain(class EXFATBITMAP * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180013770 | 0x00013770
`public: unsigned long __cdecl FAT::QueryAllocatedClusters(void)const __ptr64` | 23 (0x17) | Exported Function | 0x00000001800134d0 | 0x000134d0
`public: unsigned long __cdecl FAT::QueryLengthOfChain(unsigned long,unsigned long * __ptr64)const __ptr64` | 25 (0x19) | Exported Function | 0x0000000180013540 | 0x00013540
`public: unsigned char __cdecl EXFAT_DIRENT::VerifyAndFixPhase2(class EXFATBITMAP * __ptr64,class EXFATBITMAP * __ptr64,class WSTRING * __ptr64,unsigned char,unsigned char,unsigned char,enum FIX_LEVEL,unsigned char * __ptr64,class MESSAGE * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180011c00 | 0x00011c00
`public: unsigned long __cdecl FAT::QueryNthCluster(unsigned long,unsigned long)const __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180013510 | 0x00013510
`public: virtual __cdecl EXFAT_DIRENT::~EXFAT_DIRENT(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180010390 | 0x00010390
`public: virtual __cdecl EXFAT_SA::~EXFAT_SA(void) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180003560 | 0x00003560
`public: virtual __cdecl EXFAT_VOL::~EXFAT_VOL(void) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800028e0 | 0x000028e0
`public: virtual __cdecl EXFATDIR::~EXFATDIR(void) __ptr64` | 7 (0x7) | Exported Function | 0x000000018000f5e0 | 0x0000f5e0
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Read(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180012d20 | 0x00012d20
`public: virtual unsigned char __cdecl CLUSTER_CHAIN::Write(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180012fa0 | 0x00012fa0
`public: virtual __cdecl CLUSTER_CHAIN::~CLUSTER_CHAIN(void) __ptr64` | 6 (0x6) | Exported Function | 0x00000001800129d0 | 0x000129d0
`public: void __cdecl FAT::FreeChain(class EXFATBITMAP * __ptr64,unsigned long) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180013a30 | 0x00013a30
`public: unsigned char __cdecl EXFAT_DIRENT::SetStartingCluster(unsigned long) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180010490 | 0x00010490
`public: unsigned char __cdecl EXFAT_DIRENT::Initialize(class EXFAT_SA * __ptr64,void * __ptr64,class EXFATDIR * __ptr64,unsigned long) __ptr64` | 20 (0x14) | Exported Function | 0x00000001800103c0 | 0x000103c0
`ChkdskEx` | 13 (0xd) | Exported Function | 0x0000000180001610 | 0x00001610
`Format` | 14 (0xe) | Exported Function | 0x0000000180001d60 | 0x00001d60
`FormatEx` | 15 (0xf) | Exported Function | 0x00000001800022a0 | 0x000022a0
`GetFilesystemInformation` | 17 (0x11) | Exported Function | 0x0000000180001fc0 | 0x00001fc0
`public: __cdecl CLUSTER_CHAIN::CLUSTER_CHAIN(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180012970 | 0x00012970
`public: __cdecl EXFAT_DIRENT::EXFAT_DIRENT(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180010350 | 0x00010350
`public: unsigned char __cdecl EXFAT_DIRENT::SetFileSize(__int64) __ptr64` | 31 (0x1f) | Exported Function | 0x00000001800104c0 | 0x000104c0
`public: __cdecl EXFAT_SA::EXFAT_SA(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180003460 | 0x00003460
`public: __cdecl EXFATDIR::EXFATDIR(void) __ptr64` | 2 (0x2) | Exported Function | 0x000000018000f580 | 0x0000f580
`public: __int64 __cdecl EXFAT_DIRENT::QueryFileSize(void) __ptr64` | 24 (0x18) | Exported Function | 0x00000001800104b0 | 0x000104b0
`public: enum FORMAT_ERROR_CODE __cdecl EXFAT_VOL::Initialize(class WSTRING const * __ptr64,class MESSAGE * __ptr64,unsigned char,unsigned char,enum _MEDIA_TYPE,unsigned char,unsigned char) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180002920 | 0x00002920
`public: unsigned char __cdecl CLUSTER_CHAIN::Initialize(class MEM * __ptr64,class LOG_IO_DP_DRIVE * __ptr64,class EXFAT_SA * __ptr64,class FAT const * __ptr64,unsigned long,unsigned long,unsigned char) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180012a10 | 0x00012a10
`public: unsigned char __cdecl CLUSTER_CHAIN::ReadAndRecordBadSectors(class EXFATSECRUNBITMAP * __ptr64) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180012da0 | 0x00012da0
`public: unsigned char __cdecl CLUSTER_CHAIN::WriteAndSkipBadSectors(void) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180013020 | 0x00013020
`public: __cdecl EXFAT_VOL::EXFAT_VOL(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180002890 | 0x00002890
`Recover` | 30 (0x1e) | Exported Function | 0x0000000180002660 | 0x00002660


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/4d7ba5f8bd7aed196b07ea2317840dd1e687d97c2e0e8518e121fc17532fa7b3/detection/





MIT License. Copyright (c) 2020 Strontic.


