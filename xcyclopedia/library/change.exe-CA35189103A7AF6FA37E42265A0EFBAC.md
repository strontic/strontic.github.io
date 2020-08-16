---
title: change.exe | Remote Desktop Services Change Utility
---

# change.exe 

* File Path: `C:\windows\SysWOW64\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `CA35189103A7AF6FA37E42265A0EFBAC`
SHA1 | `0BE23E19EC52B01E39EC42986312241C4D5E775E`
SHA256 | `28E9E1C154AA7B11049AADDEBC275341A90F23395C44E07AEEB08907AAE7EC26`
SHA384 | `CFA6BE433CF7F2756C225E211B8142A3602857BEE5F164AA02FEF4F643B41CF4CAF39404641C73ADBC250E6A8CB75CCD`
SHA512 | `54EF9C85C7CE21F2127F1AD458D63FEDEDD95FF519E5052C96EE9AB6625D6CE2EF8A00868025BC20E4680B8D455328F768F6178E4C73E616C71C8A931C950721`
SSDEEP | `192:kL+3WInZQU1MJvPdeA7MIbKRCik9C8X9iTZjtmLsYBMJ9B9QkJkIEWALWBm:kAWIniYjk9C8X9UxILsgk3KHWALW8`

## Signature

* Status: The file C:\windows\SysWOW64\change.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\SysWOW64\query.exe](query.exe-CF07B03F443C3E3062FDFDEF6BDD6E6B.md) | 63
[C:\windows\SysWOW64\reset.exe](reset.exe-965976EEC978470073D538098AD76E48.md) | 65


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## change

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes Remote Desktop Session Host server settings for logons, COM port mappings, and install mode.

> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

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


