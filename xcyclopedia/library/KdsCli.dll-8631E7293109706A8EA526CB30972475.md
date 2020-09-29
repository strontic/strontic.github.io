---
title: KdsCli.dll | Microsoft Key Distribution Service Provider
excerpt: What is KdsCli.dll?
---

# KdsCli.dll 

* File Path: `C:\Windows\system32\KdsCli.dll`
* Description: Microsoft Key Distribution Service Provider

## Hashes

Type | Hash
-- | --
MD5 | `8631E7293109706A8EA526CB30972475`
SHA1 | `FACB397121BDFD3312D4E2C93AEA558E0D62016A`
SHA256 | `8CD6253B881A81B7515B1CA24081D155818608B8EA602403C5B23612DBB813E1`
SHA384 | `BF0ED690E5F463C611F52C3FE857F5BD4DF07F8EB63DEAB794241E4AA9D96426CE9A059AAD25681B2D685E3639D9D323`
SHA512 | `FDDD54A01D39A15DDEBD966223891305DFA5812D293E0627D8876C9EB17681EFDBCB54FAD9EAF192A54C2B7F8676B68E9AEC840D145EAC12ABE4CBD2CD5EA34C`
SSDEEP | `1536:mlhfV/3REB7Bw0+3BU7m2gzUcE0bMA3vBAvXq4Snuf98StJbFFrFOQwV6:mHfB3qnw0jRMlE0bMApA/q4Snuf98St7`
IMP | `2EFC17811CD8FF0304CC17CC598AAD1D`
PESHA1 | `31DD83CB3D362B4C60449719ADC1F243286E53E8`
PE256 | `2304925FB643A38D07C5D1394066C6F4ECAC300ECEE7186C9410436CC3206BBB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateRootKey` | 1 (0x1) | Exported Function | 0x0000000180003080 | 0x00003080
`GetKey` | 27 (0x1b) | Exported Function | 0x000000018000b660 | 0x0000b660
`GetLdapBinding` | 28 (0x1c) | Exported Function | 0x0000000180001230 | 0x00001230
`GetMRKPath` | 29 (0x1d) | Exported Function | 0x00000001800022d0 | 0x000022d0
`GetRootKey` | 30 (0x1e) | Exported Function | 0x00000001800048e0 | 0x000048e0
`GetServerConfig` | 33 (0x21) | Exported Function | 0x0000000180005a00 | 0x00005a00
`GetSIDKeyCacheFolder` | 31 (0x1f) | Exported Function | 0x00000001800062f0 | 0x000062f0
`GetSIDKeyFileName` | 32 (0x20) | Exported Function | 0x0000000180006670 | 0x00006670
`GetUserSidStr` | 34 (0x22) | Exported Function | 0x000000018000ab40 | 0x0000ab40
`KdsCreateClientBinding` | 35 (0x23) | Exported Function | 0x0000000180009980 | 0x00009980
`GetKDSSrvConfigPath` | 25 (0x19) | Exported Function | 0x00000001800021e0 | 0x000021e0
`KdsGetEpochLength` | 36 (0x24) | Exported Function | 0x000000018000bb30 | 0x0000bb30
`KdsGetGmsaPasswordBasedOnTimestamp` | 38 (0x26) | Exported Function | 0x000000018000c320 | 0x0000c320
`KdsGetKeyStartTime` | 39 (0x27) | Exported Function | 0x000000018000bab0 | 0x0000bab0
`SetServerConfig` | 44 (0x2c) | Exported Function | 0x0000000180005e30 | 0x00005e30
`SIDKeyProtect` | 40 (0x28) | Exported Function | 0x000000018000c810 | 0x0000c810
`SIDKeyProvAlloc` | 41 (0x29) | Exported Function | 0x000000018000a620 | 0x0000a620
`SIDKeyProvFree` | 42 (0x2a) | Exported Function | 0x000000018000a660 | 0x0000a660
`SIDKeyUnprotect` | 43 (0x2b) | Exported Function | 0x000000018000cda0 | 0x0000cda0
`TestServerConfig` | 45 (0x2d) | Exported Function | 0x0000000180008630 | 0x00008630
`UnlockRpcCache` | 46 (0x2e) | Exported Function | 0x000000018000a5d0 | 0x0000a5d0
`KdsGetGmsaPasswordBasedOnKeyId` | 37 (0x25) | Exported Function | 0x000000018000c330 | 0x0000c330
`GetKdsKeyCycleDuration` | 26 (0x1a) | Exported Function | 0x000000018000b550 | 0x0000b550
`GetIntervalStartTime` | 24 (0x18) | Exported Function | 0x000000018000ada0 | 0x0000ada0
`GetFullDCName` | 23 (0x17) | Exported Function | 0x000000018000b450 | 0x0000b450
`DeleteAllCachedKeys` | 2 (0x2) | Exported Function | 0x0000000180007db0 | 0x00007db0
`FindAndReadSIDKeyInCache` | 3 (0x3) | Exported Function | 0x0000000180007440 | 0x00007440
`FindKeyForOfflineUsage` | 4 (0x4) | Exported Function | 0x0000000180007880 | 0x00007880
`FreeRootKey` | 5 (0x5) | Exported Function | 0x0000000180002e00 | 0x00002e00
`FreeRootKeyConfig` | 6 (0x6) | Exported Function | 0x0000000180002d80 | 0x00002d80
`FreeRootKeyMetaDataList` | 7 (0x7) | Exported Function | 0x0000000180004b50 | 0x00004b50
`FreeServerConfig` | 8 (0x8) | Exported Function | 0x0000000180004f20 | 0x00004f20
`GenerateDerivedKey` | 9 (0x9) | Exported Function | 0x00000001800082d0 | 0x000082d0
`GenerateEphemeralKeyPair` | 10 (0xa) | Exported Function | 0x0000000180008e70 | 0x00008e70
`GenerateKDFContext` | 11 (0xb) | Exported Function | 0x00000001800081f0 | 0x000081f0
`GenerateSecretAgreementPrivateKey` | 13 (0xd) | Exported Function | 0x0000000180008840 | 0x00008840
`GenerateSIDPublicKeyBlob` | 12 (0xc) | Exported Function | 0x00000001800091b0 | 0x000091b0
`GetAllRootKeys` | 14 (0xe) | Exported Function | 0x0000000180004980 | 0x00004980
`GetAllRootKeysMetaData` | 15 (0xf) | Exported Function | 0x0000000180004c90 | 0x00004c90
`GetAndLockCachedRPCBinding` | 16 (0x10) | Exported Function | 0x000000018000a4d0 | 0x0000a4d0
`GetCachedMachineDomainInfo` | 17 (0x11) | Exported Function | 0x000000018000b260 | 0x0000b260
`GetCurrentIntervalID` | 18 (0x12) | Exported Function | 0x000000018000ad30 | 0x0000ad30
`GetCurrentL0ID` | 19 (0x13) | Exported Function | 0x000000018000ace0 | 0x0000ace0
`GetCurrentTimeInULL` | 20 (0x14) | Exported Function | 0x000000018000ac80 | 0x0000ac80
`GetDCInfo` | 21 (0x15) | Exported Function | 0x00000001800016d0 | 0x000016d0
`GetDefaultServerConfig` | 22 (0x16) | Exported Function | 0x0000000180005950 | 0x00005950
`ValidateSrvConfig` | 47 (0x2f) | Exported Function | 0x0000000180005af0 | 0x00005af0
`WriteSIDKeyInCache` | 48 (0x30) | Exported Function | 0x00000001800069d0 | 0x000069d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: KdsCli.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/8cd6253b881a81b7515b1ca24081d155818608b8ea602403c5b23612dbb813e1/detection/





MIT License. Copyright (c) 2020 Strontic.


