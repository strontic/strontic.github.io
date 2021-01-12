---
title: wdfkd.dll | Microsoft Kernel Debugger Extensions (WDF)
excerpt: What is wdfkd.dll?
---

# wdfkd.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\winext\wdfkd.dll`
* Description: Microsoft Kernel Debugger Extensions (WDF)

## Hashes

Type | Hash
-- | --
MD5 | `BA87CF2A2F9CB3CE99C96257BF26FB2A`
SHA1 | `D7B241FFAE12C4C790E1E89D6BEEE056994DF2E1`
SHA256 | `8FD8C65D7672329FF23F82AFA6F80723FD407632E34D5E92D897248622B1A3C2`
SHA384 | `46E76A5F6BEFF61256D7987BB6BC1A2FA53464F079CBB0B9B3A1DBD91B87E48492C1EABBE6C4C4F7236F7B2D62BABBDE`
SHA512 | `50E8BF36B96203166FC077FE97655EB410B5F03170C5CB6B2E12239578A2DD74B972E501BAE196567842A5B8760BBCA9F14C7D9A5BC8B340228313B9BCC1C5AA`
SSDEEP | `24576:J7VRTi/VJwTrWUFshsKiFXyLeqtTo3H6mQAfP/T3P/vfP/vfP/vae85:J7VRT+6Ti5+4js3HrQAfP/T3P/vfP/vc`
IMP | `C23858186453DA326E27753C70279515`
PESHA1 | `D50D9E977244F06EE414FD818F6C561A22DF68DA`
PE256 | `FF4C2B7F5BE80D2CBFF281C9F9F1F2BF3DEB95702753B6EC49C5AAAB575FA5C9`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\winext\wdfkd.dll](wdfkd.dll-63D83855E0EB1AD91040809FE20DE1BA.md) | 49
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\winext\rcdrkd.dll](rcdrkd.dll-30FD9D79A6C57BA003840127EFAC1A04.md) | 27




MIT License. Copyright (c) 2020 Strontic.


