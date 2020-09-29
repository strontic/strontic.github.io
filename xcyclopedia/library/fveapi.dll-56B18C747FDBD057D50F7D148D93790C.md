---
title: fveapi.dll | Windows BitLocker Drive Encryption API
excerpt: What is fveapi.dll?
---

# fveapi.dll 

* File Path: `C:\Windows\system32\fveapi.dll`
* Description: Windows BitLocker Drive Encryption API

## Hashes

Type | Hash
-- | --
MD5 | `56B18C747FDBD057D50F7D148D93790C`
SHA1 | `FEEAB5424A1DAA3C55FB663F285AB3EB72832138`
SHA256 | `7F4556840DFFC92A2FD38EDF0033B2F51B09CD894871281D025C6A2C05BA66B9`
SHA384 | `4D66E305F7273F44EE51FE80B46E7C2E04CEB568A6AD237CF96CE02EAF30231AA02E7E9E50F443696FDBC1D756997042`
SHA512 | `59D684AC46706D86A0B5D0C48C927317151CCEF9E5E942863A988138BD7DBB8C14C8D14A63362DC1A6C87C496E335E1371BC93A307D6A362759C7ADCF58F859F`
SSDEEP | `24576:TgBTqIamYiyWF2ljx/MFNMHgTE+KGO7n:sBTqIamQJZxkFzKGO7`
IMP | `8BFD6D482650FFD1CFC9C879E9692C99`
PESHA1 | `C40E3AAB885558E59098627294B10272C68224CF`
PE256 | `E8A341B596290D905C87D03F939B896DA5B114AC731757328E1D1165C6FAF8CA`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FveAddAuthMethodInformation` | 11 (0xb) | Exported Function | 0x00000001800209f0 | 0x000209f0
`FveLockDevice` | 105 (0x69) | Exported Function | 0x00000001800449f0 | 0x000449f0
`FveLockVolume` | 106 (0x6a) | Exported Function | 0x0000000180009ae0 | 0x00009ae0
`FveLogRecoveryReason` | 107 (0x6b) | Exported Function | 0x0000000180044ac0 | 0x00044ac0
`FveNeedsDiscoveryVolumeUpdate` | 108 (0x6c) | Exported Function | 0x0000000180044bc0 | 0x00044bc0
`FveNotifyVolumeAfterFormat` | 109 (0x6d) | Exported Function | 0x000000018000af70 | 0x0000af70
`FveOpenVolumeByHandle` | 110 (0x6e) | Exported Function | 0x000000018001db10 | 0x0001db10
`FveKeyManagement` | 104 (0x68) | Exported Function | 0x00000001800448b0 | 0x000448b0
`FveOpenVolumeExW` | 111 (0x6f) | Exported Function | 0x0000000180021c70 | 0x00021c70
`FveProtectorTypeToFlags` | 113 (0x71) | Exported Function | 0x000000018001f630 | 0x0001f630
`FveQuery` | 114 (0x72) | Exported Function | 0x0000000180044cd0 | 0x00044cd0
`FveQueryDeviceEncryptionSupport` | 115 (0x73) | Exported Function | 0x0000000180025280 | 0x00025280
`FveRecalculateOffsetsAndMoveMetadata` | 116 (0x74) | Exported Function | 0x0000000180044d90 | 0x00044d90
`FveRegenerateNbpSessionKey` | 117 (0x75) | Exported Function | 0x000000018001fb30 | 0x0001fb30
`FveResetTpmDictionaryAttackParameters` | 118 (0x76) | Exported Function | 0x0000000180044eb0 | 0x00044eb0
`FveOpenVolumeW` | 112 (0x70) | Exported Function | 0x0000000180021c40 | 0x00021c40
`FveIsVolumeEncryptable` | 103 (0x67) | Exported Function | 0x0000000180026ed0 | 0x00026ed0
`FveIsSchemaExtInstalled` | 102 (0x66) | Exported Function | 0x0000000180044800 | 0x00044800
`FveIsRecoveryPasswordValidW` | 101 (0x65) | Exported Function | 0x000000018000ac10 | 0x0000ac10
`FveGetVolumeNameW` | 86 (0x56) | Exported Function | 0x000000018001d8b0 | 0x0001d8b0
`FveInitializeDeviceEncryption` | 89 (0x59) | Exported Function | 0x0000000180043e00 | 0x00043e00
`FveInitializeDeviceEncryption2` | 90 (0x5a) | Exported Function | 0x0000000180044050 | 0x00044050
`FveInitVolume` | 87 (0x57) | Exported Function | 0x0000000180043d60 | 0x00043d60
`FveInitVolumeEx` | 88 (0x58) | Exported Function | 0x0000000180002af0 | 0x00002af0
`FveIsAnyDataVolumeBoundToOSVolume` | 91 (0x5b) | Exported Function | 0x0000000180044200 | 0x00044200
`FveIsBoundDataVolume` | 92 (0x5c) | Exported Function | 0x000000018000d970 | 0x0000d970
`FveIsBoundDataVolumeToOSVolume` | 93 (0x5d) | Exported Function | 0x00000001800442f0 | 0x000442f0
`FveIsDeviceLockable` | 94 (0x5e) | Exported Function | 0x0000000180044410 | 0x00044410
`FveIsDeviceLockedOut` | 95 (0x5f) | Exported Function | 0x0000000180044510 | 0x00044510
`FveIsHardwareReadyForConversion` | 96 (0x60) | Exported Function | 0x0000000180041dc0 | 0x00041dc0
`FveIsHybridVolume` | 97 (0x61) | Exported Function | 0x00000001800445f0 | 0x000445f0
`FveIsHybridVolumeW` | 98 (0x62) | Exported Function | 0x0000000180044700 | 0x00044700
`FveIsPassphraseCompatibleW` | 99 (0x63) | Exported Function | 0x0000000180041e50 | 0x00041e50
`FveIsRecoveryPasswordGroupValidW` | 100 (0x64) | Exported Function | 0x0000000180041f20 | 0x00041f20
`FveRevertVolume` | 119 (0x77) | Exported Function | 0x0000000180041fe0 | 0x00041fe0
`FveGetUserFlags` | 85 (0x55) | Exported Function | 0x00000001800410e0 | 0x000410e0
`FveSaveRecoveryPasswordBackupFlag` | 120 (0x78) | Exported Function | 0x00000001800420b0 | 0x000420b0
`FveServiceDiscoveryVolume` | 122 (0x7a) | Exported Function | 0x0000000180044ff0 | 0x00044ff0
`FveUpdateDeviceLockoutStateEx` | 142 (0x8e) | Exported Function | 0x0000000180045c30 | 0x00045c30
`FveUpdatePinW` | 143 (0x8f) | Exported Function | 0x0000000180045d40 | 0x00045d40
`FveUpgradeVolume` | 144 (0x90) | Exported Function | 0x0000000180042390 | 0x00042390
`FveValidateDeviceLockoutState` | 145 (0x91) | Exported Function | 0x0000000180045e50 | 0x00045e50
`FveValidateExistingPassphraseW` | 146 (0x92) | Exported Function | 0x0000000180045f20 | 0x00045f20
`FveValidateExistingPinW` | 147 (0x93) | Exported Function | 0x0000000180046030 | 0x00046030
`FveUpdateDeviceLockoutState` | 141 (0x8d) | Exported Function | 0x0000000180045b80 | 0x00045b80
`InternalFveIsVolumeEncrypted` | 1 (0x1) | Exported Function | 0x0000000180040b90 | 0x00040b90
`NgscbCheckDmaSecurityEx` | 3 (0x3) | Exported Function | 0x0000000180076460 | 0x00076460
`NgscbCheckHSTIPrerequisitesVerified` | 4 (0x4) | Exported Function | 0x0000000180076550 | 0x00076550
`NgscbCheckIsAOACDevice` | 5 (0x5) | Exported Function | 0x00000001800258c0 | 0x000258c0
`NgscbCheckIsHSTIVerified` | 6 (0x6) | Exported Function | 0x0000000180025760 | 0x00025760
`NgscbCheckPreventDeviceEncryption` | 7 (0x7) | Exported Function | 0x0000000180077700 | 0x00077700
`NgscbCheckPreventDeviceEncryptionForAad` | 8 (0x8) | Exported Function | 0x00000001800777c0 | 0x000777c0
`NgscbCheckDmaSecurity` | 2 (0x2) | Exported Function | 0x0000000180076450 | 0x00076450
`FveUpdateBandIdBcd` | 140 (0x8c) | Exported Function | 0x000000018001fed0 | 0x0001fed0
`FveUnlockVolumeWithAccessMode` | 139 (0x8b) | Exported Function | 0x0000000180045a30 | 0x00045a30
`FveUnlockVolumeAuthMethodSid` | 138 (0x8a) | Exported Function | 0x0000000180045940 | 0x00045940
`FveSetAllowKeyExport` | 123 (0x7b) | Exported Function | 0x000000018001f120 | 0x0001f120
`FveSetDescriptionW` | 124 (0x7c) | Exported Function | 0x00000001800450c0 | 0x000450c0
`FveSetFipsAllowDisabled` | 125 (0x7d) | Exported Function | 0x00000001800296e0 | 0x000296e0
`FveSetFveMethod` | 126 (0x7e) | Exported Function | 0x0000000180018a10 | 0x00018a10
`FveSetIdentificationFieldW` | 127 (0x7f) | Exported Function | 0x00000001800451c0 | 0x000451c0
`FveSetRecoveryPasswordBackupInformation` | 128 (0x80) | Exported Function | 0x0000000180042280 | 0x00042280
`FveSetUserFlags` | 129 (0x81) | Exported Function | 0x00000001800410e0 | 0x000410e0
`FveSysClearUserFlags` | 130 (0x82) | Exported Function | 0x000000018001f750 | 0x0001f750
`FveSysCloseVolume` | 131 (0x83) | Exported Function | 0x00000001800205a0 | 0x000205a0
`FveSysGetUserFlags` | 132 (0x84) | Exported Function | 0x000000018001f370 | 0x0001f370
`FveSysOpenVolumeW` | 133 (0x85) | Exported Function | 0x00000001800452d0 | 0x000452d0
`FveSysSetUserFlags` | 134 (0x86) | Exported Function | 0x000000018001f7f0 | 0x0001f7f0
`FveUnbindAllDataVolumeFromOSVolume` | 135 (0x87) | Exported Function | 0x0000000180045380 | 0x00045380
`FveUnbindDataVolume` | 136 (0x88) | Exported Function | 0x0000000180045860 | 0x00045860
`FveUnlockVolume` | 137 (0x89) | Exported Function | 0x0000000180020d40 | 0x00020d40
`FveSelectBestRecoveryPasswordByBackupInformation` | 121 (0x79) | Exported Function | 0x00000001800421a0 | 0x000421a0
`NgscbGetWinReConfiguration` | 9 (0x9) | Exported Function | 0x0000000180079070 | 0x00079070
`FveGetStatusW` | 84 (0x54) | Exported Function | 0x0000000180041ca0 | 0x00041ca0
`FveGetSecureBootBindingState` | 82 (0x52) | Exported Function | 0x0000000180029790 | 0x00029790
`FveCheckPassphrasePolicy` | 31 (0x1f) | Exported Function | 0x0000000180042e50 | 0x00042e50
`FveCheckTpmCapability` | 32 (0x20) | Exported Function | 0x0000000180042f30 | 0x00042f30
`FveClearUserFlags` | 33 (0x21) | Exported Function | 0x00000001800410e0 | 0x000410e0
`FveCloseHandle` | 34 (0x22) | Exported Function | 0x00000001800280e0 | 0x000280e0
`FveCloseVolume` | 35 (0x23) | Exported Function | 0x0000000180028060 | 0x00028060
`FveCommitChanges` | 36 (0x24) | Exported Function | 0x0000000180020930 | 0x00020930
`FveCheckADRecoveryInfoBackupPolicyEx` | 30 (0x1e) | Exported Function | 0x0000000180042d70 | 0x00042d70
`FveCommitChangesEx` | 37 (0x25) | Exported Function | 0x0000000180020940 | 0x00020940
`FveConversionDecryptEx` | 39 (0x27) | Exported Function | 0x0000000180041100 | 0x00041100
`FveConversionEncrypt` | 40 (0x28) | Exported Function | 0x0000000180043010 | 0x00043010
`FveConversionEncryptEx` | 41 (0x29) | Exported Function | 0x0000000180001c10 | 0x00001c10
`FveConversionEncryptPendingReboot` | 42 (0x2a) | Exported Function | 0x00000001800430a0 | 0x000430a0
`FveConversionEncryptPendingRebootEx` | 43 (0x2b) | Exported Function | 0x00000001800430b0 | 0x000430b0
`FveConversionPause` | 44 (0x2c) | Exported Function | 0x0000000180041200 | 0x00041200
`FveConversionDecrypt` | 38 (0x26) | Exported Function | 0x00000001800410f0 | 0x000410f0
`FveCheckADRecoveryInfoBackupPolicy` | 29 (0x1d) | Exported Function | 0x0000000180042c80 | 0x00042c80
`FveCanStandardUsersChangePin` | 28 (0x1c) | Exported Function | 0x0000000180025fc0 | 0x00025fc0
`FveCanStandardUsersChangePassphraseByProxy` | 27 (0x1b) | Exported Function | 0x0000000180026020 | 0x00026020
`FveAddAuthMethodSid` | 12 (0xc) | Exported Function | 0x00000001800426f0 | 0x000426f0
`FveApplyGroupPolicy` | 13 (0xd) | Exported Function | 0x0000000180006260 | 0x00006260
`FveApplyNkpCertChanges` | 14 (0xe) | Exported Function | 0x0000000180002180 | 0x00002180
`FveAttemptAutoUnlock` | 15 (0xf) | Exported Function | 0x0000000180042850 | 0x00042850
`FveAuthElementFromPassPhraseW` | 16 (0x10) | Exported Function | 0x0000000180040ca0 | 0x00040ca0
`FveAuthElementFromPinW` | 17 (0x11) | Exported Function | 0x0000000180040d60 | 0x00040d60
`FveAuthElementFromRecoveryPasswordW` | 18 (0x12) | Exported Function | 0x000000018000c370 | 0x0000c370
`FveAuthElementGetKeyFileNameW` | 19 (0x13) | Exported Function | 0x0000000180040e40 | 0x00040e40
`FveAuthElementReadExternalKeyW` | 20 (0x14) | Exported Function | 0x0000000180040f20 | 0x00040f20
`FveAuthElementToRecoveryPasswordW` | 21 (0x15) | Exported Function | 0x000000018000c2d0 | 0x0000c2d0
`FveAuthElementWriteExternalKeyW` | 22 (0x16) | Exported Function | 0x0000000180041010 | 0x00041010
`FveBackupRecoveryInformationToAD` | 23 (0x17) | Exported Function | 0x0000000180042940 | 0x00042940
`FveBackupRecoveryInformationToADEx` | 24 (0x18) | Exported Function | 0x0000000180042a40 | 0x00042a40
`FveBindDataVolume` | 25 (0x19) | Exported Function | 0x0000000180042b70 | 0x00042b70
`FveCanPinExceptionPolicyBeApplied` | 26 (0x1a) | Exported Function | 0x00000001800410d0 | 0x000410d0
`FveConversionResume` | 45 (0x2d) | Exported Function | 0x00000001800412f0 | 0x000412f0
`FveGetStatus` | 83 (0x53) | Exported Function | 0x00000001800232d0 | 0x000232d0
`FveConversionStop` | 46 (0x2e) | Exported Function | 0x00000001800413e0 | 0x000413e0
`FveDecrementClearKeyCounter` | 48 (0x30) | Exported Function | 0x0000000180043190 | 0x00043190
`FveGetAuthMethodSidInformation` | 68 (0x44) | Exported Function | 0x00000001800438f0 | 0x000438f0
`FveGetClearKeyCounter` | 69 (0x45) | Exported Function | 0x0000000180020600 | 0x00020600
`FveGetDataSet` | 70 (0x46) | Exported Function | 0x00000001800417d0 | 0x000417d0
`FveGetDescriptionW` | 71 (0x47) | Exported Function | 0x0000000180043aa0 | 0x00043aa0
`FveGetDeviceLockoutData` | 72 (0x48) | Exported Function | 0x0000000180043bb0 | 0x00043bb0
`FveGetExternalKeyBlob` | 73 (0x49) | Exported Function | 0x0000000180043ca0 | 0x00043ca0
`FveGetAuthMethodSid` | 67 (0x43) | Exported Function | 0x00000001800437f0 | 0x000437f0
`FveGetFipsAllowDisabled` | 74 (0x4a) | Exported Function | 0x00000001800418e0 | 0x000418e0
`FveGetFveMethodEDrv` | 76 (0x4c) | Exported Function | 0x0000000180041990 | 0x00041990
`FveGetFveMethodEx` | 77 (0x4d) | Exported Function | 0x000000018000f350 | 0x0000f350
`FveGetIdentificationFieldW` | 78 (0x4e) | Exported Function | 0x000000018000d010 | 0x0000d010
`FveGetIdentity` | 79 (0x4f) | Exported Function | 0x000000018000b2f0 | 0x0000b2f0
`FveGetKeyPackage` | 80 (0x50) | Exported Function | 0x0000000180041a90 | 0x00041a90
`FveGetRecoveryPasswordBackupInformation` | 81 (0x51) | Exported Function | 0x0000000180041bb0 | 0x00041bb0
`FveGetFveMethod` | 75 (0x4b) | Exported Function | 0x000000018000f2a0 | 0x0000f2a0
`FveGetAuthMethodInformation` | 66 (0x42) | Exported Function | 0x000000018001f1d0 | 0x0001f1d0
`FveGetAuthMethodGuids` | 65 (0x41) | Exported Function | 0x000000018001f2a0 | 0x0001f2a0
`FveGetAllowKeyExport` | 64 (0x40) | Exported Function | 0x000000018001eff0 | 0x0001eff0
`FveDeleteAuthMethod` | 49 (0x31) | Exported Function | 0x0000000180043260 | 0x00043260
`FveDeleteDeviceEncryptionOptOutForVolumeW` | 50 (0x32) | Exported Function | 0x0000000180043370 | 0x00043370
`FveDisableDeviceLockoutState` | 51 (0x33) | Exported Function | 0x00000001800434c0 | 0x000434c0
`FveDiscardChanges` | 52 (0x34) | Exported Function | 0x00000001800414f0 | 0x000414f0
`FveDraCertPresentInRegistry` | 53 (0x35) | Exported Function | 0x00000001800435a0 | 0x000435a0
`FveEnableRawAccess` | 54 (0x36) | Exported Function | 0x00000001800415d0 | 0x000415d0
`FveEnableRawAccessEx` | 55 (0x37) | Exported Function | 0x00000001800415e0 | 0x000415e0
`FveEnableRawAccessW` | 56 (0x38) | Exported Function | 0x00000001800416d0 | 0x000416d0
`FveEraseDrive` | 57 (0x39) | Exported Function | 0x000000018000aec0 | 0x0000aec0
`FveEscrowEncryptedRecoveryKeyForRetailUnlock` | 58 (0x3a) | Exported Function | 0x0000000180043650 | 0x00043650
`FveFindFirstVolume` | 59 (0x3b) | Exported Function | 0x000000018001cd20 | 0x0001cd20
`FveFindNextVolume` | 60 (0x3c) | Exported Function | 0x000000018001d340 | 0x0001d340
`FveFlagsToProtectorType` | 61 (0x3d) | Exported Function | 0x000000018000a7f0 | 0x0000a7f0
`FveGenerateNbp` | 62 (0x3e) | Exported Function | 0x0000000180043700 | 0x00043700
`FveGenerateNkpSessionKeys` | 63 (0x3f) | Exported Function | 0x0000000180002440 | 0x00002440
`FveConversionStopEx` | 47 (0x2f) | Exported Function | 0x00000001800413f0 | 0x000413f0
`NgscbIsHostOsOnRoamableDrive` | 10 (0xa) | Exported Function | 0x00000001800259b0 | 0x000259b0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FVEAPI.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7f4556840dffc92a2fd38edf0033b2f51b09cd894871281d025c6a2c05ba66b9/detection/





MIT License. Copyright (c) 2020 Strontic.


