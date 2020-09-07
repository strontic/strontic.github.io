---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
---

# AppVClient.exe 

* File Path: `C:\WINDOWS\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `63D3B1DF43B6DFDB0EB9DCA99A323A5B`
SHA1 | `05C71C70BE50747C952632D5A2D159ED3EAD9240`
SHA256 | `AC0249B6B6A7E05CAFCFC490B84AE9A7DE5515B3A58EE6AC1CFEFABE790FB6A1`
SHA384 | `0DD9032E0FCA34A61503186D994A728FCE2044D22989921B78667499B1DAC9C93D63CE424294D708528FA407D8C6D845`
SHA512 | `185377DD726CF6530BCE294488BAFBE0C4FFD73AE51FCBB1293E021C61F1BBCBDAA44496E2123B360E54E451149280F00DB1599F641EE347E375E1F76DA91902`
SSDEEP | `12288:ruXOXTsbhYPll5gFampro20OcGNUbT2QTX2rXrj7MXky:6eXMhQOampr6gcX2rXrj7MUy`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.628 (WinBuild.160101.0800)
* Product Version: 10.0.18362.628
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `    - AppvClient` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


