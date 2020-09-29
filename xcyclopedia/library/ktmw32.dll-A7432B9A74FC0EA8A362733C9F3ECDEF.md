---
title: ktmw32.dll | Windows KTM Win32 Client DLL
excerpt: What is ktmw32.dll?
---

# ktmw32.dll 

* File Path: `C:\Windows\system32\ktmw32.dll`
* Description: Windows KTM Win32 Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `A7432B9A74FC0EA8A362733C9F3ECDEF`
SHA1 | `0B3129B53D0CE4DAE277FE488AE93E00DC7C8906`
SHA256 | `6CC284E887523BC16616E71FF86C2DE2CD8026A962CF507F8AE14CDCD2CECFAE`
SHA384 | `0DA4C6396950D6CFA877A2BF3A60C50A0B6DBE3FCA7F883ACC1EB4C49083E85D700BE4F2F1FD21451BF5267C51FB987C`
SHA512 | `213C4C174FA76749225B722571C2121FFE6990652C068347D4CF4F322A672154CCC186E4073B36C35D2E38415B543636A92211E5CBF47C8717329B9D0FADE782`
SSDEEP | `192:9L0cxHBZEC+SxAkKb+F9AfmV+YM8ekPI+LyEtTuKep77WHfW7Z2Sp0ELW:9YurAkKzOV+tGrlT0p77WHfW4Spx`
IMP | `387008A82F48064617654BFD0C938DE6`
PESHA1 | `13D0FB17F5528008F9E1805CCF182D23AFFB0510`
PE256 | `0A36B6C46952B0FD8F7D2370AF19CBCF73F7FB8FF1A8BC9EBEBCDA0382A61120`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CommitComplete` | 1 (0x1) | Exported Function | 0x00000001800019e0 | 0x000019e0
`PrePrepareEnlistment` | 23 (0x17) | Exported Function | 0x00000001800012a0 | 0x000012a0
`PrivCreateTransaction` | 26 (0x1a) | Exported Function | 0x0000000180001010 | 0x00001010
`PrivIsLogWritableTransactionManager` | 27 (0x1b) | Exported Function | 0x00000001800020c0 | 0x000020c0
`PrivPropagationComplete` | 28 (0x1c) | Exported Function | 0x0000000180002810 | 0x00002810
`PrivPropagationFailed` | 29 (0x1d) | Exported Function | 0x0000000180002860 | 0x00002860
`PrivRegisterProtocolAddressInformation` | 30 (0x1e) | Exported Function | 0x00000001800027c0 | 0x000027c0
`ReadOnlyEnlistment` | 31 (0x1f) | Exported Function | 0x0000000180001990 | 0x00001990
`RecoverEnlistment` | 32 (0x20) | Exported Function | 0x0000000180002630 | 0x00002630
`PrePrepareComplete` | 22 (0x16) | Exported Function | 0x00000001800018f0 | 0x000018f0
`RecoverResourceManager` | 33 (0x21) | Exported Function | 0x00000001800022d0 | 0x000022d0
`RenameTransactionManager` | 35 (0x23) | Exported Function | 0x0000000180001e20 | 0x00001e20
`RollbackComplete` | 36 (0x24) | Exported Function | 0x0000000180001a30 | 0x00001a30
`RollbackEnlistment` | 37 (0x25) | Exported Function | 0x0000000180001340 | 0x00001340
`RollbackTransaction` | 38 (0x26) | Exported Function | 0x0000000180001430 | 0x00001430
`RollbackTransactionAsync` | 39 (0x27) | Exported Function | 0x0000000180001480 | 0x00001480
`RollforwardTransactionManager` | 40 (0x28) | Exported Function | 0x0000000180001f00 | 0x00001f00
`SetEnlistmentRecoveryInformation` | 41 (0x29) | Exported Function | 0x00000001800026e0 | 0x000026e0
`SetResourceManagerCompletionPort` | 42 (0x2a) | Exported Function | 0x0000000180002440 | 0x00002440
`RecoverTransactionManager` | 34 (0x22) | Exported Function | 0x0000000180001f50 | 0x00001f50
`PrepareEnlistment` | 25 (0x19) | Exported Function | 0x0000000180001250 | 0x00001250
`PrepareComplete` | 24 (0x18) | Exported Function | 0x0000000180001940 | 0x00001940
`OpenTransactionManagerById` | 21 (0x15) | Exported Function | 0x0000000180001d80 | 0x00001d80
`CommitEnlistment` | 2 (0x2) | Exported Function | 0x00000001800012f0 | 0x000012f0
`CommitTransaction` | 3 (0x3) | Exported Function | 0x0000000180001390 | 0x00001390
`CommitTransactionAsync` | 4 (0x4) | Exported Function | 0x00000001800013e0 | 0x000013e0
`CreateEnlistment` | 5 (0x5) | Exported Function | 0x00000001800024a0 | 0x000024a0
`CreateResourceManager` | 6 (0x6) | Exported Function | 0x0000000180002110 | 0x00002110
`CreateTransaction` | 7 (0x7) | Exported Function | 0x0000000180001170 | 0x00001170
`CreateTransactionManager` | 8 (0x8) | Exported Function | 0x0000000180001ad0 | 0x00001ad0
`GetCurrentClockTransactionManager` | 9 (0x9) | Exported Function | 0x0000000180001fa0 | 0x00001fa0
`GetEnlistmentId` | 10 (0xa) | Exported Function | 0x0000000180002730 | 0x00002730
`GetEnlistmentRecoveryInformation` | 11 (0xb) | Exported Function | 0x0000000180002680 | 0x00002680
`GetNotificationResourceManager` | 12 (0xc) | Exported Function | 0x0000000180002320 | 0x00002320
`GetNotificationResourceManagerAsync` | 13 (0xd) | Exported Function | 0x00000001800023b0 | 0x000023b0
`GetTransactionId` | 14 (0xe) | Exported Function | 0x00000001800014d0 | 0x000014d0
`GetTransactionInformation` | 15 (0xf) | Exported Function | 0x0000000180001560 | 0x00001560
`GetTransactionManagerId` | 16 (0x10) | Exported Function | 0x0000000180002030 | 0x00002030
`OpenEnlistment` | 17 (0x11) | Exported Function | 0x0000000180002590 | 0x00002590
`OpenResourceManager` | 18 (0x12) | Exported Function | 0x0000000180002230 | 0x00002230
`OpenTransaction` | 19 (0x13) | Exported Function | 0x00000001800011b0 | 0x000011b0
`OpenTransactionManager` | 20 (0x14) | Exported Function | 0x0000000180001c60 | 0x00001c60
`SetTransactionInformation` | 43 (0x2b) | Exported Function | 0x0000000180001730 | 0x00001730
`SinglePhaseReject` | 44 (0x2c) | Exported Function | 0x0000000180001a80 | 0x00001a80


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktmw32
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/6cc284e887523bc16616e71ff86c2de2cd8026a962cf507f8ae14cdcd2cecfae/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ktmw32.dll](ktmw32.dll-8C44C06934BA22FF7B27B58882999788.md) | 38




MIT License. Copyright (c) 2020 Strontic.


