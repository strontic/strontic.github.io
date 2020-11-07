---
title: TpmCoreProvisioning.dll | TPM Core Provisioning Library
excerpt: What is TpmCoreProvisioning.dll?
---

# TpmCoreProvisioning.dll 

* File Path: `C:\Windows\SysWOW64\TpmCoreProvisioning.dll`
* Description: TPM Core Provisioning Library

## Hashes

Type | Hash
-- | --
MD5 | `3CD2065C98F322360DD775A3E548B36A`
SHA1 | `CEA9E35C9BC8F01EE49DDA4CCDE683634252B78D`
SHA256 | `5702FD455966DAC163F997E50A76CA8D5B8251430DF2133E6E41F54B61CFCEA8`
SHA384 | `64FC4E4CA19B4EA68A7D9795CE0F70CAAF04D896D58A5D4291D7F4BD8CE85D2D3898E75F5ED29A852771584308067680`
SHA512 | `F68338C3B4B4C44AC74F463412750E6ABF79B35454AC1FB377E4709F0E89A868E6179F9B2D4F26D097C80464EA54B9B841C00F1FC5793804DEA5F396E95EB5CE`
SSDEEP | `24576:TA/52ev5olav2FW3bKZrt3CouwXzQlKmMOZ2wD:TA/oev5olY20rKZwCQlVMOZ2wD`
IMP | `033C9B3860B914CD9FF17E3D3EC884AA`
PESHA1 | `9750E37B0BDC932A34C5021CBEA19731F365C33A`
PE256 | `92E1C244D47D274FE04556EFF60274DADCD23B5C2CF3B9F1AFDA9F6134759AE2`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 140 | Exported Function
`TpmIsEndorsementKeyPairPresent` | 101 | Exported Function
`TpmIsEnabled` | 100 | Exported Function
`TpmIsCommandPresent` | 99 | Exported Function
`TpmIsCommandBlocked` | 98 | Exported Function
`TpmIsAutoProvisioningEnabledEx` | 97 | Exported Function
`TpmIsAutoProvisioningEnabled` | 96 | Exported Function
`TpmIsActivated` | 95 | Exported Function
`TpmImportOwnerAuth` | 94 | Exported Function
`TpmHealthCertGetAndVerify` | 93 | Exported Function
`TpmHasVulnerableFW` | 92 | Exported Function
`TpmGetVerificationRequest` | 82 | Exported Function
`TpmGetTpmVersion` | 81 | Exported Function
`TpmGetTcgLog` | 80 | Exported Function
`TpmGetSrkPublicKeyModulus` | 79 | Exported Function
`TpmGetSrkADThumbprint` | 78 | Exported Function
`TpmGetSignedEKFromVendorCommand` | 77 | Exported Function
`TpmGetRandomAuthValue` | 76 | Exported Function
`TpmGetEffectiveGroupPolicyOwnerAuthLevel` | 62 | Exported Function
`TpmGetEndorsementKeyCertificateState` | 63 | Exported Function
`TpmGetHealthCertRequest` | 64 | Exported Function
`TpmGetOrderlyShutdownInfo` | 65 | Exported Function
`TpmGetOwnerAuth` | 66 | Exported Function
`TpmGetOwnerAuthForEscrow` | 67 | Exported Function
`TpmIsFIPS` | 102 | Exported Function
`TpmGetOwnerAuthStatus` | 68 | Exported Function
`TpmGetPhysicalPresenceConfirmationStatus` | 71 | Exported Function
`TpmGetPhysicalPresenceRequest` | 72 | Exported Function
`TpmGetPhysicalPresenceResponse` | 73 | Exported Function
`TpmGetPhysicalPresenceTransition` | 74 | Exported Function
`TpmGetPPIVersion` | 70 | Exported Function
`TpmGetPssSalt` | 75 | Exported Function
`TpmGetOwnershipAuthBits` | 69 | Exported Function
`TpmIsKeyAttestationCapable` | 103 | Exported Function
`TpmIsLockedOut` | 104 | Exported Function
`TpmIsOwned` | 105 | Exported Function
`TpmRetrieveEkCertificate` | 125 | Exported Function
`TpmRetrieveEkCertificateURL` | 126 | Exported Function
`TpmRetrieveEkCertOrReschedule` | 124 | Exported Function
`TpmRetrieveHealthCertificate` | 128 | Exported Function
`TpmRetrieveHealthCertOrReschedule` | 127 | Exported Function
`TpmSelfTest` | 129 | Exported Function
`TpmResetSrkAuth` | 123 | Exported Function
`TpmSetDictionaryAttackParameters` | 130 | Exported Function
`TpmSetPhysicalPresenceRequest` | 132 | Exported Function
`TpmSetPhysicalPresenceRequestEx` | 133 | Exported Function
`TpmSetToLegacyDictionaryAttackParameters` | 134 | Exported Function
`TpmSpecVersion_From_TpmVersionInfo` | 135 | Exported Function
`TpmTakeOwnership` | 136 | Exported Function
`TpmUnattendedSetup` | 137 | Exported Function
`TpmSetInstance` | 131 | Exported Function
`TpmGetDictionaryAttackParameters` | 61 | Exported Function
`TpmResetAuthLockOut` | 122 | Exported Function
`TpmRemoveBlockedCommand` | 120 | Exported Function
`TpmIsOwnerClearDisabled` | 106 | Exported Function
`TpmIsOwnershipAllowed` | 107 | Exported Function
`TpmIsPhysicalClearDisabled` | 108 | Exported Function
`TpmIsPhysicalPresenceHardwareEnabled` | 109 | Exported Function
`TpmIsReady` | 110 | Exported Function
`TpmIsReadyInformation` | 111 | Exported Function
`TpmRemoveRegisteredWindowsAIK` | 121 | Exported Function
`TpmIsSrkAuthCompatible` | 112 | Exported Function
`TpmManufacturerId_From_TpmVersionInfo` | 114 | Exported Function
`TpmManufacturerVersion_From_TpmVersionInfo` | 116 | Exported Function
`TpmManufacturerVersionInfo_From_TpmVersionInfo` | 115 | Exported Function
`TpmOwnerAuthEscrowed` | 117 | Exported Function
`TpmPrepForNgc` | 118 | Exported Function
`TpmProvision` | 119 | Exported Function
`TpmIsUseLegacyDictionaryAttackParametersPolicySet` | 113 | Exported Function
`TpmGetDeviceInformation` | 60 | Exported Function
`TpmGetCapLockoutInfo` | 59 | Exported Function
`TpmGet_TpmVersionInfo` | 91 | Exported Function
`TpmCertGetHealthCert` | 18 | Exported Function
`TpmCertGetHealthCertFromWeb` | 19 | Exported Function
`TpmCertGetHealthCorrelationId` | 20 | Exported Function
`TpmCertGetHealthEndpoint` | 21 | Exported Function
`TpmCertGetHealthForceRetrieve` | 22 | Exported Function
`TpmCertGetHealthStatusCode` | 23 | Exported Function
`TpmCertGetHASProtocolVersion` | 141 | Exported Function
`TpmCertGetHealthStatusRequestBlob` | 24 | Exported Function
`TpmCertGetMaximumSupportedProtocolVersion` | 26 | Exported Function
`TpmCertGetPreferredMaximumProtocolVersion` | 27 | Exported Function
`TpmCertGetTpmManufacturerId` | 28 | Exported Function
`TpmCertGetWindowsAik` | 29 | Exported Function
`TpmCertInstallEkCertInRegistry` | 30 | Exported Function
`TpmCertInstallNvEkCerts` | 31 | Exported Function
`TpmCertGetIsActiveZeroExhaust` | 25 | Exported Function
`TpmCertIsHealthCertOnBootEnabled` | 32 | Exported Function
`TpmCertGetFwLinkId` | 17 | Exported Function
`TpmCertGetFormattedHASUrl` | 15 | Exported Function
`Tpm20CanClearUsingAuthPolicy` | 1 | Exported Function
`Tpm20ClearUsingAuthPolicy` | 2 | Exported Function
`Tpm20GetCompleteManufacturerVersion` | 3 | Exported Function
`Tpm20IsResetLockoutCountNeeded` | 4 | Exported Function
`Tpm20ResetLockoutCountIfNeeded` | 5 | Exported Function
`Tpm2CreateWindowsNvBits` | 6 | Exported Function
`TpmCertGetFormattedUrl` | 16 | Exported Function
`Tpm2ReadWindowsNvBit` | 7 | Exported Function
`TpmAddBlockedCommand` | 9 | Exported Function
`TpmCertCheckEkCertMatchedEkPub` | 10 | Exported Function
`TpmCertDeleteHealthCert` | 11 | Exported Function
`TpmCertDeleteHealthEndpoint` | 12 | Exported Function
`TpmCertGetCurrentProtocolVersion` | 13 | Exported Function
`TpmCertGetEkCertFromWeb` | 14 | Exported Function
`Tpm2SetWindowsNvBit` | 8 | Exported Function
`TpmVerifyDeviceHealth` | 138 | Exported Function
`TpmCertParseHealthResponse` | 33 | Exported Function
`TpmCertQueryEkPub` | 35 | Exported Function
`TpmDisableAutoProvisioning` | 53 | Exported Function
`TpmEKCertValidateAndCleanup` | 54 | Exported Function
`TpmEnable` | 55 | Exported Function
`TpmEnableAutoProvisioning` | 56 | Exported Function
`TpmGatherLogs` | 57 | Exported Function
`TpmGatherTpmData` | 58 | Exported Function
`TpmDisable` | 52 | Exported Function
`TpmGet_IsPpiVersion12` | 83 | Exported Function
`TpmGet_IsTpmVersion20` | 85 | Exported Function
`TpmGet_ManufacturerId` | 86 | Exported Function
`TpmGet_ManufacturerVersion` | 87 | Exported Function
`TpmGet_ManufacturerVersionInfo` | 88 | Exported Function
`TpmGet_PhysicalPresenceVersionInfo` | 89 | Exported Function
`TpmGet_SpecVersion` | 90 | Exported Function
`TpmGet_IsTpmPresent` | 84 | Exported Function
`TpmCertPostHealthXmlData` | 34 | Exported Function
`TpmDeleteOwnerAuth` | 51 | Exported Function
`TpmCreateHealthAttestationClaim` | 49 | Exported Function
`TpmCertSetEkAttestationOverride` | 142 | Exported Function
`TpmCertSetHealthEndpoint` | 36 | Exported Function
`TpmCertSetHealthForceRetrieve` | 37 | Exported Function
`TpmCertSetHealthStatusCode` | 38 | Exported Function
`TpmCertSetPreferredMaximumProtocolVersion` | 39 | Exported Function
`TpmCertVerifyHealthCertFromWeb` | 40 | Exported Function
`TpmCreateHealthStatusClaim` | 50 | Exported Function
`TpmChangeOwnerAuth` | 41 | Exported Function
`TpmCheckIFXRSAKeyGenVulnerability` | 43 | Exported Function
`TpmClear` | 44 | Exported Function
`TpmClearUsingPhysicalPresence` | 45 | Exported Function
`TpmClearWithPolicyOrPPI` | 46 | Exported Function
`TpmConvertToOwnerAuth` | 47 | Exported Function
`TpmCreateEndorsementKeyPair` | 48 | Exported Function
`TpmCheckCreateWindowsAIK` | 42 | Exported Function
`TpmWriteInformationSnapshotFile` | 139 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TpmCoreProvisioning.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5702fd455966dac163f997e50a76ca8d5b8251430df2133e6e41f54b61cfcea8/detection/





MIT License. Copyright (c) 2020 Strontic.


