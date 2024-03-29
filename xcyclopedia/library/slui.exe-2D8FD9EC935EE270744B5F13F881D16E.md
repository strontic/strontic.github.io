﻿---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\windows\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `2D8FD9EC935EE270744B5F13F881D16E`
SHA1 | `0CC11BA0D8C29E9F984B6484CFFDF6CB59760676`
SHA256 | `D192199BFB64E0BF52E6DF248718101FE12E33CBE20D9660FEA037204E774278`
SHA384 | `F91B78345E7F873D3CE5E518FD9017C922CFC71153D5B2C3551BF928BBD8E0007CA7A0FFAB9AC14B43C20CC976F04423`
SHA512 | `434F4D3FA0E1E79F5011E0B81B0CDC412A27690C7E0E6F0355D063D15B87174F50C59A6434F569F23F95AEC48F718E7BEE1B3CABA8039D98B40F453EA0EF34DF`
SSDEEP | `6144:bPOsWtLMrVg2X6bVlqY/W5R02qO7VKCyWQp:bPEtLmOZ7q3nyR`

## Signature

* Status: The file C:\windows\system32\slui.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: slui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\slui.exe](slui.exe-0A26DC4E016E6614991E26CE20DC9466.md) | 50
[C:\Windows\system32\slui.exe](slui.exe-10B472E52F5F0592076D7E093858A2C3.md) | 55
[C:\Windows\system32\slui.exe](slui.exe-3A171EFE71231ACB1B45E1FC00671EDF.md) | 54
[C:\Windows\system32\slui.exe](slui.exe-68974B8AD1EE9B8F59E93A799474A339.md) | 52
[C:\Windows\system32\slui.exe](slui.exe-CAF88C49F33FA27D956BC728A041346D.md) | 55
[C:\Windows\system32\sppcommdlg.dll](sppcommdlg.dll-25059CB01909EFC95C978A189C24C20B.md) | 46

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


