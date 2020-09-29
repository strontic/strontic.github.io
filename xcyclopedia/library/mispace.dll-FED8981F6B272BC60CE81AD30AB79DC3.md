---
title: mispace.dll | Storage Management Provider for Spaces
excerpt: What is mispace.dll?
---

# mispace.dll 

* File Path: `C:\Windows\system32\mispace.dll`
* Description: Storage Management Provider for Spaces

## Hashes

Type | Hash
-- | --
MD5 | `FED8981F6B272BC60CE81AD30AB79DC3`
SHA1 | `262AC1D85E5B2A5C054647E3CDBD8E76A60C4A61`
SHA256 | `A459F1EAF80DEF5A62C074FC45F83E234030F9D885C3454A5BABC6519D23CD71`
SHA384 | `CA0924B03E13769E3D6AEA0E837325699E2FA7DA9A04E4B1EDFC2046DCA28C3F12EC70B5AE7D8E8E445013529957F5C5`
SHA512 | `750271AF773D91EC7B723730F9E378556E353D600D7A82EA96F82A3BB7416EF4D673DFA17ABD9C3AECE09FCBABD608926E7771FD1914E92079B9CE9A350F1979`
SSDEEP | `24576:8rS0l5U/sVDb6r5xLsxD4jkfmqvfpfSx6iu/yXdsWCc3d/eTWJsyx0+KzP35:8rh3UEVDb6Tk4jCDiuKZ3d/eTWLKb`
IMP | `50459A616FF24B8E0012070FA25ECD39`
PESHA1 | `9B07E224A69416FD6D931369AE7E0D3312220598`
PE256 | `74020B94BA3C724F975E4C049F6FBE85F1C88B39F32C11F2912A3E5AEC017EB5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x000000018000a510 | 0x0000a510
`WspSendIndication` | 31 (0x1f) | Exported Function | 0x000000018000e790 | 0x0000e790
`WspRunMethodAsJob` | 30 (0x1e) | Exported Function | 0x000000018000df30 | 0x0000df30
`WspReferencesOfRemoteInstance` | 29 (0x1d) | Exported Function | 0x000000018000cdc0 | 0x0000cdc0
`WspProviderExit` | 28 (0x1c) | Exported Function | 0x000000018000c010 | 0x0000c010
`WspProviderEnter` | 27 (0x1b) | Exported Function | 0x000000018000be40 | 0x0000be40
`WspPostSubsystemAssociationReferenceObject` | 26 (0x1a) | Exported Function | 0x000000018000e910 | 0x0000e910
`WspPostAssociation` | 25 (0x19) | Exported Function | 0x000000018000ef70 | 0x0000ef70
`WspPackObjectId` | 24 (0x18) | Exported Function | 0x000000018000c030 | 0x0000c030
`WspIsRemoteRequest` | 23 (0x17) | Exported Function | 0x000000018000d110 | 0x0000d110
`WspIsRemoteInstance` | 22 (0x16) | Exported Function | 0x000000018000cb60 | 0x0000cb60
`WspIsAutomaticClusteringEnabled` | 21 (0x15) | Exported Function | 0x000000018000c8d0 | 0x0000c8d0
`WspInvokeRemoteMethod` | 20 (0x14) | Exported Function | 0x000000018000cf90 | 0x0000cf90
`WspGuidToString` | 19 (0x13) | Exported Function | 0x000000018000bd30 | 0x0000bd30
`WspGetSubsystemFilter` | 18 (0x12) | Exported Function | 0x000000018000cb30 | 0x0000cb30
`WspUnpackObjectId` | 32 (0x20) | Exported Function | 0x000000018000c490 | 0x0000c490
`WspGetRemoteInstance` | 17 (0x11) | Exported Function | 0x000000018000cc70 | 0x0000cc70
`WspFreeString` | 15 (0xf) | Exported Function | 0x000000018000bc70 | 0x0000bc70
`WspEnumerateRemoteInstances` | 14 (0xe) | Exported Function | 0x000000018000c9e0 | 0x0000c9e0
`WspCreateJob` | 13 (0xd) | Exported Function | 0x000000018000dd10 | 0x0000dd10
`WspCompleteMethod` | 12 (0xc) | Exported Function | 0x000000018000e530 | 0x0000e530
`WspCheckMinimumSubsystemVersion` | 1 (0x1) | Exported Function | 0x000000018000d460 | 0x0000d460
`SmpUnload` | 11 (0xb) | Exported Function | 0x000000018000ad10 | 0x0000ad10
`SetShutdownCallback` | 10 (0xa) | Exported Function | 0x000000018000ad00 | 0x0000ad00
`PreShutdown` | 9 (0x9) | Exported Function | 0x000000018000ad20 | 0x0000ad20
`MI_Main` | 8 (0x8) | Exported Function | 0x000000018000aca0 | 0x0000aca0
`GetProviderClassID` | 7 (0x7) | Exported Function | 0x000000018000a260 | 0x0000a260
`DllUnregisterServer` | 6 (0x6) | Exported Function | 0x000000018000a4c0 | 0x0000a4c0
`DllRegisterServer` | 5 (0x5) | Exported Function | 0x000000018000a470 | 0x0000a470
`DllMain` | 4 (0x4) | Exported Function | 0x000000018000a1d0 | 0x0000a1d0
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x000000018000a550 | 0x0000a550
`WspGetClassName` | 16 (0x10) | Exported Function | 0x000000018000c9b0 | 0x0000c9b0
`WspUpdateMethod` | 33 (0x21) | Exported Function | 0x000000018000e250 | 0x0000e250


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mispace.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/a459f1eaf80def5a62c074fc45f83e234030f9d885c3454a5babc6519d23cd71/detection/





MIT License. Copyright (c) 2020 Strontic.


