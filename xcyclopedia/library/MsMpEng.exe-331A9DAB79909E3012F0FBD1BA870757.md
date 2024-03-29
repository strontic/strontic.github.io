﻿---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2003.8-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `331A9DAB79909E3012F0FBD1BA870757`
SHA1 | `E11DF54105EF454702C6A312A389700832CA1D41`
SHA256 | `B595B1832B0A24D781EA501A881513381182138766B2385C96C0E356300B1B66`
SHA384 | `D83C9FC0AFFCB467A812D6D5795DF8D187F87B1930B05DDB53A7BEABAF76680E6CAC2798BA36F8AF276906C6C9E1A67B`
SHA512 | `C275F190157CE58E2AF3F0C0E2914540A1860BA1D768AED9EB65A3BC9AF21D4C62AD87180AACBE41EA642D2D5ACDA968A6958BF482710C78B37CE06588351010`
SSDEEP | `1536:P22jtIgAVwgLJnT6BynDm1CnE/+i3sFKTe0CeKDmVpWUd6swP:PHJHglnTTDm1mEr3sFKTe0zKDmVpP6/`

## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2003.8 (WinBuild.160101.0800)
* Product Version: 4.18.2003.8
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2001.10-0\MsMpEng.exe](MsMpEng.exe-F6B04D08ECC4B9FF446CAB52EC622618.md) | 82

## Possible Misuse

*The following table contains possible examples of `MsMpEng.exe` being misused. While `MsMpEng.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- 'MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- MsMpEng.exe can crash when C:\ is full`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- '\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_revil_kaseya.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_revil_kaseya.yml) | `- '\AppData\Local\Temp\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_revil_kaseya.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_revil_kaseya.yml) | `- 'C:\Windows\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `ParentImage\|endswith: '\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `- '\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s1 = "MsMpEng.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [1258b063-27d6-489b-a677-4807faacf868.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/1258b063-27d6-489b-a677-4807faacf868.yml) | `"msmpeng",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


