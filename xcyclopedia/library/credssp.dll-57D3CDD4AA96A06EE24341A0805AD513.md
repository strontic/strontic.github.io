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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`InitSecurityInterfaceW` | 1 (0x1) | Exported Function | 0x100026b0 | 0x000026b0
`SpSetContextAttributesW` | 24 (0x18) | Exported Function | 0x100025b0 | 0x000025b0
`SpRevertSecurityContext` | 23 (0x17) | Exported Function | 0x100024c0 | 0x000024c0
`SpQuerySecurityPackageInfoW` | 22 (0x16) | Exported Function | 0x10002570 | 0x00002570
`SpQuerySecurityContextToken` | 21 (0x15) | Exported Function | 0x100025d0 | 0x000025d0
`SpQueryCredentialsAttributesW` | 20 (0x14) | Exported Function | 0x10002660 | 0x00002660
`SpQueryContextAttributesW` | 19 (0x13) | Exported Function | 0x100022a0 | 0x000022a0
`SpMakeSignature` | 18 (0x12) | Exported Function | 0x100024f0 | 0x000024f0
`SpInitializeSecurityContextW` | 17 (0x11) | Exported Function | 0x100016a0 | 0x000016a0
`SpImportSecurityContextW` | 16 (0x10) | Exported Function | 0x100025b0 | 0x000025b0
`SpImpersonateSecurityContext` | 15 (0xf) | Exported Function | 0x10002490 | 0x00002490
`SpFreeCredentialsHandle` | 14 (0xe) | Exported Function | 0x10002330 | 0x00002330
`SpFreeContextBuffer` | 13 (0xd) | Exported Function | 0x10002550 | 0x00002550
`SpExportSecurityContext` | 12 (0xc) | Exported Function | 0x100025b0 | 0x000025b0
`SpEnumerateSecurityPackagesW` | 11 (0xb) | Exported Function | 0x10002260 | 0x00002260
`SpEncryptMessage` | 10 (0xa) | Exported Function | 0x10002600 | 0x00002600
`SpDeleteSecurityContext` | 9 (0x9) | Exported Function | 0x100023a0 | 0x000023a0
`SpDecryptMessage` | 8 (0x8) | Exported Function | 0x10002630 | 0x00002630
`SpCompleteAuthToken` | 7 (0x7) | Exported Function | 0x10002390 | 0x00002390
`SpChangeAccountPasswordW` | 6 (0x6) | Exported Function | 0x100025c0 | 0x000025c0
`SpApplyControlToken` | 5 (0x5) | Exported Function | 0x10002460 | 0x00002460
`SpAddCredentialsW` | 4 (0x4) | Exported Function | 0x100025c0 | 0x000025c0
`SpAcquireCredentialsHandleW` | 3 (0x3) | Exported Function | 0x10001530 | 0x00001530
`SpAcceptSecurityContext` | 2 (0x2) | Exported Function | 0x10001dd0 | 0x00001dd0
`SpSetCredentialsAttributesW` | 25 (0x19) | Exported Function | 0x10002670 | 0x00002670
`SpVerifySignature` | 26 (0x1a) | Exported Function | 0x10002520 | 0x00002520


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

*The following table contains possible examples of `credssp.dll` being misused. While `credssp.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | * CredSSP:  Provides SSO and Network Level Authentication for Remote Desktop Services.(Citation: TechNet Blogs Credential Protection) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


