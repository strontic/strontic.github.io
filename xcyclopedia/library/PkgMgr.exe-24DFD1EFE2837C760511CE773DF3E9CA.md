---
title: PkgMgr.exe | Windows Package Manager
excerpt: What is PkgMgr.exe?
---

# PkgMgr.exe 

* File Path: `C:\Windows\SysWOW64\PkgMgr.exe`
* Description: Windows Package Manager

## Screenshot

![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-1.png)
![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `24DFD1EFE2837C760511CE773DF3E9CA`
SHA1 | `9337185001101F37BC9D9B9EDADD3E34A6C11DFB`
SHA256 | `8AFD78CB0BEFD7BADAF66BBDEF884FBCE6B9BFCB41291B78DF1939227103766D`
SHA384 | `D70716CFE14F9F29FD570BDF2C28B31BF7FA0B58B992F8A89C9E78B1B09909039552DAFC8016E682881F62CF7F872F03`
SHA512 | `9246AA908E49E44C716A71A1DBD5F49A2D20189326232316DC8A02B988B591AD8404CA230AB104E78901D763F207116B3C0FCE9F3DC91AB22BA65A8BAB0F9D57`
SSDEEP | `3072:fF8r7ENnKKphw6s4RTQcWl4gECKue9Pa4iuUblDwAMQUlW1Vm:fqr78nRccMxECze9+hblDw/`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PkgMgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2457 (rs1_release_inmarket.180822-1743)
* Product Version: 10.0.14393.2457
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ocsetapi.dll](ocsetapi.dll-C21C76EB69C2341726564264A28E8B8B.md) | 49
[C:\windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-049A6E9C689E058AC091C3DD08CB06DF.md) | 47
[C:\Windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-299F9CBA823CFB6F7AD965877154902B.md) | 52
[C:\Windows\SysWOW64\PkgMgr.exe](PkgMgr.exe-2F98A0859C8F75D8EEE78E0C8DB2F59F.md) | 49
[C:\WINDOWS\SysWOW64\PkgMgr.exe](PkgMgr.exe-694A2798122C9BE0043DD732C33BC4CE.md) | 43
[C:\WINDOWS\SysWOW64\PkgMgr.exe](PkgMgr.exe-DF567ACC6355100C57611510A701335F.md) | 47
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 43

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


