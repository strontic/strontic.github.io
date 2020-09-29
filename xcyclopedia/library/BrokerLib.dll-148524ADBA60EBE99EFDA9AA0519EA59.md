---
title: BrokerLib.dll | Broker Base Library
excerpt: What is BrokerLib.dll?
---

# BrokerLib.dll 

* File Path: `C:\Windows\system32\BrokerLib.dll`
* Description: Broker Base Library

## Hashes

Type | Hash
-- | --
MD5 | `148524ADBA60EBE99EFDA9AA0519EA59`
SHA1 | `4E4993ED9EC7D1C3CE008B3B08E04B74410E2266`
SHA256 | `A643CBC761A6469BECE255398471391CCE26BA72BCDA2E4CB788C33AD5F0CE87`
SHA384 | `8184F23427936AB790511C11502A1FAE8D6780CDAEFEC1E8393A976256BA34CBCFBC8E24525C1B331F2DF8182165126C`
SHA512 | `FBCF3F6C537C6AFFB2DB65E9D72E042C696162F2F290C9FC3FE55FF8A53B5A65C33FBFDDD0BC5A9D8DE11162AAC499ADC48C11CCDD1B9A445EE054C2300473CF`
SSDEEP | `3072:jDGG3g0vQ0LKArx+YDP1ruoIb9VHbwTtMGWt5YdPyFV2JEvzBH+H01Y5laO:z33Vd1+SP1rGOGGWe9JErdnY5l`
IMP | `6B30F801CACBBC981F3BD7847A9214C5`
PESHA1 | `79B616BA2765F13A7553D4015E00865BAA7E3453`
PE256 | `75BCDE12228F0BED65C18054263DCACEFFCCB6C061C6A97C91871D68259EB1B6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BrBufferFree` | 2 (0x2) | Exported Function | 0x0000000180001aa0 | 0x00001aa0
`BrGetQuota` | 21 (0x15) | Exported Function | 0x000000018001e770 | 0x0001e770
`BrIncQuota` | 22 (0x16) | Exported Function | 0x000000018001ea10 | 0x0001ea10
`BrInitializeBrokerInstance` | 23 (0x17) | Exported Function | 0x000000018000cef0 | 0x0000cef0
`BrInitializeBrokerInstance2` | 24 (0x18) | Exported Function | 0x000000018000dec0 | 0x0000dec0
`BrLockBroker` | 25 (0x19) | Exported Function | 0x0000000180001970 | 0x00001970
`BrQueryBrokeredApplicationState` | 26 (0x1a) | Exported Function | 0x0000000180003590 | 0x00003590
`BrQueryBrokeredEvents` | 27 (0x1b) | Exported Function | 0x000000018000a440 | 0x0000a440
`BrQueryBrokeredEvents2` | 28 (0x1c) | Exported Function | 0x0000000180001ca0 | 0x00001ca0
`BrRegisterBrokeredEvent` | 29 (0x1d) | Exported Function | 0x000000018001ecd0 | 0x0001ecd0
`BrRegisterStateChangeCallbacks` | 30 (0x1e) | Exported Function | 0x0000000180011140 | 0x00011140
`BrSendActivatorControl` | 31 (0x1f) | Exported Function | 0x000000018001eea0 | 0x0001eea0
`BrSetBrokeredAppStateName` | 32 (0x20) | Exported Function | 0x000000018001f030 | 0x0001f030
`BrSignalBrokerEvent` | 33 (0x21) | Exported Function | 0x000000018001f180 | 0x0001f180
`BrSignalBrokerEvent2` | 34 (0x22) | Exported Function | 0x0000000180001520 | 0x00001520
`BrSignalBrokerEvent2Ex` | 35 (0x23) | Exported Function | 0x0000000180001550 | 0x00001550
`BrGetPackageFullNameForBrokeredEvent` | 20 (0x14) | Exported Function | 0x000000018001e520 | 0x0001e520
`BrUnlockBroker` | 36 (0x24) | Exported Function | 0x00000001800018e0 | 0x000018e0
`BrGetBrokeredEventState` | 19 (0x13) | Exported Function | 0x0000000180008790 | 0x00008790
`BrGetBrokeredAppStateName` | 17 (0x11) | Exported Function | 0x000000018001e3c0 | 0x0001e3c0
`BrCheckCallerCapabilities` | 3 (0x3) | Exported Function | 0x000000018001d530 | 0x0001d530
`BrCheckCallerCapabilities2` | 4 (0x4) | Exported Function | 0x000000018001d770 | 0x0001d770
`BrCheckCallerIsAppContainer` | 5 (0x5) | Exported Function | 0x000000018001d980 | 0x0001d980
`BrCreateBrokeredEvent` | 8 (0x8) | Exported Function | 0x000000018001db20 | 0x0001db20
`BrCreateBrokeredEvent2` | 1 (0x1) | Exported Function | 0x000000018001d2a0 | 0x0001d2a0
`BrCreateBrokerInstance` | 6 (0x6) | Exported Function | 0x000000018000cf60 | 0x0000cf60
`BrCreateBrokerInstance2` | 7 (0x7) | Exported Function | 0x000000018000cff0 | 0x0000cff0
`BrDecQuota` | 9 (0x9) | Exported Function | 0x000000018001dcc0 | 0x0001dcc0
`BrDeleteBrokeredEvent` | 11 (0xb) | Exported Function | 0x000000018001df80 | 0x0001df80
`BrDeleteBrokeredEvent2` | 12 (0xc) | Exported Function | 0x000000018001e0b0 | 0x0001e0b0
`BrDeleteBrokerInstance` | 10 (0xa) | Exported Function | 0x000000018000e4d0 | 0x0000e4d0
`BrFindBrokeredEvent` | 13 (0xd) | Exported Function | 0x0000000180008340 | 0x00008340
`BrFindBrokeredEvent2` | 14 (0xe) | Exported Function | 0x0000000180008990 | 0x00008990
`BrGetBrokeredAppState` | 15 (0xf) | Exported Function | 0x000000018001e240 | 0x0001e240
`BrGetBrokeredAppState2` | 16 (0x10) | Exported Function | 0x00000001800036f0 | 0x000036f0
`BrGetBrokeredEventInfo2` | 18 (0x12) | Exported Function | 0x00000001800013f0 | 0x000013f0
`BrUnregisterBrokeredEvent` | 37 (0x25) | Exported Function | 0x000000018001f3b0 | 0x0001f3b0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BrokerLib.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/a643cbc761a6469bece255398471391cce26ba72bcda2e4cb788c33ad5f0ce87/detection/





MIT License. Copyright (c) 2020 Strontic.


