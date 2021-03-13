---
title: pcalua.exe | Program Compatibility Assistant
excerpt: What is pcalua.exe?
---

# pcalua.exe 

* File Path: `C:\Windows\system32\pcalua.exe`
* Description: Program Compatibility Assistant

## Hashes

Type | Hash
-- | --
MD5 | `A82DD6C08CA53980D9757B43C9917F9E`
SHA1 | `BF787394D3829E0908DE480E07B12BC86BA982AA`
SHA256 | `5A18A7CDAC642694F298B02E08D2B3446A5CE156EAC0EFC752A85B072BBBD994`
SHA384 | `3E1DA8A7B9BDE90EE4B9D5B591F41A74CE20A060E63AF231BB599D8F3CB00A2BFC6AD1C8B252572819C8000275B7ED1D`
SHA512 | `85085886B13410627E08099CCEBB59D760A29037B250780A7872A8AF41ACBCF20BF6A1DC2BBB78657784B9AB6715860FA8809CE23A232236B031F98345CC8B95`
SSDEEP | `768:fNhARY9PweJRb9IxF0t77TRDpSpwmS/KA8I6AB:VtnPkWFRpSpwf/qAB`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `pcalua.exe` being misused. While `pcalua.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd.yml) | `description: Detect indirect command execution via Program Compatibility Assistant pcalua.exe or forfiles.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd.yml) | `- '\pcalua.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `Name: Pcalua.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `- Command: pcalua.exe -a calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `- Command: pcalua.exe -a \\server\payload.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `- Command: pcalua.exe -a C:\Windows\system32\javacpl.cpl -c Java`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `- Path: C:\Windows\System32\pcalua.exe`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Various Windows utilities may be used to execute commands, possibly without invoking [cmd](https://attack.mitre.org/software/S0106). For example, [Forfiles](https://attack.mitre.org/software/S0193), the Program Compatibility Assistant (pcalua.exe), components of the Windows Subsystem for Linux (WSL), as well as other utilities may invoke the execution of programs and commands from a [Command-Line Interface](https://attack.mitre.org/techniques/T1059), Run window, or via scripts. (Citation: VectorSec ForFiles Aug 2017) (Citation: Evi1cg Forfiles Nov 2017)\n\nAdversaries may abuse these features for [Defense Evasion](https://attack.mitre.org/tactics/TA0005), specifically to perform arbitrary execution while subverting detections and/or mitigation controls (such as Group Policy) that limit/prevent the usage of [cmd](https://attack.mitre.org/software/S0106) or file extensions more commonly associated with malicious payloads.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Indirect Command Execution - pcalua.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Indirect Command Execution - pcalua.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | <blockquote>Adversaries may abuse utilities that allow for command execution to bypass security restrictions that limit the use of command-line interpreters. Various Windows utilities may be used to execute commands, possibly without invoking [cmd](https://attack.mitre.org/software/S0106). For example, [Forfiles](https://attack.mitre.org/software/S0193), the Program Compatibility Assistant (pcalua.exe), components of the Windows Subsystem for Linux (WSL), as well as other utilities may invoke the execution of programs and commands from a [Command and Scripting Interpreter](https://attack.mitre.org/techniques/T1059), Run window, or via scripts. (Citation: VectorSec ForFiles Aug 2017) (Citation: Evi1cg Forfiles Nov 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | - [Atomic Test #1 - Indirect Command Execution - pcalua.exe](#atomic-test-1---indirect-command-execution---pcaluaexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | ## Atomic Test #1 - Indirect Command Execution - pcalua.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | The Program Compatibility Assistant (pcalua.exe) may invoke the execution of programs and commands from a Command-Line Interface. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | pcalua.exe -a #{process} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | pcalua.exe -a #{payload_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


