---
title: getmac.exe | Displays NIC MAC information
excerpt: What is getmac.exe?
---

# getmac.exe 

* File Path: `C:\windows\SysWOW64\getmac.exe`
* Description: Displays NIC MAC information

## Hashes

Type | Hash
-- | --
MD5 | `E6215EE9BD1542B1DA1E229761CEF879`
SHA1 | `560F138B8BDD901D9D394B16F0F619ABB8D4D1B2`
SHA256 | `13F2B062BE907D963D749F42C82A619351F1B6167F5F7E62F1E89FFA31D39B7C`
SHA384 | `58F75880359BECAAB93AB7CAA0636D10EB81FEE82460102CD25EB1A966C1F4058E46E9989907948B2FB8F087CF6590E8`
SHA512 | `497EEF37581545C0064390A238B3E8E32121D810174E8728CDBA666E27E9CA23F38CFC9629F5C52551A1DEC3D1BE9B1A62425055AD7755ABE13C560A36AA737E`
SSDEEP | `1536:Lm4azG+YFB+ve/U94vV+j5OyNyt7p+LdzNzpw6xC1d3:LlB+vezV+327p+Lbpw6xC`

## Signature

* Status: The file C:\windows\SysWOW64\getmac.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: GetMac.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## getmac

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Returns the media access control (MAC) address and list of network protocols associated with each address for all network cards in each computer, either locally or across a network. This command is particularly useful either when you want to enter the MAC address into a network analyzer, or when you need to know what protocols are currently in use on each network adapter on a computer.

### Syntax

```
getmac[.exe][/s <computer> [/u <domain\<user> [/p <password>]]][/fo {table | list | csv}][/nh][/v]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain>\<user>` | Runs the command with the account permissions of the user specified by *user* or *domain\user*. The default is the permissions of the current logged on user on the computer issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /fo {table \| list \| csv} | Specifies the format to use for the query output. Valid values are **table**, **list**, and **csv**. The default format for output is **table**. |
| /nh | Suppresses column header in output. Valid when the **/fo** parameter is set to **table** or **csv**. |
| /v | Specifies that the output display verbose information. |
| /? | Displays help at the command prompt. |

#### Examples

The following examples show how you can use the **getmac** command:

```
getmac /fo table /nh /v
```

```
getmac /s srvmain
```

```
getmac /s srvmain /u maindom\hiropln
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23 /fo list /v
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23 /fo table /nh
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


