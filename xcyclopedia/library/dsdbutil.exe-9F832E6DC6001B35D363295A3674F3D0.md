---
title: dsdbutil.exe | NT5DS
excerpt: What is dsdbutil.exe?
---

# dsdbutil.exe 

* File Path: `C:\Windows\SysWOW64\dsdbutil.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `9F832E6DC6001B35D363295A3674F3D0`
SHA1 | `EF21B51A442BB79CEF79FD9F98019AAA023431A6`
SHA256 | `6DEDF777A2C8BA7B686C34272D426281C6DEAD3770D2C80D7A2AE59DED50846D`
SHA384 | `FFC0CD3BC9D9F4DB0455A2EB573BDF5B86DB2F12098DC2614E6FA9DC1526FE89A712BAFAD04271C0322985C0160E6DC7`
SHA512 | `FC70ED9E032D4EF733FDAB1149B958BDDC1ED85539260C67DE75C134FF03BD3DA917F1B316E6386C82C4A17717DEC4459DFD54762C780227618D814631D6E88B`
SSDEEP | `6144:ozZF+xDcIqEx54mmqI9mbRHDfzumv8nX0:ozZF0jqgDmB9Wnumv`

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
(R-D)   C:\Windows\SysWOW64\en-US\dsdbutil.exe.mui | File
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
C:\Windows\SysWOW64\dsdbutil.exe |


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


