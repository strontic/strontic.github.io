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
MD5 | `7C596A9625825724991DFC4CCC314E65`
SHA1 | `0B01624DB5371FA64BD9A55A9FD347244176906E`
SHA256 | `D934E8742DBD682E7BA5ABBECCA7C31E7ED064AC7106FDA11E1CFBAD49FBE71B`
SHA384 | `43FEA6ED86FE6D59E292826B777081863D79FA25B7C6C2E6C840DBDD21C2CB001080A15ED426B9512AC586D450577440`
SHA512 | `062D1FED3DE433B5ABC14D8AF9897AE9F7D72B33C4D3AB664ED8C37FB9C64349687A45CBCDF7DCB9E49E477F413E2E484A93E2D60FE82E7A53F5E1E5A04D72D8`
SSDEEP | `192:M3WRNA8256eIMNY9akXH9TAT7+3KEVtAQSkP4Wa3WZVr02:TeRPY9akXHRA3+3KEb7P4Wa3Wff`

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
[C:\Windows\SysWOW64\change.exe](change.exe-68074CDC920210253683740773BF83BA.md) | 47
[C:\Windows\SysWOW64\reset.exe](reset.exe-4A17440BFD58A851B10902E3F04D0CAB.md) | 80


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


