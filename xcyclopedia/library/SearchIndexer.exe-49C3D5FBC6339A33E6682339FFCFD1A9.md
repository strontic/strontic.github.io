﻿---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\Windows\SysWOW64\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `49C3D5FBC6339A33E6682339FFCFD1A9`
SHA1 | `9FC59A943FA531AEE91275D1052B2212BDB98386`
SHA256 | `E5DAAFEDE3A97ADB0F532C988427CA51E73640B74D0DBC68A7A57D77A9D9A424`
SHA384 | `AA577BC7D9F321402ED058487EF2B7A4D1F8B0DD95F48EB9E6060190D11B34FD3E4CDBEA97C0C1336F4C37CA6B6AC2F4`
SHA512 | `C28DB8738EFAD357CF664CD5210CAEB13AC6B570402584C3BB98564B3A4C7FFC4AAFC6BC3D2C2F9C81B73F79B10F117243974DE6670ED53DE2F19C8FF170BB85`
SSDEEP | `12288:C57vl49wYPgcrzrlZxuJy/juIqU/oBKnJgFEsQaRQztf8ia:ClvlywYPg+zPxuJy/jft4KQTQaRQ1`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.14393.0 (rs1_release.160715-1616)
* Product Version: 7.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


