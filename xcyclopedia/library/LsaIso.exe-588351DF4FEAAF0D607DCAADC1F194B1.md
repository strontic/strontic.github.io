---
title: LsaIso.exe | Credential Guard & Key Guard
---

# LsaIso.exe 

* File Path: `C:\Windows\system32\LsaIso.exe`
* Description: Credential Guard & Key Guard

## Hashes

Type | Hash
-- | --
MD5 | `588351DF4FEAAF0D607DCAADC1F194B1`
SHA1 | `6F0E9987DDCBAF28C0286F8496EE4C313ABA1628`
SHA256 | `9E737A9EDE8D3E623524B60FD2FCF000FEF34AA1F274CB1DA00735985B86AC30`
SHA384 | `38F5390E23885A49483262B609E24702DFCA1396393E508F8B11BA6D285485D33626C8FFB6C18DC606F88C806A185EFE`
SHA512 | `90A226E233D4F3AC752C851DB913824D25AE2D05BF6FFF14ABE44E55E1AA8150051FB2AC25079DBA968286B29A146978985901901E061F0406AC493C44CA33B7`
SSDEEP | `6144:n98x5SYuOHIqnef7F18GZ2qJB4LJ1SjL8DKTQe:05INbM/zmYpe`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LsaIso.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\lsaiso.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


