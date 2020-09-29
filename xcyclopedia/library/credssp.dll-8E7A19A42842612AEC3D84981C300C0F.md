---
title: credssp.dll | Credential Delegation Security Package
excerpt: What is credssp.dll?
---

# credssp.dll 

* File Path: `C:\Windows\system32\credssp.dll`
* Description: Credential Delegation Security Package

## Hashes

Type | Hash
-- | --
MD5 | `8E7A19A42842612AEC3D84981C300C0F`
SHA1 | `B157A164AF27E934C26DAB67A428D1549B4D337F`
SHA256 | `C7F5639750640E2862082AEA046802473E869A2C93491B66FF66EEAC5E3E7FB7`
SHA384 | `5BA48A770F005A95FAB0D165FB54B2DE2C6E806EAB173F579B570CF05E4EAA7D4D6365E2B841F843F2F076E7851E7045`
SHA512 | `876E36B2751513F8498B237754553ADF4C9D69454AAEFAA056ACC184489CE4FF40CA4C64399629280DC5BAAB33480021F609BD1550CE9A27A683FDB69BCBC8D5`
SSDEEP | `384:qaugSFKHQEhnW/pdijU3girHWTGMumGfNHiLYwjWyRW:qaubFKLU3gk7fNOYE`
IMP | `829E5A92DD0FC0A479B6EBF32DEEF462`
PESHA1 | `6FB9811FD7A7206D064296F10A0972BBE43B687C`
PE256 | `B38CD4027608AF65FC95D9D00C631864CDEBB4C1C260B3D3E548A81EEF4E3335`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`InitSecurityInterfaceW` | 1 (0x1) | Exported Function | 0x00000001800025d0 | 0x000025d0
`SpSetContextAttributesW` | 24 (0x18) | Exported Function | 0x0000000180002290 | 0x00002290
`SpRevertSecurityContext` | 23 (0x17) | Exported Function | 0x0000000180002410 | 0x00002410
`SpQuerySecurityPackageInfoW` | 22 (0x16) | Exported Function | 0x00000001800024c0 | 0x000024c0
`SpQuerySecurityContextToken` | 21 (0x15) | Exported Function | 0x0000000180002510 | 0x00002510
`SpQueryCredentialsAttributesW` | 20 (0x14) | Exported Function | 0x0000000180002290 | 0x00002290
`SpQueryContextAttributesW` | 19 (0x13) | Exported Function | 0x0000000180002160 | 0x00002160
`SpMakeSignature` | 18 (0x12) | Exported Function | 0x0000000180002440 | 0x00002440
`SpInitializeSecurityContextW` | 17 (0x11) | Exported Function | 0x00000001800012a0 | 0x000012a0
`SpImportSecurityContextW` | 16 (0x10) | Exported Function | 0x0000000180002290 | 0x00002290
`SpImpersonateSecurityContext` | 15 (0xf) | Exported Function | 0x00000001800023e0 | 0x000023e0
`SpFreeCredentialsHandle` | 14 (0xe) | Exported Function | 0x0000000180002210 | 0x00002210
`SpFreeContextBuffer` | 13 (0xd) | Exported Function | 0x00000001800024a0 | 0x000024a0
`SpExportSecurityContext` | 12 (0xc) | Exported Function | 0x0000000180002290 | 0x00002290
`SpEnumerateSecurityPackagesW` | 11 (0xb) | Exported Function | 0x0000000180002110 | 0x00002110
`SpEncryptMessage` | 10 (0xa) | Exported Function | 0x0000000180002540 | 0x00002540
`SpDeleteSecurityContext` | 9 (0x9) | Exported Function | 0x00000001800022a0 | 0x000022a0
`SpDecryptMessage` | 8 (0x8) | Exported Function | 0x0000000180002570 | 0x00002570
`SpCompleteAuthToken` | 7 (0x7) | Exported Function | 0x0000000180002290 | 0x00002290
`SpChangeAccountPasswordW` | 6 (0x6) | Exported Function | 0x0000000180002290 | 0x00002290
`SpApplyControlToken` | 5 (0x5) | Exported Function | 0x00000001800023b0 | 0x000023b0
`SpAddCredentialsW` | 4 (0x4) | Exported Function | 0x0000000180002290 | 0x00002290
`SpAcquireCredentialsHandleW` | 3 (0x3) | Exported Function | 0x0000000180001030 | 0x00001030
`SpAcceptSecurityContext` | 2 (0x2) | Exported Function | 0x0000000180001bc0 | 0x00001bc0
`SpSetCredentialsAttributesW` | 25 (0x19) | Exported Function | 0x00000001800025a0 | 0x000025a0
`SpVerifySignature` | 26 (0x1a) | Exported Function | 0x0000000180002470 | 0x00002470


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: credssp.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/c7f5639750640e2862082aea046802473e869a2c93491b66ff66eeac5e3e7fb7/detection/


## Possible Misuse

*The following table contains possible examples of `credssp.dll` being misused. While `credssp.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | * CredSSP:  Provides SSO and Network Level Authentication for Remote Desktop Services.(Citation: TechNet Blogs Credential Protection) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


