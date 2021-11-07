---
title: DismHost.exe | Dism Host Servicing Process
excerpt: What is DismHost.exe?
---

# DismHost.exe 

* File Path: `C:\Windows\SysWOW64\Dism\DismHost.exe`
* Description: Dism Host Servicing Process

## Hashes

Type | Hash
-- | --
MD5 | `A20547212DECEB8EEE843306F27FBB61`
SHA1 | `7CC871BB0EBBFD4E0AAE497802770ECDBE5B1A46`
SHA256 | `2DB594B74D10F59D347F30A9217EFA3FEC134D73668433FE562FF94E2C95287C`
SHA384 | `D2E33D0FC4DBF97907278B438805E98AFC16FE79E2F1C923C8DC86E3F8E386690EB10A8C22C73D62AA062AE7F4EFE0B6`
SHA512 | `1737D684CC35085A470AA0674D6101D30DF95D332019D35601FD80B734FAD39A2C75C1FACBC35EAA46F95DA25D9D80359C0452FA136CA7ED9AF34D52AC01B4B8`
SSDEEP | `3072:sfQK0V5VY4YviGxkay8UwGHuJLoLZ32cbSc0Sy:8wGZvip8Uw2IgZ32ZHz`
IMP | `94DD26F264047715454E65BDBF87F739`
PESHA1 | `CF50C22F1CC1AF6768A0000BA740415979A6F772`
PE256 | `4D1407186C8390C2291C5FC38FD4139E4DCE9A9F1DC4BDF1C58E36113E6DE2F3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\Dism\DismHost.exe |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/2db594b74d10f59d347f30a9217efa3fec134d73668433fe562ff94e2c95287c/detection/


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


