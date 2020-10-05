---
title: tcpmib.dll | Standard TCP/IP Port Monitor Helper DLL
excerpt: What is tcpmib.dll?
---

# tcpmib.dll 

* File Path: `C:\Windows\system32\tcpmib.dll`
* Description: Standard TCP/IP Port Monitor Helper DLL

## Hashes

Type | Hash
-- | --
MD5 | `05DA8E4042706368AC6145427296F146`
SHA1 | `C895F38B443FA8802C03C52BFDFBBA5345DAEE10`
SHA256 | `80550A28B82A690594E770E82D35422D169D215F499CA82B7BBD0CA83DBCF284`
SHA384 | `95D3CEBE0181F543EC54D438822FF05A318BBF27CA3DA0E34E840214803B3DD10541223C48A539B5D14584CCF2A1DDE4`
SHA512 | `DB1CCE57687A04104BF2300B21F0A36CF9B61082A6B090263861161D7AA4940C2A9C7C2E0E81E086197984F80752BE0506167A7F4C133BF834E9FD1A88A54E46`
SSDEEP | `768:5M4rv1u05SpjDHB7k0LQWDsNKE6+fOneyS3w8y3K:pg0SJrKWN6yWZ`
IMP | `19AC11CB8915F1A9FE64BC7B95D04FB0`
PESHA1 | `E8E173C7889BAC2511F4C1B18F6ED4447B09248C`
PE256 | `A1AD5F073EB1E406777545E43D786A965BA8BFDCF1C822B4E0D66E3B614EC8BC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual int __cdecl CTcpMib::SupportsPrinterMib(char const * __ptr64,char const * __ptr64,unsigned long,int * __ptr64) __ptr64` | 33 | Exported Function
`public: virtual int __cdecl CTcpMib::RFC1157ToString(struct SnmpVarBind * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 23 | Exported Function
`public: virtual long __cdecl CTcpMib::GetPortList(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 16 | Exported Function
`public: virtual long __cdecl CTcpMib::GetDeviceId(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 12 | Exported Function
`public: unsigned long __cdecl CTcpMib::SnmpGetNext(char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 30 | Exported Function
`public: unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 27 | Exported Function
`public: virtual __cdecl CTcpMibABC::~CTcpMibABC(void) __ptr64` | 6 | Exported Function
`public: virtual __cdecl CTcpMib::~CTcpMib(void) __ptr64` | 5 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::GetDeviceDescription(char const * __ptr64,char const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long) __ptr64` | 11 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,struct AsnObjectIdentifier * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 29 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 28 | Exported Function
`public: virtual void __cdecl CTcpMib::UnInitSnmp(void) __ptr64` | 34 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::SnmpGetNext(char const * __ptr64,char const * __ptr64,struct AsnObjectIdentifier * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 31 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::InitSnmp(void) __ptr64` | 20 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::GetNextRequestId(unsigned long * __ptr64) __ptr64` | 15 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::RequestDeviceStatus(void * __ptr64,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 25 | Exported Function
`public: virtual unsigned long __cdecl CTcpMib::RegisterDeviceStatusCallback(unsigned long (__cdecl*)(int,char const * __ptr64,char const * __ptr64,unsigned long,unsigned long,unsigned long),void * __ptr64 * __ptr64) __ptr64` | 24 | Exported Function
`public: int __cdecl CTcpMib::IsValid(void)const __ptr64` | 21 | Exported Function
`private: long __cdecl CTcpMib::GetPortListFromIni(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 17 | Exported Function
`private: long __cdecl CTcpMib::GetDeviceIdFromMib(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 14 | Exported Function
`private: long __cdecl CTcpMib::SupportsPortMonMib(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 32 | Exported Function
`private: long __cdecl CTcpMib::GetPortListFromMib(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 18 | Exported Function
`const CTcpMibABC::``vftable'` | 10 | Exported Function
`const CTcpMib::``vftable'` | 9 | Exported Function
`private: long __cdecl CTcpMib::GetDeviceIdFromIni(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 13 | Exported Function
`GetTcpMibPtr` | 35 | Exported Function
`private: static int __cdecl CTcpMib::MapAsynchToPortStatus(unsigned long,struct _PORT_INFO_3W * __ptr64)` | 22 | Exported Function
`public: __cdecl CTcpMibABC::CTcpMibABC(void) __ptr64` | 4 | Exported Function
`public: __cdecl CTcpMibABC::CTcpMibABC(class CTcpMibABC const & __ptr64) __ptr64` | 3 | Exported Function
`public: class CTcpMibABC & __ptr64 __cdecl CTcpMibABC::operator=(class CTcpMibABC const & __ptr64) __ptr64` | 8 | Exported Function
`public: class CTcpMib & __ptr64 __cdecl CTcpMib::operator=(class CTcpMib const & __ptr64) __ptr64` | 7 | Exported Function
`private: static unsigned long __cdecl CTcpMib::SnmpCallback(void * __ptr64,struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64,void * __ptr64)` | 26 | Exported Function
`private: static unsigned long __cdecl CTcpMib::GetStatusFromVBL(void * __ptr64,struct smiVALUE * __ptr64,struct smiVALUE * __ptr64,struct smiVALUE * __ptr64)` | 19 | Exported Function
`public: __cdecl CTcpMib::CTcpMib(void) __ptr64` | 2 | Exported Function
`public: __cdecl CTcpMib::CTcpMib(class CTcpMib const & __ptr64) __ptr64` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tcpmib.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/80550a28b82a690594e770e82d35422d169d215f499ca82b7bbd0ca83dbcf284/detection/





MIT License. Copyright (c) 2020 Strontic.


