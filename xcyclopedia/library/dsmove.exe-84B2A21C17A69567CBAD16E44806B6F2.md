---
title: dsmove.exe | Microsoft AD DS/LDS move command line utility.
---

# dsmove.exe 

* File Path: `C:\Windows\SysWOW64\dsmove.exe`
* Description: Microsoft AD DS/LDS move command line utility.

## Hashes

Type | Hash
-- | --
MD5 | `84B2A21C17A69567CBAD16E44806B6F2`
SHA1 | `E69A5306798199FFA0D50B03112856BA43782781`
SHA256 | `CBEEDFE71149343FEF2875C514BE9E4FB113E49431F4EA79DBDFEEAF091F8995`
SHA384 | `F0CCC2AA75616DD70C7004BD7D7970915996BE92D98EB558701F3A0C7BFE54B699FBFB119B63FA36A1DDAB3F6178CD89`
SHA512 | `A546438FA303B44C91C82A9782794802484B1CCEA3E331084E74565BDDC5CD2416633BB304DFE27C04C88A2293CFB1875DB4AC6FFF00BAAED0303F41DC172A0B`
SSDEEP | `384:wD0qM6tUW8+FVtcO0H1dc6I1SpyyhpNdTw6yOod56o+ZiyLw8h52o5EIW9LrWue:G0qMOUipcIOpnwPta2Pfk`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
dsmove failed:Value for 'Target object for this command' has incorrect format.
type dsmove /? for help.
```

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


