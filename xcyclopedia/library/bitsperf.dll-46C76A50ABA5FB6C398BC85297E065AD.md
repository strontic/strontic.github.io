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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`PerfMon_Close` | 30 (0x1e) | Exported Function | 0x00000001800024c0 | 0x000024c0
`public: long * __ptr64 __cdecl CPerfMon::GetCounter32(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x00000001800023b0 | 0x000023b0
`public: class CPerfMon & __ptr64 __cdecl CPerfMon::operator=(class CPerfMon const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180002310 | 0x00002310
`public: __int64 * __ptr64 __cdecl CPerfMon::GetCounter64(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800023b0 | 0x000023b0
`public: __cdecl CPerfMon::~CPerfMon(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001010 | 0x00001010
`public: __cdecl CPerfMon::CPerfMon(unsigned short * __ptr64,struct CPerfMon::_PERF_ITEM * __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180002890 | 0x00002890
`private: void __cdecl CPerfMon::DetermineObjectsToCollect(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 14 (0xe) | Exported Function | 0x0000000180003190 | 0x00003190
`private: void __cdecl CPerfMon::CalcPerfMetrics(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64,struct CPerfMon::_PERF_METRICS * __ptr64,struct CPerfMon::_PERF_ITEM * __ptr64 * __ptr64)const __ptr64` | 5 (0x5) | Exported Function | 0x0000000180002a10 | 0x00002a10
`private: unsigned long __cdecl CPerfMon::VerifyPerfItemTable(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180004220 | 0x00004220
`private: unsigned long __cdecl CPerfMon::InitializePerfMon(int) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180003500 | 0x00003500
`private: unsigned long __cdecl CPerfMon::CollectAnObject(struct CPerfMon::__OBJECT_ORD * __ptr64,unsigned char * __ptr64 * __ptr64)const __ptr64` | 8 (0x8) | Exported Function | 0x0000000180002da0 | 0x00002da0
`private: unsigned long __cdecl CPerfMon::CollectAllObjects(unsigned short * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64)const __ptr64` | 7 (0x7) | Exported Function | 0x0000000180002bc0 | 0x00002bc0
`private: unsigned long __cdecl CPerfMon::CalcBytesForPerfObject(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 4 (0x4) | Exported Function | 0x00000001800028f0 | 0x000028f0
`private: unsigned char * __ptr64 __cdecl CPerfMon::GetCounter(struct CPerfMon::__COUNTER_ID * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180003290 | 0x00003290
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::ObjectOrdToPerfItem(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180004140 | 0x00004140
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::ObjectIdToPerfItem(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 25 (0x19) | Exported Function | 0x0000000180002470 | 0x00002470
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::CounterOrdToPerfItem(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__COUNTER_ORD * __ptr64)const __ptr64` | 13 (0xd) | Exported Function | 0x0000000180003150 | 0x00003150
`private: struct CPerfMon::_PERF_ITEM * __ptr64 __cdecl CPerfMon::CounterIdToPerfItem(struct CPerfMon::__COUNTER_ID * __ptr64)const __ptr64` | 11 (0xb) | Exported Function | 0x0000000180002380 | 0x00002380
`private: struct CPerfMon::__OBJECT_ORD * __ptr64 __cdecl CPerfMon::ObjectIdToObjectOrd(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 24 (0x18) | Exported Function | 0x00000001800040a0 | 0x000040a0
`private: struct CPerfMon::__OBJECT_ORD * __ptr64 __cdecl CPerfMon::CounterIdToObjectOrd(struct CPerfMon::__COUNTER_ID * __ptr64,int * __ptr64)const __ptr64` | 10 (0xa) | Exported Function | 0x0000000180003080 | 0x00003080
`private: int __cdecl CPerfMon::ObjectOrdToPerfItemIndex(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180004170 | 0x00004170
`private: int __cdecl CPerfMon::ObjectIdToPerfItemIndex(struct CPerfMon::__OBJECT_ID * __ptr64)const __ptr64` | 26 (0x1a) | Exported Function | 0x00000001800024a0 | 0x000024a0
`private: int __cdecl CPerfMon::IsValidObjOrd(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 23 (0x17) | Exported Function | 0x0000000180002450 | 0x00002450
`private: int __cdecl CPerfMon::IsValidInstId(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64)const __ptr64` | 22 (0x16) | Exported Function | 0x00000001800023c0 | 0x000023c0
`private: int __cdecl CPerfMon::IdToPerfItemIndex(int,unsigned __int64)const __ptr64` | 19 (0x13) | Exported Function | 0x0000000180003400 | 0x00003400
`private: int __cdecl CPerfMon::HowManyInstancesAreInUse(struct CPerfMon::__OBJECT_ORD * __ptr64)const __ptr64` | 18 (0x12) | Exported Function | 0x0000000180003350 | 0x00003350
`private: int __cdecl CPerfMon::CounterIdToPerfItemIndex(struct CPerfMon::__COUNTER_ID * __ptr64,int * __ptr64)const __ptr64` | 12 (0xc) | Exported Function | 0x00000001800030e0 | 0x000030e0
`private: int __cdecl CPerfMon::ConvertInstIdToInUseInstId(struct CPerfMon::__OBJECT_ORD * __ptr64,struct CPerfMon::__INSTANCE_ID * __ptr64)const __ptr64` | 9 (0x9) | Exported Function | 0x0000000180002fd0 | 0x00002fd0
`PerfMon_Open` | 32 (0x20) | Exported Function | 0x0000000180002520 | 0x00002520
`PerfMon_Collect` | 31 (0x1f) | Exported Function | 0x00000001800024f0 | 0x000024f0
`public: unsigned long __cdecl CPerfMon::Collect(unsigned short * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180002bb0 | 0x00002bb0
`public: unsigned long __cdecl CPerfMon::Initialize(int) __ptr64` | 20 (0x14) | Exported Function | 0x00000001800034b0 | 0x000034b0


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


