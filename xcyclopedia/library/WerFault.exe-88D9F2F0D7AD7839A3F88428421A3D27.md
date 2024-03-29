﻿---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\WINDOWS\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `88D9F2F0D7AD7839A3F88428421A3D27`
SHA1 | `13004D81CD6EAD16DDD83DF5A459E223FD1C9E11`
SHA256 | `59771B825B108E13CE89FB07570C9AC0CCFF0926AB6B7CB579A9A264D5FE9056`
SHA384 | `ABF1C565B44FA8370A1C00C96334BC67745BB73E303F02B6315E2D7AFA9525598086D5A80C2C93D18BFAF1D7587E7A10`
SHA512 | `CD1A2DBAB76F6086D8A77530CF5C18E66017AB75D79C105E52861500BAF128F49F145E5826723AE7CB3B65CF09DE76D189B4DDBFF93C05A3511DC0FB2A0F6E25`
SSDEEP | `12288:gW81rbq1E+6pulwknM87R3wG1IvOeynRFkDHc2Hywy:j8xqnUuoUR3wGnRFk7cyhy`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WerFault.exe](WerFault.exe-B843354FF4C728A87A5A061E0974FD78.md) | 35

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `title: Suspicious Werfault.exe Network Connection Outbound`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `description: Adversaries can migrate cobalt strike/metasploit/C2 beacons on compromised systems to legitimate werfault.exe process to avoid detection.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `Image: 'werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cve_2021_26857_msexchange.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cve_2021_26857_msexchange.yml) | `- 'WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `description: 'Detects attackers using tooling with bad opsec defaults e.g. spawning a sacrificial process to inject a capability into the process without taking into account how the process is normally run, one trivial example of this is using rundll32.exe without arguments as a sacrificial process (default in CS, now highlighted by c2lint), running WerFault without arguments (Kraken - credit am0nsec), and other examples.'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `Image\|endswith: '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `CommandLine\|endswith: '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_consent_comctl32.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


