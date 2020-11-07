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
MD5 | `0EB7F4F9C9F36AB73476E1445742E294`
SHA1 | `F52D1466E5CA5A3AB1E0D11834D97E90AF06EBF3`
SHA256 | `B2C302908DCF70EBD1B1112312C702247197254CB7310ADDFD66184B931B7D2D`
SHA384 | `872D8C94E5E54EDF628DCD7270E97ED050D5D084448DF6C1404E6CC0B4C3C58288EACEF450B9E68CB05B3DF2B4D7AC64`
SHA512 | `EED5CA47803DEF5D0BA83F27C89C1C02D056EC2CB985E63E334864C5F03BD129908966BCB58BD4F8B481C92DC0F16DB273849BDA2862BC52D21EB3043E617B8C`
SSDEEP | `1536:r1P+0Jmc0vyxWqcLdKAVP9xVpgVubXwxEE1d5verrSrJPRRmGQumre2q6m:Q3c0v9VP7w4sxVor2rJHJQuCe2e`
IMP | `16504DCDB7B5511E296EEF5ED950DDD2`
PESHA1 | `A3EB9401B92B74240BE1F802BE868CCCA5321D61`
PE256 | `D2255DFA270914095C14440E579CE724F7593441B549ED85A73A80D4EB691DF2`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\wsqmcons.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/b2c302908dcf70ebd1b1112312c702247197254cb7310addfd66184b931b7d2d/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-207A52DB4D9CB6A252722D51E54AB01D.md) | 32
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 35
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-3B04F0282E333C98974BB8A39360DD24.md) | 40
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-5A06B640015F7BBB113AF7FF7E29A3BB.md) | 35
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-67FA4FB09632BC10881316F229E0D128.md) | 30
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-78EBE5D865E3618F6275EFC7A54963C9.md) | 35

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


