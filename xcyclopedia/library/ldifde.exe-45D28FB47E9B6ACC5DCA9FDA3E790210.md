---
title: ldifde.exe | NT5DS
---

# ldifde.exe 

* File Path: `C:\Windows\system32\ldifde.exe`
* Description: NT5DS
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `45D28FB47E9B6ACC5DCA9FDA3E790210`
SHA1 | `229DFCDC09E5648A038106A28D514AC8393BE8AF`
SHA256 | `5AD7A0CEF6122EA7EF485F75B75E4EC758882F43B5EC570E644690ECC80AE5E4`
SHA384 | `516DA4B98A3AB712824CCDA0D7BD2744492892B4A61BE5428D1CB9A3CFB956E39F21A3856AB03E491B58053DA20A28B2`
SHA512 | `46E9B4212245F354EE905A951FCD07F4550BC1894A7420B3F903147644E591664BBFD20ABABEBA78843293B52AAFBD3F9373444DC8A7931079DA2E6798D25B8C`
SSDEEP | `1536:5X4PujIdV8eEkqVukaXp0uAwp48JvuFtn/XI1zqYIyCR:5X4WDOUG6ut3JKRXIKt`

## Runtime Data

### Usage (stdout):
```Batchfile
Invalid Parameter: Input file name required

LDIF Directory Exchange

General Parameters
==================
-i              Turn on Import Mode (The default is Export)
-f filename     Input or Output filename
-s servername   The server to bind to (Default to DC of computer's domain)
-c FromDN ToDN  Replace occurences of FromDN to ToDN
                If either FromDN or ToDN ends with #attributeName, the
                attribute value will be looked up in rootDSE and used to
                replace #attributeName.  See example for "Macro expansion
                in DNs".
-v              Turn on Verbose Mode
-j path         Log File Location
-t port         Port Number (default = 389)
-u              Use Unicode format
-w timeout      Terminate execution if the server takes longer than the
                specified number of seconds to respond to an operation
                (default = no timeout specified)
-h              Enable SASL layer signing and encryption
-?              Help

Export Specific
===============
-d RootDN       The root of the LDAP search (Default to Naming Context)
-r Filter       LDAP search filter (Default to "(objectClass=*)")
-p SearchScope  Search Scope (Base/OneLevel/Subtree)
-l list         List of attributes (comma separated) to look for
                in an LDAP search
-o list         List of attributes (comma separated) to omit from
                input.
-g              Disable Paged Search.
-m              Enable the SAM logic on export.
-n              Do not export binary values
-x              Include deleted objects (tombstones)
-1              Retain only the important replPropertyMetadata

Import
======
-k              The import will go on ignoring 'Constraint Violation'
                and 'Object Already Exists' errors
-y              The import will use lazy commit for better performance
                (enabled by default)
-e              The import will not use lazy commit
-q threads      The import will use the specified number of threads
                (default is 1)             
-z              Continue importing irrespective of errors.
-x              Enable tombstone reanimation support (passes deleted 
                objects control with ldap modify requests)

Credentials Establishment
=========================
Note that if no credentials is specified, LDIFDE will bind as the currently
logged on user, using SSPI.

-a UserDN [Password | *]            Simple authentication
-b UserName Domain [Password | *]   SSPI bind method

Example: Simple import of current domain
    ldifde -i -f INPUT.LDF

Example: Simple export of current domain
    ldifde -f OUTPUT.LDF

Example: Export of specific domain with credentials
    ldifde -m -f OUTPUT.LDF
           -b USERNAME DOMAINNAME *
           -s SERVERNAME
           -d "cn=users,DC=DOMAINNAME,DC=Microsoft,DC=Com"
           -r "(objectClass=user)"

Example: Macro expansion in DNs
    ldifde -f export.ldf -c "#configurationNamingContext" "cn=configuration,dc=x"
    ldifde -i -f import.ldf -c "cn=configuration,dc=x" "#configurationNamingContext"

No log files were written.  In order to generate a log file, please
specify the log file path via the -j option.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ldifde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ldifde.exe` being misused. While `ldifde.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_judgement_panda_gtr19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_judgement_panda_gtr19.yml) | `            - '*\ldifde.exe -f -n *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


