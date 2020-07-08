---
title: tsdiscon.exe | Session Disconnection Utility
---

# tsdiscon.exe 

* File Path: `C:\windows\SysWOW64\tsdiscon.exe`
* Description: Session Disconnection Utility

## Hashes

Type | Hash
-- | --
MD5 | `1ABB99A7422F830E1B875281155A0E2A`
SHA1 | `0965E581566F0BC654C5E694314DB347A4D66195`
SHA256 | `C6F572841F362B549C9FACC377E280D09623873502EC1D02961BD4EDDC7D1E27`
SHA384 | `B866BD70AE4A72BFBB6C99BACFFA7D1D2B0AA7C5E596E0FC39670015D2DF00EFF2EACECEF1F4A8D1310EDE8A63B15846`
SHA512 | `549F27AF7A7A5FCB49161BF5831D619B9078A921B6CAD217098FD108116B90F082F3265C2057394355477EF7133524D553F9CBF1B41ECAC9230001F10C3693AB`
SSDEEP | `384:oOy3MZoSPbv+kcw/kWmsbSjUIZ10E47nx27V3WMqWWED:oOyioSPrX/uNw2p8M`

## Runtime Data

### Usage (stdout):
```Batchfile
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

### Usage (stderr):
```Batchfile
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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tsdiscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Disconnects a session from a Remote Desktop Session Host server.



> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

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


