---
title: cryptngc.dll | Microsoft Passport API
excerpt: What is cryptngc.dll?
---

# cryptngc.dll 

* File Path: `C:\Windows\system32\cryptngc.dll`
* Description: Microsoft Passport API

## Hashes

Type | Hash
-- | --
MD5 | `E6CE271B28CB12CC56197887D4747BB8`
SHA1 | `7ADEBC4B161B1DA5ECC8CCE1443E3B566501CD41`
SHA256 | `A236E4F6E432DB2EADB3EFB30AF87FBE3F49107957026F12E649B68A52427F58`
SHA384 | `24E222D07D82954992532897326E80CB1E6595E23085BF4851D218318E4921ED2BD35E2885EC84C8A747B5F83A43C4FB`
SHA512 | `13A57B545CC3B5DF323E8B1F51B273C21510C8D0253D1CC2455D0C7A346C811D0CC3B0FA43FA509BB27C88002404787088C02252FF40B9C1CC51E53ECECB2396`
SSDEEP | `6144:oJhQofICCJdJJoJVVZyXz2RycI+C3mqL63vY9tqRwUShEVJnwn9UBeFMAae9Jd2C:oJgBdJ6JMawcvCiYtqRwgnvlAh9J3k`
IMP | `D4A1699340B3F6B52AB184D316EA5702`
PESHA1 | `967AD9AD7BAEDCA24319702D1A4144204A283D9E`
PE256 | `9A875635CCAB55F666E92F1D50D8905BF474B0204FEBFC88AE9C5D27C5C3689E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FidoCreateCredential` | 1 (0x1) | Exported Function | 0x00000001800238c0 | 0x000238c0
`NgcGetPkcs7ChainBlobFromCertificateBlob` | 37 (0x25) | Exported Function | 0x0000000180026a90 | 0x00026a90
`NgcGetPolicy` | 38 (0x26) | Exported Function | 0x00000001800317c0 | 0x000317c0
`NgcGetPregenKeyState` | 39 (0x27) | Exported Function | 0x000000018003b0d0 | 0x0003b0d0
`NgcGetPregenUserKey` | 40 (0x28) | Exported Function | 0x000000018003b210 | 0x0003b210
`NgcGetSymmetricPopKeyTransportKey` | 41 (0x29) | Exported Function | 0x000000018002bba0 | 0x0002bba0
`NgcGetSymmetricPopKeyTransportKeyName` | 42 (0x2a) | Exported Function | 0x000000018002bda0 | 0x0002bda0
`NgcGetUserIdKeyCertificate` | 43 (0x2b) | Exported Function | 0x000000018003b3b0 | 0x0003b3b0
`NgcGetUserIdKeyContainerStatus` | 44 (0x2c) | Exported Function | 0x000000018003b510 | 0x0003b510
`NgcGetUserIdKeyName` | 45 (0x2d) | Exported Function | 0x000000018003b690 | 0x0003b690
`NgcGetUserIdKeyPublicKey` | 46 (0x2e) | Exported Function | 0x000000018003b700 | 0x0003b700
`NgcImportSymmetricPopKey` | 47 (0x2f) | Exported Function | 0x0000000180033440 | 0x00033440
`NgcIsAnyContainerInVsm` | 48 (0x30) | Exported Function | 0x0000000180031990 | 0x00031990
`NgcIsPinRemovable` | 49 (0x31) | Exported Function | 0x0000000180031a40 | 0x00031a40
`NgcNotifyVscProvisioned` | 50 (0x32) | Exported Function | 0x000000018002c6b0 | 0x0002c6b0
`NgcOpenUserIdKey` | 51 (0x33) | Exported Function | 0x000000018003b840 | 0x0003b840
`NgcPackAuthBuffer` | 52 (0x34) | Exported Function | 0x0000000180029b10 | 0x00029b10
`NgcPackPasswordChangeAuthBuffer` | 53 (0x35) | Exported Function | 0x0000000180029d10 | 0x00029d10
`NgcUnpackCredData` | 67 (0x43) | Exported Function | 0x0000000180029ea0 | 0x00029ea0
`NgcUnpackAuthBuffer` | 66 (0x42) | Exported Function | 0x0000000180029dc0 | 0x00029dc0
`NgcSignWithUserIdKeySilent` | 65 (0x41) | Exported Function | 0x000000018003ba40 | 0x0003ba40
`NgcSignWithUserIdKeyEx` | 64 (0x40) | Exported Function | 0x000000018003b9a0 | 0x0003b9a0
`NgcSignWithUserIdKeyAndPadding` | 63 (0x3f) | Exported Function | 0x000000018003b8f0 | 0x0003b8f0
`NgcSignWithUserIdKey` | 62 (0x3e) | Exported Function | 0x000000018003b8a0 | 0x0003b8a0
`NgcGetLogonDecryptionKeyNameForFirstLogonAfterUpgradeFromThreshold` | 36 (0x24) | Exported Function | 0x000000018003af70 | 0x0003af70
`NgcSignWithSymmetricPopKey` | 61 (0x3d) | Exported Function | 0x000000018000e670 | 0x0000e670
`NgcRemovePrebootProtector` | 59 (0x3b) | Exported Function | 0x00000001800320f0 | 0x000320f0
`NgcRemoveCompanionDeviceProtector` | 58 (0x3a) | Exported Function | 0x0000000180031f50 | 0x00031f50
`NgcRemoveBioProtector` | 57 (0x39) | Exported Function | 0x0000000180031db0 | 0x00031db0
`NgcQueryHardwarePolicy` | 56 (0x38) | Exported Function | 0x0000000180031d60 | 0x00031d60
`NgcQueryEnabled` | 55 (0x37) | Exported Function | 0x000000018000fcf0 | 0x0000fcf0
`NgcQueryEffectiveCertPolicy` | 54 (0x36) | Exported Function | 0x000000018002c840 | 0x0002c840
`NgcRenewKeyAttestation` | 60 (0x3c) | Exported Function | 0x0000000180026be0 | 0x00026be0
`NgcUnpackPasswordChangeAuthBuffer` | 68 (0x44) | Exported Function | 0x0000000180029f40 | 0x00029f40
`NgcGetLogonDecryptionKeyName` | 35 (0x23) | Exported Function | 0x000000018003ae10 | 0x0003ae10
`NgcGetKeyAttestationForUserIdKey2` | 33 (0x21) | Exported Function | 0x00000001800267c0 | 0x000267c0
`FidoGetCredential` | 2 (0x2) | Exported Function | 0x00000001800238c0 | 0x000238c0
`FidoSignWithCredential` | 3 (0x3) | Exported Function | 0x00000001800238c0 | 0x000238c0
`NgcAddBioProtector` | 4 (0x4) | Exported Function | 0x0000000180030270 | 0x00030270
`NgcAddCompanionDeviceProtector` | 5 (0x5) | Exported Function | 0x0000000180030430 | 0x00030430
`NgcAddPrebootProtector` | 6 (0x6) | Exported Function | 0x00000001800305e0 | 0x000305e0
`NgcCancelPendingUIRequest` | 7 (0x7) | Exported Function | 0x00000001800307c0 | 0x000307c0
`NgcChangePin` | 8 (0x8) | Exported Function | 0x0000000180030950 | 0x00030950
`NgcChangePinSilent` | 9 (0x9) | Exported Function | 0x0000000180030b00 | 0x00030b00
`NgcCreateContainer` | 10 (0xa) | Exported Function | 0x0000000180030cd0 | 0x00030cd0
`NgcCreateContainerSilent` | 11 (0xb) | Exported Function | 0x0000000180031170 | 0x00031170
`NgcCreateTicketForSmartCardKeyOperation` | 12 (0xc) | Exported Function | 0x000000018003d240 | 0x0003d240
`NgcCreateTicketForSmartCardVpn` | 13 (0xd) | Exported Function | 0x000000018003d300 | 0x0003d300
`NgcCreateUserIdKey` | 14 (0xe) | Exported Function | 0x000000018003a1d0 | 0x0003a1d0
`NgcCreateUserIdKeyEx` | 15 (0xf) | Exported Function | 0x000000018003a3f0 | 0x0003a3f0
`NgcCreateUserIdKeyHandle` | 16 (0x10) | Exported Function | 0x000000018003a620 | 0x0003a620
`NgcDecryptWithSymmetricPopKey` | 17 (0x11) | Exported Function | 0x0000000180008e70 | 0x00008e70
`NgcDecryptWithUserIdKey` | 18 (0x12) | Exported Function | 0x000000018003d040 | 0x0003d040
`NgcGetKeyAttestationForUserIdKey` | 32 (0x20) | Exported Function | 0x0000000180026770 | 0x00026770
`NgcGetKeyAttestationForContainerService` | 31 (0x1f) | Exported Function | 0x0000000180026490 | 0x00026490
`NgcGetEventInterface` | 30 (0x1e) | Exported Function | 0x0000000180013480 | 0x00013480
`NgcGetDefaultDecryptionKeyName` | 29 (0x1d) | Exported Function | 0x000000018003ab50 | 0x0003ab50
`NgcFreeEnumState` | 28 (0x1c) | Exported Function | 0x000000018003aa80 | 0x0003aa80
`NgcEnumUserIdKeys` | 27 (0x1b) | Exported Function | 0x000000018003a920 | 0x0003a920
`NgcGetKeyImplType` | 34 (0x22) | Exported Function | 0x000000018003ac90 | 0x0003ac90
`NgcEnumContainers` | 26 (0x1a) | Exported Function | 0x000000018000c0e0 | 0x0000c0e0
`NgcEncryptWithAsymmetricKey` | 24 (0x18) | Exported Function | 0x000000018003d0c0 | 0x0003d0c0
`NgcDeleteUserIdKey` | 23 (0x17) | Exported Function | 0x000000018003a7c0 | 0x0003a7c0
`NgcDeleteSymmetricPopKeyTransportKey` | 22 (0x16) | Exported Function | 0x000000018002ba60 | 0x0002ba60
`NgcDeleteContainerEx` | 21 (0x15) | Exported Function | 0x00000001800313e0 | 0x000313e0
`NgcDeleteContainer` | 20 (0x14) | Exported Function | 0x00000001800313d0 | 0x000313d0
`NgcDecryptWithUserIdKeySilent` | 19 (0x13) | Exported Function | 0x000000018003d080 | 0x0003d080
`NgcEncryptWithSymmetricPopKey` | 25 (0x19) | Exported Function | 0x00000001800332a0 | 0x000332a0
`NgcVerifyWithSymmetricPopKey` | 69 (0x45) | Exported Function | 0x0000000180009490 | 0x00009490


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptngc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a236e4f6e432db2eadb3efb30af87fbe3f49107957026f12e649b68a52427f58/detection/





MIT License. Copyright (c) 2020 Strontic.


