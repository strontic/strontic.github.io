---
title: SearchFilterHost.exe | Microsoft Windows Search Filter Host
---

# SearchFilterHost.exe 

* File Path: `C:\WINDOWS\system32\SearchFilterHost.exe`
* Description: Microsoft Windows Search Filter Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2296B4F9F71EFB1FCC195C85B8EA3ED9`
SHA1 | `AA0CC5CA1AA0AC8AA5C695BACB35F31B629FFAC4`
SHA256 | `1584A43CE318552E1191E3B550ECEB1B8E291C6D5444E72E1FC71636A0F800C9`
SHA384 | `D96594AD864AA7F226E0AF9A56514FC3134D8C41CCF2327352FB6C47F1DEA3991323465E922D606262588A56B751F407`
SHA512 | `4605520FD6C9B647AC147A68409A78A10CD56AE2DEDDD391A15B2F9D06CD3096BD6CC238F971FC562073B1CC6E99C9F69AF319F25A2ADEDE96A93E8493F4D1A9`
SSDEEP | `3072:0mF0F+skOPzY6iEu0ow8lzd+cRAjgY/3wZgDmrBrBu/KS1ihk6kvtfGq0ev3U5WN:HaRY6mPw8l5YbmrB1ysrkR10efUK`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchFilterHost.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.18362.719 (WinBuild.160101.0800)
* Product Version: 7.0.18362.719
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-32070FD581B3C13740432169F764F066.md) | 44
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-673511D54A34319446EAD0B820D083A6.md) | 41
[C:\WINDOWS\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-2EF0A0531B2566153D9A3DF4160F650B.md) | 35
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-9350D231BEDC8A957F8CAA50E83BC446.md) | 38
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-98CAC0FEB32500C7CC15B6FE83F6068D.md) | 47
[C:\WINDOWS\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-BDCF47F408DA7D42D97763D27405B773.md) | 49
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-D332D4C07B7289696EE7EE8D656100B0.md) | 46
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-3F2C5E10BCC7A67751F042FE148C1B0F.md) | 41
[C:\WINDOWS\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E318AF6C41ABF3FB889EC89164A36A37.md) | 36
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E503AEEC8FA45CF5A5B530E41B7E1156.md) | 30

## Possible Misuse

*The following table contains possible examples of `SearchFilterHost.exe` being misused. While `SearchFilterHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `        Image\|endswith: '\SearchFilterHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


