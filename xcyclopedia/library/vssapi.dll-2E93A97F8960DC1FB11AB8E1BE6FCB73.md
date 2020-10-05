---
title: vssapi.dll | Microsoft Volume Shadow Copy Requestor/Writer Services API DLL
excerpt: What is vssapi.dll?
---

# vssapi.dll 

* File Path: `C:\Windows\SysWOW64\vssapi.dll`
* Description: Microsoft Volume Shadow Copy Requestor/Writer Services API DLL

## Hashes

Type | Hash
-- | --
MD5 | `2E93A97F8960DC1FB11AB8E1BE6FCB73`
SHA1 | `28C1E6707C92D2AFD0EEEA82593103D60F0B31DA`
SHA256 | `7FAE1F44D444A22FDA069C101416CBFB4DD537053DB6D5B887C944A83CF39CC5`
SHA384 | `D608AEE058FEEF60CAFF4209BCD6F2DB82A59688A9BF1BF4A61508E19A42A4B20D9EADC01A5F5B36572558D34D5938D5`
SHA512 | `F262B7A777E191B76E910504E988D4A565D5F37E9357EB09750B43006EB97921CB925250E06519350B75E67B455EAC0E17ACC88EE35C929C4C19225710414B24`
SSDEEP | `24576:9z3NVVSU6PQkneHnfL2zqsGLmGtrwqhDgrqpdIvXNaYm:d3NXUknT2zqsGLtwqJgmvsNaYm`
IMP | `9841F37A3BF3AD038DEE9388113E2ADE`
PESHA1 | `F3083884FCCBFEE7ADE4490B4BA64524218766EE`
PE256 | `7106446C484D201D4BD62C717F45415569541F2030FE950C64B694EB631309B7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual bool __stdcall CVssJetWriter::OnPostRestoreEnd(class IVssWriterComponents *,bool)` | 55 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPostSnapshot(class IVssWriterComponents *)` | 56 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPostRestoreBegin(class IVssWriterComponents *)` | 54 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnFreezeEnd(bool)` | 50 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnIdentify(class IVssCreateWriterMetadata *)` | 51 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPrepareSnapshotEnd(bool)` | 65 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPreRestoreBegin(class IVssWriterComponents *)` | 59 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPrepareSnapshotBegin(void)` | 64 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPrepareBackupBegin(class IVssWriterComponents *)` | 62 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPrepareBackupEnd(class IVssWriterComponents *,bool)` | 63 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnFreezeBegin(void)` | 49 | Exported Function
`public: long __stdcall CVssWriter::InstallAlternateWriter(struct _GUID,struct _GUID)` | 34 | Exported Function
`public: long __stdcall CVssWriter::Subscribe(unsigned long)` | 72 | Exported Function
`public: long __stdcall CVssWriter::Initialize(struct _GUID,unsigned short const *,enum VSS_USAGE_TYPE,enum VSS_SOURCE_TYPE,enum _VSS_APPLICATION_LEVEL,unsigned long,enum VSS_ALTERNATE_WRITER_STATE,bool,unsigned short const *)` | 33 | Exported Function
`public: __thiscall CVssWriter::CVssWriter(void)` | 9 | Exported Function
`public: long __stdcall CVssJetWriter::Initialize(struct _GUID,unsigned short const *,bool,bool,unsigned short const *,unsigned short const *,unsigned long)` | 32 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnBackupCompleteBegin(class IVssWriterComponents *)` | 45 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnBackupCompleteEnd(class IVssWriterComponents *,bool)` | 46 | Exported Function
`public: virtual __thiscall CVssWriter::~CVssWriter(void)` | 11 | Exported Function
`public: long __stdcall CVssWriter::Unsubscribe(void)` | 74 | Exported Function
`public: virtual __thiscall CVssJetWriter::~CVssJetWriter(void)` | 10 | Exported Function
`public: virtual void __stdcall CVssJetWriter::OnAbortBegin(void)` | 41 | Exported Function
`public: virtual void __stdcall CVssJetWriter::OnAbortEnd(void)` | 42 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnVSSShutdown(void)` | 69 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnPreRestore(class IVssWriterComponents *)` | 58 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnVSSApplicationStartup(void)` | 68 | Exported Function
`VssFreeSnapshotProperties` | 6 | Exported Function
`VssFreeSnapshotPropertiesInternal` | 88 | Exported Function
`ShouldBlockRevertInternal` | 87 | Exported Function
`public: void __stdcall CVssJetWriter::Uninitialize(void)` | 73 | Exported Function
`ShouldBlockRevert` | 7 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnPrepareBackup(class IVssWriterComponents *)` | 61 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnBackOffIOOnVolume(unsigned short *,struct _GUID,struct _GUID)` | 43 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnBackupComplete(class IVssWriterComponents *)` | 44 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnThawEnd(bool)` | 67 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnPreRestoreEnd(class IVssWriterComponents *,bool)` | 60 | Exported Function
`public: virtual bool __stdcall CVssJetWriter::OnThawBegin(void)` | 66 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnPostRestore(class IVssWriterComponents *)` | 53 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnPostSnapshot(class IVssWriterComponents *)` | 57 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnIdentify(class IVssCreateWriterMetadata *)` | 52 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnBackupShutdown(struct _GUID)` | 47 | Exported Function
`public: virtual bool __stdcall CVssWriter::OnContinueIOOnVolume(unsigned short *,struct _GUID,struct _GUID)` | 48 | Exported Function
`long __stdcall CreateVssExamineWriterMetadata(unsigned short *,class IVssExamineWriterMetadata * *)` | 15 | Exported Function
`protected: bool __stdcall CVssJetWriter::AreComponentsSelected(void)const ` | 12 | Exported Function
`long __stdcall CreateVssBackupComponents(class IVssBackupComponents * *)` | 14 | Exported Function
`IsVolumeSnapshottedInternal` | 85 | Exported Function
`LoadVssSnapshotSetDescription` | 86 | Exported Function
`protected: bool __stdcall CVssWriter::AreComponentsSelected(void)const ` | 13 | Exported Function
`protected: bool __stdcall CVssWriter::IsBootableSystemStateBackedUp(void)const ` | 36 | Exported Function
`protected: bool __stdcall CVssJetWriter::IsPathAffected(unsigned short const *)const ` | 39 | Exported Function
`protected: bool __stdcall CVssJetWriter::IsBootableSystemStateBackedUp(void)const ` | 35 | Exported Function
`protected: bool __stdcall CVssJetWriter::IsPartialFileSupportEnabled(void)const ` | 37 | Exported Function
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
`protected: struct _GUID __stdcall CVssJetWriter::GetCurrentSnapshotSetId(void)const ` | 22 | Exported Function
`protected: struct _GUID __stdcall CVssWriter::GetCurrentSnapshotSetId(void)const ` | 23 | Exported Function
`protected: long __stdcall CVssWriter::SetWriterFailure(long)` | 71 | Exported Function
`protected: long __stdcall CVssWriter::GetContext(void)const ` | 19 | Exported Function
`protected: long __stdcall CVssWriter::GetSnapshotDeviceName(unsigned short const *,unsigned short const * *)const ` | 31 | Exported Function
`protected: unsigned short const * * __stdcall CVssWriter::GetCurrentVolumeArray(void)const ` | 25 | Exported Function
`public: __thiscall CVssJetWriter::CVssJetWriter(void)` | 8 | Exported Function
`protected: unsigned short const * * __stdcall CVssJetWriter::GetCurrentVolumeArray(void)const ` | 24 | Exported Function
`protected: unsigned int __stdcall CVssJetWriter::GetCurrentVolumeCount(void)const ` | 26 | Exported Function
`protected: unsigned int __stdcall CVssWriter::GetCurrentVolumeCount(void)const ` | 27 | Exported Function
`protected: long __stdcall CVssJetWriter::SetWriterFailure(long)` | 70 | Exported Function
`protected: enum _VSS_APPLICATION_LEVEL __stdcall CVssWriter::GetCurrentLevel(void)const ` | 21 | Exported Function
`protected: enum _VSS_BACKUP_TYPE __stdcall CVssJetWriter::GetBackupType(void)const ` | 16 | Exported Function
`protected: enum _VSS_APPLICATION_LEVEL __stdcall CVssJetWriter::GetCurrentLevel(void)const ` | 20 | Exported Function
`protected: bool __stdcall CVssWriter::IsPartialFileSupportEnabled(void)const ` | 38 | Exported Function
`protected: bool __stdcall CVssWriter::IsPathAffected(unsigned short const *)const ` | 40 | Exported Function
`protected: long __stdcall CVssJetWriter::GetContext(void)const ` | 18 | Exported Function
`protected: long __stdcall CVssJetWriter::GetSnapshotDeviceName(unsigned short const *,unsigned short const * *)const ` | 30 | Exported Function
`protected: enum _VSS_RESTORE_TYPE __stdcall CVssWriter::GetRestoreType(void)const ` | 29 | Exported Function
`protected: enum _VSS_BACKUP_TYPE __stdcall CVssWriter::GetBackupType(void)const ` | 17 | Exported Function
`protected: enum _VSS_RESTORE_TYPE __stdcall CVssJetWriter::GetRestoreType(void)const ` | 28 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/7fae1f44d444a22fda069c101416cbfb4dd537053db6d5b887c944a83cf39cc5/detection/





MIT License. Copyright (c) 2020 Strontic.


