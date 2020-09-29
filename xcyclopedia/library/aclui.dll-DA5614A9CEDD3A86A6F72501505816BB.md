---
title: aclui.dll | Security Descriptor Editor
excerpt: What is aclui.dll?
---

# aclui.dll 

* File Path: `C:\Windows\SysWOW64\aclui.dll`
* Description: Security Descriptor Editor

## Hashes

Type | Hash
-- | --
MD5 | `DA5614A9CEDD3A86A6F72501505816BB`
SHA1 | `2C78A725271B0FDC184175D7D9DFDFA03B8DA917`
SHA256 | `92FB0638999CDD9F6AB468418CE99059F217D03F3771EC9BD3B38748B775D145`
SHA384 | `D02A95A8273249C8DB65FC5A4FD63B1259CA1651F902FFD1613DD608A66F0A1BCBB0B6879DFEFE0F3696D6D6D37ADB2A`
SHA512 | `5D1DCCA922C5E5AE1C7117F0210146C3241ECD09247667FDA8726B4DE60EAB28063878EA9BB69958BC0B74BB13276509A1EA1B4C923598A4D5EBB963BCEA8A0B`
SSDEEP | `12288:unLFYS8IASov7ccDYrdfU2ZBROkymfpDqL+QnDM:2hrAredbZirmxcnD`
IMP | `0314D8DBE7713E425B31788A84D5FD91`
PESHA1 | `AEE5F469E54A8B2ACCE49917E215639E19B84F3B`
PE256 | `2E98D52A3DEEBF45EF0BA12AD8E64135D2D4E076C72BBFAA05F7B8E962FEA7DD`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateSecurityPage` | 1 (0x1) | Exported Function | 0x5d53fec0 | 0x0003fec0
`EditConditionalAceClaims` | 5 (0x5) | Exported Function | 0x5d5378a0 | 0x000378a0
`EditResourceCondition` | 4 (0x4) | Exported Function | 0x5d537c20 | 0x00037c20
`EditSecurity` | 2 (0x2) | Exported Function | 0x5d53ffc0 | 0x0003ffc0
`EditSecurityAdvanced` | 3 (0x3) | Exported Function | 0x5d51ebe0 | 0x0001ebe0
`GetLocalizedStringForCondition` | 6 (0x6) | Exported Function | 0x5d51c620 | 0x0001c620
`GetTlsIndexForClaimDictionary` | 7 (0x7) | Exported Function | 0x5d52a380 | 0x0002a380
`IID_ISecurityInformation` | 16 (0x10) | Exported Function | 0x5d508010 | 0x00008010


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: aclui.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/92fb0638999cdd9f6ab468418ce99059f217d03f3771ec9bd3b38748b775d145/detection/


## Possible Misuse

*The following table contains possible examples of `aclui.dll` being misused. While `aclui.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`aclui.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


