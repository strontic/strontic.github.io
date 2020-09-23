---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\WINDOWS\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `C77B003F8CABEB8FD401DD79F95979FB`
SHA1 | `CBF276A73880A1954D00EDA206443B4DC73BC191`
SHA256 | `958419E84B173BF13F68B1E69610FCC89D6703C8A253D5DA31D28B85758AB428`
SHA384 | `325EEEC2AE38BF0903DBAA643C284D20ED4CAC2BA8B8BB3C049CB1B6C4C0459C48A8A0F610DE7AA12E2C6574EE4FD028`
SHA512 | `98BC68DA3A01688A3605A013630239CC872145299ED21FF40A392C97295E8A89FB11D16C2A6D97162C49EB563BD584B19D4FFEAAFCF71D9EA12B1A9985C01510`
SSDEEP | `12288:Ehgtv0XM21gNHVvJRjxfeBKOkUbVagQ0kqj:x21m96/kAq0ki`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.657 (WinBuild.160101.0800)
* Product Version: 10.0.18362.657
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


