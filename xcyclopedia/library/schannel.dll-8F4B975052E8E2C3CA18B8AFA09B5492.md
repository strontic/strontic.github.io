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

Function Name | Ordinal | Type
-- | -- | --
`SslCrackCertificate` | 25 | Exported Function
`SpUserModeInitialize` | 24 | Exported Function
`SslEmptyCacheW` | 27 | Exported Function
`SslEmptyCacheA` | 26 | Exported Function
`SpLsaModeInitialize` | 1 | Exported Function
`QuerySecurityPackageInfoW` | 21 | Exported Function
`QuerySecurityPackageInfoA` | 20 | Exported Function
`SealMessage` | 23 | Exported Function
`RevertSecurityContext` | 22 | Exported Function
`SslLoadCertificate` | 34 | Exported Function
`SslGetServerIdentity` | 33 | Exported Function
`VerifySignature` | 36 | Exported Function
`UnsealMessage` | 35 | Exported Function
`SslGetMaximumKeySize` | 32 | Exported Function
`SslFreeCustomBuffer` | 29 | Exported Function
`SslFreeCertificate` | 28 | Exported Function
`SslGetExtensions` | 31 | Exported Function
`SslGenerateRandomBits` | 30 | Exported Function
`EnumerateSecurityPackagesA` | 8 | Exported Function
`DeleteSecurityContext` | 7 | Exported Function
`FreeContextBuffer` | 10 | Exported Function
`EnumerateSecurityPackagesW` | 9 | Exported Function
`CompleteAuthToken` | 6 | Exported Function
`AcquireCredentialsHandleA` | 3 | Exported Function
`AcceptSecurityContext` | 2 | Exported Function
`ApplyControlToken` | 5 | Exported Function
`AcquireCredentialsHandleW` | 4 | Exported Function
`MakeSignature` | 17 | Exported Function
`InitSecurityInterfaceW` | 14 | Exported Function
`QueryContextAttributesW` | 19 | Exported Function
`QueryContextAttributesA` | 18 | Exported Function
`InitSecurityInterfaceA` | 13 | Exported Function
`ImpersonateSecurityContext` | 12 | Exported Function
`FreeCredentialsHandle` | 11 | Exported Function
`InitializeSecurityContextW` | 16 | Exported Function
`InitializeSecurityContextA` | 15 | Exported Function


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

*The following table contains possible examples of `schannel.dll` being misused. While `schannel.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s7 = "Microsoft DH SChannel Cryptographic Provider" fullword ascii /* PEStudio Blacklist: strings */ /* score: '5.00' */ /* Goodware String - occured 5 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | $s10 = "SCHANNEL.DLL" fullword ascii /* Goodware String - occured 6 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


