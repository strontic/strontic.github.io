---
title: dsadd.exe | Microsoft AD DS/LDS creation command line utility
excerpt: What is dsadd.exe?
---

# dsadd.exe 

* File Path: `C:\Windows\system32\dsadd.exe`
* Description: Microsoft AD DS/LDS creation command line utility

## Hashes

Type | Hash
-- | --
MD5 | `8FFA75162D06B8477D7DCA5B086463CD`
SHA1 | `15B5C8CEEF47E6BB51CEE9F12CFEB5BE19E7CD10`
SHA256 | `AE5775937D69EF89B26CBCBBE3E991CEFD73EE82363405E8A99975C1DCA34459`
SHA384 | `B6B489CE8DED6AF3963498ED4E69A7394725D69D6E0113F214D05027A0924F82F86FD76E86AAAE3406F53F418560C7FB`
SHA512 | `153A1FE434F8C6AC1E342BE69B0FA63D05A741A22F19437EF2076564CCB66706889E24513EAF89650E910F11010550970ADF92DE9EE023491D962E2EABBC95EF`
SSDEEP | `1536:V/BdXUTUpbOFZMbmt62y1Zfm1Giuq8jMD:VrkTUpbJcy15m1Giuc`

## Runtime Data

### Usage (stdout):
```cmhg
Description:  This tool's commands add specific types of objects to the
directory. The dsadd commands:

dsadd computer - adds a computer to the directory.
dsadd contact - adds a contact to the directory.
dsadd group - adds a group to the directory.
dsadd ou - adds an organizational unit to the directory.
dsadd user - adds a user to the directory.
dsadd quota - adds a quota specification to a directory partition.

For help on a specific command, type "dsadd <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsadd ou /?.

Remarks:
Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").

Backslashes used in distinguished names must be escaped with a backslash
(for example,
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").

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
Description:  This tool's commands add specific types of objects to the
directory. The dsadd commands:

dsadd computer - adds a computer to the directory.
dsadd contact - adds a contact to the directory.
dsadd group - adds a group to the directory.
dsadd ou - adds an organizational unit to the directory.
dsadd user - adds a user to the directory.
dsadd quota - adds a quota specification to a directory partition.

For help on a specific command, type "dsadd <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsadd ou /?.

Remarks:
Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").

Backslashes used in distinguished names must be escaped with a backslash
(for example,
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").

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
C:\Windows\system32\dsadd.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsadd.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


