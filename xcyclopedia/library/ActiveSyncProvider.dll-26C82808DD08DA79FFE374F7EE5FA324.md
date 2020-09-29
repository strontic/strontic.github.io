---
title: ActiveSyncProvider.dll | The engine that syncs ActiveSync accounts
excerpt: What is ActiveSyncProvider.dll?
---

# ActiveSyncProvider.dll 

* File Path: `C:\Windows\system32\ActiveSyncProvider.dll`
* Description: The engine that syncs ActiveSync accounts

## Hashes

Type | Hash
-- | --
MD5 | `26C82808DD08DA79FFE374F7EE5FA324`
SHA1 | `363A62E5C7DA6BC0F688B4290EEC6C78D8B5A20D`
SHA256 | `33F0C24752AE99BA3B9E8ADF4AC3441278AFD42959BB761467F9846E4A44FBB6`
SHA384 | `3D114F4D260391491B1056F6A4D1AB4F50585B73D0D2C0489B44A1E3877CB60029DA9A1FD78C1229F821C3D3537B5D63`
SHA512 | `D546498EEEFC7401B00F49387F2B4B8A1D6BCF10BFB55B5502889533C25DB7818A9E7604BE3D5179BD76B07F1E2F94661638D09071652EC533B51A7AADEDCE26`
SSDEEP | `24576:z2qHHUVw0jxg7V7ouz2IkAS4EzA2uEYffAEOxAVPqenrzP7U8X:z2IUmqxg7V7ouJkAS4EjUc0rrzP7VX`
IMP | `71DE13C0BB143D06CAD7973A4DF93A64`
PESHA1 | `E2162A6BFC657F6F9E325C4911EF3F36A20B66DB`
PE256 | `63D9A3CD9B91BE1D484FFA29553A3D7DCBEEE0695C889E8F82C954BD0F53AE68`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateMassObject` | 3 (0x3) | Exported Function | 0x000000018000e880 | 0x0000e880
`Ordinal18` | 18 (0x12) | Exported Function | 0x0000000180071450 | 0x00071450
`Ordinal19` | 19 (0x13) | Exported Function | 0x0000000180041540 | 0x00041540
`Ordinal36` | 36 (0x24) | Exported Function | 0x000000018006f030 | 0x0006f030
`Ordinal37` | 37 (0x25) | Exported Function | 0x000000018006f340 | 0x0006f340
`Ordinal44` | 44 (0x2c) | Exported Function | 0x0000000180041100 | 0x00041100
`Ordinal45` | 45 (0x2d) | Exported Function | 0x0000000180040ee0 | 0x00040ee0
`Ordinal61` | 61 (0x3d) | Exported Function | 0x00000001800a0960 | 0x000a0960
`SyncGetMAPISession` | 22 (0x16) | Exported Function | 0x0000000180062050 | 0x00062050
`SyncGetMessageStore` | 23 (0x17) | Exported Function | 0x00000001800620e0 | 0x000620e0
`SyncGetSpecialFolder` | 24 (0x18) | Exported Function | 0x0000000180062180 | 0x00062180
`SyncMgrPurgeFolderProvider` | 25 (0x19) | Exported Function | 0x000000018006f220 | 0x0006f220
`SyncMgrPurgeProviderStore` | 26 (0x1a) | Exported Function | 0x000000018006f230 | 0x0006f230
`SyncMgrRemovePolicy` | 27 (0x1b) | Exported Function | 0x000000018006f320 | 0x0006f320
`SyncSqmUpdateStats` | 63 (0x3f) | Exported Function | 0x00000001800048b0 | 0x000048b0
`UpdateEasTrackingSchema` | 28 (0x1c) | Exported Function | 0x00000001800a0ba0 | 0x000a0ba0
`Ordinal1` | 1 (0x1) | Exported Function | 0x000000018006f160 | 0x0006f160
`WriteStoreCapabilityProps` | 29 (0x1d) | Exported Function | 0x0000000180071490 | 0x00071490
`OneStopFactory` | 21 (0x15) | Exported Function | 0x000000018000aac0 | 0x0000aac0
`IsValidOutlookExtensionVersion` | 17 (0x11) | Exported Function | 0x00000001800646a0 | 0x000646a0
`CreateSyncServiceLayer` | 4 (0x4) | Exported Function | 0x00000001800c2830 | 0x000c2830
`DllCanUnloadNow` | 5 (0x5) | Exported Function | 0x000000018000a900 | 0x0000a900
`DllGetClassObject` | 6 (0x6) | Exported Function | 0x000000018000a940 | 0x0000a940
`DownloadEmailAttachment` | 7 (0x7) | Exported Function | 0x000000018005dd50 | 0x0005dd50
`DownloadEmailBody` | 8 (0x8) | Exported Function | 0x000000018005e130 | 0x0005e130
`GetActiveSyncServerProbeInstance` | 9 (0x9) | Exported Function | 0x000000018009e790 | 0x0009e790
`GetConversationSyncEnabled` | 10 (0xa) | Exported Function | 0x000000018009e840 | 0x0009e840
`GetOutlookExtensionSupportForAccount` | 11 (0xb) | Exported Function | 0x0000000180064380 | 0x00064380
`GetOutlookExtensionSupportFromAccessor` | 12 (0xc) | Exported Function | 0x0000000180064480 | 0x00064480
`GetUserInfoForUnconfiguredAccount` | 13 (0xd) | Exported Function | 0x00000001800c3e40 | 0x000c3e40
`HandleEasMeetingResponseForAppointment` | 14 (0xe) | Exported Function | 0x000000018009f1d0 | 0x0009f1d0
`HandleEasMeetingResponseForMeetingNotification` | 15 (0xf) | Exported Function | 0x000000018009f460 | 0x0009f460
`InitializeSyncStatus` | 62 (0x3e) | Exported Function | 0x00000001800048a0 | 0x000048a0
`IsEnabledForSync` | 2 (0x2) | Exported Function | 0x00000001800a9810 | 0x000a9810
`IsErrorCatastrophic` | 16 (0x10) | Exported Function | 0x00000001800a0920 | 0x000a0920
`MarkPeopleFolderForResync` | 20 (0x14) | Exported Function | 0x00000001800a0b60 | 0x000a0b60
`WriteStoreContentTypesProps` | 30 (0x1e) | Exported Function | 0x0000000180071ed0 | 0x00071ed0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ActiveSyncProvider.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/33f0c24752ae99ba3b9e8adf4ac3441278afd42959bb761467f9846e4a44fbb6/detection/





MIT License. Copyright (c) 2020 Strontic.


