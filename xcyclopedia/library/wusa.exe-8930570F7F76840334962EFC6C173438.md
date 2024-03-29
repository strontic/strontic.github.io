﻿---
title: wusa.exe | Windows Update Standalone Installer
excerpt: What is wusa.exe?
---

# wusa.exe 

* File Path: `C:\windows\system32\wusa.exe`
* Description: Windows Update Standalone Installer

## Screenshot

![wusa.exe](screenshots/wusa.exe-6C81724C47077509C4CC874E34008FC3-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `8930570F7F76840334962EFC6C173438`
SHA1 | `58C69D6FF2EC90977E42AE45C0F7E2A9E8C1E65E`
SHA256 | `EE8C9A8E161047F68B9AC1E81592587C63BC218389430EACAC0A8CAC3380AB0A`
SHA384 | `95EDEE4F201C74B61E0371634912E504F9297A76FEF924BB683B3C107677741431C5899BBA87AD00A4410A4B9DE21F49`
SHA512 | `44BE1B85D08C7D9EB6C0FB2EDBCBC531A37E48F35CF0AD7358DF9C1B0ADFA52E39C362B19E0BD40D08C313E6F0B1CB02D16F7797DF21266CA1D1F8629D4A5670`
SSDEEP | `6144:preMHxM8Ww6hnFYa8rRoVJA3pxyN90vE:4MHxMxThnFYMVCHy90`

## Signature

* Status: The file C:\windows\system32\wusa.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 50
[C:\WINDOWS\system32\wusa.exe](wusa.exe-7E8AE39BE13B6F0A7CAD480B7148123F.md) | 47
[C:\Windows\system32\wusa.exe](wusa.exe-8A0B789F779802881EEAC4F99532A35C.md) | 33
[C:\Windows\system32\wusa.exe](wusa.exe-E43499EE2B4CF328A81BACE9B1644C5D.md) | 33
[C:\Windows\system32\wusa.exe](wusa.exe-E7A1BF42A43A9031533768B393D5673A.md) | 43
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 40
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6B5F21E4B1FA9B4BF6AD402A9EA52887.md) | 38
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6C81724C47077509C4CC874E34008FC3.md) | 38
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-79499499551D1B2AE037EC1B339C7C36.md) | 43
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-A60D32269A6A6E7BFDC50E22A70B8F54.md) | 38
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-C46BE74BD433DD95952142967E3F1F9A.md) | 40
[C:\windows\SysWOW64\wusa.exe](wusa.exe-F3EF56F76D69361022B47EF1E6201644.md) | 41

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


