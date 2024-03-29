﻿---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\Windows\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `3F4C2BF030390FC8AEE8F0FCE2837E56`
SHA1 | `48FA98F8A17136CA3F0D5D0FB6BB2580D1D483E8`
SHA256 | `02AA6D3040FFE4EF897CEBC89F9D641F13DC27969B88EAFBA6A1EEE6BA9D019E`
SHA384 | `34EC0046E0BFE6265708B2E3A96481DE3CBCB4726C06AA7FCB85DE379103FC6A8CD6B3428D080DA4563C2A325C7616BA`
SHA512 | `FBCE18BA27C0D2AA88468A64613AA22EE46F7B793F42536A879FEEB198F63595A61725B6AC1BBBD99995EF386F4905C4F516D9BE53708B08B8EE25D8866B36F1`
SSDEEP | `12288:uRrF8sOx91gDVI0alMyyGN3Qr5H6NcOUXajN5eiQpm2Qztf:uTC9IdKQAGOuajzDQpm2Q`

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


