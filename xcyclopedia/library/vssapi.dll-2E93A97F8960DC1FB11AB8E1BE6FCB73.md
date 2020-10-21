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
`public: virtual __thiscall CVssWriter::~CVssWriter(void)` | 11 | Exported Function
`Unsubscribe` | 74 | Exported Function
`public: virtual __thiscall CVssJetWriter::~CVssJetWriter(void)` | 10 | Exported Function
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
`long __stdcall CreateVssExamineWriterMetadata(unsigned short *,class IVssExamineWriterMetadata * *)` | 15 | Exported Function
`AreComponentsSelected` | 12 | Exported Function
`long __stdcall CreateVssBackupComponents(class IVssBackupComponents * *)` | 14 | Exported Function
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


