---
title: tcpmib.dll | Standard TCP/IP Port Monitor Helper DLL
excerpt: What is tcpmib.dll?
---

# tcpmib.dll 

* File Path: `C:\Windows\SysWOW64\tcpmib.dll`
* Description: Standard TCP/IP Port Monitor Helper DLL

## Hashes

Type | Hash
-- | --
MD5 | `1CBB35A343A7ACDD3A0ED344F93C24F2`
SHA1 | `FEE15FE54475021956755E3BBF7A11778E058A91`
SHA256 | `46BA5CEB4683594A161E1FF448541C88AFE8132E48F98774CC598968AAD464CE`
SHA384 | `F3ECEDFD63B07E0B07044F7FC6FE69183C9F906959286891010DF8CFA06067A7E13A7B7B130809DFC7F51CC019095D18`
SHA512 | `9D99ED6086191F263C664B906C6060E5950B9D042C0E090E574984280E0310D5A8141D48FD0F74E5E9EC387181DCA6ED0975D618D4332F50FF3811CB3C8A0B96`
SSDEEP | `768:r65UN5IOTFVm66BQkYC8nDKziDKZGA84qf2aqM7pk4Sk6qw:MQkYC8nD3aGATmkM7Kf9`
IMP | `958357108933BE413075E8E72532818F`
PESHA1 | `FA1674EB0D79908E609262E6AC7E97EC292F303A`
PE256 | `8A3EC37AA92D4AD3647E3EDDAD0332C7C80D84EB15120DD774353EEF2E0828B9`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual int __thiscall CTcpMib::SupportsPrinterMib(char const *,char const *,unsigned long,int *)` | 33 | Exported Function
`public: virtual int __thiscall CTcpMib::RFC1157ToString(struct SnmpVarBind *,unsigned short *,unsigned long,unsigned long *)` | 23 | Exported Function
`public: virtual long __thiscall CTcpMib::GetPortList(unsigned short const *,unsigned char *,unsigned long,unsigned long *)` | 16 | Exported Function
`public: virtual long __thiscall CTcpMib::GetDeviceId(unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long *)` | 12 | Exported Function
`public: unsigned long __thiscall CTcpMib::SnmpGetNext(char const *,char const *,struct SnmpVarBindList *)` | 30 | Exported Function
`public: unsigned long __thiscall CTcpMib::SnmpGet(char const *,char const *,struct SnmpVarBindList *)` | 27 | Exported Function
`public: virtual __thiscall CTcpMibABC::~CTcpMibABC(void)` | 6 | Exported Function
`public: virtual __thiscall CTcpMib::~CTcpMib(void)` | 5 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::GetDeviceDescription(char const *,char const *,unsigned long,unsigned short *,unsigned long)` | 11 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::SnmpGet(char const *,char const *,struct AsnObjectIdentifier *,struct SnmpVarBindList *)` | 29 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::SnmpGet(char const *,char const *,char const *,struct SnmpVarBindList *)` | 28 | Exported Function
`public: virtual void __thiscall CTcpMib::UnInitSnmp(void)` | 34 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::SnmpGetNext(char const *,char const *,struct AsnObjectIdentifier *,struct SnmpVarBindList *)` | 31 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::InitSnmp(void)` | 20 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::GetNextRequestId(unsigned long *)` | 15 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::RequestDeviceStatus(void *,unsigned long,unsigned short const *,unsigned short const *,unsigned long)` | 25 | Exported Function
`public: virtual unsigned long __thiscall CTcpMib::RegisterDeviceStatusCallback(unsigned long (__stdcall*)(int,char const *,char const *,unsigned long,unsigned long,unsigned long),void * *)` | 24 | Exported Function
`public: int __thiscall CTcpMib::IsValid(void)const ` | 21 | Exported Function
`private: long __thiscall CTcpMib::GetPortListFromIni(unsigned short const *,unsigned char *,unsigned long,unsigned long *)` | 17 | Exported Function
`private: long __thiscall CTcpMib::GetDeviceIdFromMib(unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long *)` | 14 | Exported Function
`private: long __thiscall CTcpMib::SupportsPortMonMib(unsigned short const *,int *)` | 32 | Exported Function
`private: long __thiscall CTcpMib::GetPortListFromMib(unsigned short const *,unsigned char *,unsigned long,unsigned long *)` | 18 | Exported Function
`const CTcpMibABC::``vftable'` | 10 | Exported Function
`const CTcpMib::``vftable'` | 9 | Exported Function
`private: long __thiscall CTcpMib::GetDeviceIdFromIni(unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long *)` | 13 | Exported Function
`GetTcpMibPtr` | 35 | Exported Function
`private: static int __stdcall CTcpMib::MapAsynchToPortStatus(unsigned long,struct _PORT_INFO_3W *)` | 22 | Exported Function
`public: __thiscall CTcpMibABC::CTcpMibABC(void)` | 4 | Exported Function
`public: __thiscall CTcpMibABC::CTcpMibABC(class CTcpMibABC const &)` | 3 | Exported Function
`public: class CTcpMibABC & __thiscall CTcpMibABC::operator=(class CTcpMibABC const &)` | 8 | Exported Function
`public: class CTcpMib & __thiscall CTcpMib::operator=(class CTcpMib const &)` | 7 | Exported Function
`private: static unsigned long __stdcall CTcpMib::SnmpCallback(void *,struct HWND__ *,unsigned int,unsigned int,long,void *)` | 26 | Exported Function
`private: static unsigned long __stdcall CTcpMib::GetStatusFromVBL(void *,struct smiVALUE *,struct smiVALUE *,struct smiVALUE *)` | 19 | Exported Function
`public: __thiscall CTcpMib::CTcpMib(void)` | 2 | Exported Function
`public: __thiscall CTcpMib::CTcpMib(class CTcpMib const &)` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/46ba5ceb4683594a161e1ff448541c88afe8132e48f98774cc598968aad464ce/detection/





MIT License. Copyright (c) 2020 Strontic.


