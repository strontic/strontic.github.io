---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\WINDOWS\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `AAD6542A394B677EED278EDBBE97BA83`
SHA1 | `5393BEAE2F19B690D5380AC039E6729016452AF3`
SHA256 | `E8727E2CC66EDF54C05B86375779F7B4C6F98989E06E887D9AD0158AE645F2E4`
SHA384 | `56EA1FC4C729AA21EED7571B9B2B4CD5E0DCB240CD1C260B52114958E41FFC87C816C59AF11F68537B60336AFD36B58F`
SHA512 | `CEC68F0A1168E3B36D2F251B5770C744F85355DE82A62E71C3AE39A7EAF5D03EAE22463E3445B11B8366E922768A361149B948412B683892953D5D5568DD2D55`
SSDEEP | `12288:+RBOI0PvBZUhjr1doynmR7+gfL2YHctWNgh1CCbAhqYfw:iBOdUhtdhi7+74ghroqYI`
IMP | `E8DAA32DEAB1527251BBC2C75706037C`
PESHA1 | `2265511517ED76D2AE4FD11918811B0225609666`
PE256 | `352EC3AD659A7A0C8A2F0F167577158C7FB3EB645529CE7EDBCB62A26F76DE08`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\wimserv.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.194 (WinBuild.160101.0800)
* Product Version: 10.0.22000.194
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e8727e2cc66edf54c05b86375779f7b4c6f98989e06e887d9ad0158ae645f2e4/detection


## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\System32\wimserv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


