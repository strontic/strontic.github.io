﻿---
title: tsdiscon.exe | Session Disconnection Utility
excerpt: What is tsdiscon.exe?
---

# tsdiscon.exe 

* File Path: `C:\Windows\SysWOW64\tsdiscon.exe`
* Description: Session Disconnection Utility

## Hashes

Type | Hash
-- | --
MD5 | `47455959E0350D1E872AE5FC3BFE5DBB`
SHA1 | `9FDC68C6FADAC5DB89AFA92E6F40F7CA28FB2D27`
SHA256 | `A3A379B1834A12854EB5EAE1074091DEA0BFDD2427B64DB510D04919019CA171`
SHA384 | `85709A29820476DF8A7E42B61E17A8A0002E9C36750ADE2633E575AB25C899C09A18014794C51B8E611303ABE95B17DE`
SHA512 | `8D76D248474289E680462D3B7594E1137706F687E5CFE7D7908D4CFB1A5D767E6D541D7808CD5D1208A41C6160C14FDE84D3E884290412AD0955DB0719E9A789`
SSDEEP | `384:Pp/a0VoRbvo9qCab/qtKMjasXeTQBf/nE8hvWMmWWv:hy8oRbYm/sKBTUhwX`

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

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Disconnects a session from a Remote Desktop Session Host server. If you don't specify a session ID or session name, this command disconnects the current session.

> [!IMPORTANT]
> You must have **Full Control access** permission or **Disconnect special access** permission to disconnect another user from a session.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
tsdiscon [<sessionID> | <sessionname>] [/server:<servername>] [/v]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<sessionID>` | Specifies the ID of the session to disconnect. |
| `<sessionname>` | Specifies the name of the session to disconnect. |
| /server:`<servername>` | Specifies the terminal server that contains the session that you want to disconnect. Otherwise, the current Remote Desktop Session Host server is used. This parameter is required only if you run the **tsdiscon** command from a remote server. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- Any applications running when you disconnected the session are automatically running when you reconnect to that session with no loss of data. You can use the [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md) to end the running applications of the disconnected session, but this may result in loss of data at the session.

- The console session can't be disconnected.

### Examples

To disconnect the current session, type:

```
tsdiscon
```

To disconnect *Session 10*, type:

```
tsdiscon 10
```

To disconnect the session named *TERM04*, type:

```
tsdiscon TERM04
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

- [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


