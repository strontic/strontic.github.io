---
title: query.exe | MultiUser Query Utility
---

# query.exe 

* File Path: `C:\Windows\system32\query.exe`
* Description: MultiUser Query Utility

## Hashes

Type | Hash
-- | --
MD5 | `29043BC0B0F99EAFF36CAD35CBEE8D45`
SHA1 | `BFF9633D301818EB5DEB684E758A04BC204FECC9`
SHA256 | `58D1132B636C6D33C2B8B3659F310F6DE370A00F837226129657B2B82184A307`
SHA384 | `403C0D1AF974C954FF028F47AA1728507B5BDBD9037D8ACD3D7C94E5AD408323B5AE0E6C044FC4D0A6F569BB0B82CE30`
SHA512 | `A3FF3FB40A11C98C64AE7EE9B052BC00EB10401BAAB665BC9EFCBC0F3B0B9616761776F5942E614E40CF1C088575040024ED046A0E90BF72C7269A40A9DF91CD`
SSDEEP | `192:/+OSUSw8eEAMuDzEAk3ZsThGdgo8jJIbO4klbhwxxth2GcDK71QmPgWh3W:/+OV1M/Kg7y2bzgOxth20hVPgWh3W`

## Runtime Data

### Usage (stdout):
```Batchfile
QUERY { PROCESS | SESSION | TERMSERVER | USER }

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
QUERY { PROCESS | SESSION | TERMSERVER | USER }

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\query.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: query.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\change.exe](change.exe-B5A2475E90B9970F16C50D392B9A16BB.md) | 83
[C:\Windows\system32\reset.exe](reset.exe-FE84BB8BBAA4FA1FD3892BE328E78A3F.md) | 75


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## query

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


