---
title: DisplaySwitch.exe | Display Switch
excerpt: What is DisplaySwitch.exe?
---

# DisplaySwitch.exe 

* File Path: `C:\WINDOWS\system32\DisplaySwitch.exe`
* Description: Display Switch

## Hashes

Type | Hash
-- | --
MD5 | `FEDAF55B499C81E8ECB54288EA985F81`
SHA1 | `000D83CD9A93B21BF20D4231EE8619DE4BD9E3B6`
SHA256 | `787811303D1924C12E1FEA4B2C314960C0AEB52476C4BB71DC0C79B08E750972`
SHA384 | `C304E19C540D829983C4A3AC4B94011D9B6235B725677375D30E7462833327F3F7666BF5F5E735DA957AE2287BBC3275`
SHA512 | `D2070257F6501B68E753889234E2EA1C124704F00796D49E22660C0338A472F070A2F19E0D8EDDB909E3BCC1AF4281D96EF6AE69EB1B64D4395EFAF69AAC8069`
SSDEEP | `6144:OM/nAE0eeusn26AHtlhBDJEBTi3hM+q9mJAOsHr:OMoE0efsn2xHtLpJEhiRM+q9m+L`
IMP | `82211BBAD1D05E55E854D21C69B96783`
PESHA1 | `9AAAC437F62F8885D86AFD6314842BB2A3060B8D`
PE256 | `50F9C3786AB02482DBEF442BF1BC9D4390BAB421F1DD4D68E6B05C1DFC373C6C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\system32\DisplaySwitch.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DisplaySwitch.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/787811303d1924c12e1fea4b2c314960c0aeb52476c4bb71dc0c79b08e750972/detection


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


