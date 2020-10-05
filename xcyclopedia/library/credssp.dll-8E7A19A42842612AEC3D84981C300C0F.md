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

Function Name | Ordinal | Type
-- | -- | --
`SpInitializeSecurityContextW` | 17 | Exported Function
`SpMakeSignature` | 18 | Exported Function
`SpQueryContextAttributesW` | 19 | Exported Function
`SpFreeCredentialsHandle` | 14 | Exported Function
`SpImpersonateSecurityContext` | 15 | Exported Function
`SpImportSecurityContextW` | 16 | Exported Function
`SpQueryCredentialsAttributesW` | 20 | Exported Function
`SpSetContextAttributesW` | 24 | Exported Function
`SpSetCredentialsAttributesW` | 25 | Exported Function
`SpVerifySignature` | 26 | Exported Function
`SpQuerySecurityContextToken` | 21 | Exported Function
`SpQuerySecurityPackageInfoW` | 22 | Exported Function
`SpRevertSecurityContext` | 23 | Exported Function
`SpAddCredentialsW` | 4 | Exported Function
`SpApplyControlToken` | 5 | Exported Function
`SpChangeAccountPasswordW` | 6 | Exported Function
`InitSecurityInterfaceW` | 1 | Exported Function
`SpAcceptSecurityContext` | 2 | Exported Function
`SpAcquireCredentialsHandleW` | 3 | Exported Function
`SpCompleteAuthToken` | 7 | Exported Function
`SpEnumerateSecurityPackagesW` | 11 | Exported Function
`SpExportSecurityContext` | 12 | Exported Function
`SpFreeContextBuffer` | 13 | Exported Function
`SpDecryptMessage` | 8 | Exported Function
`SpDeleteSecurityContext` | 9 | Exported Function
`SpEncryptMessage` | 10 | Exported Function


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


