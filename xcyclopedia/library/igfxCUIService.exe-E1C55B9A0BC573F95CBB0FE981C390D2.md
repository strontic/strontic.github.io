---
title: igfxCUIService.exe | igfxCUIService Module
excerpt: What is igfxCUIService.exe?
---

# igfxCUIService.exe 

* File Path: `C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\igfxCUIService.exe`
* Description: igfxCUIService Module

## Hashes

Type | Hash
-- | --
MD5 | `E1C55B9A0BC573F95CBB0FE981C390D2`
SHA1 | `2830FC92BCEADEA27188E6D48BB4DB5A3CB2366F`
SHA256 | `C19BAB0E55DD23F0CC106D73DAA1154D359D8033E065832E41B9D710E241FCF0`
SHA384 | `C76D173AA3B040456F4DF840A4E2D757DBF063BA3A0458A7E7405EC083B08620B58ECEB2298434777D587482FF65D4EF`
SHA512 | `3D886DC308CB1FD84AE2DB480999F81335F35C750FAD1859A1640011EEC4F262D0927333CEC5B928DE02468C645E7A179B49B5545EC602AA2DD8E83764ACBC17`
SSDEEP | `6144:/NQpiVHKxO4qWTi1SGC0LP8xTcjmBhiBI:/NQcovqQR6jgl`

## Signature

* Status: Signature verified.
* Serial: `330000002D4E7AEC99B0F05F7300000000002D`
* Thumbprint: `431FA5538299F973C06FDE9D6E97CC81C047AB0E`
* Issuer: CN=Microsoft Windows Third Party Component CA 2012, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IGFXCUISERVICE.EXE
* Product Name: Intel(R) Common User Interface
* Company Name: Intel Corporation
* File Version: 6.15.10.3682
* Product Version: 6.15.10.3682
* Language: English (United States)
* Legal Copyright: Copyright 2012-2015, Intel Corporation



## Possible Misuse

*The following table contains possible examples of `igfxCUIService.exe` being misused. While `igfxCUIService.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_attrib_hiding_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_attrib_hiding_files.yml) | `- igfxCUIService.exe hiding *.cui files via .bat script (attrib.exe a child of cmd.exe and igfxCUIService.exe is the parent of the cmd.exe)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


