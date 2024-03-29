﻿---
title: ServerManager.exe | Server Manager
excerpt: What is ServerManager.exe?
---

# ServerManager.exe 

* File Path: `C:\windows\system32\ServerManager.exe`
* Description: Server Manager

## Screenshot

![ServerManager.exe](screenshots/ServerManager.exe-83D44E309295488A933B084288B976D8-1.png)
![ServerManager.exe](screenshots/ServerManager.exe-83D44E309295488A933B084288B976D8-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `4400A0F9CAF4BAD014530A98798A6CA4`
SHA1 | `DF0235171FB056A2AAE05E530DB46E34B942234C`
SHA256 | `FFB509F4A4E6619FB4535DE95A41E7BDF08AC919AC564378E14411440ED9C6A9`
SHA384 | `1543BE09650936C11BEEEFC3CC827AE592551A9C050DC77C23F17A41B2E05D8125601615C5833A42172EBC59C5AF7575`
SHA512 | `AB935562879A83B640D701B5738DF706FFD1AF0DDC848579B9292FD9B15E9C24B5F1223E6B21B6A9773D766C98242A23D57D23C54E229989F673578287F3C9F8`
SSDEEP | `6144:XixEpwpp+SNdi6gozVvPUHZsGChyB0M8VGQ8b:XiSwpp+SNQtivPyCYy7Gvb`

## Signature

* Status: The file C:\windows\system32\ServerManager.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: servermanager.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17238 (winblue_gdr.140723-2018)
* Product Version: 6.3.9600.17238
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ServerManager.exe` being misused. While `ServerManager.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\ServerManager.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


