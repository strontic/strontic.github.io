---
title: comsvcs.dll | COM+ Services
excerpt: What is comsvcs.dll?
---

# comsvcs.dll 

* File Path: `C:\Windows\system32\comsvcs.dll`
* Description: COM+ Services

## Hashes

Type | Hash
-- | --
MD5 | `67B51761A4BC3BD1B5367A22BA1A5B65`
SHA1 | `88C7BD6A30CBFB069CD34B04B0844D4AABE0577C`
SHA256 | `1AEA658899018FB370C39412BA62E3E8E8FD7A636657593530BD67005B3754B7`
SHA384 | `5D4A90012E16872A31D5C676C4EA07CB1D33BEFB2D3A4C299F8F2E8952FAFC5765D20D7F74003D9D5615E846D40A0971`
SHA512 | `FD5834F676519D18DE098747ECA70C516A18148369EFEDD8E7123071943E114CF23EBCFC360EF8C28403794E7ED713B243B662085FABAAB99DA59BAEA3CA34EF`
SSDEEP | `24576:m4yGAJkRUbm3c0cCCUO3o5VxzYTw4F+64w:mPPkR1M0lJO3mVxzYk4F+6`
IMP | `407CA0F7B523319D758A40D7C0193699`
PESHA1 | `347D2C6532B66A90EC62C74D799765446099ADD7`
PE256 | `B7FCA33B779F632076859B0F34099E88034FE3F51DD888930A849A33F3EA0EEC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`GetMTAThreadPoolMetrics` | 19 | Exported Function
`GetObjectContext` | 21 | Exported Function
`GetManagedExtensions` | 20 | Exported Function
`DllRegisterServer` | 17 | Exported Function
`DllUnregisterServer` | 18 | Exported Function
`RecycleSurrogate` | 25 | Exported Function
`SafeRef` | 26 | Exported Function
`MTSCreateActivity` | 23 | Exported Function
`GetTrkSvrObject` | 22 | Exported Function
`MiniDumpW` | 24 | Exported Function
`CoLoadServices` | 11 | Exported Function
`ComSvcsExceptionFilter` | 12 | Exported Function
`CoLeaveServiceDomain` | 10 | Exported Function
`CoCreateActivity` | 8 | Exported Function
`CoEnterServiceDomain` | 9 | Exported Function
`DllCanUnloadNow` | 15 | Exported Function
`DllGetClassObject` | 16 | Exported Function
`DispManGetContext` | 14 | Exported Function
`ComSvcsLogError` | 13 | Exported Function
`CosGetCallContext` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: COMSVCS.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/1aea658899018fb370c39412ba62e3e8e8fd7a636657593530bd67005b3754b7/detection/


## Possible Misuse

*The following table contains possible examples of `comsvcs.dll` being misused. While `comsvcs.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- ' comsvcs.dll,MiniDump'  # Process dumping method apart from procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- ' comsvcs.dll,#24'  # Process dumping method apart from procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rundll32_comsvcs.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rundll32_comsvcs.yml) | `title: Process Dump via Rundll32 and Comsvcs.dll` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rundll32_comsvcs.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rundll32_comsvcs.yml) | `description: Detects a process memory dump performed via ordinal function 24 in comsvcs.dll` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rundll32_comsvcs.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rundll32_comsvcs.yml) | `- 'comsvcs.dll,#24'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rundll32_comsvcs.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rundll32_comsvcs.yml) | `- 'comsvcs.dll,MiniDump'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_comsvcs_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_comsvcs_procdump.yml) | `title: Process Dump via Comsvcs DLL` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_comsvcs_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_comsvcs_procdump.yml) | `description: Detects process memory dump via comsvcs.dll and rundll32` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_comsvcs_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_comsvcs_procdump.yml) | `- '*comsvcs*MiniDump*full*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_comsvcs_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_comsvcs_procdump.yml) | `- '*comsvcs*MiniDumpW*full*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [comsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/comsvcs.yml) | `Name: Comsvcs.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [comsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/comsvcs.yml) | `- Command: rundll32 C:\windows\system32\comsvcs.dll MiniDump "[LSASS_PID] dump.bin full"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [comsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/comsvcs.yml) | `Description: Calls the MiniDump exported function of comsvcs.dll, which in turns calls MiniDumpWriteDump. ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [comsvcs.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/comsvcs.yml) | `- Path: c:\windows\system32\comsvcs.dll` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Dump LSASS.exe Memory using comsvcs.dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Dump LSASS.exe Memory using comsvcs.dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | - [Atomic Test #3 - Dump LSASS.exe Memory using comsvcs.dll](#atomic-test-3---dump-lsassexe-memory-using-comsvcsdll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ## Atomic Test #3 - Dump LSASS.exe Memory using comsvcs.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Upon successful execution, you should see the following file created $env:TEMP\lsass-comsvcs.dmp. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | C:\Windows\System32\rundll32.exe C:\windows\System32\comsvcs.dll, MiniDump (Get-Process lsass).id $env:TEMP\lsass-comsvcs.dmp full | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Remove-Item $env:TEMP\lsass-comsvcs.dmp -ErrorAction Ignore | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


