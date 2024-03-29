﻿---
title: query.exe | MultiUser Query Utility
excerpt: What is query.exe?
---

# query.exe 

* File Path: `C:\WINDOWS\system32\query.exe`
* Description: MultiUser Query Utility

## Hashes

Type | Hash
-- | --
MD5 | `1F85FC4EF8B60C9ADD72F6C856DD0589`
SHA1 | `4568C5F804ACCC63045F5F2C1FA4DA3750ADFC14`
SHA256 | `E0655B492CA255745D122CAA2A1147AE01554CA5AE2F53454863D6706D667910`
SHA384 | `35392498A7B0820129EC713985077739EA53001F46BD7461C5FECADEB1129020A9A28427D9A4ADC79897AE3BFB5B937E`
SHA512 | `D579ED855CF035CE0B608FC923A20567B05DA75693E9787D8F2C42DCCB49B8C854FB1ED644C98F98DCEDB1EA93A263ED2B3B9F4A68A7FE92B047B194EF65333F`
SSDEEP | `384:oyymcKXLaxy2eeTX94dnntGHK2aCP4WQ3W:Ym8etdnWHPS`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: query.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\change.exe](change.exe-01302ADDA9C5C683F8EBD151C2184683.md) | 75
[C:\WINDOWS\system32\reset.exe](reset.exe-15D84EF11876BB1264257B0CC60C7B62.md) | 71


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


