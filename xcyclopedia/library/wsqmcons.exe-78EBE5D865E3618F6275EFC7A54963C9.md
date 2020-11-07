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
MD5 | `78EBE5D865E3618F6275EFC7A54963C9`
SHA1 | `6E01CCE73376DC359E0BB1F20F36E1E3DF3D1793`
SHA256 | `B78663AF2C7177CBB51A1CB62219D8737ACC5BD76A0D9C037C949406FF5768CB`
SHA384 | `E4EE6E7E0E2661EB1C22B7D581DF349AF7641935E946F9577989CC5F30575AD2C34E87CEDF6AC5E4F4B59D6A71D40EFD`
SHA512 | `4AF7170434FEA194925524F3922FC18F25506AED4537FBFA86A0230F111EF6AF8AF8F60315188562673B5DE9392E9896A82163E5B0C4A2792E8D9101BB748963`
SSDEEP | `1536:msvpIBM5HxjuPsMpNWxA8FrMqDL5an3YZEW+yyoecNtS3JPVo1GQumre2q61:UM3dxF3D8IZf+zE43JZQuCe2t`
IMP | `16504DCDB7B5511E296EEF5ED950DDD2`
PESHA1 | `AA5C11532A3471A546E17B6EA25844D54F0A6C92`
PE256 | `DF65EA7CD1B9A0D59C30B64343369991475F2E4B4077B9D6B25D7EC139E43AD8`

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
C:\Windows\System32\shcore.dll |
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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/b78663af2c7177cbb51a1cb62219d8737acc5bd76a0d9c037c949406ff5768cb/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-0EB7F4F9C9F36AB73476E1445742E294.md) | 35
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-207A52DB4D9CB6A252722D51E54AB01D.md) | 35
[C:\WINDOWS\system32\wsqmcons.exe](wsqmcons.exe-3198C8F020BC60931404167EEC51E2BF.md) | 38
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-3B04F0282E333C98974BB8A39360DD24.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-5A06B640015F7BBB113AF7FF7E29A3BB.md) | 32
[C:\Windows\system32\wsqmcons.exe](wsqmcons.exe-67FA4FB09632BC10881316F229E0D128.md) | 30

## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `- '.WSqmCons))\|iex;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


