---
title: query.exe | MultiUser Query Utility
excerpt: What is query.exe?
---

# query.exe 

* File Path: `C:\Windows\SysWOW64\query.exe`
* Description: MultiUser Query Utility

## Hashes

Type | Hash
-- | --
MD5 | `BCB053556213C5755EAEF97D2F68BF0C`
SHA1 | `49B715FBEC24F1B1787DCD8D1658757BAFB8186A`
SHA256 | `856EA448CE7E099496A0C9D7783FFFD2A28E9F1F931D2146714AB7640C39BADA`
SHA384 | `81848D8F554C4C1E6F02FC8C7E9AAFDAC373EABE8F20CF6BC8B2B2B9D30F8A887355EC9FF04606B62F6AE0F383FB9242`
SHA512 | `F1C504270EDD6FCD7401979ED6DB86C5DF3C4E58D440E521D83D62CD5DB72C08791B423ADC543B4C54F3BB0C6489FB7AF46A924571E2F4AB94A302516F7FD706`
SSDEEP | `192:+WzogF5/eyf1wzT4Fce1pN/1mt2Wco7kPAWW3Wd8:HVDGyf1wzT4ieh/1qlwPAWW3W`
IMP | `EC309FD93AE54D1FFDF17E744E71C366`
PESHA1 | `972E27D94CFCDA78CC1C0C9E299C58F1D3081A5F`
PE256 | `7CC838D6491EF4498196B06C020BCDDCC0D4FA29428E51817D1EBC4A63A95AA2`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\query.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/856ea448ce7e099496a0c9d7783fffd2a28e9f1f931d2146714ab7640c39bada/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\change.exe](change.exe-582214B45CA2404BE73109AE47A8A6C7.md) | 54
[C:\Windows\SysWOW64\reset.exe](reset.exe-8459B5D2B47AB266516A26D9DD080979.md) | 82


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## query commands

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


