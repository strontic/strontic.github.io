﻿---
title: runonce.exe | Run Once Wrapper
excerpt: What is runonce.exe?
---

# runonce.exe 

* File Path: `C:\Windows\SysWOW64\runonce.exe`
* Description: Run Once Wrapper

## Hashes

Type | Hash
-- | --
MD5 | `6FEF96ED9F43ADB12929A3E84856C6FB`
SHA1 | `996F26AFA18D8747DBCA1F2DE180E05E95614D5A`
SHA256 | `78B8D920926EBCC685865A5AC91F21ED40889D538DDE6A4092764F44D7C015F4`
SHA384 | `2F9FC335725459DF4C39DEAEAA0DEB23D639701E3FC2F124C026BB325509DC10062B42FF61681EAA5E0AF618FC4BE478`
SHA512 | `E57DD984F3CC7C10BADA4D06DFACADBCC6D71B4E341A332A41527A16CF5A824F89DD416E6EAD84C2E7CA1F15094BF80244F3778183E29F97C90F493079C7A9BF`
SSDEEP | `768:mymNyL7EVeOf2xegirOiEjMOvDQVhxgMjxI+otootdNK2G8ZELz7Krs:mymNyckiyiobQ1gM1IltPtJdZELz7Krs`
IMP | `6294B7E7E5122F6D1B0C1EA4C1DB0725`
PESHA1 | `80ACBAC9E63CA31A5AADBB5F1F5394F4681BB474`
PE256 | `5E1E7762650711B8448813A8498C4F7A0D6FAC3A755DFB919583BE1B9E137040`

## Runtime Data

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNONCE.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/78b8d920926ebcc685865a5ac91f21ed40889d538dde6a4092764f44d7c015f4/detection/


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


