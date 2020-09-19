---
title: WerFault.exe | Windows Problem Reporting
---

# WerFault.exe 

* File Path: `C:\Windows\SysWOW64\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `9F378087906FFDFB968BCBE88BCBC840`
SHA1 | `DF5CAC004E813F964E77DF0F4BEEDE2B324A78BB`
SHA256 | `0EEFE1DDE46D019B6BE035FED5ECC867C9965CB13362F940DAD5E0F02DAFB4E3`
SHA384 | `79952B6D10856CE71BA330A1C8266898BB739E402FCA89858A88F06421FC56E22FEB0A152614838FAA8800213A0C117E`
SHA512 | `DC471DC56E32E878F009E9BA4E8D7B949DBC9C7913A9167C928A05BAB1EAF380794D1748A5350D95A1A012915A5B5FDD033F814B6E5858666C11093C9918C18C`
SSDEEP | `12288:XX/jTrVbMkWlYM/eOwTFNwJRMtqFFHzc2HywYM:XvjTrVbMkWlYM/eFgMtqFFHzcyhYM`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\WerFault.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1339 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1339
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


