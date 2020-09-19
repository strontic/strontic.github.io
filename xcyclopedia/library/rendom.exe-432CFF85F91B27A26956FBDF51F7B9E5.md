---
title: rendom.exe | NT5DS
---

# rendom.exe 

* File Path: `C:\Windows\system32\rendom.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `432CFF85F91B27A26956FBDF51F7B9E5`
SHA1 | `BA5E36692AD768DCEC2F47E297DDBF2B25FC7C1C`
SHA256 | `07B9A31A727821CEE6CE821DF1E6CF3F8BCF284612981E49244AB365E4A80670`
SHA384 | `ED95AF347FBFC61116C9E0CA634EEF4FB9D3FD8D21123FAC9C88AAD20A0A33A63A3312A5527FC068F8779BDD73CA6D79`
SHA512 | `2A5DE4DA6DB3F61526967FE518B51CCCB3A848EC7193F4FAB5B4D44E0757F8803C6B6A878513375E92C773AA1E54C46E0E4F683BDFB3BF49E7A1648E424BFEA2`
SSDEEP | `3072:3cnKbk6Y+VGGM7OxjZKgZyWhQRQs7UoSle6DDY3Uf1Mm0:gx6Y+UGM7Oxlr3hQRr7pSlHDYkf1`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft(R) Windows(TM) Active Directory domain rename utility Version 1.5
Copyright (C) Microsoft Corporation 1991-2006. All Rights Reserved.

Rendom performs various actions necessary for a domain rename operation.

USAGE:
rendom </list | /showforest | /upload | /prepare | /execute | /end | /clean>
      [/user:USERNAME] [/pwd:{PASSWORD|*}]
      [/dc:{DCNAME | DOMAIN}]
      [/listfile:LISTFILE] [/statefile:STATEFILE] [/?]

/dc:{DCNAME | DOMAIN}
      Connect to the DC with name DCNAME. If DOMAIN is specified instead, then
      connect to a DC in that domain. [Default: connect to a DC in the domain
      to which the current computer belongs]

/user:USERNAME	Connect as USERNAME [Default: the logged in user]

/pwd:{PASSWORD | *}
      Password for the user USERNAME [if * is specified instead of a password,
      then prompt for password]

/list
      List the naming contexts in the forest (forest desc) into a file as text
      description using a XML format

/upload
      Upload the auto-generated script into the directory that will perform the
      domain rename related directory changes on all domain controllers

/prepare
      Prepare for domain rename by verifying authorization, successful
      replication of the uploaded script and network connectivity

/execute
      Execute the uploaded script on all domain controllers to actually perform
      the domain rename operation

/clean
      Clean up all state left behind in the directory by the domain rename
      operation

/listfile:LISTFILE
      Use LISTFILE as the name of the file used to hold the list of naming
      contexts in the forest (forest desc). This file is created by the
      /list command and is used as input for the /upload command. [Default:
      file DOMAINLIST.XML in the current dir]

/statefile:STATEFILE
      Use STATEFILE as the name of the file used to keep track of the state of
      the domain rename operation on each DC in the forest. This file is
      created by the /upload command. [Default: file DCLIST.XML in the current
      dir]

/showforest
      Display the forest structure as represented by its naming contexts
      contained in the LISTFILE using a friendly indented format.

/end
      Ends the rename operation.  Removes restrictions placed on the
      Directory Service during the rename operation.

/disablefaz
      Will not use FAZ to verify proper DNS record support for domain rename.

/dnszonefile:DNSZONEFILE
      The name of the file to use for dns zone verifications.


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rendom.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rendom.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


