---
title: schannel.dll | TLS / SSL Security Provider
excerpt: What is schannel.dll?
---

# schannel.dll 

* File Path: `C:\Windows\SysWOW64\schannel.dll`
* Description: TLS / SSL Security Provider

## Hashes

Type | Hash
-- | --
MD5 | `8F4B975052E8E2C3CA18B8AFA09B5492`
SHA1 | `7EB55209141337E0EC175D19CA028CFFE1F00295`
SHA256 | `721FC000E0CDBDDA07965CCCF4DB47B6AFDFE0048F99AE14AB769AEE586727FF`
SHA384 | `8F98DC708247E52578727CAA83117CEEAFEF345F520069EF2C4DBC7A954C96C20E88CC3CCC67DAEB842DDBC7DF0E7883`
SHA512 | `984E4BA9FC1612467CD2DF2E5B58B116B8FAC718BA3691435689BD8931AF672CEA3B39D48D12E6172F5E33894BC5759E9A62707C5C874FF900A2436C301A3664`
SSDEEP | `12288:yPPjXJPWZO5sPXOlGWtMEIyOaZum7iOsA0i9wfQN6ZXUHaY/jTWgxftbOjQ:AjIatDH+mNqi9wf+vHL/9vbo`
IMP | `A0878B11F31B279538729A422C2F78F7`
PESHA1 | `A56A3B777824D33E0D18706EC66162DA9E1FA22E`
PE256 | `97EB2537D30345DBC080C537709B6FA6D00B5E3EF8CFC9F6C4ADF42750848A43`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 2 (0x2) | Exported Function | SSPICLI.AcceptSecurityContext | 0x00069177
`RevertSecurityContext` | 22 (0x16) | Exported Function | SSPICLI.RevertSecurityContext | 0x000695bd
`SealMessage` | 23 (0x17) | Exported Function | SSPICLI.SealMessage | 0x000695e7
`SpLsaModeInitialize` | 1 (0x1) | Exported Function | 0x58824290 | 0x00024290
`SpUserModeInitialize` | 24 (0x18) | Exported Function | 0x58808970 | 0x00008970
`SslCrackCertificate` | 25 (0x19) | Exported Function | 0x58839870 | 0x00039870
`SslEmptyCacheA` | 26 (0x1a) | Exported Function | 0x5883dfa0 | 0x0003dfa0
`QuerySecurityPackageInfoW` | 21 (0x15) | Exported Function | SSPICLI.QuerySecurityPackageInfoW | 0x00069585
`SslEmptyCacheW` | 27 (0x1b) | Exported Function | 0x5883e010 | 0x0003e010
`SslFreeCustomBuffer` | 29 (0x1d) | Exported Function | 0x58838aa0 | 0x00038aa0
`SslGenerateRandomBits` | 30 (0x1e) | Exported Function | 0x58839ae0 | 0x00039ae0
`SslGetExtensions` | 31 (0x1f) | Exported Function | 0x5883f290 | 0x0003f290
`SslGetMaximumKeySize` | 32 (0x20) | Exported Function | 0x58839b00 | 0x00039b00
`SslGetServerIdentity` | 33 (0x21) | Exported Function | 0x5883f690 | 0x0003f690
`SslLoadCertificate` | 34 (0x22) | Exported Function | 0x5881ac00 | 0x0001ac00
`SslFreeCertificate` | 28 (0x1c) | Exported Function | 0x58839ab0 | 0x00039ab0
`QuerySecurityPackageInfoA` | 20 (0x14) | Exported Function | SSPICLI.QuerySecurityPackageInfoA | 0x00069549
`QueryContextAttributesW` | 19 (0x13) | Exported Function | SSPICLI.QueryContextAttributesW | 0x0006950f
`QueryContextAttributesA` | 18 (0x12) | Exported Function | SSPICLI.QueryContextAttributesA | 0x000694d7
`AcquireCredentialsHandleA` | 3 (0x3) | Exported Function | SSPICLI.AcquireCredentialsHandleA | 0x000691af
`AcquireCredentialsHandleW` | 4 (0x4) | Exported Function | SSPICLI.AcquireCredentialsHandleW | 0x000691eb
`ApplyControlToken` | 5 (0x5) | Exported Function | SSPICLI.ApplyControlToken | 0x0006921f
`CompleteAuthToken` | 6 (0x6) | Exported Function | SSPICLI.CompleteAuthToken | 0x0006924b
`DeleteSecurityContext` | 7 (0x7) | Exported Function | SSPICLI.DeleteSecurityContext | 0x0006927b
`EnumerateSecurityPackagesA` | 8 (0x8) | Exported Function | SSPICLI.EnumerateSecurityPackagesA | 0x000692b4
`EnumerateSecurityPackagesW` | 9 (0x9) | Exported Function | SSPICLI.EnumerateSecurityPackagesW | 0x000692f2
`FreeContextBuffer` | 10 (0xa) | Exported Function | SSPICLI.FreeContextBuffer | 0x00069327
`FreeCredentialsHandle` | 11 (0xb) | Exported Function | SSPICLI.FreeCredentialsHandle | 0x00069357
`ImpersonateSecurityContext` | 12 (0xc) | Exported Function | SSPICLI.ImpersonateSecurityContext | 0x00069390
`InitializeSecurityContextA` | 15 (0xf) | Exported Function | SSPICLI.InitializeSecurityContextA | 0x0006943a
`InitializeSecurityContextW` | 16 (0x10) | Exported Function | SSPICLI.InitializeSecurityContextW | 0x00069478
`InitSecurityInterfaceA` | 13 (0xd) | Exported Function | SSPICLI.InitSecurityInterfaceA | 0x000693ca
`InitSecurityInterfaceW` | 14 (0xe) | Exported Function | SSPICLI.InitSecurityInterfaceW | 0x00069400
`MakeSignature` | 17 (0x11) | Exported Function | SSPICLI.MakeSignature | 0x000694a9
`UnsealMessage` | 35 (0x23) | Exported Function | SSPICLI.UnsealMessage | 0x000696db
`VerifySignature` | 36 (0x24) | Exported Function | SSPICLI.VerifySignature | 0x00069701


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: schannel.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/721fc000e0cdbdda07965cccf4db47b6afdfe0048f99ae14ab769aee586727ff/detection/


## Possible Misuse

*The following table contains possible examples of `schannel.dll` being misused. While `schannel.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s7 = "Microsoft DH SChannel Cryptographic Provider" fullword ascii /* PEStudio Blacklist: strings */ /* score: '5.00' */ /* Goodware String - occured 5 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | $s10 = "SCHANNEL.DLL" fullword ascii /* Goodware String - occured 6 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


