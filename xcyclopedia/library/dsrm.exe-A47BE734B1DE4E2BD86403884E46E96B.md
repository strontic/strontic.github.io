---
title: dsrm.exe | Microsoft AD DS/LDS deletion command line utility
---

# dsrm.exe 

* File Path: `C:\Windows\SysWOW64\dsrm.exe`
* Description: Microsoft AD DS/LDS deletion command line utility

## Hashes

Type | Hash
-- | --
MD5 | `A47BE734B1DE4E2BD86403884E46E96B`
SHA1 | `07642FF6B796D72911A2C30513326C0AEE99C751`
SHA256 | `F9F811DBD19372D3FD2C64ADAEB97DDC33F37B747BA6222E9D57E611CE59C4D8`
SHA384 | `8561821A6AAA8F0381AEA14EB429A22B2BDF6A6E1EF2B6CC24F5F8421DF7DFE9E5EB6D2AAAB0633F8B075BB21CC1CA15`
SHA512 | `420E695A1C436276EBBE80FEFE9CF91F010CF4BBBD8C9C5F568454529E05D290DA0ADFB3BA2C21FC437C83F092B71D9BFE17E1E13695B4AF494B6B4DB6C9B5EF`
SSDEEP | `768:Lp8X6Xz8XvdvGpgBjNO4eV3SI6RLlFV2e+Os:18G8Qg1MHVCIGHse+p`

## Runtime Data

### Usage (stdout):
```cmhg
Description: This command deletes objects from the directory.

Syntax:     dsrm <ObjectDN ...> [-noprompt] [-subtree [-exclude]]
            [{-s <Server> | -d <Domain>}] [-u <UserName>]
            [-p {<Password> | *}] [-c] [-q] [{-uc | -uco | -uci}]

Parameters:

Value               Description
<ObjectDN ...>      Required/stdin. List of one or more 
                    distinguished names (DNs) of objects to delete.
                    If this parameter is omitted it is
                    taken from standard input (stdin).
-noprompt           Silent mode: do not prompt for delete confirmation.
-subtree [-exclude] Delete object and all objects in the subtree under it.
                    -exclude excludes the object itself
                    when deleting its subtree.
{-s <Server> | -d <Domain>}
                    -s <Server> connects to the AD DC/LDS instance with
                    name <Server>.
                    -d <Domain> connects to an AD DC in domain <Domain>.
                    Default: an AD DC in the logon domain.
-u <UserName>       Connect as <UserName>. Default: the logged in user.
                    User name can be: user name, domain\user name,
                    or user principal name (UPN).
-p {<Password> | *} Password for the user <UserName>. If * is used,
                    then the command prompts you for the password.
-c                  Continuous operation mode: report errors but continue
                    with next object in argument list when multiple
                    target objects are specified.
		    Without this option, command exits on first error.
-q                  Quiet mode: suppress all output to standard output.
{-uc | -uco | -uci} -uc 
					Specifies that input from or output to pipe is
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
To remove an organizational unit (OU) called "Marketing" and all the objects
under that OU, use the following command:

dsrm -subtree -noprompt -c ou=Marketing,dc=microsoft,dc=com

To remove all objects under the OU called "Marketing" but leave
the OU intact, use the following command with the -exclude parameter:

dsrm -subtree -exclude -noprompt -c "ou=Marketing,dc=microsoft,dc=com"

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
dsrm failed:Value for 'Target object for this command' has incorrect format.
type dsrm /? for help.
```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\dsrm.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


