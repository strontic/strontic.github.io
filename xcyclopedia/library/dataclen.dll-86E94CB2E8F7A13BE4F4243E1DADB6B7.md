---
title: dataclen.dll | Disk Space Cleaner for Windows
excerpt: What is dataclen.dll?
---

# dataclen.dll 

* File Path: `C:\Windows\SysWOW64\dataclen.dll`
* Description: Disk Space Cleaner for Windows

## Hashes

Type | Hash
-- | --
MD5 | `86E94CB2E8F7A13BE4F4243E1DADB6B7`
SHA1 | `6427177403A174A14E5F3D1A844C3A882D532272`
SHA256 | `B06F6FD07C6D34AA8BD813D445B5252246C915D5DA4B0B7AC50DA9FAE3FB4D4D`
SHA384 | `6968603179D7B66B08890A122CA4FC023C4E3EE1A8E396854C6E8801F5D8FF1F249E177886DD637D953E5ABCA5432EA3`
SHA512 | `B6CE94160E712A4F9530DE358D443C430BF80577641945B599AA1769B412F417D75CFFF09079788F9A402E51F116F1C6614F5EEADBBC2C7601F055BDE56ECF15`
SSDEEP | `768:4259iWPTfvMYLfhPaq6jQVmzP4Dgah959kQ0Exbe3GRY9:b9ZXMuhiq6/gD5L303G69`
IMP | `ACF1486EAEF41DC54D76EDD9510E4B17`
PESHA1 | `366A4AE2FD1A644558D9B28A801C4CCB43D560E7`
PE256 | `DE6351E6292329ED182699A8C97B45ABCA955D15EB177DADFD6E0BA20156FAC5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CDataDrivenCleaner::``vftable'` | 5 (0x5) | Exported Function | 0x1000107c | 0x0000107c
`public: virtual long __stdcall CDataDrivenCleaner::ShowProperties(struct HWND__ *)` | 20 (0x14) | Exported Function | 0x10004930 | 0x00004930
`public: virtual long __stdcall CDataDrivenCleaner::QueryInterface(struct _GUID const &,void * *)` | 18 (0x12) | Exported Function | 0x10004110 | 0x00004110
`public: virtual long __stdcall CDataDrivenCleaner::Purge(unsigned __int64,struct IEmptyVolumeCacheCallBack *)` | 16 (0x10) | Exported Function | 0x10004750 | 0x00004750
`public: virtual long __stdcall CDataDrivenCleaner::Initialize(struct HKEY__ *,unsigned short const *,unsigned short * *,unsigned short * *,unsigned long *)` | 13 (0xd) | Exported Function | 0x10004180 | 0x00004180
`public: virtual long __stdcall CDataDrivenCleaner::GetSpaceUsed(unsigned __int64 *,struct IEmptyVolumeCacheCallBack *)` | 12 (0xc) | Exported Function | 0x10004660 | 0x00004660
`public: virtual long __stdcall CDataDrivenCleaner::Deactivate(unsigned long *)` | 9 (0x9) | Exported Function | 0x10004940 | 0x00004940
`public: int __thiscall CDataDrivenCleaner::AddFolders(unsigned short const *)` | 7 (0x7) | Exported Function | 0x100053f0 | 0x000053f0
`public: class CDataDrivenCleaner & __thiscall CDataDrivenCleaner::operator=(class CDataDrivenCleaner const &)` | 4 (0x4) | Exported Function | 0x10003ba0 | 0x00003ba0
`public: __thiscall CDataDrivenCleaner::~CDataDrivenCleaner(void)` | 3 (0x3) | Exported Function | 0x100040c0 | 0x000040c0
`public: virtual unsigned long __stdcall CDataDrivenCleaner::AddRef(void)` | 8 (0x8) | Exported Function | 0x10003e50 | 0x00003e50
`public: __thiscall CDataDrivenCleaner::CDataDrivenCleaner(void)` | 2 (0x2) | Exported Function | 0x10004070 | 0x00004070
`protected: void __thiscall CDataDrivenCleaner::PurgeFiles(struct IEmptyVolumeCacheCallBack *,unsigned __int64)` | 17 (0x11) | Exported Function | 0x10005180 | 0x00005180
`protected: void __thiscall CDataDrivenCleaner::FreeList(struct tag_CleanFileStruct *)` | 11 (0xb) | Exported Function | 0x100053b0 | 0x000053b0
`protected: void __thiscall CDataDrivenCleaner::ExecuteCmd(unsigned short *,int)` | 10 (0xa) | Exported Function | 0x100048b0 | 0x000048b0
`protected: struct tag_CleanFileStruct * __thiscall CDataDrivenCleaner::MergeSortList(struct tag_CleanFileStruct *)` | 15 (0xf) | Exported Function | 0x100052f0 | 0x000052f0
`protected: int __thiscall CDataDrivenCleaner::WalkForUsedSpace(unsigned short const *,struct IEmptyVolumeCacheCallBack *,int)` | 21 (0x15) | Exported Function | 0x100049c0 | 0x000049c0
`protected: int __thiscall CDataDrivenCleaner::LastAccessisOK(struct _FILETIME)` | 14 (0xe) | Exported Function | 0x10004980 | 0x00004980
`protected: int __thiscall CDataDrivenCleaner::AddFileToList(unsigned short const *,union _ULARGE_INTEGER,struct _FILETIME,int,int)` | 6 (0x6) | Exported Function | 0x10005040 | 0x00005040
`DllGetClassObject` | 23 (0x17) | Exported Function | 0x10003cb0 | 0x00003cb0
`DllCanUnloadNow` | 22 (0x16) | Exported Function | 0x10003e20 | 0x00003e20
`public: __thiscall CDataDrivenCleaner::CDataDrivenCleaner(class CDataDrivenCleaner const &)` | 1 (0x1) | Exported Function | 0x10003ad0 | 0x00003ad0
`public: virtual unsigned long __stdcall CDataDrivenCleaner::Release(void)` | 19 (0x13) | Exported Function | 0x10004140 | 0x00004140


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DATACLEN.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/b06f6fd07c6d34aa8bd813d445b5252246c915d5da4b0b7ac50da9fae3fb4d4d/detection/


## Possible Misuse

*The following table contains possible examples of `dataclen.dll` being misused. While `dataclen.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.dataclen.org` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


