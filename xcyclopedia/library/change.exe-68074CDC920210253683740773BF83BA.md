
# change.exe 

* File Path: `C:\Windows\SysWOW64\change.exe`
* Description: Remote Desktop Services Change Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `68074CDC920210253683740773BF83BA`
SHA1 | `3DBBD3B182763F339E3F1144916B31B2529615BC`
SHA256 | `C5ACCEE50BDD264776CD55BE2779E5526DDAAC18491B4A0F2ABB9E94B18BF3BA`
SHA384 | `1BC91DA2AE825E2EFE345DE351A2E1E4200F77CAD07DB4F571421423A13EABBB3BB435EEF2CC17033B9A470F7DA8E1A2`
SHA512 | `0752FF60B2F7737C5464A9455B8D5EF2E01514C211E9F637514CE97E9DE82CE481A62E939827B2702808E61E37AA67E080E763443A193BCEC7059CE7675CE8D3`
SSDEEP | `192:jE8NF93i5BeEP9Y9aMXXtTgT6+3KEVtAQCkHWNLWk:jaM6Y9aMXXBg2+3KEb7HWNLW`

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

### Child Processes:


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


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# change

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes Remote Desktop Session Host server settings for logons, COM port mappings, and install mode.

> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/dn283323(v=ws.11)).

## Syntax

 ```
 change logon
 change port
 change user
 ```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md) | Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status. |
| [change port command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-port.md) | Lists or changes the COM port mappings to be compatible with MS-DOS applications. |
| [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md) | Changes the install mode for the Remote Desktop Session Host server. |

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---


MIT License. Copyright (c) 2020 Strontic.


