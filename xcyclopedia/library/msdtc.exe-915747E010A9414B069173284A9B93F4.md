﻿---
title: msdtc.exe | Microsoft Distributed Transaction Coordinator Service
excerpt: What is msdtc.exe?
---

# msdtc.exe 

* File Path: `C:\windows\system32\msdtc.exe`
* Description: Microsoft Distributed Transaction Coordinator Service

## Hashes

Type | Hash
-- | --
MD5 | `915747E010A9414B069173284A9B93F4`
SHA1 | `26D909845177E3264C3D6038B754AD60EFB7FC21`
SHA256 | `8A335C28FE1EF96DD71485877F2E86155D24B5614ACE05468F4B07E2ACD56331`
SHA384 | `BFBFE46F4CE4DF0EAFB73BD78F77F44D562AB3A907D07378FC6DA3F688D16E361CBCEF91CE0F562E5B13C65234566C58`
SHA512 | `376823AA048EB50ADFCC51DEF9B45F8D7A8CCCA34A54C677125D8D292C00FF722197C4DD61CCBDE4E54DD098E436D3B3B7F5EB830753CBF17051E1C2A6E6A541`
SSDEEP | `1536:0/ftWBW6VH75ARMstrKGQE1A0a4qDLZAQcEzok3E8vroH3S7NtiXE/L/:LfbnsB3Qpv7fcmEAkyXiq/`

## Signature

* Status: The file C:\windows\system32\msdtc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: MSDTC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10530.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msdtc.exe](msdtc.exe-2EF846AC66E181BE820B513DBC15B5D2.md) | 65
[C:\Windows\system32\msdtc.exe](msdtc.exe-308F08347923DEEDE7BC03EC7D485841.md) | 66
[C:\Windows\system32\msdtc.exe](msdtc.exe-7215CE218BDEAD41B708F098258CF972.md) | 66
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-DC59FE37CFF118B6DAC426FE9923B32C.md) | 66
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-ED13DCE3E438FD8BD3DAEC15460C42A0.md) | 65

## Possible Misuse

*The following table contains possible examples of `msdtc.exe` being misused. While `msdtc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [image_load_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/image_load_pingback_backdoor.yml) | `Image\|endswith: 'msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_pingback_backdoor.yml) | `- 'msdtc'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_session_highjack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_session_highjack.yml) | `- '\msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [2021_T2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2021_T2/README.adoc) | `Msdtc`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


