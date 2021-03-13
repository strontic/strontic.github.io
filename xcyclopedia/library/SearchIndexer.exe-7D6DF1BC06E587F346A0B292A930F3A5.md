---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\windows\SysWOW64\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `7D6DF1BC06E587F346A0B292A930F3A5`
SHA1 | `3D06FB182F33A01F894E687013C7B4E5D2721C29`
SHA256 | `EC58D7F640CFCB9C6971803C5BA3A51FBDEA36D2C4DE4183FECA955A1080E00F`
SHA384 | `3BD3A783E125720DFFAF2263E84100C7A1D82AA977A80668177EB891A5E3112225DEB2888C76471931C003EC45162706`
SHA512 | `115B80599A176AC585A832463134180CD3D15AE76AA157BEEFB95C01626442FE1276A2A2347769A8ACF9C3B90BDC22F178C210BBEC92328B80A6AF95CAF34CFA`
SSDEEP | `24576:yjc4fjM6iQlSeJIjRrRkFS4KIiThSQ5kdk:yjYeJwRFkdiThSQ5K`

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
* File Version: 7.0.17763.1098 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1098
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


