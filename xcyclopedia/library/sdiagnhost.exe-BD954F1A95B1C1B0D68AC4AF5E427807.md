---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
excerpt: What is sdiagnhost.exe?
---

# sdiagnhost.exe 

* File Path: `C:\windows\SysWOW64\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host

## Hashes

Type | Hash
-- | --
MD5 | `BD954F1A95B1C1B0D68AC4AF5E427807`
SHA1 | `B917E3FDC09AF0B50E5A46044731139A4F6D3FD7`
SHA256 | `BBF6D9ED2664F6BFCCE40348A0CBD73C55BA364CEC8649B2BF332E3301ED7A19`
SHA384 | `10ADEDE125E448A651651F76C20002D036241EAD5416812450B05BCB1B218E9CD60DD1283DA4842C0308DCA6570DE522`
SHA512 | `5CE8E35948616680EAB7F18B66EBE05A73A0CE34D2459078767FE31D0D661183CAC915269A9D664F326704E7C51FFF84FCEE978C004BEA27BD8375220E26F9B3`
SSDEEP | `384:FHm8MXAvartizJWNBtoUX34d4UXiqwcI1KEac/sG/XLeitWj7DWf:irtzdnw4uw6tc/sMXLei6U`

## Signature

* Status: The file C:\windows\SysWOW64\sdiagnhost.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-258F58247AACD6568910D85E33A07886.md) | 41
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-43353191117C9236DDCCE362A8E74BA7.md) | 41
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-48582EF64F96E054C0CDCF3055258101.md) | 35

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_assembly_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_in_memory_assembly_execution.yml) | `- '\Windows\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


