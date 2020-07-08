---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
---

# SearchIndexer.exe 

* File Path: `C:\Windows\SysWOW64\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `DBC3E221CD8B44830A4B7FA1A89D1197`
SHA1 | `D5CF39D3174A974ACBAE8A7F033E53F6EE6BAF4D`
SHA256 | `73AAC2D2C4CC1163A67AAF96247FFF2D98269D1EDDEBEE3C8FE1F01EE7391B70`
SHA384 | `5DA07F063DA0127CC9E25CF70158031B75D718F53744D353E6E1AD9209C7089DA9D561FFDB3D7D227D662443D32B96D3`
SHA512 | `28F0C635FD086955F892C5A727CC22F441827C0E66C3AA6634C00E8BAC50C68A4C574A3521479E616BF2713B3E641EA572022AE42C87C17B527C4E90DFFA5927`
SSDEEP | `12288:I1BxC49hhlPhhCQBNE7v3qluM80YDUA8rQcVvOJOCz2oFXtorgAmqBlGh0CWIz:iBxC4nhlJhg7v3Uu6A8VvO/hamylGh46`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.19041.329 (WinBuild.160101.0800)
* Product Version: 7.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


