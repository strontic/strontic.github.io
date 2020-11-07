---
title: mavinject.exe | Microsoft Application Virtualization Injector
excerpt: What is mavinject.exe?
---

# mavinject.exe 

* File Path: `C:\Windows\system32\mavinject.exe`
* Description: Microsoft Application Virtualization Injector

## Hashes

Type | Hash
-- | --
MD5 | `3196E7F92E0B4367444A185B5A4E757D`
SHA1 | `34A26DEA01EA4A421F5512D1DEED5CDD0A4CCE59`
SHA256 | `CFBCA5DDE322DD0CC6DD07412589B532B59302D4D7B1739BE248F9CDD24CD8E6`
SHA384 | `6F1A5D44FFF031E592DD685D3A4E6CA141AA7E471CFEA8D17BCFC7D9B9BA6BA90B13B2819A688056A0478F39FB5D4726`
SHA512 | `AE0D34ED7377C22715E620C827FAB62801234EC687294BF29BAE2BDD2126BED14464984F197ED70CD3372B3BFA07DFC213C2A6DEF250F0D5E8DEB4AEB0BB9899`
SSDEEP | `3072:1u/7/Qapj1CpO3KTWGNU6ITT9KoN7Dq6DUv:1KQapJCpO4WGNU6ITT9KG0v`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject64.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3659 (rs1_release_1.200410-1813)
* Product Version: 10.0.14393.3659
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-2F8BF990BEDECF1974DC4189E24F709D.md) | 25
[C:\WINDOWS\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-4564AEECEED25F34A2A6156A355C09B6.md) | 32
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-EAA5FF4ED735D3D1FE292600A9E3DEC6.md) | 44
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-FE1414362471F8F2603A41BDA2B81526.md) | 29
[C:\Windows\system32\AppVFileSystemMetadata.dll](AppVFileSystemMetadata.dll-F35D3437B238B8F4492C58CA0149A861.md) | 32
[C:\Windows\system32\AppVManifest.dll](AppVManifest.dll-63DCC5E32AD7A665CF6FCE44C1CDCAB8.md) | 35
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-47C060EF467EB3E4461D26BCBC858377.md) | 35
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-8F6A8E7CEF9833166DE4A29920B48F42.md) | 38
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-E4CC15631219560406D2CE920CB2C133.md) | 36
[C:\WINDOWS\system32\AppVNice.exe](AppVNice.exe-E805EC74A53B64CE1D9D6739B8055579.md) | 50
[C:\Windows\system32\AppVScripting.dll](AppVScripting.dll-6D1231B56C6C71BA3522410EB53D00C4.md) | 30
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-3E705409974662FD944B65C3B9ADAC31.md) | 35
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-422209DBC6879722C59054DBFBCDA152.md) | 38
[C:\WINDOWS\system32\AppVShNotify.exe](AppVShNotify.exe-9252AC3912987BB99FA84EF48C00440D.md) | 36
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-F4E5D8D8C06466305663EC35C617D458.md) | 38
[C:\Windows\system32\AppVStreamingUX.dll](AppVStreamingUX.dll-C9966B7BA8CFDCD1D97185C3634763E3.md) | 36
[C:\Windows\system32\AppVStreamMap.dll](AppVStreamMap.dll-520D8187FFAE4758054A49A29831CE67.md) | 40
[C:\Windows\system32\mavinject.exe](mavinject.exe-72D5E2A3FF5D88C891E0DF1AA28B6422.md) | 41
[C:\Windows\system32\mavinject.exe](mavinject.exe-73E25B03C4DF5277BAF67004D53FC241.md) | 38
[C:\Windows\system32\mavinject.exe](mavinject.exe-750E7456BAA3820527FFA4653EF5A516.md) | 25
[C:\WINDOWS\system32\mavinject.exe](mavinject.exe-80EAEBA49FFD53712F4304A442C95F0D.md) | 41
[C:\Windows\system32\mavinject.exe](mavinject.exe-E354F3D93A7639FCE4D649874766D624.md) | 33

## Possible Misuse

*The following table contains possible examples of `mavinject.exe` being misused. While `mavinject.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `title: MavInject Process Injection` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `- https://reaqta.com/2017/12/mavinject-microsoft-injector/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `Name: Mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: MavInject.exe 3110 /INJECTRUNNING c:\folder\evil.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: Mavinject.exe 4172 /INJECTRUNNING "c:\ads\file.txt:file.dll"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\System32\mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\SysWOW64\mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- IOC: mavinject.exe should not run unless APP-v is in use on the workstation` | 
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



MIT License. Copyright (c) 2020 Strontic.


