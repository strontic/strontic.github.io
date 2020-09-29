---
title: ureg.dll | Registry Utility DLL
excerpt: What is ureg.dll?
---

# ureg.dll 

* File Path: `C:\Windows\SysWOW64\ureg.dll`
* Description: Registry Utility DLL

## Hashes

Type | Hash
-- | --
MD5 | `92A60F0F2AC1011BBDFB655C11EF7733`
SHA1 | `E043A88F075436DE32FD7FD697B19A7EFAB1FE25`
SHA256 | `D8840718AAABADE3F476D70C2A27430CC6149B71C33470B32FB7E62185D67630`
SHA384 | `EE0A85E67FA852ED73F0A96AE6D423F6674D8A67FFA80FC1B5211A998E309D91EBBAE219A199E6C8B3D34BFF633C1035`
SHA512 | `7F8AAE3AD1023EC90DCE900FA4F4101F8E97A031E95AB865EA7E799E929FD341FA4299D89A71204A7486A55104DF78528F028BA05FE5B9C678517116E0750B6A`
SSDEEP | `384:fpK8OM093eH0a8XXvnG9CS1kPkSxckDvTQsW5Esi3ZlNYc+hj0CNqqDYOWikWow:fTOM0o1wMYc2si3NaruSJ`
IMP | `D714511CDA697424B4D5E53274F6632C`
PESHA1 | `A8A4B24AC4DA197A22F82906423E9CE731CE71BD`
PE256 | `C3A716D4225795EE15D366659BB33B74943F269240DCD7CBF6A320D71D55071D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`public: __thiscall REGISTRY::REGISTRY(void)` | 1 (0x1) | Exported Function | 0x44c819d0 | 0x000019d0
`public: virtual __thiscall REGISTRY::~REGISTRY(void)` | 4 (0x4) | Exported Function | 0x44c81a10 | 0x00001a10
`public: unsigned char __thiscall REGISTRY_VALUE_ENTRY::Initialize(class WSTRING const *,unsigned long,enum _REG_TYPE,unsigned char const *,unsigned long)` | 16 (0x10) | Exported Function | 0x44c815a0 | 0x000015a0
`public: unsigned char __thiscall REGISTRY_KEY_INFO::Initialize(class WSTRING const *,class WSTRING const *,unsigned long,class WSTRING const *,struct _SECURITY_ATTRIBUTES *)` | 15 (0xf) | Exported Function | 0x44c817d0 | 0x000017d0
`public: unsigned char __thiscall REGISTRY::UpdateKeyInfo(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long *)` | 27 (0x1b) | Exported Function | 0x44c83490 | 0x00003490
`public: unsigned char __thiscall REGISTRY::UnLoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long *)` | 26 (0x1a) | Exported Function | 0x44c83ea0 | 0x00003ea0
`public: unsigned char __thiscall REGISTRY::SetKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long,void *,unsigned long *,unsigned char)` | 25 (0x19) | Exported Function | 0x44c833a0 | 0x000033a0
`public: unsigned char __thiscall REGISTRY::SaveKeyToFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 24 (0x18) | Exported Function | 0x44c83f80 | 0x00003f80
`public: unsigned char __thiscall REGISTRY::RestoreKeyFromFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned char,unsigned long *)` | 23 (0x17) | Exported Function | 0x44c84060 | 0x00004060
`public: unsigned char __thiscall REGISTRY::QueryValues(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class ARRAY *,unsigned long *)` | 22 (0x16) | Exported Function | 0x44c82ec0 | 0x00002ec0
`public: unsigned char __thiscall REGISTRY::QuerySubKeysInfo(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class ARRAY *,unsigned long *)` | 21 (0x15) | Exported Function | 0x44c82a90 | 0x00002a90
`public: unsigned char __thiscall REGISTRY::QueryKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO const *,unsigned long,void * *,unsigned long *)` | 20 (0x14) | Exported Function | 0x44c82960 | 0x00002960
`public: virtual __thiscall REGISTRY_KEY_INFO::~REGISTRY_KEY_INFO(void)` | 5 (0x5) | Exported Function | 0x44c81740 | 0x00001740
`public: unsigned char __thiscall REGISTRY::QueryKeyInfo(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class REGISTRY_KEY_INFO *,unsigned long *)` | 19 (0x13) | Exported Function | 0x44c82640 | 0x00002640
`public: unsigned char __thiscall REGISTRY::IsAccessAllowed(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long,unsigned long *)` | 17 (0x11) | Exported Function | 0x44c84150 | 0x00004150
`public: unsigned char __thiscall REGISTRY::Initialize(class WSTRING const *,unsigned long *)` | 14 (0xe) | Exported Function | 0x44c81a70 | 0x00001a70
`public: unsigned char __thiscall REGISTRY::EnableRootNotification(enum _PREDEFINED_KEY,void *,unsigned long,unsigned char)` | 13 (0xd) | Exported Function | 0x44c83a40 | 0x00003a40
`public: unsigned char __thiscall REGISTRY::DoesValueExist(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class WSTRING const *,unsigned long *)` | 12 (0xc) | Exported Function | 0x44c82570 | 0x00002570
`public: unsigned char __thiscall REGISTRY::DoesKeyExist(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,unsigned long *)` | 11 (0xb) | Exported Function | 0x44c82520 | 0x00002520
`public: unsigned char __thiscall REGISTRY::DeleteValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 10 (0xa) | Exported Function | 0x44c824c0 | 0x000024c0
`public: unsigned char __thiscall REGISTRY::DeleteKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 9 (0x9) | Exported Function | 0x44c82340 | 0x00002340
`public: unsigned char __thiscall REGISTRY::CreateKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class REGISTRY_KEY_INFO *,unsigned long *,unsigned char)` | 8 (0x8) | Exported Function | 0x44c82180 | 0x00002180
`public: unsigned char __thiscall REGISTRY::AddValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class REGISTRY_VALUE_ENTRY const *,unsigned char,unsigned long *)` | 7 (0x7) | Exported Function | 0x44c81e30 | 0x00001e30
`public: __thiscall REGISTRY_VALUE_ENTRY::REGISTRY_VALUE_ENTRY(void)` | 3 (0x3) | Exported Function | 0x44c81510 | 0x00001510
`public: __thiscall REGISTRY_KEY_INFO::REGISTRY_KEY_INFO(void)` | 2 (0x2) | Exported Function | 0x44c816d0 | 0x000016d0
`public: unsigned char __thiscall REGISTRY::LoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 18 (0x12) | Exported Function | 0x44c83d60 | 0x00003d60
`public: virtual __thiscall REGISTRY_VALUE_ENTRY::~REGISTRY_VALUE_ENTRY(void)` | 6 (0x6) | Exported Function | 0x44c81550 | 0x00001550


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d8840718aaabade3f476d70c2a27430cc6149b71c33470b32fb7e62185d67630/detection/





MIT License. Copyright (c) 2020 Strontic.


