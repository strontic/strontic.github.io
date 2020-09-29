---
title: mssrch.dll | Microsoft Embedded Search
excerpt: What is mssrch.dll?
---

# mssrch.dll 

* File Path: `C:\Windows\system32\mssrch.dll`
* Description: Microsoft Embedded Search

## Hashes

Type | Hash
-- | --
MD5 | `35AA74AC2807201EC3EA58ACFE332FDE`
SHA1 | `9C2969452FB329C855B1E1B183400F1667FEB198`
SHA256 | `6FA52C6911B38FA6A0E382739019017AB78472CF00F713DE67268C07BD565EBE`
SHA384 | `ECA54E26CD34E74C1C476C7E1687AC6E0444916E355D18B3FC732A84B65F29BD4FA4B65DF1109B96AC549F2C0336C844`
SHA512 | `072F37CE738702EF3FE963EC3331B711C3264802BA08FEF7D571E6A606C49430856FDEDE8D57D1DA64D10AFC75C933C871CBCCF78505E796B88C52F0BE55AED3`
SSDEEP | `49152:MaDLmN0SdrwvpJRvmpVk+IEjlyEMnDgVKfaAhkJRRT6H9a:piP3pfGhCAC5`
IMP | `7FE5D5A4FBAFCD0422BD90215B03F2F2`
PESHA1 | `90F8F3F6B010EEBF189553FC99F8CFFCE60BE80A`
PE256 | `66F5D9A1F1F8488AA589EEB46EBE8E7057964FEC2EFDC52407B364F74D138756`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class std::shared_ptr<struct Windows::ChangeTracking::IFileChangeClientManager> __cdecl GetFileChangeClientManagerInstance(void)` | 7 (0x7) | Exported Function | 0x00000001600502b0 | 0x000502b0
`public: virtual long __cdecl CSearchServiceObj::Shutdown(void) __ptr64` | 14 (0xe) | Exported Function | 0x0000000160082ad0 | 0x00082ad0
`public: virtual long __cdecl CSearchServiceObj::SetServiceStatusObj(struct IDCOMServiceStatus * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x00000001600c3b40 | 0x000c3b40
`public: virtual long __cdecl CSearchServiceObj::PostServiceStartup(void) __ptr64` | 12 (0xc) | Exported Function | 0x00000001600c2e90 | 0x000c2e90
`public: virtual long __cdecl CSearchServiceObj::LogonNotification(unsigned long) __ptr64` | 11 (0xb) | Exported Function | 0x00000001600c45a0 | 0x000c45a0
`public: virtual long __cdecl CSearchServiceObj::LogoffNotification(unsigned long) __ptr64` | 10 (0xa) | Exported Function | 0x00000001600c4cc0 | 0x000c4cc0
`public: virtual long __cdecl CSearchServiceObj::Initialize(bool,unsigned long,class std::vector<class ReIndexPatternInfo,class std::allocator<class ReIndexPatternInfo> > const * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x000000016009a8a0 | 0x0009a8a0
`public: virtual long __cdecl CSearchServiceObj::HandleDplKeyChange(void) __ptr64` | 8 (0x8) | Exported Function | 0x000000016012eb30 | 0x0012eb30
`public: static void __cdecl CSearchServiceObj::Cleanup(void)` | 6 (0x6) | Exported Function | 0x000000016008c280 | 0x0008c280
`public: class CSearchServiceObj & __ptr64 __cdecl CSearchServiceObj::operator=(class CSearchServiceObj const & __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x00000001601221e0 | 0x001221e0
`public: __cdecl CSearchServiceObj::~CSearchServiceObj(void) __ptr64` | 3 (0x3) | Exported Function | 0x000000016008bf90 | 0x0008bf90
`public: __cdecl CSearchServiceObj::CSearchServiceObj(void) __ptr64` | 2 (0x2) | Exported Function | 0x00000001600b20d0 | 0x000b20d0
`public: __cdecl CSearchServiceObj::CSearchServiceObj(class CSearchServiceObj const & __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000160120fb0 | 0x00120fb0
`MSSrch_SysPrep_Cleanup` | 22 (0x16) | Exported Function | 0x0000000160132180 | 0x00132180
`GetCatalogManager` | 21 (0x15) | Exported Function | 0x000000016012d420 | 0x0012d420
`DllUnregisterServer` | 20 (0x14) | Exported Function | 0x000000016012d410 | 0x0012d410
`DllRegisterServer` | 19 (0x13) | Exported Function | 0x000000016012d3a0 | 0x0012d3a0
`DllGetClassObject` | 18 (0x12) | Exported Function | 0x0000000160077ce0 | 0x00077ce0
`DllCanUnloadNow` | 17 (0x11) | Exported Function | 0x0000000160075050 | 0x00075050
`const CSearchServiceObj::``vftable'` | 5 (0x5) | Exported Function | 0x00000001601f1980 | 0x001f1980
`public: virtual long __cdecl CSearchServiceObj::Start(void) __ptr64` | 15 (0xf) | Exported Function | 0x00000001600bb810 | 0x000bb810
`public: virtual long __cdecl CSearchServiceObj::Stop(int) __ptr64` | 16 (0x10) | Exported Function | 0x0000000160082b50 | 0x00082b50


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSSRCH.dll.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.19041.1 (WinBuild.160101.0800)
* Product Version: 7.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/6fa52c6911b38fa6a0e382739019017ab78472cf00f713de67268c07bd565ebe/detection/





MIT License. Copyright (c) 2020 Strontic.


