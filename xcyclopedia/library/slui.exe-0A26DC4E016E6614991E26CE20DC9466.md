---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\WINDOWS\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `0A26DC4E016E6614991E26CE20DC9466`
SHA1 | `42E2C50603CAD00C3E5B752BF1F2E6331498954E`
SHA256 | `39D924020BA5C09BB5AB2021C973B86C29E756B5F6D3B3FCD0F3CF5C74636CE4`
SHA384 | `D4455E424F206FC4DB9000D39003F077AD0497766CE179482209627D59159707686CF899B30DF00EDE14A68D91942F92`
SHA512 | `88E7A7A90B48E617E36014F0813D50EE1609D8F0D7EF94A207FB886E53961A6FDE27C7FCD47E4D142B1603BFA0D0AE51C7BC1259895F7E314F516D983463E078`
SSDEEP | `6144:32x/n9wywep0KtB9hL8NQ+i+2faxw7jAxXk8OqY/W5R02qO7VKCyWQp:3in9dTv9J8l5xwX4LOq3nyR`

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
* File Version: 10.0.18362.693 (WinBuild.160101.0800)
* Product Version: 10.0.18362.693
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\slui.exe](slui.exe-10B472E52F5F0592076D7E093858A2C3.md) | 47
[C:\windows\system32\slui.exe](slui.exe-2D8FD9EC935EE270744B5F13F881D16E.md) | 50
[C:\Windows\system32\slui.exe](slui.exe-3A171EFE71231ACB1B45E1FC00671EDF.md) | 41
[C:\Windows\system32\slui.exe](slui.exe-68974B8AD1EE9B8F59E93A799474A339.md) | 47
[C:\Windows\system32\slui.exe](slui.exe-CAF88C49F33FA27D956BC728A041346D.md) | 47
[C:\Windows\system32\sppcommdlg.dll](sppcommdlg.dll-25059CB01909EFC95C978A189C24C20B.md) | 36

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


