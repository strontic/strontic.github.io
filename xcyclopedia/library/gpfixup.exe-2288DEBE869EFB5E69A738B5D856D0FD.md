---
title: gpfixup.exe | NT5DS
excerpt: What is gpfixup.exe?
---

# gpfixup.exe 

* File Path: `C:\Windows\SysWOW64\gpfixup.exe`
* Description: NT5DS

## Hashes

Type | Hash
-- | --
MD5 | `2288DEBE869EFB5E69A738B5D856D0FD`
SHA1 | `E1BD3A9960D738E990014373965730124CD7FA3D`
SHA256 | `5B030186EC1C03DE8195BBFA242E80EFA13D14A563BC41EEBF2FC522E8B36977`
SHA384 | `31E9257D53E1303DA018325FC2F8679676E9856B0730091D4EAA903DED92C4E2654D79C5744448FC903889889515EB6B`
SHA512 | `9540694878B5773267342B0D94C30D37A5CB32CA7512064F6D59EB44134C108695A70B9F543FD25395084618E227FE2CAAE0E6E558AC80A067D4D2A343813B2E`
SSDEEP | `768:12HHfwr7ddgZbKclD7ef3F8mtGyjb54YPiruIbvR:12H/wrG5K8u26Ibv`

## Runtime Data

### Usage (stdout):
```cmhg
Group Policy fix up utility Version 1.1 (Microsoft)

gpfixup: fix up domain name dependencies in group policy objects 
	and group policy links after a domain rename operation
 
Usage: gpfixup [/?] [/v] 
	[/olddns:OLDDNSNAME [/newdns:NEWDNSNAME]] 
	[/oldnb:OLDFLATNAME [/newnb:NEWFLATNAME]] 
	[/dc:DCNAME] [/sionly] [/user:USERNAME] [/pwd:{PASSWORD|*}]
 
/?	Display this help syntax for the command
 
/v	Verbose mode
 
/olddns:OLDDNSNAME 
	Old DNS name of renamed domain is OLDDNSNAME if the 
	domain DNS name changed
 
/newdns:NEWDNSNAME 
	New DNS name of renamed domain is NEWDNSNAME if the 
	domain DNS name changed
 
/oldnb:OLDFLATNAME 
	Old NetBIOS name of renamed domain is OLDFLATNAME 
	if the domain NETBIOS name changed
 
/newnb:NEWFLATNAME 
	New NetBIOS name of renamed domain is NEWFLATNAME 
	if the domain NetBIOS named changed
 
/dc:DCNAME Connect to the DC with DCNAME [Default: connect 
	to a DC in the renamed domain given by NEWDNSNAME or 
	NEWFLATNAME]
 
/sionly Perform only the group policy fix up relating to 
	managed software installation
 
/user:USERNAME Connect as USERNAME [Default: the logged in user]
 
/pwd:{PASSWORD | *} 
	Password for the user USERNAME; if * is specified 
	instead of a password then prompt for password


```

### Usage (stderr):
```cmhg
Invalid parameter.

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

* Original Filename: gpfixup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## gpfixup

Fixes domain name dependencies in Group Policy Objects and Group Policy links after a domain rename operation. To use this command, you must install Group Policy Management as a feature through Server Manager.

### Syntax

```
gpfixup [/v]
[/olddns:<olddnsname> /newdns:<newdnsname>]
[/oldnb:<oldflatname> /newnb:<newflatname>]
[/dc:<dcname>] [/sionly]
[/user:<username> [/pwd:{<password>|*}]] [/?]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /v | Displays detailed status messages. If this parameter isn't used, only error messages or a summary status message stating, **SUCCESS** or **FAILURE** appears. |
| /olddns:`<olddnsname>` | Specifies the old DNS name of the renamed domain as `<olddnsname>` when the domain rename operation changes the DNS name of a domain. You can use this parameter only if you also use the **/newdns** parameter to specify a new domain DNS name. |
| /newdns:`<newdnsname>` | Specifies the new DNS name of the renamed domain as `<newdnsname>` when the domain rename operation changes the DNS name of a domain. You can use this parameter only if you also use the **/olddns** parameter to specify the old domain DNS name. |
| /oldnb:`<oldflatname>` | Specifies the old NetBIOS name of the renamed domain as `<oldflatname>` when the domain rename operation changes the NetBIOS name of a domain. You can use this parameter only if you use the **/newnb** parameter to specify a new domain NetBIOS name. |
| /newnb:`<newflatname>` | Specifies the new NetBIOS name of the renamed domain as `<newflatname>` when the domain rename operation changes the NetBIOS name of a domain. You can use this parameter only if you use the **/oldnb** parameter to specify the old domain NetBIOS name. |
| /dc:`<dcname>` | Connect to the domain controller named `<dcname>` (a DNS name or a NetBIOS name). `<dcname>` must host a writable replica of the domain directory partition as indicated by one of the following:<ul><li>The DNS name `<newdnsname>` by using **/newdns**</li><li>The NetBIOS name `<newflatname>` by using **/newnb**</br>If this parameter isn't used, you can connect to any domain controller in the renamed domain indicated by `<newdnsname>` or `<newflatname>`.</li></ul> |
| /sionly | Performs only the Group Policy fix that relates to managed software installation (the Software Installation extension for Group Policy). Skip the actions that fix Group Policy links and the SYSVOL paths in GPOs. |
| /user:`<username>` |Runs this command in the security context of the user `<username>`, where `<username>` is in the format domain\user. If this parameter isn't used, this command runs as the logged in user. |
| /pwd:`{<password> | *}` | Specifies the password for the user. |
| /? | Displays Help at the command prompt. |

#### Examples

This example assumes that you have already performed a domain rename operation in which you changed the DNS name from **MyOldDnsName** to **MyNewDnsName**, and the NetBIOS name from **MyOldNetBIOSName** to **MyNewNetBIOSName**.

In this example, you use the **gpfixup** command to connect to the domain controller named **MyDcDnsName** and repair GPOs and Group Policy links by updating the old domain name embedded in the GPOs and links. Status and error output is saved to a file that is named **gpfixup.log**.

```
gpfixup /olddns: MyOldDnsName /newdns:MyNewDnsName /oldnb:MyOldNetBIOSName /newnb:MyNewNetBIOSName /dc:MyDcDnsName 2>&1 >gpfixup.log
```

This example is the same as the previous one, except that it assumes the NetBIOS name of the domain was not changed during the domain rename operation.

```
gpfixup /olddns: MyOldDnsName /newdns:MyNewDnsName /dc:MyDcDnsName 2>&1 >gpfixup.log
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Administering Active Directory Domain Rename](/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc794869(v=ws.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


