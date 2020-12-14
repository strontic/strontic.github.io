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
MD5 | `5BDB45ADBF0670E911C57F898877A002`
SHA1 | `349F721348F15C7357351A667683F7BBBAC76C25`
SHA256 | `35DA9F518B4F90AF76B014C1D8B0232E1F58ADFABA900DF0E49DA8511ECEB932`
SHA384 | `E30A0CCC214A66A22132EE452D032F0051B7E727D75BAAA2477451B9DC4FC32BD2A2465DC365379EE65F58C7706BB46A`
SHA512 | `2584E820A81A07BE438F675F57B4AB63DF7321F9107A147E54EA9190AD74031824E9910DC660A5C085D0D7F1AA971C23CDEEA3BE24E7062F817ACF16709C68D0`
SSDEEP | `12288:iM67B8aYL4AGuVmhawphV0rzerghXafFGzqgYGslys1QogFbUTI/1ylWhrAB5:iM69vYL4iEsw0zeEhq4OB9V+ulWhcB5`
IMP | `812BC377718C5596E3E57EC10AA99C88`
PESHA1 | `0C29244BFE8C10DCA813D348ACD5830F779AE972`
PE256 | `8561302E06A2A78F8D7A11CA7FD0FCD026A15C887CEB54350F1E1E47FE70D20E`

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
* File Version: 7.0.19041.610 (WinBuild.160101.0800)
* Product Version: 7.0.19041.610
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/35da9f518b4f90af76b014c1d8b0232e1f58adfaba900df0e49da8511eceb932/detection


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


