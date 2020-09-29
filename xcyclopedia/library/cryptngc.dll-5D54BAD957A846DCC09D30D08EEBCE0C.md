---
title: cryptngc.dll | Microsoft Passport API
excerpt: What is cryptngc.dll?
---

# cryptngc.dll 

* File Path: `C:\Windows\SysWOW64\cryptngc.dll`
* Description: Microsoft Passport API

## Hashes

Type | Hash
-- | --
MD5 | `5D54BAD957A846DCC09D30D08EEBCE0C`
SHA1 | `79FB66F4DCCE7CC058ABEAAA7BCEBB961C00F9B2`
SHA256 | `75EF3956597398CBC4C2A1F1745D796BCC06F46DB8FE58232168A20703FD031F`
SHA384 | `D03552CDDD68B51104FC926304CD9495F8D09ADE60192C3CD476456E8E40E17B6A346BE4840F8ED93F0859952198A022`
SHA512 | `0ADDDF96DA3D19868E80CC9AC8399178166068DFA3D56C089348B2DD5A502C678739168DA1979BF918834A1A9CBCFF27A7E55C638C25C63EE2A1486EBC5A83B4`
SSDEEP | `6144:IvDauIxDVMfMBfuUditqGLh8+7pH4tdPW6U6W5MhmjySD2SHs/HbR2OAsXlZhDNm:IvDaZhjBfuUdi3d8+B4y6U6W5MhmjySb`
IMP | `9FFCD90FB243FA9F2E3E1E6B53E012F0`
PESHA1 | `707FFA49C7F7CB8D1C380AFBFE5A0DA973D4A7B1`
PE256 | `4FCF6B928A6B777E1B273C5BE9B37CF93285BC03B19C2E716F694AA51DCE29B7`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FidoCreateCredential` | 1 (0x1) | Exported Function | 0x10029980 | 0x00029980
`NgcGetPkcs7ChainBlobFromCertificateBlob` | 37 (0x25) | Exported Function | 0x1002ba20 | 0x0002ba20
`NgcGetPolicy` | 38 (0x26) | Exported Function | 0x100331f0 | 0x000331f0
`NgcGetPregenKeyState` | 39 (0x27) | Exported Function | 0x10038b00 | 0x00038b00
`NgcGetPregenUserKey` | 40 (0x28) | Exported Function | 0x10038c20 | 0x00038c20
`NgcGetSymmetricPopKeyTransportKey` | 41 (0x29) | Exported Function | 0x1002edd0 | 0x0002edd0
`NgcGetSymmetricPopKeyTransportKeyName` | 42 (0x2a) | Exported Function | 0x1002ef70 | 0x0002ef70
`NgcGetUserIdKeyCertificate` | 43 (0x2b) | Exported Function | 0x10038d60 | 0x00038d60
`NgcGetUserIdKeyContainerStatus` | 44 (0x2c) | Exported Function | 0x10038e90 | 0x00038e90
`NgcGetUserIdKeyName` | 45 (0x2d) | Exported Function | 0x10038fb0 | 0x00038fb0
`NgcGetUserIdKeyPublicKey` | 46 (0x2e) | Exported Function | 0x10039000 | 0x00039000
`NgcImportSymmetricPopKey` | 47 (0x2f) | Exported Function | 0x100342c0 | 0x000342c0
`NgcIsAnyContainerInVsm` | 48 (0x30) | Exported Function | 0x10013090 | 0x00013090
`NgcIsPinRemovable` | 49 (0x31) | Exported Function | 0x10033330 | 0x00033330
`NgcNotifyVscProvisioned` | 50 (0x32) | Exported Function | 0x1002f430 | 0x0002f430
`NgcOpenUserIdKey` | 51 (0x33) | Exported Function | 0x100390f0 | 0x000390f0
`NgcPackAuthBuffer` | 52 (0x34) | Exported Function | 0x1002da20 | 0x0002da20
`NgcPackPasswordChangeAuthBuffer` | 53 (0x35) | Exported Function | 0x1002dba0 | 0x0002dba0
`NgcUnpackCredData` | 67 (0x43) | Exported Function | 0x1002dce0 | 0x0002dce0
`NgcUnpackAuthBuffer` | 66 (0x42) | Exported Function | 0x1002dc30 | 0x0002dc30
`NgcSignWithUserIdKeySilent` | 65 (0x41) | Exported Function | 0x10039250 | 0x00039250
`NgcSignWithUserIdKeyEx` | 64 (0x40) | Exported Function | 0x100391e0 | 0x000391e0
`NgcSignWithUserIdKeyAndPadding` | 63 (0x3f) | Exported Function | 0x10039170 | 0x00039170
`NgcSignWithUserIdKey` | 62 (0x3e) | Exported Function | 0x10039140 | 0x00039140
`NgcGetLogonDecryptionKeyNameForFirstLogonAfterUpgradeFromThreshold` | 36 (0x24) | Exported Function | 0x100389f0 | 0x000389f0
`NgcSignWithSymmetricPopKey` | 61 (0x3d) | Exported Function | 0x10015740 | 0x00015740
`NgcRemovePrebootProtector` | 59 (0x3b) | Exported Function | 0x10033820 | 0x00033820
`NgcRemoveCompanionDeviceProtector` | 58 (0x3a) | Exported Function | 0x100336f0 | 0x000336f0
`NgcRemoveBioProtector` | 57 (0x39) | Exported Function | 0x100335c0 | 0x000335c0
`NgcQueryHardwarePolicy` | 56 (0x38) | Exported Function | 0x10033590 | 0x00033590
`NgcQueryEnabled` | 55 (0x37) | Exported Function | 0x100131c0 | 0x000131c0
`NgcQueryEffectiveCertPolicy` | 54 (0x36) | Exported Function | 0x1002f530 | 0x0002f530
`NgcRenewKeyAttestation` | 60 (0x3c) | Exported Function | 0x1002bb40 | 0x0002bb40
`NgcUnpackPasswordChangeAuthBuffer` | 68 (0x44) | Exported Function | 0x1002dd70 | 0x0002dd70
`NgcGetLogonDecryptionKeyName` | 35 (0x23) | Exported Function | 0x100388e0 | 0x000388e0
`NgcGetKeyAttestationForUserIdKey2` | 32 (0x20) | Exported Function | 0x1002b790 | 0x0002b790
`FidoGetCredential` | 2 (0x2) | Exported Function | 0x10029990 | 0x00029990
`FidoSignWithCredential` | 3 (0x3) | Exported Function | 0x100299a0 | 0x000299a0
`NgcAddBioProtector` | 4 (0x4) | Exported Function | 0x10032220 | 0x00032220
`NgcAddCompanionDeviceProtector` | 5 (0x5) | Exported Function | 0x10032360 | 0x00032360
`NgcAddPrebootProtector` | 6 (0x6) | Exported Function | 0x10032490 | 0x00032490
`NgcCancelPendingUIRequest` | 7 (0x7) | Exported Function | 0x100325e0 | 0x000325e0
`NgcChangePin` | 8 (0x8) | Exported Function | 0x10032710 | 0x00032710
`NgcChangePinSilent` | 9 (0x9) | Exported Function | 0x10032840 | 0x00032840
`NgcCreateContainer` | 10 (0xa) | Exported Function | 0x10032980 | 0x00032980
`NgcCreateContainerSilent` | 11 (0xb) | Exported Function | 0x10032ce0 | 0x00032ce0
`NgcCreateTicketForSmartCardKeyOperation` | 12 (0xc) | Exported Function | 0x1003a2a0 | 0x0003a2a0
`NgcCreateTicketForSmartCardVpn` | 13 (0xd) | Exported Function | 0x1003a310 | 0x0003a310
`NgcCreateUserIdKey` | 14 (0xe) | Exported Function | 0x10037ec0 | 0x00037ec0
`NgcCreateUserIdKeyEx` | 15 (0xf) | Exported Function | 0x10038080 | 0x00038080
`NgcCreateUserIdKeyHandle` | 16 (0x10) | Exported Function | 0x10038260 | 0x00038260
`NgcDecryptWithSymmetricPopKey` | 17 (0x11) | Exported Function | 0x10012a50 | 0x00012a50
`NgcDecryptWithUserIdKey` | 18 (0x12) | Exported Function | 0x1003a110 | 0x0003a110
`NgcGetKeyAttestationForUserIdKey` | 33 (0x21) | Exported Function | 0x1002b9f0 | 0x0002b9f0
`NgcGetKeyAttestationForContainerService` | 31 (0x1f) | Exported Function | 0x1002b570 | 0x0002b570
`NgcGetEventInterface` | 30 (0x1e) | Exported Function | 0x1001aa50 | 0x0001aa50
`NgcGetDefaultDecryptionKeyName` | 29 (0x1d) | Exported Function | 0x100386a0 | 0x000386a0
`NgcFreeEnumState` | 28 (0x1c) | Exported Function | 0x10038600 | 0x00038600
`NgcEnumUserIdKeys` | 27 (0x1b) | Exported Function | 0x100384d0 | 0x000384d0
`NgcGetKeyImplType` | 34 (0x22) | Exported Function | 0x10038790 | 0x00038790
`NgcEnumContainers` | 26 (0x1a) | Exported Function | 0x10013b20 | 0x00013b20
`NgcEncryptWithAsymmetricKey` | 24 (0x18) | Exported Function | 0x1003a170 | 0x0003a170
`NgcDeleteUserIdKey` | 23 (0x17) | Exported Function | 0x100383c0 | 0x000383c0
`NgcDeleteSymmetricPopKeyTransportKey` | 22 (0x16) | Exported Function | 0x1002ece0 | 0x0002ece0
`NgcDeleteContainerEx` | 21 (0x15) | Exported Function | 0x10032eb0 | 0x00032eb0
`NgcDeleteContainer` | 20 (0x14) | Exported Function | 0x10032e90 | 0x00032e90
`NgcDecryptWithUserIdKeySilent` | 19 (0x13) | Exported Function | 0x1003a140 | 0x0003a140
`NgcEncryptWithSymmetricPopKey` | 25 (0x19) | Exported Function | 0x10034180 | 0x00034180
`NgcVerifyWithSymmetricPopKey` | 69 (0x45) | Exported Function | 0x100126d0 | 0x000126d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptngc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/75ef3956597398cbc4c2a1f1745d796bcc06f46db8fe58232168a20703fd031f/detection/





MIT License. Copyright (c) 2020 Strontic.


