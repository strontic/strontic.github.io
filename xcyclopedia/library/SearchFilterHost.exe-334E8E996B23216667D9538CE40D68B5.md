---
title: SearchFilterHost.exe | Microsoft Windows Search Filter Host
excerpt: What is SearchFilterHost.exe?
---

# SearchFilterHost.exe 

* File Path: `C:\windows\system32\SearchFilterHost.exe`
* Description: Microsoft Windows Search Filter Host

## Hashes

Type | Hash
-- | --
MD5 | `334E8E996B23216667D9538CE40D68B5`
SHA1 | `222224AFFA9A7B044C89ECCD2AC31BD9A5A27E36`
SHA256 | `B77F100BB6C4F3DB1BA5FCEDE4F1EFA5D065700BCABB365266DD494C5D8A049B`
SHA384 | `9A0629DC862702A2A4282160E9CFEEEF4DA01D8588FD32186A0DEC097C106DF234E6E1CC24A933FAB4F931500159B1AE`
SHA512 | `F42FE5964E716E8F88047615139664711F753F8AE54B4BA772B66F8297265499BA6F69D09D6187A6DF7101C59EFC1B12BDE3564319BF0AC59216347CE25ACD6F`
SSDEEP | `6144:Hztew9BLoNF7lVzzdz+ZumrroiOrkR10efUK:n9BLSF7lVzzdz+ZZrFOQztf`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchFilterHost.exe
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.17763.1098 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1098
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\SearchFilterHost.exe](SearchFilterHost.exe-2296B4F9F71EFB1FCC195C85B8EA3ED9.md) | 44
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-32070FD581B3C13740432169F764F066.md) | 33
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-673511D54A34319446EAD0B820D083A6.md) | 41
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-79242AB9AABF63BB91672F67ECE93C31.md) | 40
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-BB3FEB38673DB103CAB1634AECE1DC21.md) | 40
[C:\Windows\system32\SearchFilterHost.exe](SearchFilterHost.exe-DCE97A7B66E0D4A2BA9B52E7D05B334C.md) | 43
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-003B2FB715F4459920E5C0B9F8F7CF7A.md) | 38
[C:\WINDOWS\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-2EF0A0531B2566153D9A3DF4160F650B.md) | 33
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-67E648DEC1B91543B04463249B7C0E1D.md) | 30
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-9350D231BEDC8A957F8CAA50E83BC446.md) | 32
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-C40671F2861D99F8D64DAC58F9B1973A.md) | 35
[C:\Windows\system32\SearchProtocolHost.exe](SearchProtocolHost.exe-C4D33CE329ADDA42557420034702BDB4.md) | 30
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-09C9EB6892E603CD4265920E5A29F7CD.md) | 41
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-8B0EE156EEA810806D285878104C7FF9.md) | 44
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-98CAC0FEB32500C7CC15B6FE83F6068D.md) | 43
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-A2E770284F3AF4AFA09407862E73ADFB.md) | 35
[C:\WINDOWS\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-BDCF47F408DA7D42D97763D27405B773.md) | 41
[C:\Windows\SysWOW64\SearchFilterHost.exe](SearchFilterHost.exe-D332D4C07B7289696EE7EE8D656100B0.md) | 38
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-057EE453817460D609D83DC6427A0400.md) | 36
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-2B0E4C28B9FD8B244644FF7C4064C927.md) | 35
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-3F2C5E10BCC7A67751F042FE148C1B0F.md) | 43
[C:\WINDOWS\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E318AF6C41ABF3FB889EC89164A36A37.md) | 36
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-E503AEEC8FA45CF5A5B530E41B7E1156.md) | 32
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-EDDF12939FEF7AE88C2C2DA5B12E90B2.md) | 33
[C:\Windows\SysWOW64\SearchProtocolHost.exe](SearchProtocolHost.exe-F71E4867152289828CA8063BA1732507.md) | 30

## Possible Misuse

*The following table contains possible examples of `SearchFilterHost.exe` being misused. While `SearchFilterHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `Image\|endswith: '\SearchFilterHost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


