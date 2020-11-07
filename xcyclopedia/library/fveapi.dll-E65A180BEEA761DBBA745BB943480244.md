---
title: fveapi.dll | Windows BitLocker Drive Encryption API
excerpt: What is fveapi.dll?
---

# fveapi.dll 

* File Path: `C:\Windows\SysWOW64\fveapi.dll`
* Description: Windows BitLocker Drive Encryption API

## Hashes

Type | Hash
-- | --
MD5 | `E65A180BEEA761DBBA745BB943480244`
SHA1 | `F5A40C71C0CE343AB0116DB3286582FFBF718924`
SHA256 | `39F26FF9BF04D9F4B56FDE0CE1A9294B6925571CF38E37BE5A6490F258C2D68F`
SHA384 | `650756AB8E49F04E2154507AE9C2AE33FC5DFF5D94503B9DEF8B9969B4778DBE363298DF4661C04776CF42346BC63B78`
SHA512 | `D126900DB2131CD8B5853C05B7799BF50135CA280B3D7E97E57E74DCCC4B0FCBEA471E9A7360338818C56F435C193C03B7DFEB81BE8E23D0010C4B0CEDA4F2FF`
SSDEEP | `12288:JzmcqWXJSFXY6t9UkAmyeUZx6TWNKERJ2m7K41wOAK8ATpJ:8cqWUFIO9lAPeUL6TSxsmG41wVKHp`
IMP | `EBDCE18B7027F4A8F4E3AED748C1B2C1`
PESHA1 | `119C59C663D865381750111FBB70F9A3E5BC63A0`
PE256 | `DB648140AADBEB57A0789E1FFF01B580F6FBFC2D73A17BF2F2DDEA254ECDC4FF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`FveAddAuthMethodInformation` | 11 | Exported Function
`FveLockDevice` | 105 | Exported Function
`FveLockVolume` | 106 | Exported Function
`FveLogRecoveryReason` | 107 | Exported Function
`FveNeedsDiscoveryVolumeUpdate` | 108 | Exported Function
`FveNotifyVolumeAfterFormat` | 109 | Exported Function
`FveOpenVolumeByHandle` | 110 | Exported Function
`FveKeyManagement` | 104 | Exported Function
`FveOpenVolumeExW` | 111 | Exported Function
`FveProtectorTypeToFlags` | 113 | Exported Function
`FveQuery` | 114 | Exported Function
`FveQueryDeviceEncryptionSupport` | 115 | Exported Function
`FveRecalculateOffsetsAndMoveMetadata` | 116 | Exported Function
`FveRegenerateNbpSessionKey` | 117 | Exported Function
`FveResetTpmDictionaryAttackParameters` | 118 | Exported Function
`FveOpenVolumeW` | 112 | Exported Function
`FveIsVolumeEncryptable` | 103 | Exported Function
`FveIsSchemaExtInstalled` | 102 | Exported Function
`FveIsRecoveryPasswordValidW` | 101 | Exported Function
`FveGetVolumeNameW` | 86 | Exported Function
`FveInitializeDeviceEncryption` | 90 | Exported Function
`FveInitializeDeviceEncryption2` | 89 | Exported Function
`FveInitVolume` | 87 | Exported Function
`FveInitVolumeEx` | 88 | Exported Function
`FveIsAnyDataVolumeBoundToOSVolume` | 91 | Exported Function
`FveIsBoundDataVolume` | 92 | Exported Function
`FveIsBoundDataVolumeToOSVolume` | 93 | Exported Function
`FveIsDeviceLockable` | 94 | Exported Function
`FveIsDeviceLockedOut` | 95 | Exported Function
`FveIsHardwareReadyForConversion` | 96 | Exported Function
`FveIsHybridVolume` | 97 | Exported Function
`FveIsHybridVolumeW` | 98 | Exported Function
`FveIsPassphraseCompatibleW` | 99 | Exported Function
`FveIsRecoveryPasswordGroupValidW` | 100 | Exported Function
`FveRevertVolume` | 119 | Exported Function
`FveGetUserFlags` | 85 | Exported Function
`FveSaveRecoveryPasswordBackupFlag` | 120 | Exported Function
`FveServiceDiscoveryVolume` | 122 | Exported Function
`FveUpdateDeviceLockoutStateEx` | 142 | Exported Function
`FveUpdatePinW` | 143 | Exported Function
`FveUpgradeVolume` | 144 | Exported Function
`FveValidateDeviceLockoutState` | 145 | Exported Function
`FveValidateExistingPassphraseW` | 146 | Exported Function
`FveValidateExistingPinW` | 147 | Exported Function
`FveUpdateDeviceLockoutState` | 141 | Exported Function
`InternalFveIsVolumeEncrypted` | 1 | Exported Function
`NgscbCheckDmaSecurityEx` | 3 | Exported Function
`NgscbCheckHSTIPrerequisitesVerified` | 4 | Exported Function
`NgscbCheckIsAOACDevice` | 5 | Exported Function
`NgscbCheckIsHSTIVerified` | 6 | Exported Function
`NgscbCheckPreventDeviceEncryption` | 7 | Exported Function
`NgscbCheckPreventDeviceEncryptionForAad` | 8 | Exported Function
`NgscbCheckDmaSecurity` | 2 | Exported Function
`FveUpdateBandIdBcd` | 140 | Exported Function
`FveUnlockVolumeWithAccessMode` | 139 | Exported Function
`FveUnlockVolumeAuthMethodSid` | 138 | Exported Function
`FveSetAllowKeyExport` | 123 | Exported Function
`FveSetDescriptionW` | 124 | Exported Function
`FveSetFipsAllowDisabled` | 125 | Exported Function
`FveSetFveMethod` | 126 | Exported Function
`FveSetIdentificationFieldW` | 127 | Exported Function
`FveSetRecoveryPasswordBackupInformation` | 128 | Exported Function
`FveSetUserFlags` | 129 | Exported Function
`FveSysClearUserFlags` | 130 | Exported Function
`FveSysCloseVolume` | 131 | Exported Function
`FveSysGetUserFlags` | 132 | Exported Function
`FveSysOpenVolumeW` | 133 | Exported Function
`FveSysSetUserFlags` | 134 | Exported Function
`FveUnbindAllDataVolumeFromOSVolume` | 135 | Exported Function
`FveUnbindDataVolume` | 136 | Exported Function
`FveUnlockVolume` | 137 | Exported Function
`FveSelectBestRecoveryPasswordByBackupInformation` | 121 | Exported Function
`NgscbGetWinReConfiguration` | 9 | Exported Function
`FveGetStatusW` | 84 | Exported Function
`FveGetSecureBootBindingState` | 82 | Exported Function
`FveCheckPassphrasePolicy` | 31 | Exported Function
`FveCheckTpmCapability` | 32 | Exported Function
`FveClearUserFlags` | 33 | Exported Function
`FveCloseHandle` | 34 | Exported Function
`FveCloseVolume` | 35 | Exported Function
`FveCommitChanges` | 36 | Exported Function
`FveCheckADRecoveryInfoBackupPolicyEx` | 30 | Exported Function
`FveCommitChangesEx` | 37 | Exported Function
`FveConversionDecryptEx` | 39 | Exported Function
`FveConversionEncrypt` | 40 | Exported Function
`FveConversionEncryptEx` | 41 | Exported Function
`FveConversionEncryptPendingReboot` | 42 | Exported Function
`FveConversionEncryptPendingRebootEx` | 43 | Exported Function
`FveConversionPause` | 44 | Exported Function
`FveConversionDecrypt` | 38 | Exported Function
`FveCheckADRecoveryInfoBackupPolicy` | 29 | Exported Function
`FveCanStandardUsersChangePin` | 28 | Exported Function
`FveCanStandardUsersChangePassphraseByProxy` | 27 | Exported Function
`FveAddAuthMethodSid` | 12 | Exported Function
`FveApplyGroupPolicy` | 13 | Exported Function
`FveApplyNkpCertChanges` | 14 | Exported Function
`FveAttemptAutoUnlock` | 15 | Exported Function
`FveAuthElementFromPassPhraseW` | 16 | Exported Function
`FveAuthElementFromPinW` | 17 | Exported Function
`FveAuthElementFromRecoveryPasswordW` | 18 | Exported Function
`FveAuthElementGetKeyFileNameW` | 19 | Exported Function
`FveAuthElementReadExternalKeyW` | 20 | Exported Function
`FveAuthElementToRecoveryPasswordW` | 21 | Exported Function
`FveAuthElementWriteExternalKeyW` | 22 | Exported Function
`FveBackupRecoveryInformationToAD` | 23 | Exported Function
`FveBackupRecoveryInformationToADEx` | 24 | Exported Function
`FveBindDataVolume` | 25 | Exported Function
`FveCanPinExceptionPolicyBeApplied` | 26 | Exported Function
`FveConversionResume` | 45 | Exported Function
`FveGetStatus` | 83 | Exported Function
`FveConversionStop` | 46 | Exported Function
`FveDecrementClearKeyCounter` | 48 | Exported Function
`FveGetAuthMethodSidInformation` | 68 | Exported Function
`FveGetClearKeyCounter` | 69 | Exported Function
`FveGetDataSet` | 70 | Exported Function
`FveGetDescriptionW` | 71 | Exported Function
`FveGetDeviceLockoutData` | 72 | Exported Function
`FveGetExternalKeyBlob` | 73 | Exported Function
`FveGetAuthMethodSid` | 67 | Exported Function
`FveGetFipsAllowDisabled` | 74 | Exported Function
`FveGetFveMethodEDrv` | 76 | Exported Function
`FveGetFveMethodEx` | 77 | Exported Function
`FveGetIdentificationFieldW` | 78 | Exported Function
`FveGetIdentity` | 79 | Exported Function
`FveGetKeyPackage` | 80 | Exported Function
`FveGetRecoveryPasswordBackupInformation` | 81 | Exported Function
`FveGetFveMethod` | 75 | Exported Function
`FveGetAuthMethodInformation` | 66 | Exported Function
`FveGetAuthMethodGuids` | 65 | Exported Function
`FveGetAllowKeyExport` | 64 | Exported Function
`FveDeleteAuthMethod` | 49 | Exported Function
`FveDeleteDeviceEncryptionOptOutForVolumeW` | 50 | Exported Function
`FveDisableDeviceLockoutState` | 51 | Exported Function
`FveDiscardChanges` | 52 | Exported Function
`FveDraCertPresentInRegistry` | 53 | Exported Function
`FveEnableRawAccess` | 54 | Exported Function
`FveEnableRawAccessEx` | 55 | Exported Function
`FveEnableRawAccessW` | 56 | Exported Function
`FveEraseDrive` | 57 | Exported Function
`FveEscrowEncryptedRecoveryKeyForRetailUnlock` | 58 | Exported Function
`FveFindFirstVolume` | 59 | Exported Function
`FveFindNextVolume` | 60 | Exported Function
`FveFlagsToProtectorType` | 61 | Exported Function
`FveGenerateNbp` | 62 | Exported Function
`FveGenerateNkpSessionKeys` | 63 | Exported Function
`FveConversionStopEx` | 47 | Exported Function
`NgscbIsHostOsOnRoamableDrive` | 10 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FVEAPI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/39f26ff9bf04d9f4b56fde0ce1a9294b6925571cf38e37be5a6490f258c2d68f/detection/





MIT License. Copyright (c) 2020 Strontic.


