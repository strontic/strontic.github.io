﻿---
title: odbcconf.exe | ODBC Driver Configuration Program
excerpt: What is odbcconf.exe?
---

# odbcconf.exe 

* File Path: `C:\WINDOWS\SysWOW64\odbcconf.exe`
* Description: ODBC Driver Configuration Program

## Screenshot

![odbcconf.exe](screenshots/odbcconf.exe-4D7DE33E313C4E6E55FF977BB7E71512-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `86D1F10725566E818EEDB82ACBCD5CBE`
SHA1 | `76A40EE9C48CCD840E236C769165D77E1CD28B16`
SHA256 | `1FE23FAB90945A9C7EE6029FD953BF9360544127444B71620DA6852C408DD04E`
SHA384 | `1AFB8FE726725389DA550AB39B66A2BF32E0C0F22D4081FE07057A2571880FF30E927DD451B124B9FE669F3E9E0FA962`
SHA512 | `EFDD926F4AC98924D8FE09CD8E07BEFA3356B3E7C6AA49829EFDCD86FABB4F9D3E2D8E202E31254498460AC6C88795674448D4B136BDC1838373785AA441D1FE`
SSDEEP | `384:yVrAigT9MLPeRYdggm+EVlCK2tCnnnMreqsOlJvHRp/VeBdpStFVzlYOyvC1yJaG:gPe97ntuJgggC16SQs9sj`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: odbcconf.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\odbcconf.exe](odbcconf.exe-35CDB46FD7E96B9357D75FF285099B14.md) | 60
[C:\windows\SysWOW64\odbcconf.exe](odbcconf.exe-607DDC78852AE90B118040B3E4CC96D2.md) | 33
[C:\WINDOWS\SysWOW64\odbcconf.exe](odbcconf.exe-666D4A8753A62D3B291A6364EDE9BED4.md) | 35
[C:\Windows\SysWOW64\odbcconf.exe](odbcconf.exe-B38C108A8DB4B97EA352287BF796A273.md) | 35
[C:\Windows\SysWOW64\odbcconf.exe](odbcconf.exe-D567FFF92055255DBE43BF8F989A4B7E.md) | 47

## Possible Misuse

*The following table contains possible examples of `odbcconf.exe` being misused. While `odbcconf.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `title: Application Whitelisting Bypass via DLL Loaded by odbcconf.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `description: Detects defence evasion attempt via odbcconf.exe execution to load DLL`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `Image\|endswith: '\odbcconf.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `ParentImage\|endswith: '\odbcconf.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `- Legitimate use of odbcconf.exe by legitimate user`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `Name: Odbcconf.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Command: odbcconf -f file.rsp`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Command: odbcconf /a {REGSVR c:\test\test.dll}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Path: C:\Windows\System32\odbcconf.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Path: C:\Windows\SysWOW64\odbcconf.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.008 Odbcconf](../../T1218.008/T1218.008.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Odbcconf.exe - Execute Arbitrary DLL [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.008 Odbcconf](../../T1218.008/T1218.008.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Odbcconf.exe - Execute Arbitrary DLL [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Shortcut Modification](../../T1547.009/T1547.009.md) \| Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Shortcut Modification](../../T1547.009/T1547.009.md) \| [Winlogon Helper DLL](../../T1547.004/T1547.004.md) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | # T1218.008 - Odbcconf | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | <blockquote>Adversaries may abuse odbcconf.exe to proxy execution of malicious payloads. Odbcconf.exe is a Windows utility that allows you to configure Open Database Connectivity (ODBC) drivers and data source names.(Citation: Microsoft odbcconf.exe) Odbcconf.exe is digitally signed by Microsoft. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | Adversaries may abuse odbcconf.exe to bypass application control solutions that do not account for its potential abuse. Similar to [Regsvr32](https://attack.mitre.org/techniques/T1218/010), odbcconf.exe has a <code>REGSVR</code> flag that can be misused to execute DLLs (ex: <code>odbcconf.exe /S /A &lbrace;REGSVR "C:\Users\Public\file.dll"&rbrace;</code>). (Citation: LOLBAS Odbcconf)(Citation: TrendMicro Squiblydoo Aug 2017)(Citation: TrendMicro Cobalt Group Nov 2017)  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | - [Atomic Test #1 - Odbcconf.exe - Execute Arbitrary DLL](#atomic-test-1---odbcconfexe---execute-arbitrary-dll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | ## Atomic Test #1 - Odbcconf.exe - Execute Arbitrary DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | odbcconf.exe /S /A {REGSVR "#{dll_payload}"} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml) | `name: Signed Binary Execution - odbcconf`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml) | `description: Leverage odbcconf for DLL injection`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/a74bc239-a196-4f7e-8d5c-fe8c0266071c.yml) | `odbcconf.exe /S /A {REGSVR "C:\Users\Public\sandcat.dll"}`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


