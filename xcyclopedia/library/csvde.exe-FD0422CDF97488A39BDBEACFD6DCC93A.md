---
title: csvde.exe | NT5DS
excerpt: What is csvde.exe?
---

# csvde.exe 

* File Path: `C:\Windows\system32\csvde.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `FD0422CDF97488A39BDBEACFD6DCC93A`
SHA1 | `2E2A3974DB883D060029359A556ACD6971969CD0`
SHA256 | `F916B38169CD76FC866F4594BF9BA48513F520C43BAEECA7BD0E03CF98C94C42`
SHA384 | `A735583C551376FA7256CFD23D16559B09C760472DCCD1148BBF5CAD628D4B8A570B7C3CE2717F25908A79F1756F96B6`
SHA512 | `2C459BF163864421919DBDB108ACCED1E92A5F2AA06C68CFD5EA36E0D589153FF953465B324C88F09C231EC6898A1F6452A4C164A919F41F6FD65A5F110958DE`
SSDEEP | `768:0jlFXXvALZMS57p9SZEMOdW1RyMCMgBcL0yN5C7V2NMr6y5B1TfRx5jq5d:+lJf+MS57p8ZtOtMnm0XaYNM6y5Bt9jq`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid Parameter: Input file name required

CSV Directory Exchange

General Parameters
==================
-i              Turn on Import Mode (The default is Export)
-f filename     Input or Output filename
-s servername   The server to bind to (Default to DC of computer's domain)
-v              Turn on Verbose Mode
-c FromDN ToDN  Replace occurences of FromDN to ToDN
-j path         Log File Location
-t port         Port Number (default = 389)
-u              Use Unicode format
-h              Enable SASL layer signing and encryption
-?              Help


Export Specific
===============
-d RootDN       The root of the LDAP search (Default to Naming Context)
-r Filter       LDAP search filter (Default to "(objectClass=*)")
-p SearchScope  Search Scope (Base/OneLevel/Subtree)
-l list         List of attributes (comma separated) to look for in an 
                LDAP search
-o list         List of attributes (comma separated) to omit from input.
-g              Disable Paged Search.
-m              Enable the SAM logic on export.
-n              Do not export binary values


Import 
======
-k              The import will go on ignoring 'Constraint Violation' and 
                'Object Already Exists' errors


Credentials Establishment
=========================
Note that if no credentials is specified, CSVDE will bind as the currently
logged on user, using SSPI.

-a UserDN [Password | *]            Simple authentication
-b UserName Domain [Password | *]   SSPI bind method

Example: Simple import of current domain
    csvde -i -f INPUT.CSV
    
Example: Simple export of current domain
    csvde -f OUTPUT.CSV
    
Example: Export of specific domain with credentials 
    csvde -m -f OUTPUT.CSV 
          -b USERNAME DOMAINNAME *
          -s SERVERNAME
          -d "cn=users,DC=DOMAINNAME,DC=Microsoft,DC=Com"
          -r "(objectClass=user)"
No log files were written.  In order to generate a log file, please
specify the log file path via the -j option.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\csvde.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: csvde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


