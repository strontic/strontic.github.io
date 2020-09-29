---
title: odbcconf.dll | ODBC Driver Configuration Program
excerpt: What is odbcconf.dll?
---

# odbcconf.dll 

* File Path: `C:\Windows\SysWOW64\odbcconf.dll`
* Description: ODBC Driver Configuration Program

## Hashes

Type | Hash
-- | --
MD5 | `0DF72F82DBA6D180C4D8B9D41E3B4A6B`
SHA1 | `F178411A1B7314A1E51D4ADEF8BEB2AAA458D49A`
SHA256 | `9DD42117834404D129318CCEAEFEB3162A0999260CC9747A1F0D1B297D35B2E9`
SHA384 | `ABADCDE1F7C705A880FD02EFB377FA928629484697FF0AB003110407CACD23BC8DAA9A14608C5E4F4F62F9CBFC14A1C3`
SHA512 | `572C6A74A741B6E74702E808E9384E3E215AF7EF62B523AE32E3F7163967E09C0F895C58362D8E17A6EF9E0D366070B9C9AA1E94A24C157747893F5BADD54E5E`
SSDEEP | `384:27f3qwAL0tzT36a5dluw91XNzBhW+95RkEMqyD+3rRZaTk+uUG7rk13WTnW7+bV:2hT36a5DQTEddraTy741g+m`
IMP | `AE0423E38C4B09A0CB1292292A890F1B`
PESHA1 | `D73990B9726860E582E5C9CEB1D990CC6F2DDC66`
PE256 | `2B8C7F132CB95BC411E8FE8716F4E355C547D3DB01F60DC9BA57D43D0B760E87`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AppRegEnum` | 13 (0xd) | Exported Function | 0x10003f00 | 0x00003f00
`SetActionName` | 12 (0xc) | Exported Function | 0x100022f0 | 0x000022f0
`SetActionLogModeSz` | 8 (0x8) | Exported Function | 0x10003580 | 0x00003580
`SetActionLogMode` | 9 (0x9) | Exported Function | 0x10003600 | 0x00003600
`SetActionLogFile` | 7 (0x7) | Exported Function | 0x10003530 | 0x00003530
`SetActionEnum` | 11 (0xb) | Exported Function | 0x10002270 | 0x00002270
`RunDLL32_UnregisterApplication` | 20 (0x14) | Exported Function | 0x10003e00 | 0x00003e00
`RunDLL32_RegisterApplication` | 19 (0x13) | Exported Function | 0x10003e00 | 0x00003e00
`RegisterApplication` | 18 (0x12) | Exported Function | 0x10003e10 | 0x00003e10
`RefreshAppRegEnum` | 17 (0x11) | Exported Function | 0x10003e20 | 0x00003e20
`QueryApplication` | 16 (0x10) | Exported Function | 0x10003e30 | 0x00003e30
`OpenAppRegEnum` | 15 (0xf) | Exported Function | 0x10003ef0 | 0x00003ef0
`ExecuteAction` | 10 (0xa) | Exported Function | 0x10002390 | 0x00002390
`DllUnregisterServer` | 25 (0x19) | Exported Function | 0x10003ef0 | 0x00003ef0
`DllRegisterServer` | 24 (0x18) | Exported Function | 0x10003ef0 | 0x00003ef0
`DllGetClassObject` | 23 (0x17) | Exported Function | 0x10003f40 | 0x00003f40
`DllCanUnloadNow` | 22 (0x16) | Exported Function | 0x10003f20 | 0x00003f20
`CloseAppRegEnum` | 14 (0xe) | Exported Function | 0x10003e20 | 0x00003e20
`SetSilent` | 6 (0x6) | Exported Function | 0x10003510 | 0x00003510
`UnregisterApplication` | 21 (0x15) | Exported Function | 0x10003e20 | 0x00003e20


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: odbcconf.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/9dd42117834404d129318cceaefeb3162a0999260cc9747a1f0d1b297d35b2e9/detection/


## Possible Misuse

*The following table contains possible examples of `odbcconf.dll` being misused. While `odbcconf.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `title: Application Whitelisting Bypass via DLL Loaded by odbcconf.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `description: Detects defence evasion attempt via odbcconf.exe execution to load DLL` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `Image\|endswith: '\odbcconf.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `ParentImage\|endswith: '\odbcconf.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_odbcconf.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_odbcconf.yml) | `- Legitimate use of odbcconf.exe by legitimate user` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `Name: Odbcconf.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Command: odbcconf -f file.rsp` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Command: odbcconf /a {REGSVR c:\test\test.dll}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Path: C:\Windows\System32\odbcconf.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Odbcconf.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Odbcconf.yml) | `- Path: C:\Windows\SysWOW64\odbcconf.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.008 Odbcconf](../../T1218.008/T1218.008.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Odbcconf.exe - Execute Arbitrary DLL [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.008 Odbcconf](../../T1218.008/T1218.008.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Odbcconf.exe - Execute Arbitrary DLL [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Screensaver](../../T1546.002/T1546.002.md) \| Thread Execution Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Services Registry Permissions Weakness](../../T1574.011/T1574.011.md) \| [Windows Service](../../T1543.003/T1543.003.md) \| [Odbcconf](../../T1218.008/T1218.008.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | # T1218.008 - Odbcconf | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | <blockquote>Adversaries may abuse odbcconf.exe to proxy execution of malicious payloads. Odbcconf.exe is a Windows utility that allows you to configure Open Database Connectivity (ODBC) drivers and data source names.(Citation: Microsoft odbcconf.exe) Odbcconf.exe is digitally signed by Microsoft. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | Adversaries may abuse odbcconf.exe to bypass application control solutions that do not account for its potential abuse. Similar to [Regsvr32](https://attack.mitre.org/techniques/T1218/010), odbcconf.exe has a <code>REGSVR</code> flag that can be misused to execute DLLs (ex: <code>odbcconf.exe /S /A &lbrace;REGSVR "C:\Users\Public\file.dll"&rbrace;</code>). (Citation: LOLBAS Odbcconf)(Citation: TrendMicro Squiblydoo Aug 2017)(Citation: TrendMicro Cobalt Group Nov 2017)  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | - [Atomic Test #1 - Odbcconf.exe - Execute Arbitrary DLL](#atomic-test-1---odbcconfexe---execute-arbitrary-dll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | ## Atomic Test #1 - Odbcconf.exe - Execute Arbitrary DLL | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.008/T1218.008.md) | odbcconf.exe /S /A {REGSVR "#{dll_payload}"} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


