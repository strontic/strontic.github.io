---
title: ntdsutil.exe | NT5DS
excerpt: What is ntdsutil.exe?
---

# ntdsutil.exe 

* File Path: `C:\Windows\SysWOW64\ntdsutil.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `7605E0CA539B87217BC195E09EB0BF62`
SHA1 | `8686BA6523EB73E12BA2F4D362EB45D82A81E906`
SHA256 | `60EDE9D533D695180715915D41C1EF56021CAC59B4FD073C5C11E977512F1DB4`
SHA384 | `DEED49F075A7548919FB145CA7BC6E5ADA582CA5B5CFD64467D61EB46FB6B24001EED5FEDB6F10B6197B82272BF10D60`
SHA512 | `E3EC16481F57023D276C0947B14F7F874965B747D88739E5807FA81A0DE7C2D43DECEC6D72F2BD037E1F99513F1F9EC56D8FD669EF5BFCCF8133368514E9B051`
SSDEEP | `6144:UzHylnikvi60teB8JppPFOeAeoPaAHHBcNCFNaDhczxIkSWZ2:UzHLJq0ZAlaSmwFNBcWZ`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft(R) Windows(TM) Directory Service Utilities Version 2.0
Copyright (C) Microsoft Corporation 1991-2002. All Rights Reserved.

dsdbutil performs database maintenance of the Active Directory Domain Services store
and facilitates configuration of AD LDS communication ports and view AD LDS 
instances installed on a machine.

This is an interactive tool. Type "help" at the prompt for more information.


 ?                             - Show this help information
 Activate Instance %s          - Set "NTDS" or a specific AD LDS instance
				 as the active instance.
 Authoritative restore         - Authoritatively restore the DIT database
 Change Service Account %s1 %s2 - Change AD DS/LDS Service Account to
				 username %s1 and password %s2.
				 Use "NULL" for blank password, * to
				 enter password from the console.
 Configurable Settings         - Manage configurable settings
 DS Behavior                   - View and modify AD DS/LDS Behavior
 Files                         - Manage AD DS/LDS database files
 Group Membership Evaluation   - Evaluate SIDs in token for a given user or
				 group
 Help                          - Show this help information
 IFM                           - IFM media creation
 LDAP policies                 - Manage LDAP protocol policies
 LDAP Port %d                  - Configure LDAP Port for an AD LDS Instance.
 List Instances                - List all AD LDS instances installed 
				 on this machine.
 Local Roles                   - Local RODC roles management
 Metadata cleanup              - Clean up objects of decommissioned servers
 Partition management          - Manage directory partitions
 Popups off                    - Disable popups
 Popups on                     - Enable popups
 Quit                          - Quit the utility
 Roles                         - Manage NTDS role owner tokens
 Security account management   - Manage Security Account Database - Duplicate
				 SID Cleanup
 Semantic database analysis    - Semantic Checker
 Set DSRM Password             - Reset directory service restore mode 
				 administrator account password

 Snapshot                      - Snapshot management
 SSL Port %d                   - Configure SSL Port for an AD LDS Instance.


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\SysWOW64\en-US\ntdsutil.exe.mui | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ntdsutil.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntdsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ntdsutil.exe` being misused. While `ntdsutil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `title: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `description: Detects execution of ntdsutil.exe, which can be used for various attacks against the NTDS database (NTDS.DIT)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/ntdsutil.htm`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `CommandLine: '*\ntdsutil*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `Name: ntdsutil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `- Command: ntdsutil.exe "ac i ntds" "ifm" "create full c:\" q q`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `- Path: C:\Windows\System32\ntdsutil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `- IOC: ntdsutil.exe with command line including "ifm"`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Dump Active Directory Database with NTDSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Dump Active Directory Database with NTDSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | * Using the in-built Windows tool, ntdsutil.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | - [Atomic Test #3 - Dump Active Directory Database with NTDSUtil](#atomic-test-3---dump-active-directory-database-with-ntdsutil) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | ## Atomic Test #3 - Dump Active Directory Database with NTDSUtil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | The Active Directory database NTDS.dit may be dumped using NTDSUtil for offline credential theft attacks. This capability | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | ntdsutil "ac i ntds" "ifm" "create full #{output_folder}" q q | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


