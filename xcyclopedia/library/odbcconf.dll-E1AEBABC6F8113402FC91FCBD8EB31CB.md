---
title: odbcconf.dll | ODBC Driver Configuration Program
excerpt: What is odbcconf.dll?
---

# odbcconf.dll 

* File Path: `C:\Windows\system32\odbcconf.dll`
* Description: ODBC Driver Configuration Program

## Hashes

Type | Hash
-- | --
MD5 | `E1AEBABC6F8113402FC91FCBD8EB31CB`
SHA1 | `00DFC0BD5E293D794E1534BBA0346DE76EAC1A49`
SHA256 | `DD39EC58EE0789C4B10FA823B59641DEF885F4F4AC261A009AEBFBD6CEE46876`
SHA384 | `29880BEBB62A827170BB9297F6FB222C6F0692DCE13911A56A8B6C071F054299A061C7AEC94C9B46EEC1E8C22C66D44F`
SHA512 | `3C55BB29D1E769FB020245E165CB151C3DE177B4F7BDEFF4B6A409AE5752C36C44801C1AF57F849C6565C5C003EF12A6DB48F8F56B44B4EC47C6C034852781ED`
SSDEEP | `384:KC3ZWA5vkvh9vGLOSE9lZykxeP36U0H9MGd5fXqwgLEt8tt/+1ndnjDsCSrpbHXP:Ky5svTcOLlZyH3cwttG1d1SNbHAi`
IMP | `CFEFE1E5EA10F7D533537E26D8704082`
PESHA1 | `D975C464D617C7A0C8ED7FDD76C979B0B5DF9E6B`
PE256 | `6385FB3128F95FBCE1D8CCE96DE23F734503F49A4903D87DB12654685B712B37`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AppRegEnum` | 13 (0xd) | Exported Function | 0x00000001800035a0 | 0x000035a0
`SetActionName` | 12 (0xc) | Exported Function | 0x0000000180001590 | 0x00001590
`SetActionLogModeSz` | 8 (0x8) | Exported Function | 0x0000000180002ca0 | 0x00002ca0
`SetActionLogMode` | 9 (0x9) | Exported Function | 0x0000000180002d00 | 0x00002d00
`SetActionLogFile` | 7 (0x7) | Exported Function | 0x0000000180002c50 | 0x00002c50
`SetActionEnum` | 11 (0xb) | Exported Function | 0x00000001800014c0 | 0x000014c0
`RunDLL32_UnregisterApplication` | 20 (0x14) | Exported Function | 0x0000000180003520 | 0x00003520
`RunDLL32_RegisterApplication` | 19 (0x13) | Exported Function | 0x0000000180003520 | 0x00003520
`RegisterApplication` | 18 (0x12) | Exported Function | 0x0000000180003530 | 0x00003530
`RefreshAppRegEnum` | 17 (0x11) | Exported Function | 0x0000000180003530 | 0x00003530
`QueryApplication` | 16 (0x10) | Exported Function | 0x0000000180003540 | 0x00003540
`OpenAppRegEnum` | 15 (0xf) | Exported Function | 0x0000000180003520 | 0x00003520
`ExecuteAction` | 10 (0xa) | Exported Function | 0x0000000180001660 | 0x00001660
`DllUnregisterServer` | 25 (0x19) | Exported Function | 0x0000000180003520 | 0x00003520
`DllRegisterServer` | 24 (0x18) | Exported Function | 0x0000000180003520 | 0x00003520
`DllGetClassObject` | 23 (0x17) | Exported Function | 0x0000000180003600 | 0x00003600
`DllCanUnloadNow` | 22 (0x16) | Exported Function | 0x00000001800035d0 | 0x000035d0
`CloseAppRegEnum` | 14 (0xe) | Exported Function | 0x0000000180003530 | 0x00003530
`SetSilent` | 6 (0x6) | Exported Function | 0x0000000180002c40 | 0x00002c40
`UnregisterApplication` | 21 (0x15) | Exported Function | 0x0000000180003530 | 0x00003530


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/dd39ec58ee0789c4b10fa823b59641def885f4f4ac261a009aebfbd6cee46876/detection/


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


