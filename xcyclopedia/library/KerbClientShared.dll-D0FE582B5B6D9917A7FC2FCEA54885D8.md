---
title: KerbClientShared.dll | Kerberos Client Shared Functionality
excerpt: What is KerbClientShared.dll?
---

# KerbClientShared.dll 

* File Path: `C:\Windows\system32\KerbClientShared.dll`
* Description: Kerberos Client Shared Functionality

## Hashes

Type | Hash
-- | --
MD5 | `D0FE582B5B6D9917A7FC2FCEA54885D8`
SHA1 | `6D279DFF88B13048B5AFFD9C21447D069FF1E0E2`
SHA256 | `598ED7BCD68B1A375FA7D34E7A8F37FAE05D85AD9B803047243AA9FFE30514CC`
SHA384 | `D2E7AA4BA79CBD5E4B736AACFB7714DA66EA6D3C37F5362C00321648C23429CD64195BD58C2DA0DE4B76AEB26A8813A7`
SHA512 | `44EDE2F69208C9355EF937F707F4941B3A73E96EDD97747A02BC7B8A3AD2282E25B19B55666FA5430990A46D0B5AF170AA5CB19CE34903F9BD731015344A1D57`
SSDEEP | `3072:svoO66ppj+scThFDsG9rTS23/jLbgngWAzIPF4bh8K:sQuHj+scThPnS23/jLbgnxPy`
IMP | `F46B01F34A12BD6B1095BEDE9B008337`
PESHA1 | `796BD005113BED48BC85FC9E61C7D3A9EF89F1BF`
PE256 | `52D4FDB8AFC6511D1185440CE2E1ECC21A51E7AE4C0D2947805ACE8EEB287EFF`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`KerbClientAlloc` | 1 (0x1) | Exported Function | 0x0000000180001650 | 0x00001650
`KerbClientSharedCleanup` | 22 (0x16) | Exported Function | 0x0000000180005290 | 0x00005290
`KerbClientSharedInit` | 23 (0x17) | Exported Function | 0x00000001800023f0 | 0x000023f0
`KerbClientTransformStoredCred` | 24 (0x18) | Exported Function | 0x0000000180003980 | 0x00003980
`KerbClientUnpackAsn1BufferVoid` | 25 (0x19) | Exported Function | 0x00000001800089b0 | 0x000089b0
`KerbClientUnpackKdcReplyBody` | 26 (0x1a) | Exported Function | 0x0000000180007980 | 0x00007980
`KerbClientUpdateSharedConfiguration` | 27 (0x1b) | Exported Function | 0x0000000180002620 | 0x00002620
`KerbClientVerifyChecksum` | 28 (0x1c) | Exported Function | 0x00000001800074b0 | 0x000074b0
`KerbClientVerifyEncryptedChallengePaData` | 29 (0x1d) | Exported Function | 0x0000000180005f50 | 0x00005f50
`KerbClientVerifyFastArmoredKdcReply` | 30 (0x1e) | Exported Function | 0x0000000180006100 | 0x00006100
`KerbClientVerifyFastArmoredKerbError` | 31 (0x1f) | Exported Function | 0x00000001800067e0 | 0x000067e0
`KerbClientVerifyFastArmoredTgsReply` | 32 (0x20) | Exported Function | 0x0000000180006cb0 | 0x00006cb0
`KerbDHCreateBCryptKey` | 33 (0x21) | Exported Function | 0x0000000180007c80 | 0x00007c80
`KerbDHGetLegacyDHParameters` | 34 (0x22) | Exported Function | 0x0000000180007fb0 | 0x00007fb0
`KerbDHGetLittleEndianPublicKey` | 35 (0x23) | Exported Function | 0x00000001800082c0 | 0x000082c0
`KerbDHGetSharedSecretFromCapiKeyBuffer` | 36 (0x24) | Exported Function | 0x00000001800085a0 | 0x000085a0
`KerbClientParseKeyListReplyPaData` | 21 (0x15) | Exported Function | 0x0000000180003fe0 | 0x00003fe0
`KerbClientPackAsn1Buffer` | 20 (0x14) | Exported Function | 0x0000000180002150 | 0x00002150
`KerbClientPackApReply` | 19 (0x13) | Exported Function | 0x00000001800077a0 | 0x000077a0
`KerbClientFreeSupplementalCredentials` | 18 (0x12) | Exported Function | 0x0000000180005220 | 0x00005220
`KerbClientAllocateStoredCred` | 2 (0x2) | Exported Function | 0x0000000180003920 | 0x00003920
`KerbClientBuildAsReqAuthenticator` | 3 (0x3) | Exported Function | 0x0000000180003dd0 | 0x00003dd0
`KerbClientBuildEncryptedAuthData` | 4 (0x4) | Exported Function | 0x0000000180007060 | 0x00007060
`KerbClientBuildExplicitArmorKey` | 5 (0x5) | Exported Function | 0x0000000180005760 | 0x00005760
`KerbClientBuildFastArmoredKdcRequest` | 6 (0x6) | Exported Function | 0x0000000180005860 | 0x00005860
`KerbClientBuildFastChallenge` | 7 (0x7) | Exported Function | 0x0000000180003b20 | 0x00003b20
`KerbClientBuildKeyList` | 8 (0x8) | Exported Function | 0x0000000180001690 | 0x00001690
`KerbKdcReplyContainsTgt` | 37 (0x25) | Exported Function | 0x0000000180008af0 | 0x00008af0
`KerbClientBuildStrengthenedReplyKey` | 9 (0x9) | Exported Function | 0x0000000180005d80 | 0x00005d80
`KerbClientComputeTgsChecksum` | 11 (0xb) | Exported Function | 0x0000000180007200 | 0x00007200
`KerbClientDecryptApReply` | 12 (0xc) | Exported Function | 0x00000001800013c0 | 0x000013c0
`KerbClientDecryptPacCredentials` | 13 (0xd) | Exported Function | 0x00000001800076b0 | 0x000076b0
`KerbClientDeriveFastChallengeKey` | 14 (0xe) | Exported Function | 0x0000000180005f10 | 0x00005f10
`KerbClientDuplicateStoredCred` | 15 (0xf) | Exported Function | 0x0000000180003960 | 0x00003960
`KerbClientFree` | 16 (0x10) | Exported Function | 0x0000000180005200 | 0x00005200
`KerbClientFreeStoredCred` | 17 (0x11) | Exported Function | 0x00000001800053c0 | 0x000053c0
`KerbClientBuildTicketArmorKey` | 10 (0xa) | Exported Function | 0x0000000180005e50 | 0x00005e50
`KerbPackKdcReplyWithEncryptedSessionKey` | 38 (0x26) | Exported Function | 0x00000001800041c0 | 0x000041c0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: KerbClientSHared.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/598ed7bcd68b1a375fa7d34e7a8f37fae05d85ad9b803047243aa9ffe30514cc/detection/





MIT License. Copyright (c) 2020 Strontic.


