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
MD5 | `3B04F0282E333C98974BB8A39360DD24`
SHA1 | `70C207852420431863BE2E476177F7A835A170B8`
SHA256 | `888730CE9F3B3E325C5746D5455D0404CF1F49D85A863F678C3FE7326834309D`
SHA384 | `EC75A5FB26528395FE26D965B6B7FD4945B509714AE12176BCBCE7F03A8DBB5F06F5AC9746C438ECE128BA7B141612E9`
SHA512 | `7E77FBB835FF3CF02F0DC33122B6EC278A7727D10D44D19DC3E1827DF3745161C947DF656D816606A7397E5643C57B45C54C5630D8ABD92E4464B2C74085070E`
SSDEEP | `1536:7JnAXHc8ynLbSbeduefalu+R/0V2oKQxsFEZ1MUHuGBSrJPR9v6GQumre2q6q:qc8kSLluoaMJFYdt8rJHtQuCe2i`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-0EB7F4F9C9F36AB73476E1445742E294.md) | 40
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-207A52DB4D9CB6A252722D51E54AB01D.md) | 30
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-5A06B640015F7BBB113AF7FF7E29A3BB.md) | 30
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-67FA4FB09632BC10881316F229E0D128.md) | 33
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-78EBE5D865E3618F6275EFC7A54963C9.md) | 32

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


