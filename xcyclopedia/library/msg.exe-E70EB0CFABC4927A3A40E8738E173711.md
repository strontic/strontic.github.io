---
title: msg.exe | Message Utility
excerpt: What is msg.exe?
---

# msg.exe 

* File Path: `C:\WINDOWS\system32\msg.exe`
* Description: Message Utility

## Hashes

Type | Hash
-- | --
MD5 | `E70EB0CFABC4927A3A40E8738E173711`
SHA1 | `477C9AF2ED50133A5458242B9F3D233A126832F8`
SHA256 | `0157BD32C17BEDADEDD95C1FE59A33D0201F1C77422B40C05F2A81A5FF503F4F`
SHA384 | `BD39327C6B4E9649B34F79F7AC9920CB6FA0A5DEE8C9C5A86B6591B4D703C1901EA3E2259EC769748F30AD7366FC9E6D`
SHA512 | `8E2961176A05F3A612F42A1863D778F22C05D74C26FE7B16ECA72D571EC25A265BDDD4745B59479339CC9BE30CD932E019F4C2F1E180C2C13C5644AE03CDF13C`
SSDEEP | `384:zd2EwJxreLEQQ8oo9Z0pWPouQmjeeEETz5TwOK8j75ACMivFysnfK8TbIGSWeUW:zUEwLrJQgoPEmoupae3yOK8xfvUIy`

## Runtime Data

### Usage (stdout):
```cmhg
Send a message to a user.

MSG {username | sessionname | sessionid | @filename | *}
    [/SERVER:servername] [/TIME:seconds] [/V] [/W] [message]

  username            Identifies the specified username.
  sessionname         The name of the session.
  sessionid           The ID of the session.
  @filename           Identifies a file containing a list of usernames,
                      sessionnames, and sessionids to send the message to.
  *                   Send message to all sessions on specified server.
  /SERVER:servername  server to contact (default is current).
  /TIME:seconds       Time delay to wait for receiver to acknowledge msg.
  /V                  Display information about actions being performed.
  /W                  Wait for response from user, useful with /V.
  message             Message to send.  If none specified, prompts for it
                      or reads from stdin.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Send a message to a user.

MSG {username | sessionname | sessionid | @filename | *}
    [/SERVER:servername] [/TIME:seconds] [/V] [/W] [message]

  username            Identifies the specified username.
  sessionname         The name of the session.
  sessionid           The ID of the session.
  @filename           Identifies a file containing a list of usernames,
                      sessionnames, and sessionids to send the message to.
  *                   Send message to all sessions on specified server.
  /SERVER:servername  server to contact (default is current).
  /TIME:seconds       Time delay to wait for receiver to acknowledge msg.
  /V                  Display information about actions being performed.
  /W                  Wait for response from user, useful with /V.
  message             Message to send.  If none specified, prompts for it
                      or reads from stdin.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msg.exe](msg.exe-19F739EF36C5B97158AE639EB79E205F.md) | 85


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



MIT License. Copyright (c) 2020-2021 Strontic.


