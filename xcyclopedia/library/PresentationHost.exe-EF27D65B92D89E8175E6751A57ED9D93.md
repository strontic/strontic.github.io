---
title: PresentationHost.exe | Windows Presentation Foundation Host
excerpt: What is PresentationHost.exe?
---

# PresentationHost.exe 

* File Path: `C:\Windows\system32\PresentationHost.exe`
* Description: Windows Presentation Foundation Host

## Hashes

Type | Hash
-- | --
MD5 | `EF27D65B92D89E8175E6751A57ED9D93`
SHA1 | `7279B58E711B459434F047E9098F9131391C3778`
SHA256 | `17D6DCFACED6873A4AC0361FF14F48313F270AC9C465E9F02B5C12B5A5274C48`
SHA384 | `9779F95F87B421BFDE816FA47AE7ED4EC520B3D3A28899B66893A2EDD4084D5B040B83E152704D3318F2D5DB821990B0`
SHA512 | `40F46C3A131BB0388B8A3F7AEE422936F6E2AA8D2CDA547C43C4E7979C163D06C5AA20033A5156D3EEEE5D455EEB929CBCE89BCC8BB1766CBB65D7F03DD23E2E`
SSDEEP | `6144:nKzlwEJfWd1o8UmCz1Jf5KNXwy3Odjp19k5KNXf:nclwEyymCR3KVwy3OdLaKV`
IMP | `0F05A612CA776F9A937ECDE00BDB9592`
PESHA1 | `8D88D1300FA7F6900B4BB6CBF6BAA54AB5AB9C0E`
PE256 | `B437E2F8A7406A36DB15FFFC00BFD6795341DC1ADBCCD2BE53C79849C19D5DA5`

## Runtime Data

### Child Processes:
iexplore.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\PresentationHost.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/17d6dcfaced6873a4ac0361ff14f48313f270ac9c465e9f02b5c12b5a5274c48/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-193F1CA0ADF261816AC02CFD6553C96D.md) | 54
[C:\windows\system32\PresentationHost.exe](PresentationHost.exe-35200D32C398793D85F900B0273E6F43.md) | 60
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 61
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-446800712B6CAAC7B594F45AEA84F782.md) | 54
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 61
[C:\windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-19F810B1F9ABC04F6E6CB66A2AFB5327.md) | 61
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-5C08493395E7427487B608CE0926F678.md) | 61
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 61
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 63
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-B73ECB016B35D5B7ACB91125924525E5.md) | 61
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-C6671F8B9F073785FD617661AD1F1C45.md) | 66

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Command: Presentationhost.exe C:\temp\Evil.xbap`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\System32\Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\SysWOW64\Presentationhost.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


