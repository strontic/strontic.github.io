---
title: csvde.exe | NT5DS
---

# csvde.exe 

* File Path: `C:\Windows\SysWOW64\csvde.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `935267851F2D94580E2D0CE701C76551`
SHA1 | `6AEC94AD0469DD5BC037D9E7F0A9D269591E87A1`
SHA256 | `6CD703B0FA9F4F771F74006AF109DB80FB634209B57C3D5CC10A97363979F29D`
SHA384 | `CC365AFE3F1226506D1A12D20EC6D19E8726A0328ADB2710808E0D2FD11074B281F4FE9F278808E99837C119AA75DE5E`
SHA512 | `97CE1FD0390CE39A1299897E726DEBBB2F7586732CA420B9C431B68AA95B7991240EE0AE52F6BCB03D674C6C57BFE62C91C07A30C696323C0361E06E54BA6CDB`
SSDEEP | `768:pJhG+P2p06sCJ2MckstOokKwCNtSCDnAByPaD6RWjQk4jjz1Z6:pJhG06sC1ckstOo/wCNDAByP+jijz1`

## Runtime Data

### Usage (stdout):
```Batchfile
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


