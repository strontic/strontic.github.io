---
title: MicrosoftEdgeSH.exe | Microsoft Edge Web Platform
---

# MicrosoftEdgeSH.exe 

* File Path: `C:\Windows\system32\MicrosoftEdgeSH.exe`
* Description: Microsoft Edge Web Platform

## Hashes

Type | Hash
-- | --
MD5 | `C2599AACDB852A0E1BCB2BA6E2CA348E`
SHA1 | `2FD233F65D589BF6C4994818C3336BC8679D7CE1`
SHA256 | `E5D93718F0905B341D6FC68399257D88C56479B2A7FFB253FD88A405E6ED6E74`
SHA384 | `AB8A4059E1B3188E637C3D52642F0C71DB63799F9B13465DA9F87B1BCE03C90C5FEC6C9D4836ED981D9319AAFAE73938`
SHA512 | `ADB69E63122CD69240FB577016C77EB58A18D35528D173E31AE3E6820327606A9B83312AA308D808A635103080E6B7A00D2842F6334A7D0E6A63079ECBAC97F6`
SSDEEP | `768:el/wBBBMcf1XIOOBTn9DAvt8DQgfMycTEYL67rNFPWk+iVgkV:el/wzfhFOBThDUygL67xpr+iVgu`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeSH.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeSH.exe` being misused. While `MicrosoftEdgeSH.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - "MicrosoftEdgeSH.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


