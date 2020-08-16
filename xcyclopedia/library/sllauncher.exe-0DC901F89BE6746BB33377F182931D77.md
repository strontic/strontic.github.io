---
title: sllauncher.exe | Microsoft Silverlight Out-of-Browser Launcher
---

# sllauncher.exe 

* File Path: `C:\Program Files (x86)\Microsoft Silverlight\sllauncher.exe`
* Description: Microsoft Silverlight Out-of-Browser Launcher

## Screenshot

![sllauncher.exe](screenshots/sllauncher.exe-0DC901F89BE6746BB33377F182931D77-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `0DC901F89BE6746BB33377F182931D77`
SHA1 | `A48616ABB7284D147C2256A35FDC546E39FB65B3`
SHA256 | `29AA9AF2CA286A78F7D00F279C7F0C75462DFA5B008C122555BC97C948FBAED0`
SHA384 | `774C2100157F80552DD931671D4E80C2D6B5E96A132046887B31E28C633E37BDE26FA524AE998783B1D562F6A7066607`
SHA512 | `B1C8E741B846AAC8E43A4ECE2CC16825FE5DF3C2D2A2E4C3A3042FE05C110F70AE9CB590AF8EC4D900A11AD046BD9C0EFBB135A0E4C1BC9BAA44425FCCBF8728`
SSDEEP | `6144:vuhSmHEHYtyqe8nO6pPLJSq+iCZu5sfjkd9Eb1lqxlKsR:G8z4bjmZu5sfjkd9EzK5R`

## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sllauncher.exe
* Product Name: Microsoft Silverlight
* Company Name: Microsoft Corporation
* File Version: 5.1.50918.0
* Product Version: 5.1.50918.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sllauncher.exe` being misused. While `sllauncher.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_emissarypanda_sep19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_emissarypanda_sep19.yml) | `title: Emissary Panda Malware SLLauncher` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_emissarypanda_sep19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_emissarypanda_sep19.yml) | `        ParentImage: '*\sllauncher.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


