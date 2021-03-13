---
title: mavinject.exe | Microsoft Application Virtualization Injector
excerpt: What is mavinject.exe?
---

# mavinject.exe 

* File Path: `C:\WINDOWS\system32\mavinject.exe`
* Description: Microsoft Application Virtualization Injector

## Hashes

Type | Hash
-- | --
MD5 | `80EAEBA49FFD53712F4304A442C95F0D`
SHA1 | `1847CE5831ACAECF84DD3E28A0EE6BF6FB98E343`
SHA256 | `926B54D54DEC971022BD18F97AB970D4533B34A1CEF9C65DCA1B696C1119CD90`
SHA384 | `BB0C4F372DB5D87300D9D4DAEFCAB72234FB7811928B1940754EEB31699517345458B1793DC046FA2794945A21F77B5D`
SHA512 | `530FB4C73C8F3F85823301A68339E3653CC8F98411861938D544859D2B3BDE2155B44F2BFF1266792483E1E8A125E3969734BE5FA172A8B709132AFC05C5A51B`
SSDEEP | `3072:s0/7kEjgqJcKsiUsZWGNU6ITLxd7YYU8Q:s0/18YcKsidWGNU6ITLxdUH`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject64.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-2F8BF990BEDECF1974DC4189E24F709D.md) | 40
[C:\WINDOWS\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-4564AEECEED25F34A2A6156A355C09B6.md) | 41
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-EAA5FF4ED735D3D1FE292600A9E3DEC6.md) | 44
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-FE1414362471F8F2603A41BDA2B81526.md) | 35
[C:\Windows\system32\AppVFileSystemMetadata.dll](AppVFileSystemMetadata.dll-F35D3437B238B8F4492C58CA0149A861.md) | 38
[C:\Windows\system32\AppVManifest.dll](AppVManifest.dll-63DCC5E32AD7A665CF6FCE44C1CDCAB8.md) | 38
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-47C060EF467EB3E4461D26BCBC858377.md) | 44
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-8F6A8E7CEF9833166DE4A29920B48F42.md) | 43
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-E4CC15631219560406D2CE920CB2C133.md) | 36
[C:\WINDOWS\system32\AppVNice.exe](AppVNice.exe-E805EC74A53B64CE1D9D6739B8055579.md) | 38
[C:\Windows\system32\AppVScripting.dll](AppVScripting.dll-6D1231B56C6C71BA3522410EB53D00C4.md) | 35
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-3E705409974662FD944B65C3B9ADAC31.md) | 43
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-422209DBC6879722C59054DBFBCDA152.md) | 44
[C:\WINDOWS\system32\AppVShNotify.exe](AppVShNotify.exe-9252AC3912987BB99FA84EF48C00440D.md) | 29
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-F4E5D8D8C06466305663EC35C617D458.md) | 44
[C:\Windows\system32\AppVStreamingUX.dll](AppVStreamingUX.dll-C9966B7BA8CFDCD1D97185C3634763E3.md) | 44
[C:\Windows\system32\AppVStreamMap.dll](AppVStreamMap.dll-520D8187FFAE4758054A49A29831CE67.md) | 36
[C:\Windows\system32\mavinject.exe](mavinject.exe-3196E7F92E0B4367444A185B5A4E757D.md) | 41
[C:\Windows\system32\mavinject.exe](mavinject.exe-72D5E2A3FF5D88C891E0DF1AA28B6422.md) | 40
[C:\Windows\system32\mavinject.exe](mavinject.exe-73E25B03C4DF5277BAF67004D53FC241.md) | 43
[C:\Windows\system32\mavinject.exe](mavinject.exe-750E7456BAA3820527FFA4653EF5A516.md) | 38
[C:\Windows\system32\mavinject.exe](mavinject.exe-E354F3D93A7639FCE4D649874766D624.md) | 43

## Possible Misuse

*The following table contains possible examples of `mavinject.exe` being misused. While `mavinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | - [Atomic Test #1 - Process Injection via mavinject.exe](#atomic-test-1---process-injection-via-mavinjectexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | ## Atomic Test #1 - Process Injection via mavinject.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Upon successful execution, powershell.exe will download T1055.dll to disk. Powershell will then spawn mavinject.exe to perform process injection in T1055.dll. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | mavinject $mypid /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.004/T1056.004.md) | mavinject $pid /INJECTRUNNING #{file_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #1 - mavinject - Inject DLL into running process](#atomic-test-1---mavinject---inject-dll-into-running-process) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #1 - mavinject - Inject DLL into running process | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | mavinject.exe #{process_id} /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `name: Signed Binary Execution - Mavinject`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `description: Leverage Mavinject (signed binary) for DLL injection`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `mavinject.exe $explorer.id C:\Users\Public\sandcat.dll`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


