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

Function Name | Ordinal | Type
-- | -- | --
`public: virtual bool __cdecl CVssJetWriter::OnPostRestoreEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 55 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPostSnapshot(class IVssWriterComponents * __ptr64) __ptr64` | 56 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPostRestoreBegin(class IVssWriterComponents * __ptr64) __ptr64` | 54 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnFreezeEnd(bool) __ptr64` | 50 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnIdentify(class IVssCreateWriterMetadata * __ptr64) __ptr64` | 51 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPrepareSnapshotEnd(bool) __ptr64` | 65 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPreRestoreBegin(class IVssWriterComponents * __ptr64) __ptr64` | 59 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPrepareSnapshotBegin(void) __ptr64` | 64 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPrepareBackupBegin(class IVssWriterComponents * __ptr64) __ptr64` | 62 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPrepareBackupEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 63 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnFreezeBegin(void) __ptr64` | 49 | Exported Function
`public: long __cdecl CVssWriter::InstallAlternateWriter(struct _GUID,struct _GUID) __ptr64` | 34 | Exported Function
`public: long __cdecl CVssWriter::Subscribe(unsigned long) __ptr64` | 72 | Exported Function
`public: long __cdecl CVssWriter::Initialize(struct _GUID,unsigned short const * __ptr64,enum VSS_USAGE_TYPE,enum VSS_SOURCE_TYPE,enum _VSS_APPLICATION_LEVEL,unsigned long,enum VSS_ALTERNATE_WRITER_STATE,bool,unsigned short const * __ptr64) __ptr64` | 33 | Exported Function
`public: __cdecl CVssWriter::CVssWriter(void) __ptr64` | 9 | Exported Function
`public: long __cdecl CVssJetWriter::Initialize(struct _GUID,unsigned short const * __ptr64,bool,bool,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 32 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnBackupCompleteBegin(class IVssWriterComponents * __ptr64) __ptr64` | 45 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnBackupCompleteEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 46 | Exported Function
`public: virtual __cdecl CVssWriter::~CVssWriter(void) __ptr64` | 11 | Exported Function
`public: long __cdecl CVssWriter::Unsubscribe(void) __ptr64` | 74 | Exported Function
`public: virtual __cdecl CVssJetWriter::~CVssJetWriter(void) __ptr64` | 10 | Exported Function
`public: virtual void __cdecl CVssJetWriter::OnAbortBegin(void) __ptr64` | 41 | Exported Function
`public: virtual void __cdecl CVssJetWriter::OnAbortEnd(void) __ptr64` | 42 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnVSSShutdown(void) __ptr64` | 69 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnPreRestore(class IVssWriterComponents * __ptr64) __ptr64` | 58 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnVSSApplicationStartup(void) __ptr64` | 68 | Exported Function
`VssFreeSnapshotProperties` | 6 | Exported Function
`VssFreeSnapshotPropertiesInternal` | 88 | Exported Function
`ShouldBlockRevertInternal` | 87 | Exported Function
`public: void __cdecl CVssJetWriter::Uninitialize(void) __ptr64` | 73 | Exported Function
`ShouldBlockRevert` | 7 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnPrepareBackup(class IVssWriterComponents * __ptr64) __ptr64` | 61 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnBackOffIOOnVolume(unsigned short * __ptr64,struct _GUID,struct _GUID) __ptr64` | 43 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnBackupComplete(class IVssWriterComponents * __ptr64) __ptr64` | 44 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnThawEnd(bool) __ptr64` | 67 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnPreRestoreEnd(class IVssWriterComponents * __ptr64,bool) __ptr64` | 60 | Exported Function
`public: virtual bool __cdecl CVssJetWriter::OnThawBegin(void) __ptr64` | 66 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnPostRestore(class IVssWriterComponents * __ptr64) __ptr64` | 53 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnPostSnapshot(class IVssWriterComponents * __ptr64) __ptr64` | 57 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnIdentify(class IVssCreateWriterMetadata * __ptr64) __ptr64` | 52 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnBackupShutdown(struct _GUID) __ptr64` | 47 | Exported Function
`public: virtual bool __cdecl CVssWriter::OnContinueIOOnVolume(unsigned short * __ptr64,struct _GUID,struct _GUID) __ptr64` | 48 | Exported Function
`long __cdecl CreateVssExamineWriterMetadata(unsigned short * __ptr64,class IVssExamineWriterMetadata * __ptr64 * __ptr64)` | 15 | Exported Function
`protected: bool __cdecl CVssJetWriter::AreComponentsSelected(void)const __ptr64` | 12 | Exported Function
`long __cdecl CreateVssBackupComponents(class IVssBackupComponents * __ptr64 * __ptr64)` | 14 | Exported Function
`IsVolumeSnapshottedInternal` | 85 | Exported Function
`LoadVssSnapshotSetDescription` | 86 | Exported Function
`protected: bool __cdecl CVssWriter::AreComponentsSelected(void)const __ptr64` | 13 | Exported Function
`protected: bool __cdecl CVssWriter::IsBootableSystemStateBackedUp(void)const __ptr64` | 36 | Exported Function
`protected: bool __cdecl CVssJetWriter::IsPathAffected(unsigned short const * __ptr64)const __ptr64` | 39 | Exported Function
`protected: bool __cdecl CVssJetWriter::IsBootableSystemStateBackedUp(void)const __ptr64` | 35 | Exported Function
`protected: bool __cdecl CVssJetWriter::IsPartialFileSupportEnabled(void)const __ptr64` | 37 | Exported Function
`IsVolumeSnapshotted` | 5 | Exported Function
`CreateVssSnapshotSetDescription` | 78 | Exported Function
`CreateWriter` | 79 | Exported Function
`CreateVssExpressWriterInternal` | 77 | Exported Function
`CreateVssBackupComponentsInternal` | 75 | Exported Function
`CreateVssExamineWriterMetadataInternal` | 76 | Exported Function
`GetProviderMgmtInterface` | 83 | Exported Function
`GetProviderMgmtInterfaceInternal` | 84 | Exported Function
`DllGetClassObject` | 82 | Exported Function
`CreateWriterEx` | 80 | Exported Function
`DllCanUnloadNow` | 81 | Exported Function
`protected: struct _GUID __cdecl CVssJetWriter::GetCurrentSnapshotSetId(void)const __ptr64` | 22 | Exported Function
`protected: struct _GUID __cdecl CVssWriter::GetCurrentSnapshotSetId(void)const __ptr64` | 23 | Exported Function
`protected: long __cdecl CVssWriter::SetWriterFailure(long) __ptr64` | 71 | Exported Function
`protected: long __cdecl CVssWriter::GetContext(void)const __ptr64` | 19 | Exported Function
`protected: long __cdecl CVssWriter::GetSnapshotDeviceName(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64)const __ptr64` | 31 | Exported Function
`protected: unsigned short const * __ptr64 * __ptr64 __cdecl CVssWriter::GetCurrentVolumeArray(void)const __ptr64` | 25 | Exported Function
`public: __cdecl CVssJetWriter::CVssJetWriter(void) __ptr64` | 8 | Exported Function
`protected: unsigned short const * __ptr64 * __ptr64 __cdecl CVssJetWriter::GetCurrentVolumeArray(void)const __ptr64` | 24 | Exported Function
`protected: unsigned int __cdecl CVssJetWriter::GetCurrentVolumeCount(void)const __ptr64` | 26 | Exported Function
`protected: unsigned int __cdecl CVssWriter::GetCurrentVolumeCount(void)const __ptr64` | 27 | Exported Function
`protected: long __cdecl CVssJetWriter::SetWriterFailure(long) __ptr64` | 70 | Exported Function
`protected: enum _VSS_APPLICATION_LEVEL __cdecl CVssWriter::GetCurrentLevel(void)const __ptr64` | 21 | Exported Function
`protected: enum _VSS_BACKUP_TYPE __cdecl CVssJetWriter::GetBackupType(void)const __ptr64` | 16 | Exported Function
`protected: enum _VSS_APPLICATION_LEVEL __cdecl CVssJetWriter::GetCurrentLevel(void)const __ptr64` | 20 | Exported Function
`protected: bool __cdecl CVssWriter::IsPartialFileSupportEnabled(void)const __ptr64` | 38 | Exported Function
`protected: bool __cdecl CVssWriter::IsPathAffected(unsigned short const * __ptr64)const __ptr64` | 40 | Exported Function
`protected: long __cdecl CVssJetWriter::GetContext(void)const __ptr64` | 18 | Exported Function
`protected: long __cdecl CVssJetWriter::GetSnapshotDeviceName(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64)const __ptr64` | 30 | Exported Function
`protected: enum _VSS_RESTORE_TYPE __cdecl CVssWriter::GetRestoreType(void)const __ptr64` | 29 | Exported Function
`protected: enum _VSS_BACKUP_TYPE __cdecl CVssWriter::GetBackupType(void)const __ptr64` | 17 | Exported Function
`protected: enum _VSS_RESTORE_TYPE __cdecl CVssJetWriter::GetRestoreType(void)const __ptr64` | 28 | Exported Function


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


