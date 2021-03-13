---
title: dsmod.exe | Microsoft AD DS/LDS modification command line utility
excerpt: What is dsmod.exe?
---

# dsmod.exe 

* File Path: `C:\Windows\SysWOW64\dsmod.exe`
* Description: Microsoft AD DS/LDS modification command line utility

## Hashes

Type | Hash
-- | --
MD5 | `E2546514E2D3FD06D0F11854AF263E36`
SHA1 | `ECBD71EFE03473A447E1F32C7BEFA1D8AC2569B8`
SHA256 | `A5F9D49B28F89E9C260FC0706FD7C1C3B5B4824A684724F07BB0423AEE9559DD`
SHA384 | `5B29E8FB11FC3C2226D639021BC8A13A8505121E29BDB089CFB39F85AD14951CD5CFF51C0A13DF3FE21497A2F3277110`
SHA512 | `EDC158B35C5E738E5509EBF63FE3F0EF3FBBCFA25E95C9E3A472341A22A75695D72559DB29AFECEBC0EAE565321086097584A111FC64B9688908D8562990AA3B`
SSDEEP | `768:TmNt/r3xucgvzML0p4QnYavW44JlPT4Fljiu2q+JzNqZ:Tij3xmv4c4QYavF4jr4FReq+VNS`

## Runtime Data

### Usage (stdout):
```cmhg
Description:  This dsmod command modifies existing objects in the directory.
The dsmod commands include:

dsmod computer - modifies an existing computer in the directory.
dsmod contact - modifies an existing contact in the directory.
dsmod group - modifies an existing group in the directory.
dsmod ou - modifies an existing organizational unit in the directory.
dsmod server - modifies an existing AD DC/LDS instance in the directory.
dsmod user - modifies an existing user in the directory.
dsmod quota - modifies an existing quota specification in the directory.
dsmod partition - modifies an existing partition specification in the directory.

For help on a specific command, type "dsmod <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsmod ou /?.

Remarks:
The dsmod commands support piping of input to allow you to pipe results from
the dsquery commands as input to the dsmod commands and modify the objects
found by the dsquery commands.

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").

Backslashes used in distinguished names must be escaped with a backslash 
(for example,
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").

Examples:
To find all users in the organizational unit (OU)
"ou=Marketing,dc=microsoft,dc=com" and add them to the Marketing Staff group:

dsquery user -startnode "ou=Marketing,dc=microsoft,dc=com" | 
dsmod group "cn=Marketing Staff,ou=Marketing,dc=microsoft,dc=com" -addmbr

Directory Service command-line tools help:
dsadd /? - help for adding objects.
dsget /? - help for displaying objects.
dsmod /? - help for modifying objects.
dsmove /? - help for moving objects.
dsquery /? - help for finding objects matching search criteria.
dsrm /? - help for deleting objects.

```

### Usage (stderr):
```cmhg
Description:  This dsmod command modifies existing objects in the directory.
The dsmod commands include:

dsmod computer - modifies an existing computer in the directory.
dsmod contact - modifies an existing contact in the directory.
dsmod group - modifies an existing group in the directory.
dsmod ou - modifies an existing organizational unit in the directory.
dsmod server - modifies an existing AD DC/LDS instance in the directory.
dsmod user - modifies an existing user in the directory.
dsmod quota - modifies an existing quota specification in the directory.
dsmod partition - modifies an existing partition specification in the directory.

For help on a specific command, type "dsmod <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsmod ou /?.

Remarks:
The dsmod commands support piping of input to allow you to pipe results from
the dsquery commands as input to the dsmod commands and modify the objects
found by the dsquery commands.

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").

Backslashes used in distinguished names must be escaped with a backslash 
(for example,
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").

Examples:
To find all users in the organizational unit (OU)
"ou=Marketing,dc=microsoft,dc=com" and add them to the Marketing Staff group:

dsquery user -startnode "ou=Marketing,dc=microsoft,dc=com" | 
dsmod group "cn=Marketing Staff,ou=Marketing,dc=microsoft,dc=com" -addmbr

Directory Service command-line tools help:
dsadd /? - help for adding objects.
dsget /? - help for displaying objects.
dsmod /? - help for modifying objects.
dsmove /? - help for moving objects.
dsquery /? - help for finding objects matching search criteria.
dsrm /? - help for deleting objects.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\dsmod.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsmod.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020-2021 Strontic.


