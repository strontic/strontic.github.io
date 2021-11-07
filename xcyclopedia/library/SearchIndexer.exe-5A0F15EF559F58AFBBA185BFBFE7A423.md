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
MD5 | `5A0F15EF559F58AFBBA185BFBFE7A423`
SHA1 | `A902225C5BB62A5215CE4439DD87124CAF545F10`
SHA256 | `8FAC5E5EE7E0CFAD8684EA66605282D0B006FA151A484904860A961EEEF09750`
SHA384 | `4CF252CB518EB46CCAA3A1763109EE49B6A87A91B7F5F53C113C269C3C2BD1191B24E07C8C3D36603A54DDC3934C0BE8`
SHA512 | `8011C3B12739EEB75808570FE1A8EDBDD805D9888B3AF130FB0283723105FB87796A956F40CF6DD8699C8DFF5BDF9D9CE9C9EF89BBE5303274403D7AC6903D49`
SSDEEP | `12288:0955IPx4W4oT6KdobHSQrYmDN7zhZp/ZS8y37mW4Oxu/hQQztf/jd:Q6Px4HoT9GbHk2NfhZphVyrlu/hQQ5`
IMP | `C6066FACB10B8EEA5BB61F38891A0A29`
PESHA1 | `4A5F8A4672E4076C9608480D3AF86BE9AF9E11D0`
PE256 | `995A0D9E58074E9CAB08ABE63B81955239E96FE5259CD562C163934DEBA8E9C6`

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
* File Version: 7.0.17763.1490 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1490
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/8fac5e5ee7e0cfad8684ea66605282d0b006fa151a484904860a961eeef09750/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\SearchIndexer.exe](SearchIndexer.exe-DF78D1064A5A87767ECC9EB5D0305144.md) | 44

## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


