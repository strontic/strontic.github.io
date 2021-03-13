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
MD5 | `207A52DB4D9CB6A252722D51E54AB01D`
SHA1 | `8CCBC67E74B01B3D90387A4F099FB3C49F7F3EB0`
SHA256 | `C1D4CE55169A1EE0FB5E11DBF907DF52EBBA5A3914A754F4557CBEC96A857C20`
SHA384 | `D03345B611046A09424798E9574577EAF26AA9EF9D4F517597453C451D29BD0A64605B403159BEFC7A218CEF1E2FB111`
SHA512 | `7251D0CF73D44259D0A9FC78FE96F03B56C709BBB615CC9C36C5D2A24CFCE5C3286E7D7221AEA9B51BAFC083C9E24164C322CAD62C7851B67B4DD197EB8AEC28`
SSDEEP | `1536:Up3uiFiV/3QA1R0y4ZG6zROCEjyXTC/xlkWSZJaGQumre2q6J:we/Jf6zwjQUSZJNQuCe2B`
IMP | `D704D43E51FEE7E15E186F930CEF45D0`
PESHA1 | `301FD8BF31E67BCEFFFB0778B9BF664514D61983`
PE256 | `06B7016A59035F984F1DF6366F4A0E58AF1B0FC63CCC20C69F846FE03AFDE56F`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wsqmcons.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c1d4ce55169a1ee0fb5e11dbf907df52ebba5a3914a754f4557cbec96a857c20/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-0EB7F4F9C9F36AB73476E1445742E294.md) | 32
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 40
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-3B04F0282E333C98974BB8A39360DD24.md) | 30
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-5A06B640015F7BBB113AF7FF7E29A3BB.md) | 40
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-67FA4FB09632BC10881316F229E0D128.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-78EBE5D865E3618F6275EFC7A54963C9.md) | 35

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


