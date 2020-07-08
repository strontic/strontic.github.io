---
title: igfxCUIService.exe | igfxCUIService Module
---

# igfxCUIService.exe 

* File Path: `C:\WINDOWS\system32\igfxCUIService.exe`
* Description: igfxCUIService Module

## Hashes

Type | Hash
-- | --
MD5 | `EAEF64907434CCE808BE12D1B0043E21`
SHA1 | `78D8BEDB1239021A4080440BD3738167844CEA91`
SHA256 | `354D5B4C9B9A178899528E9B060BDE6B217D24421A4372C7AD3C2BA085956D52`
SHA384 | `191B621C1ADA5A07906D19D11E1B605148988469245C5D23F85D6939C86EA2F82ED21292121BAD99FC488E5A26FDA9B9`
SHA512 | `7592E50942FD2957716CE5F0ADD76B4D51C0F8C099FB0E69C23EF56BF62778D94D55924B64FA39330FA4B740A9C9B1C936BE6D66F63ECCBF0AEDDC6DDED10885`
SSDEEP | `6144:/X67T/HNGxW4Cm7mQuT/F/1A2RKnXYRRSgEbJ4Y:/XcT/tG4+7m50YRR`

## Signature

* Status: Signature verified.
* Serial: `3300000010D1EBBCBE1C4C7C49000100000010`
* Thumbprint: `C802CA01BC3064BFC0510CC762FFAA20BFE8EC61`
* Issuer: CN=Microsoft Windows Hardware Compatibility PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IGFXCUISERVICE.EXE
* Product Name: Intel(R) Common User Interface
* Company Name: Intel Corporation
* File Version: 6.15.10.4248
* Product Version: 6.15.10.4248
* Language: English (United States)
* Legal Copyright: Copyright 2012-2015, Intel Corporation


## Possible Misuse

*The following table contains possible examples of `igfxCUIService.exe` being misused. While `igfxCUIService.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_attrib_hiding_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_attrib_hiding_files.yml) | `    - igfxCUIService.exe hiding *.cui files via .bat script (attrib.exe a child of cmd.exe and igfxCUIService.exe is the parent of the cmd.exe)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


