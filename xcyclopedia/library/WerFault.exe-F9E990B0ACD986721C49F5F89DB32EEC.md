---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `F9E990B0ACD986721C49F5F89DB32EEC`
SHA1 | `C6A79796DF32ADA80FA4E166FC1CA45B73B61DC0`
SHA256 | `DC9ADB75C9E3CB860619CD3C76544FDE47F3839DE775D9A9ED410F1E0D6E765A`
SHA384 | `D8C18C78D56DD5D2105A8AD11C4037F82E015ACCBA89A49004CE839132F7ADF9D5E0D912B12F60132975C1AE0AF1771D`
SHA512 | `97B19577B670D37040544D51CE245546C3F68E4980B07738E19151221DC2102CF5E38629DE7F0ACC9B3B38209C112DB30205958DB1CCB386B8D9A1AFED3CB3F5`
SSDEEP | `12288:OaufHNjduBFdJjjDegMt7oUFww4Ec2Hyw3:cmbvehoUFww4Ecyh3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


