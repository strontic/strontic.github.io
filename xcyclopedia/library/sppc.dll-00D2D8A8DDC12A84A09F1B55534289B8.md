---
title: sppc.dll | Software Licensing Client Dll
excerpt: What is sppc.dll?
---

# sppc.dll 

* File Path: `C:\Windows\SysWOW64\sppc.dll`
* Description: Software Licensing Client Dll

## Hashes

Type | Hash
-- | --
MD5 | `00D2D8A8DDC12A84A09F1B55534289B8`
SHA1 | `D3F4DA5A01BE3392ED4342DD72F074EF9EB83793`
SHA256 | `71046F75D7DE76D40E8E724ABFCA311255346ED823C314115F59F22380DA9120`
SHA384 | `22582A341609CAF50A69E38B0DD69FCA4B57D5137ABC57DB74A0C137E058480630AAE7FEFBC7FCE6CF2459ECFD763722`
SHA512 | `6DF58884C09315DDD0FE1EFE4509CB73FD5EE508545297A84A5C5A39CDAB6E2D9C7192E23530B0E2FFD5CC399F3FC99BB4E39C4F0A6913CE4CE898E94063CAE9`
SSDEEP | `3072:Y6HBffAHvzaVolingnzRdc6Rc05vmQ6t+:YWBHAHvFVT5vmQ6Y`
IMP | `08EC58E80802B400E7F3B82D2061DA13`
PESHA1 | `47FE55E67D805658AB0E9E9D7BFAE68F99192F39`
PE256 | `C0A50692542BFF0299C5C1D72283202D717C7F7367FB188E25E657FBF207064C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SLCallServer` | 1 (0x1) | Exported Function | 0x10015390 | 0x00015390
`SLOpen` | 54 (0x36) | Exported Function | 0x10013d10 | 0x00013d10
`SLpAuthenticateGenuineTicketResponse` | 2 (0x2) | Exported Function | 0x1000f910 | 0x0000f910
`SLpBeginGenuineTicketTransaction` | 3 (0x3) | Exported Function | 0x1000fa40 | 0x0000fa40
`SLpClearActivationInProgress` | 4 (0x4) | Exported Function | 0x1000fb10 | 0x0000fb10
`SLpDepositDownlevelGenuineTicket` | 5 (0x5) | Exported Function | 0x1000fba0 | 0x0000fba0
`SLpDepositTokenActivationResponse` | 6 (0x6) | Exported Function | 0x1000fc60 | 0x0000fc60
`SLPersistApplicationPolicies` | 55 (0x37) | Exported Function | 0x10013dc0 | 0x00013dc0
`SLPersistRTSPayloadOverride` | 56 (0x38) | Exported Function | 0x10013ea0 | 0x00013ea0
`SLpGenerateTokenActivationChallenge` | 7 (0x7) | Exported Function | 0x1000fd60 | 0x0000fd60
`SLpGetGenuineBlob` | 8 (0x8) | Exported Function | 0x1000fe60 | 0x0000fe60
`SLpGetGenuineLocal` | 9 (0x9) | Exported Function | 0x1000ff40 | 0x0000ff40
`SLpGetLicenseAcquisitionInfo` | 10 (0xa) | Exported Function | 0x1000ff80 | 0x0000ff80
`SLpGetMachineUGUID` | 12 (0xc) | Exported Function | 0x100102c0 | 0x000102c0
`SLpGetMSPidInformation` | 11 (0xb) | Exported Function | 0x100100d0 | 0x000100d0
`SLLoadApplicationPolicies` | 53 (0x35) | Exported Function | 0x10013ca0 | 0x00013ca0
`SLpGetTokenActivationGrantInfo` | 13 (0xd) | Exported Function | 0x10010350 | 0x00010350
`SLpIsCurrentInstalledProductKeyDefaultKey` | 15 (0xf) | Exported Function | 0x10010550 | 0x00010550
`SLpProcessVMPipeMessage` | 16 (0x10) | Exported Function | 0x100105e0 | 0x000105e0
`SLpSetActivationInProgress` | 17 (0x11) | Exported Function | 0x10010700 | 0x00010700
`SLpTriggerServiceWorker` | 18 (0x12) | Exported Function | 0x10010790 | 0x00010790
`SLpVLActivateProduct` | 19 (0x13) | Exported Function | 0x100108c0 | 0x000108c0
`SLReArm` | 57 (0x39) | Exported Function | 0x10013f90 | 0x00013f90
`SLRegisterEvent` | 58 (0x3a) | Exported Function | 0x10014050 | 0x00014050
`SLRegisterPlugin` | 59 (0x3b) | Exported Function | 0x100140d0 | 0x000140d0
`SLSetAuthenticationData` | 60 (0x3c) | Exported Function | 0x10014180 | 0x00014180
`SLSetCurrentProductKey` | 61 (0x3d) | Exported Function | 0x10014240 | 0x00014240
`SLSetGenuineInformation` | 62 (0x3e) | Exported Function | 0x10014300 | 0x00014300
`SLUninstallLicense` | 63 (0x3f) | Exported Function | 0x10014420 | 0x00014420
`SLUninstallProofOfPurchase` | 64 (0x40) | Exported Function | 0x100144b0 | 0x000144b0
`SLUnloadApplicationPolicies` | 65 (0x41) | Exported Function | 0x10014550 | 0x00014550
`SLpIAActivateProduct` | 14 (0xe) | Exported Function | 0x100104b0 | 0x000104b0
`SLUnregisterEvent` | 66 (0x42) | Exported Function | 0x100145a0 | 0x000145a0
`SLIsGenuineLocalEx` | 52 (0x34) | Exported Function | 0x10013c10 | 0x00013c10
`SLInstallProofOfPurchase` | 50 (0x32) | Exported Function | 0x100139c0 | 0x000139c0
`SLClose` | 20 (0x14) | Exported Function | 0x10012270 | 0x00012270
`SLConsumeRight` | 21 (0x15) | Exported Function | 0x100122a0 | 0x000122a0
`SLDepositMigrationBlob` | 22 (0x16) | Exported Function | 0x10012350 | 0x00012350
`SLDepositOfflineConfirmationId` | 23 (0x17) | Exported Function | 0x10012400 | 0x00012400
`SLDepositOfflineConfirmationIdEx` | 24 (0x18) | Exported Function | 0x10012440 | 0x00012440
`SLDepositStoreToken` | 25 (0x19) | Exported Function | 0x10012760 | 0x00012760
`SLFireEvent` | 26 (0x1a) | Exported Function | 0x10012810 | 0x00012810
`SLGatherMigrationBlob` | 27 (0x1b) | Exported Function | 0x100128d0 | 0x000128d0
`SLGatherMigrationBlobEx` | 28 (0x1c) | Exported Function | 0x10012940 | 0x00012940
`SLGenerateOfflineInstallationId` | 29 (0x1d) | Exported Function | 0x10012a20 | 0x00012a20
`SLGenerateOfflineInstallationIdEx` | 30 (0x1e) | Exported Function | 0x10012a60 | 0x00012a60
`SLGetActiveLicenseInfo` | 31 (0x1f) | Exported Function | 0x10012b90 | 0x00012b90
`SLGetApplicationInformation` | 32 (0x20) | Exported Function | 0x10012c70 | 0x00012c70
`SLGetApplicationPolicy` | 33 (0x21) | Exported Function | 0x10012cc0 | 0x00012cc0
`SLInstallProofOfPurchaseEx` | 51 (0x33) | Exported Function | 0x10013ac0 | 0x00013ac0
`SLGetAuthenticationResult` | 34 (0x22) | Exported Function | 0x10012d30 | 0x00012d30
`SLGetGenuineInformation` | 36 (0x24) | Exported Function | 0x10012f30 | 0x00012f30
`SLGetInstalledProductKeyIds` | 37 (0x25) | Exported Function | 0x10013080 | 0x00013080
`SLGetLicense` | 38 (0x26) | Exported Function | 0x100131a0 | 0x000131a0
`SLGetLicenseFileId` | 39 (0x27) | Exported Function | 0x100132a0 | 0x000132a0
`SLGetLicenseInformation` | 40 (0x28) | Exported Function | 0x10013390 | 0x00013390
`SLGetLicensingStatusInformation` | 41 (0x29) | Exported Function | 0x100133e0 | 0x000133e0
`SLGetPKeyId` | 42 (0x2a) | Exported Function | 0x10013510 | 0x00013510
`SLGetPKeyInformation` | 43 (0x2b) | Exported Function | 0x10013650 | 0x00013650
`SLGetPolicyInformation` | 44 (0x2c) | Exported Function | 0x100136a0 | 0x000136a0
`SLGetPolicyInformationDWORD` | 45 (0x2d) | Exported Function | 0x100136e0 | 0x000136e0
`SLGetProductSkuInformation` | 46 (0x2e) | Exported Function | 0x10013720 | 0x00013720
`SLGetServiceInformation` | 48 (0x30) | Exported Function | 0x100138c0 | 0x000138c0
`SLGetSLIDList` | 47 (0x2f) | Exported Function | 0x10013760 | 0x00013760
`SLInstallLicense` | 49 (0x31) | Exported Function | 0x10013900 | 0x00013900
`SLGetEncryptedPIDEx` | 35 (0x23) | Exported Function | 0x10012e10 | 0x00012e10
`SLUnregisterPlugin` | 67 (0x43) | Exported Function | 0x10014610 | 0x00014610


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sppc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/71046f75d7de76d40e8e724abfca311255346ed823c314115f59f22380da9120/detection/





MIT License. Copyright (c) 2020 Strontic.


