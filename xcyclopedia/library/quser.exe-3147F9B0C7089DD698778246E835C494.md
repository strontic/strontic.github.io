---
title: quser.exe | Query User Utility
---

# quser.exe 

* File Path: `C:\WINDOWS\system32\quser.exe`
* Description: Query User Utility

## Hashes

Type | Hash
-- | --
MD5 | `3147F9B0C7089DD698778246E835C494`
SHA1 | `8040C04017E6B1AF0B704E632FA1FB4655D5EEF1`
SHA256 | `6EE15E5B1311D501FBDAA15C9D1197BA2F99745EA5ABB3E724D598EE53D48A6E`
SHA384 | `D800081202047346984F1BD904F87FACA2BB30BCCFF487500112BE4A21943667AB75A90BC878F9A51CBBAF823E88D42B`
SHA512 | `EEE3AB3655EB56E1FFD6EF9FAA86CA2DC2355D3466D94ABCA5B147DC46DBBCE994CFB911E0133564CDC50EAE49B5BB225570D089D0A641D5F3C972B9164CB553`
SSDEEP | `768:XdcgSIZE45pVrLSoYMmWyDwK895aPJ+dP:N9SgVrqy5aAdP`

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
C:\program files\LibreOffice\program\quickstart.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\VCRUNTIME140.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: quser.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\quser.exe](quser.exe-6309F1482DAB3BDE91074316892BDCA7.md) | 80

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


