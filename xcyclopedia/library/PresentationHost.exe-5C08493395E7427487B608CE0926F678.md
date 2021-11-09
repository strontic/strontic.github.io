---
title: PresentationHost.exe | Windows Presentation Foundation Host
excerpt: What is PresentationHost.exe?
---

# PresentationHost.exe 

* File Path: `C:\WINDOWS\SysWOW64\PresentationHost.exe`
* Description: Windows Presentation Foundation Host

## Hashes

Type | Hash
-- | --
MD5 | `5C08493395E7427487B608CE0926F678`
SHA1 | `6A78218355DDECC246A2736D5344D54D8EB49235`
SHA256 | `B8EE4521152B66DA6A8ADB270D214DF7808AC75CEDBC81149EDE4F5FAFE8BF74`
SHA384 | `51B159769C3ECB04AA88A11D6D2C590F5C15895839D6BB2465E267336299A09E41928F09D6024BCDFB67869F5E0CA430`
SHA512 | `E7049EFCACDFF4CF088D10E413CAE7F1E41A48EA03B00C1077D6B48C67D518CC779FA6FEE88395DE1E7FB8ED684B2AA74708E38A58070753B8B38CE8F06A62AE`
SSDEEP | `6144:OlCBImrA+quYVmlm5KNXwy3Odjp19k5KNXf:OlCBIUI7EsKVwy3OdLaKV`
IMP | `B2AE8CE4D2C814B2A3D6AD65A56B0477`
PESHA1 | `06DA6A4E2F059130E7114423BADC45B8C7EC7CFB`
PE256 | `9071C9E53F7745CBA7E964871E894F2ACDAE42815A53180CD2DD992C02E5727B`

## Runtime Data

### Child Processes:
iexplore.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\PresentationHost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b8ee4521152b66da6a8adb270d214df7808ac75cedbc81149ede4f5fafe8bf74/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-193F1CA0ADF261816AC02CFD6553C96D.md) | 57
[C:\windows\system32\PresentationHost.exe](PresentationHost.exe-35200D32C398793D85F900B0273E6F43.md) | 58
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 58
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-446800712B6CAAC7B594F45AEA84F782.md) | 54
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 58
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-EF27D65B92D89E8175E6751A57ED9D93.md) | 61
[C:\windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-19F810B1F9ABC04F6E6CB66A2AFB5327.md) | 61
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 63
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 63
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-B73ECB016B35D5B7ACB91125924525E5.md) | 63
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-C6671F8B9F073785FD617661AD1F1C45.md) | 68

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Command: Presentationhost.exe C:\temp\Evil.xbap`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\System32\Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\SysWOW64\Presentationhost.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


