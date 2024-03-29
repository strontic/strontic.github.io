﻿---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\SysWOW64\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `510C04C52F5CB9469A55FD440A0731FE`
SHA1 | `A2E10B23A38A1D18873FBE73B54038A2F56E9619`
SHA256 | `15B614D405F175B5EA9E5434BEDB1B9E9F5A7826CFCBD67AA1C544EBB0028BD8`
SHA384 | `CF31F05504B72133EF3C4177D4C16435F725582F008529CE4FA912214C1234E3EB48AF76672C185768A33870031CF30D`
SHA512 | `FCE3D369832F92A4C3CBD5536A6D65C6296737DB2C815EA4F90BE0E216F636E051A327FF6020812DCC8A319FCA567E25785FE4C1DF00D5A078F8AE26E664AF1F`
SSDEEP | `3072:crvATAIA7F0zcMQCGye3W9pClAO7jgpQdXfqu:OvHF/CGye3W9efQpQdXfF`

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


