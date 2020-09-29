---
title: RTWorkQ.dll | Realtime WorkQueue DLL
excerpt: What is RTWorkQ.dll?
---

# RTWorkQ.dll 

* File Path: `C:\Windows\system32\RTWorkQ.dll`
* Description: Realtime WorkQueue DLL

## Hashes

Type | Hash
-- | --
MD5 | `FF7661710BF691FBFF2D10FA8A79E5B1`
SHA1 | `B4239041C037E93728DEE3F54187EBD28DCC6637`
SHA256 | `9A64F0D2AD904A67DEAAF35DB50CE5A2E31ADCDB0D153B81F8F042C1F3AF35F3`
SHA384 | `1281FE78F80C8F498096BF5BF15CF3648B93C516A07A2644AD7BF59BF4EC85B8F805543E8D426E4CDC8ABFABD58D6EAC`
SHA512 | `AF31955C2C7575BD6B60A5825BC9BE10EFBF9B652C52FD825A951855399C64BE03ECF9C474E32EDB7B9428604F81EF331A3614D776F16D5D324BE6F689A03E8A`
SSDEEP | `3072:Gi/XuUBXru0ILbIyXxXHrEys2LAZs8i8hLuDMKraUBR2q5a:1/XuUpu7AyXxy2L2DcMjU+qk`
IMP | `6905CB3319FA91E98133205A243B7F44`
PESHA1 | `B00E47C20C3656203ABD9ABABE9F87FA52468788`
PE256 | `3B4627256BBA625D69E0C32DD26DF61CB20EA7BC37F0DF0493EAF166D37FA6B2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`RtwqAddPeriodicCallback` | 2 (0x2) | Exported Function | 0x00000001800050f0 | 0x000050f0
`RtwqPutMultipleWaitingWorkItem` | 21 (0x15) | Exported Function | 0x0000000180013c80 | 0x00013c80
`RtwqPutWaitingWorkItem` | 22 (0x16) | Exported Function | 0x0000000180006120 | 0x00006120
`RtwqPutWorkItem` | 23 (0x17) | Exported Function | 0x000000018000a6b0 | 0x0000a6b0
`RtwqRegisterPlatformEvents` | 24 (0x18) | Exported Function | 0x000000018000c2c0 | 0x0000c2c0
`RtwqRegisterPlatformWithMMCSS` | 25 (0x19) | Exported Function | 0x0000000180002f10 | 0x00002f10
`RtwqRemovePeriodicCallback` | 26 (0x1a) | Exported Function | 0x0000000180005690 | 0x00005690
`RtwqScheduleWorkItem` | 27 (0x1b) | Exported Function | 0x00000001800027e0 | 0x000027e0
`RtwqSetDeadline` | 28 (0x1c) | Exported Function | 0x0000000180002350 | 0x00002350
`RtwqSetDeadline2` | 29 (0x1d) | Exported Function | 0x0000000180002370 | 0x00002370
`RtwqSetLongRunning` | 30 (0x1e) | Exported Function | 0x0000000180001040 | 0x00001040
`RtwqShutdown` | 31 (0x1f) | Exported Function | 0x000000018000aaa0 | 0x0000aaa0
`RtwqStartup` | 32 (0x20) | Exported Function | 0x0000000180006af0 | 0x00006af0
`RtwqUnjoinWorkQueue` | 33 (0x21) | Exported Function | 0x0000000180005a90 | 0x00005a90
`RtwqUnlockPlatform` | 34 (0x22) | Exported Function | 0x00000001800022d0 | 0x000022d0
`RtwqUnlockWorkQueue` | 35 (0x23) | Exported Function | 0x00000001800096f0 | 0x000096f0
`RtwqLockWorkQueue` | 20 (0x14) | Exported Function | 0x0000000180004ad0 | 0x00004ad0
`RtwqUnregisterPlatformEvents` | 36 (0x24) | Exported Function | 0x0000000180014230 | 0x00014230
`RtwqLockSharedWorkQueue` | 19 (0x13) | Exported Function | 0x00000001800032f0 | 0x000032f0
`RtwqJoinWorkQueue` | 17 (0x11) | Exported Function | 0x00000001800059a0 | 0x000059a0
`RtwqAllocateSerialWorkQueue` | 3 (0x3) | Exported Function | 0x0000000180006ef0 | 0x00006ef0
`RtwqAllocateWorkQueue` | 4 (0x4) | Exported Function | 0x0000000180002e50 | 0x00002e50
`RtwqBeginRegisterWorkQueueWithMMCSS` | 5 (0x5) | Exported Function | 0x0000000180004060 | 0x00004060
`RtwqBeginUnregisterWorkQueueWithMMCSS` | 6 (0x6) | Exported Function | 0x0000000180013ee0 | 0x00013ee0
`RtwqCancelDeadline` | 7 (0x7) | Exported Function | 0x0000000180002580 | 0x00002580
`RtwqCancelMultipleWaitingWorkItem` | 8 (0x8) | Exported Function | 0x0000000180013c50 | 0x00013c50
`RtwqCancelWorkItem` | 9 (0x9) | Exported Function | 0x000000018000be40 | 0x0000be40
`RtwqCreateAsyncResult` | 10 (0xa) | Exported Function | 0x000000018000bd70 | 0x0000bd70
`RtwqEndRegisterWorkQueueWithMMCSS` | 11 (0xb) | Exported Function | 0x0000000180005780 | 0x00005780
`RtwqEndUnregisterWorkQueueWithMMCSS` | 12 (0xc) | Exported Function | 0x0000000180013fd0 | 0x00013fd0
`RtwqGetPlatform` | 1 (0x1) | Exported Function | 0x0000000180013630 | 0x00013630
`RtwqGetWorkQueueMMCSSClass` | 13 (0xd) | Exported Function | 0x0000000180014000 | 0x00014000
`RtwqGetWorkQueueMMCSSPriority` | 14 (0xe) | Exported Function | 0x00000001800058b0 | 0x000058b0
`RtwqGetWorkQueueMMCSSTaskId` | 15 (0xf) | Exported Function | 0x0000000180014120 | 0x00014120
`RtwqInvokeCallback` | 16 (0x10) | Exported Function | 0x0000000180001f80 | 0x00001f80
`RtwqLockPlatform` | 18 (0x12) | Exported Function | 0x0000000180002310 | 0x00002310
`RtwqUnregisterPlatformFromMMCSS` | 37 (0x25) | Exported Function | 0x0000000180014250 | 0x00014250


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RTWorkQ.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/9a64f0d2ad904a67deaaf35db50ce5a2e31adcdb0d153b81f8f042c1f3af35f3/detection/





MIT License. Copyright (c) 2020 Strontic.


