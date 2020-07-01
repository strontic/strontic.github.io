---
title: msg.exe | Message Utility
---

# msg.exe 

* File Path: `C:\windows\SysWOW64\msg.exe`
* Description: Message Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FE0EB81511453BCA1D52ACDD17F4F0CD`
SHA1 | `BB5F310784C4728959F336CFA562DCBFBD05D425`
SHA256 | `6FE1FF95B3C6AB578445BF126EC2BC7EB0B5244D2F27C6E443AC9A645FC23152`
SHA384 | `D6FFEB53360F8A0F4019E80CA8D7BD33E2036BE57EB7C90F4CDDBBA1564097391D22E1095A2B1D4F36C3C8008EFEECE8`
SHA512 | `88D6955BDFBAAAEBDA084E4701E55E0636E5B5FA2C02E3BDDD5D925B0F3929EB25049F7504F8E247BFB4D8F238F1058615788464E7BAB9C1E7C5BE4E4FC1DA6B`
SSDEEP | `384:nXjTTPZKC5OSwd9IPAp/Gr2bVuuacXLg6vALmwRwbyWhUWO61:X/4C5O3cqPoU1H`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\msg.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: msg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## msg

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Sends a message to a user on a Remote Desktop Session Host server.

> [!NOTE]
> You must have Message special access permission to send a message.

### Syntax

```
msg {<username> | <sessionname> | <sessionID>| @<filename> | *} [/server:<servername>] [/time:<seconds>] [/v] [/w] [<message>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<username>` | Specifies the name of the user that you want to receive the message. If you don't specify a user or a session, this command displays an error message. When specifying a session, it must be an active one. |
| `<sessionname>` | Specifies the name of the session that you want to receive the message. If you don't specify a user or a session, this command displays an error message. When specifying a session, it must be an active one. |
| `<sessionID>` | Specifies the numeric ID of the session whose user you want to receive a message. |
| `@<filename>` | Identifies a file containing a list of user names, session names, and session IDs that you want to receive the message. |
| * | Sends the message to all user names on the system. |
| /server:`<servername>` | Specifies the Remote Desktop Session Host server whose session or user you want to receive the message. If unspecified, **/server** uses the server to which you are currently logged on. |
| /time:`<seconds>` | Specifies the amount of time that the message you sent is displayed on the user's screen. After the time limit is reached, the message disappears. If no time limit is set, the message remains on the user's screen until the user sees the message and clicks **OK**. |
| /v | Displays information about the actions being performed. |
| /w | Waits for an acknowledgment from the user that the message has been received. Use this parameter with `/time:<*seconds*>` to avoid a possible long delay if the user does not immediately respond. Using this parameter with **/v** is also helpful. |
| `<message>` | Specifies the text of the message that you want to send. If no message is specified, you will be prompted to enter a message. To send a message that is contained in a file, type the less than (<) symbol followed by the file name. |
| /? | Displays help at the command prompt. |

#### Examples

To send a message entitled, *Let's meet at 1PM today* to all sessions for *User1*, type:

```
msg User1 Let's meet at 1PM today
```

To send the same message to session *modeM02*, type:

```
msg modem02 Let's meet at 1PM today
```

To send the message to all sessions contained in the file *userlist*, type:

```
msg @userlist Let's meet at 1PM today
```

To send the message to all users who are logged on, type:

```
msg * Let's meet at 1PM today
```

To send the message to all users, with an acknowledgment time-out (for example, 10 seconds), type:

```
msg * /time:10 Let's meet at 1PM today
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


