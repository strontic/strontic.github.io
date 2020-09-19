---
title: tsdiscon.exe | Session Disconnection Utility
---

# tsdiscon.exe 

* File Path: `C:\Windows\system32\tsdiscon.exe`
* Description: Session Disconnection Utility

## Hashes

Type | Hash
-- | --
MD5 | `55DCB64D819703BE022D32BF66D1A108`
SHA1 | `9E654AD675965B51DED819909AF6506A2E7BBFE8`
SHA256 | `F80EDBEB4CC05669EA5E9074261504BBABFCA2370AF868AE8C7B96E7645C3B41`
SHA384 | `9CABF98023EC1DDCBAFD900363E9FAA2890AFC8778D7112BCFD3D3372C3E4CF0DCDCFA796C8008226CDF746B546F48F3`
SHA512 | `F81BD057F3889B8012B1110512EF08F7A983D838FDA6F5DEB33E9C9358B8BB180AD7A33C9A008E19B8BCB898924A6DA773CBB71977FBE54DC7ABB3AAE55DD77A`
SSDEEP | `384:xGRs3qOHWuTfRDB825sttUGnREL55rSg0Nh7CJzjjp+vcu05yKcyGMrUEePWMmWW:xGRmHzw2ynnA9DYRCFjUjwyLEeQ`

## Runtime Data

### Usage (stdout):
```cmhg
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tsdiscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Disconnects a session from a Remote Desktop Session Host server.



> [!NOTE]
> To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](/previous-versions/orphan-topics/ws.11/hh831527(v=ws.11)) in the Windows Server TechNet Library.

### Syntax
```
tsdiscon [<SessionID> | <SessionName>] [/server:<ServerName>] [/v]
```

#### Parameters

|Parameter|Description|
|-------|--------|
|\<SessionId>|Specifies the ID of the session to disconnect.|
|\<SessionName>|Specifies the name of the session to disconnect.|
|/server:\<ServerName>|Specifies the terminal server that contains the session that you want to disconnect. Otherwise, the current rd Session Host server is used.|
|/v|Displays information about the actions being performed.|
|/?|Displays help at the command prompt.|

### Remarks
-   You must have Full Control permission or Disconnect special access permission to disconnect another user from a session.
-   if no session ID or session name is specified, **tsdiscon** disconnects the current session.
-   Any applications that were running when you disconnected the session are automatically running when you reconnect to that session with no loss of data. Use **reset session** to end the running applications of the disconnected session, but be aware that this might result in loss of data at the session.
-   The **/server** parameter is required only if you use **tsdiscon** from a remote server.
-   The console session cannot be disconnected.

### Examples
- To disconnect the current session, type:
  ```
  tsdiscon
  ```
- To disconnect session 10, type:
  ```
  tsdiscon 10
  ```
- To disconnect the session named TERM04, type:
  ```
  tsdiscon TERM04
  ```
  ## Additional References
  - [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
  [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


