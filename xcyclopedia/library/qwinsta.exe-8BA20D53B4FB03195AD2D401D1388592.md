
# qwinsta.exe 

* File Path: `C:\Windows\SysWOW64\qwinsta.exe`
* Description: Query Session Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8BA20D53B4FB03195AD2D401D1388592`
SHA1 | `2D0A923E867034C41ED4E0F4CB01F342E1052C9C`
SHA256 | `D292A447B82B1EE408B3FEE4AA092B9E437866E2C2631087B4A698426592DC76`
SHA384 | `5D31F95B1AD51000EC5FDCF4C9104BDB219C350FE47C5FEAAB906074494500EBEF78ED508446C66B6206EF59FAA1C8EE`
SHA512 | `EFE51E11802A8F02EE2388B181F5CCBE980FD3E434242516F232515192121AF92936B58D34CEE51EA8B178CCCEBA27B7869C6BAF1ED38CA0B26FDD7FAFF5418A`
SSDEEP | `384:ngeQrphbmcLelWRzVBlfBg1PE9iU3ogAv9QasXFZg8XImvCSGFETUYjWV6Ww/m:gLhbBBVXfBgG14IvSYGOm`

## Runtime Data

### Usage (stdout):
```Batchfile
Display information about Remote Desktop Services sessions.

QUERY SESSION [sessionname | username | sessionid]
              [/SERVER:servername] [/MODE] [/FLOW] [/CONNECT] [/COUNTER] [/VM]

  sessionname         Identifies the session named sessionname.
  username            Identifies the session with user username.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).
  /MODE               Display current line settings.
  /FLOW               Display current flow control settings.
  /CONNECT            Display current connect settings.
  /COUNTER            Display current Remote Desktop Services counters information.
  /VM                 Display information about sessions within virtual machines.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Display information about Remote Desktop Services sessions.

QUERY SESSION [sessionname | username | sessionid]
              [/SERVER:servername] [/MODE] [/FLOW] [/CONNECT] [/COUNTER] [/VM]

  sessionname         Identifies the session named sessionname.
  username            Identifies the session with user username.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).
  /MODE               Display current line settings.
  /FLOW               Display current flow control settings.
  /CONNECT            Display current connect settings.
  /COUNTER            Display current Remote Desktop Services counters information.
  /VM                 Display information about sessions within virtual machines.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---
# qwinsta

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about sessions on a Remote Desktop Session Host (RD Session Host) server.

> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

## Remarks
This command is the same as the **query session** command.

## Additional References
[query session](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-session.md)
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
[Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---


MIT License. Copyright (c) 2020 Strontic.


