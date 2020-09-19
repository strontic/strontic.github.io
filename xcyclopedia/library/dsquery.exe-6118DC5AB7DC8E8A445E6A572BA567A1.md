---
title: dsquery.exe | Microsoft AD DS/LDS query command line utility
---

# dsquery.exe 

* File Path: `C:\Windows\system32\dsquery.exe`
* Description: Microsoft AD DS/LDS query command line utility

## Hashes

Type | Hash
-- | --
MD5 | `6118DC5AB7DC8E8A445E6A572BA567A1`
SHA1 | `C3295628152218E33586246913F17375956BEABC`
SHA256 | `1698A3CD79E3793E830C2190C46333D1A5DE7626577E1F31EC10462D9D003B39`
SHA384 | `F4EA650CF99899C95DE8092CEE169EF73F5EE46EFFC1A4EBC69D992DAEF756EDBADF237607EC481C52CE42E142EAD7E2`
SHA512 | `941C69B4AEEA8A7A7E98B2372A0F582F0224D142EA57641A88718ADF57126D5220BC56D6F1B1FFA849A53ACF64F3867F4790EF6230218C81CF2EF802017E523A`
SSDEEP | `1536:urUx5mbDtKLErGgDManxmpjpl12OIBdVkbEkgHh5ArSCy29:WUx5mbBbxuplYxS9gCSCyO`

## Runtime Data

### Usage (stdout):
```cmhg
Description: This tool's commands suite allow you to query the directory
according to specified criteria. Each of the following dsquery commands finds
objects of a specific object type, with the exception of dsquery *, which can
query for any type of object:

dsquery computer - finds computers in the directory.
dsquery contact - finds contacts in the directory.
dsquery subnet - finds subnets in the directory.
dsquery group - finds groups in the directory.
dsquery ou - finds organizational units in the directory.
dsquery site - finds sites in the directory.
dsquery server - finds AD DCs/LDS instances in the directory.
dsquery user - finds users in the directory.
dsquery quota - finds quota specifications in the directory.
dsquery partition - finds partitions in the directory.
dsquery * - finds any object in the directory by using a generic LDAP query.

For help on a specific command, type "dsquery <ObjectType> /?" where
<ObjectType> is one of the supported object types shown above.
For example, dsquery ou /?.

Remarks:
The dsquery commands help you find objects in the directory that match 
a specified search criterion: the input to dsquery is a search criterion 
and the output is a list of objects matching the search. To get the 
properties of a specific object, use the dsget commands (dsget /?).

The results from a dsquery command can be piped as input to one of the other
directory service command-line tools, such as dsmod, dsget, dsrm or dsmove.

Commas that are not used as separators in distinguished names must be
escaped with the backslash ("\") character
(for example, "CN=Company\, Inc.,CN=Users,DC=microsoft,DC=com"). 

Backslashes used in distinguished names must be escaped with a backslash 
(for example, 
"CN=Sales\\ Latin America,OU=Distribution Lists,DC=microsoft,DC=com").


Examples:
To find all computers that have been inactive for the last four weeks and
remove them from the directory:

	dsquery computer -inactive 4 | dsrm

To find all users in the organizational unit
"ou=Marketing,dc=microsoft,dc=com" and add them to the Marketing Staff group:

	dsquery user ou=Marketing,dc=microsoft,dc=com |	dsmod group
        "cn=Marketing Staff,ou=Marketing,dc=microsoft,dc=com" -addmbr

To find all users with names starting with "John" and display his office
number:

	dsquery user -name John* | dsget user -office

To display an arbitrary set of attributes of any given object in the
directory use the dsquery * command. For example, to display the
sAMAccountName, userPrincipalName and department attributes of the object
whose DN is ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base
	-attr sAMAccountName userPrincipalName department

To read all attributes of the object whose DN is ou=Test,dc=microsoft,dc=com:

	dsquery * ou=Test,dc=microsoft,dc=com -scope base -attr *

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
dsquery failed:The parameter is incorrect.:Incorrect object type specified.
type dsquery /? for help.
```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\dsquery.exe |
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

* Original Filename: dsquery.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `dsquery.exe` being misused. While `dsquery.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_dsquery_domain_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dsquery_domain_trust_discovery.yml) | `- Image\|endswith: '\dsquery.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- dsquery.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `description: Identifies execution of nltest.exe and dsquery.exe for domain trust discovery. This technique is used by attackers to enumerate Active Directory trusts.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `- Image\|endswith: '\dsquery.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


