---
title: EventAggregation.dll | Event Aggregation User Mode Library
excerpt: What is EventAggregation.dll?
---

# EventAggregation.dll 

* File Path: `C:\Windows\system32\EventAggregation.dll`
* Description: Event Aggregation User Mode Library

## Hashes

Type | Hash
-- | --
MD5 | `334C85560A446B765CF56BDE471759DD`
SHA1 | `B2E36F43E6729B09961170A05452B4DB98A9B134`
SHA256 | `C3135EAD3A6229FE815DABB6560E529B652E4711FDFD732B39C5970BD023D0B6`
SHA384 | `BDC5C9E2B78C2079412E2454E0A3641E8639F8860A5E49CC25E05285F8931CB74660EAC3FCCEDBB10269640B933E52C1`
SHA512 | `234167F89FB2C2D78BA3C0361B4352A68015568992E33AB461579E7E59558330949E3A9A85ECB412C65D5C7FE1E74561636A3EB03189ABC85F7F2F6EBD9C4522`
SSDEEP | `1536:1ksAW5n7UYKO47TC2t1km92knTn1GhKc86:sW57UYtBm1kmsknTn1kKS`
IMP | `74742BDAB2F59D103E384D350219AC62`
PESHA1 | `1746DD68FA689AE81D7297A1C21D9A0B747FE4FF`
PE256 | `968880AAF929D896506936C9F86A2FB5159A357CAB55733AFF1132E26C2AF0D2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BriAllocateRpcBuffer` | 1 (0x1) | Exported Function | 0x0000000180006f20 | 0x00006f20
`EAQueryAggregateEventData` | 16 (0x10) | Exported Function | 0x00000001800047e0 | 0x000047e0
`EaQueryAggregateEventConditionState` | 29 (0x1d) | Exported Function | 0x00000001800064a0 | 0x000064a0
`EaQueryAggregatedEventParameters` | 31 (0x1f) | Exported Function | 0x000000018000aff0 | 0x0000aff0
`EaQueryAggregatedEvent` | 30 (0x1e) | Exported Function | 0x0000000180004c70 | 0x00004c70
`EaGetAggregation` | 28 (0x1c) | Exported Function | 0x0000000180005f10 | 0x00005f10
`EaFreeBuffer` | 27 (0x1b) | Exported Function | 0x0000000180008940 | 0x00008940
`EaFreeAggregatedEventParameters` | 26 (0x1a) | Exported Function | 0x0000000180009e50 | 0x00009e50
`EAEnumerateAggregateEvents` | 15 (0xf) | Exported Function | 0x0000000180004630 | 0x00004630
`EaEncodeBrokeredEvent` | 25 (0x19) | Exported Function | 0x0000000180008ed0 | 0x00008ed0
`EaEnableAggregatedEvent` | 24 (0x18) | Exported Function | 0x0000000180005f20 | 0x00005f20
`EaDisableAggregatedEvent` | 23 (0x17) | Exported Function | 0x0000000180006160 | 0x00006160
`EaDeleteAggregation` | 22 (0x16) | Exported Function | 0x0000000180005b80 | 0x00005b80
`EADeleteAggregateEvent` | 14 (0xe) | Exported Function | 0x00000001800045c0 | 0x000045c0
`EaDeleteAggregatedEventParameters` | 21 (0x15) | Exported Function | 0x000000018000b440 | 0x0000b440
`EaSignalAggregatedEvent` | 32 (0x20) | Exported Function | 0x0000000180004a00 | 0x00004a00
`EaDeleteAggregatedEvent` | 20 (0x14) | Exported Function | 0x0000000180006830 | 0x00006830
`EaCreateAggregation` | 18 (0x12) | Exported Function | 0x00000001800051f0 | 0x000051f0
`EACreateAggregateEvent` | 13 (0xd) | Exported Function | 0x0000000180003e50 | 0x00003e50
`EaCreateAggregatedEvent` | 17 (0x11) | Exported Function | 0x0000000180006e50 | 0x00006e50
`BriUnregisterFromBrokerAvailability` | 12 (0xc) | Exported Function | 0x0000000180008c20 | 0x00008c20
`BriSignalBrokeredEvent` | 11 (0xb) | Exported Function | 0x00000001800087f0 | 0x000087f0
`BriResolveBrokerIdByEventId` | 10 (0xa) | Exported Function | 0x0000000180008780 | 0x00008780
`BriRegisterToBrokerAvailability` | 9 (0x9) | Exported Function | 0x0000000180008ac0 | 0x00008ac0
`BriIsBrokerRegistered` | 8 (0x8) | Exported Function | 0x0000000180006f30 | 0x00006f30
`BriGetBrokerAvailabilityChangeStamp` | 7 (0x7) | Exported Function | 0x0000000180008970 | 0x00008970
`BriFreeRpcBuffer` | 6 (0x6) | Exported Function | 0x0000000180007d80 | 0x00007d80
`BriDeleteBrokeredEvent` | 5 (0x5) | Exported Function | 0x0000000180007c00 | 0x00007c00
`BriCreateBrokeredEventEx` | 4 (0x4) | Exported Function | 0x0000000180007300 | 0x00007300
`BriCreateBrokeredEvent` | 3 (0x3) | Exported Function | 0x00000001800072b0 | 0x000072b0
`BriCleanup` | 2 (0x2) | Exported Function | 0x0000000180007020 | 0x00007020
`EaDecodeBrokeredEvent` | 19 (0x13) | Exported Function | 0x0000000180008fc0 | 0x00008fc0
`EaStoreAggregatedEventParameters` | 33 (0x21) | Exported Function | 0x000000018000ad80 | 0x0000ad80


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: EventAggregation.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c3135ead3a6229fe815dabb6560e529b652e4711fdfd732b39c5970bd023d0b6/detection/





MIT License. Copyright (c) 2020 Strontic.


