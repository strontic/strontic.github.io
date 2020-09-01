---
title: quser.exe | Query User Utility
---

# quser.exe 

* File Path: `C:\Windows\SysWOW64\quser.exe`
* Description: Query User Utility

## Hashes

Type | Hash
-- | --
MD5 | `F62DB52805E9F7016F529565D99EF3C9`
SHA1 | `C842F013741901BCC4E15EDF2FFCA5E262D8C01B`
SHA256 | `EAE530A0D5CD045A90BBE6E12839AEC0383486CCDAAC07102D50250F381A2309`
SHA384 | `230F599CE7A04A4600AA4AF9881709A523A206EAE7F94308E879D955A66DFCF01750325433EC8B2CD0BA33D678EA6BFF`
SHA512 | `3B199C0F4766323BB4D11BB9A510B0B132F5129A0EF25811E4DF9544792D5622255F74C8FD515F9170C54EBF8E629CB29E0A8CB513AAD6C6968749601BE6001A`
SSDEEP | `384:Hu4v05f4EIE9aXi/aoqaEXR63o8RzgGDETULPWS3FWnSHLY:vM5f40x/m6VTLbISHLY`

## Runtime Data

### Usage (stdout):
```Batchfile
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: quser.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `quser.exe` being misused. While `quser.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `            - '\quser.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - quser.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | quser /SERVER:"#{computer_name}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | quser | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) |     quser | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) |     quser /SERVER:"${computer_name}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## quser

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about user sessions on a Remote Desktop Session Host server. You can use this command to find out if a specific user is logged on to a specific Remote Desktop Session Host server. This command returns the following information:

- Name of the user

- Name of the session on the Remote Desktop Session Host server

- Session ID

- State of the session (active or disconnected)

- Idle time (the number of minutes since the last keystroke or mouse movement at the session)

- Date and time the user logged on

> [!NOTE]
> This command is the same as the [query user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md). To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
quser [<username> | <sessionname> | <sessionID>] [/server:<servername>]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<username>` | Specifies the logon name of the user that you want to query. |
| `<sessionname>` | Specifies the name of the session that you want to query. |
| `<sessionID>` | Specifies the ID of the session that you want to query. |
| /server:`<servername>` | Specifies the Remote Desktop Session Host server that you want to query. Otherwise, the current Remote Desktop Session Host server is used. This parameter is only required if you're using this command from a remote server. |
| /? | Displays help at the command prompt. |

##### Remarks

- To use this command, you must have Full Control permission or special access permission.

- If you don't specify a user using the <*username*>, <*sessionname*>, or *sessionID* parameters, a list of all users who are logged on to the server is returned. Alternatively, you can also use the **query session** command to display a list of all sessions on a server.

- When **quser** returns information, a greater than `(>)` symbol is displayed before the current session.

#### Examples

To display information about all users logged on the system, type:

```
quser
```

To display information about the user *USER1* on server *Server1*, type:

```
quser USER1 /server:Server1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


