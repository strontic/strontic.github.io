﻿---
title: query.exe | MultiUser Query Utility
excerpt: What is query.exe?
---

# query.exe 

* File Path: `C:\Windows\system32\query.exe`
* Description: MultiUser Query Utility

## Hashes

Type | Hash
-- | --
MD5 | `45AAE6BB615AE7972BB24A317F6AFC3E`
SHA1 | `2A2BDB268F3514A418056CF53609557E807F0579`
SHA256 | `0141B31C3583FC37D82B2506D0806E2060D34B89CD507A329A69162F435A8CE0`
SHA384 | `AFB5FA485A0D50A5F694DFC79CEF3914A6C0781638652268701A4DD771CDCD03E58CB6697DD1A70B9C6BCCD12754FED2`
SHA512 | `E9644DCD3B8BAF0C5237AB1E997040776FA3BB7F9B8E38986E1502F3AD2DBA23DDA8945E0A012B69480EE3D5BD8FA23C9D4897F39F4FAB5BB8A1BD9CCB6F8C93`
SSDEEP | `192:k/P8qyttAW2/Ei8h9aPB/E/RJoqxx2+YcILhAvNsr+GXn1qmPQWa3W:k/P8qyUW2s9/fTD2T72vNsr+APQWa3W`

## Runtime Data

### Usage (stdout):
```cmhg
QUERY { PROCESS | SESSION | TERMSERVER | USER }

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
QUERY { PROCESS | SESSION | TERMSERVER | USER }

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: query.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\change.exe](change.exe-4645FC757936A446550596B27CE63E79.md) | 86


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## query commands

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes, sessions, and Remote Desktop Session Host servers. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
query process
query session
query termserver
query user
```

#### Parameters

| Parameter | Description |
|--|--|
| [query process](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md) | Displays information about processes running on an Remote Desktop Session Host server. |
| [query session](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-session.md) | Displays information about sessions on a Remote Desktop Session Host server. |
| [query termserver](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md) | Displays a list of all Remote Desktop Session Host servers on the network. |
| [query user](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md) | Displays information about user sessions on a Remote Desktop Session Host server. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


