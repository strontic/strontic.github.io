---
title: DismHost.exe | Dism Host Servicing Process
excerpt: What is DismHost.exe?
---

# DismHost.exe 

* File Path: `C:\windows\SysWOW64\Dism\DismHost.exe`
* Description: Dism Host Servicing Process

## Hashes

Type | Hash
-- | --
MD5 | `771392D6C4F545481B988A9B2DEC88AE`
SHA1 | `AC2BA5CC335186BF5FB378A9D2801F4839C61808`
SHA256 | `0695D0A7E20BD23DD3761710A223353A33DF9EF96F8AD79E76174C9035A1F518`
SHA384 | `EEC4D244A15DFDF2D819D5E6DCB6DAD501F1FBE6F2D4907D00DBCF641A8B66F38C4C1595551567979B58615CAEA9F2AD`
SHA512 | `859021FD833FC5D1B8F0999A95A3D1FC36651F749C06B040669B5804861A61A67D5CB63A7FE803F7FB5D4E68B2F050EFFEA3237F56185965B751A83E07C53494`
SSDEEP | `1536:ENwLPJB70OZyLMeTRtPxrKWVV/V/WIeGWAwhI/dIpvrDN3dM93lGfR:gwDSoeTRPrzVCIeGWAwecvr53unGfR`

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


