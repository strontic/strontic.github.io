---
title: UserDataPlatformHelperUtil.dll | Platform Utilities for data access
excerpt: What is UserDataPlatformHelperUtil.dll?
---

# UserDataPlatformHelperUtil.dll 

* File Path: `C:\Windows\system32\UserDataPlatformHelperUtil.dll`
* Description: Platform Utilities for data access

## Hashes

Type | Hash
-- | --
MD5 | `CBF31B2054EBFE9DE6F2F36E292EF9A4`
SHA1 | `BDF9FA79AB7E2B5CF10A9FEA28A52C14E13C69BC`
SHA256 | `C17941B67B0303D6221176A224A8E4C3C013A2DA7CC6EFC9395226C0457D45E0`
SHA384 | `1E554B48C1303B90A58016F9D5CD3EFCCD3F37005B5CD87DF4F2917420974E33BF31498B2826F972D7CB7A2858423EB3`
SHA512 | `EF0415A654D10A74C2066534C4F9BB3D91639C9C80B64153DE404D8B1679DBC04623F5B5F18CE1A09D6A26AF06DB176B082CD57DD72C11E56A3AECD8D5834A60`
SSDEEP | `1536:EtbEq52wX2HdYim9WBtb3UQOGxv6NtNSw/aXKyn7f/Hayz9p:E6/wcKWBtle3NSTKyn7f/HaO9p`
IMP | `A43945C2790903069C62C81E001E1B45`
PESHA1 | `966C7738DE492065F31A99D7AAB9C4E0D6ACC740`
PE256 | `D6A402E3A319F4C718798ED8FF210A5F6DD7594B4EE0BFDE3C8ECED4C9454B2C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,char * __ptr64 & __ptr64)` | 13 (0xd) | Exported Function | 0x0000000180001a80 | 0x00001a80
`public: __cdecl Comms::Deserializer::~Deserializer(void) __ptr64` | 6 (0x6) | Exported Function | 0x00000001800011e0 | 0x000011e0
`public: __cdecl Comms::RpcClient::RpcClient(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001cc0 | 0x00001cc0
`public: __cdecl Comms::RpcClient::~RpcClient(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180001ce0 | 0x00001ce0
`public: __cdecl Comms::SecureRpcClient::SecureRpcClient(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180001e50 | 0x00001e50
`public: __cdecl Comms::SerializeBuffer::SerializeBuffer(class Comms::CalculateSize const & __ptr64,bool,bool) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180002460 | 0x00002460
`public: bool __cdecl Comms::Deserializer::CopyBytesOut(void * __ptr64,unsigned __int64,class type_info const & __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180001980 | 0x00001980
`public: bool __cdecl Comms::SerializeBuffer::Initialize(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180002500 | 0x00002500
`public: class utl::vector<unsigned char,class utl::allocator<unsigned char> > const * __ptr64 __cdecl Comms::SerializeBuffer::GetBuffer(void)const __ptr64` | 23 (0x17) | Exported Function | 0x0000000180001180 | 0x00001180
`public: long __cdecl Comms::RpcClient::InitializeBinding(unsigned short const * __ptr64,void * __ptr64 & __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180001d30 | 0x00001d30
`public: unsigned __int64 __cdecl Comms::CalculateSize::GetTotal(void)const __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180001170 | 0x00001170
`public: virtual __cdecl Comms::SecureRpcClient::~SecureRpcClient(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001e70 | 0x00001e70
`public: virtual void __cdecl Comms::CalculateSize::CopyBytesIn(void const * __ptr64,unsigned __int64,class type_info const & __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180002410 | 0x00002410
`public: virtual void __cdecl Comms::SerializeBuffer::CopyBytesIn(void const * __ptr64,unsigned __int64,class type_info const & __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180002540 | 0x00002540
`public: void * __ptr64 __cdecl Comms::Deserializer::GetBuffer(unsigned __int64) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180001240 | 0x00001240
`public: __cdecl Comms::Deserializer::Deserializer(unsigned char const * __ptr64,unsigned char const * __ptr64,bool,bool) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001950 | 0x00001950
`public: void __cdecl Comms::Deserializer::ReleaseBuffer(void const * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x00000001800012e0 | 0x000012e0
`ResizeImageBySizeInMemory` | 34 (0x22) | Exported Function | 0x0000000180005760 | 0x00005760
`ResizeImageBySizeToStream` | 35 (0x23) | Exported Function | 0x0000000180005b40 | 0x00005b40
`RunServicesInProc` | 62 (0x3e) | Exported Function | 0x0000000180003e30 | 0x00003e30
`SetCommsServiceJetGlobalSystemParameters` | 63 (0x3f) | Exported Function | 0x0000000180007420 | 0x00007420
`SetPoolThreadBasePriority` | 41 (0x29) | Exported Function | 0x0000000180005f20 | 0x00005f20
`SetThreadIOPriority` | 42 (0x2a) | Exported Function | 0x0000000180005ea0 | 0x00005ea0
`StartAndWaitForService` | 64 (0x40) | Exported Function | 0x0000000180003e50 | 0x00003e50
`StartAndWaitForServiceForUser` | 65 (0x41) | Exported Function | 0x0000000180003e90 | 0x00003e90
`StopAndWaitForFullyNamedService` | 66 (0x42) | Exported Function | 0x0000000180004110 | 0x00004110
`StopAndWaitForService` | 67 (0x43) | Exported Function | 0x0000000180004090 | 0x00004090
`UT_UninitializeTrident` | 68 (0x44) | Exported Function | 0x0000000180006350 | 0x00006350
`void __cdecl Comms::SerializeObject(class Comms::SerializeBase & __ptr64,char const * __ptr64)` | 39 (0x27) | Exported Function | 0x00000001800022d0 | 0x000022d0
`void __cdecl Comms::SerializeObject(class Comms::SerializeBase & __ptr64,class Comms::detail::NullType const & __ptr64)` | 38 (0x26) | Exported Function | 0x00000001800023d0 | 0x000023d0
`void __cdecl Comms::SerializeObject(class Comms::SerializeBase & __ptr64,class utl::basic_string<unsigned short,struct utl::char_traits<unsigned short>,class utl::allocator<unsigned short> > const & __ptr64)` | 36 (0x24) | Exported Function | 0x0000000180001310 | 0x00001310
`public: void __cdecl Comms::SerializeBuffer::GetBuffer(class utl::vector<unsigned char,class utl::allocator<unsigned char> > & __ptr64) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001190 | 0x00001190
`public: __cdecl Comms::CalculateSize::CalculateSize(bool,bool) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800023e0 | 0x000023e0
`protected: long __cdecl Comms::SecureRpcClient::_InitializeSecureRpcBinding(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180001eb0 | 0x00001eb0
`PrependHtmlOneCore` | 61 (0x3d) | Exported Function | 0x0000000180006540 | 0x00006540
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,char const * __ptr64 & __ptr64)` | 15 (0xf) | Exported Function | 0x0000000180001b30 | 0x00001b30
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,class Comms::detail::NullType & __ptr64)` | 19 (0x13) | Exported Function | 0x0000000180001c10 | 0x00001c10
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,class Comms::detail::NullType const & __ptr64)` | 20 (0x14) | Exported Function | 0x0000000180001c10 | 0x00001c10
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,class utl::basic_string<unsigned short,struct utl::char_traits<unsigned short>,class utl::allocator<unsigned short> > & __ptr64)` | 17 (0x11) | Exported Function | 0x0000000180001390 | 0x00001390
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,class utl::vector<unsigned char,class utl::allocator<unsigned char> > & __ptr64)` | 18 (0x12) | Exported Function | 0x00000001800014c0 | 0x000014c0
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,unsigned short * __ptr64 & __ptr64)` | 14 (0xe) | Exported Function | 0x0000000180001b40 | 0x00001b40
`bool __cdecl Comms::DeserializeObject(class Comms::Deserializer & __ptr64,unsigned short const * __ptr64 & __ptr64)` | 16 (0x10) | Exported Function | 0x0000000180001c00 | 0x00001c00
`ConvertHtmlStringToPlainTextStringOneCore` | 44 (0x2c) | Exported Function | 0x00000001800063e0 | 0x000063e0
`ConvertPlainTextStringToHtmlStringOneCore` | 45 (0x2d) | Exported Function | 0x0000000180006520 | 0x00006520
`CreateKnownFolderPath` | 12 (0xc) | Exported Function | 0x0000000180003a80 | 0x00003a80
`DefaultMakeHresultFromJetError` | 46 (0x2e) | Exported Function | 0x0000000180007490 | 0x00007490
`DllCanUnloadNow` | 47 (0x2f) | Exported Function | 0x00000001800029b0 | 0x000029b0
`DllGetClassObject` | 48 (0x30) | Exported Function | 0x00000001800029f0 | 0x000029f0
`FreeEnumColumn` | 49 (0x31) | Exported Function | 0x00000001800070a0 | 0x000070a0
`GenerateUserModeServiceName` | 50 (0x32) | Exported Function | 0x0000000180004450 | 0x00004450
`GetCalendarColors` | 51 (0x33) | Exported Function | 0x00000001800065a0 | 0x000065a0
`GetCombinedTransientObjectSecurityDescriptor` | 52 (0x34) | Exported Function | 0x0000000180004820 | 0x00004820
`JetReallocMethod` | 60 (0x3c) | Exported Function | 0x0000000180007010 | 0x00007010
`IsImageExtension` | 32 (0x20) | Exported Function | 0x0000000180004f40 | 0x00004f40
`IsCommsSystemService` | 59 (0x3b) | Exported Function | 0x00000001800043b0 | 0x000043b0
`IsActiveDebugger` | 31 (0x1f) | Exported Function | 0x0000000180001e10 | 0x00001e10
`GetUserTokenFromContext` | 58 (0x3a) | Exported Function | 0x0000000180003d90 | 0x00003d90
`GetUserContextFromHandle` | 57 (0x39) | Exported Function | 0x0000000180003de0 | 0x00003de0
`void __cdecl Comms::SerializeObject(class Comms::SerializeBase & __ptr64,class utl::vector<unsigned char,class utl::allocator<unsigned char> > const & __ptr64)` | 37 (0x25) | Exported Function | 0x0000000180001450 | 0x00001450
`GetThreadIOPriority` | 27 (0x1b) | Exported Function | 0x0000000180005e20 | 0x00005e20
`GetSupportedImageFileExtensions` | 25 (0x19) | Exported Function | 0x0000000180004b50 | 0x00004b50
`GetRpcClientThreadToken` | 24 (0x18) | Exported Function | 0x00000001800042f0 | 0x000042f0
`GetQueryProcessHandle` | 56 (0x38) | Exported Function | 0x0000000180004a30 | 0x00004a30
`GetNextNewCalendarColor` | 55 (0x37) | Exported Function | 0x0000000180006610 | 0x00006610
`GetFileExtensionFromContentType` | 54 (0x36) | Exported Function | 0x0000000180006d60 | 0x00006d60
`GetContentTypeFromFilePath` | 53 (0x35) | Exported Function | 0x0000000180006a90 | 0x00006a90
`GetTempFileNameWithExt` | 26 (0x1a) | Exported Function | 0x0000000180003720 | 0x00003720
`void __cdecl Comms::SerializeObject(class Comms::SerializeBase & __ptr64,unsigned short const * __ptr64)` | 40 (0x28) | Exported Function | 0x0000000180002350 | 0x00002350


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CommsPlatformHelperUtil.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c17941b67b0303d6221176a224a8e4c3c013a2da7cc6efc9395226c0457d45e0/detection/





MIT License. Copyright (c) 2020 Strontic.


