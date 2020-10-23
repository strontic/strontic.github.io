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
`CVssJetWriter::OnPostRestoreEnd` | 55 | Exported Function
`CVssJetWriter::OnPostSnapshot` | 56 | Exported Function
`CVssJetWriter::OnPostRestoreBegin` | 54 | Exported Function
`CVssJetWriter::OnFreezeEnd` | 50 | Exported Function
`CVssJetWriter::OnIdentify` | 51 | Exported Function
`CVssJetWriter::OnPrepareSnapshotEnd` | 65 | Exported Function
`CVssJetWriter::OnPreRestoreBegin` | 59 | Exported Function
`CVssJetWriter::OnPrepareSnapshotBegin` | 64 | Exported Function
`CVssJetWriter::OnPrepareBackupBegin` | 62 | Exported Function
`CVssJetWriter::OnPrepareBackupEnd` | 63 | Exported Function
`CVssJetWriter::OnFreezeBegin` | 49 | Exported Function
`CVssWriter::InstallAlternateWriter` | 34 | Exported Function
`CVssWriter::Subscribe` | 72 | Exported Function
`CVssWriter::Initialize` | 33 | Exported Function
`CVssWriter::CVssWriter` | 9 | Exported Function
`CVssJetWriter::Initialize` | 32 | Exported Function
`CVssJetWriter::OnBackupCompleteBegin` | 45 | Exported Function
`CVssJetWriter::OnBackupCompleteEnd` | 46 | Exported Function
`public: virtual __thiscall CVssWriter::~CVssWriter(void)` | 11 | Exported Function
`CVssWriter::Unsubscribe` | 74 | Exported Function
`public: virtual __thiscall CVssJetWriter::~CVssJetWriter(void)` | 10 | Exported Function
`CVssJetWriter::OnAbortBegin` | 41 | Exported Function
`CVssJetWriter::OnAbortEnd` | 42 | Exported Function
`CVssWriter::OnVSSShutdown` | 69 | Exported Function
`CVssWriter::OnPreRestore` | 58 | Exported Function
`CVssWriter::OnVSSApplicationStartup` | 68 | Exported Function
`VssFreeSnapshotProperties` | 6 | Exported Function
`VssFreeSnapshotPropertiesInternal` | 88 | Exported Function
`ShouldBlockRevertInternal` | 87 | Exported Function
`CVssJetWriter::Uninitialize` | 73 | Exported Function
`ShouldBlockRevert` | 7 | Exported Function
`CVssWriter::OnPrepareBackup` | 61 | Exported Function
`CVssWriter::OnBackOffIOOnVolume` | 43 | Exported Function
`CVssWriter::OnBackupComplete` | 44 | Exported Function
`CVssJetWriter::OnThawEnd` | 67 | Exported Function
`CVssJetWriter::OnPreRestoreEnd` | 60 | Exported Function
`CVssJetWriter::OnThawBegin` | 66 | Exported Function
`CVssWriter::OnPostRestore` | 53 | Exported Function
`CVssWriter::OnPostSnapshot` | 57 | Exported Function
`CVssWriter::OnIdentify` | 52 | Exported Function
`CVssWriter::OnBackupShutdown` | 47 | Exported Function
`CVssWriter::OnContinueIOOnVolume` | 48 | Exported Function
`long __stdcall CreateVssExamineWriterMetadata(unsigned short *,class IVssExamineWriterMetadata * *)` | 15 | Exported Function
`CVssJetWriter::AreComponentsSelected` | 12 | Exported Function
`long __stdcall CreateVssBackupComponents(class IVssBackupComponents * *)` | 14 | Exported Function
`IsVolumeSnapshottedInternal` | 85 | Exported Function
`LoadVssSnapshotSetDescription` | 86 | Exported Function
`CVssWriter::AreComponentsSelected` | 13 | Exported Function
`CVssWriter::IsBootableSystemStateBackedUp` | 36 | Exported Function
`CVssJetWriter::IsPathAffected` | 39 | Exported Function
`CVssJetWriter::IsBootableSystemStateBackedUp` | 35 | Exported Function
`CVssJetWriter::IsPartialFileSupportEnabled` | 37 | Exported Function
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
`CVssJetWriter::GetCurrentSnapshotSetId` | 22 | Exported Function
`CVssWriter::GetCurrentSnapshotSetId` | 23 | Exported Function
`CVssWriter::SetWriterFailure` | 71 | Exported Function
`CVssWriter::GetContext` | 19 | Exported Function
`CVssWriter::GetSnapshotDeviceName` | 31 | Exported Function
`CVssWriter::GetCurrentVolumeArray` | 25 | Exported Function
`CVssJetWriter::CVssJetWriter` | 8 | Exported Function
`CVssJetWriter::GetCurrentVolumeArray` | 24 | Exported Function
`CVssJetWriter::GetCurrentVolumeCount` | 26 | Exported Function
`CVssWriter::GetCurrentVolumeCount` | 27 | Exported Function
`CVssJetWriter::SetWriterFailure` | 70 | Exported Function
`CVssWriter::GetCurrentLevel` | 21 | Exported Function
`CVssJetWriter::GetBackupType` | 16 | Exported Function
`CVssJetWriter::GetCurrentLevel` | 20 | Exported Function
`CVssWriter::IsPartialFileSupportEnabled` | 38 | Exported Function
`CVssWriter::IsPathAffected` | 40 | Exported Function
`CVssJetWriter::GetContext` | 18 | Exported Function
`CVssJetWriter::GetSnapshotDeviceName` | 30 | Exported Function
`CVssWriter::GetRestoreType` | 29 | Exported Function
`CVssWriter::GetBackupType` | 17 | Exported Function
`CVssJetWriter::GetRestoreType` | 28 | Exported Function


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


