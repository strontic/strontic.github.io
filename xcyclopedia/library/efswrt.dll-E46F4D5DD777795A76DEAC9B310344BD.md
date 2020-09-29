---
title: efswrt.dll | Storage Protection Windows Runtime DLL
excerpt: What is efswrt.dll?
---

# efswrt.dll 

* File Path: `C:\Windows\system32\efswrt.dll`
* Description: Storage Protection Windows Runtime DLL

## Hashes

Type | Hash
-- | --
MD5 | `E46F4D5DD777795A76DEAC9B310344BD`
SHA1 | `66CB607C0E559C6AA6252667C82CEFC153C0679C`
SHA256 | `D405C7803A86C75E5D878458C2CCA781AAC426F3DE7FE05D1E968222F9AB0631`
SHA384 | `193019DB4ACD5A714BD9D97B983EA92E01D45AFE244EB3E713E6CC3E5D57E03D2E43E0E78D2417C153CD6EEE994FE5BE`
SHA512 | `651E382E384A8EBE0D4AC8D92B3CA6191623A5E476856EA27D65036D2238741469911A4E7293053FBC3552593AA429F80D33DDA073ED2C9AF3971EF7B7F51178`
SSDEEP | `12288:8F6baO2KYs594qlfd2TC53hBTwcksGptDQuEGJa+sEgLMX1d:IQaOYs594WNx7LPGptUFXLMX`
IMP | `00E2795A249257463C9BBE96064306A3`
PESHA1 | `598DA2C5CEA7AA011A911B1E2D33125FC97C3FCD`
PE256 | `A4E3DBFC4F06FBF7953E2FC538781B5837421E477DFACBFEA03545CDE44340A2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CdplGetFileProtectionLevel` | 1 (0x1) | Exported Function | 0x0000000180018ac0 | 0x00018ac0
`ProtectOrReprotectFileToIdentity` | 29 (0x1d) | Exported Function | 0x000000018000eaa0 | 0x0000eaa0
`ProtectFileToIdentity` | 28 (0x1c) | Exported Function | 0x000000018000ce80 | 0x0000ce80
`ProtectFileToEnterpriseIdentity` | 27 (0x1b) | Exported Function | 0x000000018000ea50 | 0x0000ea50
`GetEnterpriseIdForNetworkPath` | 26 (0x1a) | Exported Function | 0x000000018000dc40 | 0x0000dc40
`GetEnterpriseActionForCopy` | 25 (0x19) | Exported Function | 0x000000018000de70 | 0x0000de70
`FreeIdentityProtectorList` | 24 (0x18) | Exported Function | 0x000000018000e640 | 0x0000e640
`EnterpriseDataRevoke` | 23 (0x17) | Exported Function | 0x000000018000d3d0 | 0x0000d3d0
`EnterpriseDataProtect` | 22 (0x16) | Exported Function | 0x000000018000ca10 | 0x0000ca10
`EnterpriseDataGetStatus` | 21 (0x15) | Exported Function | 0x000000018000d8d0 | 0x0000d8d0
`EnterpriseDataCopyProtection` | 20 (0x14) | Exported Function | 0x000000018000d000 | 0x0000d000
`DpmUnprotectSecret` | 19 (0x13) | Exported Function | 0x000000018000e7d0 | 0x0000e7d0
`DpmStreamUpdate` | 18 (0x12) | Exported Function | 0x000000018000ea20 | 0x0000ea20
`DpmStreamOpenToUnprotect` | 17 (0x11) | Exported Function | 0x000000018000e940 | 0x0000e940
`QueryIdentityProtectors` | 30 (0x1e) | Exported Function | 0x000000018000e410 | 0x0000e410
`DpmStreamOpenToProtectToIdentity` | 16 (0x10) | Exported Function | 0x000000018000e850 | 0x0000e850
`DpmProtectSecretToIdentity` | 14 (0xe) | Exported Function | 0x000000018000e670 | 0x0000e670
`DpmBufferFree` | 13 (0xd) | Exported Function | 0x000000018000ea40 | 0x0000ea40
`DllGetClassObject` | 12 (0xc) | Exported Function | 0x0000000180005d80 | 0x00005d80
`DllGetActivationFactory` | 11 (0xb) | Exported Function | 0x0000000180005ba0 | 0x00005ba0
`DllCanUnloadNow` | 10 (0xa) | Exported Function | 0x0000000180005b30 | 0x00005b30
`CdplUnprotectSecret` | 9 (0x9) | Exported Function | 0x0000000180018ee0 | 0x00018ee0
`CdplProtectSecretToLevel` | 8 (0x8) | Exported Function | 0x0000000180018e20 | 0x00018e20
`CdplProtectKnownUserFolders` | 7 (0x7) | Exported Function | 0x0000000180018b10 | 0x00018b10
`CdplProtectFileToLevelWithResult` | 6 (0x6) | Exported Function | 0x0000000180018810 | 0x00018810
`CdplProtectFileToLevel` | 5 (0x5) | Exported Function | 0x0000000180018980 | 0x00018980
`CdplIsSupported` | 4 (0x4) | Exported Function | 0x0000000180019870 | 0x00019870
`CdplIsAppDataProtectionSupported` | 3 (0x3) | Exported Function | 0x000000018000eb70 | 0x0000eb70
`CdplIsAppAllowedToRun` | 2 (0x2) | Exported Function | 0x0000000180018f00 | 0x00018f00
`DpmStreamClose` | 15 (0xf) | Exported Function | 0x000000018000ea30 | 0x0000ea30
`UnprotectFile` | 31 (0x1f) | Exported Function | 0x000000018000ea70 | 0x0000ea70


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: efswrt.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d405c7803a86c75e5d878458c2cca781aac426f3de7fe05d1e968222f9ab0631/detection/





MIT License. Copyright (c) 2020 Strontic.


