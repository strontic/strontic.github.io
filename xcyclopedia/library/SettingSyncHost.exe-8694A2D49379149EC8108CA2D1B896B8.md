---
title: SettingSyncHost.exe | Host Process for Setting Synchronization
excerpt: What is SettingSyncHost.exe?
---

# SettingSyncHost.exe 

* File Path: `C:\Windows\system32\SettingSyncHost.exe`
* Description: Host Process for Setting Synchronization

## Hashes

Type | Hash
-- | --
MD5 | `8694A2D49379149EC8108CA2D1B896B8`
SHA1 | `F0A6CCE43E61603CC074C3C0B76EB4F9998689D2`
SHA256 | `D6A24CCC2D3FA93E3F9E5053C9DA05A0CA2625C82BE548543386D5AE5518B001`
SHA384 | `941E30A6B8A332BBB0CEB93892B84CFE65E44E069267580AB3CADB7379DD2051182090B107473E42FE1C51EAAD7FD609`
SHA512 | `C1FE1C6134B49FBE7A3C76EA11BCA941EAC9D548A6F9FF182A09EF286EE66984F28CF29B4822CAD29E2C2BE45015D3CEE69D9ED269033D8A8B7F3BC5C1C4537B`
SSDEEP | `12288:JNE3C87eVaxbbHPSAvK4qhO/flsUTVmPjNHyE:zES8aVw/vK3hkflsUT2pHyE`

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
* File Version: 10.0.14393.3085 (rs1_release.190703-1816)
* Product Version: 10.0.14393.3085
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


