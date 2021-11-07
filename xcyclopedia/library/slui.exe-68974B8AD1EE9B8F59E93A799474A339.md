---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\windows\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `68974B8AD1EE9B8F59E93A799474A339`
SHA1 | `2E11A6C026C6C025835E757D5B23C17438F3974A`
SHA256 | `42B6BBECE4CDE24C4BD93D3D640B9300589E8311FF6232E02558952854484C41`
SHA384 | `7B47AA6503B0BCD3571CC40D98F5A9C36AAFAD3DEE4ED4ADC5C7F265C82D862D86DFF25A1EFD41FED69D8E8985030BCB`
SHA512 | `58A8876A8B76DED6101838188D89CFAB632AA57543A32668EA767D21961163703BD1F628766625B99977B2C0C99541355ACDDADC6834FFAD6214BC50D7621B3C`
SSDEEP | `6144:7VxpC1u+z53bQeILDS7LZAwHfcqY/W5R02qO7VKCyWQp:hxIptMX26pq3nyR`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: slui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\slui.exe](slui.exe-0A26DC4E016E6614991E26CE20DC9466.md) | 47
[C:\Windows\system32\slui.exe](slui.exe-10B472E52F5F0592076D7E093858A2C3.md) | 97
[C:\windows\system32\slui.exe](slui.exe-2D8FD9EC935EE270744B5F13F881D16E.md) | 52
[C:\Windows\system32\slui.exe](slui.exe-3A171EFE71231ACB1B45E1FC00671EDF.md) | 55
[C:\Windows\system32\slui.exe](slui.exe-CAF88C49F33FA27D956BC728A041346D.md) | 97
[C:\Windows\system32\sppcommdlg.dll](sppcommdlg.dll-25059CB01909EFC95C978A189C24C20B.md) | 38

## Possible Misuse

*The following table contains possible examples of `slui.exe` being misused. While `slui.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `description: Detects an UAC bypass that uses changepk.exe and slui.exe (UACMe 61)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_changepk_slui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_changepk_slui.yml) | `ParentImage\|endswith: '\slui.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_shell_open.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_shell_open.yml) | `description: Detects the pattern of UAC Bypass using fodhelper.exe, computerdefaults.exe, slui.exe via registry keys (e.g. UACMe 33 or 62)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\slui.exe, \system32\changepk.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [b7344901-0b02-4ead-baf6-e3f629ed545f.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/privilege-escalation/b7344901-0b02-4ead-baf6-e3f629ed545f.yml) | `description: executes the slui exe file handler hijack`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


