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
MD5 | `8A7520A6CC2A2968F4A8EE4DB946AD8D`
SHA1 | `B7B0589F7CA2A526F77E39BD6534CBD8A53BC7D0`
SHA256 | `3369E8FEA09C3C226D636B13108DA357093D0D98214236417839A94F56D3BA02`
SHA384 | `DB9ED4EACEEB20C1F895DC2066E0F1AD08B2485EDA4A0D1864B463180B2A0EF1B635E34287AD824EA614C9A651F4B093`
SHA512 | `A0643B80F86B18F40BF7717B131341AFCB43158705B8339C717BC78D79F3BFA318759CF8A548427F2D3AD59EF5296B1EA70CEA0E1E812417CB2D02AA61D7D48D`
SSDEEP | `384:5yKvwEHdWH1ZMqxdBeEh+98XfGHK2aKPoWW3W:8Kv5SVBA984vP8`
IMP | `CCC9DA4A55E90DFE34CBCDB066D6A6B3`
PESHA1 | `A4493A79E3020E560A71C4B67CE78FAE8ABC66D4`
PE256 | `720EBD80DA487D87055B12A3596F6EEAD620FB458CCEF94CB0F51532EEC87FB3`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\query.exe |
C:\Windows\system32\REGAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/3369e8fea09c3c226d636b13108da357093d0d98214236417839a94f56d3ba02/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\change.exe](change.exe-5171C542F9F07AE7D7068ED8FE0FADE0.md) | 80
[C:\Windows\system32\reset.exe](reset.exe-EDE443A63F4A5914F87DFDC6F8F59697.md) | 74


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


