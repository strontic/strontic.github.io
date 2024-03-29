﻿---
title: wmplayer.exe | Windows Media Player
excerpt: What is wmplayer.exe?
---

# wmplayer.exe 

* File Path: `C:\Program Files (x86)\Windows Media Player\wmplayer.exe`
* Description: Windows Media Player

## Hashes

Type | Hash
-- | --
MD5 | `6AA4614C7ADE4C07F2F6E362D08DCF5A`
SHA1 | `4016C560BF32ED6DD672A146891D33760D0E4C46`
SHA256 | `90D10CC4636741F5B8A9DADDB43B22561CF4CA647D2AC7197621C124BF0EB53F`
SHA384 | `6B0CEF08237EB422988044B1D7B38F4D7F560EBB6B13BE84A2B69F28F2B30C5193218A2DC5E47860C39D7F1C733B6FA2`
SHA512 | `2AFC953BF8C7B3FE54957D9BC3D9AF19A984A926AF4351256F37F2972EFC33C38762EDD84F6100A458CC2D6BB91F7D510355D98F613CA7D19D3C71495F5BC401`
SSDEEP | `3072:TWEZohYkQr0jeLwJr95rJolNAzyP+msVK0Zi:OYQqLwhHrWsOP+5VT`
IMP | `4C7D471D886B447BB6DF2D2962D0414C`
PESHA1 | `29440FCBC5108AF455215E4A207BCD21C885DB96`
PE256 | `14EAC1C7203CC9EF9BAB84DCA3821C8C5CF36CCDF56EDFCCA9AF3F10DB534730`

## Runtime Data

### Child Processes:
setup_wm.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Media Player\wmplayer.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmplayer.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 12.0.19041.1 (WinBuild.160101.0800)
* Product Version: 12.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/90d10cc4636741f5b8a9daddb43b22561cf4ca647d2ac7197621c124bf0eb53f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-4ACC57344531EEAC412463137996B8C1.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-B63509CF3065B3E9EE39B5A5280BD667.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-E173D6822FF7ACBBA5ADD79705D8DEB1.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-A7790328035BBFCF041A6D815F9C28DF.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-EEB987151A57294A024B8FBE323E8E94.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-1BA5B0F52DCD29859D8D3C5DB0F59410.md) | 66
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-5B0FE3F52814453B2EDDC48AE24193F5.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-AA5933CE16373F146EC28DA42A0700B7.md) | 65
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-29E52BFB44C74B2E3730F79D04082692.md) | 63
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-5607F957C0A4FF1B26F7D1A5F7D66814.md) | 63
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-71BDBF69E9CD49CFCEFC09C63E3B882A.md) | 63
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-113719B2BC20764BE5D1F2E1679E149E.md) | 93
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-89DCD2D4C0EC638AADC00D3530E07E1D.md) | 85
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-D86F92A0D66CD72733ECA3BE2B1A412C.md) | 88
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-275462C97656943B9F1A11F1701861FA.md) | 63
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-5E1E371446C859EB714A2C53BF9FAEC6.md) | 68
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-A89F75B51EAADA8C97F8D674B3EDB2F2.md) | 63

## Possible Misuse

*The following table contains possible examples of `wmplayer.exe` being misused. While `wmplayer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `Image\|endswith: '\wmplayer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


