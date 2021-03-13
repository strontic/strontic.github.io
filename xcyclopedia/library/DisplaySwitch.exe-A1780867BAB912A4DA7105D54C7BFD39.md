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
MD5 | `A1780867BAB912A4DA7105D54C7BFD39`
SHA1 | `CDD54DC89F9E064C0C5E8FA4E9F30735FA4DDB95`
SHA256 | `A5F3500875F4C482BD821B251B6A79E144C021A40E7054D10085619932FF4FF9`
SHA384 | `145543BCE6897085BF05D9F8C9F1696170486E2CF855FE3FF3F2B58544A4A3436400246FB6A889F922AB28BA42DA5983`
SHA512 | `C1C010228441726624C820FBBB2EF43762353D7D75F440D424672C45FAB2BEBCDAFF17F83BCC319B1B38C08FD6C1832DDEEDB7B047092E498934DEED917DB8FA`
SSDEEP | `3072:QsdJNVZUwfBEjFSJu20qc7sPv+W1jOGy2XvkY0rPRLTWyDSBloU:QwZU+2ThsPv+W1jOGy2/3yJjY`
IMP | `3DBF1C80950DFBF8F40A0705EDFD00AD`
PESHA1 | `2CB69F8960F607FFAEC66F85A36530480C83EF41`
PE256 | `B1866B98E5E31F46C7C4A9E098A0C8C16BCA8A55438C4920B2CC285FF49A8BE3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\DisplaySwitch.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\policymanager.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/a5f3500875f4c482bd821b251b6a79e144c021a40e7054d10085619932ff4ff9/detection


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


