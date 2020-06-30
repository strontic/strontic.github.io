---
title: SearchFilterHost.exe | Microsoft Windows Search Filter Host
---

# SearchFilterHost.exe 

* File Path: `C:\WINDOWS\SysWOW64\SearchFilterHost.exe`
* Description: Microsoft Windows Search Filter Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BDCF47F408DA7D42D97763D27405B773`
SHA1 | `57253FE513CCDDA3D84D1DCF18C93610D80BD673`
SHA256 | `CC7C85554C720281D2D2BFBA3D667820A6C17F53DA5A92AF49179ADFB425D545`
SHA384 | `E3ECF48741EF618FA4870B53C90FDE2A9822414C50C8FE72D867ACD1B2DB62EB07C77D5103A4B111EEC8A72F47ADCA91`
SHA512 | `4FAD46C2BA356BF631AC3E1E7158491605FE6CA6C81599F202EE6708288E684F1903BFA45DC8FBD68ED8EBABDFAAC79310000BFB418124C3C4209EE0A755D6D8`
SSDEEP | `3072:yvcRz+cqmLP+hyqcESiQoBzBGtIsL5tzsv7HTnrBgyS1ihk6kvtfGq0ev3U5WNrc:lJSY6QsGtIslt+/nrBgErkR10efUKr`

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
[C:\WINDOWS\system32\SearchFilterHost.exe](SearchFilterHost.exe-2296B4F9F71EFB1FCC195C85B8EA3ED9.md) | 49
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-32070FD581B3C13740432169F764F066.md) | 43
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-334E8E996B23216667D9538CE40D68B5.md) | 41
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-673511D54A34319446EAD0B820D083A6.md) | 40
[C:\WINDOWS\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-2EF0A0531B2566153D9A3DF4160F650B.md) | 43
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-9350D231BEDC8A957F8CAA50E83BC446.md) | 36
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-C4D33CE329ADDA42557420034702BDB4.md) | 29
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-09C9EB6892E603CD4265920E5A29F7CD.md) | 43
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-98CAC0FEB32500C7CC15B6FE83F6068D.md) | 50
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-D332D4C07B7289696EE7EE8D656100B0.md) | 44
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-3F2C5E10BCC7A67751F042FE148C1B0F.md) | 40
[C:\WINDOWS\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E318AF6C41ABF3FB889EC89164A36A37.md) | 36
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E503AEEC8FA45CF5A5B530E41B7E1156.md) | 30
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-EDDF12939FEF7AE88C2C2DA5B12E90B2.md) | 32

## Possible Misuse

*The following table contains possible examples of `SearchFilterHost.exe` being misused. While `SearchFilterHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `        Image\|endswith: '\SearchFilterHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


