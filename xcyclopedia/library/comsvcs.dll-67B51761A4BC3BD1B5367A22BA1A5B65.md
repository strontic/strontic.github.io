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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CoCreateActivity` | 8 (0x8) | Exported Function | 0x000000018003bfd0 | 0x0003bfd0
`Ordinal7` | 7 (0x7) | Exported Function | 0x000000018003c230 | 0x0003c230
`Ordinal6` | 6 (0x6) | Exported Function | 0x0000000180002890 | 0x00002890
`MTSCreateActivity` | 23 (0x17) | Exported Function | 0x000000018003c2f0 | 0x0003c2f0
`MiniDumpW` | 24 (0x18) | Exported Function | 0x0000000180021e30 | 0x00021e30
`GetTrkSvrObject` | 22 (0x16) | Exported Function | 0x0000000180021d50 | 0x00021d50
`GetObjectContext` | 21 (0x15) | Exported Function | 0x000000018002d2e0 | 0x0002d2e0
`GetMTAThreadPoolMetrics` | 19 (0x13) | Exported Function | 0x0000000180021be0 | 0x00021be0
`GetManagedExtensions` | 20 (0x14) | Exported Function | 0x0000000180021c80 | 0x00021c80
`DllUnregisterServer` | 18 (0x12) | Exported Function | 0x0000000180002890 | 0x00002890
`DllRegisterServer` | 17 (0x11) | Exported Function | 0x0000000180002890 | 0x00002890
`DllGetClassObject` | 16 (0x10) | Exported Function | 0x0000000180021900 | 0x00021900
`DllCanUnloadNow` | 15 (0xf) | Exported Function | 0x00000001800218b0 | 0x000218b0
`DispManGetContext` | 14 (0xe) | Exported Function | 0x000000018002e990 | 0x0002e990
`CosGetCallContext` | 5 (0x5) | Exported Function | 0x0000000180033960 | 0x00033960
`ComSvcsLogError` | 13 (0xd) | Exported Function | 0x000000018002d200 | 0x0002d200
`ComSvcsExceptionFilter` | 12 (0xc) | Exported Function | 0x0000000180021780 | 0x00021780
`CoLoadServices` | 11 (0xb) | Exported Function | 0x0000000180074010 | 0x00074010
`CoLeaveServiceDomain` | 10 (0xa) | Exported Function | 0x0000000180028fd0 | 0x00028fd0
`CoEnterServiceDomain` | 9 (0x9) | Exported Function | 0x0000000180028ea0 | 0x00028ea0
`RecycleSurrogate` | 25 (0x19) | Exported Function | 0x000000018002d320 | 0x0002d320
`SafeRef` | 26 (0x1a) | Exported Function | 0x000000018002d330 | 0x0002d330


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


