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
MD5 | `E1CF89FC48F0C246C7FFDAC3727CFFCB`
SHA1 | `15C30A19D1661E5DECF643BE09FFA358EC83A6CA`
SHA256 | `69644AB12ECC3A89BC2DB5DC8198A506647D14F5B44745BCED02EAFAC362E8CF`
SHA384 | `54AA3E9793223853216E400F1126FA25EAD5ECA9B2EE11B269AD6CC64B302BBB1C026C918CE75EF430F6DEDDB12732E5`
SHA512 | `F904C301C09937C8C7F246CFFB3CB2792C61D3679B3EE60D8CD6B3D9D46EB0488692803E7DD3ABAA113C1C808539F7491069249FDDF1ACCE850A6E4FED771B01`
SSDEEP | `1536:17F+2BGymzag4U8AIvd1scT05vzj07j5UfE9AIP:ejyzg4U3Ivd1sU0lK5UfEqI`
IMP | `E3EFA1B5D57BA8D5B087542C1D3F58F7`
PESHA1 | `2519A33EAE53413E71D91AB7A893FA89E9A6087A`
PE256 | `1CE9E6C4811EF1160C4C0DFED1F7619DF0B21D054A0DFDD245B2994B56703726`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\system32\changepk.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\System32\win32u.dll |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/69644ab12ecc3a89bc2db5dc8198a506647d14f5b44745bced02eafac362e8cf/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\changepk.exe](changepk.exe-1379B19A1C5D68C64E5602B23DC6632B.md) | 35
[C:\WINDOWS\system32\changepk.exe](changepk.exe-4917CA1A1A28315E3E7711D4B3174128.md) | 38
[C:\Windows\system32\changepk.exe](changepk.exe-712C2F1E1A8AC13E7DB69B2253294484.md) | 43
[C:\Windows\system32\changepk.exe](changepk.exe-E158157A57E322D9BB683FE2378724BA.md) | 36

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


