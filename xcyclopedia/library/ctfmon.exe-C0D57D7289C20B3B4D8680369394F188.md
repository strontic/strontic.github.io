﻿---
title: ctfmon.exe | CTF Loader
excerpt: What is ctfmon.exe?
---

# ctfmon.exe 

* File Path: `C:\WINDOWS\SysWOW64\ctfmon.exe`
* Description: CTF Loader

## Hashes

Type | Hash
-- | --
MD5 | `C0D57D7289C20B3B4D8680369394F188`
SHA1 | `CD1F9222C9C8F4704D6E53453027340602D03A5E`
SHA256 | `CED6EA595E441B17DCAC9109031215601728ED04CDADA8D9E1893546AC3E1657`
SHA384 | `5D7E1204AE2735A55CB41302012DDAE47C157762ACE59997BFCC61244C6357AD345E9EFF7154C1F65BEF3D47EDD0E349`
SHA512 | `7C4F19BA728D593BD345DAE0CCBFC00F585BED107CE37F2DF20C2DE7651DA35E16992CF7332FF97736581C42A47332BDD0DF0A501CA12D2A0AED23B321A7BC1D`
SSDEEP | `96:M4WjLouIAnAwAuEaAp2hpHXDGjoaqHjK9osw2mpDJ7pRKR0LEWAgWwtevwDp:6LIbu2J0m9osw2m/iWAgWGp`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-1B19D302D7FFA3D0901B3D990A4E8E12.md) | 55
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-29656B9E6B04C85E7BF4018B6844BE28.md) | 33
[C:\WINDOWS\SysWOW64\ctfmon.exe](ctfmon.exe-82FEE2FD4957DD49F911D12C082AA49C.md) | 35
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-97D7FF9EED95ADF3785F2D0219EEED46.md) | 61
[C:\windows\SysWOW64\ctfmon.exe](ctfmon.exe-BE80808B5FE1D9C9351653EEC814A75A.md) | 33

## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_four_element_sword.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_four_element_sword.yar) | $s1 = "\\System32\\ctfmon.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s0 = "%USERPROFILE%\\AppData\\Local\\Temp\\Low\\ctfmon.log" fullword ascii /* PEStudio Blacklist: strings */ /* score: '43.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s1 = "%USERPROFILE%\\AppData\\Local\\Temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '37.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s2 = "\\temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '28.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


