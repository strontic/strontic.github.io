---
title: PkgMgr.exe | Windows Package Manager
excerpt: What is PkgMgr.exe?
---

# PkgMgr.exe 

* File Path: `C:\windows\SysWOW64\PkgMgr.exe`
* Description: Windows Package Manager

## Screenshot

![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-1.png)
![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `049A6E9C689E058AC091C3DD08CB06DF`
SHA1 | `8C38D2628C43AC4632941539BDBD5294A41C51ED`
SHA256 | `833DB9236CA1471180D12D1EDF5655FCF8959BA839CA8DF07141BB8AF52D2A5C`
SHA384 | `E30B2B87642D7DCC6069ECC670E33649CC197335CB6D859496B2F40418DD763C72DE5A918A7C4648FD27CEB9B32973AB`
SHA512 | `EC4DB6B6F8194814E7DB661010F84BE0350591C49ACE84EFE15BB4BC5C968F6F4FAC8BB06F8E091FF25D11C4338D2FBB6BFA45BEBB8960EA8534DA6D1A0EEF90`
SSDEEP | `3072:7i5rUENnKKphw6s4RTQcWl4Fa/DkCFdCf9TGOK18/qZ9vRtFmZQ:crU8nRccMC6hzCf9TGOIaqZ`

## Signature

* Status: The file C:\windows\SysWOW64\PkgMgr.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: PkgMgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ocsetapi.dll](ocsetapi.dll-C21C76EB69C2341726564264A28E8B8B.md) | 49
[C:\Windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-24DFD1EFE2837C760511CE773DF3E9CA.md) | 47
[C:\Windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-299F9CBA823CFB6F7AD965877154902B.md) | 49
[C:\Windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-2F98A0859C8F75D8EEE78E0C8DB2F59F.md) | 46
[C:\WINDOWS\SysWOW64\PkgMgr.exe](PkgMgr.exe-DF567ACC6355100C57611510A701335F.md) | 43
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 46

## Possible Misuse

*The following table contains possible examples of `PkgMgr.exe` being misused. While `PkgMgr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_msconfig_gui.yml) | `TargetFilename\|endswith: '\AppData\Local\Temp\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_msconfig_gui.yml) | `ParentImage\|endswith: '\AppData\Local\Temp\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `title: UAC Bypass Using PkgMgr and DISM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `description: Detects the pattern of UAC Bypass using pkgmgr.exe and dism.exe (UACMe 23)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `ParentImage\|endswith: '\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\pkgmgr.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


