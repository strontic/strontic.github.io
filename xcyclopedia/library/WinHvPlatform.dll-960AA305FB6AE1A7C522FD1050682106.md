---
title: WinHvPlatform.dll | Hyper-V Hypervisor User-Mode API Library
excerpt: What is WinHvPlatform.dll?
---

# WinHvPlatform.dll 

* File Path: `C:\Windows\system32\WinHvPlatform.dll`
* Description: Hyper-V Hypervisor User-Mode API Library

## Hashes

Type | Hash
-- | --
MD5 | `960AA305FB6AE1A7C522FD1050682106`
SHA1 | `7E2ACCACCECFAEC8D8569516E7976CBBABF92D6A`
SHA256 | `6ADAB2AAA5CE7A227835B3477D532116D5929558F178FB662D607CFF7F4ED861`
SHA384 | `0019CF936BABDE23DDA4FADE1164EB5058C59B5C07BB6CFD86CED8DB40C4B492A21029AAA4BE6C38AE1AF455D23DBE9F`
SHA512 | `ABCDCBEDEAF5B919B5359BC56CC860FBD606B050291B74C4A757D6C54F1F25C781D8A8E1969BB6E18234DE47FDBE79F2EDEC1778F7072AA5571639A19EE89D6B`
SSDEEP | `3072:VD+Dbz6i0zG9hJnxVZW7ZWLwSfScVzpX9CziYJS:VDcb+FzwhJxrW7Ew/K4iYJ`
IMP | `64C9FDBC9119671F27649B41ECB9C51F`
PESHA1 | `E4C882F4212D993AB8CD1218452ADE578B4E8723`
PE256 | `ECA8A67A025B82B52356E1DDAEA702E53AF7CABADC2DF82B570EC051511B5F74`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WHvCancelRunVirtualProcessor` | 1 (0x1) | Exported Function | 0x0000000180011de0 | 0x00011de0
`WHvTranslateGva` | 27 (0x1b) | Exported Function | 0x0000000180011ab0 | 0x00011ab0
`WHvSuspendPartitionTime` | 26 (0x1a) | Exported Function | 0x0000000180012980 | 0x00012980
`WHvSetVirtualProcessorXsaveState` | 24 (0x18) | Exported Function | 0x00000001800124a0 | 0x000124a0
`WHvSetVirtualProcessorRegisters` | 23 (0x17) | Exported Function | 0x0000000180012080 | 0x00012080
`WHvSetVirtualProcessorInterruptControllerState2` | 22 (0x16) | Exported Function | 0x0000000180012320 | 0x00012320
`WHvSetVirtualProcessorInterruptControllerState` | 21 (0x15) | Exported Function | 0x00000001800122d0 | 0x000122d0
`WHvSetupPartition` | 25 (0x19) | Exported Function | 0x0000000180011750 | 0x00011750
`WHvSetPartitionProperty` | 20 (0x14) | Exported Function | 0x0000000180011810 | 0x00011810
`WHvRunVirtualProcessor` | 19 (0x13) | Exported Function | 0x0000000180011d90 | 0x00011d90
`WHvResumePartitionTime` | 18 (0x12) | Exported Function | 0x0000000180012a70 | 0x00012a70
`WHvRequestInterrupt` | 17 (0x11) | Exported Function | 0x0000000180012370 | 0x00012370
`WHvRegisterPartitionDoorbellEvent` | 16 (0x10) | Exported Function | 0x0000000180012aa0 | 0x00012aa0
`WHvUnmapGpaRange` | 28 (0x1c) | Exported Function | 0x0000000180011a20 | 0x00011a20
`WHvQueryGpaRangeDirtyBitmap` | 15 (0xf) | Exported Function | 0x0000000180012530 | 0x00012530
`WHvGetVirtualProcessorXsaveState` | 13 (0xd) | Exported Function | 0x00000001800123d0 | 0x000123d0
`WHvGetVirtualProcessorRegisters` | 12 (0xc) | Exported Function | 0x0000000180011f70 | 0x00011f70
`WHvGetVirtualProcessorInterruptControllerState2` | 11 (0xb) | Exported Function | 0x0000000180012230 | 0x00012230
`WHvGetVirtualProcessorInterruptControllerState` | 10 (0xa) | Exported Function | 0x0000000180012190 | 0x00012190
`WHvGetVirtualProcessorCounters` | 9 (0x9) | Exported Function | 0x00000001800128f0 | 0x000128f0
`WHvGetPartitionProperty` | 8 (0x8) | Exported Function | 0x0000000180011780 | 0x00011780
`WHvGetPartitionCounters` | 7 (0x7) | Exported Function | 0x00000001800126f0 | 0x000126f0
`WHvGetCapability` | 6 (0x6) | Exported Function | 0x0000000180011200 | 0x00011200
`WHvDeleteVirtualProcessor` | 5 (0x5) | Exported Function | 0x0000000180011d00 | 0x00011d00
`WHvDeletePartition` | 4 (0x4) | Exported Function | 0x0000000180011720 | 0x00011720
`WHvCreateVirtualProcessor` | 3 (0x3) | Exported Function | 0x0000000180011ca0 | 0x00011ca0
`WHvCreatePartition` | 2 (0x2) | Exported Function | 0x00000001800116b0 | 0x000116b0
`WHvMapGpaRange` | 14 (0xe) | Exported Function | 0x0000000180011860 | 0x00011860
`WHvUnregisterPartitionDoorbellEvent` | 29 (0x1d) | Exported Function | 0x0000000180012ae0 | 0x00012ae0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WinHvApi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/6adab2aaa5ce7a227835b3477d532116d5929558f178fb662d607cff7f4ed861/detection/





MIT License. Copyright (c) 2020 Strontic.


