﻿---
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
MD5 | `712C2F1E1A8AC13E7DB69B2253294484`
SHA1 | `38F033D14EFD15DCBA2387656B3099141B6E8261`
SHA256 | `0D07EC1EB0FF9DCABE175C93E5F354484FF2BA1FF5ACCE13ED3872A31E7FE22A`
SHA384 | `DE9EA2E08B211EB54A956F8D498D7CAE70AF1C6BDF4909B58E70A551DE2B29F1EFCA0B611D74BF80020FFBF4192D4EC3`
SHA512 | `8D24B801147E4E159158C0F1E0FF1F716784E1957800734DB906E417EFCB5969134D430964305F392B389312704370405432962FC4CE822359209E5EB6D32FDD`
SSDEEP | `1536:0NQZep+vv1Tj9aZ1q5TOvzj07j5Uff3vpP:Pv1Tj9aZ18yK5Uff3B`
IMP | `EE22AD7AC89E2E7EACBAF51750A69C27`
PESHA1 | `F0CAEC0354BF8A916B7E9701BCF74E844ACFCEC3`
PE256 | `4AC715DF233ACEE5965DF6B31E8750D8B7204A8B93A1A08207F85196F9C0DEA3`

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
C:\Windows\System32\kernel.appcore.dll |
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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/0d07ec1eb0ff9dcabe175c93e5f354484ff2ba1ff5acce13ed3872a31e7fe22a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\changepk.exe](changepk.exe-1379B19A1C5D68C64E5602B23DC6632B.md) | 40
[C:\WINDOWS\system32\changepk.exe](changepk.exe-4917CA1A1A28315E3E7711D4B3174128.md) | 44
[C:\Windows\system32\changepk.exe](changepk.exe-E158157A57E322D9BB683FE2378724BA.md) | 49
[C:\Windows\system32\changepk.exe](changepk.exe-E1CF89FC48F0C246C7FFDAC3727CFFCB.md) | 43

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


