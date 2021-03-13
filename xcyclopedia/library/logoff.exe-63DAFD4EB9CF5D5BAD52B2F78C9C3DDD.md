---
title: logoff.exe | Session Logoff Utility
excerpt: What is logoff.exe?
---

# logoff.exe 

* File Path: `C:\Windows\system32\logoff.exe`
* Description: Session Logoff Utility

## Hashes

Type | Hash
-- | --
MD5 | `63DAFD4EB9CF5D5BAD52B2F78C9C3DDD`
SHA1 | `54128FE2F1E8E2E325F73000E78D321A6C84D1DE`
SHA256 | `EC35AEEDEDEAD912B65247BEBF6B87D010182ACA99EA78B6EE2D80BD267FBD40`
SHA384 | `5D424FD643753FA6842994CB9B601E43F9C7F0FC6561368D89BB9EA390B7926468C8BCB9B082D311FEF8FFD878C04320`
SHA512 | `782724E112FBF327DD170957819C329B9E2A63CA2FC828ACD76337A23E8C4CB288AF8E0D9C92A0E93D73DC85D58BBF1B4EEC7AF7D8F8FF3C996CFC7EB80A8617`
SSDEEP | `384:jrh2V3nRO3qQRC9QgstQrldEg55M2ID2/GFtR+nzn5mocyGMrUvbzCW37uW:jrhEYdLaRlmh3Qz5mxvbz/`

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


