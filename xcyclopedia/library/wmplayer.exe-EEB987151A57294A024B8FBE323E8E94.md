---
title: wmplayer.exe | Windows Media Player
excerpt: What is wmplayer.exe?
---

# wmplayer.exe 

* File Path: `C:\Program Files (x86)\Windows Media Player\wmplayer.exe`
* Description: Windows Media Player

## Hashes

Type | Hash
-- | --
MD5 | `EEB987151A57294A024B8FBE323E8E94`
SHA1 | `29BF99CF79E6E43ABCF4C387B2426F1ED358BDE4`
SHA256 | `E38036765FDDA1E24BC2DBBD83E3FE7726CD3BDA85FCA555CAE25520A200918C`
SHA384 | `1886362E833B6A8A678B7A78A075D3B9C5572B1C59C1465A34EDDB4BB98478687A6DDDE24C074DF3C697E38EEDD271B2`
SHA512 | `3DF32906E4AF61484F75DD4E624AC25B2812EDA0F23D8A498DC9B60B5BF8FC54A760D9D62DC7AE883A37A2DE02C8FE92B807F773EE5046CFBEF9C2BA4810E12C`
SSDEEP | `3072:8xdohYkQr0jeLwJr95rJolNAzyP+msVK0Zh:lYQqLwhHrWsOP+5VT`
IMP | `4C7D471D886B447BB6DF2D2962D0414C`
PESHA1 | `F7C3E20D5234319A48A946BE51C4AB0BAFF738C8`
PE256 | `9918512D4E0DA6AFEE6418AE3FC8D9CAF23D257D661147488905F7F935A1405E`

## Runtime Data

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
* File Version: 12.0.17763.1 (WinBuild.160101.0800)
* Product Version: 12.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/e38036765fdda1e24bc2dbbd83e3fe7726cd3bda85fca555cae25520a200918c/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-4ACC57344531EEAC412463137996B8C1.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-B63509CF3065B3E9EE39B5A5280BD667.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-E173D6822FF7ACBBA5ADD79705D8DEB1.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-6AA4614C7ADE4C07F2F6E362D08DCF5A.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-A7790328035BBFCF041A6D815F9C28DF.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-1BA5B0F52DCD29859D8D3C5DB0F59410.md) | 71
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-5B0FE3F52814453B2EDDC48AE24193F5.md) | 66
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-AA5933CE16373F146EC28DA42A0700B7.md) | 66
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-29E52BFB44C74B2E3730F79D04082692.md) | 65
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-5607F957C0A4FF1B26F7D1A5F7D66814.md) | 65
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-71BDBF69E9CD49CFCEFC09C63E3B882A.md) | 65
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-113719B2BC20764BE5D1F2E1679E149E.md) | 93
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-89DCD2D4C0EC638AADC00D3530E07E1D.md) | 85
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-D86F92A0D66CD72733ECA3BE2B1A412C.md) | 85
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-275462C97656943B9F1A11F1701861FA.md) | 63
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-5E1E371446C859EB714A2C53BF9FAEC6.md) | 69
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-A89F75B51EAADA8C97F8D674B3EDB2F2.md) | 63

## Possible Misuse

*The following table contains possible examples of `wmplayer.exe` being misused. While `wmplayer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `Image\|endswith: '\wmplayer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


