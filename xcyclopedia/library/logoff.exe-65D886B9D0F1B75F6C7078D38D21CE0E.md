---
title: logoff.exe | Session Logoff Utility
excerpt: What is logoff.exe?
---

# logoff.exe 

* File Path: `C:\Windows\SysWOW64\logoff.exe`
* Description: Session Logoff Utility

## Hashes

Type | Hash
-- | --
MD5 | `65D886B9D0F1B75F6C7078D38D21CE0E`
SHA1 | `7A7381D1F2ED4429861B0271DB7020A2941C609E`
SHA256 | `0069EF09C0FA4113DD6E4EB62361382F1745D8A5FB9C68D45E2F03378275BF44`
SHA384 | `509C513A08DB128E63702638AEF868962C831155A93D2FA29A68B47DDFC7A481EF58B36BF7F6C08360BD3E85AEABB7BE`
SHA512 | `1D66D632B6A50A8C50201CD0A15960D93DEA4B92A592367C19C1DD74D521FFE733C4EF67625B18165C6384B9F4F1106962879033EB4573FEBF69B56D6883CA22`
SSDEEP | `384:lkIqdNQ+ltuY9i0gb/qm9rPacXFqwe+Tf/nE8kKW37uWeC99gn:lkImNQ+nz+/NdqeknuCIn`

## Runtime Data

### Usage (stderr):
```cmhg
Invalid parameter(s)
Terminates a session.

LOGOFF [sessionname | sessionid] [/SERVER:servername] [/V] [/VM]

  sessionname         The name of the session.
  sessionid           The ID of the session.
  /SERVER:servername  Specifies the Remote Desktop server containing the user
                      session to log off (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Logs off a session on server or within virtual machine. The unique ID of the session needs to be specified.


```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logoff.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## logoff

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Logs off a user from a session on a Remote Desktop Session Host server and deletes the session.

### Syntax
```
logoff [<sessionname> | <sessionID>] [/server:<servername>] [/v]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<sessionname>` | Specifies the name of the session. This must be an active session.|
| `<sessionID>` | Specifies the numeric ID which identifies the session to the server. |
| /server:`<servername>` | Specifies the Remote Desktop Session Host server that contains the session whose user you want to log off. If unspecified, the server on which you are currently active is used. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- You can always log off yourself from the session to which you are currently logged on. You must, however, have **Full Control** permission to log off users from other sessions.

- Logging off a user from a session without warning can result in loss of data at the user's session. You should send a message to the user by using the **msg** command to warn the user before taking this action.

- If `<sessionID>` or `<sessionname>` isn't specified, **logoff** logs the user off from the current session.

- After you log off a user, all processes end and the session is deleted from the server.

- You can't log off a user from the console session.

#### Examples

To log off a user from the current session, type:

```
logoff
```

To log off a user from a session by using the session's ID, for example *session 12*, type:

```
logoff 12
```

To log off a user from a session by using the name of the session and server, for example session *TERM04* on *Server1*, type:

```
logoff TERM04 /server:Server1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


