---
title: wdfkd.dll | Microsoft Kernel Debugger Extensions (WDF)
excerpt: What is wdfkd.dll?
---

# wdfkd.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winext\wdfkd.dll`
* Description: Microsoft Kernel Debugger Extensions (WDF)

## Hashes

Type | Hash
-- | --
MD5 | `5602BDB2CC9426DBE930E593E65BFA78`
SHA1 | `FBC5CCA2AC9FE5DCD8D1B6A560B697C43ADCDF35`
SHA256 | `C5DDE8A812B03BF19A2E06428CE7B5658ED4F3923403EA5575196B6AF4B6EF0B`
SHA384 | `A420DC0F45C4905CE96BC44AF1F1B29EC02FDF21557AC7D791D26E1BBB36F75DFE1F29EBFE924E1BB853432CBEEBFEB6`
SHA512 | `3A9603616A60FD7C1E286568BBF10B85ED33D032933252CD3EB18C5603DAE12A390540A5E9EA4DE933DAC8696C6B8B9664E7839636A17E59A535DD1D98C80379`
SSDEEP | `12288:iW+XBLu0XhAgJYow6DIexZAuskLlxjpEz/gnYyL:v+X42hAgJZw6saLlxjC/MYyL`
IMP | `FBA819FBF85B564304593FA3E9267DE6`
PESHA1 | `487F6AE6EDCF8B91B489E480F4400EAF833E054F`
PE256 | `FF2C1F4DFD4364E72ECF90009974E42282AC8C37DE1BF882AE6B1EC9E427B514`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`wdfopenhandles` | 49 | Exported Function
`wdfpoolusage` | 50 | Exported Function
`wdfmemory` | 47 | Exported Function
`wdfobject` | 48 | Exported Function
`wdfqueue` | 51 | Exported Function
`wdfsetdriver` | 54 | Exported Function
`wdfsettraceprefix` | 55 | Exported Function
`wdfrequest` | 52 | Exported Function
`wdfsearchpath` | 53 | Exported Function
`wdfhandle` | 40 | Exported Function
`wdfhelp` | 41 | Exported Function
`wdfforwardprogress` | 38 | Exported Function
`wdfgetdriver` | 39 | Exported Function
`wdfinterrupt` | 42 | Exported Function
`wdflogdump` | 45 | Exported Function
`wdflogsave` | 46 | Exported Function
`wdfiotarget` | 43 | Exported Function
`wdfldr` | 44 | Exported Function
`wdfumrefhistory` | 67 | Exported Function
`wdfumtriage` | 68 | Exported Function
`wdfumirp` | 65 | Exported Function
`wdfumirps` | 66 | Exported Function
`wdfusbdevice` | 69 | Exported Function
`wdfwmi` | 72 | Exported Function
`WinDbgExtensionDllInit` | 5 | Exported Function
`wdfusbinterface` | 70 | Exported Function
`wdfusbpipe` | 71 | Exported Function
`wdftaskqueue` | 58 | Exported Function
`wdftmffile` | 59 | Exported Function
`wdfspinlock` | 56 | Exported Function
`wdftagtracker` | 57 | Exported Function
`wdftraceprtdebug` | 60 | Exported Function
`wdfumdownirp` | 63 | Exported Function
`wdfumfile` | 64 | Exported Function
`wdfumdevstack` | 61 | Exported Function
`wdfumdevstacks` | 62 | Exported Function
`_EFN_WdfKdWdfObjectToWdfHandle` | 17 | Exported Function
`_EFN_WdfKdWdfQueueGetRequests` | 18 | Exported Function
`_EFN_WdfKdWdfHandleToWdfObject` | 16 | Exported Function
`_EFN_WdfKdWdfInterruptNormalizeIsr` | 10 | Exported Function
`_EFN_WdfKdWdfRequestGetCompletionRoutineAndContext` | 19 | Exported Function
`CheckVersion` | 1 | Exported Function
`DebugExtensionInitialize` | 2 | Exported Function
`_EFN_WdfKdWdfRequestGetIrp` | 20 | Exported Function
`_EFN_WdfKdWdfUmDevstackGetSuspectThreadID` | 21 | Exported Function
`_EFN_WdfKdGetCrashMetadata` | 7 | Exported Function
`_EFN_WdfKdSetDriver` | 12 | Exported Function
`_EFN_WdfKdBindDbgExtNotify` | 11 | Exported Function
`_EFN_WdfKdBindDbgExtNotifyEx` | 6 | Exported Function
`_EFN_WdfKdUnbindDbgExtNotify` | 13 | Exported Function
`_EFN_WdfKdWdfHandleGetContextByName` | 14 | Exported Function
`_EFN_WdfKdWdfHandleGetParent` | 15 | Exported Function
`_EFN_WdfKdWdfContextGetWdfObject` | 8 | Exported Function
`_EFN_WdfKdWdfDrvGlobalsGetDriverInfoFromCrashDump` | 9 | Exported Function
`wdfdevicequeues` | 31 | Exported Function
`wdfdmaenabler` | 32 | Exported Function
`wdfdevice` | 29 | Exported Function
`wdfdeviceinterrupts` | 30 | Exported Function
`wdfdmaenablers` | 33 | Exported Function
`wdfextendwatchdog` | 36 | Exported Function
`wdffindobjects` | 37 | Exported Function
`wdfdmatransaction` | 34 | Exported Function
`wdfdriverinfo` | 35 | Exported Function
`help` | 22 | Exported Function
`wdfchildlist` | 23 | Exported Function
`DebugExtensionUninitialize` | 3 | Exported Function
`ExtensionApiVersion` | 4 | Exported Function
`wdfcollection` | 24 | Exported Function
`wdfcrashdump` | 27 | Exported Function
`wdfdevext` | 28 | Exported Function
`wdfcommonbuffer` | 25 | Exported Function
`wdfcompanion` | 26 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wdfkd.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/c5dde8a812b03bf19a2e06428ce7b5658ed4f3923403ea5575196b6af4b6ef0b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\tracefmt.exe](tracefmt.exe-1A132D3C750C4F6E6A49DD0B15037A01.md) | 36
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracefmt.exe](tracefmt.exe-A02AC40EA76F0B6AFE2C9FF49BB15692.md) | 30
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\winext\wdfkd.dll](wdfkd.dll-22783C7922A5F8678B086785C60E99A1.md) | 32
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winext\rcdrkd.dll](rcdrkd.dll-17D72886BD70CE923FAB6A6427360028.md) | 32
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winxp\wmitrace.dll](wmitrace.dll-2B386CB3C2E87D0AE428CDA7EB809640.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\perf_wpp.dll](perf_wpp.dll-5570A1894C91C49766FFF4CFDB1BE221.md) | 30




MIT License. Copyright (c) 2020 Strontic.


