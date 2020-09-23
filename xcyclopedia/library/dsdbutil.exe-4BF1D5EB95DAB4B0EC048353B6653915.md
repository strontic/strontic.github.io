---
title: dsdbutil.exe | NT5DS
excerpt: What is dsdbutil.exe?
---

# dsdbutil.exe 

* File Path: `C:\Windows\system32\dsdbutil.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `4BF1D5EB95DAB4B0EC048353B6653915`
SHA1 | `108DC5DE0C232086941704FB522E3BCF134F5F2B`
SHA256 | `C9E704B6D6FD081E305C14BD8526B83B4165C04877584A99E8E1F8A0AB5C1F2C`
SHA384 | `EDB2C0F5547A14E3722CD7167A0ADBCEA230EE106F4F4BA8C289771B16435346E2891A8C369206B9FAF9FF1ABD7B690A`
SHA512 | `A1195636698D3FC2EA26FF9840B704EF5426ABB162F5E1CB19272C8145A3434810C1D42B17888B68CF3D2BDD5EE3B86526A589DDB07CFAB6444FBE177DC616BC`
SSDEEP | `6144:ujvypYe8yDZGzS2MA2ojjtZckR66HpgFZTzZSSGKfz/HWG:u4Ye8yDZGzS2MA2QDPJgPTzZSSGU/HW`

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
 Files                         - Manage AD DS/LDS database files
 Help                          - Show this help information
 IFM                           - IFM media creation
 LDAP Port %d                  - Configure LDAP Port for an AD LDS Instance.
 List Instances                - List all AD LDS instances installed 
				 on this machine.
 Popups off                    - Disable popups
 Popups on                     - Enable popups
 Quit                          - Quit the utility
 Semantic database analysis    - Semantic Checker
 Snapshot                      - Snapshot management
 SSL Port %d                   - Configure SSL Port for an AD LDS Instance.


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\dsdbutil.exe.mui | File
(RW-)   C:\Users\Administrator\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\system32\dsdbutil.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsDbUtil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


