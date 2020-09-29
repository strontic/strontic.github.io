---
title: webauthn.dll | Web Authentication
excerpt: What is webauthn.dll?
---

# webauthn.dll 

* File Path: `C:\Windows\system32\webauthn.dll`
* Description: Web Authentication

## Hashes

Type | Hash
-- | --
MD5 | `A0090836B9F92B6C72FEFE3D14E3EF35`
SHA1 | `D35ED77D0351654A2AF2BD3D4C6F5220F796C633`
SHA256 | `733A963B933EA83783351B70979AD70413FA93147D50A8AADD13EFD3BBABE369`
SHA384 | `6C472BC25EE89830241B68D56EA36D98228FED8C1033BC2055834CB014ACE9C6F936EEC6F25218CEC744F1F7B5ABF334`
SHA512 | `895CB297E6175EDEA1E5A04AFC37DEB604E66A4CEE67D67E9A55BEAA4B23AB25947295AD192752EA9A6638DFED470C9B95F7D8624877481095303EDC24337BE4`
SSDEEP | `6144:XFchHxaUZtRSFDRYq+t8MBCprZ/zLSCjzU2TKPdYaHZIuyM/q1T/TqCItn:1U0UZt+RjrDrRLfjzU2wdvMM/qrgn`
IMP | `2BE8FE1EDDBFC29A5C6EA773C496CEC0`
PESHA1 | `942EC2523733236073E1DA5B7CC429D5E75B4533`
PE256 | `290DB0880A85EC6AFF4249AF109A33CAF5543055EEE2021C28EB71A38249D501`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CryptsvcDllCtrl` | 1 (0x1) | Exported Function | 0x000000018001f590 | 0x0001f590
`WebAuthNCtapResetDevice` | 30 (0x1e) | Exported Function | 0x000000018000c9d0 | 0x0000c9d0
`WebAuthNCtapRpcGetAssertionUserList` | 31 (0x1f) | Exported Function | 0x000000018000fb80 | 0x0000fb80
`WebAuthNCtapRpcGetCborCommand` | 32 (0x20) | Exported Function | 0x000000018000fa20 | 0x0000fa20
`WebAuthNCtapRpcSelectGetAssertion` | 33 (0x21) | Exported Function | 0x000000018000ffa0 | 0x0000ffa0
`WebAuthNCtapSendCommand` | 34 (0x22) | Exported Function | 0x000000018000f0f0 | 0x0000f0f0
`WebAuthNCtapSetClientPin` | 35 (0x23) | Exported Function | 0x000000018000c690 | 0x0000c690
`WebAuthNCtapStartDeviceChangeNotify` | 36 (0x24) | Exported Function | 0x00000001800106b0 | 0x000106b0
`WebAuthNCtapStopDeviceChangeNotify` | 37 (0x25) | Exported Function | 0x00000001800106c0 | 0x000106c0
`WebAuthNCtapVerifyGetAssertion` | 38 (0x26) | Exported Function | 0x000000018000ed90 | 0x0000ed90
`WebAuthNDecodeAccountInformation` | 39 (0x27) | Exported Function | 0x000000018001c170 | 0x0001c170
`WebAuthNDeletePlatformCredential` | 40 (0x28) | Exported Function | 0x000000018001c240 | 0x0001c240
`WebAuthNCtapParseAuthenticatorData` | 29 (0x1d) | Exported Function | 0x000000018000f050 | 0x0000f050
`WebAuthNEncodeAccountInformation` | 41 (0x29) | Exported Function | 0x000000018001c0a0 | 0x0001c0a0
`WebAuthNFreeCredentialAttestation` | 43 (0x2b) | Exported Function | 0x000000018000ad30 | 0x0000ad30
`WebAuthNFreeDecodedAccountInformation` | 44 (0x2c) | Exported Function | 0x000000018000e130 | 0x0000e130
`WebAuthNFreeEncodedAccountInformation` | 45 (0x2d) | Exported Function | 0x000000018000e130 | 0x0000e130
`WebAuthNFreePlatformCredentials` | 46 (0x2e) | Exported Function | 0x0000000180013c00 | 0x00013c00
`WebAuthNFreeUserEntityList` | 47 (0x2f) | Exported Function | 0x000000018000e130 | 0x0000e130
`WebAuthNGetApiVersionNumber` | 48 (0x30) | Exported Function | 0x0000000180016b90 | 0x00016b90
`WebAuthNGetCancellationId` | 49 (0x31) | Exported Function | 0x0000000180016b30 | 0x00016b30
`WebAuthNGetCoseAlgorithmIdentifier` | 50 (0x32) | Exported Function | 0x0000000180015ad0 | 0x00015ad0
`WebAuthNGetCredentialIdFromAuthenticatorData` | 51 (0x33) | Exported Function | 0x00000001800106d0 | 0x000106d0
`WebAuthNGetErrorName` | 52 (0x34) | Exported Function | 0x000000018000f960 | 0x0000f960
`WebAuthNGetPlatformCredentials` | 53 (0x35) | Exported Function | 0x000000018001c9e0 | 0x0001c9e0
`WebAuthNFreeAssertion` | 42 (0x2a) | Exported Function | 0x000000018000e130 | 0x0000e130
`WebAuthNGetW3CExceptionDOMError` | 54 (0x36) | Exported Function | 0x000000018000f990 | 0x0000f990
`WebAuthNCtapManageSetPin` | 28 (0x1c) | Exported Function | 0x0000000180013050 | 0x00013050
`WebAuthNCtapManageResetDevice` | 26 (0x1a) | Exported Function | 0x0000000180012c40 | 0x00012c40
`I_WebAuthNCtapDecodeGetAssertionRpcResponse` | 2 (0x2) | Exported Function | 0x000000018000d860 | 0x0000d860
`I_WebAuthNCtapDecodeMakeCredentialRpcResponse` | 3 (0x3) | Exported Function | 0x000000018000b1c0 | 0x0000b1c0
`I_WebAuthNCtapEncodeGetAssertionRpcRequest` | 4 (0x4) | Exported Function | 0x000000018000d240 | 0x0000d240
`I_WebAuthNCtapEncodeMakeCredentialRpcRequest` | 5 (0x5) | Exported Function | 0x000000018000ada0 | 0x0000ada0
`WebAuthNAuthenticatorGetAssertion` | 6 (0x6) | Exported Function | 0x00000001800163b0 | 0x000163b0
`WebAuthNAuthenticatorMakeCredential` | 7 (0x7) | Exported Function | 0x0000000180015bc0 | 0x00015bc0
`WebAuthNCancelCurrentOperation` | 8 (0x8) | Exported Function | 0x0000000180016b70 | 0x00016b70
`WebAuthNCtapChangeClientPin` | 9 (0x9) | Exported Function | 0x000000018000c7d0 | 0x0000c7d0
`WebAuthNCtapChangeClientPinForSelectedDevice` | 10 (0xa) | Exported Function | 0x000000018000ea90 | 0x0000ea90
`WebAuthNCtapFreeSelectedDeviceInformation` | 11 (0xb) | Exported Function | 0x000000018000e130 | 0x0000e130
`WebAuthNCtapGetAssertion` | 12 (0xc) | Exported Function | 0x000000018000e160 | 0x0000e160
`WebAuthNCtapManageSelect` | 27 (0x1b) | Exported Function | 0x0000000180012b00 | 0x00012b00
`WebAuthNCtapGetSupportedTransports` | 13 (0xd) | Exported Function | 0x0000000180010250 | 0x00010250
`WebAuthNCtapIsStopSendCommandError` | 15 (0xf) | Exported Function | 0x000000018000f9c0 | 0x0000f9c0
`WebAuthNCtapMakeCredential` | 16 (0x10) | Exported Function | 0x000000018000ca70 | 0x0000ca70
`WebAuthNCtapManageAuthenticatePin` | 17 (0x11) | Exported Function | 0x0000000180012ec0 | 0x00012ec0
`WebAuthNCtapManageCancelEnrollFingerprint` | 18 (0x12) | Exported Function | 0x0000000180013680 | 0x00013680
`WebAuthNCtapManageChangePin` | 19 (0x13) | Exported Function | 0x00000001800131c0 | 0x000131c0
`WebAuthNCtapManageClose` | 20 (0x14) | Exported Function | 0x00000001800124b0 | 0x000124b0
`WebAuthNCtapManageDeleteCredential` | 21 (0x15) | Exported Function | 0x00000001800141f0 | 0x000141f0
`WebAuthNCtapManageEnrollFingerprint` | 22 (0x16) | Exported Function | 0x00000001800133f0 | 0x000133f0
`WebAuthNCtapManageFreeDisplayCredentials` | 23 (0x17) | Exported Function | 0x0000000180013c00 | 0x00013c00
`WebAuthNCtapManageGetDisplayCredentials` | 24 (0x18) | Exported Function | 0x0000000180013c60 | 0x00013c60
`WebAuthNCtapManageRemoveFingerprints` | 25 (0x19) | Exported Function | 0x0000000180013750 | 0x00013750
`WebAuthNCtapGetWnfLocalizedString` | 14 (0xe) | Exported Function | 0x0000000180014280 | 0x00014280
`WebAuthNIsUserVerifyingPlatformAuthenticatorAvailable` | 55 (0x37) | Exported Function | 0x000000018001be00 | 0x0001be00


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: webauthn.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/733a963b933ea83783351b70979ad70413fa93147d50a8aadd13efd3bbabe369/detection/





MIT License. Copyright (c) 2020 Strontic.


