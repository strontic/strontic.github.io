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
MD5 | `1379B19A1C5D68C64E5602B23DC6632B`
SHA1 | `9200C55C35E20FA685BB0DDB30379BAD5E070B56`
SHA256 | `6A90159A258D58E6246BCA231A69F3A4A3A0C303ACED9D736DF7F6B9AA3E9C56`
SHA384 | `5A5134F0001A7FDE5EF8549F331D4D4ABB25B72071F955BA6B85E5413C371039FBD9F702B5AF1B8F8727EF3D295FF1AD`
SHA512 | `D3FA9A2905E17E2A350139D5CB97AAFC3AE1EC5804CFD4611C835B77B16E26900099DAC7CC36CEA46EBAF840816F44E1F89CE0AA2D6244442327C5C1CF57A8B4`
SSDEEP | `1536:vIpRUHlGKnfXRbZeT3tS8dYkGtaTDvzj07j5UfbkQP0e:wpq1nfXRbO9S8d7GtWTK5UfbkQb`
IMP | `92E1D19DF58A53FFB6A0A1367A0E0918`
PESHA1 | `401479B0140263786FF35F312F77497DFDB07816`
PE256 | `BF4C2A1CF3E485DBE79ABB874A50966E1EAB34F5C723C7726F8EB52F081FA0A7`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\System32\bcryptPrimitives.dll |
C:\WINDOWS\system32\changepk.exe |
C:\WINDOWS\System32\clbcatq.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\SYSTEM32\cryptsp.dll |
C:\WINDOWS\system32\DUI70.dll |
C:\WINDOWS\system32\EditionUpgradeManagerObj.dll |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\IMM32.DLL |
C:\WINDOWS\SYSTEM32\kernel.appcore.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ole32.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\system32\pkeyhelper.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\shcore.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\shlwapi.dll |
C:\WINDOWS\system32\SLC.dll |
C:\WINDOWS\system32\SPPC.DLL |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\user32.dll |
C:\WINDOWS\system32\uxtheme.dll |
C:\WINDOWS\System32\win32u.dll |
C:\WINDOWS\SYSTEM32\winbrand.dll |
C:\WINDOWS\SYSTEM32\windows.storage.dll |
C:\WINDOWS\system32\Windows.UI.Immersive.dll |
C:\WINDOWS\SYSTEM32\wintypes.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: changepk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/6a90159a258d58e6246bca231a69f3a4a3a0c303aced9d736df7f6b9aa3e9c56/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\changepk.exe](changepk.exe-4917CA1A1A28315E3E7711D4B3174128.md) | 35
[C:\Windows\system32\changepk.exe](changepk.exe-712C2F1E1A8AC13E7DB69B2253294484.md) | 40
[C:\Windows\system32\changepk.exe](changepk.exe-E158157A57E322D9BB683FE2378724BA.md) | 40
[C:\Windows\system32\changepk.exe](changepk.exe-E1CF89FC48F0C246C7FFDAC3727CFFCB.md) | 35

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


