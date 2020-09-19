---
title: change.exe | Remote Desktop Services Change Utility
---

# change.exe 

* File Path: `C:\Windows\SysWOW64\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `582214B45CA2404BE73109AE47A8A6C7`
SHA1 | `A7774C5CB46E39E493D63CE1C32B66DD2353B503`
SHA256 | `41DC113DA22BD4CF8454F12CD69E1B695FC2C78EE149EBC0DC02624425F00CA6`
SHA384 | `1D89AC9E430012BB371E7EC98AC9EF22B96E7719D15FD28C9E34DDAA0B91E2B5B21AECF80763498E1440E552E0F46F51`
SHA512 | `070C7346DE337F1EA9941209DCB10D5CDDC46D98D007032BB3B8BF07EDE920F093953386164A0E57BF01BE5B81E60136835BFF3BD49BBA236570A6E4ED1B41C3`
SSDEEP | `192:Ew0YSkgF5ne93NhfTqVc+1pd/1mt2WcogKkPWZLW7:EVxDe93NhfTqy+R/1qlg9PWZLW7`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\change.exe |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\query.exe](query.exe-BCB053556213C5755EAEF97D2F68BF0C.md) | 54
[C:\Windows\SysWOW64\reset.exe](reset.exe-8459B5D2B47AB266516A26D9DD080979.md) | 54


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


