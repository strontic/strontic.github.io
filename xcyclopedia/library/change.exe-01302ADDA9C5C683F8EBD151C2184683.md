---
title: change.exe | Remote Desktop Services Change Utility
---

# change.exe 

* File Path: `C:\WINDOWS\system32\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `01302ADDA9C5C683F8EBD151C2184683`
SHA1 | `7FEB516366D12056A3443379712279649FDB24F9`
SHA256 | `9D509F6F0B21A33E758C50418BF5592B6A8078365F18AA3784AB6CD1023940BC`
SHA384 | `2EF6D82DA193A9151F161CE91B91697CD13B087510F90F535517F09ED2C8DC272940C68234EC522AF22B011AC38C336F`
SHA512 | `19581C959E1EB56CDBB2673C29D25623F7640B5D91C66C403431F5E78DAF203269677DDCCC0129EA62B3577B42910DC3A5192CD42C9770504183C98812D2DC5C`
SSDEEP | `384:o1yecKXLaxy2eeTX94dAbPtGHK2ayXWDLW:de8etdAbWng`

## Runtime Data

### Usage (stdout):
```Batchfile
CHANGE { LOGON | PORT | USER }

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
CHANGE { LOGON | PORT | USER }

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\query.exe](query.exe-1F85FC4EF8B60C9ADD72F6C856DD0589.md) | 75
[C:\WINDOWS\system32\reset.exe](reset.exe-15D84EF11876BB1264257B0CC60C7B62.md) | 74


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## change

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes Remote Desktop Session Host server settings for logons, COM port mappings, and install mode.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

 ```
 change logon
 change port
 change user
 ```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md) | Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status. |
| [change port command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-port.md) | Lists or changes the COM port mappings to be compatible with MS-DOS applications. |
| [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md) | Changes the install mode for the Remote Desktop Session Host server. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


