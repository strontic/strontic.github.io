---
title: bitsperf.dll | Perfmon Counter Access
excerpt: What is bitsperf.dll?
---

# bitsperf.dll 

* File Path: `C:\Windows\SysWOW64\bitsperf.dll`
* Description: Perfmon Counter Access

## Hashes

Type | Hash
-- | --
MD5 | `82CA769F90474D5193ABD865D12BE7ED`
SHA1 | `41928814DB8F3B5EAA437816FAFFF69B5F2EA6CB`
SHA256 | `937A83A1D023AD6CAE7C3D9677C7C33CF8F5F7AFA3B263C17E1BB6409E06A5D2`
SHA384 | `34F3351155A050A34E805A13C3A05FC2BDDE86DDFE993B4096D552ADB0956D76ECE5CEE43EA08F183F1C01F30546929F`
SHA512 | `4948BD414A8C6FA4AABBB9FF93FC3DE97FAB7801F0728E1209D2A9D2D5F3618F14842CAEA82E93D68EEB989ABD8C7A6F20FC6E78644EFF86AF1D3180D0E8D49F`
SSDEEP | `768:VrfH5teup/XrZOA2jlX3YGB9X7/EKm4fTx/LzUmrI:VrSuBrZMjlX30ITxUmrI`
IMP | `ECADF0428408BA7CD17471037A52CF50`
PESHA1 | `ADF72EEE1438542F96C2F34DF75387798C89C4A5`
PE256 | `2A437AA862915A73C0ED33ED8DF7A3CAA4E9690AA45ACDD9144FCA32657FE597`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`PerfMon_Close` | 30 (0x1e) | Exported Function | 0x100044f0 | 0x000044f0
`public: long * __thiscall CPerfMon::GetCounter32(struct CPerfMon::__COUNTER_ID *,struct CPerfMon::__INSTANCE_ID *)` | 15 (0xf) | Exported Function | 0x10004410 | 0x00004410
`public: class CPerfMon & __thiscall CPerfMon::operator=(class CPerfMon const &)` | 3 (0x3) | Exported Function | 0x100043a0 | 0x000043a0
`public: __thiscall CPerfMon::~CPerfMon(void)` | 2 (0x2) | Exported Function | 0x10002fc0 | 0x00002fc0
`public: __thiscall CPerfMon::CPerfMon(unsigned short *,struct CPerfMon::_PERF_ITEM *)` | 1 (0x1) | Exported Function | 0x10003170 | 0x00003170
`public: __int64 * __thiscall CPerfMon::GetCounter64(struct CPerfMon::__COUNTER_ID *,struct CPerfMon::__INSTANCE_ID *)` | 16 (0x10) | Exported Function | 0x10004410 | 0x00004410
`private: void __thiscall CPerfMon::DetermineObjectsToCollect(struct CPerfMon::__OBJECT_ORD *)const ` | 14 (0xe) | Exported Function | 0x10004d40 | 0x00004d40
`private: void __thiscall CPerfMon::CalcPerfMetrics(struct CPerfMon::__OBJECT_ORD *,struct CPerfMon::__INSTANCE_ID *,struct CPerfMon::_PERF_METRICS *,struct CPerfMon::_PERF_ITEM * *)const ` | 5 (0x5) | Exported Function | 0x10003210 | 0x00003210
`private: unsigned long __thiscall CPerfMon::VerifyPerfItemTable(void)` | 29 (0x1d) | Exported Function | 0x10002c70 | 0x00002c70
`private: unsigned long __thiscall CPerfMon::InitializePerfMon(int)` | 21 (0x15) | Exported Function | 0x10001f80 | 0x00001f80
`private: unsigned long __thiscall CPerfMon::CollectAnObject(struct CPerfMon::__OBJECT_ORD *,unsigned char * *)const ` | 8 (0x8) | Exported Function | 0x100049f0 | 0x000049f0
`private: unsigned long __thiscall CPerfMon::CollectAllObjects(unsigned short *,unsigned char * *,unsigned long *,unsigned long *)const ` | 7 (0x7) | Exported Function | 0x10004840 | 0x00004840
`private: unsigned long __thiscall CPerfMon::CalcBytesForPerfObject(struct CPerfMon::__OBJECT_ORD *)const ` | 4 (0x4) | Exported Function | 0x10004750 | 0x00004750
`private: unsigned char * __thiscall CPerfMon::GetCounter(struct CPerfMon::__COUNTER_ID *,struct CPerfMon::__INSTANCE_ID *)` | 17 (0x11) | Exported Function | 0x10004df0 | 0x00004df0
`private: struct CPerfMon::_PERF_ITEM * __thiscall CPerfMon::ObjectOrdToPerfItem(struct CPerfMon::__OBJECT_ORD *)const ` | 27 (0x1b) | Exported Function | 0x10005030 | 0x00005030
`private: struct CPerfMon::_PERF_ITEM * __thiscall CPerfMon::ObjectIdToPerfItem(struct CPerfMon::__OBJECT_ID *)const ` | 25 (0x19) | Exported Function | 0x100044a0 | 0x000044a0
`private: struct CPerfMon::_PERF_ITEM * __thiscall CPerfMon::CounterOrdToPerfItem(struct CPerfMon::__OBJECT_ORD *,struct CPerfMon::__COUNTER_ORD *)const ` | 13 (0xd) | Exported Function | 0x10004d10 | 0x00004d10
`private: struct CPerfMon::_PERF_ITEM * __thiscall CPerfMon::CounterIdToPerfItem(struct CPerfMon::__COUNTER_ID *)const ` | 11 (0xb) | Exported Function | 0x100043e0 | 0x000043e0
`private: struct CPerfMon::__OBJECT_ORD * __thiscall CPerfMon::ObjectIdToObjectOrd(struct CPerfMon::__OBJECT_ID *)const ` | 24 (0x18) | Exported Function | 0x10004fb0 | 0x00004fb0
`private: struct CPerfMon::__OBJECT_ORD * __thiscall CPerfMon::CounterIdToObjectOrd(struct CPerfMon::__COUNTER_ID *,int *)const ` | 10 (0xa) | Exported Function | 0x10004c60 | 0x00004c60
`private: int __thiscall CPerfMon::ObjectOrdToPerfItemIndex(struct CPerfMon::__OBJECT_ORD *)const ` | 28 (0x1c) | Exported Function | 0x10005060 | 0x00005060
`private: int __thiscall CPerfMon::ObjectIdToPerfItemIndex(struct CPerfMon::__OBJECT_ID *)const ` | 26 (0x1a) | Exported Function | 0x100044d0 | 0x000044d0
`private: int __thiscall CPerfMon::IsValidObjOrd(struct CPerfMon::__OBJECT_ORD *)const ` | 23 (0x17) | Exported Function | 0x10004480 | 0x00004480
`private: int __thiscall CPerfMon::IsValidInstId(struct CPerfMon::__OBJECT_ORD *,struct CPerfMon::__INSTANCE_ID *)const ` | 22 (0x16) | Exported Function | 0x10004420 | 0x00004420
`private: int __thiscall CPerfMon::IdToPerfItemIndex(int,unsigned long)const ` | 19 (0x13) | Exported Function | 0x10003370 | 0x00003370
`private: int __thiscall CPerfMon::HowManyInstancesAreInUse(struct CPerfMon::__OBJECT_ORD *)const ` | 18 (0x12) | Exported Function | 0x10004e70 | 0x00004e70
`private: int __thiscall CPerfMon::CounterIdToPerfItemIndex(struct CPerfMon::__COUNTER_ID *,int *)const ` | 12 (0xc) | Exported Function | 0x10004cb0 | 0x00004cb0
`private: int __thiscall CPerfMon::ConvertInstIdToInUseInstId(struct CPerfMon::__OBJECT_ORD *,struct CPerfMon::__INSTANCE_ID *)const ` | 9 (0x9) | Exported Function | 0x10004be0 | 0x00004be0
`PerfMon_Open` | 32 (0x20) | Exported Function | 0x10004540 | 0x00004540
`PerfMon_Collect` | 31 (0x1f) | Exported Function | 0x10004520 | 0x00004520
`public: unsigned long __thiscall CPerfMon::Collect(unsigned short *,unsigned char * *,unsigned long *,unsigned long *)` | 6 (0x6) | Exported Function | 0x10004830 | 0x00004830
`public: unsigned long __thiscall CPerfMon::Initialize(int)` | 20 (0x14) | Exported Function | 0x10001f30 | 0x00001f30


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/937a83a1d023ad6cae7c3d9677c7c33cf8f5f7afa3b263c17e1bb6409e06a5d2/detection/





MIT License. Copyright (c) 2020 Strontic.


