﻿---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\system32\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `8FB3C4E8D6CF99B509F1907CA29B4414`
SHA1 | `2B80D0749D01E4BDA5BC2328EE52E4353CBADEB1`
SHA256 | `7F275ECEB1695FA7AD42B045B5D7FCA9045F274AD27A8D47BA9D152DCB2435E0`
SHA384 | `27EB4356E0B23DBFB026DFEDD064C8684663579C34354BAD1FDD8A21B97DAE8DD963BD2E73934702E98B4B3621BA7F54`
SHA512 | `004B13BB3C472917CB71BC2839433D95E26B6B0F3199EB2D496C01DCEDE131D3C022B609ADEFFE6B95CAB60D0DEF820A747E8E64DAAEE57AD752D162DAD7326E`
SSDEEP | `1536:lztYYuuibdLyFFw7fX1xjFRjYUBoGiuCLdyQGcMe7wX1qJF0T4Q/Sm1Z0aYuAp:AhT5yFGbXLDjX9OfGcy51HYdp`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2515 (rs1_release_1.180830-1044)
* Product Version: 10.0.14393.2515
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


