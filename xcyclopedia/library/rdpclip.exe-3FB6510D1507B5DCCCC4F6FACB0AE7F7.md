---
title: rdpclip.exe | RDP Clipboard Monitor
---

# rdpclip.exe 

* File Path: `C:\Windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `3FB6510D1507B5DCCCC4F6FACB0AE7F7`
SHA1 | `49D438A1A0E9DFF03A498A7057B33080EEFC9156`
SHA256 | `013CC1072338B426FAF2A953E56A8950849ADDA308600FA1627DE6495E924941`
SHA384 | `4F06CB5BB9F28CE357B6F6C0142CA0D3819A78B8A9116CF1FCCBB0C1842F3FC79B7416F3B9FD3216FD9860DF4752024D`
SHA512 | `F85DC17CF8BBAC1D1B8DAAD5ECC11070033E153DE5D7662F42F04C727CC824A3DD58E52017D942C7334917AF3F0F952B013172483088709FE8CC261BD2B1F6E2`
SSDEEP | `12288:H5o2qNI+bZUHw3SUZKJtIgWrGt6Wn1Es+Ek410uIgewuAhX9Hyecd7FOUaMMJtCZ:y2qNzbWHwiUZKJt+rGEWn1hzuAXgILwn`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image: '*\rdpclip.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


