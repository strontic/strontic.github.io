---
title: ie4uinit.exe | IE Per-User Initialization Utility
excerpt: What is ie4uinit.exe?
---

# ie4uinit.exe 

* File Path: `C:\windows\system32\ie4uinit.exe`
* Description: IE Per-User Initialization Utility

## Hashes

Type | Hash
-- | --
MD5 | `BBF8EE53B30855A956873F173068DB01`
SHA1 | `A1BCE35BC6ACC786806EE39AE85BEAEF1D5FF38F`
SHA256 | `ADFF353BDCEBBF38EE48A1255FBF1C7722758969F257188592538251D3BBB9B3`
SHA384 | `7E3B102D1D2E4788CFC9072B57E41F8577F631317EEAB0E4148F2927486340C063BF119535F721C08F7455CDF745EB4B`
SHA512 | `2DEE795D6DF7A7B7FE76DF2A8A3ADB2185C4F7386F56681F64849EB6A421BF044D0D1FF76A5DF14850E21D9CF689FAC6064D23B3A4804FE0E1208404A037B26D`
SSDEEP | `12288:hG3lgNCIQHgzZpIjfbOToMrEDL1FwhdFbjzlZXHFtlxJuZUQd3i/SmDtVvg8JANs:FCIlVpIbbO`

## Signature

* Status: The file C:\windows\system32\ie4uinit.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: IE4UINIT.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 11.00.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ie4uinit.exe` being misused. While `ie4uinit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Name: Ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Command: ie4uinit.exe -BaseSettings` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Description: Executes commands from a specially prepared ie4uinit.inf file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\system32\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\sysWOW64\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- IOC: ie4uinit.exe loading a inf file from outside %windir%` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`IE4UINIT.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


