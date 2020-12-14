---
title: credssp.dll | Credential Delegation Security Package
excerpt: What is credssp.dll?
---

# credssp.dll 

* File Path: `C:\Windows\SysWOW64\credssp.dll`
* Description: Credential Delegation Security Package

## Hashes

Type | Hash
-- | --
MD5 | `57D3CDD4AA96A06EE24341A0805AD513`
SHA1 | `4352D4A338B254AC25AF554ED9C9FE28ABB5F2A8`
SHA256 | `1BE265CF483CC9A9DC68287CDD212F0D91ED842E22A20740D291B567DBB423D3`
SHA384 | `A33AA1ACE4337FCA0F9D38CEBB4357ECFBADD2B899F78A21FE8018A4A045AA1E2B962671B488D5D98D4E28D5C0D2412A`
SHA512 | `4DA19EE3E7B5FB45DF1EFE6543190E71A5B4C2186FFCCDC63AB0F9542BE247F13C558F67FDC12561820F7C4D6F354236C4923327CA8B707C6F40FD21D000B923`
SSDEEP | `384:JTRnMmVMY6jzpGwdfooCh0J+QQAxx3/9yZgTWyRWV:NRMmSGhhr2xgZY4`
IMP | `9B9CD3160C44FB25ED87C8B700BCC9DC`
PESHA1 | `AD990FBB5D5B37C041DDA7CC8A643D6229B7C5C5`
PE256 | `4D8A663D81355D04A1149B5130B2AD6E07050C26B27F37367EAEAD4DFAC4D887`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/1be265cf483cc9a9dc68287cdd212f0d91ed842e22a20740d291b567dbb423d3/detection/


## Possible Misuse

*The following table contains possible examples of `credssp.dll` being misused. While `credssp.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | * CredSSP:  Provides SSO and Network Level Authentication for Remote Desktop Services.(Citation: TechNet Blogs Credential Protection) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


