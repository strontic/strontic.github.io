---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\WINDOWS\SysWOW64\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `435D951C7B6B47CD676DFF0776DC61A8`
SHA1 | `C228594862FA260D22E89F1C60B689CF35795A73`
SHA256 | `A1B94298C0BAC96946DE1850AB76781A9E4D6A2EFA8F631AB78D55DA7E88D62D`
SHA384 | `3E925E6739A986A579C923DD3FA74A6EF9B7F1D4447EA8A48D8DDB3E693131FF50CD846F84B2F4BE8B86D6D0B55C3975`
SHA512 | `2CDB96F5C76A39A43D5074C0BCCADFE7DCA0149F0ECD2F62AE872D44ADEFE9081AA1263B0C442A2CD9119CF8AE1FCF76F051798A7ED27F8625642ECABD9DBCFB`
SSDEEP | `12288:jpZuDj4wgpxQrS+mJ/4DXrFkF4Y7lxWujS4p0ehoPYxRCqtpzwzFhirDd:vuX44rSZJADXrHklxvS4pVPtpzwzFhi9`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.18362.719 (WinBuild.160101.0800)
* Product Version: 7.0.18362.719
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


