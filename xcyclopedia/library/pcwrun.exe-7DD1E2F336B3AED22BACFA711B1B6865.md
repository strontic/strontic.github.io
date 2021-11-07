---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
excerpt: What is pcwrun.exe?
---

# pcwrun.exe 

* File Path: `C:\Windows\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `7DD1E2F336B3AED22BACFA711B1B6865`
SHA1 | `E7E4D21EF4E8B5DDC063E97D92A9B752D9EB0E95`
SHA256 | `3E324CB58048F034E83168C1D4A66A8984C2238F0CABB6C6357BCACE00E2BB50`
SHA384 | `9FC0CAF6DFA951668C8699E75FD0141499222DD1F12723325F3950ED01EAFC8AD23C931249EBA98EDC1EC40976AA2C0C`
SHA512 | `90594FAFFAF99469DC69A9F3BA86C230F83413D3DDCE73EDF2E0902703636086F719287E806269203DA57A0DB733F187754D718A51B9F7A95323D8D5742D7F33`
SSDEEP | `192:mvSmJnyjUKTlOBkBgFvOCjZp6OebqGhQBQuIfkpBuJdrxUYmTWDgW:mqmJnyj3MBcsvrp6rThIjWJwtTWDgW`
IMP | `B78658A8BFA515AFA2CD46E53317253F`
PESHA1 | `884EC77551DA5F1AB1F7CB06EF46564A6C872C11`
PE256 | `C4896F24F226C668E4AD94AC17DF7F94417FF71FC72D792BC6F13769D43D5CE8`

## Runtime Data

### Child Processes:
msdt.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\pcwrun.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
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

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1202 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1202
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3e324cb58048f034e83168c1d4a66a8984c2238f0cabb6c6357bcace00e2bb50/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\pcwrun.exe](pcwrun.exe-5304FC0B26B34335369EAEDD7BB30E97.md) | 58

## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `description: Detect indirect command execution via Program Compatibility Assistant pcwrun.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Pcwrun/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `ParentImage\|endswith: '\pcwrun.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Command: Pcwrun.exe c:\temp\beacon.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Path: C:\Windows\System32\pcwrun.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


