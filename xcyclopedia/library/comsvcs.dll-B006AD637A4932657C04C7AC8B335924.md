---
title: comsvcs.dll | COM+ Services
excerpt: What is comsvcs.dll?
---

# comsvcs.dll 

* File Path: `C:\Windows\SysWOW64\comsvcs.dll`
* Description: COM+ Services

## Hashes

Type | Hash
-- | --
MD5 | `B006AD637A4932657C04C7AC8B335924`
SHA1 | `BBD475DF5033F585D7F6AD9D22D7CD2B5CE5FFB6`
SHA256 | `E0B9FCA1F03CC9D196A78339A0CCBBBA32BEA78A0FE645257D32310B5AD4E273`
SHA384 | `1EC3DB752784F5F2EBC78CB91504229C26C518846D73D5B8C24D562D731F563B52EA49F3DFEC68A6AB140C60A47F7225`
SHA512 | `CEBE4A35F94CDDEAEA60B36BB00437B1E902061B8F85F6B3F72117B6AA448AE7E9AC9A55741B2BE4741CFCB8B30EA0F66CB9131B9880C26F423F022C4D162F7C`
SSDEEP | `24576:/xddbmUfF1z4Nhsaxf9etlZ23pTF5v41i4llZOayt:Dmhz6KufllZE`
IMP | `281D618F4E6271E527E6386EA6F748DE`
PESHA1 | `73FA5F23BAB33D421046BDDF9B7C9F153920D37F`
PE256 | `B5F9B40F50B5235F4B0157C1A736B66A18694DA462516A94127849CB78BAD478`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CoCreateActivity` | 8 (0x8) | Exported Function | 0x10079ce0 | 0x00079ce0
`Ordinal7` | 7 (0x7) | Exported Function | 0x10079ef0 | 0x00079ef0
`Ordinal6` | 6 (0x6) | Exported Function | 0x10044300 | 0x00044300
`MTSCreateActivity` | 23 (0x17) | Exported Function | 0x10079f60 | 0x00079f60
`MiniDumpW` | 24 (0x18) | Exported Function | 0x10064b90 | 0x00064b90
`GetTrkSvrObject` | 22 (0x16) | Exported Function | 0x10064aa0 | 0x00064aa0
`GetObjectContext` | 21 (0x15) | Exported Function | 0x1006e280 | 0x0006e280
`GetMTAThreadPoolMetrics` | 19 (0x13) | Exported Function | 0x10064990 | 0x00064990
`GetManagedExtensions` | 20 (0x14) | Exported Function | 0x10064a10 | 0x00064a10
`DllUnregisterServer` | 18 (0x12) | Exported Function | 0x10044300 | 0x00044300
`DllRegisterServer` | 17 (0x11) | Exported Function | 0x10044300 | 0x00044300
`DllGetClassObject` | 16 (0x10) | Exported Function | 0x1003eb60 | 0x0003eb60
`DllCanUnloadNow` | 15 (0xf) | Exported Function | 0x100648e0 | 0x000648e0
`DispManGetContext` | 14 (0xe) | Exported Function | 0x1006eff0 | 0x0006eff0
`CosGetCallContext` | 5 (0x5) | Exported Function | 0x10072800 | 0x00072800
`ComSvcsLogError` | 13 (0xd) | Exported Function | 0x1006e190 | 0x0006e190
`ComSvcsExceptionFilter` | 12 (0xc) | Exported Function | 0x10064800 | 0x00064800
`CoLoadServices` | 11 (0xb) | Exported Function | 0x100aa340 | 0x000aa340
`CoLeaveServiceDomain` | 10 (0xa) | Exported Function | 0x1006aac0 | 0x0006aac0
`CoEnterServiceDomain` | 9 (0x9) | Exported Function | 0x1006a9b0 | 0x0006a9b0
`RecycleSurrogate` | 25 (0x19) | Exported Function | 0x1006e2b0 | 0x0006e2b0
`SafeRef` | 26 (0x1a) | Exported Function | 0x1006e2d0 | 0x0006e2d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/61
* VirusTotal Link: https://www.virustotal.com/gui/file/e0b9fca1f03cc9d196a78339a0ccbbba32bea78a0fe645257d32310b5ad4e273/detection/


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


