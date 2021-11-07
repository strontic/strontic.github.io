---
title: changepk.exe | Change Product Key
excerpt: What is changepk.exe?
---

# changepk.exe 

* File Path: `C:\windows\system32\changepk.exe`
* Description: Change Product Key

## Screenshot

![changepk.exe](screenshots/changepk.exe-E158157A57E322D9BB683FE2378724BA-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `410263744BBC5538EAB0B3A065F97F3A`
SHA1 | `ACFA549940045F5DD4056C5973F55254BEB24C95`
SHA256 | `70FF5A0B20FCA4226451174C3C079BEF1CF9F35BDD776E20E846C08519D5671E`
SHA384 | `5BCDA0765C0DF1108E6BB1B9AD77D19B785973E04707CFA2A60B266C211771EFA6956CD06EC4ECE685A1B39092BCB2E7`
SHA512 | `7B1F60BBA9162F972274AC107445425311564F83D071D58CDCB9B52231C6AF38E4668B91FA794848C7CFF19AD237B6709A8ED55295E9FE5A3EAB8AC8D8C5A547`
SSDEEP | `1536:Na8cHHHHHHHHHHHHHHHANOHHCHHH0sav0pb5vTYjMS2nksl7Rz2MPxT5QR:qZv0nM+ksl7VJT5C`

## Signature

* Status: Signature verified.
* Serial: `330000002418FC0B689E7399D0000000000024`
* Thumbprint: `812705D0EDDCE07C8A1DCCD9DC6E50C5E3D19219`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: changepkey.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `changepk.exe` being misused. While `changepk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `title: UAC Bypass Using ChangePK and SLUI`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `description: Detects an UAC bypass that uses changepk.exe and slui.exe (UACMe 61)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `- https://mattharr0ey.medium.com/privilege-escalation-uac-bypass-in-changepk-c40b92818d1b`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `Image\|endswith: '\changepk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\slui.exe, \system32\changepk.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


