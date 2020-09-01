---
title: rendom.exe | NT5DS
---

# rendom.exe 

* File Path: `C:\Windows\SysWOW64\rendom.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `7EBAF6AD28BCAD4D7E1886C62DC91722`
SHA1 | `AABF91BA4DB9533DC11744F7877214FBCC7975E1`
SHA256 | `E375651B0A6AB4594618426E591A2196690A6ABAC5F31AE341E33F49486BA93D`
SHA384 | `FD76FA253EAE3CEAA17F6A2B8CB4D26FA546B6C7F9902D76184F907026564AA69C92C8A887362F22EFB15E72173CE0D0`
SHA512 | `C5A73B004D520BEE6BFC1E96F39343FF3670CB1EF01379F73178866ECCC508E8AF54F179E592C9DCF74D067FD93308E5C851C905958C1C46E629AA7816E33360`
SSDEEP | `3072:4SVuucV13OoScqAU1b8GiQLq/Dy+gXMNqXNS:4SVo13mXb5Vr+gXMNcNS`

## Runtime Data

### Usage (stdout):
```Batchfile
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
C:\Windows\SysWOW64\rendom.exe |


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


