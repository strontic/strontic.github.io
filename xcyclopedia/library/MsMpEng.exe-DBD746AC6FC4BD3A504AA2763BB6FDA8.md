﻿---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `DBD746AC6FC4BD3A504AA2763BB6FDA8`
SHA1 | `7C9D6E1335FE1AA4BCB0D246E58B2C8441192A0A`
SHA256 | `35B450F1946D573A37F711CFB4D6DC0385778C71F7CA2A70657DD68C456C40CC`
SHA384 | `1A40C10A89388C5743933271E12F337022DAC0C9C1BAA99869FB16E0A5122555A7A24104938EF538BA02A453BCCBE22B`
SHA512 | `BDE122BF1E39BA82E676D0FE79F59D2E41479E602E954D48F68748ACDDEB26E3983896662477B4948E1F5C646764D4AFE757251AEAC66AEA170081304A24EFC9`
SSDEEP | `3072:EM8k0I8/TmWYVq/c326i7G1KTecmj1aaWiNb:EMA7mJVtqGZjAaJ`
IMP | `2DFE2B101E95D9803D7B3F7C3C2C42BE`
PESHA1 | `545F9A95686AF0CEAE016B48D5BBC874E014683A`
PE256 | `0B1CDA9F73797367209F05C5E9627F8D4A33C0353187627F2828128DE177F0A3`

## Signature

* Status: Signature verified.
* Serial: `330000024BB2230A43CD03636200000000024B`
* Thumbprint: `50AFF9A191126B5BAD57B29846F3B68D550758CA`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2007.8 (WinBuild.160101.0800)
* Product Version: 4.18.2007.8
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/35b450f1946d573a37f711cfb4d6dc0385778c71f7ca2a70657dd68c456c40cc/detection/


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


