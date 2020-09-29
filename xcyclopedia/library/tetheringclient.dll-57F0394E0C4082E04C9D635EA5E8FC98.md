---
title: tetheringclient.dll | Tethering Client
excerpt: What is tetheringclient.dll?
---

# tetheringclient.dll 

* File Path: `C:\Windows\system32\tetheringclient.dll`
* Description: Tethering Client

## Hashes

Type | Hash
-- | --
MD5 | `57F0394E0C4082E04C9D635EA5E8FC98`
SHA1 | `DF9779AAF47019EE0CB8B8FCBE6510A3D6B29BF5`
SHA256 | `8EF6E578C77CAA6C47C512BA733B6532AC21D34F396632D8FF5EE7DECA47846A`
SHA384 | `4EAD8797004CD1CB4E04BE98A7088D5AE0BC888DED2216454B633B15E2C367388151E72690A2F4A914D442E1A9C01D89`
SHA512 | `F8CD179D9F3F8625736D64236D8451EA9CFE16CC0A25EF3A844FD15D408E8DCA2858226B70E4377D589016BEAB30B7CA936A6613A5E49152F8C99BD523F6BDC1`
SSDEEP | `1536:lSHcfDBYCUsn4OpOgLjgVKGmEBCLpakUg:oQqzijguLLpakUg`
IMP | `D710B5319731543F3ADD057E2A6E2943`
PESHA1 | `595A46E4C943166598EB5DD2DDB1E1ECF49279F3`
PE256 | `882ADDC1666F2D270422980DD759F1B9E4068063ABF8CB1BCB7FD960AC4CA307`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`TetheringAuthorize` | 2 (0x2) | Exported Function | 0x0000000180001c70 | 0x00001c70
`TetheringStopSharing` | 30 (0x1e) | Exported Function | 0x0000000180001730 | 0x00001730
`TetheringStartSharingAsync` | 29 (0x1d) | Exported Function | 0x0000000180001720 | 0x00001720
`TetheringStartSharing` | 28 (0x1c) | Exported Function | 0x0000000180001710 | 0x00001710
`TetheringSetSharingStateAsync` | 27 (0x1b) | Exported Function | 0x00000001800016f0 | 0x000016f0
`TetheringSetSharingState` | 26 (0x1a) | Exported Function | 0x00000001800016f0 | 0x000016f0
`TetheringSetPublicConnectionSettings` | 25 (0x19) | Exported Function | 0x00000001800019b0 | 0x000019b0
`TetheringSetPrivateConnectionSettingsAsync` | 24 (0x18) | Exported Function | 0x00000001800019f0 | 0x000019f0
`TetheringSetPrivateConnectionSettings` | 23 (0x17) | Exported Function | 0x00000001800019d0 | 0x000019d0
`TetheringSetPreferredInterface` | 22 (0x16) | Exported Function | 0x0000000180001cb0 | 0x00001cb0
`TetheringSetIsPeerlessTimeoutEnabled` | 21 (0x15) | Exported Function | 0x0000000180001d10 | 0x00001d10
`TetheringRegisterNotification` | 20 (0x14) | Exported Function | 0x0000000180001b40 | 0x00001b40
`TetheringIsAllowed` | 19 (0x13) | Exported Function | 0x0000000180001760 | 0x00001760
`TetheringIs5GHzSupported` | 18 (0x12) | Exported Function | 0x0000000180001790 | 0x00001790
`TetheringInitApi` | 17 (0x11) | Exported Function | 0x0000000180001660 | 0x00001660
`TetheringGetSharingState` | 16 (0x10) | Exported Function | 0x00000001800016e0 | 0x000016e0
`TetheringGetSharedInterfaceIndices` | 1 (0x1) | Exported Function | 0x0000000180001c60 | 0x00001c60
`TetheringGetPublicConnectionSettings` | 15 (0xf) | Exported Function | 0x00000001800017b0 | 0x000017b0
`TetheringGetPrivateConnectionSettings` | 14 (0xe) | Exported Function | 0x00000001800018b0 | 0x000018b0
`TetheringGetPreferredInterface` | 13 (0xd) | Exported Function | 0x0000000180001cd0 | 0x00001cd0
`TetheringGetPeerList` | 12 (0xc) | Exported Function | 0x0000000180001a10 | 0x00001a10
`TetheringGetMaxClientCount` | 11 (0xb) | Exported Function | 0x0000000180001a50 | 0x00001a50
`TetheringGetLastApiError` | 10 (0xa) | Exported Function | 0x0000000180001750 | 0x00001750
`TetheringGetIsPeerlessTimeoutEnabled` | 9 (0x9) | Exported Function | 0x0000000180001cf0 | 0x00001cf0
`TetheringGetErrorString` | 8 (0x8) | Exported Function | 0x0000000180001c90 | 0x00001c90
`TetheringGetDefaultInterface` | 7 (0x7) | Exported Function | 0x0000000180001700 | 0x00001700
`TetheringGetClientCount` | 6 (0x6) | Exported Function | 0x0000000180001a90 | 0x00001a90
`TetheringFreePeerList` | 5 (0x5) | Exported Function | 0x0000000180001b10 | 0x00001b10
`TetheringFreeMemory` | 4 (0x4) | Exported Function | 0x0000000180001b10 | 0x00001b10
`TetheringDeinitApi` | 3 (0x3) | Exported Function | 0x00000001800016a0 | 0x000016a0
`TetheringStopSharingAsync` | 31 (0x1f) | Exported Function | 0x0000000180001740 | 0x00001740
`TetheringUnregisterNotification` | 32 (0x20) | Exported Function | 0x0000000180001b90 | 0x00001b90


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TetheringClient.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/8ef6e578c77caa6c47c512ba733b6532ac21d34f396632d8ff5ee7deca47846a/detection/





MIT License. Copyright (c) 2020 Strontic.


