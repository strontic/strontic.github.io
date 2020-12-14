---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
excerpt: What is sdiagnhost.exe?
---

# sdiagnhost.exe 

* File Path: `C:\Windows\system32\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host

## Hashes

Type | Hash
-- | --
MD5 | `C91529A7EB209224BF6D6D47A4620865`
SHA1 | `CB2EA519864BEF397C434B33DD507EB4E9D30CED`
SHA256 | `6FEDAAF41148F8E0803451B44AA5270AE6F96BF6D31CB81B3FE9459D2239E54E`
SHA384 | `73F4EFD6FAABB3A196E86190744C494D387E4D99E8AAFC233D89EE7A9DB8428202C4C18C15D034B7AA8650F63DFC4860`
SHA512 | `3F2B8CC14C10A6CAEC9049F0A84889A895DEB1039EE0F91045554A591992A6F80AEE810C2E0CCAF89787DBB478D146835CB93B067C44AE70AFD54895E03C5280`
SSDEEP | `384:VWGCbl3oxEU8mgjLaunvYb1f4Z9OLv74qurfnC4HGcMXgRaoaDMnkfPiu1Wa7DW:VlWoAzvNeLv8zqfoaAnGPiub`

## Runtime Data

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


