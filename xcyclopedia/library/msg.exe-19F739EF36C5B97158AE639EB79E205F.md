﻿---
title: msg.exe | Message Utility
excerpt: What is msg.exe?
---

# msg.exe 

* File Path: `C:\Windows\system32\msg.exe`
* Description: Message Utility

## Hashes

Type | Hash
-- | --
MD5 | `19F739EF36C5B97158AE639EB79E205F`
SHA1 | `2550979706A69EE32622B30A8032C45CAD4755FB`
SHA256 | `9DBCA701E0A0F9CF7D98F5BC7A5E7D0C844F992EE4E2670F124F6344FA182E42`
SHA384 | `B4CAE34A447AD7712A48B16A6E8A9F2FB3BB201D64D0B46E9479A7CEA520C4D080EBF965A40F8370581B8623491F5870`
SHA512 | `D064CC88748D7E15AD0E4E3A586954106040070E5DAA9DE73D7B2A6F009FAB0CE3F9E597113C2FE88C9C39106CF982FC89662BA402BC9772848389022CCBDF48`
SSDEEP | `384:hd2EwJxreLEQQ8oo9Z0pWPouQmjeeEETz5TwOK8j7eACMivFYKVRfK9bIjLyW4UW:hUEwLrJQgoPEmoupae3yOK8WfvBV4ic`
IMP | `CD3B5466F111A79E4AC06248B98E0B04`
PESHA1 | `19A93009DCE54E5D03E6A4FB2E539520960F1600`
PE256 | `C0A042EEA8C8E4D5F0DE928DFDB36FBFEED9970F70F6F30FE3F182A97DADF694`

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

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\msg.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\msg.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/9dbca701e0a0f9cf7d98f5bc7a5e7d0c844f992ee4e2670f124f6344fa182e42/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\msg.exe](msg.exe-E70EB0CFABC4927A3A40E8738E173711.md) | 85


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## msg

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


