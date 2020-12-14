---
title: smss.exe | Windows Session Manager
excerpt: What is smss.exe?
---

# smss.exe 

* File Path: `C:\Windows\system32\smss.exe`
* Description: Windows Session Manager

## Hashes

Type | Hash
-- | --
MD5 | `793C887D404F3EE2F9B490C21C38DD80`
SHA1 | `C438640E94CDC3A0037D47B8228A6DA9EA293AF4`
SHA256 | `E11AE324BA8C7AD66869BC34D16594F053C9447F0B11BF8D147DA259AD19DC92`
SHA384 | `3F2E621E6A84F35B5B86B514FC1201FBC63CC0CA6D5863883CDF3D2549118FDF1E0E26E58D378F4A04CB34E3FB79FEE1`
SHA512 | `ED78C1AA8A106E08F36C71CAB204AF7535371499961FC998459DEDFD75DE318229A9494DFF77A8DE6F3657345ACE39D0EBE7CCF9C3A0FEFCEF61C88F0D5DFF18`
SSDEEP | `3072:yQePhGRSAkjk9DswG11GIYH23Nh5+cLy4LBNG:yzijkjk9Ir1Gv23Nd+`
IMP | `9514316F92E1910DDBCE2EA3735D33A5`
PESHA1 | `12907A129BD9309F39F866D90ED56B50E1D560F5`
PE256 | `6D57331D6A666AD555B009202277F69F3309C95EA8ECB7F6E3EF0F47436F834E`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smss.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/e11ae324ba8c7ad66869bc34d16594f053c9447f0b11bf8d147da259ad19dc92/detection


## Possible Misuse

*The following table contains possible examples of `smss.exe` being misused. While `smss.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`smss.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


