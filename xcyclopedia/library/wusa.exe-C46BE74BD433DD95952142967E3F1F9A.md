﻿---
title: wusa.exe | Windows Update Standalone Installer
excerpt: What is wusa.exe?
---

# wusa.exe 

* File Path: `C:\WINDOWS\SysWOW64\wusa.exe`
* Description: Windows Update Standalone Installer

## Screenshot

![wusa.exe](screenshots/wusa.exe-6C81724C47077509C4CC874E34008FC3-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `C46BE74BD433DD95952142967E3F1F9A`
SHA1 | `CFC825ABCFA834D79D4BFFA79EE00AC872AFB8B5`
SHA256 | `4166FBFA83D143585B0092E6CB354859529EFBD7A5D3092D028242DE60D86F48`
SHA384 | `953C61CCDB693C130E9D6308E92954C9195AC19F1A36AFC214E50F646181F0DC6755F47437B9498B663F162BAA88CA03`
SHA512 | `7D65A359D513C0198B7B3594FBB8541866ECEF042E2689FCA6BA9495D3330DD8D504E902A4C4FA87C0318FEDEA505309A9CE75E04B1F2C1342FAB9BE5F83CEDF`
SSDEEP | `6144:1ce8nRccM7KChv1tB3zXBPVo9PpxyN90vEp:1B8nRcvLdfB3n2fy90M`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wusa.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\wusa.exe](wusa.exe-297CE1CB7C6CE8EF6F5655EC78E4C667.md) | 33
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 38
[C:\WINDOWS\system32\wusa.exe](wusa.exe-7E8AE39BE13B6F0A7CAD480B7148123F.md) | 36
[C:\windows\system32\wusa.exe](wusa.exe-8930570F7F76840334962EFC6C173438.md) | 40
[C:\Windows\system32\wusa.exe](wusa.exe-8A0B789F779802881EEAC4F99532A35C.md) | 32
[C:\Windows\system32\wusa.exe](wusa.exe-E43499EE2B4CF328A81BACE9B1644C5D.md) | 35
[C:\Windows\system32\wusa.exe](wusa.exe-E7A1BF42A43A9031533768B393D5673A.md) | 33
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 52
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6B5F21E4B1FA9B4BF6AD402A9EA52887.md) | 49
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6C81724C47077509C4CC874E34008FC3.md) | 54
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-79499499551D1B2AE037EC1B339C7C36.md) | 40
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-A60D32269A6A6E7BFDC50E22A70B8F54.md) | 49
[C:\windows\SysWOW64\wusa.exe](wusa.exe-F3EF56F76D69361022B47EF1E6201644.md) | 49

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


