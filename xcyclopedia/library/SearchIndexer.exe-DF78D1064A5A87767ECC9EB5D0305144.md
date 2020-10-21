---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\Windows\SysWOW64\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `DF78D1064A5A87767ECC9EB5D0305144`
SHA1 | `3703E521645041AA4F58F5F0C505D5B76DB0FFA3`
SHA256 | `745FE249F9F28FDF2972148187479231A01D18C29E5A75A2B7E93458EFFD66ED`
SHA384 | `0F4E47B41664EF8A2BCB0B415D189CB945D0A178C5F4775A0D068D0CC54228F6611C4691B608E067D6A037830071F11A`
SHA512 | `AABDD99EBCC681EF095E35B298FC26B361639BE0BBEBE4729275CECB810EB9A695FEA682B240B2F4DF2A26286332602F5C0DA7A48225344BEF7394B72727C66F`
SSDEEP | `12288:Z9z58ft4WYhTqawoXX8QrcmvtzghZJDxyzH/w+WzLEuChgQztf/jd:f2ft4nhT9/XXWKt8hZJ9aH4+uChgQ5`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\SearchIndexer.exe |


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
* File Version: 7.0.17763.1369 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1369
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\SearchIndexer.exe](SearchIndexer.exe-5A0F15EF559F58AFBBA185BFBFE7A423.md) | 44

## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


