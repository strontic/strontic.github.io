---
title: dsget.exe | Microsoft AD DS/LDS Get command line utility
---

# dsget.exe 

* File Path: `C:\Windows\system32\dsget.exe`
* Description: Microsoft AD DS/LDS Get command line utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `10E981C5FEE18D004726634FA650A18D`
SHA1 | `285CB7E14C780F73BA683D19FEA3AC7E8B96A1C2`
SHA256 | `CD1EE46AE4B0C48617C99DC8B041A9586173B95560F1A1352F47BB9C9C7F90DC`
SHA384 | `FD5E6518063290544DD2BD0B06ADBC98007864575B2F05960AF96040B1BF828ABDEF5A4C8F0E52ACF9297A22D71595F1`
SHA512 | `D12651199F0F22EB9990256E8FB7F1519B3EFDF11B89FC320DA861F7016CED7652EE93A0B399227FA7398BF61F1ABA18223D5F54DA949F3561BFB8364E564F31`
SSDEEP | `1536:1FX4sGI2Q5eaNim1sRVOCjigtii8CaCD8ZksSM7RX3joPk/gG/3n:1FX4sneaNtsTLti3CDGSAX3qqgA`

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

### Child Processes:


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


