---
title: logoff.exe | Session Logoff Utility
---

# logoff.exe 

* File Path: `C:\windows\SysWOW64\logoff.exe`
* Description: Session Logoff Utility

## Hashes

Type | Hash
-- | --
MD5 | `E66392FCCF58EC60E8D978CF49496A48`
SHA1 | `A7221A90E8C08F999C40BFB9606DABF1A2DE89AD`
SHA256 | `9C05D671E08BD2310204E4C4F1D2C6D4CF06378EF00D208EB96639B4B4B0E770`
SHA384 | `E81281EF9F93CC9F402330908583B3BF54767258A325FCDA09D833FE7DD42A2F1A0D60E623DED9FE2908918AD95EC2C0`
SHA512 | `443FA49ABF34445EDAAFADEEBEF833287726D960E6683D6E0E4B838228E317A2C9C038224DF54C24C7AC079E375CE8FDBD56E252277086B1F7CECD7C1F412FFD`
SSDEEP | `384:SZNKKtYAoCo9KW3AmJy4Ba0XzsDiWbG476W3CuW+jv:sNdYAofJG7muD`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logoff.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\SysWOW64\logoff.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: logoff.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


