﻿---
title: PresentationHost.exe | Windows Presentation Foundation Host
excerpt: What is PresentationHost.exe?
---

# PresentationHost.exe 

* File Path: `C:\WINDOWS\system32\PresentationHost.exe`
* Description: Windows Presentation Foundation Host
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `49FA711824925D5FA0286A7FDE8C1821`
SHA1 | `BAD31D3C32ABFBB8C4FC9FDB319A44738D0D65ED`
SHA256 | `FED3EB0690FBF5702FB8F737F81E7F73E5649F0FE692BD4649F03DFAC81F07AD`
SHA384 | `51D20D59155CFAA4AD2BB58DA4C86AB7C1223A5A1830C612DBA798C85DA4AF5A80088921E38C47C80859CD2442572DB1`
SHA512 | `DD522992F5D0F2E01ECEB8567BC2990C8FC6AB9562777E091EE54F0F74C67839058D6AF68FDEEE24F6DEE85E198145210D7E2430B1B0DD2EB27A38E5499AF36C`
SSDEEP | `6144:GvMzhWcTzxZmi/tzLqt5KNXwy3Odjp19k5KNXf:GvMzIoPm2tnyKVwy3OdLaKV`

## Runtime Data

### Child Processes:
iexplore.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe.mui
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.0.41210.0 built by: Main
* Product Version: 4.0.41210.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-193F1CA0ADF261816AC02CFD6553C96D.md) | 60
[C:\windows\system32\PresentationHost.exe](PresentationHost.exe-35200D32C398793D85F900B0273E6F43.md) | 58
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 60
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-446800712B6CAAC7B594F45AEA84F782.md) | 61
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-EF27D65B92D89E8175E6751A57ED9D93.md) | 61
[C:\windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-19F810B1F9ABC04F6E6CB66A2AFB5327.md) | 68
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-5C08493395E7427487B608CE0926F678.md) | 58
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 60
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 63
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-B73ECB016B35D5B7ACB91125924525E5.md) | 65
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-C6671F8B9F073785FD617661AD1F1C45.md) | 61

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Command: Presentationhost.exe C:\temp\Evil.xbap`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\System32\Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\SysWOW64\Presentationhost.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


