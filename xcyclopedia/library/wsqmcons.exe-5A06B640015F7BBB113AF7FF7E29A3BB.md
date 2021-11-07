---
title: wsqmcons.exe | Windows SQM Consolidator
excerpt: What is wsqmcons.exe?
---

# wsqmcons.exe 

* File Path: `C:\windows\system32\wsqmcons.exe`
* Description: Windows SQM Consolidator

## Hashes

Type | Hash
-- | --
MD5 | `5A06B640015F7BBB113AF7FF7E29A3BB`
SHA1 | `E36B915DB31E9E7C6D4C0E21DA3D04B35B4D7C88`
SHA256 | `4530B5A7AEDF53CF8FF57F6237B5015C09DEED0B1493662A9B21E3F4B676FE8C`
SHA384 | `AE543BFF124E3A53C54DBB7A4C5EA30A8FCA063D62A830F1CBDC55F64DEAEA07E4DEE2E4192DB88060A582837E6FF0D6`
SHA512 | `C0DF29FCDC0717E6490149A2C36320AF4E3C3F7EC0EA8399A8728A0960D86CC6A018AFEA4308BFA51FCD3488BAE02D83748CDCF918742FFDF0CFCC2EBBCF9DC4`
SSDEEP | `1536:rvOuxC3lSApQTIJvEey2mCz/g791XqSjh4fSZJCGQumre2q6L:rABNvdy2mM0f26ZJ1QuCe2j`

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-0EB7F4F9C9F36AB73476E1445742E294.md) | 35
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-207A52DB4D9CB6A252722D51E54AB01D.md) | 40
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 40
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-3B04F0282E333C98974BB8A39360DD24.md) | 30
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-67FA4FB09632BC10881316F229E0D128.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-78EBE5D865E3618F6275EFC7A54963C9.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-94CD268C54DB44FBA471C7C47EC47D9B.md) | 35

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


