---
title: WerFault.exe | Windows Problem Reporting
---

# WerFault.exe 

* File Path: `C:\windows\SysWOW64\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `66EF7E5E7D794CEEEE1BB1894B310ED6`
SHA1 | `4D881D50A3B6E3D2CCCD9EE7346155D408BFD590`
SHA256 | `BC3A271DEB217692A1C628D9F987361DD020C91BFD0D1AF509FB124EF4127CE7`
SHA384 | `0636DEBDA0FA1C398A609D9FB7CC4D0C7E8EE2271B9E2C47187608F7AC7A636A78DB95A079D01D09FDDC1187143BC44C`
SHA512 | `DCACFC74977EF749355430B76569A497FA2D00B4F8DE4A5586D4DE9B7ABE94B12E72B338AD5E969EEF58906365A672E2E0B7ECC3131B9A9FA06AF99B9E6FFB5A`
SSDEEP | `12288:41gQOji0As2cfF57opXqn+1qFFlSc2HywoC:ugQOji0As2cfFOa+1qFFlScyhoC`

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
* File Version: 10.0.17763.1282 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


