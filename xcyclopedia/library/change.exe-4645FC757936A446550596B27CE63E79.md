---
title: change.exe | Remote Desktop Services Change Utility
excerpt: What is change.exe?
---

# change.exe 

* File Path: `C:\Windows\system32\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `4645FC757936A446550596B27CE63E79`
SHA1 | `A68600DEF3CCA2294CDBC2933C8D5081220FB227`
SHA256 | `C66BF7322DEEAEC6109FD82C700569E3322701AFB5EC19006B51E3600EEE86CB`
SHA384 | `2D15C5554ED1049137820CF75C3461A05F186678BC1402AE51BB0D726F5268BB2C3CB2356AF53717071B93E05DCBFF9A`
SHA512 | `2ACE5B1370A0F0931A96951EED0AF1E382D6A18D41D6F4786265B79EA1254D3BC6C5035D3902DCEC873A07D0216CA292340B77CE65D53C2567860052C41D3B92`
SSDEEP | `192:vWS8qyttAW2/Ei8h9aPB/E/RJoqxx2+YcLWjhAvNsr+GXn1qmvWNLW:vWS8qyUW2s9/fTD2TKo2vNsr+wvWNLW`

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

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\query.exe](query.exe-45AAE6BB615AE7972BB24A317F6AFC3E.md) | 86


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## change

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020-2021 Strontic.


