---
title: KerbClientShared.dll | Kerberos Client Shared Functionality
excerpt: What is KerbClientShared.dll?
---

# KerbClientShared.dll 

* File Path: `C:\Windows\SysWOW64\KerbClientShared.dll`
* Description: Kerberos Client Shared Functionality

## Hashes

Type | Hash
-- | --
MD5 | `22FD99432EC0BC9B1990F66E965F838C`
SHA1 | `D4848FFA945A85B15CCE41E10CBA63F2B8BFCDD9`
SHA256 | `9C97A6DFCDDB4F7976F5E75B2086C87ABF5C834446E1FFC3D961BF1E1D3DD492`
SHA384 | `002C67B2F561968E8849F30CC276EB8CCEBD06A515BA4CFBE0CE91060F26BA7643DC1ECDFC1D62F0127EFB531B547C3D`
SHA512 | `488C8A7832B4F45120873ADF53D9498B143338789A03F953BC86C2CF20E2751505E8B697DD10BF101CC70B1AF026C84FC2446E2183FFC34B01FA7A57151E1F7B`
SSDEEP | `3072:TcFIiEkdo7ba0z5ngyvCPPQBhUwSXX9kpKF4/R6t4zALt:oFIJk4bczwSHMK2BIt`
IMP | `0638E05A8F2DB4D0878B4389D3527AF1`
PESHA1 | `9CF33BD81527999061AE626A70360426D6998D28`
PE256 | `77580FE76100BCFB68F510EE06F34AB657C31F2D7CD70D3282A2A52EA771745A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`KerbClientAlloc` | 1 (0x1) | Exported Function | 0x100036b0 | 0x000036b0
`KerbClientSharedCleanup` | 22 (0x16) | Exported Function | 0x10006110 | 0x00006110
`KerbClientSharedInit` | 23 (0x17) | Exported Function | 0x10003ba0 | 0x00003ba0
`KerbClientTransformStoredCred` | 24 (0x18) | Exported Function | 0x10004e70 | 0x00004e70
`KerbClientUnpackAsn1BufferVoid` | 25 (0x19) | Exported Function | 0x10008c40 | 0x00008c40
`KerbClientUnpackKdcReplyBody` | 26 (0x1a) | Exported Function | 0x10007f70 | 0x00007f70
`KerbClientUpdateSharedConfiguration` | 27 (0x1b) | Exported Function | 0x10003d90 | 0x00003d90
`KerbClientVerifyChecksum` | 28 (0x1c) | Exported Function | 0x10007af0 | 0x00007af0
`KerbClientVerifyEncryptedChallengePaData` | 29 (0x1d) | Exported Function | 0x10006ae0 | 0x00006ae0
`KerbClientVerifyFastArmoredKdcReply` | 30 (0x1e) | Exported Function | 0x10006c30 | 0x00006c30
`KerbClientVerifyFastArmoredKerbError` | 31 (0x1f) | Exported Function | 0x10007150 | 0x00007150
`KerbClientVerifyFastArmoredTgsReply` | 32 (0x20) | Exported Function | 0x10007570 | 0x00007570
`KerbDHCreateBCryptKey` | 33 (0x21) | Exported Function | 0x100081d0 | 0x000081d0
`KerbDHGetLegacyDHParameters` | 34 (0x22) | Exported Function | 0x10008470 | 0x00008470
`KerbDHGetLittleEndianPublicKey` | 35 (0x23) | Exported Function | 0x100086d0 | 0x000086d0
`KerbDHGetSharedSecretFromCapiKeyBuffer` | 36 (0x24) | Exported Function | 0x10008910 | 0x00008910
`KerbClientParseKeyListReplyPaData` | 21 (0x15) | Exported Function | 0x10005430 | 0x00005430
`KerbClientPackAsn1Buffer` | 20 (0x14) | Exported Function | 0x10003750 | 0x00003750
`KerbClientPackApReply` | 19 (0x13) | Exported Function | 0x10007e20 | 0x00007e20
`KerbClientFreeSupplementalCredentials` | 18 (0x12) | Exported Function | 0x100060a0 | 0x000060a0
`KerbClientAllocateStoredCred` | 2 (0x2) | Exported Function | 0x10004de0 | 0x00004de0
`KerbClientBuildAsReqAuthenticator` | 3 (0x3) | Exported Function | 0x10005230 | 0x00005230
`KerbClientBuildEncryptedAuthData` | 4 (0x4) | Exported Function | 0x100077a0 | 0x000077a0
`KerbClientBuildExplicitArmorKey` | 5 (0x5) | Exported Function | 0x10006490 | 0x00006490
`KerbClientBuildFastArmoredKdcRequest` | 6 (0x6) | Exported Function | 0x10006570 | 0x00006570
`KerbClientBuildFastChallenge` | 7 (0x7) | Exported Function | 0x10004f80 | 0x00004f80
`KerbClientBuildKeyList` | 8 (0x8) | Exported Function | 0x10002b50 | 0x00002b50
`KerbKdcReplyContainsTgt` | 37 (0x25) | Exported Function | 0x10008d40 | 0x00008d40
`KerbClientBuildStrengthenedReplyKey` | 9 (0x9) | Exported Function | 0x10006960 | 0x00006960
`KerbClientComputeTgsChecksum` | 11 (0xb) | Exported Function | 0x100078c0 | 0x000078c0
`KerbClientDecryptApReply` | 12 (0xc) | Exported Function | 0x10007cb0 | 0x00007cb0
`KerbClientDecryptPacCredentials` | 13 (0xd) | Exported Function | 0x10007d70 | 0x00007d70
`KerbClientDeriveFastChallengeKey` | 14 (0xe) | Exported Function | 0x10006aa0 | 0x00006aa0
`KerbClientDuplicateStoredCred` | 15 (0xf) | Exported Function | 0x10004e50 | 0x00004e50
`KerbClientFree` | 16 (0x10) | Exported Function | 0x10006070 | 0x00006070
`KerbClientFreeStoredCred` | 17 (0x11) | Exported Function | 0x10006200 | 0x00006200
`KerbClientBuildTicketArmorKey` | 10 (0xa) | Exported Function | 0x10006a00 | 0x00006a00
`KerbPackKdcReplyWithEncryptedSessionKey` | 38 (0x26) | Exported Function | 0x100055b0 | 0x000055b0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9c97a6dfcddb4f7976f5e75b2086c87abf5c834446e1ffc3d961bf1e1d3dd492/detection/





MIT License. Copyright (c) 2020 Strontic.


