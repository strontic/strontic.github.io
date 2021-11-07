---
title: Dism.exe | Dism Image Servicing Utility
excerpt: What is Dism.exe?
---

# Dism.exe 

* File Path: `C:\windows\system32\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `4DF5F1072A21A2CE50A4BC1C2E8BA2DE`
SHA1 | `133E3902A6FD1B83A2A362B24EC27A07F04A0B2D`
SHA256 | `2FBFF06B431E9B0144BFC689E94257B77F9A8F91F03AF4851BD100278415A667`
SHA384 | `DA6AB89CEB06E137FE80374F0FC13B30D9BC2305954FEEE894901F5263AE4DDE316B9CCECE521254E43BE31A255AEBB2`
SHA512 | `7ECB0F33B486A4138B61C1CE4DCBF8B30F4F6D819729955B14FB1B87B6B80D5F46306AAADC25C8A854C6CC776810F2D2B4BF0D1AE03313C69E5C56684B70D9AD`
SSDEEP | `3072:dr5BWjxg0uMYjLKntkyPmw9JxEDRI5BaPrdpQa5s7Phoua+anr:xvWjxHuMYKtkytbgKDaPrdaa0Pho5r`

## Signature

* Status: The file C:\windows\system32\Dism.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17031 (winblue_gdr.140221-1952)
* Product Version: 6.3.9600.17031
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\System32\Dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `Image\|endswith: '\Windows\System32\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_via_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_uac_bypass_via_dism.yml) | `- '\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `ParentCommandLine: '"C:\Windows\system32\dism.exe" /online /quiet /norestart /add-package /packagepath:"C:\Windows\system32\pe386" /ignorecheck'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `description: Detects the pattern of UAC Bypass using pkgmgr.exe and dism.exe (UACMe 23)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `Image\|endswith: '\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


