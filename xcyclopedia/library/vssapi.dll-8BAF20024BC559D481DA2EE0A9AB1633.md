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
`OnPostRestoreEnd` | 55 | Exported Function
`OnPostSnapshot` | 56 | Exported Function
`OnPostRestoreBegin` | 54 | Exported Function
`OnFreezeEnd` | 50 | Exported Function
`OnIdentify` | 51 | Exported Function
`OnPrepareSnapshotEnd` | 65 | Exported Function
`OnPreRestoreBegin` | 59 | Exported Function
`OnPrepareSnapshotBegin` | 64 | Exported Function
`OnPrepareBackupBegin` | 62 | Exported Function
`OnPrepareBackupEnd` | 63 | Exported Function
`OnFreezeBegin` | 49 | Exported Function
`InstallAlternateWriter` | 34 | Exported Function
`Subscribe` | 72 | Exported Function
`Initialize` | 33 | Exported Function
`CVssWriter` | 9 | Exported Function
`Initialize` | 32 | Exported Function
`OnBackupCompleteBegin` | 45 | Exported Function
`OnBackupCompleteEnd` | 46 | Exported Function
`public: virtual __cdecl CVssWriter::~CVssWriter(void) __ptr64` | 11 | Exported Function
`Unsubscribe` | 74 | Exported Function
`public: virtual __cdecl CVssJetWriter::~CVssJetWriter(void) __ptr64` | 10 | Exported Function
`OnAbortBegin` | 41 | Exported Function
`OnAbortEnd` | 42 | Exported Function
`OnVSSShutdown` | 69 | Exported Function
`OnPreRestore` | 58 | Exported Function
`OnVSSApplicationStartup` | 68 | Exported Function
`VssFreeSnapshotProperties` | 6 | Exported Function
`VssFreeSnapshotPropertiesInternal` | 88 | Exported Function
`ShouldBlockRevertInternal` | 87 | Exported Function
`Uninitialize` | 73 | Exported Function
`ShouldBlockRevert` | 7 | Exported Function
`OnPrepareBackup` | 61 | Exported Function
`OnBackOffIOOnVolume` | 43 | Exported Function
`OnBackupComplete` | 44 | Exported Function
`OnThawEnd` | 67 | Exported Function
`OnPreRestoreEnd` | 60 | Exported Function
`OnThawBegin` | 66 | Exported Function
`OnPostRestore` | 53 | Exported Function
`OnPostSnapshot` | 57 | Exported Function
`OnIdentify` | 52 | Exported Function
`OnBackupShutdown` | 47 | Exported Function
`OnContinueIOOnVolume` | 48 | Exported Function
`long __cdecl CreateVssExamineWriterMetadata(unsigned short * __ptr64,class IVssExamineWriterMetadata * __ptr64 * __ptr64)` | 15 | Exported Function
`AreComponentsSelected` | 12 | Exported Function
`long __cdecl CreateVssBackupComponents(class IVssBackupComponents * __ptr64 * __ptr64)` | 14 | Exported Function
`IsVolumeSnapshottedInternal` | 85 | Exported Function
`LoadVssSnapshotSetDescription` | 86 | Exported Function
`AreComponentsSelected` | 13 | Exported Function
`IsBootableSystemStateBackedUp` | 36 | Exported Function
`IsPathAffected` | 39 | Exported Function
`IsBootableSystemStateBackedUp` | 35 | Exported Function
`IsPartialFileSupportEnabled` | 37 | Exported Function
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
`GetCurrentSnapshotSetId` | 22 | Exported Function
`GetCurrentSnapshotSetId` | 23 | Exported Function
`SetWriterFailure` | 71 | Exported Function
`GetContext` | 19 | Exported Function
`GetSnapshotDeviceName` | 31 | Exported Function
`GetCurrentVolumeArray` | 25 | Exported Function
`CVssJetWriter` | 8 | Exported Function
`GetCurrentVolumeArray` | 24 | Exported Function
`GetCurrentVolumeCount` | 26 | Exported Function
`GetCurrentVolumeCount` | 27 | Exported Function
`SetWriterFailure` | 70 | Exported Function
`GetCurrentLevel` | 21 | Exported Function
`GetBackupType` | 16 | Exported Function
`GetCurrentLevel` | 20 | Exported Function
`IsPartialFileSupportEnabled` | 38 | Exported Function
`IsPathAffected` | 40 | Exported Function
`GetContext` | 18 | Exported Function
`GetSnapshotDeviceName` | 30 | Exported Function
`GetRestoreType` | 29 | Exported Function
`GetBackupType` | 17 | Exported Function
`GetRestoreType` | 28 | Exported Function


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


