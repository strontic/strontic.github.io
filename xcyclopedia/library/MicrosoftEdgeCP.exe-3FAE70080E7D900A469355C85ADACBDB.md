---
title: MicrosoftEdgeCP.exe | Microsoft Edge Content Process
---

# MicrosoftEdgeCP.exe 

* File Path: `C:\windows\system32\MicrosoftEdgeCP.exe`
* Description: Microsoft Edge Content Process

## Hashes

Type | Hash
-- | --
MD5 | `3FAE70080E7D900A469355C85ADACBDB`
SHA1 | `DEA5960571532F73D886F5DD79B0F7EED6F10582`
SHA256 | `34B6D32D2345DB5DFE803573F4AA74479EA961004B2F72D25A486D55369AECD8`
SHA384 | `A0AC924BDB2BC8B264BE59D9A3C29B7A511D0BB1A603319215849FDFC589F8A61A19248E3256A0CBC2EFD913A67B2E01`
SHA512 | `C8909FAD5F3FCEAB7A825C30B033844645E49F171C285A560CF8E0DFD0D848356B8E2CC0DF8019E42B1EFE69623B715BF3237D7DD42D3EC63A462D2682711ABD`
SSDEEP | `1536:zermIcat/7LnbR8l/DNRo04HwnVC8AknP8RsK:zeryK3V8l/804oV3TP8Rs`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeCP.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - '\microsoftedgecp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


