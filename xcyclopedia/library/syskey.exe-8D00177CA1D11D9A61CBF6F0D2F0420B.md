---
title: syskey.exe | SAM Lock Tool
excerpt: What is syskey.exe?
---

# syskey.exe 

* File Path: `C:\Windows\system32\syskey.exe`
* Description: SAM Lock Tool

## Screenshot

![syskey.exe](screenshots/syskey.exe-8D00177CA1D11D9A61CBF6F0D2F0420B-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `8D00177CA1D11D9A61CBF6F0D2F0420B`
SHA1 | `92663620780C8FFB12A9C51BB2316B2A77200918`
SHA256 | `C33F6532E98DD6FBFF3F30B80982D2B6B97D8A78AF19F50D0C8A9C114AA0C510`
SHA384 | `E4DA7363985AC0BEB9F28F542675331D2B2CD572E3E03A3C650F219C7F7AD52708A3D79FADE918CD05C212E7C9ED22F2`
SHA512 | `BD5F26E0BD7FBACB0E17DC7398BA170B9820CF6681C8EE20E3ADB857DEE08AC0120E2701ECEE34AEEAAC7B71D9A3A359AB6017AF289793CF7C85D801EE5860BF`
SSDEEP | `384:D898VYh93aAjZSD59AD3Vr2+alwOUQCigL/tPGwdAvkyUrlv6mkc1KC1Q1fWaxW:D898UKA1WS12+alNCxtPbgkyUrlAl`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: samlock.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\syskey.exe](syskey.exe-EFDF337667EB0516CC325BA74A7F9411.md) | 33

## Possible Misuse

*The following table contains possible examples of `syskey.exe` being misused. While `syskey.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'reg SAVE HKLM\SAM'  # save registry SAM - syskey extraction` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `title: SysKey Registry Keys Access` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `description: Detects handle requests and access operations to specific registry keys to calculate the SysKey` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | description      = "LSA dump programe (bootkey/syskey) - pwdump and others" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


