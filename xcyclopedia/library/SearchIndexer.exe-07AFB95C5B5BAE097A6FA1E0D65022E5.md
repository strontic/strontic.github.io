---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
---

# SearchIndexer.exe 

* File Path: `C:\windows\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `07AFB95C5B5BAE097A6FA1E0D65022E5`
SHA1 | `6AB03B152882B9425E132834D39DC113B7E30A36`
SHA256 | `E30696AAD9ED79A56608B561FB521908B764B2FA169D93E671B3B30E5B08AE40`
SHA384 | `3E4032CBFBDEAD5587FDE94E8FDF87E6978CDD0E7A14EC855F3A1D8255368C7DC0171D6999D9B8EFCF6DDEEE82917D6E`
SHA512 | `FD4EC52B6E85386D04FBF1DF4D7C566A2EB62E8010A07D69A5FEFB6C346FC6341C1CC68B8B313FE2E19E1960C184F28EE6F26BADF4442E358650DFC06E92A12D`
SSDEEP | `24576:JNbP/VEqwJdD6V3M+LbJG167b/0u0Ihh+eQ:7bCDq3MqJG167b/j0IhhhQ`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 7.0.17763.1 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


