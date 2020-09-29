---
title: webauthn.dll | Web Authentication
excerpt: What is webauthn.dll?
---

# webauthn.dll 

* File Path: `C:\Windows\SysWOW64\webauthn.dll`
* Description: Web Authentication

## Hashes

Type | Hash
-- | --
MD5 | `B95F44370D38E9F7C42975AB85DAFF72`
SHA1 | `AF5E7AB0FEB7695F07F2D46590C5D75B95B335A1`
SHA256 | `E9601F9BA50B6FE58520A58F0F6BD88FEBDECD129741ACAD5E242639ED1C5546`
SHA384 | `A2B26BF21C54146F114300A42B0F1AA51B8F30ED6DBCEA5681D40B9B1855C3535497E5439A2BD4B356924D4C3B2EAF7A`
SHA512 | `4DC8308B3919ED3E57B8CF6420880F6991BF990250862739419F77474BFC5A861BD86B4D4C5A38DB57DD99FBE61AD47918E9104CBA8977603388F9C4E3267734`
SSDEEP | `12288:hgRxm1YZUJ5SJXUYp60WHueb02uZ7+JIQ:hgRxm1gUJ0JzpdWVw2uZ7+`
IMP | `555AC0C05D6ADB89F2BA0FE713F2D4E4`
PESHA1 | `0499DBC6E459E2666C5A223F36EA8D96716B6DF9`
PE256 | `16A34A58733A1C634B6D8ECCFDA6841F6350D5913728CDE5FDBFB935812C6D1D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CryptsvcDllCtrl` | 1 (0x1) | Exported Function | 0x1001fc70 | 0x0001fc70
`WebAuthNCtapResetDevice` | 30 (0x1e) | Exported Function | 0x100112c0 | 0x000112c0
`WebAuthNCtapRpcGetAssertionUserList` | 31 (0x1f) | Exported Function | 0x100135b0 | 0x000135b0
`WebAuthNCtapRpcGetCborCommand` | 32 (0x20) | Exported Function | 0x10013490 | 0x00013490
`WebAuthNCtapRpcSelectGetAssertion` | 33 (0x21) | Exported Function | 0x100138d0 | 0x000138d0
`WebAuthNCtapSendCommand` | 34 (0x22) | Exported Function | 0x10012df0 | 0x00012df0
`WebAuthNCtapSetClientPin` | 35 (0x23) | Exported Function | 0x100110a0 | 0x000110a0
`WebAuthNCtapStartDeviceChangeNotify` | 36 (0x24) | Exported Function | 0x10013de0 | 0x00013de0
`WebAuthNCtapStopDeviceChangeNotify` | 37 (0x25) | Exported Function | 0x10013df0 | 0x00013df0
`WebAuthNCtapVerifyGetAssertion` | 38 (0x26) | Exported Function | 0x10012bd0 | 0x00012bd0
`WebAuthNDecodeAccountInformation` | 39 (0x27) | Exported Function | 0x1001d490 | 0x0001d490
`WebAuthNDeletePlatformCredential` | 40 (0x28) | Exported Function | 0x1001d520 | 0x0001d520
`WebAuthNCtapParseAuthenticatorData` | 29 (0x1d) | Exported Function | 0x10012d60 | 0x00012d60
`WebAuthNEncodeAccountInformation` | 41 (0x29) | Exported Function | 0x1001d400 | 0x0001d400
`WebAuthNFreeCredentialAttestation` | 43 (0x2b) | Exported Function | 0x1000fdf0 | 0x0000fdf0
`WebAuthNFreeDecodedAccountInformation` | 44 (0x2c) | Exported Function | 0x100122a0 | 0x000122a0
`WebAuthNFreeEncodedAccountInformation` | 45 (0x2d) | Exported Function | 0x100122a0 | 0x000122a0
`WebAuthNFreePlatformCredentials` | 46 (0x2e) | Exported Function | 0x10016460 | 0x00016460
`WebAuthNFreeUserEntityList` | 47 (0x2f) | Exported Function | 0x100122a0 | 0x000122a0
`WebAuthNGetApiVersionNumber` | 48 (0x30) | Exported Function | 0x10018e60 | 0x00018e60
`WebAuthNGetCancellationId` | 49 (0x31) | Exported Function | 0x10018e10 | 0x00018e10
`WebAuthNGetCoseAlgorithmIdentifier` | 50 (0x32) | Exported Function | 0x100181c0 | 0x000181c0
`WebAuthNGetCredentialIdFromAuthenticatorData` | 51 (0x33) | Exported Function | 0x10013e00 | 0x00013e00
`WebAuthNGetErrorName` | 52 (0x34) | Exported Function | 0x100133e0 | 0x000133e0
`WebAuthNGetPlatformCredentials` | 53 (0x35) | Exported Function | 0x1001d9b0 | 0x0001d9b0
`WebAuthNFreeAssertion` | 42 (0x2a) | Exported Function | 0x100122a0 | 0x000122a0
`WebAuthNGetW3CExceptionDOMError` | 54 (0x36) | Exported Function | 0x10013410 | 0x00013410
`WebAuthNCtapManageSetPin` | 28 (0x1c) | Exported Function | 0x10015c00 | 0x00015c00
`WebAuthNCtapManageResetDevice` | 26 (0x1a) | Exported Function | 0x10015910 | 0x00015910
`I_WebAuthNCtapDecodeGetAssertionRpcResponse` | 2 (0x2) | Exported Function | 0x10011cc0 | 0x00011cc0
`I_WebAuthNCtapDecodeMakeCredentialRpcResponse` | 3 (0x3) | Exported Function | 0x10010150 | 0x00010150
`I_WebAuthNCtapEncodeGetAssertionRpcRequest` | 4 (0x4) | Exported Function | 0x10011880 | 0x00011880
`I_WebAuthNCtapEncodeMakeCredentialRpcRequest` | 5 (0x5) | Exported Function | 0x1000fe40 | 0x0000fe40
`WebAuthNAuthenticatorGetAssertion` | 6 (0x6) | Exported Function | 0x100188a0 | 0x000188a0
`WebAuthNAuthenticatorMakeCredential` | 7 (0x7) | Exported Function | 0x100182a0 | 0x000182a0
`WebAuthNCancelCurrentOperation` | 8 (0x8) | Exported Function | 0x10018e40 | 0x00018e40
`WebAuthNCtapChangeClientPin` | 9 (0x9) | Exported Function | 0x10011180 | 0x00011180
`WebAuthNCtapChangeClientPinForSelectedDevice` | 10 (0xa) | Exported Function | 0x10012990 | 0x00012990
`WebAuthNCtapFreeSelectedDeviceInformation` | 11 (0xb) | Exported Function | 0x100122a0 | 0x000122a0
`WebAuthNCtapGetAssertion` | 12 (0xc) | Exported Function | 0x100122c0 | 0x000122c0
`WebAuthNCtapManageSelect` | 27 (0x1b) | Exported Function | 0x10015850 | 0x00015850
`WebAuthNCtapGetSupportedTransports` | 13 (0xd) | Exported Function | 0x10013af0 | 0x00013af0
`WebAuthNCtapIsStopSendCommandError` | 15 (0xf) | Exported Function | 0x10013440 | 0x00013440
`WebAuthNCtapMakeCredential` | 16 (0x10) | Exported Function | 0x10011330 | 0x00011330
`WebAuthNCtapManageAuthenticatePin` | 17 (0x11) | Exported Function | 0x10015b00 | 0x00015b00
`WebAuthNCtapManageCancelEnrollFingerprint` | 18 (0x12) | Exported Function | 0x10016050 | 0x00016050
`WebAuthNCtapManageChangePin` | 19 (0x13) | Exported Function | 0x10015ce0 | 0x00015ce0
`WebAuthNCtapManageClose` | 20 (0x14) | Exported Function | 0x10015350 | 0x00015350
`WebAuthNCtapManageDeleteCredential` | 21 (0x15) | Exported Function | 0x100168f0 | 0x000168f0
`WebAuthNCtapManageEnrollFingerprint` | 22 (0x16) | Exported Function | 0x10015e30 | 0x00015e30
`WebAuthNCtapManageFreeDisplayCredentials` | 23 (0x17) | Exported Function | 0x10016460 | 0x00016460
`WebAuthNCtapManageGetDisplayCredentials` | 24 (0x18) | Exported Function | 0x100164b0 | 0x000164b0
`WebAuthNCtapManageRemoveFingerprints` | 25 (0x19) | Exported Function | 0x10016100 | 0x00016100
`WebAuthNCtapGetWnfLocalizedString` | 14 (0xe) | Exported Function | 0x10016970 | 0x00016970
`WebAuthNIsUserVerifyingPlatformAuthenticatorAvailable` | 55 (0x37) | Exported Function | 0x1001d250 | 0x0001d250


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: webauthn.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/e9601f9ba50b6fe58520a58f0f6bd88febdecd129741acad5e242639ed1c5546/detection/





MIT License. Copyright (c) 2020 Strontic.


