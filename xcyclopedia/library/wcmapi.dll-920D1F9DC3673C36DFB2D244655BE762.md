---
title: wcmapi.dll | Windows Connection Manager Client API
excerpt: What is wcmapi.dll?
---

# wcmapi.dll 

* File Path: `C:\Windows\SysWOW64\wcmapi.dll`
* Description: Windows Connection Manager Client API

## Hashes

Type | Hash
-- | --
MD5 | `920D1F9DC3673C36DFB2D244655BE762`
SHA1 | `CE0669E828408E2F4036DE9731B8B3E4E1993345`
SHA256 | `ECEF312E76DC17F483CF29DE7C6CDCC63728D67042E3A8E4B8237553A112A98C`
SHA384 | `155833F8445B75B7983B3155BD3493235A03098CFFA9513A0B3D4D6F4CF51FB8783D1B8FE76E155DF84BE6B9D95E7E70`
SHA512 | `45953B7EE971D6C40FDC9F17B1152013768F9AB4EC91284F052B997242E80D725C87C7784939171661690A96F5B9F411D4E6AAAC88C00D6877F4369BC59EFCA6`
SSDEEP | `3072:TDCJeGqDWoSYsZJUCI7Ir+qXjgECFSCWmESuJN:TJGOLSYseIHXk/y7SuJ`
IMP | `CE1EA40512C0C6FF5C5672B0D3042594`
PESHA1 | `30E971181A48D871AAC1F4DBDFE9B469F6ABA299`
PE256 | `8C8027AEB2F7E9C749B98F2F11203CB08CD0F0C844480A4A36B362E0B21F6CE5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x1000de70 | 0x0000de70
`WcmGetRoutingHint` | 24 (0x18) | Exported Function | 0x10011ab0 | 0x00011ab0
`WcmOpenHandle` | 25 (0x19) | Exported Function | 0x10006ec0 | 0x00006ec0
`WcmOpenOnDemandRequestHandle` | 26 (0x1a) | Exported Function | 0x10011c50 | 0x00011c50
`WcmOpenOnDemandRequestHandleByWwanProfileName` | 27 (0x1b) | Exported Function | 0x10012040 | 0x00012040
`WcmOrderConnection` | 28 (0x1c) | Exported Function | 0x100123d0 | 0x000123d0
`WcmQueryOnDemandRequestStateInfo` | 29 (0x1d) | Exported Function | 0x100125a0 | 0x000125a0
`WcmQueryParameter` | 30 (0x1e) | Exported Function | 0x10006ca0 | 0x00006ca0
`WcmQueryProperty` | 31 (0x1f) | Exported Function | 0x10012830 | 0x00012830
`WcmGetProfileListByPurpose` | 23 (0x17) | Exported Function | 0x10011880 | 0x00011880
`WcmRemoveMatchingRoutePolicy` | 32 (0x20) | Exported Function | 0x10012a30 | 0x00012a30
`WcmResetIgnoreProfileList` | 34 (0x22) | Exported Function | 0x10012cb0 | 0x00012cb0
`WcmSetOperatorConnectionCost` | 35 (0x23) | Exported Function | 0x10012e80 | 0x00012e80
`WcmSetOperatorCycleData` | 36 (0x24) | Exported Function | 0x10013010 | 0x00013010
`WcmSetOperatorDataplanStatus` | 37 (0x25) | Exported Function | 0x10013190 | 0x00013190
`WcmSetParameter` | 38 (0x26) | Exported Function | 0x10013320 | 0x00013320
`WcmSetProfileList` | 39 (0x27) | Exported Function | 0x10013570 | 0x00013570
`WcmSetProperty` | 40 (0x28) | Exported Function | 0x100137d0 | 0x000137d0
`WcmSetProxyInformation` | 41 (0x29) | Exported Function | 0x10009fa0 | 0x00009fa0
`WcmRemoveRoutePolicy` | 33 (0x21) | Exported Function | 0x10012b90 | 0x00012b90
`WcmStartOnDemandRequest` | 42 (0x2a) | Exported Function | 0x10013990 | 0x00013990
`WcmGetProfileList` | 22 (0x16) | Exported Function | 0x10011710 | 0x00011710
`WcmGetInterfaceContextTable` | 20 (0x14) | Exported Function | 0x10007540 | 0x00007540
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x1000de90 | 0x0000de90
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x100087d0 | 0x000087d0
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x100087d0 | 0x000087d0
`WcmAddRoutePolicy` | 5 (0x5) | Exported Function | 0x10010430 | 0x00010430
`WcmBeginIgnoreProfileList` | 6 (0x6) | Exported Function | 0x100105e0 | 0x000105e0
`WcmCancelOnDemandRequest` | 7 (0x7) | Exported Function | 0x100107c0 | 0x000107c0
`WcmCheckCapabilityStatus` | 8 (0x8) | Exported Function | 0x10009b50 | 0x00009b50
`WcmCloseHandle` | 9 (0x9) | Exported Function | 0x10007090 | 0x00007090
`WcmGetInterfaceToken` | 21 (0x15) | Exported Function | 0x10011540 | 0x00011540
`WcmCloseOnDemandRequestHandle` | 10 (0xa) | Exported Function | 0x10010a40 | 0x00010a40
`WcmDeprovisionCapability` | 12 (0xc) | Exported Function | 0x10009e20 | 0x00009e20
`WcmEndIgnoreProfileList` | 13 (0xd) | Exported Function | 0x10010cd0 | 0x00010cd0
`WcmEnterConnectedStandby` | 14 (0xe) | Exported Function | 0x10010e90 | 0x00010e90
`WcmEnterNetQuiet` | 15 (0xf) | Exported Function | 0x10010fc0 | 0x00010fc0
`WcmEnumInterfaces` | 16 (0x10) | Exported Function | 0x100110e0 | 0x000110e0
`WcmExitConnectedStandby` | 17 (0x11) | Exported Function | 0x10011300 | 0x00011300
`WcmExitNetQuiet` | 18 (0x12) | Exported Function | 0x10011420 | 0x00011420
`WcmFreeMemory` | 19 (0x13) | Exported Function | 0x100076b0 | 0x000076b0
`WcmDeleteProxyInformation` | 11 (0xb) | Exported Function | 0x10009cb0 | 0x00009cb0
`WcmUpdateCapabilityAccess` | 43 (0x2b) | Exported Function | 0x1000a120 | 0x0000a120


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ecef312e76dc17f483cf29de7c6cdcc63728d67042e3a8e4b8237553a112a98c/detection/





MIT License. Copyright (c) 2020 Strontic.


