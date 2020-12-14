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

Function Name | Ordinal | Type
-- | -- | --
`TpmHasVulnerableFW` | 92 | Exported Function
`TpmGetVerificationRequest` | 82 | Exported Function
`TpmImportOwnerAuth` | 94 | Exported Function
`TpmHealthCertGetAndVerify` | 93 | Exported Function
`TpmGetSrkPublicKeyModulus` | 79 | Exported Function
`TpmGetSrkADThumbprint` | 78 | Exported Function
`TpmGetTpmVersion` | 81 | Exported Function
`TpmGetTcgLog` | 80 | Exported Function
`TpmIsActivated` | 95 | Exported Function
`TpmIsEndorsementKeyPairPresent` | 101 | Exported Function
`TpmIsEnabled` | 100 | Exported Function
`TpmIsKeyAttestationCapable` | 103 | Exported Function
`TpmIsFIPS` | 102 | Exported Function
`TpmIsAutoProvisioningEnabledEx` | 97 | Exported Function
`TpmIsAutoProvisioningEnabled` | 96 | Exported Function
`TpmIsCommandPresent` | 99 | Exported Function
`TpmIsCommandBlocked` | 98 | Exported Function
`TpmGetSignedEKFromVendorCommand` | 77 | Exported Function
`TpmGetOrderlyShutdownInfo` | 65 | Exported Function
`TpmGetHealthCertRequest` | 64 | Exported Function
`TpmGetOwnerAuthForEscrow` | 67 | Exported Function
`TpmGetOwnerAuth` | 66 | Exported Function
`TpmGetDictionaryAttackParameters` | 61 | Exported Function
`TpmGetDeviceInformation` | 60 | Exported Function
`TpmGetEndorsementKeyCertificateState` | 63 | Exported Function
`TpmGetEffectiveGroupPolicyOwnerAuthLevel` | 62 | Exported Function
`TpmGetOwnerAuthStatus` | 68 | Exported Function
`TpmGetPPIVersion` | 70 | Exported Function
`TpmGetPhysicalPresenceTransition` | 74 | Exported Function
`TpmGetRandomAuthValue` | 76 | Exported Function
`TpmGetPssSalt` | 75 | Exported Function
`TpmGetPhysicalPresenceConfirmationStatus` | 71 | Exported Function
`TpmGetOwnershipAuthBits` | 69 | Exported Function
`TpmGetPhysicalPresenceResponse` | 73 | Exported Function
`TpmGetPhysicalPresenceRequest` | 72 | Exported Function
`TpmIsLockedOut` | 104 | Exported Function
`TpmRetrieveHealthCertOrReschedule` | 127 | Exported Function
`TpmRetrieveHealthCertificate` | 128 | Exported Function
`TpmSetDictionaryAttackParameters` | 130 | Exported Function
`TpmSelfTest` | 129 | Exported Function
`TpmRetrieveEkCertificate` | 125 | Exported Function
`TpmResetSrkAuth` | 123 | Exported Function
`TpmRetrieveEkCertOrReschedule` | 124 | Exported Function
`TpmRetrieveEkCertificateURL` | 126 | Exported Function
`TpmSetInstance` | 131 | Exported Function
`TpmUnattendedSetup` | 137 | Exported Function
`TpmTakeOwnership` | 136 | Exported Function
`TpmWriteInformationSnapshotFile` | 139 | Exported Function
`TpmVerifyDeviceHealth` | 138 | Exported Function
`TpmSetPhysicalPresenceRequestEx` | 133 | Exported Function
`TpmSetPhysicalPresenceRequest` | 132 | Exported Function
`TpmSpecVersion_From_TpmVersionInfo` | 135 | Exported Function
`TpmSetToLegacyDictionaryAttackParameters` | 134 | Exported Function
`TpmResetAuthLockOut` | 122 | Exported Function
`TpmIsReady` | 110 | Exported Function
`TpmIsPhysicalPresenceHardwareEnabled` | 109 | Exported Function
`TpmIsSrkAuthCompatible` | 112 | Exported Function
`TpmIsReadyInformation` | 111 | Exported Function
`TpmIsOwnerClearDisabled` | 106 | Exported Function
`TpmIsOwned` | 105 | Exported Function
`TpmIsPhysicalClearDisabled` | 108 | Exported Function
`TpmIsOwnershipAllowed` | 107 | Exported Function
`TpmIsUseLegacyDictionaryAttackParametersPolicySet` | 113 | Exported Function
`TpmProvision` | 119 | Exported Function
`TpmPrepForNgc` | 118 | Exported Function
`TpmRemoveRegisteredWindowsAIK` | 121 | Exported Function
`TpmRemoveBlockedCommand` | 120 | Exported Function
`TpmManufacturerVersion_From_TpmVersionInfo` | 116 | Exported Function
`TpmManufacturerId_From_TpmVersionInfo` | 114 | Exported Function
`TpmOwnerAuthEscrowed` | 117 | Exported Function
`TpmManufacturerVersionInfo_From_TpmVersionInfo` | 115 | Exported Function
`TpmCertGetHealthForceRetrieve` | 22 | Exported Function
`TpmCertGetHealthEndpoint` | 21 | Exported Function
`TpmCertGetHealthStatusRequestBlob` | 24 | Exported Function
`TpmCertGetHealthStatusCode` | 23 | Exported Function
`TpmCertGetHealthCert` | 18 | Exported Function
`TpmCertGetHASProtocolVersion` | 141 | Exported Function
`TpmCertGetHealthCorrelationId` | 20 | Exported Function
`TpmCertGetHealthCertFromWeb` | 19 | Exported Function
`TpmCertGetIsActiveZeroExhaust` | 25 | Exported Function
`TpmCertInstallNvEkCerts` | 31 | Exported Function
`TpmCertInstallEkCertInRegistry` | 30 | Exported Function
`TpmCertParseHealthResponse` | 33 | Exported Function
`TpmCertIsHealthCertOnBootEnabled` | 32 | Exported Function
`TpmCertGetPreferredMaximumProtocolVersion` | 27 | Exported Function
`TpmCertGetMaximumSupportedProtocolVersion` | 26 | Exported Function
`TpmCertGetWindowsAik` | 29 | Exported Function
`TpmCertGetTpmManufacturerId` | 28 | Exported Function
`TpmCertGetFwLinkId` | 17 | Exported Function
`Tpm20ResetLockoutCountIfNeeded` | 5 | Exported Function
`Tpm20IsResetLockoutCountNeeded` | 4 | Exported Function
`Tpm2ReadWindowsNvBit` | 7 | Exported Function
`Tpm2CreateWindowsNvBits` | 6 | Exported Function
`Tpm20CanClearUsingAuthPolicy` | 1 | Exported Function
`DllCanUnloadNow` | 140 | Exported Function
`Tpm20GetCompleteManufacturerVersion` | 3 | Exported Function
`Tpm20ClearUsingAuthPolicy` | 2 | Exported Function
`Tpm2SetWindowsNvBit` | 8 | Exported Function
`TpmCertGetEkCertFromWeb` | 14 | Exported Function
`TpmCertGetCurrentProtocolVersion` | 13 | Exported Function
`TpmCertGetFormattedUrl` | 16 | Exported Function
`TpmCertGetFormattedHASUrl` | 15 | Exported Function
`TpmCertCheckEkCertMatchedEkPub` | 10 | Exported Function
`TpmAddBlockedCommand` | 9 | Exported Function
`TpmCertDeleteHealthEndpoint` | 12 | Exported Function
`TpmCertDeleteHealthCert` | 11 | Exported Function
`TpmCertPostHealthXmlData` | 34 | Exported Function
`TpmGatherLogs` | 57 | Exported Function
`TpmEnableAutoProvisioning` | 56 | Exported Function
`TpmGet_IsPpiVersion12` | 83 | Exported Function
`TpmGatherTpmData` | 58 | Exported Function
`TpmDisableAutoProvisioning` | 53 | Exported Function
`TpmDisable` | 52 | Exported Function
`TpmEnable` | 55 | Exported Function
`TpmEKCertValidateAndCleanup` | 54 | Exported Function
`TpmGet_IsTpmPresent` | 84 | Exported Function
`TpmGet_SpecVersion` | 90 | Exported Function
`TpmGet_PhysicalPresenceVersionInfo` | 89 | Exported Function
`TpmGetCapLockoutInfo` | 59 | Exported Function
`TpmGet_TpmVersionInfo` | 91 | Exported Function
`TpmGet_ManufacturerId` | 86 | Exported Function
`TpmGet_IsTpmVersion20` | 85 | Exported Function
`TpmGet_ManufacturerVersionInfo` | 88 | Exported Function
`TpmGet_ManufacturerVersion` | 87 | Exported Function
`TpmDeleteOwnerAuth` | 51 | Exported Function
`TpmCertSetPreferredMaximumProtocolVersion` | 39 | Exported Function
`TpmCertSetHealthStatusCode` | 38 | Exported Function
`TpmChangeOwnerAuth` | 41 | Exported Function
`TpmCertVerifyHealthCertFromWeb` | 40 | Exported Function
`TpmCertSetEkAttestationOverride` | 142 | Exported Function
`TpmCertQueryEkPub` | 35 | Exported Function
`TpmCertSetHealthForceRetrieve` | 37 | Exported Function
`TpmCertSetHealthEndpoint` | 36 | Exported Function
`TpmCheckCreateWindowsAIK` | 42 | Exported Function
`TpmCreateEndorsementKeyPair` | 48 | Exported Function
`TpmConvertToOwnerAuth` | 47 | Exported Function
`TpmCreateHealthStatusClaim` | 50 | Exported Function
`TpmCreateHealthAttestationClaim` | 49 | Exported Function
`TpmClear` | 44 | Exported Function
`TpmCheckIFXRSAKeyGenVulnerability` | 43 | Exported Function
`TpmClearWithPolicyOrPPI` | 46 | Exported Function
`TpmClearUsingPhysicalPresence` | 45 | Exported Function


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


