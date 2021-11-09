---
title: logoff.exe | Session Logoff Utility
excerpt: What is logoff.exe?
---

# logoff.exe 

* File Path: `C:\WINDOWS\system32\logoff.exe`
* Description: Session Logoff Utility

## Hashes

Type | Hash
-- | --
MD5 | `FE5DD4FD361069AF182D6B8E3A4DE7A3`
SHA1 | `1FEAB299D9C494BA3C2FDE6AF2359A838BE9126C`
SHA256 | `32362C85BA2F3389A9CF950123720FC8CFE46926A375A56AECB0DDD3AF9AEEF6`
SHA384 | `EF5A91144C25E9093BF5771FAD8C797F12596A726CA07F08D5284ABBC2771B753C199E9427961727C0F35A99C343E2C7`
SHA512 | `08BA045CD60C970DAD8ACAF4BC2AF04662B90125811D587A38248FFDF04AD1181C91DE5AE1D1256C997759DC63673D58100AC32D3B2D6AAE7B8C471EDF651FB1`
SSDEEP | `384:u6DJjsCiyQUVxMkMLUHOAvZ+1frJay0+NvgR6Z5YIJSyz0mTzvhJZNWP1eOqW3b3:u6DuaQUVxZMeYRJaD6vCiuIB0mTO8On`
IMP | `5DEE48EC7C50D677FA5BFE4D23399111`
PESHA1 | `B59DA047F8B4F7C64800F8580EC4F943065B89D6`
PE256 | `6B97351F446B32DC82D2FAAD251DE247724F32187A15A9B3CCA5D4A10A220ECB`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\logoff.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logoff.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/32362c85ba2f3389a9cf950123720fc8cfe46926a375a56aecb0ddd3af9aeef6/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## logoff

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


