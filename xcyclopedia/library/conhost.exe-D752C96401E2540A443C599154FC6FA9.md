﻿---
title: conhost.exe | Console Window Host
excerpt: What is conhost.exe?
---

# conhost.exe 

* File Path: `C:\Windows\system32\conhost.exe`
* Description: Console Window Host

## Hashes

Type | Hash
-- | --
MD5 | `D752C96401E2540A443C599154FC6FA9`
SHA1 | `00667A0F0C0D5E9DA697E9FF54ECDDD449259354`
SHA256 | `046F7A1B4DE67562547ED9A180A72F481FC41E803DE49A96D7D7C731964D53A0`
SHA384 | `AD67D3EDBB13C362730836F72850B01A0E5A0F8C5155D50FC21A1BBE6799B356C54C0CD182C644A17BDD48C240AB244A`
SHA512 | `DDEFBDD11FF0A4B3F47155331479E4D01852C1EA7670A7E449F3AD5F0AA0EAFED4146B91AEDC50328BC1BF80395B1E7E51E42A0B8507BBBFDEE5ACD9867073F4`
SSDEEP | `384:MJrgzqNPdIb4NQUFiuBGPnUixUXeYKSWhnWUOufano5wACtQMyBs:MFVVdvQUnGPUixUOYK1SuYotCtGBs`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONHOST.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\winsrv.dll](winsrv.dll-19979E1729CFA0E56EB4CCCB198DFD05.md) | 40

## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `CommandLine\|contains: 'conhost.exe 0xffffffff -ForceV1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `title: Conhost Parent Process Executions`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `description: Detects the conhost execution as parent process. Can be used to evaded defense mechanism.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `ParentImage\|endswith: '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `- Unlikely, conhost is a child less process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `Image\|endswith: '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Indirect Command Execution - conhost.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Indirect Command Execution - conhost.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | - [Atomic Test #3 - Indirect Command Execution - conhost.exe](#atomic-test-3---indirect-command-execution---conhostexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | ## Atomic Test #3 - Indirect Command Execution - conhost.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | conhost.exe refers to a host process for the console window. It provide an interface between command prompt and Windows explorer. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | conhost.exe "#{process}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_between-hk-and-burma.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_between-hk-and-burma.yar) | $file1 = "\\Microsoft\\Internet Explorer\\conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $two4 = "/Delete /F /TN Conhost & del" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a10 = "\\conhost.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


