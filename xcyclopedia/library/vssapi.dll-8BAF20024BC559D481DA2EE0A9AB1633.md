---
title: vssapi.dll | Microsoft Volume Shadow Copy Requestor/Writer Services API DLL
excerpt: What is vssapi.dll?
---

# vssapi.dll 

* File Path: `C:\Windows\system32\vssapi.dll`
* Description: Microsoft Volume Shadow Copy Requestor/Writer Services API DLL

## Hashes

Type | Hash
-- | --
MD5 | `8BAF20024BC559D481DA2EE0A9AB1633`
SHA1 | `6927E2E28BCD3E6967DAB00A611F0DAF7522CD10`
SHA256 | `B855F615114A1294BFD927EFAC262E0DAF388BE4519DC70B1085B1F5028402CF`
SHA384 | `AE7C1050B26DB7D1CFC0DCDA96F7F87D22ED83A3475D59B4168EC480CB261A0DCC4811DF25AB66977BF6857C585852FA`
SHA512 | `CCA8BDE9263C155A5989103306D03C8C0187711F2B45DFC37CEC73ED9B68EC2FF402B12D7D8984D1E1A91A13E371669136F9B670B908D53D2D7FCEB1B57AFEE9`
SSDEEP | `24576:yWeoPPR3Y4xQX2unJ28ne3feOYTRWW1/5qO2QvMIq:0oPZ3zc2kfn8YTR/12gR`
IMP | `54AED0AFBFDD9A06168BDE379CFF799E`
PESHA1 | `3C1CBE71A929735EDB5B2401D8ED1ECF0DC010DD`
PE256 | `51C98F2CB6A9DB2BE46ECA20F6C33E0224DCA24329A36C384AAE57109D3483DB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateVssBackupComponentsInternal` | 75 (0x4b) | Exported Function | 0x0000000180030e30 | 0x00030e30
`public: virtual bool __cdecl CVssJetWriter::OnPrepareSnapshotBegin(void) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180034210 | 0x00034210
`public: virtual bool __cdecl CVssJetWriter::OnPrepareBackupEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180034170 | 0x00034170
`public: virtual bool __cdecl CVssJetWriter::OnPrepareBackupBegin(class IVssWriterComponents * __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x00000001800340e0 | 0x000340e0
`public: virtual bool __cdecl CVssJetWriter::OnPostSnapshot(class IVssWriterComponents * __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x0000000180033f30 | 0x00033f30
`public: virtual bool __cdecl CVssJetWriter::OnPostRestoreEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180033ea0 | 0x00033ea0
`public: virtual bool __cdecl CVssJetWriter::OnPostRestoreBegin(class IVssWriterComponents * __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180033e10 | 0x00033e10
`public: virtual bool __cdecl CVssJetWriter::OnIdentify(class IVssCreateWriterMetadata * __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180033d80 | 0x00033d80
`public: virtual bool __cdecl CVssJetWriter::OnFreezeEnd(bool) __ptr64` | 50 (0x32) | Exported Function | 0x0000000180033ce0 | 0x00033ce0
`public: virtual bool __cdecl CVssJetWriter::OnFreezeBegin(void) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180033c50 | 0x00033c50
`public: virtual bool __cdecl CVssJetWriter::OnBackupCompleteEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180033bc0 | 0x00033bc0
`public: virtual bool __cdecl CVssJetWriter::OnBackupCompleteBegin(class IVssWriterComponents * __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180033b30 | 0x00033b30
`public: virtual __cdecl CVssWriter::~CVssWriter(void) __ptr64` | 11 (0xb) | Exported Function | 0x000000018002d1a0 | 0x0002d1a0
`public: virtual __cdecl CVssJetWriter::~CVssJetWriter(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180032750 | 0x00032750
`public: long __cdecl CVssWriter::Unsubscribe(void) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180030950 | 0x00030950
`public: long __cdecl CVssWriter::Subscribe(unsigned long) __ptr64` | 72 (0x48) | Exported Function | 0x00000001800305f0 | 0x000305f0
`public: long __cdecl CVssWriter::InstallAlternateWriter(struct _GUID,struct _GUID) __ptr64` | 34 (0x22) | Exported Function | 0x000000018002ee80 | 0x0002ee80
`public: long __cdecl CVssWriter::Initialize(struct _GUID,unsigned short const * __ptr64,enum VSS_USAGE_TYPE,enum VSS_SOURCE_TYPE,enum _VSS_APPLICATION_LEVEL,unsigned long,enum VSS_ALTERNATE_WRITER_STATE,bool,unsigned short const * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x000000018002ee10 | 0x0002ee10
`public: virtual bool __cdecl CVssJetWriter::OnPrepareSnapshotEnd(bool) __ptr64` | 65 (0x41) | Exported Function | 0x00000001800342a0 | 0x000342a0
`public: long __cdecl CVssJetWriter::Initialize(struct _GUID,unsigned short const * __ptr64,bool,bool,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180032f90 | 0x00032f90
`public: virtual bool __cdecl CVssJetWriter::OnPreRestoreBegin(class IVssWriterComponents * __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180033fc0 | 0x00033fc0
`public: virtual bool __cdecl CVssJetWriter::OnThawBegin(void) __ptr64` | 66 (0x42) | Exported Function | 0x0000000180034340 | 0x00034340
`ShouldBlockRevertInternal` | 87 (0x57) | Exported Function | 0x000000018002b6a0 | 0x0002b6a0
`ShouldBlockRevert` | 7 (0x7) | Exported Function | 0x000000018002b6a0 | 0x0002b6a0
`public: void __cdecl CVssJetWriter::Uninitialize(void) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180034570 | 0x00034570
`public: virtual void __cdecl CVssJetWriter::OnAbortEnd(void) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180033aa0 | 0x00033aa0
`public: virtual void __cdecl CVssJetWriter::OnAbortBegin(void) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180033a10 | 0x00033a10
`public: virtual bool __cdecl CVssWriter::OnVSSShutdown(void) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnVSSApplicationStartup(void) __ptr64` | 68 (0x44) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnPreRestore(class IVssWriterComponents * __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnPrepareBackup(class IVssWriterComponents * __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnPostSnapshot(class IVssWriterComponents * __ptr64) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnPostRestore(class IVssWriterComponents * __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnIdentify(class IVssCreateWriterMetadata * __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnContinueIOOnVolume(unsigned short * __ptr64,struct _GUID,struct _GUID) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnBackupShutdown(struct _GUID) __ptr64` | 47 (0x2f) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnBackupComplete(class IVssWriterComponents * __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssWriter::OnBackOffIOOnVolume(unsigned short * __ptr64,struct _GUID,struct _GUID) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual bool __cdecl CVssJetWriter::OnThawEnd(bool) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800343d0 | 0x000343d0
`public: virtual bool __cdecl CVssJetWriter::OnPreRestoreEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180034050 | 0x00034050
`public: __cdecl CVssWriter::CVssWriter(void) __ptr64` | 9 (0x9) | Exported Function | 0x000000018002ccf0 | 0x0002ccf0
`public: __cdecl CVssJetWriter::CVssJetWriter(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180032730 | 0x00032730
`protected: unsigned short const * __ptr64 * __ptr64 __cdecl CVssWriter::GetCurrentVolumeArray(void)const __ptr64` | 25 (0x19) | Exported Function | 0x000000018002e040 | 0x0002e040
`protected: bool __cdecl CVssJetWriter::IsPartialFileSupportEnabled(void)const __ptr64` | 37 (0x25) | Exported Function | 0x0000000180033850 | 0x00033850
`protected: bool __cdecl CVssJetWriter::IsBootableSystemStateBackedUp(void)const __ptr64` | 35 (0x23) | Exported Function | 0x0000000180033780 | 0x00033780
`protected: bool __cdecl CVssJetWriter::AreComponentsSelected(void)const __ptr64` | 12 (0xc) | Exported Function | 0x00000001800327f0 | 0x000327f0
`long __cdecl CreateVssExamineWriterMetadata(unsigned short * __ptr64,class IVssExamineWriterMetadata * __ptr64 * __ptr64)` | 15 (0xf) | Exported Function | 0x0000000180031190 | 0x00031190
`long __cdecl CreateVssBackupComponents(class IVssBackupComponents * __ptr64 * __ptr64)` | 14 (0xe) | Exported Function | 0x0000000180030e30 | 0x00030e30
`LoadVssSnapshotSetDescription` | 86 (0x56) | Exported Function | 0x00000001800323c0 | 0x000323c0
`IsVolumeSnapshottedInternal` | 85 (0x55) | Exported Function | 0x0000000180029f70 | 0x00029f70
`IsVolumeSnapshotted` | 5 (0x5) | Exported Function | 0x0000000180029f70 | 0x00029f70
`GetProviderMgmtInterfaceInternal` | 84 (0x54) | Exported Function | 0x0000000180029380 | 0x00029380
`GetProviderMgmtInterface` | 83 (0x53) | Exported Function | 0x0000000180029380 | 0x00029380
`DllGetClassObject` | 82 (0x52) | Exported Function | 0x0000000180029360 | 0x00029360
`DllCanUnloadNow` | 81 (0x51) | Exported Function | 0x0000000180029340 | 0x00029340
`CreateWriterEx` | 80 (0x50) | Exported Function | 0x0000000180014d60 | 0x00014d60
`CreateWriter` | 79 (0x4f) | Exported Function | 0x0000000180002fa0 | 0x00002fa0
`CreateVssSnapshotSetDescription` | 78 (0x4e) | Exported Function | 0x0000000180031be0 | 0x00031be0
`CreateVssExpressWriterInternal` | 77 (0x4d) | Exported Function | 0x0000000180031740 | 0x00031740
`CreateVssExamineWriterMetadataInternal` | 76 (0x4c) | Exported Function | 0x0000000180031190 | 0x00031190
`protected: bool __cdecl CVssJetWriter::IsPathAffected(unsigned short const * __ptr64)const __ptr64` | 39 (0x27) | Exported Function | 0x0000000180033920 | 0x00033920
`protected: bool __cdecl CVssWriter::AreComponentsSelected(void)const __ptr64` | 13 (0xd) | Exported Function | 0x000000018002d750 | 0x0002d750
`protected: bool __cdecl CVssWriter::IsBootableSystemStateBackedUp(void)const __ptr64` | 36 (0x24) | Exported Function | 0x000000018002efa0 | 0x0002efa0
`protected: bool __cdecl CVssWriter::IsPartialFileSupportEnabled(void)const __ptr64` | 38 (0x26) | Exported Function | 0x000000018002efd0 | 0x0002efd0
`protected: unsigned short const * __ptr64 * __ptr64 __cdecl CVssJetWriter::GetCurrentVolumeArray(void)const __ptr64` | 24 (0x18) | Exported Function | 0x0000000180032c20 | 0x00032c20
`protected: unsigned int __cdecl CVssWriter::GetCurrentVolumeCount(void)const __ptr64` | 27 (0x1b) | Exported Function | 0x000000018002e070 | 0x0002e070
`protected: unsigned int __cdecl CVssJetWriter::GetCurrentVolumeCount(void)const __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180032cf0 | 0x00032cf0
`protected: struct _GUID __cdecl CVssWriter::GetCurrentSnapshotSetId(void)const __ptr64` | 23 (0x17) | Exported Function | 0x000000018002dff0 | 0x0002dff0
`protected: struct _GUID __cdecl CVssJetWriter::GetCurrentSnapshotSetId(void)const __ptr64` | 22 (0x16) | Exported Function | 0x0000000180032b30 | 0x00032b30
`protected: long __cdecl CVssWriter::SetWriterFailure(long) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180030330 | 0x00030330
`protected: long __cdecl CVssWriter::GetSnapshotDeviceName(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64)const __ptr64` | 31 (0x1f) | Exported Function | 0x000000018002e760 | 0x0002e760
`protected: long __cdecl CVssWriter::GetContext(void)const __ptr64` | 19 (0x13) | Exported Function | 0x000000018002ddf0 | 0x0002ddf0
`VssFreeSnapshotProperties` | 6 (0x6) | Exported Function | 0x000000018002c740 | 0x0002c740
`protected: long __cdecl CVssJetWriter::SetWriterFailure(long) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180034470 | 0x00034470
`protected: long __cdecl CVssJetWriter::GetContext(void)const __ptr64` | 18 (0x12) | Exported Function | 0x0000000180032990 | 0x00032990
`protected: enum _VSS_RESTORE_TYPE __cdecl CVssWriter::GetRestoreType(void)const __ptr64` | 29 (0x1d) | Exported Function | 0x000000018002e6f0 | 0x0002e6f0
`protected: enum _VSS_RESTORE_TYPE __cdecl CVssJetWriter::GetRestoreType(void)const __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180032dc0 | 0x00032dc0
`protected: enum _VSS_BACKUP_TYPE __cdecl CVssWriter::GetBackupType(void)const __ptr64` | 17 (0x11) | Exported Function | 0x000000018002ddc0 | 0x0002ddc0
`protected: enum _VSS_BACKUP_TYPE __cdecl CVssJetWriter::GetBackupType(void)const __ptr64` | 16 (0x10) | Exported Function | 0x00000001800328c0 | 0x000328c0
`protected: enum _VSS_APPLICATION_LEVEL __cdecl CVssWriter::GetCurrentLevel(void)const __ptr64` | 21 (0x15) | Exported Function | 0x000000018002df60 | 0x0002df60
`protected: enum _VSS_APPLICATION_LEVEL __cdecl CVssJetWriter::GetCurrentLevel(void)const __ptr64` | 20 (0x14) | Exported Function | 0x0000000180032a60 | 0x00032a60
`protected: bool __cdecl CVssWriter::IsPathAffected(unsigned short const * __ptr64)const __ptr64` | 40 (0x28) | Exported Function | 0x000000018002efe0 | 0x0002efe0
`protected: long __cdecl CVssJetWriter::GetSnapshotDeviceName(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64)const __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180032e90 | 0x00032e90
`VssFreeSnapshotPropertiesInternal` | 88 (0x58) | Exported Function | 0x000000018002c740 | 0x0002c740


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSAPI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b855f615114a1294bfd927efac262e0daf388be4519dc70b1085b1f5028402cf/detection/





MIT License. Copyright (c) 2020 Strontic.


