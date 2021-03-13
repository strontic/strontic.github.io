---
title: eventcreate.exe | Event Create - Creates a custom event in an event log
excerpt: What is eventcreate.exe?
---

# eventcreate.exe 

* File Path: `C:\windows\system32\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log

## Hashes

Type | Hash
-- | --
MD5 | `E4B3425316E1B413523551E4CE50CF82`
SHA1 | `768A4BA253BB904A3C31C93E8F5A9487941E3FA6`
SHA256 | `95E14793FA57F97A8FC73F5860A070CDAE667546A7A04C82B2B3DBAE94D2DA0C`
SHA384 | `25C8818CADD6FE60536E841FB87EB4C914EE59C3956241DE8709B6817A0A8B427EF342B52666A8E4901C768812ABB5E6`
SHA512 | `1D9857EAAE9A075F21565461713B1B5ECB25C7FC466591F1560CE03F23D819075AE73AE8C36B3BB80DF47D6AAB980293FBB4A66F314D9C6F1C8622E965461277`
SSDEEP | `768:fYQZL2xNBX7CBM2sPO+gx5IJ2OP7bv07ZqyhHjIpHuY6I6xoMINw:fYQZgeBM2U6x5e/vOMHj6rxxINw`

## Signature

* Status: The file C:\windows\system32\eventcreate.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
eventcreate /t ERROR /id 100 /l application /d "Create event in application log"
eventcreate /t INFORMATION /id 1000 /d "Create event in WinMgmt source"
eventcreate /t ERROR /id 201 /so winword /l application /d "New src Winword in application log"
eventcreate /s server /t ERROR /id 100 /l application /d "Remote machine without user credentials"
eventcreate /s server /u user /p password /id 100 /t ERROR /l application /d "Remote machine with user credentials"
eventcreate /s server1 /s server2 /u user /p password /id 100 /t ERROR /d "Creating events on Multiple remote machines"
eventcreate /s server /u user /id 100 /t WARNING /d "Remote machine with partial user credentials"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


