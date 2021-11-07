---
title: runonce.exe | Run Once Wrapper
excerpt: What is runonce.exe?
---

# runonce.exe 

* File Path: `C:\Windows\SysWOW64\runonce.exe`
* Description: Run Once Wrapper

## Hashes

Type | Hash
-- | --
MD5 | `A368C8AFDAEB269F48E8D7A006EE6A15`
SHA1 | `9856DADD0F49B00C72524E0233A8BF027374DADF`
SHA256 | `E2031017207A33A6FA147A5BB6E32AD5788DF03F783D424A0053BA1B16D561F5`
SHA384 | `052FE97FB8C026D3ABB7311D64D5E9D7CAE993C9B12627433B9BA9BA5ED6943777620257CE27FA8105B9587B362C9552`
SHA512 | `6D276E7969371FDA95A8411CCBFBC8E26ACDAFB8A2814B0FFB32DA6B39C6783A697C01F3BEB7232CEE3492D7F542487ACD5B675C292A6F8CCD8712B5733FC780`
SSDEEP | `768:A/6/iNbCpNS7yjLRUgHA9hIn7A1TI1B5keJx+DGtFwex8ZsAfFW:A/6/iNbcb3nI2mI1cq+ytlaZsAfQ`
IMP | `97CC98DB681CF599B4F85D3B9CF8A780`
PESHA1 | `C5C871F3221A22325C67F0D70555F3BE76E5520E`
PE256 | `762F6C842007D550270AA71FA921AFEB3926850E46748BECDF4A9DE7D2250CD9`

## Runtime Data

### Child Processes:
perfmon.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\runonce.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNONCE.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/e2031017207a33a6fa147a5bb6e32ad5788df03f783d424a0053ba1b16d561f5/detection


## Possible Misuse

*The following table contains possible examples of `runonce.exe` being misused. While `runonce.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `ParentImage\|endswith: '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `ParentCommandLine\|endswith: '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_setupapi_installhinfsection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_setupapi_installhinfsection.yml) | `InstallHinfSection function in setupapi.dll calls runonce.exe executable regardless of actual content of INF file.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_setupapi_installhinfsection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_setupapi_installhinfsection.yml) | `Image\|endswith: '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_runonce_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_runonce_execution.yml) | `- '\runonce.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_runonce_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_runonce_persistence.yml) | `description: Rule to detect the configuration of Run Once registry key. Configured payload can be run by runonce.exe /AlternateShellStartup`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `Name: Runonce.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Command: Runonce.exe /AlternateShellStartup`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\System32\runonce.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\SysWOW64\runonce.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


