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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FveAddAuthMethodInformation` | 11 (0xb) | Exported Function | 0x1002f510 | 0x0002f510
`FveLockDevice` | 105 (0x69) | Exported Function | 0x10054200 | 0x00054200
`FveLockVolume` | 106 (0x6a) | Exported Function | 0x10029fe0 | 0x00029fe0
`FveLogRecoveryReason` | 107 (0x6b) | Exported Function | 0x100542c0 | 0x000542c0
`FveNeedsDiscoveryVolumeUpdate` | 108 (0x6c) | Exported Function | 0x10054390 | 0x00054390
`FveNotifyVolumeAfterFormat` | 109 (0x6d) | Exported Function | 0x10029330 | 0x00029330
`FveOpenVolumeByHandle` | 110 (0x6e) | Exported Function | 0x1001e020 | 0x0001e020
`FveKeyManagement` | 104 (0x68) | Exported Function | 0x100540e0 | 0x000540e0
`FveOpenVolumeExW` | 111 (0x6f) | Exported Function | 0x10031290 | 0x00031290
`FveProtectorTypeToFlags` | 113 (0x71) | Exported Function | 0x1002e860 | 0x0002e860
`FveQuery` | 114 (0x72) | Exported Function | 0x10054470 | 0x00054470
`FveQueryDeviceEncryptionSupport` | 115 (0x73) | Exported Function | 0x10033d60 | 0x00033d60
`FveRecalculateOffsetsAndMoveMetadata` | 116 (0x74) | Exported Function | 0x100544f0 | 0x000544f0
`FveRegenerateNbpSessionKey` | 117 (0x75) | Exported Function | 0x10025bf0 | 0x00025bf0
`FveResetTpmDictionaryAttackParameters` | 118 (0x76) | Exported Function | 0x100545d0 | 0x000545d0
`FveOpenVolumeW` | 112 (0x70) | Exported Function | 0x10031260 | 0x00031260
`FveIsVolumeEncryptable` | 103 (0x67) | Exported Function | 0x10030d90 | 0x00030d90
`FveIsSchemaExtInstalled` | 102 (0x66) | Exported Function | 0x10054020 | 0x00054020
`FveIsRecoveryPasswordValidW` | 101 (0x65) | Exported Function | 0x10029b30 | 0x00029b30
`FveGetVolumeNameW` | 86 (0x56) | Exported Function | 0x1001de50 | 0x0001de50
`FveInitializeDeviceEncryption` | 90 (0x5a) | Exported Function | 0x100538d0 | 0x000538d0
`FveInitializeDeviceEncryption2` | 89 (0x59) | Exported Function | 0x10053760 | 0x00053760
`FveInitVolume` | 87 (0x57) | Exported Function | 0x100536f0 | 0x000536f0
`FveInitVolumeEx` | 88 (0x58) | Exported Function | 0x1002d5c0 | 0x0002d5c0
`FveIsAnyDataVolumeBoundToOSVolume` | 91 (0x5b) | Exported Function | 0x10053ae0 | 0x00053ae0
`FveIsBoundDataVolume` | 92 (0x5c) | Exported Function | 0x1001ffb0 | 0x0001ffb0
`FveIsBoundDataVolumeToOSVolume` | 93 (0x5d) | Exported Function | 0x10053bb0 | 0x00053bb0
`FveIsDeviceLockable` | 94 (0x5e) | Exported Function | 0x10053ca0 | 0x00053ca0
`FveIsDeviceLockedOut` | 95 (0x5f) | Exported Function | 0x10053d90 | 0x00053d90
`FveIsHardwareReadyForConversion` | 96 (0x60) | Exported Function | 0x10051c30 | 0x00051c30
`FveIsHybridVolume` | 97 (0x61) | Exported Function | 0x10053e50 | 0x00053e50
`FveIsHybridVolumeW` | 98 (0x62) | Exported Function | 0x10053f30 | 0x00053f30
`FveIsPassphraseCompatibleW` | 99 (0x63) | Exported Function | 0x10051cc0 | 0x00051cc0
`FveIsRecoveryPasswordGroupValidW` | 100 (0x64) | Exported Function | 0x10051d80 | 0x00051d80
`FveRevertVolume` | 119 (0x77) | Exported Function | 0x10051e40 | 0x00051e40
`FveGetUserFlags` | 85 (0x55) | Exported Function | 0x100510c0 | 0x000510c0
`FveSaveRecoveryPasswordBackupFlag` | 120 (0x78) | Exported Function | 0x10051f00 | 0x00051f00
`FveServiceDiscoveryVolume` | 122 (0x7a) | Exported Function | 0x10054700 | 0x00054700
`FveUpdateDeviceLockoutStateEx` | 142 (0x8e) | Exported Function | 0x100550e0 | 0x000550e0
`FveUpdatePinW` | 143 (0x8f) | Exported Function | 0x100551c0 | 0x000551c0
`FveUpgradeVolume` | 144 (0x90) | Exported Function | 0x10052150 | 0x00052150
`FveValidateDeviceLockoutState` | 145 (0x91) | Exported Function | 0x100552b0 | 0x000552b0
`FveValidateExistingPassphraseW` | 146 (0x92) | Exported Function | 0x10055370 | 0x00055370
`FveValidateExistingPinW` | 147 (0x93) | Exported Function | 0x10055450 | 0x00055450
`FveUpdateDeviceLockoutState` | 141 (0x8d) | Exported Function | 0x10055060 | 0x00055060
`InternalFveIsVolumeEncrypted` | 1 (0x1) | Exported Function | 0x10050bd0 | 0x00050bd0
`NgscbCheckDmaSecurityEx` | 3 (0x3) | Exported Function | 0x1007a7a0 | 0x0007a7a0
`NgscbCheckHSTIPrerequisitesVerified` | 4 (0x4) | Exported Function | 0x1007a850 | 0x0007a850
`NgscbCheckIsAOACDevice` | 5 (0x5) | Exported Function | 0x10034290 | 0x00034290
`NgscbCheckIsHSTIVerified` | 6 (0x6) | Exported Function | 0x100341a0 | 0x000341a0
`NgscbCheckPreventDeviceEncryption` | 7 (0x7) | Exported Function | 0x1007b870 | 0x0007b870
`NgscbCheckPreventDeviceEncryptionForAad` | 8 (0x8) | Exported Function | 0x1007b900 | 0x0007b900
`NgscbCheckDmaSecurity` | 2 (0x2) | Exported Function | 0x1007a780 | 0x0007a780
`FveUpdateBandIdBcd` | 140 (0x8c) | Exported Function | 0x1002ea70 | 0x0002ea70
`FveUnlockVolumeWithAccessMode` | 139 (0x8b) | Exported Function | 0x10054f60 | 0x00054f60
`FveUnlockVolumeAuthMethodSid` | 138 (0x8a) | Exported Function | 0x10054e90 | 0x00054e90
`FveSetAllowKeyExport` | 123 (0x7b) | Exported Function | 0x1002e2e0 | 0x0002e2e0
`FveSetDescriptionW` | 124 (0x7c) | Exported Function | 0x100547c0 | 0x000547c0
`FveSetFipsAllowDisabled` | 125 (0x7d) | Exported Function | 0x100357f0 | 0x000357f0
`FveSetFveMethod` | 126 (0x7e) | Exported Function | 0x1002eeb0 | 0x0002eeb0
`FveSetIdentificationFieldW` | 127 (0x7f) | Exported Function | 0x100548a0 | 0x000548a0
`FveSetRecoveryPasswordBackupInformation` | 128 (0x80) | Exported Function | 0x10052080 | 0x00052080
`FveSetUserFlags` | 129 (0x81) | Exported Function | 0x100510c0 | 0x000510c0
`FveSysClearUserFlags` | 130 (0x82) | Exported Function | 0x1002e690 | 0x0002e690
`FveSysCloseVolume` | 131 (0x83) | Exported Function | 0x1002ec20 | 0x0002ec20
`FveSysGetUserFlags` | 132 (0x84) | Exported Function | 0x1002e430 | 0x0002e430
`FveSysOpenVolumeW` | 133 (0x85) | Exported Function | 0x10054990 | 0x00054990
`FveSysSetUserFlags` | 134 (0x86) | Exported Function | 0x1002e730 | 0x0002e730
`FveUnbindAllDataVolumeFromOSVolume` | 135 (0x87) | Exported Function | 0x10054a10 | 0x00054a10
`FveUnbindDataVolume` | 136 (0x88) | Exported Function | 0x10054dc0 | 0x00054dc0
`FveUnlockVolume` | 137 (0x89) | Exported Function | 0x1002e220 | 0x0002e220
`FveSelectBestRecoveryPasswordByBackupInformation` | 121 (0x79) | Exported Function | 0x10051fc0 | 0x00051fc0
`NgscbGetWinReConfiguration` | 9 (0x9) | Exported Function | 0x1007cea0 | 0x0007cea0
`FveGetStatusW` | 84 (0x54) | Exported Function | 0x10051b30 | 0x00051b30
`FveGetSecureBootBindingState` | 82 (0x52) | Exported Function | 0x10035810 | 0x00035810
`FveCheckPassphrasePolicy` | 31 (0x1f) | Exported Function | 0x100529c0 | 0x000529c0
`FveCheckTpmCapability` | 32 (0x20) | Exported Function | 0x10052a80 | 0x00052a80
`FveClearUserFlags` | 33 (0x21) | Exported Function | 0x100510c0 | 0x000510c0
`FveCloseHandle` | 34 (0x22) | Exported Function | 0x100315d0 | 0x000315d0
`FveCloseVolume` | 35 (0x23) | Exported Function | 0x10031560 | 0x00031560
`FveCommitChanges` | 36 (0x24) | Exported Function | 0x1002f4f0 | 0x0002f4f0
`FveCheckADRecoveryInfoBackupPolicyEx` | 30 (0x1e) | Exported Function | 0x10052900 | 0x00052900
`FveCommitChangesEx` | 37 (0x25) | Exported Function | 0x10037c40 | 0x00037c40
`FveConversionDecryptEx` | 39 (0x27) | Exported Function | 0x100510f0 | 0x000510f0
`FveConversionEncrypt` | 40 (0x28) | Exported Function | 0x10052b60 | 0x00052b60
`FveConversionEncryptEx` | 41 (0x29) | Exported Function | 0x1002e180 | 0x0002e180
`FveConversionEncryptPendingReboot` | 42 (0x2a) | Exported Function | 0x10052bd0 | 0x00052bd0
`FveConversionEncryptPendingRebootEx` | 43 (0x2b) | Exported Function | 0x10052bf0 | 0x00052bf0
`FveConversionPause` | 44 (0x2c) | Exported Function | 0x100511d0 | 0x000511d0
`FveConversionDecrypt` | 38 (0x26) | Exported Function | 0x100510d0 | 0x000510d0
`FveCheckADRecoveryInfoBackupPolicy` | 29 (0x1d) | Exported Function | 0x10052830 | 0x00052830
`FveCanStandardUsersChangePin` | 28 (0x1c) | Exported Function | 0x1002fce0 | 0x0002fce0
`FveCanStandardUsersChangePassphraseByProxy` | 27 (0x1b) | Exported Function | 0x1002fd60 | 0x0002fd60
`FveAddAuthMethodSid` | 12 (0xc) | Exported Function | 0x10052370 | 0x00052370
`FveApplyGroupPolicy` | 13 (0xd) | Exported Function | 0x1002c810 | 0x0002c810
`FveApplyNkpCertChanges` | 14 (0xe) | Exported Function | 0x1002d8f0 | 0x0002d8f0
`FveAttemptAutoUnlock` | 15 (0xf) | Exported Function | 0x10052480 | 0x00052480
`FveAuthElementFromPassPhraseW` | 16 (0x10) | Exported Function | 0x10050cc0 | 0x00050cc0
`FveAuthElementFromPinW` | 17 (0x11) | Exported Function | 0x10050d80 | 0x00050d80
`FveAuthElementFromRecoveryPasswordW` | 18 (0x12) | Exported Function | 0x100283b0 | 0x000283b0
`FveAuthElementGetKeyFileNameW` | 19 (0x13) | Exported Function | 0x10050e50 | 0x00050e50
`FveAuthElementReadExternalKeyW` | 20 (0x14) | Exported Function | 0x10050f10 | 0x00050f10
`FveAuthElementToRecoveryPasswordW` | 21 (0x15) | Exported Function | 0x10028440 | 0x00028440
`FveAuthElementWriteExternalKeyW` | 22 (0x16) | Exported Function | 0x10050fe0 | 0x00050fe0
`FveBackupRecoveryInformationToAD` | 23 (0x17) | Exported Function | 0x10052560 | 0x00052560
`FveBackupRecoveryInformationToADEx` | 24 (0x18) | Exported Function | 0x10052630 | 0x00052630
`FveBindDataVolume` | 25 (0x19) | Exported Function | 0x10052730 | 0x00052730
`FveCanPinExceptionPolicyBeApplied` | 26 (0x1a) | Exported Function | 0x100510a0 | 0x000510a0
`FveConversionResume` | 45 (0x2d) | Exported Function | 0x100512b0 | 0x000512b0
`FveGetStatus` | 83 (0x53) | Exported Function | 0x10031690 | 0x00031690
`FveConversionStop` | 46 (0x2e) | Exported Function | 0x10051390 | 0x00051390
`FveDecrementClearKeyCounter` | 48 (0x30) | Exported Function | 0x10052cb0 | 0x00052cb0
`FveGetAuthMethodSidInformation` | 68 (0x44) | Exported Function | 0x10053340 | 0x00053340
`FveGetClearKeyCounter` | 69 (0x45) | Exported Function | 0x1002ed90 | 0x0002ed90
`FveGetDataSet` | 70 (0x46) | Exported Function | 0x10051720 | 0x00051720
`FveGetDescriptionW` | 71 (0x47) | Exported Function | 0x100534a0 | 0x000534a0
`FveGetDeviceLockoutData` | 72 (0x48) | Exported Function | 0x10053580 | 0x00053580
`FveGetExternalKeyBlob` | 73 (0x49) | Exported Function | 0x10053640 | 0x00053640
`FveGetAuthMethodSid` | 67 (0x43) | Exported Function | 0x10053270 | 0x00053270
`FveGetFipsAllowDisabled` | 74 (0x4a) | Exported Function | 0x10051800 | 0x00051800
`FveGetFveMethodEDrv` | 76 (0x4c) | Exported Function | 0x100518b0 | 0x000518b0
`FveGetFveMethodEx` | 77 (0x4d) | Exported Function | 0x10021740 | 0x00021740
`FveGetIdentificationFieldW` | 78 (0x4e) | Exported Function | 0x1002ecd0 | 0x0002ecd0
`FveGetIdentity` | 79 (0x4f) | Exported Function | 0x10021520 | 0x00021520
`FveGetKeyPackage` | 80 (0x50) | Exported Function | 0x10051980 | 0x00051980
`FveGetRecoveryPasswordBackupInformation` | 81 (0x51) | Exported Function | 0x10051a70 | 0x00051a70
`FveGetFveMethod` | 75 (0x4b) | Exported Function | 0x10020fa0 | 0x00020fa0
`FveGetAuthMethodInformation` | 66 (0x42) | Exported Function | 0x10021460 | 0x00021460
`FveGetAuthMethodGuids` | 65 (0x41) | Exported Function | 0x10021050 | 0x00021050
`FveGetAllowKeyExport` | 64 (0x40) | Exported Function | 0x1002e3a0 | 0x0002e3a0
`FveDeleteAuthMethod` | 49 (0x31) | Exported Function | 0x10052d70 | 0x00052d70
`FveDeleteDeviceEncryptionOptOutForVolumeW` | 50 (0x32) | Exported Function | 0x10052e60 | 0x00052e60
`FveDisableDeviceLockoutState` | 51 (0x33) | Exported Function | 0x10052f70 | 0x00052f70
`FveDiscardChanges` | 52 (0x34) | Exported Function | 0x10051490 | 0x00051490
`FveDraCertPresentInRegistry` | 53 (0x35) | Exported Function | 0x10053040 | 0x00053040
`FveEnableRawAccess` | 54 (0x36) | Exported Function | 0x10051560 | 0x00051560
`FveEnableRawAccessEx` | 55 (0x37) | Exported Function | 0x10051580 | 0x00051580
`FveEnableRawAccessW` | 56 (0x38) | Exported Function | 0x10051650 | 0x00051650
`FveEraseDrive` | 57 (0x39) | Exported Function | 0x10029770 | 0x00029770
`FveEscrowEncryptedRecoveryKeyForRetailUnlock` | 58 (0x3a) | Exported Function | 0x100530f0 | 0x000530f0
`FveFindFirstVolume` | 59 (0x3b) | Exported Function | 0x1001d5e0 | 0x0001d5e0
`FveFindNextVolume` | 60 (0x3c) | Exported Function | 0x1001da70 | 0x0001da70
`FveFlagsToProtectorType` | 61 (0x3d) | Exported Function | 0x1002b8a0 | 0x0002b8a0
`FveGenerateNbp` | 62 (0x3e) | Exported Function | 0x100531a0 | 0x000531a0
`FveGenerateNkpSessionKeys` | 63 (0x3f) | Exported Function | 0x1002da30 | 0x0002da30
`FveConversionStopEx` | 47 (0x2f) | Exported Function | 0x100513b0 | 0x000513b0
`NgscbIsHostOsOnRoamableDrive` | 10 (0xa) | Exported Function | 0x10034330 | 0x00034330


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


