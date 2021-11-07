---
title: DismHost.exe | Dism Host Servicing Process
excerpt: What is DismHost.exe?
---

# DismHost.exe 

* File Path: `C:\windows\system32\Dism\DismHost.exe`
* Description: Dism Host Servicing Process

## Hashes

Type | Hash
-- | --
MD5 | `DD630511F697002DDEE58570A2E7A3D1`
SHA1 | `519C1A21CAC1C1BC0EBF9CEC20761AEF4E5ED335`
SHA256 | `95AEC6D12E6F9E6E1E3045259CF024D30625BF4E520D94F333387359221735E4`
SHA384 | `6BFBDA34E225FA5071F2D264560BEA257E4F39C50526C8378F0FD84A12DA572633FA296B3BE73343CF71A6A24B3BDCE3`
SHA512 | `74C201C375F994551CC7DB591993D330521025466B8C3B2CCBA6E9835448F9C86B795E0AC4289F1804C5568AEE3FC3057D51380AC3AA67D2BDF2387FE4A828E5`
SSDEEP | `3072:RJ7FsTbuZ7Zi+lzqDq7FUm/AuRXSprvBODB:LFsTbu/lzaqNANprvs1`

## Signature

* Status: Signature verified.
* Serial: `33000001B24A37C6C97E0168860001000001B2`
* Thumbprint: `A380D6A21D68FA9B52D2405B36C712BAFA57632B`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DismHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.19397 (winblue_ltsb.190608-0600)
* Product Version: 6.3.9600.19397
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


