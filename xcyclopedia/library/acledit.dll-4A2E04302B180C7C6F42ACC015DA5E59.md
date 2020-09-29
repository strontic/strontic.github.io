---
title: acledit.dll | Access Control List Editor
excerpt: What is acledit.dll?
---

# acledit.dll 

* File Path: `C:\Windows\SysWOW64\acledit.dll`
* Description: Access Control List Editor

## Hashes

Type | Hash
-- | --
MD5 | `4A2E04302B180C7C6F42ACC015DA5E59`
SHA1 | `3037D3DE78A1B8DC4B245DA8E462DD2D72E16CC2`
SHA256 | `21931694874BDB65642D6FEA9410298703836EC5D7258123A734DE7A0A30BDC7`
SHA384 | `05980F5E43F9F792637FD97794C0E44EBF109E5ACF35F56CF2F6D0D0D98E6B280E5FA9C49D0B3AD9A3ED16F7E1274776`
SHA512 | `C77A573BEE705F922DC0DE63531C70C2E94BE843829B59E2A21942B174633B69F189EA7D86000081059347BAF7AF60829F0BC96ED3685C4B10A4727ABFD5EDA3`
SSDEEP | `96:wUsyq7l8N0sN+CeuPzQ2+QZ3ehTDLUASwpBArn/6rstCPzCEW1YTWw9oOA:lq7l8N02Pz5+QxgZBAWDPzPW2TWRO`
IMP | `73B56FCAA206B14596A4684588E01D6D`
PESHA1 | `57F6CCA9AFEF25B2041D0CCCDE76BEE377054F1F`
PE256 | `1B93226F3F9657793EF02527A86A9B49DBD3F9032CCE5564AA6BE7A88940887D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllMain` | 5 (0x5) | Exported Function | 0x4b601390 | 0x00001390
`EditAuditInfo` | 1 (0x1) | Exported Function | 0x4b6014f0 | 0x000014f0
`EditOwnerInfo` | 2 (0x2) | Exported Function | 0x4b601470 | 0x00001470
`EditPermissionInfo` | 3 (0x3) | Exported Function | 0x4b601510 | 0x00001510
`FMExtensionProcW` | 4 (0x4) | Exported Function | 0x4b601530 | 0x00001530
`SedDiscretionaryAclEditor` | 6 (0x6) | Exported Function | 0x4b6014b0 | 0x000014b0
`SedSystemAclEditor` | 7 (0x7) | Exported Function | 0x4b6014d0 | 0x000014d0
`SedTakeOwnership` | 8 (0x8) | Exported Function | 0x4b601490 | 0x00001490


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: acledit.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/21931694874bdb65642d6fea9410298703836ec5d7258123a734de7a0a30bdc7/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\acledit.dll](acledit.dll-7C2B65E0756E0DC59E0BE5D9EFD25DA0.md) | 35

## Possible Misuse

*The following table contains possible examples of `acledit.dll` being misused. While `acledit.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.acledit.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


