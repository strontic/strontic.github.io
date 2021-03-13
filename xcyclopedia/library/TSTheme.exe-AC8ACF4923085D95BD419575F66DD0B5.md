---
title: TSTheme.exe | TSTheme Server Module
excerpt: What is TSTheme.exe?
---

# TSTheme.exe 

* File Path: `C:\WINDOWS\system32\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `AC8ACF4923085D95BD419575F66DD0B5`
SHA1 | `9B290C213D7C2EF568D28E37C7EDFA464FC2FFB5`
SHA256 | `3F9BEFAD2FDAD5D2DC4CEBD61A909F45F5EF5E900256BBA51FE30D8FE2D63CB6`
SHA384 | `4DDE0056DAF5F896778F0F054E427547FAC44DA375603766C4571B565574FF8E25E22FA7356EE167E2397AF4621732DA`
SHA512 | `811CE88CD65308DC18641F28A102F3872763ABE9A5E68BDC797B815511DA414ED88A400E083253EA772A1F72E7AC5FA6B9F848D7025CFFB58712907ED7EA812E`
SSDEEP | `1536:NLjiAABY4fuwn3qag3i9qFnBVivyhyqv2:N3iE9G6JtnBVVYq+`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\tstheme.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


