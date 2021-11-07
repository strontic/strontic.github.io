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
MD5 | `A7790328035BBFCF041A6D815F9C28DF`
SHA1 | `7EE75C72F50D37B1C69F72F33BA1063E8278B29E`
SHA256 | `6CEE4877B6663FC93E94ECC0489834379D2FAE6C363EB36035D863733AB7C304`
SHA384 | `40F3069354EE025236180121E07F0346BB97586D0D77E90D377286D4EDFDA37DD2F0CDF42DF85D1F6CEBFA41A41926B6`
SHA512 | `125D7E387A90DDE64858A9B82E237233F3262F22F47474714D3A3FAD193D1CD3BF4823E239B967AE73979BF9492DC15B3D57ADBDDF91831E5B6AA6B18906AA09`
SSDEEP | `3072:l91ZohYkQr0jeLwJr95rJolNAzyP+msVK0Zz:oYQqLwhHrWsOP+5VT`
IMP | `4C7D471D886B447BB6DF2D2962D0414C`
PESHA1 | `0C53437A9E9AB0504D433D0ECE87F7E82781DA96`
PE256 | `101D1AD2E3D6203C90D64CCF3EF0580AFA6AB578D1B6E89AAD196D56CA790798`

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6cee4877b6663fc93e94ecc0489834379d2fae6c363eb36035d863733ab7c304/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-4ACC57344531EEAC412463137996B8C1.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-B63509CF3065B3E9EE39B5A5280BD667.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-E173D6822FF7ACBBA5ADD79705D8DEB1.md) | 63
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-6AA4614C7ADE4C07F2F6E362D08DCF5A.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-EEB987151A57294A024B8FBE323E8E94.md) | 96
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-1BA5B0F52DCD29859D8D3C5DB0F59410.md) | 66
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-5B0FE3F52814453B2EDDC48AE24193F5.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-AA5933CE16373F146EC28DA42A0700B7.md) | 65
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-29E52BFB44C74B2E3730F79D04082692.md) | 63
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-5607F957C0A4FF1B26F7D1A5F7D66814.md) | 63
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-71BDBF69E9CD49CFCEFC09C63E3B882A.md) | 63
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-113719B2BC20764BE5D1F2E1679E149E.md) | 93
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-89DCD2D4C0EC638AADC00D3530E07E1D.md) | 88
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-D86F92A0D66CD72733ECA3BE2B1A412C.md) | 85
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-275462C97656943B9F1A11F1701861FA.md) | 63
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-5E1E371446C859EB714A2C53BF9FAEC6.md) | 68
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-A89F75B51EAADA8C97F8D674B3EDB2F2.md) | 63

## Possible Misuse

*The following table contains possible examples of `wmplayer.exe` being misused. While `wmplayer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `Image\|endswith: '\wmplayer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


