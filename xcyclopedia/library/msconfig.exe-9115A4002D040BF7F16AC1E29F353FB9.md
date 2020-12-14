---
title: msconfig.exe | System Configuration Utility
excerpt: What is msconfig.exe?
---

# msconfig.exe 

* File Path: `C:\windows\system32\msconfig.exe`
* Description: System Configuration Utility

## Screenshot

![msconfig.exe](screenshots/msconfig.exe-FA81544250A477790C003D6D88256078-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `9115A4002D040BF7F16AC1E29F353FB9`
SHA1 | `91B7CAE13D59A181627063EFBBD4CE07B57954B6`
SHA256 | `9015EDEB220C2EAD7317B34466BEF90C413B383FFFB5F124585CB89AA29DCE69`
SHA384 | `63031526A2A0E2B6C38944C38D7843FEDDD7D4A8A01530EEDB98C4C85A9C748A870C868772991A4E6315D29B44DD3F69`
SHA512 | `7E01484498E54F9E9DEE8CAF36D260B5CC5AEAB0F8E396EE0BE1347527790B3F1CE0215199B6A2B5FA470BEFFCC454D36FCDDCAC319C9A4FE2006AB95DD27EFC`
SSDEEP | `3072:sW38gnQSkI9lIV3kGFOI74CT0rCfUd0/HlGJRA1Q:XhpBFGFOIsCT5UdSGJRW`

## Signature

* Status: The file C:\windows\system32\msconfig.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: msconfig.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msconfig.exe](msconfig.exe-C39148DD0D650E2C49095237998218F2.md) | 41
[C:\Windows\system32\msconfig.exe](msconfig.exe-EA390568A41C03B6327AAE1873664B45.md) | 55
[C:\WINDOWS\system32\msconfig.exe](msconfig.exe-EC284B6D1AFBBA44211F4F0C3EA44838.md) | 44
[C:\Windows\system32\msconfig.exe](msconfig.exe-FA81544250A477790C003D6D88256078.md) | 46

## Possible Misuse

*The following table contains possible examples of `msconfig.exe` being misused. While `msconfig.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Name: Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Description: MSConfig is a troubleshooting tool which is used to temporarily disable or re-enable software, device drivers or Windows services that run during startup process to help the user determine the cause of a problem with Windows` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Command: Msconfig.exe -5` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Usecase: Code execution using Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Path: C:\Windows\System32\msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- IOC: msconfig.exe executing` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`msconfig.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


