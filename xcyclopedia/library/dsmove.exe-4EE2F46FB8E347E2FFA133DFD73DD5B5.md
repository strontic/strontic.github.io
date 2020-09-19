---
title: dsmove.exe | Microsoft AD DS/LDS move command line utility.
---

# dsmove.exe 

* File Path: `C:\Windows\system32\dsmove.exe`
* Description: Microsoft AD DS/LDS move command line utility.

## Hashes

Type | Hash
-- | --
MD5 | `4EE2F46FB8E347E2FFA133DFD73DD5B5`
SHA1 | `CC0C9229BF5A8B7C3000E8DEC31F4DE9833DB711`
SHA256 | `9BDDE328F1837C2A2414882EC4CB6F2D08DBC87B9504EAC62C3704EF809AED2A`
SHA384 | `431CE0B983974708A10D38CD0BF4C871925DD71AB3E722861D8128900A1148B7F6859A4BAF0C150DAC3EFC37BE08D661`
SHA512 | `734EBA59AEAB6F75F0C8D7B37AAD390739578A269E6C2C7D2B000E7D482424C1C0DB872E0A6A0E32E66DE14E3B9527D4F5501C7C90F204AFEE58F84E3BB060BF`
SSDEEP | `768:h6zlMEklTAML2TTEfGwlYdksNHOllBwURZP5qX7u1bAf:oMTA+2T+GwlY97URZP5C7Nf`

## Runtime Data

### Usage (stdout):
```cmhg
Description:  This command moves or renames an object within the directory.

Syntax:     dsmove <ObjectDN>
                [-newparent <ParentDN>] 
                [-newname <NewName>]
                [{-s <Server> | -d <Domain>}] 
                [-u <UserName>] 
                [-p {<Password> | *}]
                [-q]
		[{-uc | -uco | -uci}]

Parameters:

Value                   Description
<ObjectDN>              Required/stdin. Distinguished name (DN) 
                        of object to move or rename.
                        If this parameter is omitted it
                        will be taken from standard input (stdin).
-newparent <ParentDN>   DN of the new parent location to which object
                        should be moved.
-newname <NewName>      New relative distinguished name (RDN) value
                        to which object should be renamed.
{-s <Server> | -d <Domain>}
                        -s <Server> connects to the AD DC/LDS instance
                        with name <Server>.
                        -d <Domain> connects to an AD DC in domain <Domain>.
                        Default: an AD DC in the logon domain.
-u <UserName>           Connect as <UserName>. Default: the logged in user.
                        User name can be: user name, domain\user name,
                        or user principal name (UPN).
-p <Password>           Password for the user <UserName>.
                        If * is used, then the command prompts for a
                        password.
-q                      Quiet mode: suppress all output to standard output.
{-uc | -uco | -uci}	-uc Specifies that input from or output to pipe is
			formatted in Unicode. 
			-uco Specifies that output to pipe or file is 
			formatted in Unicode. 
			-uci Specifies that input from pipe or file is
			formatted in Unicode.

Remarks:
If a value that you supply contains spaces, use quotation marks 
around the text (for example, "CN=John Smith,CN=Users,DC=microsoft,DC=com").

If you enter multiple values, the values must be separated by spaces
(for example, a list of distinguished names). 

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com").

Backslashes used in distinguished names must be escaped with a backslash
(for example,
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").

Examples:
The user object for the user Jane Doe can be renamed to Jane Jones
with the following command:

    dsmove "cn=Jane Doe,ou=sales,dc=microsoft,dc=com" -newname "Jane Jones"

The same user can be moved from the Sales organization to the Marketing
organization with the following command:

    dsmove "cn=Jane Doe,ou=sales,dc=microsoft,dc=com"
    -newparent ou=Marketing,dc=microsoft,dc=com

The rename and move operations for the user can be combined with the
following command:

    dsmove "cn=Jane Doe,ou=sales,dc=microsoft,dc=com"
    -newparent ou=Marketing,dc=microsoft,dc=com -newname "Jane Jones"

Directory Service command-line tools help:
dsadd /? - help for adding objects.
dsget /? - help for displaying objects.
dsmod /? - help for modifying objects.
dsmove /? - help for moving objects.
dsquery /? - help for finding objects matching search criteria.
dsrm /? - help for deleting objects.
dsmove succeeded

```

### Usage (stderr):
```cmhg
dsmove failed:Value for 'Target object for this command' has incorrect format.
type dsmove /? for help.
```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\dsmove.exe |
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

* Original Filename: dsmove.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


