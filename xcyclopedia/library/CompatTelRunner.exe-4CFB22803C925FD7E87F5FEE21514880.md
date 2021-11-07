---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
excerpt: What is CompatTelRunner.exe?
---

# CompatTelRunner.exe 

* File Path: `C:\Windows\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry

## Hashes

Type | Hash
-- | --
MD5 | `4CFB22803C925FD7E87F5FEE21514880`
SHA1 | `77F2E744C92417653B5ABD6CCB3B5E521111979A`
SHA256 | `C52B831C4471E30EF6BD816DB7B62FEFEB3FA4EF0CE2CF46D70E527F624ABE2D`
SHA384 | `F862C9F47D6DFD464509B7F96962605C93A563259FE24396E4BC047CFFB01A19C8652369C5C28B7F5BE07B6939AE36F8`
SHA512 | `E4487937071AAB04583E2939BEC3618F032092CD9C97DC15779E97188BA15242DA89328675C2F6846D58BA618967F37D00DB285E399ECC889AC6799575317CD9`
SSDEEP | `3072:RusBqwKCNhECrehGWN4hwKz/60+SrDG69UkPeEbSFD6twJ2HiGpBF:82qwx/ECahGWN4b/NAtkDiD66B2`
IMP | `073D2008CD517DAA64FE601CE086A682`
PESHA1 | `0BE4D267FEFBE1B147B85D2DE239FC32467C3CDD`
PE256 | `136C8C75588A8DB5F53AC644572F1236BFF0794897FA9E30C84360781C5BFCC7`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\CompatTelRunner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19645.1046 (WinBuild.160101.0800)
* Product Version: 10.0.19645.1046
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c52b831c4471e30ef6bd816db7b62fefeb3fa4ef0ce2cf46d70e527f624abe2d/detection


## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\CompatTelRunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_abusing_windows_telemetry_for_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_abusing_windows_telemetry_for_persistence.yml) | `description: Windows telemetry makes use of the binary CompatTelRunner.exe to run a variety of commands and perform the actual telemetry collections. This binary was created to be easily extensible, and to that end, it relies on the registry to instruct on which commands to run. The problem is, it will run any arbitrary command without restriction of location or type.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_non_interactive_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_non_interactive_powershell.yml) | `- '\CompatTelRunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\compattelrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_abusing_windows_telemetry_for_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_abusing_windows_telemetry_for_persistence.yml) | `description: Windows telemetry makes use of the binary CompatTelRunner.exe to run a variety of commands and perform the actual telemetry collections. This binary was created to be easily extensible, and to that end, it relies on the registry to instruct on which commands to run. The problem is, it will run any arbitrary command without restriction of location or type.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_win_reg_telemetry_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_win_reg_telemetry_persistence.yml) | `- '\system32\CompatTelRunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


