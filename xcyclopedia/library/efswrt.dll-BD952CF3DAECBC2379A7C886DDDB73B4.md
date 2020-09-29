---
title: efswrt.dll | Storage Protection Windows Runtime DLL
excerpt: What is efswrt.dll?
---

# efswrt.dll 

* File Path: `C:\Windows\SysWOW64\efswrt.dll`
* Description: Storage Protection Windows Runtime DLL

## Hashes

Type | Hash
-- | --
MD5 | `BD952CF3DAECBC2379A7C886DDDB73B4`
SHA1 | `7B8E1339CBE0A8CD557E2724240EA4A7E56933AF`
SHA256 | `59D07B546F445716B1C7693A397E19F1985AFFBCDC62AF54BEA155F77182B22C`
SHA384 | `9F558512C3F8016A39466979D6E443EA1D7CF23EBB971A837374F61A211A90E901F14C150EF3B58F58DB3DB53712CD4A`
SHA512 | `A5C5F32C3869AFB36E523E7E67D4E1822457AAA6DBBAC60FAC10843AA8D592772BD071FF232F3C65703F2EB87CEB582FB457175A36152242FE379DCFA8C9C86C`
SSDEEP | `12288:nYpdyhyQMLAhu0Bp0iR5XG7RDtTY+QimRSzkMNuW7wp:nJhyZLAhu0BpVzXcXTJQz0zkc`
IMP | `89B0D925F63A3F063373EE0E9FFF62A8`
PESHA1 | `B8D4BBE87614FA4D30056A96380C76C24413CA97`
PE256 | `3FE2B5DC2CAD8A007289B46C39E9317A5DECB55E0F83FB6BA36F166F6E231171`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CdplGetFileProtectionLevel` | 1 (0x1) | Exported Function | 0x10034190 | 0x00034190
`ProtectOrReprotectFileToIdentity` | 29 (0x1d) | Exported Function | 0x1002b240 | 0x0002b240
`ProtectFileToIdentity` | 28 (0x1c) | Exported Function | 0x10029db0 | 0x00029db0
`ProtectFileToEnterpriseIdentity` | 27 (0x1b) | Exported Function | 0x1002b1f0 | 0x0002b1f0
`GetEnterpriseIdForNetworkPath` | 26 (0x1a) | Exported Function | 0x1002a7a0 | 0x0002a7a0
`GetEnterpriseActionForCopy` | 25 (0x19) | Exported Function | 0x1002a9c0 | 0x0002a9c0
`FreeIdentityProtectorList` | 24 (0x18) | Exported Function | 0x1002afa0 | 0x0002afa0
`EnterpriseDataRevoke` | 23 (0x17) | Exported Function | 0x1002a170 | 0x0002a170
`EnterpriseDataProtect` | 22 (0x16) | Exported Function | 0x10029a70 | 0x00029a70
`EnterpriseDataGetStatus` | 21 (0x15) | Exported Function | 0x1002a530 | 0x0002a530
`EnterpriseDataCopyProtection` | 20 (0x14) | Exported Function | 0x10029eb0 | 0x00029eb0
`DpmUnprotectSecret` | 19 (0x13) | Exported Function | 0x1002b090 | 0x0002b090
`DpmStreamUpdate` | 18 (0x12) | Exported Function | 0x1002b1b0 | 0x0002b1b0
`DpmStreamOpenToUnprotect` | 17 (0x11) | Exported Function | 0x1002b190 | 0x0002b190
`QueryIdentityProtectors` | 30 (0x1e) | Exported Function | 0x1002ae30 | 0x0002ae30
`DpmStreamOpenToProtectToIdentity` | 16 (0x10) | Exported Function | 0x1002b0f0 | 0x0002b0f0
`DpmProtectSecretToIdentity` | 14 (0xe) | Exported Function | 0x1002afc0 | 0x0002afc0
`DpmBufferFree` | 13 (0xd) | Exported Function | 0x1002b1e0 | 0x0002b1e0
`DllGetClassObject` | 12 (0xc) | Exported Function | 0x10024920 | 0x00024920
`DllGetActivationFactory` | 11 (0xb) | Exported Function | 0x10024900 | 0x00024900
`DllCanUnloadNow` | 10 (0xa) | Exported Function | 0x100248c0 | 0x000248c0
`CdplUnprotectSecret` | 9 (0x9) | Exported Function | 0x10034450 | 0x00034450
`CdplProtectSecretToLevel` | 8 (0x8) | Exported Function | 0x100343e0 | 0x000343e0
`CdplProtectKnownUserFolders` | 7 (0x7) | Exported Function | 0x100341e0 | 0x000341e0
`CdplProtectFileToLevelWithResult` | 6 (0x6) | Exported Function | 0x10033f80 | 0x00033f80
`CdplProtectFileToLevel` | 5 (0x5) | Exported Function | 0x100340a0 | 0x000340a0
`CdplIsSupported` | 4 (0x4) | Exported Function | 0x10034b20 | 0x00034b20
`CdplIsAppDataProtectionSupported` | 3 (0x3) | Exported Function | 0x1002b2f0 | 0x0002b2f0
`CdplIsAppAllowedToRun` | 2 (0x2) | Exported Function | 0x10034470 | 0x00034470
`DpmStreamClose` | 15 (0xf) | Exported Function | 0x1002b1d0 | 0x0002b1d0
`UnprotectFile` | 31 (0x1f) | Exported Function | 0x1002b210 | 0x0002b210


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/59d07b546f445716b1c7693a397e19f1985affbcdc62af54bea155f77182b22c/detection/





MIT License. Copyright (c) 2020 Strontic.


