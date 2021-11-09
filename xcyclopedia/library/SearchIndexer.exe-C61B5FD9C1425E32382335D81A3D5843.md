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
MD5 | `C61B5FD9C1425E32382335D81A3D5843`
SHA1 | `DA6D0BF41C407CDFD14BBD9290B8B0509DCBBCFB`
SHA256 | `CB1B0B0D8A4C093CFF7CBB711CBECCCE38EF409C0D15E9030BE093DDE71357BB`
SHA384 | `BBE7DD5A293B08F5820B115940EA519F9E175B88D50990AD26C49A8230C5900A3FEEB3E9D2F92014B98666179D7C2EE3`
SHA512 | `944FD3C52B9E4240CCAFADFD4FF7016BCB47E8721BF61FEFACC7B0A2F718C90FCE19123F5971081E7DFB21C6FCD4F26FCBA202AB8D927DA9F91DC7F903346B1D`
SSDEEP | `12288:fjh96xk8nPQA1CNhvxwEgJ7mVA4+O6sOXz8ru3sIKtsQpxyq8uxlV+aByFF:rh9624QAihuEgJOZ+O6sOXz8uKs8OuxU`
IMP | `09173619889B19C4E1D2C480C3263786`
PESHA1 | `82F934C592C6BAFF9FDFF380B21B4FB12102BC1E`
PE256 | `7D4FCC606CC7D175ED6A30D52CB68A834FF3C44B1EDBF120A3395CDED0D03215`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\SearchIndexer.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.22000.282 (WinBuild.160101.0800)
* Product Version: 7.0.22000.282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/cb1b0b0d8a4c093cff7cbb711cbeccce38ef409c0d15e9030be093dde71357bb/detection


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


