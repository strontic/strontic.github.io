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

Function Name | Ordinal | Type
-- | -- | --
`FveNotifyVolumeAfterFormat` | 109 | Exported Function
`FveNeedsDiscoveryVolumeUpdate` | 108 | Exported Function
`FveOpenVolumeExW` | 111 | Exported Function
`FveOpenVolumeByHandle` | 110 | Exported Function
`FveLogRecoveryReason` | 107 | Exported Function
`FveKeyManagement` | 104 | Exported Function
`FveIsVolumeEncryptable` | 103 | Exported Function
`FveLockVolume` | 106 | Exported Function
`FveLockDevice` | 105 | Exported Function
`FveResetTpmDictionaryAttackParameters` | 118 | Exported Function
`FveRegenerateNbpSessionKey` | 117 | Exported Function
`FveSaveRecoveryPasswordBackupFlag` | 120 | Exported Function
`FveRevertVolume` | 119 | Exported Function
`FveRecalculateOffsetsAndMoveMetadata` | 116 | Exported Function
`FveProtectorTypeToFlags` | 113 | Exported Function
`FveOpenVolumeW` | 112 | Exported Function
`FveQueryDeviceEncryptionSupport` | 115 | Exported Function
`FveQuery` | 114 | Exported Function
`FveIsAnyDataVolumeBoundToOSVolume` | 91 | Exported Function
`FveInitVolumeEx` | 88 | Exported Function
`FveIsBoundDataVolumeToOSVolume` | 93 | Exported Function
`FveIsBoundDataVolume` | 92 | Exported Function
`FveInitVolume` | 87 | Exported Function
`FveGetVolumeNameW` | 86 | Exported Function
`FveGetUserFlags` | 85 | Exported Function
`FveInitializeDeviceEncryption2` | 90 | Exported Function
`FveInitializeDeviceEncryption` | 89 | Exported Function
`FveIsRecoveryPasswordGroupValidW` | 100 | Exported Function
`FveIsPassphraseCompatibleW` | 99 | Exported Function
`FveIsSchemaExtInstalled` | 102 | Exported Function
`FveIsRecoveryPasswordValidW` | 101 | Exported Function
`FveIsHybridVolumeW` | 98 | Exported Function
`FveIsDeviceLockedOut` | 95 | Exported Function
`FveIsDeviceLockable` | 94 | Exported Function
`FveIsHybridVolume` | 97 | Exported Function
`FveIsHardwareReadyForConversion` | 96 | Exported Function
`FveSelectBestRecoveryPasswordByBackupInformation` | 121 | Exported Function
`FveValidateExistingPassphraseW` | 146 | Exported Function
`FveValidateDeviceLockoutState` | 145 | Exported Function
`InternalFveIsVolumeEncrypted` | 1 | Exported Function
`FveValidateExistingPinW` | 147 | Exported Function
`FveUpgradeVolume` | 144 | Exported Function
`FveUpdateDeviceLockoutState` | 141 | Exported Function
`FveUpdateBandIdBcd` | 140 | Exported Function
`FveUpdatePinW` | 143 | Exported Function
`FveUpdateDeviceLockoutStateEx` | 142 | Exported Function
`NgscbCheckPreventDeviceEncryptionForAad` | 8 | Exported Function
`NgscbCheckPreventDeviceEncryption` | 7 | Exported Function
`NgscbIsHostOsOnRoamableDrive` | 10 | Exported Function
`NgscbGetWinReConfiguration` | 9 | Exported Function
`NgscbCheckIsHSTIVerified` | 6 | Exported Function
`NgscbCheckDmaSecurityEx` | 3 | Exported Function
`NgscbCheckDmaSecurity` | 2 | Exported Function
`NgscbCheckIsAOACDevice` | 5 | Exported Function
`NgscbCheckHSTIPrerequisitesVerified` | 4 | Exported Function
`FveSetRecoveryPasswordBackupInformation` | 128 | Exported Function
`FveSetIdentificationFieldW` | 127 | Exported Function
`FveSysClearUserFlags` | 130 | Exported Function
`FveSetUserFlags` | 129 | Exported Function
`FveSetFveMethod` | 126 | Exported Function
`FveSetAllowKeyExport` | 123 | Exported Function
`FveServiceDiscoveryVolume` | 122 | Exported Function
`FveSetFipsAllowDisabled` | 125 | Exported Function
`FveSetDescriptionW` | 124 | Exported Function
`FveUnlockVolume` | 137 | Exported Function
`FveUnbindDataVolume` | 136 | Exported Function
`FveUnlockVolumeWithAccessMode` | 139 | Exported Function
`FveUnlockVolumeAuthMethodSid` | 138 | Exported Function
`FveUnbindAllDataVolumeFromOSVolume` | 135 | Exported Function
`FveSysGetUserFlags` | 132 | Exported Function
`FveSysCloseVolume` | 131 | Exported Function
`FveSysSetUserFlags` | 134 | Exported Function
`FveSysOpenVolumeW` | 133 | Exported Function
`FveGetStatusW` | 84 | Exported Function
`FveCloseVolume` | 35 | Exported Function
`FveCloseHandle` | 34 | Exported Function
`FveCommitChangesEx` | 37 | Exported Function
`FveCommitChanges` | 36 | Exported Function
`FveClearUserFlags` | 33 | Exported Function
`FveCheckADRecoveryInfoBackupPolicyEx` | 30 | Exported Function
`FveCheckADRecoveryInfoBackupPolicy` | 29 | Exported Function
`FveCheckTpmCapability` | 32 | Exported Function
`FveCheckPassphrasePolicy` | 31 | Exported Function
`FveConversionPause` | 44 | Exported Function
`FveConversionEncryptPendingRebootEx` | 43 | Exported Function
`FveConversionStop` | 46 | Exported Function
`FveConversionResume` | 45 | Exported Function
`FveConversionEncryptPendingReboot` | 42 | Exported Function
`FveConversionDecryptEx` | 39 | Exported Function
`FveConversionDecrypt` | 38 | Exported Function
`FveConversionEncryptEx` | 41 | Exported Function
`FveConversionEncrypt` | 40 | Exported Function
`FveAuthElementFromPinW` | 17 | Exported Function
`FveAuthElementFromPassPhraseW` | 16 | Exported Function
`FveAuthElementGetKeyFileNameW` | 19 | Exported Function
`FveAuthElementFromRecoveryPasswordW` | 18 | Exported Function
`FveAttemptAutoUnlock` | 15 | Exported Function
`FveAddAuthMethodSid` | 12 | Exported Function
`FveAddAuthMethodInformation` | 11 | Exported Function
`FveApplyNkpCertChanges` | 14 | Exported Function
`FveApplyGroupPolicy` | 13 | Exported Function
`FveCanPinExceptionPolicyBeApplied` | 26 | Exported Function
`FveBindDataVolume` | 25 | Exported Function
`FveCanStandardUsersChangePin` | 28 | Exported Function
`FveCanStandardUsersChangePassphraseByProxy` | 27 | Exported Function
`FveBackupRecoveryInformationToADEx` | 24 | Exported Function
`FveAuthElementToRecoveryPasswordW` | 21 | Exported Function
`FveAuthElementReadExternalKeyW` | 20 | Exported Function
`FveBackupRecoveryInformationToAD` | 23 | Exported Function
`FveAuthElementWriteExternalKeyW` | 22 | Exported Function
`FveConversionStopEx` | 47 | Exported Function
`FveGetDeviceLockoutData` | 72 | Exported Function
`FveGetDescriptionW` | 71 | Exported Function
`FveGetFipsAllowDisabled` | 74 | Exported Function
`FveGetExternalKeyBlob` | 73 | Exported Function
`FveGetDataSet` | 70 | Exported Function
`FveGetAuthMethodSid` | 67 | Exported Function
`FveGetAuthMethodInformation` | 66 | Exported Function
`FveGetClearKeyCounter` | 69 | Exported Function
`FveGetAuthMethodSidInformation` | 68 | Exported Function
`FveGetRecoveryPasswordBackupInformation` | 81 | Exported Function
`FveGetKeyPackage` | 80 | Exported Function
`FveGetStatus` | 83 | Exported Function
`FveGetSecureBootBindingState` | 82 | Exported Function
`FveGetIdentity` | 79 | Exported Function
`FveGetFveMethodEDrv` | 76 | Exported Function
`FveGetFveMethod` | 75 | Exported Function
`FveGetIdentificationFieldW` | 78 | Exported Function
`FveGetFveMethodEx` | 77 | Exported Function
`FveEnableRawAccess` | 54 | Exported Function
`FveDraCertPresentInRegistry` | 53 | Exported Function
`FveEnableRawAccessW` | 56 | Exported Function
`FveEnableRawAccessEx` | 55 | Exported Function
`FveDiscardChanges` | 52 | Exported Function
`FveDeleteAuthMethod` | 49 | Exported Function
`FveDecrementClearKeyCounter` | 48 | Exported Function
`FveDisableDeviceLockoutState` | 51 | Exported Function
`FveDeleteDeviceEncryptionOptOutForVolumeW` | 50 | Exported Function
`FveGenerateNkpSessionKeys` | 63 | Exported Function
`FveGenerateNbp` | 62 | Exported Function
`FveGetAuthMethodGuids` | 65 | Exported Function
`FveGetAllowKeyExport` | 64 | Exported Function
`FveFlagsToProtectorType` | 61 | Exported Function
`FveEscrowEncryptedRecoveryKeyForRetailUnlock` | 58 | Exported Function
`FveEraseDrive` | 57 | Exported Function
`FveFindNextVolume` | 60 | Exported Function
`FveFindFirstVolume` | 59 | Exported Function


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


