---
title: logoff.exe | Session Logoff Utility
---

# logoff.exe 

* File Path: `C:\Windows\system32\logoff.exe`
* Description: Session Logoff Utility

## Hashes

Type | Hash
-- | --
MD5 | `8D2514979820B970A4E4E7D5CF93DE28`
SHA1 | `04D171619689103D1E3C946A462E4D4BB5A765A6`
SHA256 | `A8801F55523961A7DC8B38CBF48FBC1E46AE8E993E09153A240AC8F996C3A46F`
SHA384 | `3199DDDAA55A88E0F7B84DA47F91B8912595D72CF0D06CAA1E3F11EDBAB03662E95F232288348501183DBA9FE01D3FBE`
SHA512 | `9312835DA78C5BBBDA7AB1FE92AC2015047EF2450F2DDC94B1EBE96F1096963670C4A2F00E0C95165ED421520468081ED3842F50D49E4F931B0C0C82A7A58D4A`
SSDEEP | `384:43i4l2W1q3dkKm7E57ECz5z4FK8u2k49uEmqJrrXfWjMcZexKW3PuW:43JsCsdk7o5fSFK8nk4nmeiwxj`

## Runtime Data

### Usage (stderr):
```Batchfile
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

* Original Filename: logoff.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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



MIT License. Copyright (c) 2020 Strontic.


