---
title: RTWorkQ.dll | Realtime WorkQueue DLL
excerpt: What is RTWorkQ.dll?
---

# RTWorkQ.dll 

* File Path: `C:\Windows\SysWOW64\RTWorkQ.dll`
* Description: Realtime WorkQueue DLL

## Hashes

Type | Hash
-- | --
MD5 | `25F4BAE1FE4989FFB5A2EC6513D9EA0F`
SHA1 | `18D0FCA792649EC7B694F750242BD33A81A1E00F`
SHA256 | `EB07722EF244BB0A5C057E060DBA22482C64BDBDB2008B358D04290F2A96E157`
SHA384 | `2AB57D697902F9E3EF38A9B5CFB203D7B51E9D5458973467A2AA30033F3B846BD87CFDC0F84F799543B337E7653B3DA5`
SHA512 | `24714F40D5894E164A18C761EE2C29D03F6A285D0C6E3CD23929C2ADC05B0DE9D07536B74D53F8D7906568D542DC2DF932F779AEDAFD29492A3C33E1B66A6EB9`
SSDEEP | `3072:mkZiXzGNUNJhBcyZE7L9nj4/3RBQfvhh3oQa2JCwNuTMpR2F0ajJSB:mkZQzGNuJhBcqvRBQfvhh3oQa2eMW14`
IMP | `2FA46369E7EA294FA8C885F76E008FA2`
PESHA1 | `F10FBB1682D105DE3E195C3CC65B89FB3E00D6F4`
PE256 | `8599674825C5BDBECF013D2522A9310CB4D459B7AB0775F5B79D9ECBF15C4FEE`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`RtwqAddPeriodicCallback` | 2 (0x2) | Exported Function | 0x1000fa80 | 0x0000fa80
`RtwqPutMultipleWaitingWorkItem` | 21 (0x15) | Exported Function | 0x1000f770 | 0x0000f770
`RtwqPutWaitingWorkItem` | 22 (0x16) | Exported Function | 0x10006350 | 0x00006350
`RtwqPutWorkItem` | 23 (0x17) | Exported Function | 0x10004130 | 0x00004130
`RtwqRegisterPlatformEvents` | 24 (0x18) | Exported Function | 0x100099e0 | 0x000099e0
`RtwqRegisterPlatformWithMMCSS` | 25 (0x19) | Exported Function | 0x1000ff30 | 0x0000ff30
`RtwqRemovePeriodicCallback` | 26 (0x1a) | Exported Function | 0x1000ff60 | 0x0000ff60
`RtwqScheduleWorkItem` | 27 (0x1b) | Exported Function | 0x1000ffc0 | 0x0000ffc0
`RtwqSetDeadline` | 29 (0x1d) | Exported Function | 0x100100d0 | 0x000100d0
`RtwqSetDeadline2` | 28 (0x1c) | Exported Function | 0x1000fff0 | 0x0000fff0
`RtwqSetLongRunning` | 30 (0x1e) | Exported Function | 0x10010100 | 0x00010100
`RtwqShutdown` | 31 (0x1f) | Exported Function | 0x10007140 | 0x00007140
`RtwqStartup` | 32 (0x20) | Exported Function | 0x10007c40 | 0x00007c40
`RtwqUnjoinWorkQueue` | 33 (0x21) | Exported Function | 0x10010120 | 0x00010120
`RtwqUnlockPlatform` | 34 (0x22) | Exported Function | 0x10006d70 | 0x00006d70
`RtwqUnlockWorkQueue` | 35 (0x23) | Exported Function | 0x10003810 | 0x00003810
`RtwqLockWorkQueue` | 20 (0x14) | Exported Function | 0x1000ff10 | 0x0000ff10
`RtwqUnregisterPlatformEvents` | 36 (0x24) | Exported Function | 0x100101b0 | 0x000101b0
`RtwqLockSharedWorkQueue` | 19 (0x13) | Exported Function | 0x10002a20 | 0x00002a20
`RtwqJoinWorkQueue` | 17 (0x11) | Exported Function | 0x1000fe80 | 0x0000fe80
`RtwqAllocateSerialWorkQueue` | 3 (0x3) | Exported Function | 0x100033c0 | 0x000033c0
`RtwqAllocateWorkQueue` | 4 (0x4) | Exported Function | 0x10002600 | 0x00002600
`RtwqBeginRegisterWorkQueueWithMMCSS` | 5 (0x5) | Exported Function | 0x1000faa0 | 0x0000faa0
`RtwqBeginUnregisterWorkQueueWithMMCSS` | 6 (0x6) | Exported Function | 0x1000fb10 | 0x0000fb10
`RtwqCancelDeadline` | 7 (0x7) | Exported Function | 0x1000fb70 | 0x0000fb70
`RtwqCancelMultipleWaitingWorkItem` | 8 (0x8) | Exported Function | 0x1000f740 | 0x0000f740
`RtwqCancelWorkItem` | 9 (0x9) | Exported Function | 0x100026a0 | 0x000026a0
`RtwqCreateAsyncResult` | 10 (0xa) | Exported Function | 0x10006e80 | 0x00006e80
`RtwqEndRegisterWorkQueueWithMMCSS` | 11 (0xb) | Exported Function | 0x1000fc20 | 0x0000fc20
`RtwqEndUnregisterWorkQueueWithMMCSS` | 12 (0xc) | Exported Function | 0x1000fc60 | 0x0000fc60
`RtwqGetPlatform` | 1 (0x1) | Exported Function | 0x1000f160 | 0x0000f160
`RtwqGetWorkQueueMMCSSClass` | 13 (0xd) | Exported Function | 0x1000fc90 | 0x0000fc90
`RtwqGetWorkQueueMMCSSPriority` | 14 (0xe) | Exported Function | 0x1000fd40 | 0x0000fd40
`RtwqGetWorkQueueMMCSSTaskId` | 15 (0xf) | Exported Function | 0x1000fde0 | 0x0000fde0
`RtwqInvokeCallback` | 16 (0x10) | Exported Function | 0x10003660 | 0x00003660
`RtwqLockPlatform` | 18 (0x12) | Exported Function | 0x10006d40 | 0x00006d40
`RtwqUnregisterPlatformFromMMCSS` | 37 (0x25) | Exported Function | 0x100101d0 | 0x000101d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RTWorkQ.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/eb07722ef244bb0a5c057e060dba22482c64bdbdb2008b358d04290f2a96e157/detection/





MIT License. Copyright (c) 2020 Strontic.


