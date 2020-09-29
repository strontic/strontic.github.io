---
title: feclient.dll | Windows NT File Encryption Client Interfaces
excerpt: What is feclient.dll?
---

# feclient.dll 

* File Path: `C:\Windows\system32\feclient.dll`
* Description: Windows NT File Encryption Client Interfaces

## Hashes

Type | Hash
-- | --
MD5 | `4401F4795005B5DC4BB1BAF1A87B1342`
SHA1 | `4061A34907C7B7240A2D0F70CEC1AB7F9C73A358`
SHA256 | `A5BD0D33940328C60D50F05F387E8CEF277F596F2D96935471568D820F807727`
SHA384 | `5FEDD5149CDCBEF1C79887ABBE877D8B4C61E115894A5EDC0DFA3BF0CC3E6F62BD117AA4A999B40594BC9E0657C5FF00`
SHA512 | `2AF537DD94358C24966A43286A8DB8970BECF2200BBADE0CA35ED39B0D0BC9622F6B507254E31DC90B634EA24BBCE78ED612B0D1C706086F8578154481C48D8F`
SSDEEP | `3072:n8oP0YhYA0+oA1PswL4qPcWoDaASgIEVn0MHjOk8+MgSBL/ynOxcrvkFTd6b5+B0:n8GZhYGplPrCaAzIu0MHipjyOUfb8OP`
IMP | `92D0B17F3FBF8F96B5AFA7076C7D717B`
PESHA1 | `DD99ECB0E218DBD33FC45E6AD1F8873407B3F967`
PE256 | `611B0510AE441644587C1220F4D30C87AD2EAEED761008E94255358CA449D76E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DpQueryUserProtectorDescriptor` | 1 (0x1) | Exported Function | 0x00000001800133a0 | 0x000133a0
`EfsClientCloseFileRaw` | 30 (0x1e) | Exported Function | 0x0000000180010c40 | 0x00010c40
`EfsClientCopyFileRaw` | 31 (0x1f) | Exported Function | 0x0000000180012e00 | 0x00012e00
`EfsClientDecryptFile` | 32 (0x20) | Exported Function | 0x00000001800108f0 | 0x000108f0
`EfsClientDuplicateEncryptionInfo` | 33 (0x21) | Exported Function | 0x0000000180011320 | 0x00011320
`EfsClientEncryptFileEx` | 34 (0x22) | Exported Function | 0x00000001800107d0 | 0x000107d0
`EfsClientFileEncryptionStatus` | 35 (0x23) | Exported Function | 0x00000001800109c0 | 0x000109c0
`EfsClientFreeKeyInfo` | 36 (0x24) | Exported Function | 0x00000001800116c0 | 0x000116c0
`EfsClientFreeProtectorList` | 37 (0x25) | Exported Function | 0x0000000180011240 | 0x00011240
`EfsClientGetEncryptedFileVersion` | 38 (0x26) | Exported Function | 0x0000000180011720 | 0x00011720
`EfsClientGetKeyInfo` | 39 (0x27) | Exported Function | 0x00000001800115f0 | 0x000115f0
`EfsClientOpenFileRaw` | 40 (0x28) | Exported Function | 0x0000000180010a50 | 0x00010a50
`EfsClientQueryProtectors` | 41 (0x29) | Exported Function | 0x0000000180010fe0 | 0x00010fe0
`EfsClientReadFileRaw` | 42 (0x2a) | Exported Function | 0x0000000180010b90 | 0x00010b90
`EfsClientWriteFileRaw` | 43 (0x2b) | Exported Function | 0x0000000180010bb0 | 0x00010bb0
`EfsClientWriteFileWithHeaderRaw` | 44 (0x2c) | Exported Function | 0x0000000180010bf0 | 0x00010bf0
`EfsReprotectFile` | 45 (0x2d) | Exported Function | 0x0000000180012e30 | 0x00012e30
`EfsUtilGetCurrentKey` | 46 (0x2e) | Exported Function | efsutil._EfsUtilGetCurrentKey_Deprecated@16 | 0x00039824
`EfsValidateTokenForConsumer` | 47 (0x2f) | Exported Function | 0x00000001800130d0 | 0x000130d0
`EfsValidateUserForConsumer` | 48 (0x30) | Exported Function | 0x0000000180012f10 | 0x00012f10
`FeClClearCaches` | 49 (0x31) | Exported Function | 0x0000000180012d00 | 0x00012d00
`FeClientInitialize` | 51 (0x33) | Exported Function | 0x0000000180010710 | 0x00010710
`FeClQueryInfo` | 50 (0x32) | Exported Function | 0x0000000180012c70 | 0x00012c70
`GetLockSessionUnwrappedKey` | 52 (0x34) | Exported Function | 0x0000000180012540 | 0x00012540
`EdpWriteLogSiteLearningEvents` | 29 (0x1d) | Exported Function | 0x0000000180012df0 | 0x00012df0
`EdpUnprotectFile` | 28 (0x1c) | Exported Function | 0x0000000180012dc0 | 0x00012dc0
`EdpSetCredServiceInfo` | 27 (0x1b) | Exported Function | 0x0000000180012a70 | 0x00012a70
`EdpRmsClearKeys` | 26 (0x1a) | Exported Function | 0x0000000180012d20 | 0x00012d20
`DpQueryUserProtectorDescriptorInfo` | 2 (0x2) | Exported Function | 0x00000001800135e0 | 0x000135e0
`EdpAllowFileAccessForProcess` | 3 (0x3) | Exported Function | 0x0000000180012da0 | 0x00012da0
`EdpContainerizeFile` | 4 (0x4) | Exported Function | 0x0000000180012d30 | 0x00012d30
`EdpCredentialCreate` | 5 (0x5) | Exported Function | 0x0000000180011e30 | 0x00011e30
`EdpCredentialDelete` | 6 (0x6) | Exported Function | 0x00000001800121f0 | 0x000121f0
`EdpCredentialExists` | 7 (0x7) | Exported Function | 0x00000001800120d0 | 0x000120d0
`EdpCredentialQuery` | 8 (0x8) | Exported Function | 0x0000000180011f80 | 0x00011f80
`EdpDecontainerizeFile` | 9 (0x9) | Exported Function | 0x0000000180012d80 | 0x00012d80
`EdpDplPolicyEnabledForUser` | 10 (0xa) | Exported Function | 0x00000001800127a0 | 0x000127a0
`EdpDplStartCredServiceIfDplEnabledForUser` | 11 (0xb) | Exported Function | 0x00000001800127b0 | 0x000127b0
`EdpDplUpgradePinInfo` | 12 (0xc) | Exported Function | 0x0000000180012700 | 0x00012700
`GetLockSessionWrappedKey` | 53 (0x35) | Exported Function | 0x00000001800123e0 | 0x000123e0
`EdpDplUpgradeVerifyUser` | 13 (0xd) | Exported Function | 0x0000000180012730 | 0x00012730
`EdpDplUserUnlockComplete` | 15 (0xf) | Exported Function | 0x0000000180012790 | 0x00012790
`EdpDplUserUnlockStart` | 16 (0x10) | Exported Function | 0x0000000180012790 | 0x00012790
`EdpFree` | 17 (0x11) | Exported Function | 0x0000000180012260 | 0x00012260
`EdpGetContainerIdentity` | 18 (0x12) | Exported Function | 0x0000000180012d60 | 0x00012d60
`EdpGetCredServiceState` | 19 (0x13) | Exported Function | 0x0000000180012690 | 0x00012690
`EdpIsConsumerDataProtectionEnforced` | 20 (0x14) | Exported Function | 0x0000000180012ee0 | 0x00012ee0
`EdpIsConsumerDataProtectionSupported` | 21 (0x15) | Exported Function | 0x0000000180012ed0 | 0x00012ed0
`EdpPurgeAppLearningEvents` | 22 (0x16) | Exported Function | 0x0000000180012de0 | 0x00012de0
`EdpQueryCredServiceInfo` | 23 (0x17) | Exported Function | 0x0000000180012830 | 0x00012830
`EdpQueryDplEnforcedPolicyOwnerIds` | 24 (0x18) | Exported Function | 0x0000000180012240 | 0x00012240
`EdpQueryRevokedPolicyOwnerIds` | 25 (0x19) | Exported Function | 0x0000000180012220 | 0x00012220
`EdpDplUserCredentialsSet` | 14 (0xe) | Exported Function | 0x0000000180012760 | 0x00012760
`OefsCheckSupport` | 54 (0x36) | Exported Function | 0x0000000180012e10 | 0x00012e10


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a5bd0d33940328c60d50f05f387e8cef277f596f2d96935471568d820f807727/detection/





MIT License. Copyright (c) 2020 Strontic.


