---
title: changepk.exe | Windows Activation
excerpt: What is changepk.exe?
---

# changepk.exe 

* File Path: `C:\WINDOWS\system32\changepk.exe`
* Description: Windows Activation

## Screenshot

![changepk.exe](screenshots/changepk.exe-E158157A57E322D9BB683FE2378724BA-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `4917CA1A1A28315E3E7711D4B3174128`
SHA1 | `1760176B668FFCFB325919ABA63AE06A1150B6B9`
SHA256 | `D2BFC0DCE8C97309FE5D8B95E25A419A001422424E48CD8578C6ABCBCF99608C`
SHA384 | `42C27E25A7CE5FD6B7907A0DF5FC7BFDBD98E00A3F9F3AB23C2F0F44FB24954571FFC15A6077BBFB6081B74ED426A030`
SHA512 | `DFA5B78F896B1BCC9DAA6AB00DC604576F9588C852A4C6D38DB7EF5C4BCA99FC01CA3B681F31BC3DA15D74D59235C794029DDDB57431CBE43AE5C2F2E1338D71`
SSDEEP | `1536:VDep0Ef77YAmocVoyg1e1qpTBPvzj07j5Ufcc1PiL:WH7YAdQoyR1cBXK5Ufcc16L`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: changepk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\changepk.exe](changepk.exe-712C2F1E1A8AC13E7DB69B2253294484.md) | 44
[C:\Windows\system32\changepk.exe](changepk.exe-E158157A57E322D9BB683FE2378724BA.md) | 44
[C:\Windows\system32\changepk.exe](changepk.exe-E1CF89FC48F0C246C7FFDAC3727CFFCB.md) | 38

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


