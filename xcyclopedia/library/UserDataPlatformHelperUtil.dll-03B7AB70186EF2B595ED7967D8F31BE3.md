---
title: UserDataPlatformHelperUtil.dll | Platform Utilities for data access
excerpt: What is UserDataPlatformHelperUtil.dll?
---

# UserDataPlatformHelperUtil.dll 

* File Path: `C:\Windows\SysWOW64\UserDataPlatformHelperUtil.dll`
* Description: Platform Utilities for data access

## Hashes

Type | Hash
-- | --
MD5 | `03B7AB70186EF2B595ED7967D8F31BE3`
SHA1 | `F2A71F2B8F5C0232CF7FE3B437295FFDBDB9937F`
SHA256 | `62C60717217DFE11C944F8EB924C8CA819818F9250C3F6462FFF56AA1343CCA0`
SHA384 | `F03100E8358E5873F374F366E7341F518E9E29F66E3D6E523AB9760088F0DD09EF7E895F81C80F37CCC8D5DAAF0A9366`
SHA512 | `6C5294EC84107488E095A4AFE16C0F203CA11D082E2BD0CEFF9127D7988306BAF7732FD95C3CD8F0A7E6710EDCD87FE48E11FFE4D2A8208E2D41DB8BE393DF90`
SSDEEP | `1536:h9e8yQb0hWMUN8P2InF0de2dxCrAt68M6tLoOq4eOC9YFH6izBkO:TTpMrP2InF0de2/Lt68jkOqbOC9YFH62`
IMP | `D57C3F2DCDD0007A715CAAB80034B2BC`
PESHA1 | `2CA863B38DFD5CC1045BF4A19494BCC063C24D8A`
PE256 | `A765378D6A9B0109FA02173AC8F9CEF1188B91F57EB8D8836C4AB96FB2128A71`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,char * &)` | 13 (0xd) | Exported Function | 0x10002c30 | 0x00002c30
`public: __thiscall Comms::Deserializer::~Deserializer(void)` | 6 (0x6) | Exported Function | 0x100024e0 | 0x000024e0
`public: __thiscall Comms::RpcClient::RpcClient(void)` | 3 (0x3) | Exported Function | 0x10002de0 | 0x00002de0
`public: __thiscall Comms::RpcClient::~RpcClient(void)` | 7 (0x7) | Exported Function | 0x10002e00 | 0x00002e00
`public: __thiscall Comms::SecureRpcClient::SecureRpcClient(void)` | 4 (0x4) | Exported Function | 0x10002f20 | 0x00002f20
`public: __thiscall Comms::SerializeBuffer::SerializeBuffer(class Comms::CalculateSize const &,bool,bool)` | 5 (0x5) | Exported Function | 0x10003330 | 0x00003330
`public: bool __thiscall Comms::Deserializer::CopyBytesOut(void *,unsigned int,class type_info const &)` | 11 (0xb) | Exported Function | 0x10002b90 | 0x00002b90
`public: bool __thiscall Comms::SerializeBuffer::Initialize(void)` | 29 (0x1d) | Exported Function | 0x100033b0 | 0x000033b0
`public: class utl::vector<unsigned char,class utl::allocator<unsigned char> > const * __thiscall Comms::SerializeBuffer::GetBuffer(void)const ` | 23 (0x17) | Exported Function | 0x10002490 | 0x00002490
`public: long __thiscall Comms::RpcClient::InitializeBinding(unsigned short const *,void * &)` | 30 (0x1e) | Exported Function | 0x10002e10 | 0x00002e10
`public: unsigned int __thiscall Comms::CalculateSize::GetTotal(void)const ` | 28 (0x1c) | Exported Function | 0x10002480 | 0x00002480
`public: virtual __thiscall Comms::SecureRpcClient::~SecureRpcClient(void)` | 8 (0x8) | Exported Function | 0x10002f40 | 0x00002f40
`public: virtual void __thiscall Comms::CalculateSize::CopyBytesIn(void const *,unsigned int,class type_info const &)` | 9 (0x9) | Exported Function | 0x100032f0 | 0x000032f0
`public: virtual void __thiscall Comms::SerializeBuffer::CopyBytesIn(void const *,unsigned int,class type_info const &)` | 10 (0xa) | Exported Function | 0x100033e0 | 0x000033e0
`public: void * __thiscall Comms::Deserializer::GetBuffer(unsigned int)` | 21 (0x15) | Exported Function | 0x10002520 | 0x00002520
`public: __thiscall Comms::Deserializer::Deserializer(unsigned char const *,unsigned char const *,bool,bool)` | 2 (0x2) | Exported Function | 0x10002b50 | 0x00002b50
`public: void __thiscall Comms::Deserializer::ReleaseBuffer(void const *)` | 33 (0x21) | Exported Function | 0x10002580 | 0x00002580
`ResizeImageBySizeInMemory` | 34 (0x22) | Exported Function | 0x10005e50 | 0x00005e50
`ResizeImageBySizeToStream` | 35 (0x23) | Exported Function | 0x10006150 | 0x00006150
`RunServicesInProc` | 62 (0x3e) | Exported Function | 0x100048a0 | 0x000048a0
`SetCommsServiceJetGlobalSystemParameters` | 63 (0x3f) | Exported Function | 0x100071d0 | 0x000071d0
`SetPoolThreadBasePriority` | 41 (0x29) | Exported Function | 0x10006480 | 0x00006480
`SetThreadIOPriority` | 42 (0x2a) | Exported Function | 0x10006420 | 0x00006420
`StartAndWaitForService` | 64 (0x40) | Exported Function | 0x100048d0 | 0x000048d0
`StartAndWaitForServiceForUser` | 65 (0x41) | Exported Function | 0x10004900 | 0x00004900
`StopAndWaitForFullyNamedService` | 66 (0x42) | Exported Function | 0x10004b10 | 0x00004b10
`StopAndWaitForService` | 67 (0x43) | Exported Function | 0x10004aa0 | 0x00004aa0
`UT_UninitializeTrident` | 68 (0x44) | Exported Function | 0x100065c0 | 0x000065c0
`void __stdcall Comms::SerializeObject(class Comms::SerializeBase &,char const *)` | 39 (0x27) | Exported Function | 0x100031f0 | 0x000031f0
`void __stdcall Comms::SerializeObject(class Comms::SerializeBase &,class Comms::detail::NullType const &)` | 38 (0x26) | Exported Function | 0x100032b0 | 0x000032b0
`void __stdcall Comms::SerializeObject(class Comms::SerializeBase &,class utl::basic_string<unsigned short,struct utl::char_traits<unsigned short>,class utl::allocator<unsigned short> > const &)` | 36 (0x24) | Exported Function | 0x100025b0 | 0x000025b0
`public: void __thiscall Comms::SerializeBuffer::GetBuffer(class utl::vector<unsigned char,class utl::allocator<unsigned char> > &)` | 22 (0x16) | Exported Function | 0x100024a0 | 0x000024a0
`public: __thiscall Comms::CalculateSize::CalculateSize(bool,bool)` | 1 (0x1) | Exported Function | 0x100032c0 | 0x000032c0
`protected: long __thiscall Comms::SecureRpcClient::_InitializeSecureRpcBinding(unsigned short const *,unsigned short const *)` | 43 (0x2b) | Exported Function | 0x10002f70 | 0x00002f70
`PrependHtmlOneCore` | 61 (0x3d) | Exported Function | 0x10006630 | 0x00006630
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,char const * &)` | 15 (0xf) | Exported Function | 0x10002cb0 | 0x00002cb0
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,class Comms::detail::NullType &)` | 19 (0x13) | Exported Function | 0x10002d50 | 0x00002d50
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,class Comms::detail::NullType const &)` | 20 (0x14) | Exported Function | 0x10002d50 | 0x00002d50
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,class utl::basic_string<unsigned short,struct utl::char_traits<unsigned short>,class utl::allocator<unsigned short> > &)` | 17 (0x11) | Exported Function | 0x10002600 | 0x00002600
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,class utl::vector<unsigned char,class utl::allocator<unsigned char> > &)` | 18 (0x12) | Exported Function | 0x100026e0 | 0x000026e0
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,unsigned short * &)` | 14 (0xe) | Exported Function | 0x10002cc0 | 0x00002cc0
`bool __stdcall Comms::DeserializeObject(class Comms::Deserializer &,unsigned short const * &)` | 16 (0x10) | Exported Function | 0x10002d40 | 0x00002d40
`ConvertHtmlStringToPlainTextStringOneCore` | 45 (0x2d) | Exported Function | 0x100065e0 | 0x000065e0
`ConvertPlainTextStringToHtmlStringOneCore` | 46 (0x2e) | Exported Function | 0x10006610 | 0x00006610
`CreateKnownFolderPath` | 12 (0xc) | Exported Function | 0x10004540 | 0x00004540
`DefaultMakeHresultFromJetError` | 44 (0x2c) | Exported Function | 0x10007220 | 0x00007220
`DllCanUnloadNow` | 47 (0x2f) | Exported Function | 0x10003610 | 0x00003610
`DllGetClassObject` | 48 (0x30) | Exported Function | 0x10003640 | 0x00003640
`FreeEnumColumn` | 49 (0x31) | Exported Function | 0x10006f50 | 0x00006f50
`GenerateUserModeServiceName` | 50 (0x32) | Exported Function | 0x10004da0 | 0x00004da0
`GetCalendarColors` | 51 (0x33) | Exported Function | 0x100066b0 | 0x000066b0
`GetCombinedTransientObjectSecurityDescriptor` | 52 (0x34) | Exported Function | 0x10005020 | 0x00005020
`JetReallocMethod` | 60 (0x3c) | Exported Function | 0x10006ef0 | 0x00006ef0
`IsImageExtension` | 32 (0x20) | Exported Function | 0x100055e0 | 0x000055e0
`IsCommsSystemService` | 59 (0x3b) | Exported Function | 0x10004d10 | 0x00004d10
`IsActiveDebugger` | 31 (0x1f) | Exported Function | 0x10002ef0 | 0x00002ef0
`GetUserTokenFromContext` | 58 (0x3a) | Exported Function | 0x10004820 | 0x00004820
`GetUserContextFromHandle` | 57 (0x39) | Exported Function | 0x10004860 | 0x00004860
`void __stdcall Comms::SerializeObject(class Comms::SerializeBase &,class utl::vector<unsigned char,class utl::allocator<unsigned char> > const &)` | 37 (0x25) | Exported Function | 0x10002690 | 0x00002690
`GetThreadIOPriority` | 27 (0x1b) | Exported Function | 0x100063c0 | 0x000063c0
`GetSupportedImageFileExtensions` | 25 (0x19) | Exported Function | 0x100052a0 | 0x000052a0
`GetRpcClientThreadToken` | 24 (0x18) | Exported Function | 0x10004c90 | 0x00004c90
`GetQueryProcessHandle` | 56 (0x38) | Exported Function | 0x100051b0 | 0x000051b0
`GetNextNewCalendarColor` | 55 (0x37) | Exported Function | 0x100066f0 | 0x000066f0
`GetFileExtensionFromContentType` | 54 (0x36) | Exported Function | 0x10006ca0 | 0x00006ca0
`GetContentTypeFromFilePath` | 53 (0x35) | Exported Function | 0x10006a50 | 0x00006a50
`GetTempFileNameWithExt` | 26 (0x1a) | Exported Function | 0x10004320 | 0x00004320
`void __stdcall Comms::SerializeObject(class Comms::SerializeBase &,unsigned short const *)` | 40 (0x28) | Exported Function | 0x10003250 | 0x00003250


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/62c60717217dfe11c944f8eb924c8ca819818f9250c3f6462fff56aa1343cca0/detection/





MIT License. Copyright (c) 2020 Strontic.


