---
title: AtBroker.exe | Windows Assistive Technology Manager
excerpt: What is AtBroker.exe?
---

# AtBroker.exe 

* File Path: `C:\Windows\SysWOW64\AtBroker.exe`
* Description: Windows Assistive Technology Manager

## Hashes

Type | Hash
-- | --
MD5 | `D5B61959A509BDA85300781F5A829610`
SHA1 | `FC729FD404040DF6A5A3CEEDA355A53B77B43D85`
SHA256 | `E54BCE96572F17B4DAD28689A5C4FCB55042830BF167FFA91005B0748D11C0B5`
SHA384 | `F219C0F9551BBC212C8F874D5B9F8F0B8E2805D17D38F07F2C1B64F597812DF4061F2C990B469D9B5A67395C7A027BA0`
SHA512 | `322DA19B91BC1A9E00CE47AE7625BF109C96BD5AFCF819C32C277E9C3099465B5BF780F5DB0299AF6FD87E4FBA0380D7193DBA72C4C6ECBA21DEA7C91A1A0C5F`
SSDEEP | `1536:EMH9XIoZOzDT3tAc3KT8HCz25SSLnKLzB:79izb6AfSSLnKLzB`
IMP | `8345A2F978F5669C81FFF2049DC536DA`
PESHA1 | `FC14E9569544672C600B04A1942138B59A9E519F`
PE256 | `9022822AE0F6FE02899C47BE93480F32B18557140C6EAF2162E1F943E909C4A8`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\AtBroker.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e54bce96572f17b4dad28689a5c4fcb55042830bf167ffa91005b0748d11c0b5/detection


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


