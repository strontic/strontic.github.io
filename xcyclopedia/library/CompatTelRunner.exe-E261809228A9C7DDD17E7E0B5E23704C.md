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
MD5 | `E261809228A9C7DDD17E7E0B5E23704C`
SHA1 | `32AFE403DB068F240400435688B179FDF8290AE7`
SHA256 | `B1F8A6AE285A2485AC2D876DFC135B985450A887DFDB42C2BDDC414CCB487E46`
SHA384 | `7E4FFBE63A3E00E88C85C64622A543EEFA77EFBC8D57FD0E941B3AD1035A0232BA86F2DFB2A8A8DE773B84B48367A473`
SHA512 | `7C4F57D9813962F9DB22392B5220EA6230C2E3511AEAA37367C023A0D22CD6A36712832F9B0C59B89C2577AD05FCDFAD8F7A001D94A17C5C1917F3624E9807F4`
SSDEEP | `3072:017mRucu5IfDAZp+dBYE6lDgQr9hbwwBr5cxQ+VBD4nax79UkJvmRItLJ2wkLkl5:m7mRuc0IfDUoBCge9hbwwBtaQH6ukMRI`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1035 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1035
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\CompatTelRunner.exe](CompatTelRunner.exe-1E79615EF9946EB8A28D15584B21DB2F.md) | 96
[C:\windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-4BDD8E93D7A5E57BEA22B18BF9675021.md) | 32
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-F3C4479D5AC4E943381049640E628993.md) | 96

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


