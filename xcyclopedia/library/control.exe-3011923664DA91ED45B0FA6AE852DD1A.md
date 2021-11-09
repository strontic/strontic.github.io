---
title: control.exe | Windows Control Panel
excerpt: What is control.exe?
---

# control.exe 

* File Path: `C:\Windows\system32\control.exe`
* Description: Windows Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `3011923664DA91ED45B0FA6AE852DD1A`
SHA1 | `DA28F05F804E2E02EF2594B899B51976E745455A`
SHA256 | `54D9F98F36BC5511D281318B8022002F74AD30B6383696E861220E15EE68E5A3`
SHA384 | `98AE8CC78B1E74D2F0A6CD6B5F32567B80B3C2092E0682E81E4418BD2407EAE3C13E8681B9B577B522C5E5E9EDECBA6A`
SHA512 | `F09F07F6285A7ED8AB6066F95EC4C770378D40282D41ED65D3CC7DE701EC73506053BADE2AF0D34C98DF8E6CEF4CFBB77A22B6C63B1C179E27FF53D2BC0A6AF3`
SSDEEP | `3072:tCPVV7dL01mNUug7Sp5+1k12b/Af885RK:tCtVZi7+5+1kf15`
IMP | `ED7ECF5DCE55D515F7FE036FCAEBFF1A`
PESHA1 | `191F24AF6F8B7D227ACD9944247824BBA5A334E4`
PE256 | `9DD0AB521FF0F56FDEAD107709DB7A598F63AB9C0F9FC09205561FC95011FFE9`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\control.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONTROL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/54d9f98f36bc5511d281318b8022002f74ad30b6383696e861220e15ee68e5a3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\control.exe](control.exe-44A936B4839A614723811EA66423B432.md) | 69
[C:\windows\system32\control.exe](control.exe-4B605DF70C49B6B9D65652879ACAEE32.md) | 71
[C:\WINDOWS\system32\control.exe](control.exe-62D970D8B60F75C12D21C740F2D8A5DA.md) | 68
[C:\Windows\system32\control.exe](control.exe-88EA810385F455C74306D71C4879C61C.md) | 68
[C:\Windows\system32\control.exe](control.exe-924219B426830FF7476AF7D22AE91DE1.md) | 68
[C:\Windows\system32\control.exe](control.exe-D7D596CA323E67AAE7F8752BD9B45A1E.md) | 66
[C:\Windows\SysWOW64\control.exe](control.exe-1F13E714A0FEA8887707DFF49287996F.md) | 66
[C:\Windows\SysWOW64\control.exe](control.exe-359DE40504BF90EFD590C248B71C8B81.md) | 66
[C:\Windows\SysWOW64\control.exe](control.exe-4DBD69D4C9DA5AAAC731F518EF8EBEA0.md) | 68
[C:\WINDOWS\SysWOW64\control.exe](control.exe-C7C91F18B0F90ABE6C09D3CEAA895E83.md) | 66
[C:\Windows\SysWOW64\control.exe](control.exe-C8FA632CEF3B25E6AAD2C3ACFCF98E59.md) | 66
[C:\WINDOWS\SysWOW64\control.exe](control.exe-DB53126BF65990E37E3A3B12D3DEDBCE.md) | 66
[C:\windows\SysWOW64\control.exe](control.exe-F74B09C54E47526BB0679F8F0967AD0E.md) | 68

## Possible Misuse

*The following table contains possible examples of `control.exe` being misused. While `control.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_cve_2021_40444.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_cve_2021_40444.yml) | `Image\|endswith: '\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_cve_2021_40444.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_cve_2021_40444.yml) | `CommandLine\|endswith: '\control.exe input.dll'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `description: Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `ParentImage\|endswith: '\System32\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `description: Detects using WorkFolders.exe to execute an arbitrary control.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `Image\|endswith: '\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `Image: 'C:\Windows\System32\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `Name: Control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Command: control.exe c:\windows\tasks\file.txt:evil.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\System32\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\SysWOW64\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- IOC: Control.exe executing files from alternate data streams.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `Description: Execute control.exe in the current working directory`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | <blockquote>Adversaries may abuse control.exe to proxy execution of malicious payloads. The Windows Control Panel process binary (control.exe) handles execution of Control Panel items, which are utilities that allow users to view and adjust computer settings. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | This test simulates an adversary leveraging control.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | control.exe #{cpl_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


