﻿---
title: wusa.exe | Windows Update Standalone Installer
excerpt: What is wusa.exe?
---

# wusa.exe 

* File Path: `C:\windows\SysWOW64\wusa.exe`
* Description: Windows Update Standalone Installer

## Screenshot

![wusa.exe](screenshots/wusa.exe-6C81724C47077509C4CC874E34008FC3-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `F3EF56F76D69361022B47EF1E6201644`
SHA1 | `8E3913A7085E596A9CC45F2B6A4795B9C3FEEF6C`
SHA256 | `1E384E490AFF301349D27C37139D304EDC83CF62571875540AB468E3B0D65C06`
SHA384 | `D07A979713A1EBBAF3D8B08A7B5F1A1A713C61420BED449A1064E80F41C839FEFFC223B124BED55C4FA1AA816A4D2080`
SHA512 | `E8EA9D8981A4EF86EB52782ED5CBF23E55FD9E2F3BB7DB59391271E91E48FD06875A89C448FEA005B7D9969BCA579D228EC157154EB5C6CA8B7FFA2ADFC5B6DB`
SSDEEP | `6144:eK8nRccM6pf5XvrFMU2AGGpxyN90vE/5:D8nRcepxXzyyfy90C5`

## Signature

* Status: The file C:\windows\SysWOW64\wusa.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: wusa.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\wusa.exe](wusa.exe-297CE1CB7C6CE8EF6F5655EC78E4C667.md) | 38
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 41
[C:\WINDOWS\system32\wusa.exe](wusa.exe-7E8AE39BE13B6F0A7CAD480B7148123F.md) | 38
[C:\windows\system32\wusa.exe](wusa.exe-8930570F7F76840334962EFC6C173438.md) | 41
[C:\Windows\system32\wusa.exe](wusa.exe-8A0B789F779802881EEAC4F99532A35C.md) | 33
[C:\Windows\system32\wusa.exe](wusa.exe-E43499EE2B4CF328A81BACE9B1644C5D.md) | 32
[C:\Windows\system32\wusa.exe](wusa.exe-E7A1BF42A43A9031533768B393D5673A.md) | 36
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 52
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6B5F21E4B1FA9B4BF6AD402A9EA52887.md) | 50
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6C81724C47077509C4CC874E34008FC3.md) | 50
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-79499499551D1B2AE037EC1B339C7C36.md) | 43
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-A60D32269A6A6E7BFDC50E22A70B8F54.md) | 50
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-C46BE74BD433DD95952142967E3F1F9A.md) | 49

## Possible Misuse

*The following table contains possible examples of `wusa.exe` being misused. While `wusa.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_ntfs_reparse_point.yml) | `description: Detects the pattern of UAC Bypass using NTFS reparse point and wusa.exe DLL hijacking (UACMe 36)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `description: Detects the pattern of UAC Bypass using NTFS reparse point and wusa.exe DLL hijacking (UACMe 36)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `CommandLine\|startswith: '"C:\Windows\system32\wusa.exe"  /quiet C:\Users\'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s5 = "wusa.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s4 = "wusa.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


