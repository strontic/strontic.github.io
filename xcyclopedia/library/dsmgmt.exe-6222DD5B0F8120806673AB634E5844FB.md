---
title: dsmgmt.exe | NT5DS
---

# dsmgmt.exe 

* File Path: `C:\Windows\SysWOW64\dsmgmt.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `6222DD5B0F8120806673AB634E5844FB`
SHA1 | `CCC8B5BDD3740C4B8DAFF87B2D4BCF2C8891EAB4`
SHA256 | `6BF9FB668246B6AA81328D3FCC19360575E06C3FA0C98008C1810D5088B5DA43`
SHA384 | `B860AB7D5077B769735175DB102A4197EB9CDD4537EE7E38B3074DB05F3F8656A663618DC0099E12778257C340DB95A0`
SHA512 | `45FEF47A77248C16E301B9BF55DBB58B07F3D7C603F28AF3F8676DBD8A5724B06A691565939F70FE82FE69AFC164F29C0ED6E28BB3EFD170A88E41DDA9167536`
SSDEEP | `3072:mKM9vnHihUYTJfoS3o4xraJenr0i4Kg2f87P8KE902XGef+BH3W4sdZIeujJrP4P:EvnChTJfoS39xraJenrhkNREZXX2BHzY`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft(R) Windows(TM) Directory Service Utilities Version 2.0
Copyright (C) Microsoft Corporation 1991-2002. All Rights Reserved.

dsmgmt facilitates managing AD DS/LDS application partitions, management
and control of the Flexible Single Master Operations (FSMO),
and cleaning up of metadata left behind by abandoned AD DCs/LDS instances,
those which are removed from the network without being uninstalled.

This is an interactive tool. Type "help" at the prompt for more information.

 ?                             - Show this help information
 Configurable Settings         - Manage configurable settings
 DS Behavior                   - View and modify AD DS/LDS Behavior
 Group Membership Evaluation   - Evaluate SIDs in token for a given user or
				 group
 Help                          - Show this help information
 LDAP policies                 - Manage LDAP protocol policies
 Local Roles                   - Local RODC roles management
 Metadata cleanup              - Clean up objects of decommissioned servers
 Partition management          - Manage directory partitions
 Popups off                    - Disable popups
 Popups on                     - Enable popups
 Quit                          - Quit the utility
 Roles                         - Manage NTDS role owner tokens
 Security account management   - Manage Security Account Database - Duplicate
				 SID Cleanup
 Set DSRM Password             - Reset directory service restore mode 
				 administrator account password



```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\SysWOW64\en-US\dsmgmt.exe.mui | File
(RW-)   C:\Users\Administrator\Documents | File
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
C:\Windows\SysWOW64\dsmgmt.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsmgmt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\dcdiag.exe](dcdiag.exe-CA1502D2B3342A4F8890FC8A120E4B32.md) | 41
[C:\Windows\SysWOW64\repadmin.exe](repadmin.exe-D79A33E972B365D254CD6B9718DCB213.md) | 41




MIT License. Copyright (c) 2020 Strontic.


