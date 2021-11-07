---
title: DismHost.exe | Dism Host Servicing Process
excerpt: What is DismHost.exe?
---

# DismHost.exe 

* File Path: `C:\Windows\system32\Dism\DismHost.exe`
* Description: Dism Host Servicing Process

## Hashes

Type | Hash
-- | --
MD5 | `1AE12EB030839C374CF89CA82B7F45C0`
SHA1 | `E3040F7D963A366AD6FCF0DE3D64A0277CD9A140`
SHA256 | `F81B2F9FBBFA6E16D59D8AB703B3EF5A4A63BF4B23E002BD7B5BFA01CE62B937`
SHA384 | `E6A728567D14A45598152E1CF04309B68CECFDFCF7F2FFFC9B65F548DB81743CE23EF65776A7BF6050005936459C1ED4`
SHA512 | `854B67DE4E03124D8B94EF71EDAD92876225F6CA4EF82D8319287C001D4B0F3335C50C95424E4A5DA14F49F7CEECEF5C303B862B03D0C1F5E0367BC3A265995A`
SSDEEP | `1536:gcyoV9r967An2g8+V3NkqmKs0dwymJaw9oyDTSEjf9/DSzLO5LxMQSGP8:gcyk9rU7G22V/7w56fy5LxDBU`
IMP | `C601FA732FF0599995A293BA7882B84D`
PESHA1 | `DF41B1F3C84CEF9439CF49B592B9B80A43160D3C`
PE256 | `7945F4870C90EA05B65A0A5A4A237C442294FDDC550988CE5DC5E99BF2866303`

## Runtime Data

### Child Processes:
csrss.exe wininit.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DismHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1518 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1518
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/f81b2f9fbbfa6e16d59d8ab703b3ef5a4a63bf4b23e002bd7b5bfa01ce62b937/detection/


## Possible Misuse

*The following table contains possible examples of `DismHost.exe` being misused. While `DismHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- 'dismhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `title: UAC Bypass Using DismHost`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `description: Detects the pattern of UAC Bypass using DismHost DLL hijacking (UACMe 63)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `- '\DismHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `- '\dismhost.exe {'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `Image\|endswith: '\DismHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


