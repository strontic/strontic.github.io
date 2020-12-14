---
title: gpscript.exe | Group Policy Script Application
excerpt: What is gpscript.exe?
---

# gpscript.exe 

* File Path: `C:\Windows\system32\gpscript.exe`
* Description: Group Policy Script Application

## Hashes

Type | Hash
-- | --
MD5 | `30428B3173B15CFE22457523CE381A74`
SHA1 | `4CF52B13BBB97F97C07B90C61C7546E97A4D4BBE`
SHA256 | `8BEEC3990687ECBDDF7A7E2A4278F8C220314688F914C5D87280A55A97FB6DFA`
SHA384 | `873D3EACCDC98BCB0DBE10AB277011DBADC6E59FE15C31755E3BA442EDCC075CFD33FB458D528F9EB31E8B75719331A2`
SHA512 | `D8FCBA2A25868A18DD834402657E8F57AC069295AA7CE1FC8E26B2F1267B19F9F8818650BB2BB9677F5A096AE822E780ADC33F03BF2914421D246737A3280A34`
SSDEEP | `768:V3L2ztRYJU4MgmP2I2dKAIyel0ex0HLykudTSY2R6OSJ:ZIHGUvBf0KAe+ex0HRudTn2R6nJ`
IMP | `BAC4D390D64C9513CF9CEE8307C17C47`
PESHA1 | `DD48D0C2467139A90A35BFF1E3D2513C37C37E66`
PE256 | `DAAFD67A4F2D605ECF28E27571E75D82E3C132A4267063709C0C83ED70C6971D`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPSCRIPT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1518 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1518
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/8beec3990687ecbddf7a7e2a4278f8c220314688f914c5d87280a55a97fb6dfa/detection/


## Possible Misuse

*The following table contains possible examples of `gpscript.exe` being misused. While `gpscript.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `Name: Gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /startup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\System32\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\SysWOW64\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- IOC: Execution of Gpscript.exe after logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Link: https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/` | 



MIT License. Copyright (c) 2020 Strontic.


