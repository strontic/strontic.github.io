---
title: eventcreate.exe | Event Create - Creates a custom event in an event log
---

# eventcreate.exe 

* File Path: `C:\windows\SysWOW64\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log

## Hashes

Type | Hash
-- | --
MD5 | `30463A5EA5BB6D0F8F3EB43F496DF2F3`
SHA1 | `E147EAE8ADA2F8F5B6615B5B9BC4A12CF887609A`
SHA256 | `8C7AD7303B8E4ADDAFC174B46EE951FC063DB116DEB7ABFB6AEEBF733B84D87C`
SHA384 | `3278C7CA6DD762B10D28786B0C37FE69525D62E606A417AE1A242AD2D8F7121E18F3AA8012E7238D5B3FAB9E349B5201`
SHA512 | `F68EFB300A03D40F7CE5D1E6F9047673A64BBC3E712EAECF5780E8ECBB43CED2C90F0BE9313A0D86DDD940D0D8F4245E0AD867313FDD3E32AED269E31B0C58FD`
SSDEEP | `768:dYgC1IJDS8nn+18w2FKAws02VUMJgIAI/SSYMhxYxWI2ANwX:dYgCGDvnBf+2tJffYkxYxYANwX`

## Signature

* Status: The file C:\windows\SysWOW64\eventcreate.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: evcreate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## eventcreate

Enables an administrator to create a custom event in a specified event log.

> [!IMPORTANT]
> Custom events can't be written to the security log.

### Syntax

```
eventcreate [/s <computer> [/u <domain\user> [/p <password>]] {[/l {APPLICATION|SYSTEM}]|[/so <srcname>]} /t {ERROR|WARNING|INFORMATION|SUCCESSAUDIT|FAILUREAUDIT} /id <eventID> /d <description>
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain\user>` | Runs the command with the account permissions of the user specified by `<user>` or `<domain\user>`. The default is the permissions of the current logged on user on the computer issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /l `{APPLICATION | SYSTEM}` | Specifies the name of the event log where the event will be created. The valid log names are **APPLICATION** or **SYSTEM**. |
| /so `<srcname>` | Specifies the source to use for the event. A valid source can be any string and should represent the application or component that is generating the event. |
| /t `{ERROR | WARNING | INFORMATION | SUCCESSAUDIT | FAILUREAUDIT}` | Specifies the type of event to create. The valid types are **ERROR**, **WARNING**, **INFORMATION**, **SUCCESSAUDIT**, and **FAILUREAUDIT**. |
| /id `<eventID>` | Specifies the event ID for the event. A valid ID is any number from 1 to 1000. |
| /d `<description>` | Specifies the description to use for the newly created event. |
| /? | Displays help at the command prompt. |

#### Examples

The following examples show how you can use the **eventcreate** command:

```
eventcreate /t error /id 100 /l application /d Create event in application log
eventcreate /t information /id 1000 /so winmgmt /d Create event in WinMgmt source
eventcreate /t error /id 2001 /so winword /l application /d new src Winword in application log
eventcreate /s server /t error /id 100 /l application /d Remote machine without user credentials
eventcreate /s server /u user /p password /id 100 /t error /l application /d Remote machine with user credentials
eventcreate /s server1 /s server2 /u user /p password /id 100 /t error /so winmgmt /d Creating events on Multiple remote machines
eventcreate /s server /u user /id 100 /t warning /so winmgmt /d Remote machine with partial user credentials
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


