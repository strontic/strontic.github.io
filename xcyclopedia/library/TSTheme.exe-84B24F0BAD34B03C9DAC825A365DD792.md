---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\WINDOWS\SysWOW64\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `84B24F0BAD34B03C9DAC825A365DD792`
SHA1 | `3D96E1535487CE03121BDD97A2D6F2DE7735D93C`
SHA256 | `718F32125A1F03DAA778CB3A01BD18E782B653D613ADD53670E6670775C018B2`
SHA384 | `90AB12716776ABEA0AC615C9A10EF1BABB0614EED067B3E90BB98F0A4090ADFEB2782B4523AA6BC1C5A321FB1776AF26`
SHA512 | `50599F9F37EDE696880687CA12D00887F757A08D13B4EA04DD27D8F8659A1D9B3A86263C0F24B11408DA71997DB85813ADE1D610D6475EB9445E8F742E360B1A`
SSDEEP | `768:bk4i/Ayw9twnfyVi2/DtkMtTLWFVi8V1VIBRPXyF6qjaJbisf5dU:bJi/Ayw9twnqwCDtkNFVRaXyF6qjaJ`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\TSTheme.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


