---
title: DismHost.exe | Dism Host Servicing Process
excerpt: What is DismHost.exe?
---

# DismHost.exe 

* File Path: `C:\Windows\SysWOW64\Dism\DismHost.exe`
* Description: Dism Host Servicing Process

## Hashes

Type | Hash
-- | --
MD5 | `FB4395A6F71C952A9ACFE85F332F9162`
SHA1 | `BAEC94BC39D107426A0A55E0AB676ACC12746A85`
SHA256 | `28107B86DBB48F331EB8B36607DF1373A76717DD6A46F664933FDB0B6C2EEE8F`
SHA384 | `2DCBBEDB0F47F3E0404CB578B73E58FDEA2784278EF8FF75E84DC71A0B9193F253E4EBFA8E50B94667C7BB6E3CDD489D`
SHA512 | `5E4D1C0A673AB4DD402F450FD52171B3DEB5E7B12A88C94B5859C8BD7E1DF48875E23CC924CCF0003C15224A245C8DE96DC6EB4334B2AAD3CB002442E0C1C45A`
SSDEEP | `1536:8PSXj8TJ1ORkmr5oWOzwaWfVIyioV9zpwqcGEYuXYR3UWcVrrw+r/3kN:vv9NoWOziVvio/+qcGEYbRkhVrk+r/3q`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DismHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3241 (rs1_release_inmarket.190910-1801)
* Product Version: 10.0.14393.3241
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `DismHost.exe` being misused. While `DismHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- 'dismhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `title: UAC Bypass Using DismHost`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `description: Detects the pattern of UAC Bypass using DismHost DLL hijacking (UACMe 63)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_dismhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_dismhost.yml) | `- '\DismHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `- '\dismhost.exe {'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `Image\|endswith: '\DismHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


