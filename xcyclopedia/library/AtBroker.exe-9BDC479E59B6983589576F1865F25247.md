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
MD5 | `9BDC479E59B6983589576F1865F25247`
SHA1 | `770904DA1FAD1B0A5FE7347BB2FE817E0F299FFD`
SHA256 | `22B2A930D97C30BF53B7BC9838F8C4C938D7D0F806EAE3601F9A01AEAC803443`
SHA384 | `9A28B5BE91C23353CB0C869585B6271CCB1127FF4BD8B7CB881F19EDEFC876D2E6A1FC7F67176C3ACE7C306C72BF871E`
SHA512 | `736A1216B361D49426D7CFCFFE97C50207948139BD98F2C4D5C174553C3BF49D4F752C7C7E704E1A54F8474B9EE69925634DAFA7B7F670317DC3F6EDE4F94F61`
SSDEEP | `768:3T+Kjgbmte3DLwhxr5Fo2cMfUuc0xpkh9hwTPGV5X62UbtGeKJaD+RIu62EMKaHs:3Tlxr5FoJ+dvO9hwTGV9GfDg7DHpmV`
IMP | `F791708993F51197FF73758E81E9637C`
PESHA1 | `D203AFA581E27593A46961A41B021E0B7B54871B`
PE256 | `D0EC86755BE20CD389C6CFC60CA825A561BC543AE16550A4E73B9533A1736746`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ATBroker.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/22b2a930d97c30bf53b7bc9838f8c4c938d7d0f806eae3601f9a01aeac803443/detection/


## Possible Misuse

*The following table contains possible examples of `AtBroker.exe` being misused. While `AtBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\atbroker.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `Name: Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Command: ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\System32\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\SysWOW64\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- IOC: Unknown AT starting C:\Windows\System32\ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * App Switcher: <code>C:\Windows\System32\AtBroker.exe</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


