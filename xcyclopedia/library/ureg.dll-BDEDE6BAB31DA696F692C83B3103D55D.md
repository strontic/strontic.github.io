---
title: ureg.dll | Registry Utility DLL
excerpt: What is ureg.dll?
---

# ureg.dll 

* File Path: `C:\Windows\system32\ureg.dll`
* Description: Registry Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `BDEDE6BAB31DA696F692C83B3103D55D`
SHA1 | `9832F19DA8E8DA8E0C4E95D15503F0172B07C523`
SHA256 | `CC7126B30F64FC34A926935AE303276D0E729E990F428C667FAC32AF2B67F64F`
SHA384 | `047FFFD1D41315B9B7BC0F8F967792D16EFD1C86AE6EACF1D0354B57182478F79115E9979177A21D426CA37B02E12717`
SHA512 | `A941522C60031D778BB4A36BBDAA236E69355F490D36EC1A87D36EB2A8E956C679ED4896B45915591FF2E22006C4EC7A1679B917CBFFFF759F1F6C15DAA1BB7B`
SSDEEP | `768:x3ukuHt/hudw7gBWOJQIhm4SJF+10YVb1KCZxd+lm9AR2BqobRZfEQ:8lNA2cBWOJQIhm4yFCS8bnA8BqobXft`
IMP | `D5D82E33B15E62EBE634510399778633`
PESHA1 | `92A35DCCE7E934625767296A289046A5AAAC9827`
PE256 | `A6C1C29BA90CF67722DA0206E748BC6CAEC9E846CBB84ED58423975608F82639`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __cdecl REGISTRY::RestoreKeyFromFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class WSTRING const * __ptr64,unsigned char,unsigned long * __ptr64) __ptr64` | 23 | Exported Function
`public: unsigned char __cdecl REGISTRY::SaveKeyToFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 24 | Exported Function
`public: unsigned char __cdecl REGISTRY::SetKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,unsigned long,void * __ptr64,unsigned long * __ptr64,unsigned char) __ptr64` | 25 | Exported Function
`public: unsigned char __cdecl REGISTRY::QueryKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO const * __ptr64,unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 20 | Exported Function
`public: unsigned char __cdecl REGISTRY::QuerySubKeysInfo(enum _PREDEFINED_KEY,class WSTRING const * __ptr64,class WSTRING const * __ptr64,class ARRAY * __ptr64,unsigned long * __ptr64) __ptr64` | 21 | Exported Function
`public: unsigned char __cdecl REGISTRY::QueryValues(enum _PREDEFINED_KEY,class WSTRING const * __ptr64,class WSTRING const * __ptr64,class ARRAY * __ptr64,unsigned long * __ptr64) __ptr64` | 22 | Exported Function
`public: unsigned char __cdecl REGISTRY::UnLoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,unsigned long * __ptr64) __ptr64` | 26 | Exported Function
`public: virtual __cdecl REGISTRY::~REGISTRY(void) __ptr64` | 4 | Exported Function
`public: virtual __cdecl REGISTRY_KEY_INFO::~REGISTRY_KEY_INFO(void) __ptr64` | 5 | Exported Function
`public: virtual __cdecl REGISTRY_VALUE_ENTRY::~REGISTRY_VALUE_ENTRY(void) __ptr64` | 6 | Exported Function
`public: unsigned char __cdecl REGISTRY::UpdateKeyInfo(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,unsigned long * __ptr64) __ptr64` | 27 | Exported Function
`public: unsigned char __cdecl REGISTRY_KEY_INFO::Initialize(class WSTRING const * __ptr64,class WSTRING const * __ptr64,unsigned long,class WSTRING const * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64) __ptr64` | 15 | Exported Function
`public: unsigned char __cdecl REGISTRY_VALUE_ENTRY::Initialize(class WSTRING const * __ptr64,unsigned long,enum _REG_TYPE,unsigned char const * __ptr64,unsigned long) __ptr64` | 16 | Exported Function
`public: unsigned char __cdecl REGISTRY::QueryKeyInfo(enum _PREDEFINED_KEY,class WSTRING const * __ptr64,class WSTRING const * __ptr64,class REGISTRY_KEY_INFO * __ptr64,unsigned long * __ptr64) __ptr64` | 19 | Exported Function
`public: unsigned char __cdecl REGISTRY::AddValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class REGISTRY_VALUE_ENTRY const * __ptr64,unsigned char,unsigned long * __ptr64) __ptr64` | 7 | Exported Function
`public: unsigned char __cdecl REGISTRY::CreateKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class REGISTRY_KEY_INFO * __ptr64,unsigned long * __ptr64,unsigned char) __ptr64` | 8 | Exported Function
`public: unsigned char __cdecl REGISTRY::DeleteKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 9 | Exported Function
`public: __cdecl REGISTRY::REGISTRY(void) __ptr64` | 1 | Exported Function
`public: __cdecl REGISTRY_KEY_INFO::REGISTRY_KEY_INFO(void) __ptr64` | 2 | Exported Function
`public: __cdecl REGISTRY_VALUE_ENTRY::REGISTRY_VALUE_ENTRY(void) __ptr64` | 3 | Exported Function
`public: unsigned char __cdecl REGISTRY::DeleteValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 10 | Exported Function
`public: unsigned char __cdecl REGISTRY::Initialize(class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 14 | Exported Function
`public: unsigned char __cdecl REGISTRY::IsAccessAllowed(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 17 | Exported Function
`public: unsigned char __cdecl REGISTRY::LoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 18 | Exported Function
`public: unsigned char __cdecl REGISTRY::DoesKeyExist(enum _PREDEFINED_KEY,class WSTRING const * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 11 | Exported Function
`public: unsigned char __cdecl REGISTRY::DoesValueExist(enum _PREDEFINED_KEY,class WSTRING const * __ptr64,class WSTRING const * __ptr64,class WSTRING const * __ptr64,unsigned long * __ptr64) __ptr64` | 12 | Exported Function
`public: unsigned char __cdecl REGISTRY::EnableRootNotification(enum _PREDEFINED_KEY,void * __ptr64,unsigned long,unsigned char) __ptr64` | 13 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ureg.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/cc7126b30f64fc34a926935ae303276d0e729e990f428c667fac32af2b67f64f/detection/





MIT License. Copyright (c) 2020 Strontic.


