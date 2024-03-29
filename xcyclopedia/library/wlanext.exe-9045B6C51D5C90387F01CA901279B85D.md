﻿---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
excerpt: What is wlanext.exe?
---

# wlanext.exe 

* File Path: `C:\WINDOWS\SysWOW64\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `9045B6C51D5C90387F01CA901279B85D`
SHA1 | `F1C5FF3441A18DDE20DF04EBAFFEAB94EFCAC0FA`
SHA256 | `EEA910712ED819AB42D80833DF0B0666DE6D8971A03A791FC4D598AEC75EFA70`
SHA384 | `2CB649DDF65EF40800556A2614300D6C92306F8DF6EE46D118EF9EF75912966E846F8A19BB461F419B78110A4AA1BE1C`
SHA512 | `1818EB37D1FE38EEF89EC88F1B2FA5CA5491709D4B9C1A9CC2214C2F8AE2FE7EC6D2FAB4320FC59A7B96826792E7169DA2935EC2B10141019028BA9425161100`
SSDEEP | `768:Baom1KGJQ9yJKySgGtPtdCkdhy/RkS6NAAu6H3VTtkyHba9ftjG/FTR4m4kRmbtA:wo5S4TLgGtFriySuAABlfdSm4bZudD0`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


