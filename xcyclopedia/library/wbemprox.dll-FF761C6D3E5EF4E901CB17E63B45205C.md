---
title: wbemprox.dll | WMI
excerpt: What is wbemprox.dll?
---

# wbemprox.dll 

* File Path: `C:\Windows\SysWOW64\wbem\wbemprox.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `FF761C6D3E5EF4E901CB17E63B45205C`
SHA1 | `31F3F9D0733780587F4D5E046EDFC1DC505AD477`
SHA256 | `D37FA85748116F9BF601A3C8BD6A7428EDCC5ABBED00F2E3749CD7D8C374E6B3`
SHA384 | `91B510F880B495F49F88E23105E27B32B71B7A32129DB38AA64F2792348C4D8ACE91ECF52A6023504A4381528D863950`
SHA512 | `3130688D5D64A1F912909A1757C093C7136AF2702BD8CECD5E2B9C008D6B584387C71D3E3DCFDC6EC641BF99AE01E44A22D573918878A6FE0DB44AB120B2E559`
SSDEEP | `768:RhsfJNJKOyHlOs4uq2xRQzdA1gV/KZsl:RhsfJ3KOyHcs4x2xRQzdA1gV/KZsl`
IMP | `9D055036D2E10337714BF0C5E850ECC9`
PESHA1 | `C275FBFE05BB5768AD40644D489C6F01090D58A0`
PE256 | `59C4FBD69326AA8BB1574B27E534A03CDCBD5694ABF132262BBADEBA17473A75`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x10003240 | 0x00003240
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x10002ea0 | 0x00002ea0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x10006380 | 0x00006380
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x10006480 | 0x00006480


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wbemprox.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d37fa85748116f9bf601a3c8bd6a7428edcc5abbed00f2e3749cd7d8c374e6b3/detection/


## Possible Misuse

*The following table contains possible examples of `wbemprox.dll` being misused. While `wbemprox.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemprox.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wbemprox.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


