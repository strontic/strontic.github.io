﻿---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\WINDOWS\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `BA2347843ED36587134C3B8AF434EC8C`
SHA1 | `AD97137043D41A4651C65CD98AE6D9AAAD11BE4B`
SHA256 | `A806AF080DC55499462C55C93E7EB701B01E71079DE9ED0E5F439C1257F2725D`
SHA384 | `8934B89F58F1479E55E8DCF570A538C14457EF631C9EFA5B9C19AAD0590E46F54093410832148EE8E437B3B6B6C10F3C`
SHA512 | `1B44CE4A8A0BDD4ED0CAFE4716B83DC1D25DC7EA28CE67979546FAFA51888E90A98979F562255C63BAE9A9032ACC940D2686B35A22990411B44DCAC2DEAC2E0D`
SSDEEP | `192:ik1L4V5rSrqEpitQ3xFey4zP7UJDoGoDL0FZqGxZPWmpfPWbjMiWSBWKX:ik1LLqElBFDk6DoG7ZlxZumfsMiWSBW`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\rasautou.exe](rasautou.exe-81A6467E638E5C15C0C0ABB4DA13DEAD.md) | 55
[C:\Windows\SysWOW64\rasautou.exe](rasautou.exe-DFDBEDC2ED47CBABC13CCC64E97868F3.md) | 57

## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `title: DLL Execution via Rasautou.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `description: Detects using Rasautou.exe for loading arbitrary .DLL specified in -d option and executes the export specified in -p. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Rasautou/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `Image\|endswith: '\rasautou.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


