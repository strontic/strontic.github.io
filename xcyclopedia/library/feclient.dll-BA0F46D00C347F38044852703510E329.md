---
title: feclient.dll | Windows NT File Encryption Client Interfaces
excerpt: What is feclient.dll?
---

# feclient.dll 

* File Path: `C:\Windows\SysWOW64\feclient.dll`
* Description: Windows NT File Encryption Client Interfaces

## Hashes

Type | Hash
-- | --
MD5 | `BA0F46D00C347F38044852703510E329`
SHA1 | `2081F9A8B876F1BFD322FAFCC944411B20240950`
SHA256 | `CB68D51F285F5EE3C29BD81E5D058840D11F2A3F2092D618AE50B649ACAD1FC3`
SHA384 | `AF5338FB74A5770C2A91A1C0CDA327969201949AEB5022905F1CE8DBFDF9758B97936FFAB7C59BAECA65B590052965FC`
SHA512 | `2619A498DD358DBF5195A6501466D1C305CFC163AFE384F5EDD4944838F2DD07F88264FDE1A3E77E6F19599BD7D37185DFDC419FC0525C4478F7EAA8BC6E81B2`
SSDEEP | `3072:0a+SbvkBo7fXrUgUUxKRVTyGV6QzMZLaIZyLZyLRicyL/6feeHuO3hKhUg6pVjXE:lJ3r7UUCclaIZyLZyLUcyLSfnhKhB6pU`
IMP | `BE81CAAFBD94620974731B5CB2722E06`
PESHA1 | `B5681F24646E4DB82E2DE1E836EC1AEFE11BEAD8`
PE256 | `78D0EEBB97514B8F95C2BE1E3445391E3253F02F4134E41321E88DDD56138849`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DpQueryUserProtectorDescriptor` | 2 (0x2) | Exported Function | 0x5ad16c70 | 0x00016c70
`EfsClientCloseFileRaw` | 31 (0x1f) | Exported Function | 0x5ad15150 | 0x00015150
`EfsClientCopyFileRaw` | 32 (0x20) | Exported Function | 0x5ad167b0 | 0x000167b0
`EfsClientDecryptFile` | 33 (0x21) | Exported Function | 0x5ad14ed0 | 0x00014ed0
`EfsClientDuplicateEncryptionInfo` | 34 (0x22) | Exported Function | 0x5ad155a0 | 0x000155a0
`EfsClientEncryptFileEx` | 35 (0x23) | Exported Function | 0x5ad14e10 | 0x00014e10
`EfsClientFileEncryptionStatus` | 36 (0x24) | Exported Function | 0x5ad14f60 | 0x00014f60
`EfsClientFreeKeyInfo` | 37 (0x25) | Exported Function | 0x5ad157e0 | 0x000157e0
`EfsClientFreeProtectorList` | 38 (0x26) | Exported Function | 0x5ad15510 | 0x00015510
`EfsClientGetEncryptedFileVersion` | 39 (0x27) | Exported Function | 0x5ad15820 | 0x00015820
`EfsClientGetKeyInfo` | 40 (0x28) | Exported Function | 0x5ad15750 | 0x00015750
`EfsClientOpenFileRaw` | 41 (0x29) | Exported Function | 0x5ad14fc0 | 0x00014fc0
`EfsClientQueryProtectors` | 42 (0x2a) | Exported Function | 0x5ad153f0 | 0x000153f0
`EfsClientReadFileRaw` | 43 (0x2b) | Exported Function | 0x5ad150a0 | 0x000150a0
`EfsClientWriteFileRaw` | 44 (0x2c) | Exported Function | 0x5ad150d0 | 0x000150d0
`EfsClientWriteFileWithHeaderRaw` | 45 (0x2d) | Exported Function | 0x5ad15110 | 0x00015110
`EfsReprotectFile` | 46 (0x2e) | Exported Function | 0x5ad167e0 | 0x000167e0
`EfsUtilGetCurrentKey` | 1 (0x1) | Exported Function | efsutil._EfsUtilGetCurrentKey_Deprecated@16 | 0x0002b026
`EfsValidateTokenForConsumer` | 47 (0x2f) | Exported Function | 0x5ad16a00 | 0x00016a00
`EfsValidateUserForConsumer` | 48 (0x30) | Exported Function | 0x5ad168a0 | 0x000168a0
`FeClClearCaches` | 49 (0x31) | Exported Function | 0x5ad16720 | 0x00016720
`FeClientInitialize` | 51 (0x33) | Exported Function | 0x5ad14d80 | 0x00014d80
`FeClQueryInfo` | 50 (0x32) | Exported Function | 0x5ad166c0 | 0x000166c0
`GetLockSessionUnwrappedKey` | 52 (0x34) | Exported Function | 0x5ad16170 | 0x00016170
`EdpWriteLogSiteLearningEvents` | 30 (0x1e) | Exported Function | 0x5ad167a0 | 0x000167a0
`EdpUnprotectFile` | 29 (0x1d) | Exported Function | 0x5ad16780 | 0x00016780
`EdpSetCredServiceInfo` | 28 (0x1c) | Exported Function | 0x5ad16520 | 0x00016520
`EdpRmsClearKeys` | 27 (0x1b) | Exported Function | 0x5ad16730 | 0x00016730
`DpQueryUserProtectorDescriptorInfo` | 3 (0x3) | Exported Function | 0x5ad16d50 | 0x00016d50
`EdpAllowFileAccessForProcess` | 4 (0x4) | Exported Function | 0x5ad16770 | 0x00016770
`EdpContainerizeFile` | 5 (0x5) | Exported Function | 0x5ad16740 | 0x00016740
`EdpCredentialCreate` | 6 (0x6) | Exported Function | 0x5ad15c30 | 0x00015c30
`EdpCredentialDelete` | 7 (0x7) | Exported Function | 0x5ad15f60 | 0x00015f60
`EdpCredentialExists` | 8 (0x8) | Exported Function | 0x5ad15e70 | 0x00015e70
`EdpCredentialQuery` | 9 (0x9) | Exported Function | 0x5ad15d50 | 0x00015d50
`EdpDecontainerizeFile` | 10 (0xa) | Exported Function | 0x5ad16760 | 0x00016760
`EdpDplPolicyEnabledForUser` | 11 (0xb) | Exported Function | 0x5ad162c0 | 0x000162c0
`EdpDplStartCredServiceIfDplEnabledForUser` | 12 (0xc) | Exported Function | 0x5ad162e0 | 0x000162e0
`EdpDplUpgradePinInfo` | 13 (0xd) | Exported Function | 0x5ad16270 | 0x00016270
`GetLockSessionWrappedKey` | 53 (0x35) | Exported Function | 0x5ad16080 | 0x00016080
`EdpDplUpgradeVerifyUser` | 14 (0xe) | Exported Function | 0x5ad16280 | 0x00016280
`EdpDplUserUnlockComplete` | 16 (0x10) | Exported Function | 0x5ad162b0 | 0x000162b0
`EdpDplUserUnlockStart` | 17 (0x11) | Exported Function | 0x5ad162a0 | 0x000162a0
`EdpFree` | 18 (0x12) | Exported Function | 0x5ad15f90 | 0x00015f90
`EdpGetContainerIdentity` | 19 (0x13) | Exported Function | 0x5ad16750 | 0x00016750
`EdpGetCredServiceState` | 20 (0x14) | Exported Function | 0x5ad16260 | 0x00016260
`EdpIsConsumerDataProtectionEnforced` | 21 (0x15) | Exported Function | 0x5ad16860 | 0x00016860
`EdpIsConsumerDataProtectionSupported` | 22 (0x16) | Exported Function | 0x5ad16840 | 0x00016840
`EdpPurgeAppLearningEvents` | 23 (0x17) | Exported Function | 0x5ad16790 | 0x00016790
`EdpQueryCredServiceInfo` | 24 (0x18) | Exported Function | 0x5ad16320 | 0x00016320
`EdpQueryDplEnforcedPolicyOwnerIds` | 25 (0x19) | Exported Function | 0x5ad15f80 | 0x00015f80
`EdpQueryRevokedPolicyOwnerIds` | 26 (0x1a) | Exported Function | 0x5ad15f70 | 0x00015f70
`EdpDplUserCredentialsSet` | 15 (0xf) | Exported Function | 0x5ad16290 | 0x00016290
`OefsCheckSupport` | 54 (0x36) | Exported Function | 0x5ad167d0 | 0x000167d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FECLIENT.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/cb68d51f285f5ee3c29bd81e5d058840d11f2a3f2092d618ae50b649acad1fc3/detection/





MIT License. Copyright (c) 2020 Strontic.


