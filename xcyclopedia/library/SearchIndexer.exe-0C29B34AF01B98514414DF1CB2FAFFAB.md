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
MD5 | `0C29B34AF01B98514414DF1CB2FAFFAB`
SHA1 | `51C46901AEA3207EB093273FFA33DDF1B90B1C95`
SHA256 | `B2F7E272A5E959B6FEBA8720CD63DB34EE638D5D3419A00CDCD3A3753E725C30`
SHA384 | `DA207F4AB4C60E603DBE9AC2FA0E163CD4CCC1A166AB9E55E03D65D91DC6DB2820FB8B214F577CEF9B225B4588F6D70E`
SHA512 | `C7810D1276D5E4EC4487FE86F22860CEBC6D89871DE4880515BF601942A023CDEA783C68C84E3072BB694B6198F31FE97CB18D4A68C977E235C707A2D22BC4A8`
SSDEEP | `12288:KMoaWcqp4xpdVoTVTBQtGkgBE0y4GY/8rjtYbEwoOQNVxJlRn6/+W+NaQyWcPC/t:gaW1p4xXVwzcD3Ht4EwoxJe+NayJnqKn`
IMP | `812BC377718C5596E3E57EC10AA99C88`
PESHA1 | `5B2AAB9AEF02E1155FD0449080092F2AAB9BF2E0`
PE256 | `31BEF7091BC70B5C95708377D70BDAEB173EED9BE9B2E662F200FABB5D0B072E`

## Runtime Data

### Child Processes:
perfmon.exe

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.19041.1151 (WinBuild.160101.0800)
* Product Version: 7.0.19041.1151
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/b2f7e272a5e959b6feba8720cd63db34ee638d5d3419a00cdcd3a3753e725c30/detection


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


