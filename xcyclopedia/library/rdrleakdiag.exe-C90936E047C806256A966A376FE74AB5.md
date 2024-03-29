﻿---
title: rdrleakdiag.exe | Microsoft Windows Resource Leak Diagnostic
excerpt: What is rdrleakdiag.exe?
---

# rdrleakdiag.exe 

* File Path: `C:\Windows\system32\rdrleakdiag.exe`
* Description: Microsoft Windows Resource Leak Diagnostic

## Hashes

Type | Hash
-- | --
MD5 | `C90936E047C806256A966A376FE74AB5`
SHA1 | `A1DEBBE8AB2D85CB2EF29A023FD61CB33AC41D4D`
SHA256 | `CFDB4DDDF8E024B38012CF753E45837E9D3C1D7F4DCBBD75CDCF1B9565CC41BA`
SHA384 | `58C717777F203A18C714F72A88DD4BE2F7A1311E2EC5B08845BF4AEBAD0CED3C003B198FCFCC817B745D9B1A2EDCC84B`
SHA512 | `75203DF287657250D6B532093332985E28AAD5544B628693723280DB20B03C50507CDBB9415D458DA8CF8320ED9880C1D0E996E849B6BF3A853AEAB9DF43D358`
SSDEEP | `768:e3RJG0VpogU20p4mm79a8qlhM3uP7Qs336vk42iENco2NS3wrv:hgB0pI9Mz6+xiENR3w`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdrLeakDiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


