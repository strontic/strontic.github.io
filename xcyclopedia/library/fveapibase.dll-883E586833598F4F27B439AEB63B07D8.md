---
title: fveapibase.dll | Windows BitLocker Drive Encryption Base API
excerpt: What is fveapibase.dll?
---

# fveapibase.dll 

* File Path: `C:\Windows\SysWOW64\fveapibase.dll`
* Description: Windows BitLocker Drive Encryption Base API

## Hashes

Type | Hash
-- | --
MD5 | `883E586833598F4F27B439AEB63B07D8`
SHA1 | `E349B36012277C124470DC86A77E819E616DE464`
SHA256 | `515A8077729612E97EBEA6396356E68CCEB30D28C1A938D4EB16E6E1857697FE`
SHA384 | `FDF54B43B7F85D3B8B2F29C5570A5E7FBCCC75777A8540577D2AA9551631EF2510701900FD1DBBEEF62A44D700F6DDF5`
SHA512 | `017C803EAB0F34F36B1DBC0F05239C4335675EF440810C773239441CC3478AC016605BF4CF14C3105D81BF603D4106A8775707EDCE8111474BBD3D6951CEB9C9`
SSDEEP | `6144:E+OB+YHyO0CZUsLJai0VWLbIf2xTdDfPw20ncaKTSl2ukUmDU:et0CZTmYJXPw2LOl2uc4`
IMP | `6BE7885E8B5FE3453D7B50451549C1E5`
PESHA1 | `3C2B946A4E549C14E6AAA5893BCBC243A7266C13`
PE256 | `D5318DCD14AB886C65592C83DF85028AA8D1D7F92B29430F76B0FF18BF853FD6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FveAuthElementFromPassPhraseW` | 2 (0x2) | Exported Function | 0x1000eab0 | 0x0000eab0
`FveGetFveMethodEDrv` | 32 (0x20) | Exported Function | 0x1000f610 | 0x0000f610
`FveGetFveMethodEx` | 33 (0x21) | Exported Function | 0x1000f6e0 | 0x0000f6e0
`FveGetIdentity` | 34 (0x22) | Exported Function | 0x1000e6c0 | 0x0000e6c0
`FveGetKeyPackage` | 35 (0x23) | Exported Function | 0x1000fb80 | 0x0000fb80
`FveGetStatus` | 36 (0x24) | Exported Function | 0x1000e340 | 0x0000e340
`FveGetStatusW` | 37 (0x25) | Exported Function | 0x1000e240 | 0x0000e240
`FveGetUserFlags` | 38 (0x26) | Exported Function | 0x1000e430 | 0x0000e430
`FveGetVolumeNameW` | 39 (0x27) | Exported Function | 0x10010300 | 0x00010300
`FveIsHardwareReadyForConversion` | 40 (0x28) | Exported Function | 0x1000faf0 | 0x0000faf0
`FveIsRecoveryPasswordGroupValidW` | 41 (0x29) | Exported Function | 0x1000ee80 | 0x0000ee80
`FveIsRecoveryPasswordValidW` | 42 (0x2a) | Exported Function | 0x1000ef40 | 0x0000ef40
`FveIsVolumeEncryptable` | 43 (0x2b) | Exported Function | 0x1000f480 | 0x0000f480
`FveLockVolume` | 44 (0x2c) | Exported Function | 0x1000e440 | 0x0000e440
`FveNotifyVolumeAfterFormat` | 45 (0x2d) | Exported Function | 0x10010080 | 0x00010080
`FveOpenVolumeByHandle` | 46 (0x2e) | Exported Function | 0x10010500 | 0x00010500
`FveOpenVolumeExW` | 47 (0x2f) | Exported Function | 0x100109e0 | 0x000109e0
`FveOpenVolumeW` | 48 (0x30) | Exported Function | 0x100109b0 | 0x000109b0
`FveQuery` | 49 (0x31) | Exported Function | 0x10010ac0 | 0x00010ac0
`FveRevertVolume` | 50 (0x32) | Exported Function | 0x1000f000 | 0x0000f000
`FveSelectBestRecoveryPasswordByBackupInformation` | 51 (0x33) | Exported Function | 0x1000e860 | 0x0000e860
`FveSetAllowKeyExport` | 52 (0x34) | Exported Function | 0x1000f8a0 | 0x0000f8a0
`FveSetFipsAllowDisabled` | 53 (0x35) | Exported Function | 0x1000f890 | 0x0000f890
`FveSetFveMethod` | 54 (0x36) | Exported Function | 0x1000f7d0 | 0x0000f7d0
`FveSetRecoveryPasswordBackupInformation` | 55 (0x37) | Exported Function | 0x1000e790 | 0x0000e790
`FveSetUserFlags` | 56 (0x38) | Exported Function | 0x1000e430 | 0x0000e430
`FveGetFveMethod` | 31 (0x1f) | Exported Function | 0x1000f540 | 0x0000f540
`FveUpgradeVolume` | 57 (0x39) | Exported Function | 0x1000e180 | 0x0000e180
`FveGetFipsAllowDisabled` | 30 (0x1e) | Exported Function | 0x1000f980 | 0x0000f980
`FveGetAuthMethodInformation` | 28 (0x1c) | Exported Function | 0x1000e500 | 0x0000e500
`FveAuthElementFromPinW` | 3 (0x3) | Exported Function | 0x1000e9e0 | 0x0000e9e0
`FveAuthElementFromRecoveryPasswordW` | 4 (0x4) | Exported Function | 0x1000eb70 | 0x0000eb70
`FveAuthElementGetKeyFileNameW` | 5 (0x5) | Exported Function | 0x1000edc0 | 0x0000edc0
`FveAuthElementReadExternalKeyW` | 6 (0x6) | Exported Function | 0x1000ec30 | 0x0000ec30
`FveAuthElementToRecoveryPasswordW` | 7 (0x7) | Exported Function | 0x1000e920 | 0x0000e920
`FveAuthElementWriteExternalKeyW` | 8 (0x8) | Exported Function | 0x1000ed00 | 0x0000ed00
`FveCanPinExceptionPolicyBeApplied` | 9 (0x9) | Exported Function | 0x10010700 | 0x00010700
`FveClearUserFlags` | 10 (0xa) | Exported Function | 0x1000e430 | 0x0000e430
`FveCloseHandle` | 11 (0xb) | Exported Function | 0x1000ffb0 | 0x0000ffb0
`FveCloseVolume` | 12 (0xc) | Exported Function | 0x1000ff00 | 0x0000ff00
`FveCommitChanges` | 13 (0xd) | Exported Function | 0x1000dfe0 | 0x0000dfe0
`FveCommitChangesEx` | 14 (0xe) | Exported Function | 0x10010720 | 0x00010720
`FveConversionDecrypt` | 15 (0xf) | Exported Function | 0x1000f0c0 | 0x0000f0c0
`FveConversionDecryptEx` | 16 (0x10) | Exported Function | 0x1000f0e0 | 0x0000f0e0
`FveConversionPause` | 17 (0x11) | Exported Function | 0x1000f2c0 | 0x0000f2c0
`FveConversionResume` | 18 (0x12) | Exported Function | 0x1000f3a0 | 0x0000f3a0
`FveConversionStop` | 19 (0x13) | Exported Function | 0x1000f1c0 | 0x0000f1c0
`FveConversionStopEx` | 20 (0x14) | Exported Function | 0x1000f1e0 | 0x0000f1e0
`FveDiscardChanges` | 21 (0x15) | Exported Function | 0x1000e000 | 0x0000e000
`FveEnableRawAccess` | 22 (0x16) | Exported Function | 0x1000fc60 | 0x0000fc60
`FveEraseDrive` | 23 (0x17) | Exported Function | 0x1000e0c0 | 0x0000e0c0
`FveFindFirstVolume` | 24 (0x18) | Exported Function | 0x10010140 | 0x00010140
`FveFindNextVolume` | 25 (0x19) | Exported Function | 0x10010240 | 0x00010240
`FveGetAllowKeyExport` | 26 (0x1a) | Exported Function | 0x1000fa30 | 0x0000fa30
`FveGetAuthMethodGuids` | 27 (0x1b) | Exported Function | 0x1000e5e0 | 0x0000e5e0
`FveGetDataSet` | 29 (0x1d) | Exported Function | 0x1000fd40 | 0x0000fd40
`InternalFveIsVolumeEncrypted` | 1 (0x1) | Exported Function | 0x1000fe10 | 0x0000fe10


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/515a8077729612e97ebea6396356e68cceb30d28c1a938d4eb16e6e1857697fe/detection/





MIT License. Copyright (c) 2020 Strontic.


