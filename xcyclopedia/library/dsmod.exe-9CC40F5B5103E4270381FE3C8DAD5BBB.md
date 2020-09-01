---
title: dsmod.exe | Microsoft AD DS/LDS modification command line utility
---

# dsmod.exe 

* File Path: `C:\Windows\system32\dsmod.exe`
* Description: Microsoft AD DS/LDS modification command line utility

## Hashes

Type | Hash
-- | --
MD5 | `9CC40F5B5103E4270381FE3C8DAD5BBB`
SHA1 | `9FF5DAD8530733C1C94060E336AA72717C7BB598`
SHA256 | `DC8001BA719DB2E8959CAEEFDB1538B6427B453EFF592F0B679600C2C8560CB5`
SHA384 | `322B8528D216F05E505DF2B45B8B6394B0561E87885D307417FCEA396C2F6EA2211B7624205CB9256E3CFA56B0A5E641`
SHA512 | `4F39452F2F07FEBE697D4EFE0C0E507C831BAB2C301C629F6421FB36A689F0DE543707F18123127719F620C27AC90F2ED829CE0E38133821EB28DD53D4272A59`
SSDEEP | `1536:kT1f/lpyIYoVeoD9IIvGcWqjTRpqlR8ue:cwgHIILWUTRMRH`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
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





MIT License. Copyright (c) 2020 Strontic.


