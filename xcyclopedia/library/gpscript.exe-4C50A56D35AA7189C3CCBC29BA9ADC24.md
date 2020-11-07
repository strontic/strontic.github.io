---
title: gpscript.exe | Group Policy Script Application
excerpt: What is gpscript.exe?
---

# gpscript.exe 

* File Path: `C:\Windows\SysWOW64\gpscript.exe`
* Description: Group Policy Script Application

## Hashes

Type | Hash
-- | --
MD5 | `4C50A56D35AA7189C3CCBC29BA9ADC24`
SHA1 | `CA1436CC32BAB1A5E9F420280D6391F57DEEB48D`
SHA256 | `E2434CD5C049DB2976702490C5E34C0134A9F158FA76020C62DE4A6DC4AAA25F`
SHA384 | `14A4976A8B69586A7990661D043151D2A1AFA298D1C229953DD776F40799043471BFA9276EA8EE10C3B84F77AF9254D6`
SHA512 | `F5F053925C81E74598CF24B7700FA623FAB3198DD940223FEDE522894D8169BBF3A5AA00F2930E8EF73FFF3887A26DCFF5AACE9E2AD8A1D660DE29EACA597DC4`
SSDEEP | `768:poMQyZlU+Bk3f8hor4US+XLC2Ece+b9GZpCTdTR7LIELR/X:pB++Bk3f8hor4t+7C2EXZpCTdTRLIE1f`
IMP | `5C9ADBC2A218AEE3FE31C3D2507C5911`
PESHA1 | `59AD00A4A1AD9EA6BEC615846EADBC0624DEC3BB`
PE256 | `0C2A3D0D6A22CAFD8738BB80A1103AF123FB123F67A2615BE8EE15A4C565FBDC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\gpscript.exe |


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
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/e2434cd5c049db2976702490c5e34c0134a9f158fa76020c62de4a6dc4aaa25f/detection


## Possible Misuse

*The following table contains possible examples of `gpscript.exe` being misused. While `gpscript.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


