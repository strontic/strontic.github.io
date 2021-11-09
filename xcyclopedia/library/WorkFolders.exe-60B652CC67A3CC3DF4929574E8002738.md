---
title: WorkFolders.exe | Work Folders
excerpt: What is WorkFolders.exe?
---

# WorkFolders.exe 

* File Path: `C:\Windows\system32\WorkFolders.exe`
* Description: Work Folders

## Hashes

Type | Hash
-- | --
MD5 | `60B652CC67A3CC3DF4929574E8002738`
SHA1 | `BA12F8F090C82FA627FB0E135711160083EC19C6`
SHA256 | `8EB0B45FDE1883EBA4CFE9545FB64A17243EBFF32ED69FD39E9CB36FEBD54760`
SHA384 | `4AEBFC4698A9487B02EE8012DFBD71F985B298CC452C705221E988668CDD93FDDEE8C76DB442870FAFF035D2AB28146E`
SHA512 | `55A73B1787C6FD8009D93C7D7ABB0CED571590408002E74F994E9F1D5BFFB9517BF5033B51AB909D08A61CE4F02C662F3DDFC5AC3FE605E61A9C9C75D825BBA7`
SSDEEP | `1536:mNhNDlQJs4bZim+iQg+jFCb73Im1wisw/8cxEa:KhGDjkg++73Im1Uw0cxE`
IMP | `7468ED9A85006965C01F519C0D2C8E9F`
PESHA1 | `F4AF209A2EEFAA29D894CC514D825E260AF25062`
PE256 | `A2905B5857B858F60686A06D62143CBCA458445CF61FAC6FDC6910E84E00E9C3`

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
C:\Windows\system32\WorkFolders.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WorkFolders.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1202 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1202
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8eb0b45fde1883eba4cfe9545fb64a17243ebff32ed69fd39e9cb36febd54760/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-1DB54E2E5D713F1B7B3B0D4E3B6CED52.md) | 47
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-8373D16B14416C0F892DDFECBB4CBFAC.md) | 57
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-E981562DBC7E8680D21EF6F78ED91006.md) | 49
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


