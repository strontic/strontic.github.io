---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `36CD34291E413E2406539C9FF40DCE1C`
SHA1 | `D0C362F8C2794C5123BACB4762ED1DD18377A79A`
SHA256 | `A8DC3BA17EA1519C2026B91500DDF2979BCEF4145CF220ED775825C15FDD00FD`
SHA384 | `90EACD6CEE0B93A1CE0156BFDFCFA8FDCEA4A809CA78217EB1B4591C821AE5F2F889A99D08BAB69BAE21A74DB0556322`
SHA512 | `85B25003D721786F0225DB6C33F15C7FA10B12CF8EF1C7857C2920ACAB8F3532E989B28E318E2FD5B65030EFAEC6188075F936AA4D7C7613DBF5064FFC4DE534`
SSDEEP | `6144:MsjKw62wMgi0wTDMwffNtDTU4BUFhbwRVegMU7k3QRfX/1vPeoNcM80Au9Oyo:1jKn21gi0wTgwNtHU45Mp3W1d80Q`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3503 (rs1_release.200131-0410)
* Product Version: 10.0.14393.3503
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


