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

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __thiscall REGISTRY::RestoreKeyFromFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned char,unsigned long *)` | 23 | Exported Function
`public: unsigned char __thiscall REGISTRY::SaveKeyToFile(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 24 | Exported Function
`public: unsigned char __thiscall REGISTRY::SetKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long,void *,unsigned long *,unsigned char)` | 25 | Exported Function
`public: unsigned char __thiscall REGISTRY::QueryKeySecurity(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO const *,unsigned long,void * *,unsigned long *)` | 20 | Exported Function
`public: unsigned char __thiscall REGISTRY::QuerySubKeysInfo(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class ARRAY *,unsigned long *)` | 21 | Exported Function
`public: unsigned char __thiscall REGISTRY::QueryValues(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class ARRAY *,unsigned long *)` | 22 | Exported Function
`public: unsigned char __thiscall REGISTRY::UnLoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long *)` | 26 | Exported Function
`public: virtual __thiscall REGISTRY::~REGISTRY(void)` | 4 | Exported Function
`public: virtual __thiscall REGISTRY_KEY_INFO::~REGISTRY_KEY_INFO(void)` | 5 | Exported Function
`public: virtual __thiscall REGISTRY_VALUE_ENTRY::~REGISTRY_VALUE_ENTRY(void)` | 6 | Exported Function
`public: unsigned char __thiscall REGISTRY::UpdateKeyInfo(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long *)` | 27 | Exported Function
`public: unsigned char __thiscall REGISTRY_KEY_INFO::Initialize(class WSTRING const *,class WSTRING const *,unsigned long,class WSTRING const *,struct _SECURITY_ATTRIBUTES *)` | 15 | Exported Function
`public: unsigned char __thiscall REGISTRY_VALUE_ENTRY::Initialize(class WSTRING const *,unsigned long,enum _REG_TYPE,unsigned char const *,unsigned long)` | 16 | Exported Function
`public: unsigned char __thiscall REGISTRY::QueryKeyInfo(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class REGISTRY_KEY_INFO *,unsigned long *)` | 19 | Exported Function
`public: unsigned char __thiscall REGISTRY::AddValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class REGISTRY_VALUE_ENTRY const *,unsigned char,unsigned long *)` | 7 | Exported Function
`public: unsigned char __thiscall REGISTRY::CreateKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class REGISTRY_KEY_INFO *,unsigned long *,unsigned char)` | 8 | Exported Function
`public: unsigned char __thiscall REGISTRY::DeleteKey(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 9 | Exported Function
`public: __thiscall REGISTRY::REGISTRY(void)` | 1 | Exported Function
`public: __thiscall REGISTRY_KEY_INFO::REGISTRY_KEY_INFO(void)` | 2 | Exported Function
`public: __thiscall REGISTRY_VALUE_ENTRY::REGISTRY_VALUE_ENTRY(void)` | 3 | Exported Function
`public: unsigned char __thiscall REGISTRY::DeleteValueEntry(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 10 | Exported Function
`public: unsigned char __thiscall REGISTRY::Initialize(class WSTRING const *,unsigned long *)` | 14 | Exported Function
`public: unsigned char __thiscall REGISTRY::IsAccessAllowed(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,unsigned long,unsigned long *)` | 17 | Exported Function
`public: unsigned char __thiscall REGISTRY::LoadHive(enum _PREDEFINED_KEY,class REGISTRY_KEY_INFO *,class WSTRING const *,unsigned long *)` | 18 | Exported Function
`public: unsigned char __thiscall REGISTRY::DoesKeyExist(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,unsigned long *)` | 11 | Exported Function
`public: unsigned char __thiscall REGISTRY::DoesValueExist(enum _PREDEFINED_KEY,class WSTRING const *,class WSTRING const *,class WSTRING const *,unsigned long *)` | 12 | Exported Function
`public: unsigned char __thiscall REGISTRY::EnableRootNotification(enum _PREDEFINED_KEY,void *,unsigned long,unsigned char)` | 13 | Exported Function


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


