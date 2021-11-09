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
MD5 | `98AED5286F2D76C0248C13684981222A`
SHA1 | `AAD7DA20C43DFD658F8C35E122CF294931187F90`
SHA256 | `1721B942DEE057C5CF45C455096557173F2CC261BCA542BD70AA201090133C4E`
SHA384 | `3069F33B89904FA4BAF13A01E544E5428A29BF7FD034E5F19627EE37F38378DCBF2492A73C41A44A0F0F3387899B374A`
SHA512 | `99E1561E3AD3B5A57928582E7A491F1D2334068E3F72D081952EDCBDB407E34FBCF97446B520BACF0173C169308CF55C5E06DCDD4A855FDE9BAD9353B55DAFAD`
SSDEEP | `12288:+cj3KysCCC2BJjRrxPhH/rhtUZQqq3nyR:+C3KysE2BlRrxPhH/gZQt3`
IMP | `FB4FABA295B4DFEEDB3276B076A9F293`
PESHA1 | `09FBE076EA900C614E09AB2D62401EDCC5F8D470`
PE256 | `D3C947D75CFFAD7410AD7FC3C799CBF21F723F89DC2C53FA206358C73AD2AC76`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\IMM32.DLL |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ole32.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\shcore.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\system32\SLC.dll |
C:\WINDOWS\system32\slui.exe |
C:\WINDOWS\system32\sppc.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |
C:\WINDOWS\system32\WINBRAND.dll |
C:\WINDOWS\system32\WTSAPI32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: slui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/1721b942dee057c5cf45c455096557173f2cc261bca542bd70aa201090133c4e/detection


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


