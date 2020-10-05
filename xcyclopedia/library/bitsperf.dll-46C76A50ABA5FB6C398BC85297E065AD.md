---
title: bitsperf.dll | Perfmon Counter Access
excerpt: What is bitsperf.dll?
---

# bitsperf.dll 

* File Path: `C:\Windows\system32\bitsperf.dll`
* Description: Perfmon Counter Access

## Hashes

Type | Hash
-- | --
MD5 | `46C76A50ABA5FB6C398BC85297E065AD`
SHA1 | `B0D01ECCBB00DD0CFD28AA7DFA4052F5289CFAD2`
SHA256 | `2553CF125F93610ED057307486B8B07A9B3924E61981EB536B41441688EF14B0`
SHA384 | `8E693C1FC396208600A89D47233E7C586C6C12314DD33F54A129AB7EEF359BB504003D363EEB44B88C356ABA5AD8CEF9`
SHA512 | `F19F02AE54177063A6F09DC9EB55E109779BD93B39B026ECEDBC1470613765D4BB7BEEBC1A8B1F9A1AA0FF01185BF4E33E112F2DD9A7566AFDB940F0B4F40973`
SSDEEP | `384:vQHevBhKveWvCbrx8LNr8PVLgXqXtnAjRgejA5kOTjdRxenHptgH7EZv5L6SYE7s:vRhKv+bXgXlGbhjdRsnHptLZk9+mr7X`
IMP | `9693B61EB765F62EEB39D42FFDD19508`
PESHA1 | `B0AB8684957F3535AEB75E865568062657783DF7`
PE256 | `D05232981031DF9ACB82CC12394E753186EDF3A62D15E89000B749BFABECCBB6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`private: unsigned long __cdecl CPerfMon::InitializePerfMon(int) __ptr64` | 21 | Exported Function
`private: unsigned long __cdecl CPerfMon::CollectAnObject(struct CPerfMon::__OBJECT_ORD * __ptr64,unsigned char * __ptr64 * __ptr64)const __ptr64` | 8 | Exported Function
`private: void __cdecl CPerfMon::CalcPerfMetrics(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64,struct CPerfMon::_PERF_METRICS * __ptr64,struct CPerfMon::_PERF_ITEM * __ptr64 * __ptr64)const __ptr64` | 5 | Exported Function
`private: unsigned long __cdecl CPerfMon::VerifyPerfItemTable(void) __ptr64` | 29 | Exported Function
`private: unsigned char * __ptr64 __cdecl CPerfMon::GetCounter(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 17 | Exported Function
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::ObjectOrdToPerfItem(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 27 | Exported Function
`private: unsigned long __cdecl CPerfMon::CollectAllObjects(unsigned short * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64)const __ptr64` | 7 | Exported Function
`private: unsigned long __cdecl CPerfMon::CalcBytesForPerfObject(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 4 | Exported Function
`public: long * __ptr64 __cdecl CPerfMon::GetCounter32(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 15 | Exported Function
`public: class CPerfMon & __ptr64 __cdecl CPerfMon::operator=(class CPerfMon const & __ptr64) __ptr64` | 3 | Exported Function
`public: unsigned long __cdecl CPerfMon::Initialize(int) __ptr64` | 20 | Exported Function
`public: unsigned long __cdecl CPerfMon::Collect(unsigned short * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 6 | Exported Function
`public: __cdecl CPerfMon::CPerfMon(unsigned short * __ptr64,struct CPerfMon::_PERF_ITEM * __ptr64) __ptr64` | 1 | Exported Function
`private: void __cdecl CPerfMon::DetermineObjectsToCollect(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 14 | Exported Function
`public: __int64 * __ptr64 __cdecl CPerfMon::GetCounter64(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 16 | Exported Function
`public: __cdecl CPerfMon::~CPerfMon(void) __ptr64` | 2 | Exported Function
`private: int __cdecl CPerfMon::HowManyInstancesAreInUse(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 18 | Exported Function
`private: int __cdecl CPerfMon::CounterIdToPerfItemIndex(struct CPerfMon::__COUNTER_ID * __ptr64,int * __ptr64)const __ptr64` | 12 | Exported Function
`private: int __cdecl CPerfMon::IsValidInstId(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64)const __ptr64` | 22 | Exported Function
`private: int __cdecl CPerfMon::IdToPerfItemIndex(int,unsigned __int64)const __ptr64` | 19 | Exported Function
`PerfMon_Collect` | 31 | Exported Function
`PerfMon_Close` | 30 | Exported Function
`private: int __cdecl CPerfMon::ConvertInstIdToInUseInstId(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64)const __ptr64` | 9 | Exported Function
`PerfMon_Open` | 32 | Exported Function
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::CounterIdToPerfItem(struct CPerfMon::__COUNTER_ID * __ptr64)const __ptr64` | 11 | Exported Function
`private: struct CPerfMon::__OBJECT_ORD * __ptr64 __cdecl CPerfMon::ObjectIdToObjectOrd(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 24 | Exported Function
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::ObjectIdToPerfItem(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 25 | Exported Function
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::CounterOrdToPerfItem(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__COUNTER_ORD * __ptr64)const __ptr64` | 13 | Exported Function
`private: int __cdecl CPerfMon::ObjectIdToPerfItemIndex(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 26 | Exported Function
`private: int __cdecl CPerfMon::IsValidObjOrd(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 23 | Exported Function
`private: struct CPerfMon::__OBJECT_ORD * __ptr64 __cdecl CPerfMon::CounterIdToObjectOrd(struct CPerfMon::__COUNTER_ID * __ptr64,int * __ptr64)const __ptr64` | 10 | Exported Function
`private: int __cdecl CPerfMon::ObjectOrdToPerfItemIndex(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 28 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BitsPerf.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 7.8.19041.1 (WinBuild.160101.0800)
* Product Version: 7.8.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/2553cf125f93610ed057307486b8b07a9b3924e61981eb536b41441688ef14b0/detection/





MIT License. Copyright (c) 2020 Strontic.


