---
title: AtBroker.exe | Windows Assistive Technology Manager
excerpt: What is AtBroker.exe?
---

# AtBroker.exe 

* File Path: `C:\Windows\system32\AtBroker.exe`
* Description: Windows Assistive Technology Manager

## Hashes

Type | Hash
-- | --
MD5 | `30076E434A015BDF4C136E09351882CC`
SHA1 | `584C958A35E23083A0861421357405AFD26D9A0C`
SHA256 | `AE7B1E298A6E38F0A3428151BFC5565EDE50A8D98DAFAA147B13CF89C61F2DDD`
SHA384 | `8727E2DF9EF16342B3475F873863523DE9D84502771A85972399C4F5EB14BEB0DD2AA113FA0990FAA2BF754815807635`
SHA512 | `675E310C2455ACF9220735F34FA527AFE87DAC691E89CC0EDC3C4659147E9FD223F96B7A3BEEA532047AA0EBC58880A7010343019A50AA73CE69A038E3592024`
SSDEEP | `1536:To4xehkWhYULcid2bpS8r0sMCl9Mx07zLrwkkqz3q/Troh7YTVZPyOh+id+Uk9:M8vQc79vr0wPLrwkkCq/nEYTVZPy9id2`
IMP | `468490D98938AAE93ECC62C54A775DC2`
PESHA1 | `2A3F4DFF927E9626ED7DEA0528815CDCB729163F`
PE256 | `3458DB0C05AFF9F18439E83F3E47C7A075D925D71209458F16906C1BE429089E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\system32\AtBroker.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
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

* Original Filename: ATBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1023 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1023
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ae7b1e298a6e38f0a3428151bfc5565ede50a8d98dafaa147b13cf89c61f2ddd/detection


## Possible Misuse

*The following table contains possible examples of `AtBroker.exe` being misused. While `AtBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- 'atbroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_atbroker.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_atbroker.yml) | `title: Suspicious Atbroker Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_atbroker.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_atbroker.yml) | `description: Atbroker executing non-deafualt Assistive Technology applications`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_atbroker.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_atbroker.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Atbroker/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_atbroker.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_atbroker.yml) | `Image\|endswith: 'AtBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_atbroker_change.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_atbroker_change.yml) | `title: Atbroker Registry Change`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_atbroker_change.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_atbroker_change.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `Name: Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Command: ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\System32\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\SysWOW64\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- IOC: Unknown AT starting C:\Windows\System32\ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * App Switcher: <code>C:\Windows\System32\AtBroker.exe</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


