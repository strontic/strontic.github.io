---
title: WorkFolders.exe | Work Folders
excerpt: What is WorkFolders.exe?
---

# WorkFolders.exe 

* File Path: `C:\WINDOWS\system32\WorkFolders.exe`
* Description: Work Folders

## Hashes

Type | Hash
-- | --
MD5 | `1DB54E2E5D713F1B7B3B0D4E3B6CED52`
SHA1 | `7ADB609C9EB76CCE66EE744557B8766962D2BC4E`
SHA256 | `F4704F7172E0CB5F4C79775A91638F94D3220562A4DC8F660373F29D1AD0848C`
SHA384 | `111A8DDCF0F56AD94C60D9CF2EFFB863F1A91A35997B44E903501B56B7A7EF170A97EBF73F05D2474279840F2FA22258`
SHA512 | `F0F134201FCD250CE1900BAF5E21FD591DDEFC9D9F32BE7CF1C87FBF49C205D37609B8B472785720EB4152CF8DDB59093B5CFE76F369FFD08F702C15B47E0F55`
SSDEEP | `1536:xtZvJRBO2lLmer8ul+Mr0wlIm1wisw/8cxEa:H7/tmInl+Mr0wlIm1Uw0cxE`
IMP | `7C7016FD29449ABF043594BBD6397B63`
PESHA1 | `7B1BBCC2164A11954418586AB096898388B7938E`
PE256 | `A261858BB445D0AED2849E60DF901FBCC2C6D79406937CA7D0037833B293A580`

## Runtime Data

### Child Processes:
control.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\system32\dmEnrollEngine.DLL |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\system32\msvcp110_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\system32\policymanager.dll |
C:\WINDOWS\system32\profapi.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |
C:\WINDOWS\system32\WorkFolders.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WorkFolders.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f4704f7172e0cb5f4c79775a91638f94d3220562a4dc8f660373f29d1ad0848c/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-60B652CC67A3CC3DF4929574E8002738.md) | 47
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-8373D16B14416C0F892DDFECBB4CBFAC.md) | 52
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-E981562DBC7E8680D21EF6F78ED91006.md) | 54
[C:\Windows\system32\WorkFoldersRes.dll](WorkFoldersRes.dll-268D2AC1DBF7EBA04E0AE10E8C812331.md) | 52
[C:\Windows\SysWOW64\WorkFoldersRes.dll](WorkFoldersRes.dll-8B3FDCE08A2D909FD22DA56C2418D5CC.md) | 52

## Possible Misuse

*The following table contains possible examples of `WorkFolders.exe` being misused. While `WorkFolders.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `title: Execution via WorkFolders.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `description: Detects using WorkFolders.exe to execute an arbitrary control.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_workfolders.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_workfolders.yml) | `ParentImage\|endswith: '\WorkFolders.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `Name: WorkFolders.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `- Command: WorkFolders`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `- Path: C:\Windows\System32\WorkFolders.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [WorkFolders.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/WorkFolders.yml) | `- IOC: WorkFolders.exe should not be run on a normal workstation`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


