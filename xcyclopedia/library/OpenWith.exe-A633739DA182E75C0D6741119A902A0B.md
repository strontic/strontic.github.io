﻿---
title: OpenWith.exe | Pick an app
excerpt: What is OpenWith.exe?
---

# OpenWith.exe 

* File Path: `C:\Windows\SysWOW64\OpenWith.exe`
* Description: Pick an app

## Hashes

Type | Hash
-- | --
MD5 | `A633739DA182E75C0D6741119A902A0B`
SHA1 | `26D3C98CFCDE9F6BF74F7131935653EE06661541`
SHA256 | `05DA72B7B1906C504482410E2F2F4D57D41ADA140DA833D1AB5B9195AB80A3E0`
SHA384 | `D027F0E71FDB35F897B0AF55BBF0BCC07C07AF7BC722B5A50E478CCC4690763023F1248DDC6C4D59EC63D59ABB4B1B85`
SHA512 | `3334DBA8E90E35A4881A1B7E4AD417861E908ECD1C8DF0D27C43346DFE836BE17C8AE2EF2ED188D7E8B866620C526F76CA33DA0EB037234868DD60302BEDA21C`
SSDEEP | `1536:TxTONUUIeF6ZyGhAUfKQTzBNer+CE+Ge+aPRL:rNKIrer+CE+GgpL`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OpenWith.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-0234BF822C4D6070819403F1BEF37F14.md) | 43
[C:\windows\system32\OpenWith.exe](OpenWith.exe-2C56E3290BED2E82AE666EEA01843073.md) | 49
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-2CBE77C5FE6617C174954532A0C189BB.md) | 43
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-49371805F24C419A1362A6672F0A8A76.md) | 43
[C:\WINDOWS\system32\OpenWith.exe](OpenWith.exe-49A571B29C15214D0D3B58A6A5180680.md) | 40
[C:\WINDOWS\system32\OpenWith.exe](OpenWith.exe-C9B3F7E1EB1970A715FA56AB076A260B.md) | 44
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-E4A834784FA08C17D47A1E72429C5109.md) | 49
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-FEAEEC585FEA59A316DDDD6C8505DA8D.md) | 54
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-0ED31792A7FFF811883F80047CBCFC91.md) | 41
[C:\windows\SysWOW64\OpenWith.exe](OpenWith.exe-1DFE1ED0A9EF0FA4FFE8D08DFB00F121.md) | 52
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-53E3F9F13C4C20B32CDA36FDEE865890.md) | 49
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-64148E3F7B8519DCB04FE5E96D5F1184.md) | 46
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-C6CEF89904DEC9404CCCD414E353C344.md) | 46
[C:\WINDOWS\SysWOW64\OpenWith.exe](OpenWith.exe-F1156D86892A581100107B8CDE2BF0AA.md) | 54
[C:\WINDOWS\SysWOW64\OpenWith.exe](OpenWith.exe-FADC6187E347B4820DA5B907B45F6024.md) | 49

## Possible Misuse

*The following table contains possible examples of `OpenWith.exe` being misused. While `OpenWith.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `title: OpenWith.exe Executes Specified Binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `description: The OpenWith.exe executes other binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `Image\|endswith: '\OpenWith.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- Legitimate use of OpenWith.exe by legitimate user`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Openwith.yml) | `Name: Openwith.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\test.hta`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\testing.msi`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\system32\Openwith.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\sysWOW64\Openwith.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


