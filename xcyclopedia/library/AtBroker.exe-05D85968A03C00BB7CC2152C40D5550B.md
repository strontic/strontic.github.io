---
title: AtBroker.exe | Windows Assistive Technology Manager
excerpt: What is AtBroker.exe?
---

# AtBroker.exe 

* File Path: `C:\WINDOWS\SysWOW64\AtBroker.exe`
* Description: Windows Assistive Technology Manager

## Hashes

Type | Hash
-- | --
MD5 | `05D85968A03C00BB7CC2152C40D5550B`
SHA1 | `B70759D4F2A7E50852D93FA7685C1A3342972D7B`
SHA256 | `020736CA188D1C9E9B4EEFC274951550AA3C926918EF1038566D5EB4C6649DC8`
SHA384 | `5A349A224BC737641EF1973300E8CF73CCB9CAE79CA445008DD554AF91E6DB39C6CEBBEF1DC26B935AC5462388F36C7F`
SHA512 | `B414B78EC6568EF7E82C0CA7667BC41B94612F46A92A82D91159A11CE40ADBA1514CD71EECD9A4A11D8339732196807673C09A658D6A70E14274DE93C0F113D3`
SSDEEP | `1536:ZxuqWvwbAQtp0cqwtsYIB1ks6N7Hk1pJHfw1DZZMx3WdkCEV941TA9/qyEu:WqSKpfqwtsYO1ks6pkwH/BA9wk4yE`
IMP | `AD6697DB3D380D03EACBB4BE152A7C5A`
PESHA1 | `891E258BD997DC73F6D54776ECD8F8ED16ED4671`
PE256 | `9DD0D1127FC67136EA2C8F81CF9AD4E989DD6B66D0CE0B10A5D08A1777613593`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\AtBroker.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ATBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/020736ca188d1c9e9b4eefc274951550aa3c926918ef1038566d5eb4c6649dc8/detection


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


