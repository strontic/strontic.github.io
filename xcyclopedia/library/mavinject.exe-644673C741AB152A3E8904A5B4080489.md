---
title: mavinject.exe | Microsoft Application Virtualization Injector
excerpt: What is mavinject.exe?
---

# mavinject.exe 

* File Path: `C:\Windows\SysWOW64\mavinject.exe`
* Description: Microsoft Application Virtualization Injector

## Hashes

Type | Hash
-- | --
MD5 | `644673C741AB152A3E8904A5B4080489`
SHA1 | `0DFA1403967ACCCFD15D608B69B7C327ED5BBEB5`
SHA256 | `18AF462A5EE58BF8BFA175BA734CE91B48E28C7859CA57AB18B5948D1A4B35DD`
SHA384 | `3306653037A4D3B4F88DD29E8B77E837F6798B252CECAA51F61FECF78770F7FAE815A6CD646462ACB5F655B40A7269AF`
SHA512 | `9EAA3DDFF753ED4A0D6B47FFE5815409F3D39D8DCFA7ADC5FF2BFF0167F908AFF34B051BD8511E97BB985F8DEFA3B2A30CD79504AD639829ED274DC46F975556`
SSDEEP | `3072:nQ7FmBt0fSoD79hILhpVVrujzKdu5ommZPEAkp8:imBt0fSoD79hOLazAZ`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3659 (rs1_release_1.200410-1813)
* Product Version: 10.0.14393.3659
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVDllSurrogate32.exe](AppVDllSurrogate32.exe-BB87D970CD29CC07A84A92E637ADD9A2.md) | 38
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVLP.exe](AppVLP.exe-F8CF92A63D69595CE0E6ECB9265EA7F7.md) | 32
[C:\Program Files\Common Files\microsoft shared\ClickToRun\MavInject32.exe](MavInject32.exe-AC6978D0FEF8F6F2F07051473D188F02.md) | 29
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-49338D141DD60CA212D85F60521FB1DF.md) | 49
[C:\WINDOWS\SysWOW64\mavinject.exe](mavinject.exe-639104A1BBEE03C2101A3FDC4FB4DF8A.md) | 36
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-651259747F1C4401A88A23AD816BB0ED.md) | 43
[C:\WINDOWS\SysWOW64\mavinject.exe](mavinject.exe-8FE5871DE2870F39CFA317FA5C28988D.md) | 54
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-A0B66B648C645B6B2A982C9414153437.md) | 33
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-B8B01B6A24B8A2BA242D96DB63298120.md) | 43
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-CB3E03CBECB798CE4254E1D17716C623.md) | 32

## Possible Misuse

*The following table contains possible examples of `mavinject.exe` being misused. While `mavinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_mavinject_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_creation_mavinject_dll.yml) | `title: Mavinject Inject DLL Into Running Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_mavinject_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_creation_mavinject_dll.yml) | `OriginalFileName\|contains: mavinject`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `title: MavInject Process Injection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `- https://reaqta.com/2017/12/mavinject-microsoft-injector/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `Name: Mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: MavInject.exe 3110 /INJECTRUNNING c:\folder\evil.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: Mavinject.exe 4172 /INJECTRUNNING "c:\ads\file.txt:file.dll"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\System32\mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\SysWOW64\mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- IOC: mavinject.exe should not run unless APP-v is in use on the workstation`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.001/T1055.001.md) | - [Atomic Test #1 - Process Injection via mavinject.exe](#atomic-test-1---process-injection-via-mavinjectexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.001/T1055.001.md) | ## Atomic Test #1 - Process Injection via mavinject.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.001/T1055.001.md) | Upon successful execution, powershell.exe will download T1055.dll to disk. Powershell will then spawn mavinject.exe to perform process injection in T1055.dll. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.001/T1055.001.md) | mavinject $mypid /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.004/T1056.004.md) | mavinject $pid /INJECTRUNNING #{file_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #1 - mavinject - Inject DLL into running process](#atomic-test-1---mavinject---inject-dll-into-running-process) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #1 - mavinject - Inject DLL into running process | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | mavinject.exe #{process_id} /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `name: Signed Binary Execution - Mavinject`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `description: Leverage Mavinject (signed binary) for DLL injection`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `mavinject.exe $explorer.id C:\Users\Public\sandcat.dll`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


