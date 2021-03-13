---
title: ie4uinit.exe | IE Per-User Initialization Utility
excerpt: What is ie4uinit.exe?
---

# ie4uinit.exe 

* File Path: `C:\WINDOWS\system32\ie4uinit.exe`
* Description: IE Per-User Initialization Utility

## Hashes

Type | Hash
-- | --
MD5 | `21CB4852E203215BB472B1804DA5C80B`
SHA1 | `78C3E5CF258E100089C703A130580B2E64915C16`
SHA256 | `856955EB4EBF79FD8C45B58E4271FB7F45F2659C88A5E94BA2D8E5484F4E9E11`
SHA384 | `E8826384884AEEFA213366D6BE216732E31D39F3DFC4A7DF4EAE31DDFDAD4CFCCEE2F90A530D738AD54653BDFB4A1EB4`
SHA512 | `A88FA5508AD574D73F08828EEC29426E1C5D2CA0DBE28115CB1D72EEA272A80FD78E24E81EF25500DDE30C33B923155E360A603451872C6F4EA4906FB7D30F7B`
SSDEEP | `6144:MPyvRc+5+bRhN1Wjl4K/eZb8vm1YWAIu350PK:cypFqRhPK4KW8vm1YCuwK`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IE4UINIT.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.18362.1 (WinBuild.160101.0800)
* Product Version: 11.00.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ie4uinit.exe` being misused. While `ie4uinit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Name: Ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Command: ie4uinit.exe -BaseSettings`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Description: Executes commands from a specially prepared ie4uinit.inf file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\system32\ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\sysWOW64\ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- IOC: ie4uinit.exe loading a inf file from outside %windir%`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`IE4UINIT.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


