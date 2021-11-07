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
MD5 | `5338D4BEDDF23DB817EB5C37500B5735`
SHA1 | `1B5C56F00B53FCA3205FF24770203AF46CBC7C54`
SHA256 | `8B581F1D15A6920E4ECFE172D8EF753D0A2BF1A47E686A8D5D8E01147FA4C65E`
SHA384 | `A3568954A0C6E755A3418A1956B85F10E917BA7D1433E53CB7EA407B6A6C2907CAA0DDD37E4722E508F9C53EF7AF4AC6`
SHA512 | `173170B83E0048EE05DA18C0C957744204954DA58A93C532B669D62EDB632C4C73D0744C13EB864ECF357FF12831AA46C4F2445DC33B62A4547385B9E0297B0C`
SSDEEP | `3072:xZtA8bXIUwXCuQJfR5ibYxGXyt9McD9GIPv02BTvkSorZoJTW/TY1e7j:xfrIUNbLi80yt9McD9GIPv02BjNJPe`
IMP | `3DBF1C80950DFBF8F40A0705EDFD00AD`
PESHA1 | `4BE99B4D2B5F4218514C9A282705E0791BB544B9`
PE256 | `84C4F7BF5A07AC786384A107F17325C1FE97FFB9B2D1F02FD2A6E389221AEE26`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\system32\DisplaySwitch.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/8b581f1d15a6920e4ecfe172d8ef753d0a2bf1a47e686a8d5d8e01147fa4c65e/detection


## Possible Misuse

*The following table contains possible examples of `DisplaySwitch.exe` being misused. While `DisplaySwitch.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stickykey_like_backdoor.yml) | `- 'DisplaySwitch.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- 'displayswitch.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_stickykey_like_backdoor.yml) | `- '\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\DisplaySwitch.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Display Switcher: <code>C:\Windows\System32\DisplaySwitch.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


