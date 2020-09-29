---
title: iumbase.dll | IUM Layer Secure Win32 DLL
excerpt: What is iumbase.dll?
---

# iumbase.dll 

* File Path: `C:\Windows\system32\iumbase.dll`
* Description: IUM Layer Secure Win32 DLL

## Hashes

Type | Hash
-- | --
MD5 | `FDB3C7D85D50A51C365EA2ADACAB37B6`
SHA1 | `0BE5EE21AFBD2D4D87B6B70B794760846D38ECE6`
SHA256 | `D33D061F3389434A2E0245DF0F254BFD77BD492471AC125E5EBA6DF00427D784`
SHA384 | `4AC637B12F49290BDAFED0F4997B2E1075A66C251AAAEB9A7DFC0B447EF7F3E742F0A2DA933DDC520021BE69E052DCDC`
SHA512 | `750CECBBBF93DD6F18EBF23B60D7DE9B242F1F55690EFD2C0C084A3D5763D07FAB657EA217687A0AF180726B71F55732EFB84ED8162077E4F5442DC9CE938E5F`
SSDEEP | `384:kKhYBFuxjhX0SgVIOWV6NWyNoJGVcG/WG1kJGL8SpVyDBRJnVvlm08:JhYBc0LIUNflRZPI1PnVO`
IMP | `0DAC99DB7FFC774E1B197156795B2A0B`
PESHA1 | `7B482F2D0DC0F1F4EF8BB9116E000CC3A66F9EAA`
PE256 | `3308FB5C6E3F92045B305D8CA45592A38013E01A515EFF04BE42DAC28BB0718B`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AssignMemoryToSocDomain` | 1 (0x1) | Exported Function | 0x0000000180001010 | 0x00001010
`GetTaggedDataSize` | 20 (0x14) | Exported Function | 0x0000000180001910 | 0x00001910
`GetTpmBindingInfo` | 21 (0x15) | Exported Function | 0x0000000180001930 | 0x00001930
`IsSecureProcess` | 22 (0x16) | Exported Function | 0x0000000180001240 | 0x00001240
`MapSecureIo` | 23 (0x17) | Exported Function | 0x0000000180001c40 | 0x00001c40
`OpenCurrentExtension` | 24 (0x18) | Exported Function | 0x0000000180001360 | 0x00001360
`OpenSecureSection` | 25 (0x19) | Exported Function | 0x00000001800013a0 | 0x000013a0
`GetTaggedData` | 19 (0x13) | Exported Function | 0x0000000180001920 | 0x00001920
`PostMailbox` | 26 (0x1a) | Exported Function | 0x00000001800013e0 | 0x000013e0
`QuerySecureDeviceInformation` | 28 (0x1c) | Exported Function | 0x0000000180001d60 | 0x00001d60
`SecureStorageGet` | 29 (0x1d) | Exported Function | 0x00000001800014d0 | 0x000014d0
`SecureStoragePut` | 30 (0x1e) | Exported Function | 0x0000000180001480 | 0x00001480
`SetDmaTargetProperties` | 31 (0x1f) | Exported Function | 0x0000000180001dc0 | 0x00001dc0
`SetPolicyExtension` | 32 (0x20) | Exported Function | 0x0000000180001e20 | 0x00001e20
`UnmapSecureIo` | 33 (0x21) | Exported Function | 0x0000000180001ca0 | 0x00001ca0
`ProtectSecureIo` | 27 (0x1b) | Exported Function | 0x0000000180001430 | 0x00001430
`UpdateSecureDeviceState` | 34 (0x22) | Exported Function | 0x0000000180001d20 | 0x00001d20
`GetSignedReport` | 18 (0x12) | Exported Function | 0x0000000180001670 | 0x00001670
`GetSecureIdentitySigningKey` | 16 (0x10) | Exported Function | 0x00000001800012e0 | 0x000012e0
`AwaitSmc` | 2 (0x2) | Exported Function | 0x0000000180001080 | 0x00001080
`CreateSecureDevice` | 3 (0x3) | Exported Function | 0x0000000180001ce0 | 0x00001ce0
`CreateSecureSection` | 4 (0x4) | Exported Function | 0x00000001800010c0 | 0x000010c0
`CreateSecureSectionSpecifyPages` | 5 (0x5) | Exported Function | 0x0000000180001120 | 0x00001120
`DecryptData` | 6 (0x6) | Exported Function | 0x0000000180001840 | 0x00001840
`DecryptISKBoundData` | 7 (0x7) | Exported Function | 0x00000001800015c0 | 0x000015c0
`GetSeedFromIumKernelState` | 17 (0x11) | Exported Function | 0x00000001800019d0 | 0x000019d0
`DmaMapMemory` | 8 (0x8) | Exported Function | 0x0000000180001ba0 | 0x00001ba0
`EncryptData` | 10 (0xa) | Exported Function | 0x0000000180001770 | 0x00001770
`FlushSecureSectionBuffers` | 11 (0xb) | Exported Function | 0x00000001800011c0 | 0x000011c0
`GetDmaEnabler` | 12 (0xc) | Exported Function | 0x0000000180001b30 | 0x00001b30
`GetExposedSecureSection` | 13 (0xd) | Exported Function | 0x0000000180001200 | 0x00001200
`GetFipsModeFromIumKernelState` | 14 (0xe) | Exported Function | 0x0000000180001a90 | 0x00001a90
`GetSecureIdentityKey` | 15 (0xf) | Exported Function | 0x0000000180001260 | 0x00001260
`EmitSmc` | 9 (0x9) | Exported Function | 0x0000000180001180 | 0x00001180
`VbsVmSysCall` | 35 (0x23) | Exported Function | 0x0000000180001520 | 0x00001520


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iumbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d33d061f3389434a2e0245df0f254bfd77bd492471ac125e5eba6df00427d784/detection/





MIT License. Copyright (c) 2020 Strontic.


