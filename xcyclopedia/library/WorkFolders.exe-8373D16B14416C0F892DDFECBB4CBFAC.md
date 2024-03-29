﻿---
title: WorkFolders.exe | Work Folders
excerpt: What is WorkFolders.exe?
---

# WorkFolders.exe 

* File Path: `C:\Windows\system32\WorkFolders.exe`
* Description: Work Folders

## Hashes

Type | Hash
-- | --
MD5 | `8373D16B14416C0F892DDFECBB4CBFAC`
SHA1 | `0E3397AE69A35CBDE52719F01097B2930A89C464`
SHA256 | `CFC058A712B0F1A0932E7FA1F17430EEAA231C41FDD1EAD38639D603A8006ACA`
SHA384 | `9E2F49CDD221E6F38DE9F5C40974DCCE0E6216631E9CE81FFA86D7D7671C4BA17155B52DB4E81BC929F34D7B30D06A51`
SHA512 | `9575B2C03492994A4DAECC1920E8B18BE5FD2968DDAA99D4FD1ED7BA2730F2A952669FCD86B653A3FD7E9F45A268D0B9C153FFC80070DD745871E3AA6AA0F9F3`
SSDEEP | `1536:wfNflQGO4bUh97+Bq+KvejHDHIm1wisw/8cxEa:oBhAfT+lHDHIm1Uw0cxE`
IMP | `7468ED9A85006965C01F519C0D2C8E9F`
PESHA1 | `28EDC5C9728C1BF1EE2FADB9985B6D1FC2564BF5`
PE256 | `731232265E86E45F30872B1D4DC4D44127031BFCF3B1B97EA5C91EA47FE1EA39`

## Runtime Data

### Child Processes:
control.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\WorkFolders.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WorkFolders.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/cfc058a712b0f1a0932e7fa1f17430eeaa231c41fdd1ead38639d603a8006aca/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-1DB54E2E5D713F1B7B3B0D4E3B6CED52.md) | 52
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-60B652CC67A3CC3DF4929574E8002738.md) | 57
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-E981562DBC7E8680D21EF6F78ED91006.md) | 57
[C:\Windows\system32\WorkFoldersRes.dll](WorkFoldersRes.dll-268D2AC1DBF7EBA04E0AE10E8C812331.md) | 50
[C:\Windows\SysWOW64\WorkFoldersRes.dll](WorkFoldersRes.dll-8B3FDCE08A2D909FD22DA56C2418D5CC.md) | 50

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


