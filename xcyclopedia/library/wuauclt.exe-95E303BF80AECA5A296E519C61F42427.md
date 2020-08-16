---
title: wuauclt.exe | Windows Update
---

# wuauclt.exe 

* File Path: `C:\Windows\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `95E303BF80AECA5A296E519C61F42427`
SHA1 | `B523E0CD46B3E5F6CDCD6F99E8CC9932D9585B9E`
SHA256 | `AC52D02086B83A2FA92E305E1EACD490101D08BE6C47210989BAA192E030DC06`
SHA384 | `9C899FC7C606C6A2B9BF926510CBE2A902F82DAE7496BEBF83A844C066107C44BE2F01D8CBEF3B8F6952D63F4F3E5FEB`
SHA512 | `884A18F68FE328958AD7B0EBA5A13515C517992423CF123DC81D44D0EAC5988771F7958D877997E9BFCA74427F99E2B87EFBCA8A44132164A6928E0368D3F125`
SSDEEP | `1536:HK0TzC8tY6HAqCsd56ncymh7TpkwsZYm+P/:HKE+8tY6H/FPRkLYm+n`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-11F337850E397E473B3666AFB7AC1D44.md) | 88

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | 		$x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


