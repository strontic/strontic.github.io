---
title: wdfkd.dll | Microsoft Kernel Debugger Extensions (WDF)
excerpt: What is wdfkd.dll?
---

# wdfkd.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\winext\wdfkd.dll`
* Description: Microsoft Kernel Debugger Extensions (WDF)

## Hashes

Type | Hash
-- | --
MD5 | `63D83855E0EB1AD91040809FE20DE1BA`
SHA1 | `DCAE997FB4F7400E0555461EE148970983D10ED5`
SHA256 | `E4C51C8FAE1C206DB8104477B5B6D9E7ABAF5F422D5C7D89F46DCF38D64908A9`
SHA384 | `16D73202A361647A9B84599CF889F5FB6D1A3499777D9D9C729D7A060B8050B97E90D08132D610777EB968AFCE10F432`
SHA512 | `EC33276A7E82BB7B6A895D93C38D7897846735BAD32275AADDBB4208EE0ED4A54CB1650A2DCD434030629A02B6903664129E436D94C081B271B28251FDAF5F5E`
SSDEEP | `24576:F7VRTi/aTelZ4sYHQnUJdwgQAwcIAfP/vfP/vfPjHdY:F7VRTNmB4wgQAwcIAfP/vfP/vfPjHdY`
IMP | `EBC5BD5FE9D73C6F24D0D033EBB106B3`
PESHA1 | `2EAAD6A73FC4CC441D73AEDB7BD10DA579FBE320`
PE256 | `F46B781D265419A427D8444E63D45804571CA480CEF74289C416DEBDB4CAE617`

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
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wdfkd.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\winext\wdfkd.dll](wdfkd.dll-BA87CF2A2F9CB3CE99C96257BF26FB2A.md) | 49
[C:\Windows\SysWOW64\tdh.dll](tdh.dll-B868D4AD3E68EBA1501E8CA91DFAF2BC.md) | 54




MIT License. Copyright (c) 2020 Strontic.


