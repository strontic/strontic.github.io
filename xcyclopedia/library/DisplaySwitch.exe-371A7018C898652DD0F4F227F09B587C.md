---
title: DisplaySwitch.exe | Display Switch
excerpt: What is DisplaySwitch.exe?
---

# DisplaySwitch.exe 

* File Path: `C:\Windows\system32\DisplaySwitch.exe`
* Description: Display Switch

## Hashes

Type | Hash
-- | --
MD5 | `371A7018C898652DD0F4F227F09B587C`
SHA1 | `586FA91F18EBA31E4552D16A8E2867D660BE5F7E`
SHA256 | `5E4E1662EB2D4D08D8D0D52F4F9BB9B30B61634F2B5E0799B03CFC098D8BEF0A`
SHA384 | `47DF298F6668E1DD0F418FE35718F138632EF735C5310F7632EB999B1EE078835E7EDEECEE9C67F3CA7D1D78AA7F9B10`
SHA512 | `3E444C62CB595DBA50414C44DAE98EB02457FC029E6D2F0B358FB084D1B8CAFBCD329E7386A623D3548DAF6883BA80202DB49DE03516BF9ACF8F8153DE22C672`
SSDEEP | `3072:+eJVmi/wGrmvdEcW9cIEd/qGhtIdRHORSqvkqxXfoOETWB+/VSHP9a:+emi6vdEcyId/q06zHORNvxJp+k9`
IMP | `35BD06246B07F938DD6E5AE1B25C3715`
PESHA1 | `F0BDD91C9D2B3017F3CB72844ECE9D6918C2CAE9`
PE256 | `BCA34E93D4AC9B6D69244C7DCF72BC246B035C099605D3FEE097807B042FAC99`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\DisplaySwitch.exe |
C:\Windows\system32\DUI70.dll |
C:\Windows\system32\DUser.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\policymanager.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DisplaySwitch.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/5e4e1662eb2d4d08d8d0d52f4f9bb9b30b61634f2b5e0799b03cfc098d8bef0a/detection/


## Possible Misuse

*The following table contains possible examples of `DisplaySwitch.exe` being misused. While `DisplaySwitch.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\displayswitch.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\DisplaySwitch.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*cmd.exe DisplaySwitch.exe *'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Display Switcher: <code>C:\Windows\System32\DisplaySwitch.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


