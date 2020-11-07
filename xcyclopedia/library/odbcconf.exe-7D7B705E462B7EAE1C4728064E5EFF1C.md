---
title: odbcconf.exe | ODBC Driver Configuration Program
excerpt: What is odbcconf.exe?
---

# odbcconf.exe 

* File Path: `C:\Windows\system32\odbcconf.exe`
* Description: ODBC Driver Configuration Program

## Screenshot

![odbcconf.exe](screenshots/odbcconf.exe-4D7DE33E313C4E6E55FF977BB7E71512-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `7D7B705E462B7EAE1C4728064E5EFF1C`
SHA1 | `50D0ABDA40FC878682723BDAECC12D3974419429`
SHA256 | `476346234300504CCCF360EF8172B4E07CCA59B43B7F09818B11B71210DF3481`
SHA384 | `5876AB1D3FD483E7BB6565EC668FADF0D7FCA52BB935C066682508647E0C103469D2664082DA7600600D87E0674F6265`
SHA512 | `745036FA0BDDE18E2302580C4EE0E95969D1C27F6F0741A95581A0C45F4946ED926D9F30D9D018308A4A3734A074C959DF51275C5A81FBE253D7F93BFC4A2779`
SSDEEP | `768:O3PYdy60y+LCmASNmMexDlqxCSl9NBid:9yry+LCmASNoxlqjlMd`
IMP | `09AE8655C843B33D7FA4CDD4F87AD0BF`
PESHA1 | `4B4449F11177B18DA4FB9ACD258458A97AF61A92`
PE256 | `76AECFF9B1075695955082677F4F392D838627B8A6335E4160C9D5778EBF1035`

## Runtime Data

### Window Title:
Invalid Parameter

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\odbcconf.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1800662698 | Section
\Windows\Theme722103516 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\odbcconf.dll |
C:\Windows\system32\odbcconf.exe |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\TextShaping.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: odbcconf.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/476346234300504cccf360ef8172b4e07cca59b43b7f09818b11b71210df3481/detection


## Possible Misuse

*The following table contains possible examples of `odbcconf.exe` being misused. While `odbcconf.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


