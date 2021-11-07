---
title: SettingSyncHost.exe | Host Process for Setting Synchronization
excerpt: What is SettingSyncHost.exe?
---

# SettingSyncHost.exe 

* File Path: `C:\WINDOWS\system32\SettingSyncHost.exe`
* Description: Host Process for Setting Synchronization

## Hashes

Type | Hash
-- | --
MD5 | `0AD082F50295AB0632942B31024A1DF9`
SHA1 | `6A4B7C9670826DC7E1EDB4A65D21E854F613C0D3`
SHA256 | `55A7313DBEE536185207FB38D23BD080908AD1F6709A3E1AF196A1C1F8BF46B3`
SHA384 | `057391E646CD69A056AA0E7B36087C5B246A6E45DB7EDD37CCAC70F660B3BF6ACB612B411FDC7C4CF2FFDF5FB846A83F`
SHA512 | `4697EFE76F9A607B20C2224A02A62E6D96EB82E9BBA2C9DE45EA9D51AEEC25B74F0496F8E98DB584DC9DB72BDF2691FD73653A93A18A04146191A2C18FFD47DD`
SSDEEP | `24576:6P8gM1JEemUovOL2WwAPgmwjTel+mCggax:2FHe9l2kPgXTeEmxjx`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SettingSyncHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.239 (WinBuild.160101.0800)
* Product Version: 10.0.18362.239
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SettingSyncHost.exe` being misused. While `SettingSyncHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `title: Using SettingSyncHost.exe as LOLBin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `description: Detects using SettingSyncHost.exe to run hijacked binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `- https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `Name: SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScript anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Command: SettingSyncHost -LoadAndRunDiagScriptNoCab anything`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\System32\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Path: C:\Windows\SysWOW64\SettingSyncHost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- IOC: SettingSyncHost.exe should not be run on a normal workstation`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [SettingSyncHost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/SettingSyncHost.yml) | `- Link: https://www.hexacorn.com/blog/2020/02/02/settingsynchost-exe-as-a-lolbin/`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


