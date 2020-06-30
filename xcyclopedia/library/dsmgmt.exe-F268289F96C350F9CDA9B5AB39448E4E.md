---
title: dsmgmt.exe | NT5DS
---

# dsmgmt.exe 

* File Path: `C:\Windows\system32\dsmgmt.exe`
* Description: NT5DS
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F268289F96C350F9CDA9B5AB39448E4E`
SHA1 | `891A1DFA389152571DB948CE3C236F303CB449FE`
SHA256 | `FBD635CC9DD65F705ACC7A88060D9A1984AA724FA5FF962F63807B867BF637AC`
SHA384 | `79A13CDBFDE904B9F9D48FA553F4C79E2F07E51C9A0AB0F983A3FE4F41E4773E89C32622F2AA37CA6400E719CEBF4F75`
SHA512 | `1ED1469C3EF4A2DC45C9CB6D92C119C27983450B9458B2DF22433FA588A0479A4574CD78DB434FC013462C06148BC3DA02A4086A8F519AE22681B75D04BB9145`
SSDEEP | `6144:7neoo4G9IFZPNDOfOWEdwB7Q0KZPX7AFaFH8NwZaWc52oYM9hkl:7nesG9ILFCDEdw+0KFAmD`

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
[C:\Windows\system32\dcdiag.exe](dcdiag.exe-7936349C0FD5FEF9317F678460C78707.md) | 35
[C:\Windows\system32\repadmin.exe](repadmin.exe-951B223D0B582BF2B5ED27EF3130F7BF.md) | 40




MIT License. Copyright (c) 2020 Strontic.


