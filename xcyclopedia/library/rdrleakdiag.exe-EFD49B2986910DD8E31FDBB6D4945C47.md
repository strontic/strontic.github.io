﻿---
title: rdrleakdiag.exe | Microsoft Windows Resource Leak Diagnostic
excerpt: What is rdrleakdiag.exe?
---

# rdrleakdiag.exe 

* File Path: `C:\WINDOWS\system32\rdrleakdiag.exe`
* Description: Microsoft Windows Resource Leak Diagnostic

## Hashes

Type | Hash
-- | --
MD5 | `EFD49B2986910DD8E31FDBB6D4945C47`
SHA1 | `B4CB1973CB785DE16FC0E55FCB0ED5B278C28387`
SHA256 | `886F96D3C5EB4DD553BA71D8C32E3182BD1D0862B260A30D1136C232A7004CA3`
SHA384 | `17932140D3E9B0613B68C6BEF5F969843675FEF2CD9FC280D9F224BEDA5B5780F1D959C5E2A1085E3B1335D54D00AA28`
SHA512 | `E49AAD564E1DBDA65E968259B3628AB4A2FD6B313C0F3DDD81C0859575AA5F0C0738C5C271D24DC90B10C572D3C489DC40348B6825CD8078EB49022C71EC3EF4`
SSDEEP | `768:XLTJWbFuasCKqgvWLcSsUaF4I6FrYQJvI/pII6pNco2NnzlTqz:XQbFsLvWwVUH1FRmv6pNWzlT`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdrLeakDiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `rdrleakdiag.exe` being misused. While `rdrleakdiag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `title: Process Dump via RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `description: Detects a process memory dump performed by RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `OriginalFileName: RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


