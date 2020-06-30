---
title: ntdsutil.exe | NT5DS
---

# ntdsutil.exe 

* File Path: `C:\Windows\system32\ntdsutil.exe`
* Description: NT5DS
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FBF152DADED7AF9E20980C8B68240A95`
SHA1 | `F55569ADC3A792654A977CE9FD9B1F3D2009D69B`
SHA256 | `692D8824D329AB6A2ED520CEDA1F13EBF0CAB9E8D32C4FD0A2F1BC980A0C002A`
SHA384 | `85C72D7D534CAD29B2A6618E92D42102461276C12457C6F0FBAA315DB9430F0AEA2BA2ABDBAE90C6601278E3018397D0`
SHA512 | `3367492FFF5ECB43296C1DF0F12FAA679F454A450385270C649A88F37D538240C8B05A0862B320970B172C16218753F598A3B55285B4BE4D29D9DDF08DD6981A`
SSDEEP | `12288:khXbbOpCsfDzMRU5PdviO9WrBCRwiGwfn+L0zXACne/JIxXe:kgpCsfDzMRcPd9sBCL+qACne/uXe`

## Runtime Data

### Usage (stdout):
```Batchfile
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

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

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

*The following table contains possible examples of `ntdsutil.exe` being misused. While `ntdsutil.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `title: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `description: Detects execution of ntdsutil.exe, which can be used for various attacks against the NTDS database (NTDS.DIT)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `    - https://jpcertcc.github.io/ToolAnalysisResultSheet/details/ntdsutil.htm` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ntdsutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ntdsutil.yml) | `        CommandLine: '*\ntdsutil*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `Name: ntdsutil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `  - Command: ntdsutil.exe "ac i ntds" "ifm" "create full c:\" q q` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `  - Path: C:\Windows\System32\ntdsutil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ntdsutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Ntdsutil.yml) | `  - IOC: ntdsutil.exe with command line including "ifm"` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #3: Dump Active Directory Database with NTDSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #3: Dump Active Directory Database with NTDSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | * Using the in-built Windows tool, ntdsutil.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | - [Atomic Test #3 - Dump Active Directory Database with NTDSUtil](#atomic-test-3---dump-active-directory-database-with-ntdsutil) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | ## Atomic Test #3 - Dump Active Directory Database with NTDSUtil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | The Active Directory database NTDS.dit may be dumped using NTDSUtil for offline credential theft attacks. This capability | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | ntdsutil "ac i ntds" "ifm" "create full #{output_folder}" q q | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


