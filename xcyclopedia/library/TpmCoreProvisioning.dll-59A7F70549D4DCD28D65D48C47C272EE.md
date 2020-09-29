---
title: TpmCoreProvisioning.dll | TPM Core Provisioning Library
excerpt: What is TpmCoreProvisioning.dll?
---

# TpmCoreProvisioning.dll 

* File Path: `C:\Windows\system32\TpmCoreProvisioning.dll`
* Description: TPM Core Provisioning Library

## Hashes

Type | Hash
-- | --
MD5 | `59A7F70549D4DCD28D65D48C47C272EE`
SHA1 | `76622500371CB20C4521DA97AD920F8EC86C87C3`
SHA256 | `8C84B9B71A3BB146E753B7D08310508A715B0743D53BBDC5792B9C4E37B76C14`
SHA384 | `AEACB70053E5364D1D3CE846157308F9394369E1A2B404A7EBF076AE0D59CE91E500E1632961F6237E857535EF535AA0`
SHA512 | `51DB56DEFCE4639F1447185256BB04CDDB2C47EA9FABE47FE3F70739C05CB9398EF67270E05382F8B40095D78366922BDBA29BC0E6871329140EA40D5A526014`
SSDEEP | `12288:hOLrxpMVtDilHjaIrKVe0MH/c1csfcJHiNGIpCujezBXMNeJtIrAAfQsgyKvwTWP:shpMnAHjalzm/c1Nfc0GIpCmcDIkAaS`
IMP | `16223DCC6EDCAECE944CB341E0666256`
PESHA1 | `28174E58924EBB5572B15942F13D68E80F6C77B9`
PE256 | `8AFC227DB1B83C7E68BFB8DCB05FC7DDCE2E9D40155C54CAE47BFDD4B83F76DB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 140 (0x8c) | Exported Function | 0x000000018000e790 | 0x0000e790
`TpmIsEndorsementKeyPairPresent` | 101 (0x65) | Exported Function | 0x000000018002f9f0 | 0x0002f9f0
`TpmIsEnabled` | 100 (0x64) | Exported Function | 0x000000018002f0e0 | 0x0002f0e0
`TpmIsCommandPresent` | 99 (0x63) | Exported Function | 0x000000018002f6e0 | 0x0002f6e0
`TpmIsCommandBlocked` | 98 (0x62) | Exported Function | 0x00000001800317f0 | 0x000317f0
`TpmIsAutoProvisioningEnabledEx` | 97 (0x61) | Exported Function | 0x0000000180031a70 | 0x00031a70
`TpmIsAutoProvisioningEnabled` | 96 (0x60) | Exported Function | 0x0000000180031a50 | 0x00031a50
`TpmIsActivated` | 95 (0x5f) | Exported Function | 0x000000018002f320 | 0x0002f320
`TpmImportOwnerAuth` | 94 (0x5e) | Exported Function | 0x0000000180031fa0 | 0x00031fa0
`TpmHealthCertGetAndVerify` | 93 (0x5d) | Exported Function | 0x0000000180040220 | 0x00040220
`TpmHasVulnerableFW` | 92 (0x5c) | Exported Function | 0x0000000180033bb0 | 0x00033bb0
`TpmGetVerificationRequest` | 82 (0x52) | Exported Function | 0x0000000180040b30 | 0x00040b30
`TpmGetTpmVersion` | 81 (0x51) | Exported Function | 0x0000000180033940 | 0x00033940
`TpmGetTcgLog` | 80 (0x50) | Exported Function | 0x00000001800322f0 | 0x000322f0
`TpmGetSrkPublicKeyModulus` | 79 (0x4f) | Exported Function | 0x0000000180032130 | 0x00032130
`TpmGetSrkADThumbprint` | 78 (0x4e) | Exported Function | 0x0000000180032200 | 0x00032200
`TpmGetSignedEKFromVendorCommand` | 77 (0x4d) | Exported Function | 0x0000000180033fb0 | 0x00033fb0
`TpmGetRandomAuthValue` | 76 (0x4c) | Exported Function | 0x0000000180030f30 | 0x00030f30
`TpmGetEffectiveGroupPolicyOwnerAuthLevel` | 62 (0x3e) | Exported Function | 0x0000000180032620 | 0x00032620
`TpmGetEndorsementKeyCertificateState` | 63 (0x3f) | Exported Function | 0x00000001800331a0 | 0x000331a0
`TpmGetHealthCertRequest` | 64 (0x40) | Exported Function | 0x0000000180040a00 | 0x00040a00
`TpmGetOrderlyShutdownInfo` | 65 (0x41) | Exported Function | 0x0000000180032950 | 0x00032950
`TpmGetOwnerAuth` | 66 (0x42) | Exported Function | 0x0000000180031d30 | 0x00031d30
`TpmGetOwnerAuthForEscrow` | 67 (0x43) | Exported Function | 0x00000001800323c0 | 0x000323c0
`TpmIsFIPS` | 102 (0x66) | Exported Function | 0x000000018002fab0 | 0x0002fab0
`TpmGetOwnerAuthStatus` | 68 (0x44) | Exported Function | 0x0000000180032560 | 0x00032560
`TpmGetPhysicalPresenceConfirmationStatus` | 71 (0x47) | Exported Function | 0x0000000180032060 | 0x00032060
`TpmGetPhysicalPresenceRequest` | 72 (0x48) | Exported Function | 0x0000000180031340 | 0x00031340
`TpmGetPhysicalPresenceResponse` | 73 (0x49) | Exported Function | 0x00000001800314c0 | 0x000314c0
`TpmGetPhysicalPresenceTransition` | 74 (0x4a) | Exported Function | 0x0000000180031400 | 0x00031400
`TpmGetPPIVersion` | 70 (0x46) | Exported Function | 0x0000000180033a00 | 0x00033a00
`TpmGetPssSalt` | 75 (0x4b) | Exported Function | 0x0000000180033ed0 | 0x00033ed0
`TpmGetOwnershipAuthBits` | 69 (0x45) | Exported Function | 0x000000018002f260 | 0x0002f260
`TpmIsKeyAttestationCapable` | 103 (0x67) | Exported Function | 0x000000018002f7b0 | 0x0002f7b0
`TpmIsLockedOut` | 104 (0x68) | Exported Function | 0x00000001800333e0 | 0x000333e0
`TpmIsOwned` | 105 (0x69) | Exported Function | 0x000000018002f1a0 | 0x0002f1a0
`TpmRetrieveEkCertificate` | 125 (0x7d) | Exported Function | 0x0000000180043260 | 0x00043260
`TpmRetrieveEkCertificateURL` | 126 (0x7e) | Exported Function | 0x00000001800430a0 | 0x000430a0
`TpmRetrieveEkCertOrReschedule` | 124 (0x7c) | Exported Function | 0x0000000180033000 | 0x00033000
`TpmRetrieveHealthCertificate` | 128 (0x80) | Exported Function | 0x0000000180040110 | 0x00040110
`TpmRetrieveHealthCertOrReschedule` | 127 (0x7f) | Exported Function | 0x00000001800330c0 | 0x000330c0
`TpmSelfTest` | 129 (0x81) | Exported Function | 0x0000000180031000 | 0x00031000
`TpmResetSrkAuth` | 123 (0x7b) | Exported Function | 0x0000000180030c00 | 0x00030c00
`TpmSetDictionaryAttackParameters` | 130 (0x82) | Exported Function | 0x0000000180032860 | 0x00032860
`TpmSetPhysicalPresenceRequest` | 132 (0x84) | Exported Function | 0x00000001800311b0 | 0x000311b0
`TpmSetPhysicalPresenceRequestEx` | 133 (0x85) | Exported Function | 0x0000000180031270 | 0x00031270
`TpmSetToLegacyDictionaryAttackParameters` | 134 (0x86) | Exported Function | 0x0000000180033260 | 0x00033260
`TpmSpecVersion_From_TpmVersionInfo` | 135 (0x87) | Exported Function | 0x000000018002eff0 | 0x0002eff0
`TpmTakeOwnership` | 136 (0x88) | Exported Function | 0x000000018002fc30 | 0x0002fc30
`TpmUnattendedSetup` | 137 (0x89) | Exported Function | 0x0000000180033560 | 0x00033560
`TpmSetInstance` | 131 (0x83) | Exported Function | 0x000000018002e220 | 0x0002e220
`TpmGetDictionaryAttackParameters` | 61 (0x3d) | Exported Function | 0x0000000180032780 | 0x00032780
`TpmResetAuthLockOut` | 122 (0x7a) | Exported Function | 0x0000000180031730 | 0x00031730
`TpmRemoveBlockedCommand` | 120 (0x78) | Exported Function | 0x0000000180031670 | 0x00031670
`TpmIsOwnerClearDisabled` | 106 (0x6a) | Exported Function | 0x000000018002f4a0 | 0x0002f4a0
`TpmIsOwnershipAllowed` | 107 (0x6b) | Exported Function | 0x000000018002f620 | 0x0002f620
`TpmIsPhysicalClearDisabled` | 108 (0x6c) | Exported Function | 0x000000018002f3e0 | 0x0002f3e0
`TpmIsPhysicalPresenceHardwareEnabled` | 109 (0x6d) | Exported Function | 0x000000018002f560 | 0x0002f560
`TpmIsReady` | 110 (0x6e) | Exported Function | 0x00000001800318c0 | 0x000318c0
`TpmIsReadyInformation` | 111 (0x6f) | Exported Function | 0x0000000180031980 | 0x00031980
`TpmRemoveRegisteredWindowsAIK` | 121 (0x79) | Exported Function | 0x0000000180032e70 | 0x00032e70
`TpmIsSrkAuthCompatible` | 112 (0x70) | Exported Function | 0x0000000180030b40 | 0x00030b40
`TpmManufacturerId_From_TpmVersionInfo` | 114 (0x72) | Exported Function | 0x000000018002ed30 | 0x0002ed30
`TpmManufacturerVersion_From_TpmVersionInfo` | 116 (0x74) | Exported Function | 0x000000018002ee10 | 0x0002ee10
`TpmManufacturerVersionInfo_From_TpmVersionInfo` | 115 (0x73) | Exported Function | 0x000000018002ef00 | 0x0002ef00
`TpmOwnerAuthEscrowed` | 117 (0x75) | Exported Function | 0x00000001800324a0 | 0x000324a0
`TpmPrepForNgc` | 118 (0x76) | Exported Function | 0x0000000180032f30 | 0x00032f30
`TpmProvision` | 119 (0x77) | Exported Function | 0x0000000180031ec0 | 0x00031ec0
`TpmIsUseLegacyDictionaryAttackParametersPolicySet` | 113 (0x71) | Exported Function | 0x000000018002fcf0 | 0x0002fcf0
`TpmGetDeviceInformation` | 60 (0x3c) | Exported Function | 0x0000000180033af0 | 0x00033af0
`TpmGetCapLockoutInfo` | 59 (0x3b) | Exported Function | 0x0000000180032a10 | 0x00032a10
`TpmGet_TpmVersionInfo` | 91 (0x5b) | Exported Function | 0x000000018002e960 | 0x0002e960
`TpmCertGetHealthCert` | 18 (0x12) | Exported Function | 0x000000018003f0b0 | 0x0003f0b0
`TpmCertGetHealthCertFromWeb` | 19 (0x13) | Exported Function | 0x0000000180049b70 | 0x00049b70
`TpmCertGetHealthCorrelationId` | 20 (0x14) | Exported Function | 0x000000018003ea50 | 0x0003ea50
`TpmCertGetHealthEndpoint` | 21 (0x15) | Exported Function | 0x000000018003e790 | 0x0003e790
`TpmCertGetHealthForceRetrieve` | 22 (0x16) | Exported Function | 0x000000018003ec00 | 0x0003ec00
`TpmCertGetHealthStatusCode` | 23 (0x17) | Exported Function | 0x000000018003eda0 | 0x0003eda0
`TpmCertGetHASProtocolVersion` | 141 (0x8d) | Exported Function | 0x000000018003e510 | 0x0003e510
`TpmCertGetHealthStatusRequestBlob` | 24 (0x18) | Exported Function | 0x00000001800495c0 | 0x000495c0
`TpmCertGetMaximumSupportedProtocolVersion` | 26 (0x1a) | Exported Function | 0x000000018003f190 | 0x0003f190
`TpmCertGetPreferredMaximumProtocolVersion` | 27 (0x1b) | Exported Function | 0x000000018003f250 | 0x0003f250
`TpmCertGetTpmManufacturerId` | 28 (0x1c) | Exported Function | 0x0000000180041920 | 0x00041920
`TpmCertGetWindowsAik` | 29 (0x1d) | Exported Function | 0x000000018003ff70 | 0x0003ff70
`TpmCertInstallEkCertInRegistry` | 30 (0x1e) | Exported Function | 0x0000000180041f60 | 0x00041f60
`TpmCertInstallNvEkCerts` | 31 (0x1f) | Exported Function | 0x00000001800419e0 | 0x000419e0
`TpmCertGetIsActiveZeroExhaust` | 25 (0x19) | Exported Function | 0x0000000180043810 | 0x00043810
`TpmCertIsHealthCertOnBootEnabled` | 32 (0x20) | Exported Function | 0x000000018003f820 | 0x0003f820
`TpmCertGetFwLinkId` | 17 (0x11) | Exported Function | 0x00000001800446e0 | 0x000446e0
`TpmCertGetFormattedHASUrl` | 15 (0xf) | Exported Function | 0x0000000180046920 | 0x00046920
`Tpm20CanClearUsingAuthPolicy` | 1 (0x1) | Exported Function | 0x0000000180030900 | 0x00030900
`Tpm20ClearUsingAuthPolicy` | 2 (0x2) | Exported Function | 0x00000001800309c0 | 0x000309c0
`Tpm20GetCompleteManufacturerVersion` | 3 (0x3) | Exported Function | 0x0000000180033870 | 0x00033870
`Tpm20IsResetLockoutCountNeeded` | 4 (0x4) | Exported Function | 0x0000000180030db0 | 0x00030db0
`Tpm20ResetLockoutCountIfNeeded` | 5 (0x5) | Exported Function | 0x0000000180030e70 | 0x00030e70
`Tpm2CreateWindowsNvBits` | 6 (0x6) | Exported Function | 0x000000018002fe50 | 0x0002fe50
`TpmCertGetFormattedUrl` | 16 (0x10) | Exported Function | 0x0000000180046410 | 0x00046410
`Tpm2ReadWindowsNvBit` | 7 (0x7) | Exported Function | 0x000000018002ff10 | 0x0002ff10
`TpmAddBlockedCommand` | 9 (0x9) | Exported Function | 0x00000001800315b0 | 0x000315b0
`TpmCertCheckEkCertMatchedEkPub` | 10 (0xa) | Exported Function | 0x0000000180041e70 | 0x00041e70
`TpmCertDeleteHealthCert` | 11 (0xb) | Exported Function | 0x000000018003f4c0 | 0x0003f4c0
`TpmCertDeleteHealthEndpoint` | 12 (0xc) | Exported Function | 0x000000018003e860 | 0x0003e860
`TpmCertGetCurrentProtocolVersion` | 13 (0xd) | Exported Function | 0x000000018003f3f0 | 0x0003f3f0
`TpmCertGetEkCertFromWeb` | 14 (0xe) | Exported Function | 0x0000000180046d30 | 0x00046d30
`Tpm2SetWindowsNvBit` | 8 (0x8) | Exported Function | 0x000000018002ffe0 | 0x0002ffe0
`TpmVerifyDeviceHealth` | 138 (0x8a) | Exported Function | 0x0000000180040940 | 0x00040940
`TpmCertParseHealthResponse` | 33 (0x21) | Exported Function | 0x00000001800452f0 | 0x000452f0
`TpmCertQueryEkPub` | 35 (0x23) | Exported Function | 0x0000000180041cb0 | 0x00041cb0
`TpmDisableAutoProvisioning` | 53 (0x35) | Exported Function | 0x0000000180031c70 | 0x00031c70
`TpmEKCertValidateAndCleanup` | 54 (0x36) | Exported Function | 0x0000000180033320 | 0x00033320
`TpmEnable` | 55 (0x37) | Exported Function | 0x000000018002f870 | 0x0002f870
`TpmEnableAutoProvisioning` | 56 (0x38) | Exported Function | 0x0000000180031b40 | 0x00031b40
`TpmGatherLogs` | 57 (0x39) | Exported Function | 0x0000000180033d50 | 0x00033d50
`TpmGatherTpmData` | 58 (0x3a) | Exported Function | 0x000000018004c6d0 | 0x0004c6d0
`TpmDisable` | 52 (0x34) | Exported Function | 0x000000018002f930 | 0x0002f930
`TpmGet_IsPpiVersion12` | 83 (0x53) | Exported Function | 0x000000018002ec70 | 0x0002ec70
`TpmGet_IsTpmVersion20` | 85 (0x55) | Exported Function | 0x000000018002eb90 | 0x0002eb90
`TpmGet_ManufacturerId` | 86 (0x56) | Exported Function | 0x000000018002e540 | 0x0002e540
`TpmGet_ManufacturerVersion` | 87 (0x57) | Exported Function | 0x000000018002e620 | 0x0002e620
`TpmGet_ManufacturerVersionInfo` | 88 (0x58) | Exported Function | 0x000000018002e6f0 | 0x0002e6f0
`TpmGet_PhysicalPresenceVersionInfo` | 89 (0x59) | Exported Function | 0x000000018002e890 | 0x0002e890
`TpmGet_SpecVersion` | 90 (0x5a) | Exported Function | 0x000000018002e7c0 | 0x0002e7c0
`TpmGet_IsTpmPresent` | 84 (0x54) | Exported Function | 0x000000018002ea50 | 0x0002ea50
`TpmCertPostHealthXmlData` | 34 (0x22) | Exported Function | 0x0000000180049700 | 0x00049700
`TpmDeleteOwnerAuth` | 51 (0x33) | Exported Function | 0x0000000180031e00 | 0x00031e00
`TpmCreateHealthAttestationClaim` | 49 (0x31) | Exported Function | 0x000000018003fc50 | 0x0003fc50
`TpmCertSetEkAttestationOverride` | 142 (0x8e) | Exported Function | 0x000000018003e600 | 0x0003e600
`TpmCertSetHealthEndpoint` | 36 (0x24) | Exported Function | 0x000000018003e6d0 | 0x0003e6d0
`TpmCertSetHealthForceRetrieve` | 37 (0x25) | Exported Function | 0x000000018003eb30 | 0x0003eb30
`TpmCertSetHealthStatusCode` | 38 (0x26) | Exported Function | 0x000000018003ecd0 | 0x0003ecd0
`TpmCertSetPreferredMaximumProtocolVersion` | 39 (0x27) | Exported Function | 0x000000018003f320 | 0x0003f320
`TpmCertVerifyHealthCertFromWeb` | 40 (0x28) | Exported Function | 0x0000000180049e50 | 0x00049e50
`TpmCreateHealthStatusClaim` | 50 (0x32) | Exported Function | 0x000000018003f890 | 0x0003f890
`TpmChangeOwnerAuth` | 41 (0x29) | Exported Function | 0x0000000180030cc0 | 0x00030cc0
`TpmCheckIFXRSAKeyGenVulnerability` | 43 (0x2b) | Exported Function | 0x000000018004cbd0 | 0x0004cbd0
`TpmClear` | 44 (0x2c) | Exported Function | 0x0000000180030a80 | 0x00030a80
`TpmClearUsingPhysicalPresence` | 45 (0x2d) | Exported Function | 0x00000001800334a0 | 0x000334a0
`TpmClearWithPolicyOrPPI` | 46 (0x2e) | Exported Function | 0x0000000180033c80 | 0x00033c80
`TpmConvertToOwnerAuth` | 47 (0x2f) | Exported Function | 0x00000001800310d0 | 0x000310d0
`TpmCreateEndorsementKeyPair` | 48 (0x30) | Exported Function | 0x000000018002fb70 | 0x0002fb70
`TpmCheckCreateWindowsAIK` | 42 (0x2a) | Exported Function | 0x0000000180032ae0 | 0x00032ae0
`TpmWriteInformationSnapshotFile` | 139 (0x8b) | Exported Function | 0x0000000180033e10 | 0x00033e10


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TpmCoreProvisioning.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8c84b9b71a3bb146e753b7d08310508a715b0743d53bbdc5792b9c4e37b76c14/detection/





MIT License. Copyright (c) 2020 Strontic.


