---
title: skci.dll | Secure Kernel Code Integrity Module
excerpt: What is skci.dll?
---

# skci.dll 

* File Path: `C:\Windows\system32\skci.dll`
* Description: Secure Kernel Code Integrity Module

## Hashes

Type | Hash
-- | --
MD5 | `7E88E785DFD6D6A343770C1BADD19D2E`
SHA1 | `457F53C7D237BCD0B41C3BB5724A832A5B5D576B`
SHA256 | `DDCFB8617A289F06D639ED06297E30E590A4BA97CDF9463562D476F876E358B8`
SHA384 | `DF69CC84F94EC99506CD960B16206AD58AEC41DECF9D9731B8B98B11B9C7EA824B3B6871FAD774732BCD25153540C769`
SHA512 | `C52663FAD2BFABDC0B4971A914734EF3DF5207FF41B91180C62B18E4ADEBEBA217101C3510EBF0F8A38BB5F93F0BEF5C33C7CBB8DA0DAE11D11BD2CF83CBDFC2`
SSDEEP | `6144:MIc0I2n9o7PxcA919swGby170h0z4A1Yoq:Vbne7PmW19uby170h0z4A1`
IMP | `258E187B1224E817873F8D0FC1A58064`
PESHA1 | `F51EB18A23C334B88756037EAC77E0C7B02DF4EA`
PE256 | `61F2E50DAC12DA133685A04A30968346A0B93ADE991941F7C2DEB7807D0B6EA9`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SkciCompareSigningLevels` | 1 (0x1) | Exported Function | 0x00000001c003f1d0 | 0x0003f1d0
`SkciCreateCodeCatalog` | 2 (0x2) | Exported Function | 0x00000001c0001910 | 0x00001910
`SkciCreateSecureImage` | 3 (0x3) | Exported Function | 0x00000001c0001e50 | 0x00001e50
`SkciFinalizeSecureImageHash` | 4 (0x4) | Exported Function | 0x00000001c00024c0 | 0x000024c0
`SkciFinishImageValidation` | 5 (0x5) | Exported Function | 0x00000001c0002590 | 0x00002590
`SkciFreeImageContext` | 6 (0x6) | Exported Function | 0x00000001c0002180 | 0x00002180
`SkciInitialize` | 7 (0x7) | Exported Function | 0x00000001c00016e0 | 0x000016e0
`SkciMatchHotPatch` | 8 (0x8) | Exported Function | 0x00000001c0002f00 | 0x00002f00
`SkciQueryImageAuthorID` | 9 (0x9) | Exported Function | 0x00000001c0002f80 | 0x00002f80
`SkciQueryImageUniqueID` | 10 (0xa) | Exported Function | 0x00000001c0002f50 | 0x00002f50
`SkciQueryInformation` | 11 (0xb) | Exported Function | 0x00000001c0041ff0 | 0x00041ff0
`SkciSetCodeIntegrityPolicy` | 12 (0xc) | Exported Function | 0x00000001c0002fb0 | 0x00002fb0
`SkciTransferVersionResource` | 13 (0xd) | Exported Function | 0x00000001c0002d00 | 0x00002d00
`SkciValidateAmeCertChain` | 14 (0xe) | Exported Function | 0x00000001c0001c00 | 0x00001c00
`SkciValidateDynamicCodePages` | 15 (0xf) | Exported Function | 0x00000001c0002470 | 0x00002470
`SkciValidateImageData` | 16 (0x10) | Exported Function | 0x00000001c0002230 | 0x00002230


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: skci.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/ddcfb8617a289f06d639ed06297e30e590a4ba97cdf9463562d476f876e358b8/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\bcryptprimitives.dll](bcryptprimitives.dll-BE8C33CD5A83B698EEE876403CCC3929.md) | 36
[C:\Windows\system32\BioIso.exe](BioIso.exe-9B0B54FBAC17F4ADE9D0245889912694.md) | 44
[C:\Windows\system32\BioIso.exe](BioIso.exe-CA90DB02AAF23C6D9E81896B63913B85.md) | 35
[C:\Windows\system32\ci.dll](ci.dll-2D3C21DC26898B49E4FF25B9B755BB61.md) | 36




MIT License. Copyright (c) 2020 Strontic.


