---
title: OSPPCEXT.DLL | Office Software Protection Platform Client Extension Dll
excerpt: What is OSPPCEXT.DLL?
---

# OSPPCEXT.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX64\Microsoft Shared\OfficeSoftwareProtectionPlatform\OSPPCEXT.DLL`
* Description: Office Software Protection Platform Client Extension Dll

## Hashes

Type | Hash
-- | --
MD5 | `4A2F0AB044A62C8D23A1D5BEC55B3AF5`
SHA1 | `8BEB6169ADEA56C087CD468546BA224C2F25DAF9`
SHA256 | `B0668DEEB6697D20E5052F55F6D86A864DFB18ADB440696BCB0DAB70CABD966A`
SHA384 | `2CDF49A12143B302AA904B10E01631F17DAB85F129E30EA98DE082D6B7D42426CC8AD7A6EA81DABB4D1325192D8063EC`
SHA512 | `50A76399C1EBFF8774984C262425F7F93FF32672D55308C2EE4900A7B60B6DEE0DD86181EE63ABB33BCCF77C10EEA490811DA3C2466BE93729E69299DC763CE4`
SSDEEP | `24576:+WdNnZeMCbnu3n8yIO9bqXV1VT6JFvULfY/DZeWFCPKmk4IEw2bfLqmMVQ6mbPF/:+gWb2n8yIyiVPh74Gzqmf6aGgKqd`
IMP | `8790983BD452894CFF427147D20F1CEF`
PESHA1 | `6730471F0FB40372057C73D72A5928D430029FE2`
PE256 | `1EE597D8AC223CEF3079F3A998D46DF16F2C28FB1DADC5E17769BFA92B1BA8AA`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SLGetTokenActivationCertificates` | 12 | Exported Function
`SLGetTokenActivationGrants` | 13 | Exported Function
`SLGetReferralInformation` | 10 | Exported Function
`SLGetServerStatus` | 11 | Exported Function
`SLSignTokenActivationChallenge` | 16 | Exported Function
`SLUninstallPackage` | 17 | Exported Function
`SLInitialize` | 14 | Exported Function
`SLInstallPackage` | 15 | Exported Function
`SLGetPackageToken` | 9 | Exported Function
`SLDepositTokenActivationResponse` | 3 | Exported Function
`SLFreeTokenActivationCertificates` | 4 | Exported Function
`SLAcquireGenuineTicket` | 1 | Exported Function
`SLActivateProduct` | 2 | Exported Function
`SLGetPackageProductKey` | 7 | Exported Function
`SLGetPackageProperties` | 8 | Exported Function
`SLFreeTokenActivationGrants` | 5 | Exported Function
`SLGenerateTokenActivationChallenge` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `6119CC93000100000066`
* Thumbprint: `19F8F76F4655074509769C20349FFAECCECD217D`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osppcext.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 15.0.0169.500 (win7sp1_gdr_oob_osppv2(oobla).120705-1649)
* Product Version: 15.0.0169.500
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b0668deeb6697d20e5052f55f6d86a864dfb18adb440696bcb0dab70cabd966a/detection/

## Possible Misuse

*The following table contains possible examples of `OSPPCEXT.DLL` being misused. While `OSPPCEXT.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"value": "osppcext.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `osppcext.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


