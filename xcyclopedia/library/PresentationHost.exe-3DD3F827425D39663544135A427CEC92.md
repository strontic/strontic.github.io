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
MD5 | `3DD3F827425D39663544135A427CEC92`
SHA1 | `44483EDB64B64DE425E5889F5B4BB01E9AA0CB7A`
SHA256 | `54BE944EB17BC7DEB3618C7844580BDF74308A1F07DE10004CEB4A8ECCE2B367`
SHA384 | `EC922394BEBD4A428792853F71A7EBB54379E45215F5B5B08EC87F44F357EA4CE2539818A92F4C010D3B0EEE3968CC52`
SHA512 | `17F0AFBAAB04B05C57BB725DB80EFD2C5B995402418EE87385743A46AEF50007DAB5F60565106AADC44F416F6C7697FC044630164D03D2547460F4E67319BBEC`
SSDEEP | `6144:CFezZkNSw/gk9J9i1d55KNXwy3Odjp19k5KNXf:y6ZkN9J92lKVwy3OdLaKV`

## Runtime Data

### Child Processes:
iexplore.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-193F1CA0ADF261816AC02CFD6553C96D.md) | 63
[C:\windows\system32\PresentationHost.exe](PresentationHost.exe-35200D32C398793D85F900B0273E6F43.md) | 61
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-446800712B6CAAC7B594F45AEA84F782.md) | 55
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 60
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-EF27D65B92D89E8175E6751A57ED9D93.md) | 61
[C:\windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-19F810B1F9ABC04F6E6CB66A2AFB5327.md) | 68
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-5C08493395E7427487B608CE0926F678.md) | 58
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 63
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 66
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-B73ECB016B35D5B7ACB91125924525E5.md) | 63
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-C6671F8B9F073785FD617661AD1F1C45.md) | 65

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Command: Presentationhost.exe C:\temp\Evil.xbap`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\System32\Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\SysWOW64\Presentationhost.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


