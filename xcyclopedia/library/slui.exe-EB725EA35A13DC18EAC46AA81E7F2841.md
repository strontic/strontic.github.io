---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\Windows\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `EB725EA35A13DC18EAC46AA81E7F2841`
SHA1 | `C0B3304C970324952E18C4A51073E3BDEC73440B`
SHA256 | `25E7624D469A592934AB8C509D12C153C2799E604C2A4B8A83650A7268577DFF`
SHA384 | `A18EBA9D31210D73F844EA5BBDC716A212FF92212CF2AA58706BB4EF82CB2F6010FA5E7DCF4505292A479BB297DE5285`
SHA512 | `39192A1FAD29654B3769F007298EFF049D0688A3CB51390833EC563F44F9931CD3F6F8693DB37B649B061B5AAB379B166C15DADE56D0FC414375243320375B26`
SSDEEP | `12288:h0RtNWU//5TEDbZUfBsphGkQhHBcyxlT2Lq3nyR:h07NWu/KUYGk4nXT2m3`
IMP | `F2014F5555EEFEC494A169DEEBA0FEE5`
PESHA1 | `E8A2AD11590A0FCC44EDBE44930C682DF430F6CE`
PE256 | `66B804B7E1992404FB4A0E071858207EBB5BB8A3E5B6964521BC245AC9D46873`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\system32\slui.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINBRAND.dll |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/25e7624d469a592934ab8c509d12c153c2799e604c2a4b8a83650a7268577dff/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\slui.exe](slui.exe-1C3B89A1EB78B676C80AFC8BC0FA4E26.md) | 91

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


