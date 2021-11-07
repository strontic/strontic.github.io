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
MD5 | `D106A29E1A787A673ACBB11968EFDFF5`
SHA1 | `992AAAB7A56C5447A2D5209D3135E1F9494A97D5`
SHA256 | `D4C583BC6EFD5F24ADF5C70421BA3FDCF6A53B010BC6A0D96147A6C7C3ADBC0C`
SHA384 | `33A5D8054A54D1307B3A7CD1C7AC4B21FE62E4A135619553984B8DBE50CF40C6556145BFAE85BC06D89D2E447F6BF6AF`
SHA512 | `392737C08A8BE420561D3189BDB64714D265D23C10C00915CA8E6C471BCFDBE0C6501C955608F3CF6C907C4E9D630EE847A0A5027E45D01F624C13CFCBBF506F`
SSDEEP | `3072:emQNq9Gqo0bp/59ziXK4z2fuukK+NqD2n6f9UkaVxR8t3J2wPFr:ejNq95o0l/59ziXK4zkNA5k8R8dV`
IMP | `8AA2AD4D02CD4F329F140F0BFF16AE96`
PESHA1 | `15881ADFA4497DD6A80B82D2C798961A53458AFE`
PE256 | `B746B22EE3270BAB1ACBF693D8066CB710C5488CFA0C9F1B4C082D9098C71833`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d4c583bc6efd5f24adf5c70421ba3fdcf6a53b010bc6a0d96147a6c7c3adbc0c/detection/


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


