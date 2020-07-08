---
title: audiodg.exe | Windows Audio Device Graph Isolation 
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `59000715B25E6FCA6329259BE2D6CB4C`
SHA1 | `745522798FE498059DA3DD2CD2C385C11FCF32D9`
SHA256 | `93666B4C63239E5C8128D1CC6CDF0765FB8E1E3893E7D6B8285D65D005FB296B`
SHA384 | `8C7D0199FEA85FC37D022E16ABE6C12CDC4ADCDAE457D322CF1900144FB4E108FF220444DA21F0FA1DE39560F5263755`
SHA512 | `F6C9ED31770289D5777952877AB181A22748AD5DDF947B4DDE9636E1FD5E5A24EF013293873AF10D1C0C2A402914B07F7AA48F441FCDC0426102FE30EE37DFB4`
SSDEEP | `12288:bFDBfxbQn+aEjHy7gUczucUULq85zzVMvS:pBW+aEjS7Ez8UZ/Ka`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


