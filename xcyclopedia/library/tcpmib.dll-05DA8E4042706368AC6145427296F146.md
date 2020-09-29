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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CTcpMib::``vftable'` | 9 (0x9) | Exported Function | 0x0000000180008080 | 0x00008080
`public: unsigned long __cdecl CTcpMib::SnmpGetNext(char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x00000001800038d0 | 0x000038d0
`public: virtual __cdecl CTcpMib::~CTcpMib(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180002ff0 | 0x00002ff0
`public: virtual __cdecl CTcpMibABC::~CTcpMibABC(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001030 | 0x00001030
`public: virtual int __cdecl CTcpMib::RFC1157ToString(struct SnmpVarBind * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180004760 | 0x00004760
`public: virtual int __cdecl CTcpMib::SupportsPrinterMib(char const * __ptr64,char const * __ptr64,unsigned long,int * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x00000001800030f0 | 0x000030f0
`public: virtual long __cdecl CTcpMib::GetDeviceId(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180004940 | 0x00004940
`public: unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 27 (0x1b) | Exported Function | 0x00000001800036a0 | 0x000036a0
`public: virtual long __cdecl CTcpMib::GetPortList(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800048a0 | 0x000048a0
`public: virtual unsigned long __cdecl CTcpMib::GetNextRequestId(unsigned long * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180004700 | 0x00004700
`public: virtual unsigned long __cdecl CTcpMib::InitSnmp(void) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180003040 | 0x00003040
`public: virtual unsigned long __cdecl CTcpMib::RegisterDeviceStatusCallback(unsigned long (__cdecl*)(int,char const * __ptr64,char const * __ptr64,unsigned long,unsigned long,unsigned long),void * __ptr64 * __ptr64) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180003f30 | 0x00003f30
`public: virtual unsigned long __cdecl CTcpMib::RequestDeviceStatus(void * __ptr64,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180003ae0 | 0x00003ae0
`public: virtual unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,char const * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x00000001800035c0 | 0x000035c0
`public: virtual unsigned long __cdecl CTcpMib::SnmpGet(char const * __ptr64,char const * __ptr64,struct AsnObjectIdentifier * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800034a0 | 0x000034a0
`public: virtual unsigned long __cdecl CTcpMib::GetDeviceDescription(char const * __ptr64,char const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800033c0 | 0x000033c0
`public: virtual unsigned long __cdecl CTcpMib::SnmpGetNext(char const * __ptr64,char const * __ptr64,struct AsnObjectIdentifier * __ptr64,struct SnmpVarBindList * __ptr64) __ptr64` | 31 (0x1f) | Exported Function | 0x00000001800037b0 | 0x000037b0
`public: int __cdecl CTcpMib::IsValid(void)const __ptr64` | 21 (0x15) | Exported Function | 0x0000000180003030 | 0x00003030
`public: class CTcpMib & __ptr64 __cdecl CTcpMib::operator=(class CTcpMib const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180001a30 | 0x00001a30
`const CTcpMibABC::``vftable'` | 10 (0xa) | Exported Function | 0x0000000180008010 | 0x00008010
`GetTcpMibPtr` | 35 (0x23) | Exported Function | 0x0000000180002da0 | 0x00002da0
`private: long __cdecl CTcpMib::GetDeviceIdFromIni(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x00000001800051c0 | 0x000051c0
`private: long __cdecl CTcpMib::GetDeviceIdFromMib(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180005090 | 0x00005090
`private: long __cdecl CTcpMib::GetPortListFromIni(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180004c90 | 0x00004c90
`private: long __cdecl CTcpMib::GetPortListFromMib(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180004a10 | 0x00004a10
`public: class CTcpMibABC & __ptr64 __cdecl CTcpMibABC::operator=(class CTcpMibABC const & __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001050 | 0x00001050
`private: long __cdecl CTcpMib::SupportsPortMonMib(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180003230 | 0x00003230
`private: static unsigned long __cdecl CTcpMib::GetStatusFromVBL(void * __ptr64,struct smiVALUE * __ptr64,struct smiVALUE * __ptr64,struct smiVALUE * __ptr64)` | 19 (0x13) | Exported Function | 0x0000000180004380 | 0x00004380
`private: static unsigned long __cdecl CTcpMib::SnmpCallback(void * __ptr64,struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64,void * __ptr64)` | 26 (0x1a) | Exported Function | 0x0000000180003f90 | 0x00003f90
`public: __cdecl CTcpMib::CTcpMib(class CTcpMib const & __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800019f0 | 0x000019f0
`public: __cdecl CTcpMib::CTcpMib(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180002fb0 | 0x00002fb0
`public: __cdecl CTcpMibABC::CTcpMibABC(class CTcpMibABC const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001010 | 0x00001010
`public: __cdecl CTcpMibABC::CTcpMibABC(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180001010 | 0x00001010
`private: static int __cdecl CTcpMib::MapAsynchToPortStatus(unsigned long,struct _PORT_INFO_3W * __ptr64)` | 22 (0x16) | Exported Function | 0x00000001800039e0 | 0x000039e0
`public: virtual void __cdecl CTcpMib::UnInitSnmp(void) __ptr64` | 34 (0x22) | Exported Function | 0x00000001800030d0 | 0x000030d0


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


