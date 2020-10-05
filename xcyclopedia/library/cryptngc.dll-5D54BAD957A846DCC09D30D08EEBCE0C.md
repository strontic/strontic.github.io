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

Function Name | Ordinal | Type
-- | -- | --
`NgcImportSymmetricPopKey` | 47 | Exported Function
`NgcIsAnyContainerInVsm` | 48 | Exported Function
`NgcGetUserIdKeyName` | 45 | Exported Function
`NgcGetUserIdKeyPublicKey` | 46 | Exported Function
`NgcOpenUserIdKey` | 51 | Exported Function
`NgcPackAuthBuffer` | 52 | Exported Function
`NgcIsPinRemovable` | 49 | Exported Function
`NgcNotifyVscProvisioned` | 50 | Exported Function
`NgcGetUserIdKeyContainerStatus` | 44 | Exported Function
`NgcGetPolicy` | 38 | Exported Function
`NgcGetPregenKeyState` | 39 | Exported Function
`NgcGetLogonDecryptionKeyNameForFirstLogonAfterUpgradeFromThreshold` | 36 | Exported Function
`NgcGetPkcs7ChainBlobFromCertificateBlob` | 37 | Exported Function
`NgcGetSymmetricPopKeyTransportKeyName` | 42 | Exported Function
`NgcGetUserIdKeyCertificate` | 43 | Exported Function
`NgcGetPregenUserKey` | 40 | Exported Function
`NgcGetSymmetricPopKeyTransportKey` | 41 | Exported Function
`NgcSignWithUserIdKeyEx` | 64 | Exported Function
`NgcSignWithUserIdKeySilent` | 65 | Exported Function
`NgcSignWithUserIdKey` | 62 | Exported Function
`NgcSignWithUserIdKeyAndPadding` | 63 | Exported Function
`NgcUnpackPasswordChangeAuthBuffer` | 68 | Exported Function
`NgcVerifyWithSymmetricPopKey` | 69 | Exported Function
`NgcUnpackAuthBuffer` | 66 | Exported Function
`NgcUnpackCredData` | 67 | Exported Function
`NgcSignWithSymmetricPopKey` | 61 | Exported Function
`NgcQueryEnabled` | 55 | Exported Function
`NgcQueryHardwarePolicy` | 56 | Exported Function
`NgcPackPasswordChangeAuthBuffer` | 53 | Exported Function
`NgcQueryEffectiveCertPolicy` | 54 | Exported Function
`NgcRemovePrebootProtector` | 59 | Exported Function
`NgcRenewKeyAttestation` | 60 | Exported Function
`NgcRemoveBioProtector` | 57 | Exported Function
`NgcRemoveCompanionDeviceProtector` | 58 | Exported Function
`NgcGetLogonDecryptionKeyName` | 35 | Exported Function
`NgcCreateTicketForSmartCardKeyOperation` | 12 | Exported Function
`NgcCreateTicketForSmartCardVpn` | 13 | Exported Function
`NgcCreateContainer` | 10 | Exported Function
`NgcCreateContainerSilent` | 11 | Exported Function
`NgcCreateUserIdKeyHandle` | 16 | Exported Function
`NgcDecryptWithSymmetricPopKey` | 17 | Exported Function
`NgcCreateUserIdKey` | 14 | Exported Function
`NgcCreateUserIdKeyEx` | 15 | Exported Function
`NgcChangePinSilent` | 9 | Exported Function
`FidoSignWithCredential` | 3 | Exported Function
`NgcAddBioProtector` | 4 | Exported Function
`FidoCreateCredential` | 1 | Exported Function
`FidoGetCredential` | 2 | Exported Function
`NgcCancelPendingUIRequest` | 7 | Exported Function
`NgcChangePin` | 8 | Exported Function
`NgcAddCompanionDeviceProtector` | 5 | Exported Function
`NgcAddPrebootProtector` | 6 | Exported Function
`NgcGetDefaultDecryptionKeyName` | 29 | Exported Function
`NgcGetEventInterface` | 30 | Exported Function
`NgcEnumUserIdKeys` | 27 | Exported Function
`NgcFreeEnumState` | 28 | Exported Function
`NgcGetKeyAttestationForUserIdKey2` | 32 | Exported Function
`NgcGetKeyImplType` | 34 | Exported Function
`NgcGetKeyAttestationForContainerService` | 31 | Exported Function
`NgcGetKeyAttestationForUserIdKey` | 33 | Exported Function
`NgcEnumContainers` | 26 | Exported Function
`NgcDeleteContainer` | 20 | Exported Function
`NgcDeleteContainerEx` | 21 | Exported Function
`NgcDecryptWithUserIdKey` | 18 | Exported Function
`NgcDecryptWithUserIdKeySilent` | 19 | Exported Function
`NgcEncryptWithAsymmetricKey` | 24 | Exported Function
`NgcEncryptWithSymmetricPopKey` | 25 | Exported Function
`NgcDeleteSymmetricPopKeyTransportKey` | 22 | Exported Function
`NgcDeleteUserIdKey` | 23 | Exported Function


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


