---
title: dsget.exe | Microsoft AD DS/LDS Get command line utility
---

# dsget.exe 

* File Path: `C:\Windows\SysWOW64\dsget.exe`
* Description: Microsoft AD DS/LDS Get command line utility

## Hashes

Type | Hash
-- | --
MD5 | `1F5282BC8F715E9E58483497B008300A`
SHA1 | `CDEAE2AD3C83D3CD18B3D6A11BF20C2D9AC2510E`
SHA256 | `1A9FB894DC7F4996AA08F708FFD384490924F5C01F36D5534E7F01442E9B3C4B`
SHA384 | `C5CC0AFD8A0350C37C812134A514D2C2F39854438978ACF052F86C9CD7A936947B7E21EAD4249CC374D2FD65E3A61C8B`
SHA512 | `44E782BCD2E3A8071F69AFC5A4D791D94A2464FFEDEAEDE39098E807F63850FC431AE4EE91EDFD0878459ECC4C8D89E67E95C0CD594BA6EDC592BF8F8356556F`
SSDEEP | `1536:VXsZ2cqVsJK1fc6JD4nKDx4qf744pTnniUrH7:VXsZ2cqVs2fcgwKuqM4Fi27`

## Runtime Data

### Usage (stdout):
```Batchfile
Description:  This tool's commands display the selected properties
of a specific object in the directory. The dsget commands:

dsget computer - displays properties of computers in the directory.
dsget contact - displays properties of contacts in the directory.
dsget subnet - displays properties of subnets in the directory.
dsget group - displays properties of groups in the directory.
dsget ou - displays properties of ou's in the directory.
dsget server - displays properties of servers in the directory.
dsget site - displays properties of sites in the directory.
dsget user - displays properties of users in the directory.
dsget quota - displays properties of quotas in the directory.
dsget partition - displays properties of partitions in the directory.

To display an arbitrary set of attributes of any given object in the
directory use the dsquery * command (see examples below).

For help on a specific command, type "dsget <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsget ou /?.

Remarks:
The dsget commands help you to view the properties of a specific object in
the directory: the input to dsget is an object and the output is a list of
properties for that object. To find all objects that meet a given search
criterion, use the dsquery commands (dsquery /?).

The dsget commands support piping of input to allow you to pipe results from
the dsquery commands as input to the dsget commands and display detailed
information on the objects found by the dsquery commands.

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").
Backslashes used in distinguished names must be escaped with a backslash (for
example, "CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,
DC=com").

Examples:
To find all users with names starting with "John" and display their office
numbers:

	dsquery user -name John* | dsget user -office

To display the sAMAccountName, userPrincipalName and department attributes of
the object whose DN is ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base -attr
	sAMAccountName userPrincipalName department

To read all attributes of any object use the dsquery * command.
For example, to read all attributes of the object whose DN is
ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base -attr *

Directory Service command-line tools help:
dsadd /? - help for adding objects.
dsget /? - help for displaying objects.
dsmod /? - help for modifying objects.
dsmove /? - help for moving objects.
dsquery /? - help for finding objects matching search criteria.
dsrm /? - help for deleting objects.
dsget succeeded

```

### Usage (stderr):
```Batchfile
Description:  This tool's commands display the selected properties
of a specific object in the directory. The dsget commands:

dsget computer - displays properties of computers in the directory.
dsget contact - displays properties of contacts in the directory.
dsget subnet - displays properties of subnets in the directory.
dsget group - displays properties of groups in the directory.
dsget ou - displays properties of ou's in the directory.
dsget server - displays properties of servers in the directory.
dsget site - displays properties of sites in the directory.
dsget user - displays properties of users in the directory.
dsget quota - displays properties of quotas in the directory.
dsget partition - displays properties of partitions in the directory.

To display an arbitrary set of attributes of any given object in the
directory use the dsquery * command (see examples below).

For help on a specific command, type "dsget <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsget ou /?.

Remarks:
The dsget commands help you to view the properties of a specific object in
the directory: the input to dsget is an object and the output is a list of
properties for that object. To find all objects that meet a given search
criterion, use the dsquery commands (dsquery /?).

The dsget commands support piping of input to allow you to pipe results from
the dsquery commands as input to the dsget commands and display detailed
information on the objects found by the dsquery commands.

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").
Backslashes used in distinguished names must be escaped with a backslash (for
example, "CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,
DC=com").

Examples:
To find all users with names starting with "John" and display their office
numbers:

	dsquery user -name John* | dsget user -office

To display the sAMAccountName, userPrincipalName and department attributes of
the object whose DN is ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base -attr
	sAMAccountName userPrincipalName department

To read all attributes of any object use the dsquery * command.
For example, to read all attributes of the object whose DN is
ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base -attr *

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
C:\Windows\SysWOW64\dsget.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsget.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


