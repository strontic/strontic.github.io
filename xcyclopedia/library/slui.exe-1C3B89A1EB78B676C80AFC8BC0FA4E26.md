﻿---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\Windows\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `1C3B89A1EB78B676C80AFC8BC0FA4E26`
SHA1 | `22826B7D7808CD2AC30518BC7F5114890E2C0268`
SHA256 | `FC4D1FD06A10682E53170D388CDFC9053AF70001E57F3D8B84D666E9D95560B7`
SHA384 | `54DF85335334B0AE1E6D89FD676496FE81BB360F5C16BB956030B7D3F6D592AC12B1A0B5BF1CB893B242EF65B65EFD9C`
SHA512 | `B52462D328E51539B878AC7EC531E21A76C5997D99B69C29617769CA73917C5C769F01866557EFCF9B97193A76A9C65137633663311B74FE75767AE81AF3A49C`
SSDEEP | `12288:k0RtNWU//5TEDbZUfBsphGkQhHBcyxxz2Eq3nyR:k07NWu/KUYGk4nLz2b3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\slui.exe |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\slui.exe](slui.exe-EB725EA35A13DC18EAC46AA81E7F2841.md) | 91

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


