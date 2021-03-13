---
title: dsrm.exe | Microsoft AD DS/LDS deletion command line utility
excerpt: What is dsrm.exe?
---

# dsrm.exe 

* File Path: `C:\Windows\system32\dsrm.exe`
* Description: Microsoft AD DS/LDS deletion command line utility

## Hashes

Type | Hash
-- | --
MD5 | `6398E312D516556CC0D86F3B37DAA3D2`
SHA1 | `CC08334A2CE2F99D808B63E197979285913C9FE9`
SHA256 | `D0B1577512D1F1023221BCA12EE221624255C843D35C0D5D21941F76C3F36231`
SHA384 | `3A86EAD4DB552FE2DD5CD9FFD34AC7A4E117C779558FD00D6D55CBB390F61E63EF0D2F3458C42387DF7DE0CFFA1F8BAA`
SHA512 | `D3FAF54D644937BB9FEF8F18ACE70F539321E532FEA2C6118AF9344DA3255E7BFC6D85936541F7BB9DC6906A4D2A1A67AE834677E0195B583D0F78C80D80389D`
SSDEEP | `768:SYqvkGBUTyCb+TrH6xYh0W1VshOYT789hZnz1bSYG:tJ+iyAQH6+h0Wko9vnzG`

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
C:\Windows\system32\dsrm.exe |
C:\Windows\SYSTEM32\ntdll.dll |


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






MIT License. Copyright (c) 2020-2021 Strontic.


