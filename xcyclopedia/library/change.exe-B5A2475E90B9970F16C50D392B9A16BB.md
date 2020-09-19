---
title: change.exe | Remote Desktop Services Change Utility
---

# change.exe 

* File Path: `C:\Windows\system32\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `B5A2475E90B9970F16C50D392B9A16BB`
SHA1 | `0FC5EAAFBB93C2D1816F0FED0E1D5B2A3AE57373`
SHA256 | `D2DF044B73E57CB2FFAB4BEAE33355301B124B7CA45861C683B97D376019D717`
SHA384 | `9D521667F05AA8D2E975441A3B1FA7E0560A0F2C82116D68A58EE38433D69AD0DB43C2C709C347EF3994562E7C8D7324`
SHA512 | `C2AFC2FF49A578C67921290D598BFF0E5AA0149731B4732D6ECDB3A44E71C3AA20C734E6E63E4ECAEB668F49C168BB1CF2A72D6F711332457B05B7D1FC65B9BE`
SSDEEP | `192:/YOS4SwveEAMuDzEAk3ZsThGdgo8jJIbO4kvByIhwxxth2GcDK71gmfWOLW:/YOQ1M/Kg7y2bzGlOxth20hFfWOLW`

## Runtime Data

### Usage (stdout):
```cmhg
CHANGE { LOGON | PORT | USER }

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
CHANGE { LOGON | PORT | USER }

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\change.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\query.exe](query.exe-29043BC0B0F99EAFF36CAD35CBEE8D45.md) | 83
[C:\Windows\system32\reset.exe](reset.exe-FE84BB8BBAA4FA1FD3892BE328E78A3F.md) | 75


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


