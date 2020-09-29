---
title: dataclen.dll | Disk Space Cleaner for Windows
excerpt: What is dataclen.dll?
---

# dataclen.dll 

* File Path: `C:\Windows\system32\dataclen.dll`
* Description: Disk Space Cleaner for Windows

## Hashes

Type | Hash
-- | --
MD5 | `E241E854379C5A81D966A8726638C663`
SHA1 | `B28A9928CD194848F517D8404A174763C1380F09`
SHA256 | `DE282E8AA88E772A50C6C8AF759DBD5A3CFAAF9A83ABA4955ED39A01182AF500`
SHA384 | `80DD4B71786AEC60B3CA53D970DD1BDBF1CCEC10B75FB426F04FAE78C491A06925683CDBB320C9341A05F4BA4E8F4BAE`
SHA512 | `1913B977613F488DE1812A8B75A764D3757620D2F0F17BC2A5088C4B7793521A4054C13369014F78B42BD6E8CCA57C58593466496EC37B6DF2E3F47AECEA1359`
SSDEEP | `768:RIkDzzB4AKbFYnY1x+/7Tjn9+GXOTZVt7hlsHmy2vSWHKZCQWk9DQbH3Ja:2m4AKxKY1xu7TfOFVZ4GTp4CQWOm3Ja`
IMP | `717AD49CA307335844DEA3F8309C8065`
PESHA1 | `D14A10FFFEB5284AA7C11685307F1F3DCC7FE513`
PE256 | `45DCD11DFA3ABA3EFFB4AD582013EB28C4A7D56DC7C0959CC51D4CA137946B79`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CDataDrivenCleaner::``vftable'` | 5 (0x5) | Exported Function | 0x00000001800080f8 | 0x000080f8
`public: virtual long __cdecl CDataDrivenCleaner::ShowProperties(struct HWND__ * __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180004e20 | 0x00004e20
`public: virtual long __cdecl CDataDrivenCleaner::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180004470 | 0x00004470
`public: virtual long __cdecl CDataDrivenCleaner::Purge(unsigned __int64,struct IEmptyVolumeCacheCallBack * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180004b40 | 0x00004b40
`public: virtual long __cdecl CDataDrivenCleaner::Initialize(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x00000001800044d0 | 0x000044d0
`public: virtual long __cdecl CDataDrivenCleaner::GetSpaceUsed(unsigned __int64 * __ptr64,struct IEmptyVolumeCacheCallBack * __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180004a40 | 0x00004a40
`public: virtual long __cdecl CDataDrivenCleaner::Deactivate(unsigned long * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180004e30 | 0x00004e30
`public: int __cdecl CDataDrivenCleaner::AddFolders(unsigned short const * __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x00000001800059c0 | 0x000059c0
`public: class CDataDrivenCleaner & __ptr64 __cdecl CDataDrivenCleaner::operator=(class CDataDrivenCleaner const & __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180003e50 | 0x00003e50
`public: __cdecl CDataDrivenCleaner::~CDataDrivenCleaner(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180004410 | 0x00004410
`public: virtual unsigned long __cdecl CDataDrivenCleaner::AddRef(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180004160 | 0x00004160
`public: __cdecl CDataDrivenCleaner::CDataDrivenCleaner(void) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800043b0 | 0x000043b0
`protected: void __cdecl CDataDrivenCleaner::PurgeFiles(struct IEmptyVolumeCacheCallBack * __ptr64,unsigned __int64) __ptr64` | 17 (0x11) | Exported Function | 0x00000001800056f0 | 0x000056f0
`protected: void __cdecl CDataDrivenCleaner::FreeList(struct tag_CleanFileStruct * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180005970 | 0x00005970
`protected: void __cdecl CDataDrivenCleaner::ExecuteCmd(unsigned short * __ptr64,int) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180004d40 | 0x00004d40
`protected: struct tag_CleanFileStruct * __ptr64 __cdecl CDataDrivenCleaner::MergeSortList(struct tag_CleanFileStruct * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180005870 | 0x00005870
`protected: int __cdecl CDataDrivenCleaner::WalkForUsedSpace(unsigned short const * __ptr64,struct IEmptyVolumeCacheCallBack * __ptr64,int) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180004eb0 | 0x00004eb0
`protected: int __cdecl CDataDrivenCleaner::LastAccessisOK(struct _FILETIME) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180004e60 | 0x00004e60
`protected: int __cdecl CDataDrivenCleaner::AddFileToList(unsigned short const * __ptr64,union _ULARGE_INTEGER,struct _FILETIME,int,int) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180005570 | 0x00005570
`DllGetClassObject` | 23 (0x17) | Exported Function | 0x0000000180003f50 | 0x00003f50
`DllCanUnloadNow` | 22 (0x16) | Exported Function | 0x0000000180004120 | 0x00004120
`public: __cdecl CDataDrivenCleaner::CDataDrivenCleaner(class CDataDrivenCleaner const & __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180003c30 | 0x00003c30
`public: virtual unsigned long __cdecl CDataDrivenCleaner::Release(void) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180004490 | 0x00004490


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DATACLEN.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/de282e8aa88e772a50c6c8af759dbd5a3cfaaf9a83aba4955ed39a01182af500/detection/


## Possible Misuse

*The following table contains possible examples of `dataclen.dll` being misused. While `dataclen.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.dataclen.org` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


