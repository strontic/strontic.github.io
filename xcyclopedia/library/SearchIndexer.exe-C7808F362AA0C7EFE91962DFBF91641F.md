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
MD5 | `C7808F362AA0C7EFE91962DFBF91641F`
SHA1 | `01186EF9D5548CFB5B735F79CD29E540FFF0475D`
SHA256 | `710AF458414E90BC0B312D63B0A2CD7552227B269D0D617FCF93F02775948DD4`
SHA384 | `C1EF8F990919E08607850706A08ECE2A84C0FFBE5878EFB9B6E3789351F7E770D7C9F73ADBC7DF3021CACBE12ACC3EBF`
SHA512 | `9727BE13D2FA944EF061D2984F4BB17C5F3BB8E0CF36ABE4C13B2F773BC4495E0E7681BA689B731C3AB12544F3362F08B059061518DBDADD657B380712CC642A`
SSDEEP | `12288:Zk1Oq4dyht2B4Q1BO+SPQPOYWdazET6phIYFNm5CLK4lf+WLhmiNflVhURCWIz:q1Oq48htI4P+SPQmYST6XFNmWHTmOlV3`
IMP | `812BC377718C5596E3E57EC10AA99C88`
PESHA1 | `2E0E24C6671601D4A1D49083D33062885DBED2C8`
PE256 | `124E00DDC4CEB536A638B7C185F89387A4A8EAA8B7C499E51AF2D683282BC475`

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
* File Version: 7.0.19041.488 (WinBuild.160101.0800)
* Product Version: 7.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/710af458414e90bc0b312d63b0a2cd7552227b269d0d617fcf93f02775948dd4/detection/


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


