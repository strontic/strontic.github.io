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
MD5 | `E981562DBC7E8680D21EF6F78ED91006`
SHA1 | `E800E6A7186B97D72004171A427869F97E6D1F4C`
SHA256 | `A4ED29118F6A9C15A16668161BCC872C4785D76F68144B57D2FE1011EC4764B6`
SHA384 | `4BED9FD2D32A23A018B57A173BFFEFF51E4AAACF076D026C5E762EC0E901C8B11ABFF0A370A8EA5284CA2D8D0C0B92B8`
SHA512 | `CC5B782DC7D9BC058E86E993207A45660436279D694A5425FE18C2CA58B6E3409C566D047CADE4BBB9E328A1775ED59C1F065D6BFE892F75171E352F144370ED`
SSDEEP | `1536:l2QTk0Va3gfCVMrS7rF+VlCaIm1wisw/8cxEa:lbTRZ6ZPF+VlCaIm1Uw0cxE`

## Runtime Data

### Child Processes:
control.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WorkFolders.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.778 (WinBuild.160101.0800)
* Product Version: 10.0.18362.778
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WorkFolders.exe](WorkFolders.exe-1DB54E2E5D713F1B7B3B0D4E3B6CED52.md) | 54
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-60B652CC67A3CC3DF4929574E8002738.md) | 49
[C:\Windows\system32\WorkFolders.exe](WorkFolders.exe-8373D16B14416C0F892DDFECBB4CBFAC.md) | 57
[C:\Windows\system32\WorkFoldersRes.dll](WorkFoldersRes.dll-268D2AC1DBF7EBA04E0AE10E8C812331.md) | 55
[C:\Windows\SysWOW64\WorkFoldersRes.dll](WorkFoldersRes.dll-8B3FDCE08A2D909FD22DA56C2418D5CC.md) | 55

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


