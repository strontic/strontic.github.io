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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateVssBackupComponentsInternal` | 75 (0x4b) | Exported Function | 0x1005b3c0 | 0x0005b3c0
`public: virtual bool __stdcall CVssJetWriter::OnPrepareSnapshotBegin(void)` | 64 (0x40) | Exported Function | 0x1005cdb0 | 0x0005cdb0
`public: virtual bool __stdcall CVssJetWriter::OnPrepareBackupEnd(class IVssWriterComponents *,bool)` | 63 (0x3f) | Exported Function | 0x1005cd60 | 0x0005cd60
`public: virtual bool __stdcall CVssJetWriter::OnPrepareBackupBegin(class IVssWriterComponents *)` | 62 (0x3e) | Exported Function | 0x1005cd10 | 0x0005cd10
`public: virtual bool __stdcall CVssJetWriter::OnPostSnapshot(class IVssWriterComponents *)` | 56 (0x38) | Exported Function | 0x1005cc20 | 0x0005cc20
`public: virtual bool __stdcall CVssJetWriter::OnPostRestoreEnd(class IVssWriterComponents *,bool)` | 55 (0x37) | Exported Function | 0x1005cbd0 | 0x0005cbd0
`public: virtual bool __stdcall CVssJetWriter::OnPostRestoreBegin(class IVssWriterComponents *)` | 54 (0x36) | Exported Function | 0x1005cb80 | 0x0005cb80
`public: virtual bool __stdcall CVssJetWriter::OnIdentify(class IVssCreateWriterMetadata *)` | 51 (0x33) | Exported Function | 0x1005cb30 | 0x0005cb30
`public: virtual bool __stdcall CVssJetWriter::OnFreezeEnd(bool)` | 50 (0x32) | Exported Function | 0x1005cae0 | 0x0005cae0
`public: virtual bool __stdcall CVssJetWriter::OnFreezeBegin(void)` | 49 (0x31) | Exported Function | 0x1005ca90 | 0x0005ca90
`public: virtual bool __stdcall CVssJetWriter::OnBackupCompleteEnd(class IVssWriterComponents *,bool)` | 46 (0x2e) | Exported Function | 0x1005ca40 | 0x0005ca40
`public: virtual bool __stdcall CVssJetWriter::OnBackupCompleteBegin(class IVssWriterComponents *)` | 45 (0x2d) | Exported Function | 0x1005c9f0 | 0x0005c9f0
`public: virtual __thiscall CVssWriter::~CVssWriter(void)` | 11 (0xb) | Exported Function | 0x10058570 | 0x00058570
`public: virtual __thiscall CVssJetWriter::~CVssJetWriter(void)` | 10 (0xa) | Exported Function | 0x1005bf80 | 0x0005bf80
`public: long __stdcall CVssWriter::Unsubscribe(void)` | 74 (0x4a) | Exported Function | 0x1005b050 | 0x0005b050
`public: long __stdcall CVssWriter::Subscribe(unsigned long)` | 72 (0x48) | Exported Function | 0x1005ae50 | 0x0005ae50
`public: long __stdcall CVssWriter::InstallAlternateWriter(struct _GUID,struct _GUID)` | 34 (0x22) | Exported Function | 0x10059b70 | 0x00059b70
`public: long __stdcall CVssWriter::Initialize(struct _GUID,unsigned short const *,enum VSS_USAGE_TYPE,enum VSS_SOURCE_TYPE,enum _VSS_APPLICATION_LEVEL,unsigned long,enum VSS_ALTERNATE_WRITER_STATE,bool,unsigned short const *)` | 33 (0x21) | Exported Function | 0x10059ae0 | 0x00059ae0
`public: virtual bool __stdcall CVssJetWriter::OnPrepareSnapshotEnd(bool)` | 65 (0x41) | Exported Function | 0x1005ce00 | 0x0005ce00
`public: long __stdcall CVssJetWriter::Initialize(struct _GUID,unsigned short const *,bool,bool,unsigned short const *,unsigned short const *,unsigned long)` | 32 (0x20) | Exported Function | 0x1005c410 | 0x0005c410
`public: virtual bool __stdcall CVssJetWriter::OnPreRestoreBegin(class IVssWriterComponents *)` | 59 (0x3b) | Exported Function | 0x1005cc70 | 0x0005cc70
`public: virtual bool __stdcall CVssJetWriter::OnThawBegin(void)` | 66 (0x42) | Exported Function | 0x1005ce50 | 0x0005ce50
`ShouldBlockRevertInternal` | 87 (0x57) | Exported Function | 0x10057360 | 0x00057360
`ShouldBlockRevert` | 7 (0x7) | Exported Function | 0x10057360 | 0x00057360
`public: void __stdcall CVssJetWriter::Uninitialize(void)` | 73 (0x49) | Exported Function | 0x1005cf60 | 0x0005cf60
`public: virtual void __stdcall CVssJetWriter::OnAbortEnd(void)` | 42 (0x2a) | Exported Function | 0x1005c9a0 | 0x0005c9a0
`public: virtual void __stdcall CVssJetWriter::OnAbortBegin(void)` | 41 (0x29) | Exported Function | 0x1005c950 | 0x0005c950
`public: virtual bool __stdcall CVssWriter::OnVSSShutdown(void)` | 69 (0x45) | Exported Function | 0x10043fc0 | 0x00043fc0
`public: virtual bool __stdcall CVssWriter::OnVSSApplicationStartup(void)` | 68 (0x44) | Exported Function | 0x10043fc0 | 0x00043fc0
`public: virtual bool __stdcall CVssWriter::OnPreRestore(class IVssWriterComponents *)` | 58 (0x3a) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnPrepareBackup(class IVssWriterComponents *)` | 61 (0x3d) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnPostSnapshot(class IVssWriterComponents *)` | 57 (0x39) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnPostRestore(class IVssWriterComponents *)` | 53 (0x35) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnIdentify(class IVssCreateWriterMetadata *)` | 52 (0x34) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnContinueIOOnVolume(unsigned short *,struct _GUID,struct _GUID)` | 48 (0x30) | Exported Function | 0x10043f90 | 0x00043f90
`public: virtual bool __stdcall CVssWriter::OnBackupShutdown(struct _GUID)` | 47 (0x2f) | Exported Function | 0x10043fb0 | 0x00043fb0
`public: virtual bool __stdcall CVssWriter::OnBackupComplete(class IVssWriterComponents *)` | 44 (0x2c) | Exported Function | 0x10043fa0 | 0x00043fa0
`public: virtual bool __stdcall CVssWriter::OnBackOffIOOnVolume(unsigned short *,struct _GUID,struct _GUID)` | 43 (0x2b) | Exported Function | 0x10043f90 | 0x00043f90
`public: virtual bool __stdcall CVssJetWriter::OnThawEnd(bool)` | 67 (0x43) | Exported Function | 0x1005cea0 | 0x0005cea0
`public: virtual bool __stdcall CVssJetWriter::OnPreRestoreEnd(class IVssWriterComponents *,bool)` | 60 (0x3c) | Exported Function | 0x1005ccc0 | 0x0005ccc0
`public: __thiscall CVssWriter::CVssWriter(void)` | 9 (0x9) | Exported Function | 0x10058230 | 0x00058230
`public: __thiscall CVssJetWriter::CVssJetWriter(void)` | 8 (0x8) | Exported Function | 0x1005bf60 | 0x0005bf60
`protected: unsigned short const * * __stdcall CVssWriter::GetCurrentVolumeArray(void)const ` | 25 (0x19) | Exported Function | 0x10059040 | 0x00059040
`protected: bool __stdcall CVssJetWriter::IsPartialFileSupportEnabled(void)const ` | 37 (0x25) | Exported Function | 0x1005c870 | 0x0005c870
`protected: bool __stdcall CVssJetWriter::IsBootableSystemStateBackedUp(void)const ` | 35 (0x23) | Exported Function | 0x1005c800 | 0x0005c800
`protected: bool __stdcall CVssJetWriter::AreComponentsSelected(void)const ` | 12 (0xc) | Exported Function | 0x1005c010 | 0x0005c010
`long __stdcall CreateVssExamineWriterMetadata(unsigned short *,class IVssExamineWriterMetadata * *)` | 15 (0xf) | Exported Function | 0x1005b550 | 0x0005b550
`long __stdcall CreateVssBackupComponents(class IVssBackupComponents * *)` | 14 (0xe) | Exported Function | 0x1005b3c0 | 0x0005b3c0
`LoadVssSnapshotSetDescription` | 86 (0x56) | Exported Function | 0x1005bdc0 | 0x0005bdc0
`IsVolumeSnapshottedInternal` | 85 (0x55) | Exported Function | 0x10056b90 | 0x00056b90
`IsVolumeSnapshotted` | 5 (0x5) | Exported Function | 0x10056b90 | 0x00056b90
`GetProviderMgmtInterfaceInternal` | 84 (0x54) | Exported Function | 0x10039460 | 0x00039460
`GetProviderMgmtInterface` | 83 (0x53) | Exported Function | 0x10039460 | 0x00039460
`DllGetClassObject` | 82 (0x52) | Exported Function | 0x10056b70 | 0x00056b70
`DllCanUnloadNow` | 81 (0x51) | Exported Function | 0x10056b50 | 0x00056b50
`CreateWriterEx` | 80 (0x50) | Exported Function | 0x10039830 | 0x00039830
`CreateWriter` | 79 (0x4f) | Exported Function | 0x10039a00 | 0x00039a00
`CreateVssSnapshotSetDescription` | 78 (0x4e) | Exported Function | 0x1005ba10 | 0x0005ba10
`CreateVssExpressWriterInternal` | 77 (0x4d) | Exported Function | 0x1005b7e0 | 0x0005b7e0
`CreateVssExamineWriterMetadataInternal` | 76 (0x4c) | Exported Function | 0x1005b550 | 0x0005b550
`protected: bool __stdcall CVssJetWriter::IsPathAffected(unsigned short const *)const ` | 39 (0x27) | Exported Function | 0x1005c8e0 | 0x0005c8e0
`protected: bool __stdcall CVssWriter::AreComponentsSelected(void)const ` | 13 (0xd) | Exported Function | 0x10058990 | 0x00058990
`protected: bool __stdcall CVssWriter::IsBootableSystemStateBackedUp(void)const ` | 36 (0x24) | Exported Function | 0x10059c30 | 0x00059c30
`protected: bool __stdcall CVssWriter::IsPartialFileSupportEnabled(void)const ` | 38 (0x26) | Exported Function | 0x10059cb0 | 0x00059cb0
`protected: unsigned short const * * __stdcall CVssJetWriter::GetCurrentVolumeArray(void)const ` | 24 (0x18) | Exported Function | 0x1005c250 | 0x0005c250
`protected: unsigned int __stdcall CVssWriter::GetCurrentVolumeCount(void)const ` | 27 (0x1b) | Exported Function | 0x10059080 | 0x00059080
`protected: unsigned int __stdcall CVssJetWriter::GetCurrentVolumeCount(void)const ` | 26 (0x1a) | Exported Function | 0x1005c2c0 | 0x0005c2c0
`protected: struct _GUID __stdcall CVssWriter::GetCurrentSnapshotSetId(void)const ` | 23 (0x17) | Exported Function | 0x10059000 | 0x00059000
`protected: struct _GUID __stdcall CVssJetWriter::GetCurrentSnapshotSetId(void)const ` | 22 (0x16) | Exported Function | 0x1005c1d0 | 0x0005c1d0
`protected: long __stdcall CVssWriter::SetWriterFailure(long)` | 71 (0x47) | Exported Function | 0x1005ac30 | 0x0005ac30
`protected: long __stdcall CVssWriter::GetSnapshotDeviceName(unsigned short const *,unsigned short const * *)const ` | 31 (0x1f) | Exported Function | 0x10059610 | 0x00059610
`protected: long __stdcall CVssWriter::GetContext(void)const ` | 19 (0x13) | Exported Function | 0x10058e60 | 0x00058e60
`VssFreeSnapshotProperties` | 6 (0x6) | Exported Function | 0x10057ea0 | 0x00057ea0
`protected: long __stdcall CVssJetWriter::SetWriterFailure(long)` | 70 (0x46) | Exported Function | 0x1005cef0 | 0x0005cef0
`protected: long __stdcall CVssJetWriter::GetContext(void)const ` | 18 (0x12) | Exported Function | 0x1005c0f0 | 0x0005c0f0
`protected: enum _VSS_RESTORE_TYPE __stdcall CVssWriter::GetRestoreType(void)const ` | 29 (0x1d) | Exported Function | 0x10059580 | 0x00059580
`protected: enum _VSS_RESTORE_TYPE __stdcall CVssJetWriter::GetRestoreType(void)const ` | 28 (0x1c) | Exported Function | 0x1005c330 | 0x0005c330
`protected: enum _VSS_BACKUP_TYPE __stdcall CVssWriter::GetBackupType(void)const ` | 17 (0x11) | Exported Function | 0x10058e20 | 0x00058e20
`protected: enum _VSS_BACKUP_TYPE __stdcall CVssJetWriter::GetBackupType(void)const ` | 16 (0x10) | Exported Function | 0x1005c080 | 0x0005c080
`protected: enum _VSS_APPLICATION_LEVEL __stdcall CVssWriter::GetCurrentLevel(void)const ` | 21 (0x15) | Exported Function | 0x10058f70 | 0x00058f70
`protected: enum _VSS_APPLICATION_LEVEL __stdcall CVssJetWriter::GetCurrentLevel(void)const ` | 20 (0x14) | Exported Function | 0x1005c160 | 0x0005c160
`protected: bool __stdcall CVssWriter::IsPathAffected(unsigned short const *)const ` | 40 (0x28) | Exported Function | 0x10059cf0 | 0x00059cf0
`protected: long __stdcall CVssJetWriter::GetSnapshotDeviceName(unsigned short const *,unsigned short const * *)const ` | 30 (0x1e) | Exported Function | 0x1005c3a0 | 0x0005c3a0
`VssFreeSnapshotPropertiesInternal` | 88 (0x58) | Exported Function | 0x10057ea0 | 0x00057ea0


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


