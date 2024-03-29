﻿---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\windows\SysWOW64\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `92D184C0851753F67DC5BE6126FA9CFD`
SHA1 | `A30F63719FBEEA42F497088D4645E443AA1C3F23`
SHA256 | `D7161581BAAA04FC2E515BF724CC2CC17C25250A3574717D53A8F9D638E3D30F`
SHA384 | `A94EE3E7665D16B3EEFC2BD740DA42298861C7FE05B2E558091A2C6FD421515E75385E8DCF45E6DE3637BB210DE09B7B`
SHA512 | `AE85F65A474831EB1B40644B30F8A9797336D206B4C3F06054CC60C8ACC30AFE0559C88889B2EA94A8BA7C0AA5394033B355A64AB81A89FBAC21312AC5DFFC19`
SSDEEP | `1536:l/n5JY+scMJsM8VETCJFjfUYYAHa2fp2LMSza9fjjvA8CPmCC4MDg+NCHaf4CI3p:l/rY9x6YDyvAskHafZIr4W5ylo4RqJ`

## Signature

* Status: The file C:\windows\SysWOW64\wbem\WMIADAP.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


