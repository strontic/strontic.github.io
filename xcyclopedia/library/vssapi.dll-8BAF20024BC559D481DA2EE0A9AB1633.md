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
`public: virtual __cdecl CVssWriter::~CVssWriter(void) __ptr64` | 11 | Exported Function
`CVssWriter::Unsubscribe` | 74 | Exported Function
`public: virtual __cdecl CVssJetWriter::~CVssJetWriter(void) __ptr64` | 10 | Exported Function
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
`long __cdecl CreateVssExamineWriterMetadata(unsigned short * __ptr64,class IVssExamineWriterMetadata * __ptr64 * __ptr64)` | 15 | Exported Function
`CVssJetWriter::AreComponentsSelected` | 12 | Exported Function
`long __cdecl CreateVssBackupComponents(class IVssBackupComponents * __ptr64 * __ptr64)` | 14 | Exported Function
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


