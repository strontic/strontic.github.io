---
title: schannel.dll | TLS / SSL Security Provider
excerpt: What is schannel.dll?
---

# schannel.dll 

* File Path: `C:\Windows\system32\schannel.dll`
* Description: TLS / SSL Security Provider

## Hashes

Type | Hash
-- | --
MD5 | `B992E335A9868FE4FB7E05B1EC660F90`
SHA1 | `3BD62EAE693DDB8548206D715DCF984D5BE344C3`
SHA256 | `9A7076CCE1B58F4A8BCFF3C95041B19210920A79A75399BA83EFE42F04D7C6FC`
SHA384 | `E55021D4A08534DC526FFA568630CCB6E5FE98F838D9EE69E49E69AA1C7C9A3B501CE477DCE9E3E79E9C4406F882DBA7`
SHA512 | `E9C99F61A7E58EED87614BCADA79E11673F657006720268FF760324CA30E7E5AAC089DF6A1EEC7BC2E570B00FB485FA019F96399B5930DDEE29AACDEF8B9E109`
SSDEEP | `6144:hu8G5Yvoa6kXHsOrr4ZhjRhTtIGEPb91V2U4gkPWVEjlP2rutuT4oC/6B8c+fVmR:ha8oDqPiHCGED91VtlaToKtJ66pkK`
IMP | `A8008D74F52F27906ED8B28403843059`
PESHA1 | `2633E2842F8A80AC5F7F7200CAD33AADE4EEE12B`
PE256 | `2B300EC4EAF919F04E1581464582F04CBAF4279928B32DA327B20CCFB58BBC8B`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 2 (0x2) | Exported Function | SSPICLI.AcceptSecurityContext | 0x00081b27
`RevertSecurityContext` | 22 (0x16) | Exported Function | SSPICLI.RevertSecurityContext | 0x00081f6d
`SealMessage` | 23 (0x17) | Exported Function | SSPICLI.SealMessage | 0x00081f97
`SpLsaModeInitialize` | 1 (0x1) | Exported Function | 0x0000000180025e00 | 0x00025e00
`SpUserModeInitialize` | 24 (0x18) | Exported Function | 0x0000000180013570 | 0x00013570
`SslCrackCertificate` | 25 (0x19) | Exported Function | 0x000000018003ee00 | 0x0003ee00
`SslEmptyCacheA` | 26 (0x1a) | Exported Function | 0x0000000180044980 | 0x00044980
`QuerySecurityPackageInfoW` | 21 (0x15) | Exported Function | SSPICLI.QuerySecurityPackageInfoW | 0x00081f35
`SslEmptyCacheW` | 27 (0x1b) | Exported Function | 0x0000000180044a20 | 0x00044a20
`SslFreeCustomBuffer` | 29 (0x1d) | Exported Function | 0x000000018003de10 | 0x0003de10
`SslGenerateRandomBits` | 30 (0x1e) | Exported Function | 0x000000018003f110 | 0x0003f110
`SslGetExtensions` | 31 (0x1f) | Exported Function | 0x0000000180046250 | 0x00046250
`SslGetMaximumKeySize` | 32 (0x20) | Exported Function | 0x000000018003f120 | 0x0003f120
`SslGetServerIdentity` | 33 (0x21) | Exported Function | 0x0000000180046740 | 0x00046740
`SslLoadCertificate` | 34 (0x22) | Exported Function | 0x0000000180017420 | 0x00017420
`SslFreeCertificate` | 28 (0x1c) | Exported Function | 0x000000018003f0e0 | 0x0003f0e0
`QuerySecurityPackageInfoA` | 20 (0x14) | Exported Function | SSPICLI.QuerySecurityPackageInfoA | 0x00081ef9
`QueryContextAttributesW` | 19 (0x13) | Exported Function | SSPICLI.QueryContextAttributesW | 0x00081ebf
`QueryContextAttributesA` | 18 (0x12) | Exported Function | SSPICLI.QueryContextAttributesA | 0x00081e87
`AcquireCredentialsHandleA` | 3 (0x3) | Exported Function | SSPICLI.AcquireCredentialsHandleA | 0x00081b5f
`AcquireCredentialsHandleW` | 4 (0x4) | Exported Function | SSPICLI.AcquireCredentialsHandleW | 0x00081b9b
`ApplyControlToken` | 5 (0x5) | Exported Function | SSPICLI.ApplyControlToken | 0x00081bcf
`CompleteAuthToken` | 6 (0x6) | Exported Function | SSPICLI.CompleteAuthToken | 0x00081bfb
`DeleteSecurityContext` | 7 (0x7) | Exported Function | SSPICLI.DeleteSecurityContext | 0x00081c2b
`EnumerateSecurityPackagesA` | 8 (0x8) | Exported Function | SSPICLI.EnumerateSecurityPackagesA | 0x00081c64
`EnumerateSecurityPackagesW` | 9 (0x9) | Exported Function | SSPICLI.EnumerateSecurityPackagesW | 0x00081ca2
`FreeContextBuffer` | 10 (0xa) | Exported Function | SSPICLI.FreeContextBuffer | 0x00081cd7
`FreeCredentialsHandle` | 11 (0xb) | Exported Function | SSPICLI.FreeCredentialsHandle | 0x00081d07
`ImpersonateSecurityContext` | 12 (0xc) | Exported Function | SSPICLI.ImpersonateSecurityContext | 0x00081d40
`InitializeSecurityContextA` | 15 (0xf) | Exported Function | SSPICLI.InitializeSecurityContextA | 0x00081dea
`InitializeSecurityContextW` | 16 (0x10) | Exported Function | SSPICLI.InitializeSecurityContextW | 0x00081e28
`InitSecurityInterfaceA` | 13 (0xd) | Exported Function | SSPICLI.InitSecurityInterfaceA | 0x00081d7a
`InitSecurityInterfaceW` | 14 (0xe) | Exported Function | SSPICLI.InitSecurityInterfaceW | 0x00081db0
`MakeSignature` | 17 (0x11) | Exported Function | SSPICLI.MakeSignature | 0x00081e59
`UnsealMessage` | 35 (0x23) | Exported Function | SSPICLI.UnsealMessage | 0x0008208b
`VerifySignature` | 36 (0x24) | Exported Function | SSPICLI.VerifySignature | 0x000820b1


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: schannel.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/9a7076cce1b58f4a8bcff3c95041b19210920a79a75399ba83efe42f04d7c6fc/detection/


## Possible Misuse

*The following table contains possible examples of `schannel.dll` being misused. While `schannel.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s7 = "Microsoft DH SChannel Cryptographic Provider" fullword ascii /* PEStudio Blacklist: strings */ /* score: '5.00' */ /* Goodware String - occured 5 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | $s10 = "SCHANNEL.DLL" fullword ascii /* Goodware String - occured 6 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


