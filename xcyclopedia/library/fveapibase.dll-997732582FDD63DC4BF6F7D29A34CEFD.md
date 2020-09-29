---
title: fveapibase.dll | Windows BitLocker Drive Encryption Base API
excerpt: What is fveapibase.dll?
---

# fveapibase.dll 

* File Path: `C:\Windows\system32\fveapibase.dll`
* Description: Windows BitLocker Drive Encryption Base API

## Hashes

Type | Hash
-- | --
MD5 | `997732582FDD63DC4BF6F7D29A34CEFD`
SHA1 | `6F4BC8419DAD4380657384BE9D66EF3A98FB981E`
SHA256 | `7D4E1F8412F217F0376742E6BEDDEBAAC9417D0C9006270B6C82F932991BD857`
SHA384 | `8FA2BBBB1B74616B4AA40FCC28F2F36ACBC2D36ECF0B173B3E62DD1ADE4E12B7B90519BA11FB73EB002971764868F14C`
SHA512 | `80F7AC15807F644A558A534248E931762D166F72FEC5C793F446BD6C6C2398F37636ACAAE6C36EDC85AD1443F8F61DCF244543092F2E89CDCEAB1B7E983FA37F`
SSDEEP | `12288:td+r6ymCJk9rIiOGOsPhXBQADcOvACOOidce:Sr6yq1+GDXBQAD+vOgce`
IMP | `8E557471042BD6AF59F99694922DCB2C`
PESHA1 | `130E2CAEF186DBBB04ECEFA2CE1312F9714168BE`
PE256 | `A5479AC0E58F5CF682F215CBE20AD238EAEA8155A57DC577793EC3005C1E5232`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FveAuthElementFromPassPhraseW` | 2 (0x2) | Exported Function | 0x0000000180002c30 | 0x00002c30
`FveGetFveMethodEDrv` | 32 (0x20) | Exported Function | 0x0000000180003740 | 0x00003740
`FveGetFveMethodEx` | 33 (0x21) | Exported Function | 0x0000000180003820 | 0x00003820
`FveGetIdentity` | 34 (0x22) | Exported Function | 0x0000000180002800 | 0x00002800
`FveGetKeyPackage` | 35 (0x23) | Exported Function | 0x0000000180003cc0 | 0x00003cc0
`FveGetStatus` | 36 (0x24) | Exported Function | 0x0000000180002430 | 0x00002430
`FveGetStatusW` | 37 (0x25) | Exported Function | 0x0000000180002330 | 0x00002330
`FveGetUserFlags` | 38 (0x26) | Exported Function | 0x0000000180002520 | 0x00002520
`FveGetVolumeNameW` | 39 (0x27) | Exported Function | 0x00000001800044c0 | 0x000044c0
`FveIsHardwareReadyForConversion` | 40 (0x28) | Exported Function | 0x0000000180003c40 | 0x00003c40
`FveIsRecoveryPasswordGroupValidW` | 41 (0x29) | Exported Function | 0x0000000180002ff0 | 0x00002ff0
`FveIsRecoveryPasswordValidW` | 42 (0x2a) | Exported Function | 0x00000001800030a0 | 0x000030a0
`FveIsVolumeEncryptable` | 43 (0x2b) | Exported Function | 0x00000001800035c0 | 0x000035c0
`FveLockVolume` | 44 (0x2c) | Exported Function | 0x0000000180002530 | 0x00002530
`FveNotifyVolumeAfterFormat` | 45 (0x2d) | Exported Function | 0x0000000180004200 | 0x00004200
`FveOpenVolumeByHandle` | 46 (0x2e) | Exported Function | 0x0000000180004780 | 0x00004780
`FveOpenVolumeExW` | 47 (0x2f) | Exported Function | 0x0000000180004cd0 | 0x00004cd0
`FveOpenVolumeW` | 48 (0x30) | Exported Function | 0x0000000180004ca0 | 0x00004ca0
`FveQuery` | 49 (0x31) | Exported Function | 0x0000000180004de0 | 0x00004de0
`FveRevertVolume` | 50 (0x32) | Exported Function | 0x0000000180003150 | 0x00003150
`FveSelectBestRecoveryPasswordByBackupInformation` | 51 (0x33) | Exported Function | 0x00000001800029d0 | 0x000029d0
`FveSetAllowKeyExport` | 52 (0x34) | Exported Function | 0x0000000180003a00 | 0x00003a00
`FveSetFipsAllowDisabled` | 53 (0x35) | Exported Function | 0x00000001800039f0 | 0x000039f0
`FveSetFveMethod` | 54 (0x36) | Exported Function | 0x0000000180003930 | 0x00003930
`FveSetRecoveryPasswordBackupInformation` | 55 (0x37) | Exported Function | 0x00000001800028d0 | 0x000028d0
`FveSetUserFlags` | 56 (0x38) | Exported Function | 0x0000000180002520 | 0x00002520
`FveGetFveMethod` | 31 (0x1f) | Exported Function | 0x0000000180003670 | 0x00003670
`FveUpgradeVolume` | 57 (0x39) | Exported Function | 0x0000000180002280 | 0x00002280
`FveGetFipsAllowDisabled` | 30 (0x1e) | Exported Function | 0x0000000180003ae0 | 0x00003ae0
`FveGetAuthMethodInformation` | 28 (0x1c) | Exported Function | 0x0000000180002600 | 0x00002600
`FveAuthElementFromPinW` | 3 (0x3) | Exported Function | 0x0000000180002b60 | 0x00002b60
`FveAuthElementFromRecoveryPasswordW` | 4 (0x4) | Exported Function | 0x0000000180002ce0 | 0x00002ce0
`FveAuthElementGetKeyFileNameW` | 5 (0x5) | Exported Function | 0x0000000180002f20 | 0x00002f20
`FveAuthElementReadExternalKeyW` | 6 (0x6) | Exported Function | 0x0000000180002d90 | 0x00002d90
`FveAuthElementToRecoveryPasswordW` | 7 (0x7) | Exported Function | 0x0000000180002a90 | 0x00002a90
`FveAuthElementWriteExternalKeyW` | 8 (0x8) | Exported Function | 0x0000000180002e70 | 0x00002e70
`FveCanPinExceptionPolicyBeApplied` | 9 (0x9) | Exported Function | 0x00000001800049b0 | 0x000049b0
`FveClearUserFlags` | 10 (0xa) | Exported Function | 0x0000000180002520 | 0x00002520
`FveCloseHandle` | 11 (0xb) | Exported Function | 0x0000000180004140 | 0x00004140
`FveCloseVolume` | 12 (0xc) | Exported Function | 0x0000000180004090 | 0x00004090
`FveCommitChanges` | 13 (0xd) | Exported Function | 0x00000001800020e0 | 0x000020e0
`FveCommitChangesEx` | 14 (0xe) | Exported Function | 0x00000001800049c0 | 0x000049c0
`FveConversionDecrypt` | 15 (0xf) | Exported Function | 0x0000000180003200 | 0x00003200
`FveConversionDecryptEx` | 16 (0x10) | Exported Function | 0x0000000180003210 | 0x00003210
`FveConversionPause` | 17 (0x11) | Exported Function | 0x0000000180003400 | 0x00003400
`FveConversionResume` | 18 (0x12) | Exported Function | 0x00000001800034e0 | 0x000034e0
`FveConversionStop` | 19 (0x13) | Exported Function | 0x0000000180003300 | 0x00003300
`FveConversionStopEx` | 20 (0x14) | Exported Function | 0x0000000180003310 | 0x00003310
`FveDiscardChanges` | 21 (0x15) | Exported Function | 0x00000001800020f0 | 0x000020f0
`FveEnableRawAccess` | 22 (0x16) | Exported Function | 0x0000000180003dd0 | 0x00003dd0
`FveEraseDrive` | 23 (0x17) | Exported Function | 0x00000001800021b0 | 0x000021b0
`FveFindFirstVolume` | 24 (0x18) | Exported Function | 0x00000001800042b0 | 0x000042b0
`FveFindNextVolume` | 25 (0x19) | Exported Function | 0x00000001800043d0 | 0x000043d0
`FveGetAllowKeyExport` | 26 (0x1a) | Exported Function | 0x0000000180003b80 | 0x00003b80
`FveGetAuthMethodGuids` | 27 (0x1b) | Exported Function | 0x0000000180002700 | 0x00002700
`FveGetDataSet` | 29 (0x1d) | Exported Function | 0x0000000180003ea0 | 0x00003ea0
`InternalFveIsVolumeEncrypted` | 1 (0x1) | Exported Function | 0x0000000180003f90 | 0x00003f90


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FVEAPIBASE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/7d4e1f8412f217f0376742e6beddebaac9417d0c9006270b6c82f932991bd857/detection/





MIT License. Copyright (c) 2020 Strontic.


