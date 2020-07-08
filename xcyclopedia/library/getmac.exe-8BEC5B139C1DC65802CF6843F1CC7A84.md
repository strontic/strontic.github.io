---
title: getmac.exe | Displays NIC MAC information
---

# getmac.exe 

* File Path: `C:\windows\system32\getmac.exe`
* Description: Displays NIC MAC information

## Hashes

Type | Hash
-- | --
MD5 | `8BEC5B139C1DC65802CF6843F1CC7A84`
SHA1 | `AD5DDA2CA9BD948AA175E838BEC96D9DC8834EA7`
SHA256 | `10A496C92DFDCE13697E15C47E2A9AC0C3F04121DFBEFDBF7F5067292446E186`
SHA384 | `7F0E7FDE02CD2D039E27F6E29FDE8F9F3B2FE2312235C0BBB647B909C651A5DF05CB48A99EE45D0F0F0E1ED2E2906667`
SHA512 | `E154783682855D9470E61661712D5F914EE4EB61A1809ECAE20EF1079F0E75D98A02C9AA94DA7EE27A35AA3D3A3B04AB89F9970A0725BBD3140F7FB080C03DC7`
SSDEEP | `1536:14azInSl7NeGHN+I1LQNrLiTvwvwMHK9AuZ0ozuOU3xXKFE1yd/q2EdExClp:EnG0G/mLav4KKuZ0uup3xXK+1ydRwExA`

## Signature

* Status: The file C:\windows\system32\getmac.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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
| /fo {table | list | csv} | Specifies the format to use for the query output. Valid values are **table**, **list**, and **csv**. The default format for output is **table**. |
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



MIT License. Copyright (c) 2020 Strontic.


