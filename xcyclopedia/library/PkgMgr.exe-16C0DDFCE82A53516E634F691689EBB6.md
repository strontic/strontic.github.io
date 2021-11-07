---
title: PkgMgr.exe | Windows Package Manager
excerpt: What is PkgMgr.exe?
---

# PkgMgr.exe 

* File Path: `C:\WINDOWS\system32\PkgMgr.exe`
* Description: Windows Package Manager

## Screenshot

![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-1.png)
![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `16C0DDFCE82A53516E634F691689EBB6`
SHA1 | `36F2AB8F5E09123CFF95C2C188FB3DA829891EBE`
SHA256 | `986FEC137EB41A90AA72A7EF290B8D1D9DF0207B69A401A2BA60DFDBBF30A8B9`
SHA384 | `2E2F138740E9A81F5BB41CF9B2ECE2F143CFE869639D235CDC31FF99536DE29D25A9B97439E65F3650A4832F6ECD3CE6`
SHA512 | `9545C15569BB820DD7E55B4F2B2EAA6BB67E9E4508B4A11F063F1D6D5F13D2992AA8FEB03F23296BF185B3099095EB9A986384EF65E2BF2CD9AE06ACBF9733D6`
SSDEEP | `3072:2E3D6AFOZaz0xulwqmeSkENXK6JRAqs4xjw8m1I1nUhu:7GAFixqwq7SkMHxM8cAUh`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PkgMgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ocsetapi.dll](ocsetapi.dll-23BC4F98A5F7B0810CA560BF3DF76EF7.md) | 54
[C:\windows\system32\PkgMgr.exe](PkgMgr.exe-B212B2FE6910AF8B2068F2FF2242204F.md) | 38
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10.md) | 49
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DDE0B63F2E276B969C9C1E6983990CB2.md) | 50
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 43

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


