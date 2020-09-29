---
title: wcmapi.dll | Windows Connection Manager Client API
excerpt: What is wcmapi.dll?
---

# wcmapi.dll 

* File Path: `C:\Windows\system32\wcmapi.dll`
* Description: Windows Connection Manager Client API

## Hashes

Type | Hash
-- | --
MD5 | `A380F826576F4BAE3CB92D541C8274BB`
SHA1 | `FAA6D8B5CE7E56ECA4B3F6B20B1B05AAAAE3ABFA`
SHA256 | `2584A6D8C5D3C5BB77BF76C84521AD268A7956586FA607DFADD14A577F66A440`
SHA384 | `01A972A3EAF6D214FFF87CC4D732D6CFFE4ABFF005CF570F12A30288F03E476A749F9C41E285BFA57EEBCDD97B0B3E26`
SHA512 | `058D396620583285EAF190E03258206EBC0B9C32A1AA4E2C35FAA6A741990181D48954C50E8A7DEDF56448700175FACC94CEF5C054C7AC706B5617E4FF7AF023`
SSDEEP | `1536:BcSKlOIAB3hS347kXpSS10jP6H+BAqvWUZECzfIue4IBDE+gHBQvQyZ9hS+a8pe+:K+UnXwKd2E74IGbHBQvlZr4CZvuToNd`
IMP | `4F39B456EDE6BB4289C0303F71C2643A`
PESHA1 | `E920EDE398F53BA496A7D58CAD3C760BD080D573`
PE256 | `D84772C25B1BD4BBF8138CFA3B6BF9A54C04B12E1602D1688F6D8386EB23C0A9`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180007c50 | 0x00007c50
`WcmGetRoutingHint` | 24 (0x18) | Exported Function | 0x000000018000d710 | 0x0000d710
`WcmOpenHandle` | 25 (0x19) | Exported Function | 0x000000018000d920 | 0x0000d920
`WcmOpenOnDemandRequestHandle` | 26 (0x1a) | Exported Function | 0x000000018000dc90 | 0x0000dc90
`WcmOpenOnDemandRequestHandleByWwanProfileName` | 27 (0x1b) | Exported Function | 0x000000018000e180 | 0x0000e180
`WcmOrderConnection` | 28 (0x1c) | Exported Function | 0x000000018000e580 | 0x0000e580
`WcmQueryOnDemandRequestStateInfo` | 29 (0x1d) | Exported Function | 0x000000018000e7b0 | 0x0000e7b0
`WcmQueryParameter` | 30 (0x1e) | Exported Function | 0x000000018000ea90 | 0x0000ea90
`WcmQueryProperty` | 31 (0x1f) | Exported Function | 0x000000018000ee10 | 0x0000ee10
`WcmGetProfileListByPurpose` | 23 (0x17) | Exported Function | 0x000000018000d490 | 0x0000d490
`WcmRemoveMatchingRoutePolicy` | 32 (0x20) | Exported Function | 0x000000018000f0c0 | 0x0000f0c0
`WcmResetIgnoreProfileList` | 34 (0x22) | Exported Function | 0x000000018000f3e0 | 0x0000f3e0
`WcmSetOperatorConnectionCost` | 35 (0x23) | Exported Function | 0x000000018000f610 | 0x0000f610
`WcmSetOperatorCycleData` | 36 (0x24) | Exported Function | 0x000000018000f7f0 | 0x0000f7f0
`WcmSetOperatorDataplanStatus` | 37 (0x25) | Exported Function | 0x000000018000f9c0 | 0x0000f9c0
`WcmSetParameter` | 38 (0x26) | Exported Function | 0x000000018000fba0 | 0x0000fba0
`WcmSetProfileList` | 39 (0x27) | Exported Function | 0x000000018000fec0 | 0x0000fec0
`WcmSetProperty` | 40 (0x28) | Exported Function | 0x00000001800101a0 | 0x000101a0
`WcmSetProxyInformation` | 41 (0x29) | Exported Function | 0x0000000180010400 | 0x00010400
`WcmRemoveRoutePolicy` | 33 (0x21) | Exported Function | 0x000000018000f290 | 0x0000f290
`WcmStartOnDemandRequest` | 42 (0x2a) | Exported Function | 0x00000001800105d0 | 0x000105d0
`WcmGetProfileList` | 22 (0x16) | Exported Function | 0x000000018000d2e0 | 0x0000d2e0
`WcmGetInterfaceContextTable` | 20 (0x14) | Exported Function | 0x0000000180002e40 | 0x00002e40
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x0000000180007c70 | 0x00007c70
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x0000000180003310 | 0x00003310
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x0000000180003310 | 0x00003310
`WcmAddRoutePolicy` | 5 (0x5) | Exported Function | 0x000000018000b620 | 0x0000b620
`WcmBeginIgnoreProfileList` | 6 (0x6) | Exported Function | 0x000000018000b840 | 0x0000b840
`WcmCancelOnDemandRequest` | 7 (0x7) | Exported Function | 0x000000018000ba70 | 0x0000ba70
`WcmCheckCapabilityStatus` | 8 (0x8) | Exported Function | 0x000000018000bd30 | 0x0000bd30
`WcmCloseHandle` | 9 (0x9) | Exported Function | 0x000000018000bed0 | 0x0000bed0
`WcmGetInterfaceToken` | 21 (0x15) | Exported Function | 0x000000018000d0d0 | 0x0000d0d0
`WcmCloseOnDemandRequestHandle` | 10 (0xa) | Exported Function | 0x000000018000c0c0 | 0x0000c0c0
`WcmDeprovisionCapability` | 12 (0xc) | Exported Function | 0x000000018000c560 | 0x0000c560
`WcmEndIgnoreProfileList` | 13 (0xd) | Exported Function | 0x000000018000c730 | 0x0000c730
`WcmEnterConnectedStandby` | 14 (0xe) | Exported Function | 0x000000018000c930 | 0x0000c930
`WcmEnterNetQuiet` | 15 (0xf) | Exported Function | 0x000000018000ca70 | 0x0000ca70
`WcmEnumInterfaces` | 16 (0x10) | Exported Function | 0x000000018000cbb0 | 0x0000cbb0
`WcmExitConnectedStandby` | 17 (0x11) | Exported Function | 0x000000018000ce50 | 0x0000ce50
`WcmExitNetQuiet` | 18 (0x12) | Exported Function | 0x000000018000cf90 | 0x0000cf90
`WcmFreeMemory` | 19 (0x13) | Exported Function | 0x0000000180003130 | 0x00003130
`WcmDeleteProxyInformation` | 11 (0xb) | Exported Function | 0x000000018000c3a0 | 0x0000c3a0
`WcmUpdateCapabilityAccess` | 43 (0x2b) | Exported Function | 0x00000001800109f0 | 0x000109f0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wcmapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/2584a6d8c5d3c5bb77bf76c84521ad268a7956586fa607dfadd14a577f66a440/detection/





MIT License. Copyright (c) 2020 Strontic.


