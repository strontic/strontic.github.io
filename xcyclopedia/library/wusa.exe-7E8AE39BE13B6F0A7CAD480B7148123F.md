﻿---
title: wusa.exe | Windows Update Standalone Installer
excerpt: What is wusa.exe?
---

# wusa.exe 

* File Path: `C:\WINDOWS\system32\wusa.exe`
* Description: Windows Update Standalone Installer

## Screenshot

![wusa.exe](screenshots/wusa.exe-6C81724C47077509C4CC874E34008FC3-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `7E8AE39BE13B6F0A7CAD480B7148123F`
SHA1 | `7C564D675A33EEA6A7F5952935416311B0087A05`
SHA256 | `B38C8C76D561271BA6F49AD9645D06CD8C1733CFD55E4FDAEED1D41682D67BAF`
SHA384 | `DB02F90A695E7F0C4A5F001E9BEFC2C02C65C0BDDDE9F96C7509B40E7EF46953F7236D922D41C6AD4FC39AC23531F34D`
SHA512 | `621A4B1DE59A9A2CDF1D8F591B4BB27162C6F932DD638F38D777F3C0EB47539E1F24C3B0AB48F9AE023F53EB18F60FAF1691C6867DBD5C38A339C3ED28BDC502`
SSDEEP | `6144:LlNRXjJMGrLIirYc+MHxM8cp98pxyN90vE:LlXTyGrxrYxMHxMf8y90`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wusa.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-9934CEF23769FA6D63A4330C45B13157.md) | 47
[C:\WINDOWS\system32\wusa.exe](wusa.exe-297CE1CB7C6CE8EF6F5655EC78E4C667.md) | 38
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 58
[C:\windows\system32\wusa.exe](wusa.exe-8930570F7F76840334962EFC6C173438.md) | 47
[C:\Windows\system32\wusa.exe](wusa.exe-8A0B789F779802881EEAC4F99532A35C.md) | 44
[C:\Windows\system32\wusa.exe](wusa.exe-E43499EE2B4CF328A81BACE9B1644C5D.md) | 44
[C:\Windows\system32\wusa.exe](wusa.exe-E7A1BF42A43A9031533768B393D5673A.md) | 41
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 35
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6B5F21E4B1FA9B4BF6AD402A9EA52887.md) | 47
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6C81724C47077509C4CC874E34008FC3.md) | 46
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-79499499551D1B2AE037EC1B339C7C36.md) | 36
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-A60D32269A6A6E7BFDC50E22A70B8F54.md) | 43
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-C46BE74BD433DD95952142967E3F1F9A.md) | 36
[C:\windows\SysWOW64\wusa.exe](wusa.exe-F3EF56F76D69361022B47EF1E6201644.md) | 38

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


