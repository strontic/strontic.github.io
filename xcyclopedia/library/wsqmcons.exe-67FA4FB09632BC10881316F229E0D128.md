---
title: wsqmcons.exe | Windows SQM Consolidator
excerpt: What is wsqmcons.exe?
---

# wsqmcons.exe 

* File Path: `C:\Windows\system32\wsqmcons.exe`
* Description: Windows SQM Consolidator

## Hashes

Type | Hash
-- | --
MD5 | `67FA4FB09632BC10881316F229E0D128`
SHA1 | `F2DAEC3A3459ADD53D5D81E9BE32E8CFE2B48227`
SHA256 | `9FD2D9FE6BB0620B8DBDBE1335CE93F508B3CB5CF7F5C053A5C91C2220AD4332`
SHA384 | `5C05573CFAAAEFB91386D39202207308569475E6BE293B30A5DAF6F793834DF7474CBFB9D64A94998061A13424BF0B1D`
SHA512 | `4524C89FC3CEB9854888D8767A6D1A53935856068EF3FFC3CEEC416823A575878B2F5E397FF82D8A200D7FAB7695CF5354CADE8B2F8336081BE9D5582C57F9BD`
SSDEEP | `768:xO9MbwAtFq+ogaRQpv1ojVbPJGJBMCat2Jp0sBflQuWnnnPreUVnbO6wGNj4:tbLogYkv16PJGACLJp0sB9Qumre2q6Q`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsqmcons.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-0EB7F4F9C9F36AB73476E1445742E294.md) | 30
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-207A52DB4D9CB6A252722D51E54AB01D.md) | 32
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 36
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-3B04F0282E333C98974BB8A39360DD24.md) | 33
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-5A06B640015F7BBB113AF7FF7E29A3BB.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-78EBE5D865E3618F6275EFC7A54963C9.md) | 30

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


