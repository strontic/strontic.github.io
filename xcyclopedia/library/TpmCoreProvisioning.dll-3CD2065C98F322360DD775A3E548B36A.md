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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 140 (0x8c) | Exported Function | 0x10039e80 | 0x00039e80
`TpmIsEndorsementKeyPairPresent` | 101 (0x65) | Exported Function | 0x100541e0 | 0x000541e0
`TpmIsEnabled` | 100 (0x64) | Exported Function | 0x100538e0 | 0x000538e0
`TpmIsCommandPresent` | 99 (0x63) | Exported Function | 0x10053ee0 | 0x00053ee0
`TpmIsCommandBlocked` | 98 (0x62) | Exported Function | 0x10055d10 | 0x00055d10
`TpmIsAutoProvisioningEnabledEx` | 97 (0x61) | Exported Function | 0x10055fa0 | 0x00055fa0
`TpmIsAutoProvisioningEnabled` | 96 (0x60) | Exported Function | 0x10055f50 | 0x00055f50
`TpmIsActivated` | 95 (0x5f) | Exported Function | 0x10053b20 | 0x00053b20
`TpmImportOwnerAuth` | 94 (0x5e) | Exported Function | 0x10056400 | 0x00056400
`TpmHealthCertGetAndVerify` | 93 (0x5d) | Exported Function | 0x10060f80 | 0x00060f80
`TpmHasVulnerableFW` | 92 (0x5c) | Exported Function | 0x10057bc0 | 0x00057bc0
`TpmGetVerificationRequest` | 82 (0x52) | Exported Function | 0x10061670 | 0x00061670
`TpmGetTpmVersion` | 81 (0x51) | Exported Function | 0x100579a0 | 0x000579a0
`TpmGetTcgLog` | 80 (0x50) | Exported Function | 0x10056710 | 0x00056710
`TpmGetSrkPublicKeyModulus` | 79 (0x4f) | Exported Function | 0x10056580 | 0x00056580
`TpmGetSrkADThumbprint` | 78 (0x4e) | Exported Function | 0x10056640 | 0x00056640
`TpmGetSignedEKFromVendorCommand` | 77 (0x4d) | Exported Function | 0x10057f90 | 0x00057f90
`TpmGetRandomAuthValue` | 76 (0x4c) | Exported Function | 0x100554a0 | 0x000554a0
`TpmGetEffectiveGroupPolicyOwnerAuthLevel` | 62 (0x3e) | Exported Function | 0x10056a20 | 0x00056a20
`TpmGetEndorsementKeyCertificateState` | 63 (0x3f) | Exported Function | 0x10057320 | 0x00057320
`TpmGetHealthCertRequest` | 64 (0x40) | Exported Function | 0x100615b0 | 0x000615b0
`TpmGetOrderlyShutdownInfo` | 65 (0x41) | Exported Function | 0x10056d10 | 0x00056d10
`TpmGetOwnerAuth` | 66 (0x42) | Exported Function | 0x100561b0 | 0x000561b0
`TpmGetOwnerAuthForEscrow` | 67 (0x43) | Exported Function | 0x100567d0 | 0x000567d0
`TpmIsFIPS` | 102 (0x66) | Exported Function | 0x100542a0 | 0x000542a0
`TpmGetOwnerAuthStatus` | 68 (0x44) | Exported Function | 0x10056960 | 0x00056960
`TpmGetPhysicalPresenceConfirmationStatus` | 71 (0x47) | Exported Function | 0x100564c0 | 0x000564c0
`TpmGetPhysicalPresenceRequest` | 72 (0x48) | Exported Function | 0x10055870 | 0x00055870
`TpmGetPhysicalPresenceResponse` | 73 (0x49) | Exported Function | 0x100559f0 | 0x000559f0
`TpmGetPhysicalPresenceTransition` | 74 (0x4a) | Exported Function | 0x10055930 | 0x00055930
`TpmGetPPIVersion` | 70 (0x46) | Exported Function | 0x10057a30 | 0x00057a30
`TpmGetPssSalt` | 75 (0x4b) | Exported Function | 0x10057ec0 | 0x00057ec0
`TpmGetOwnershipAuthBits` | 69 (0x45) | Exported Function | 0x10053a60 | 0x00053a60
`TpmIsKeyAttestationCapable` | 103 (0x67) | Exported Function | 0x10053fa0 | 0x00053fa0
`TpmIsLockedOut` | 104 (0x68) | Exported Function | 0x10057560 | 0x00057560
`TpmIsOwned` | 105 (0x69) | Exported Function | 0x100539a0 | 0x000539a0
`TpmRetrieveEkCertificate` | 125 (0x7d) | Exported Function | 0x10063340 | 0x00063340
`TpmRetrieveEkCertificateURL` | 126 (0x7e) | Exported Function | 0x100631f0 | 0x000631f0
`TpmRetrieveEkCertOrReschedule` | 124 (0x7c) | Exported Function | 0x10057190 | 0x00057190
`TpmRetrieveHealthCertificate` | 128 (0x80) | Exported Function | 0x10060ea0 | 0x00060ea0
`TpmRetrieveHealthCertOrReschedule` | 127 (0x7f) | Exported Function | 0x10057250 | 0x00057250
`TpmSelfTest` | 129 (0x81) | Exported Function | 0x10055560 | 0x00055560
`TpmResetSrkAuth` | 123 (0x7b) | Exported Function | 0x10055190 | 0x00055190
`TpmSetDictionaryAttackParameters` | 130 (0x82) | Exported Function | 0x10056c40 | 0x00056c40
`TpmSetPhysicalPresenceRequest` | 132 (0x84) | Exported Function | 0x100556f0 | 0x000556f0
`TpmSetPhysicalPresenceRequestEx` | 133 (0x85) | Exported Function | 0x100557b0 | 0x000557b0
`TpmSetToLegacyDictionaryAttackParameters` | 134 (0x86) | Exported Function | 0x100573e0 | 0x000573e0
`TpmSpecVersion_From_TpmVersionInfo` | 135 (0x87) | Exported Function | 0x10053810 | 0x00053810
`TpmTakeOwnership` | 136 (0x88) | Exported Function | 0x10054420 | 0x00054420
`TpmUnattendedSetup` | 137 (0x89) | Exported Function | 0x100576e0 | 0x000576e0
`TpmSetInstance` | 131 (0x83) | Exported Function | 0x10052ce0 | 0x00052ce0
`TpmGetDictionaryAttackParameters` | 61 (0x3d) | Exported Function | 0x10056b70 | 0x00056b70
`TpmResetAuthLockOut` | 122 (0x7a) | Exported Function | 0x10055c50 | 0x00055c50
`TpmRemoveBlockedCommand` | 120 (0x78) | Exported Function | 0x10055b90 | 0x00055b90
`TpmIsOwnerClearDisabled` | 106 (0x6a) | Exported Function | 0x10053ca0 | 0x00053ca0
`TpmIsOwnershipAllowed` | 107 (0x6b) | Exported Function | 0x10053e20 | 0x00053e20
`TpmIsPhysicalClearDisabled` | 108 (0x6c) | Exported Function | 0x10053be0 | 0x00053be0
`TpmIsPhysicalPresenceHardwareEnabled` | 109 (0x6d) | Exported Function | 0x10053d60 | 0x00053d60
`TpmIsReady` | 110 (0x6e) | Exported Function | 0x10055dd0 | 0x00055dd0
`TpmIsReadyInformation` | 111 (0x6f) | Exported Function | 0x10055e90 | 0x00055e90
`TpmRemoveRegisteredWindowsAIK` | 121 (0x79) | Exported Function | 0x10057010 | 0x00057010
`TpmIsSrkAuthCompatible` | 112 (0x70) | Exported Function | 0x100550d0 | 0x000550d0
`TpmManufacturerId_From_TpmVersionInfo` | 114 (0x72) | Exported Function | 0x100535b0 | 0x000535b0
`TpmManufacturerVersion_From_TpmVersionInfo` | 116 (0x74) | Exported Function | 0x10053670 | 0x00053670
`TpmManufacturerVersionInfo_From_TpmVersionInfo` | 115 (0x73) | Exported Function | 0x10053740 | 0x00053740
`TpmOwnerAuthEscrowed` | 117 (0x75) | Exported Function | 0x100568a0 | 0x000568a0
`TpmPrepForNgc` | 118 (0x76) | Exported Function | 0x100570d0 | 0x000570d0
`TpmProvision` | 119 (0x77) | Exported Function | 0x10056330 | 0x00056330
`TpmIsUseLegacyDictionaryAttackParametersPolicySet` | 113 (0x71) | Exported Function | 0x100544e0 | 0x000544e0
`TpmGetDeviceInformation` | 60 (0x3c) | Exported Function | 0x10057b00 | 0x00057b00
`TpmGetCapLockoutInfo` | 59 (0x3b) | Exported Function | 0x10056dd0 | 0x00056dd0
`TpmGet_TpmVersionInfo` | 91 (0x5b) | Exported Function | 0x10053280 | 0x00053280
`TpmCertGetHealthCert` | 18 (0x12) | Exported Function | 0x10060260 | 0x00060260
`TpmCertGetHealthCertFromWeb` | 19 (0x13) | Exported Function | 0x10067f80 | 0x00067f80
`TpmCertGetHealthCorrelationId` | 20 (0x14) | Exported Function | 0x1005fd30 | 0x0005fd30
`TpmCertGetHealthEndpoint` | 21 (0x15) | Exported Function | 0x1005fb00 | 0x0005fb00
`TpmCertGetHealthForceRetrieve` | 22 (0x16) | Exported Function | 0x1005fec0 | 0x0005fec0
`TpmCertGetHealthStatusCode` | 23 (0x17) | Exported Function | 0x10060040 | 0x00060040
`TpmCertGetHASProtocolVersion` | 141 (0x8d) | Exported Function | 0x1005f8b0 | 0x0005f8b0
`TpmCertGetHealthStatusRequestBlob` | 24 (0x18) | Exported Function | 0x10067ce0 | 0x00067ce0
`TpmCertGetMaximumSupportedProtocolVersion` | 26 (0x1a) | Exported Function | 0x10060330 | 0x00060330
`TpmCertGetPreferredMaximumProtocolVersion` | 27 (0x1b) | Exported Function | 0x100603f0 | 0x000603f0
`TpmCertGetTpmManufacturerId` | 28 (0x1c) | Exported Function | 0x10062220 | 0x00062220
`TpmCertGetWindowsAik` | 29 (0x1d) | Exported Function | 0x10060c50 | 0x00060c50
`TpmCertInstallEkCertInRegistry` | 30 (0x1e) | Exported Function | 0x10062740 | 0x00062740
`TpmCertInstallNvEkCerts` | 31 (0x1f) | Exported Function | 0x100622e0 | 0x000622e0
`TpmCertGetIsActiveZeroExhaust` | 25 (0x19) | Exported Function | 0x100637c0 | 0x000637c0
`TpmCertIsHealthCertOnBootEnabled` | 32 (0x20) | Exported Function | 0x10060870 | 0x00060870
`TpmCertGetFwLinkId` | 17 (0x11) | Exported Function | 0x100644b0 | 0x000644b0
`TpmCertGetFormattedHASUrl` | 15 (0xf) | Exported Function | 0x10065bd0 | 0x00065bd0
`Tpm20CanClearUsingAuthPolicy` | 1 (0x1) | Exported Function | 0x10054e90 | 0x00054e90
`Tpm20ClearUsingAuthPolicy` | 2 (0x2) | Exported Function | 0x10054f50 | 0x00054f50
`Tpm20GetCompleteManufacturerVersion` | 3 (0x3) | Exported Function | 0x100578e0 | 0x000578e0
`Tpm20IsResetLockoutCountNeeded` | 4 (0x4) | Exported Function | 0x10055320 | 0x00055320
`Tpm20ResetLockoutCountIfNeeded` | 5 (0x5) | Exported Function | 0x100553e0 | 0x000553e0
`Tpm2CreateWindowsNvBits` | 6 (0x6) | Exported Function | 0x10054670 | 0x00054670
`TpmCertGetFormattedUrl` | 16 (0x10) | Exported Function | 0x10065a20 | 0x00065a20
`Tpm2ReadWindowsNvBit` | 7 (0x7) | Exported Function | 0x10054730 | 0x00054730
`TpmAddBlockedCommand` | 9 (0x9) | Exported Function | 0x10055ad0 | 0x00055ad0
`TpmCertCheckEkCertMatchedEkPub` | 10 (0xa) | Exported Function | 0x10062670 | 0x00062670
`TpmCertDeleteHealthCert` | 11 (0xb) | Exported Function | 0x10060630 | 0x00060630
`TpmCertDeleteHealthEndpoint` | 12 (0xc) | Exported Function | 0x1005fbc0 | 0x0005fbc0
`TpmCertGetCurrentProtocolVersion` | 13 (0xd) | Exported Function | 0x10060570 | 0x00060570
`TpmCertGetEkCertFromWeb` | 14 (0xe) | Exported Function | 0x10065d60 | 0x00065d60
`Tpm2SetWindowsNvBit` | 8 (0x8) | Exported Function | 0x100547f0 | 0x000547f0
`TpmVerifyDeviceHealth` | 138 (0x8a) | Exported Function | 0x100614f0 | 0x000614f0
`TpmCertParseHealthResponse` | 33 (0x21) | Exported Function | 0x10064fd0 | 0x00064fd0
`TpmCertQueryEkPub` | 35 (0x23) | Exported Function | 0x10062580 | 0x00062580
`TpmDisableAutoProvisioning` | 53 (0x35) | Exported Function | 0x10056100 | 0x00056100
`TpmEKCertValidateAndCleanup` | 54 (0x36) | Exported Function | 0x100574a0 | 0x000574a0
`TpmEnable` | 55 (0x37) | Exported Function | 0x10054060 | 0x00054060
`TpmEnableAutoProvisioning` | 56 (0x38) | Exported Function | 0x10056050 | 0x00056050
`TpmGatherLogs` | 57 (0x39) | Exported Function | 0x10057d40 | 0x00057d40
`TpmGatherTpmData` | 58 (0x3a) | Exported Function | 0x1006a050 | 0x0006a050
`TpmDisable` | 52 (0x34) | Exported Function | 0x10054120 | 0x00054120
`TpmGet_IsPpiVersion12` | 83 (0x53) | Exported Function | 0x100534f0 | 0x000534f0
`TpmGet_IsTpmVersion20` | 85 (0x55) | Exported Function | 0x10053400 | 0x00053400
`TpmGet_ManufacturerId` | 86 (0x56) | Exported Function | 0x10052e80 | 0x00052e80
`TpmGet_ManufacturerVersion` | 87 (0x57) | Exported Function | 0x10052f80 | 0x00052f80
`TpmGet_ManufacturerVersionInfo` | 88 (0x58) | Exported Function | 0x10053040 | 0x00053040
`TpmGet_PhysicalPresenceVersionInfo` | 89 (0x59) | Exported Function | 0x100531c0 | 0x000531c0
`TpmGet_SpecVersion` | 90 (0x5a) | Exported Function | 0x10053100 | 0x00053100
`TpmGet_IsTpmPresent` | 84 (0x54) | Exported Function | 0x10053360 | 0x00053360
`TpmCertPostHealthXmlData` | 34 (0x22) | Exported Function | 0x10067dc0 | 0x00067dc0
`TpmDeleteOwnerAuth` | 51 (0x33) | Exported Function | 0x10056270 | 0x00056270
`TpmCreateHealthAttestationClaim` | 49 (0x31) | Exported Function | 0x10060ac0 | 0x00060ac0
`TpmCertSetEkAttestationOverride` | 142 (0x8e) | Exported Function | 0x1005f980 | 0x0005f980
`TpmCertSetHealthEndpoint` | 36 (0x24) | Exported Function | 0x1005fa40 | 0x0005fa40
`TpmCertSetHealthForceRetrieve` | 37 (0x25) | Exported Function | 0x1005fe00 | 0x0005fe00
`TpmCertSetHealthStatusCode` | 38 (0x26) | Exported Function | 0x1005ff80 | 0x0005ff80
`TpmCertSetPreferredMaximumProtocolVersion` | 39 (0x27) | Exported Function | 0x100604b0 | 0x000604b0
`TpmCertVerifyHealthCertFromWeb` | 40 (0x28) | Exported Function | 0x10068110 | 0x00068110
`TpmCreateHealthStatusClaim` | 50 (0x32) | Exported Function | 0x100608f0 | 0x000608f0
`TpmChangeOwnerAuth` | 41 (0x29) | Exported Function | 0x10055250 | 0x00055250
`TpmCheckIFXRSAKeyGenVulnerability` | 43 (0x2b) | Exported Function | 0x1006a380 | 0x0006a380
`TpmClear` | 44 (0x2c) | Exported Function | 0x10055010 | 0x00055010
`TpmClearUsingPhysicalPresence` | 45 (0x2d) | Exported Function | 0x10057620 | 0x00057620
`TpmClearWithPolicyOrPPI` | 46 (0x2e) | Exported Function | 0x10057c80 | 0x00057c80
`TpmConvertToOwnerAuth` | 47 (0x2f) | Exported Function | 0x10055620 | 0x00055620
`TpmCreateEndorsementKeyPair` | 48 (0x30) | Exported Function | 0x10054360 | 0x00054360
`TpmCheckCreateWindowsAIK` | 42 (0x2a) | Exported Function | 0x10056e90 | 0x00056e90
`TpmWriteInformationSnapshotFile` | 139 (0x8b) | Exported Function | 0x10057e00 | 0x00057e00


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


