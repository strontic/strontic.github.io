---
title: changepk.exe | Windows Activation
excerpt: What is changepk.exe?
---

# changepk.exe 

* File Path: `C:\Windows\system32\changepk.exe`
* Description: Windows Activation

## Screenshot

![changepk.exe](screenshots/changepk.exe-E158157A57E322D9BB683FE2378724BA-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `E158157A57E322D9BB683FE2378724BA`
SHA1 | `A863F6C4299446AA6DFBDADCA98AE40FA044EB5E`
SHA256 | `64708A3E27EE5ACBEB14140A956AAF8F6472CF60D592C05BC564851BE5CD42D5`
SHA384 | `D86A41EA963DC9B3970EE8B909AA03E6FD79ECA23384145FCF3FF02C74EB09FC31989F87BDCFF901A3323508F89A8A62`
SHA512 | `2767FB90151E7A2BFB41516854D8893BCEC9E9458369ED481ED6A97EE06E7107832FB1215FF61973C17645F2511DCED990B6C3A04664EC94302DEB5AD673154E`
SSDEEP | `1536:/nceOoyWlp5h15wTGjvzj07j5UfTTfPLr0:EoyqHXzK5UfTTfzr0`

## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: changepk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\changepk.exe](changepk.exe-1379B19A1C5D68C64E5602B23DC6632B.md) | 40
[C:\WINDOWS\system32\changepk.exe](changepk.exe-4917CA1A1A28315E3E7711D4B3174128.md) | 44
[C:\Windows\system32\changepk.exe](changepk.exe-712C2F1E1A8AC13E7DB69B2253294484.md) | 49
[C:\Windows\system32\changepk.exe](changepk.exe-E1CF89FC48F0C246C7FFDAC3727CFFCB.md) | 36

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


