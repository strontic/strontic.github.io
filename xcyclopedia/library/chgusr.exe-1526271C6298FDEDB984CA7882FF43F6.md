---
title: chgusr.exe | Change INI File Mapping Utility
excerpt: What is chgusr.exe?
---

# chgusr.exe 

* File Path: `C:\WINDOWS\system32\chgusr.exe`
* Description: Change INI File Mapping Utility

## Hashes

Type | Hash
-- | --
MD5 | `1526271C6298FDEDB984CA7882FF43F6`
SHA1 | `075E7839A4EE0D357D2784386FD309DA70C8B55F`
SHA256 | `866FA19C2F5E84C01870F6838DD8AB12BAD9C0D0C41A567B693DA797C0ADCF6E`
SHA384 | `09B67843080875B46FB5DEF341C1F01021A37412CE9B6381C5058724BAC6D443452184182B19A08A5C298AF0D8863213`
SHA512 | `B6EA77D11CEAEF8794126AD504B8B47BF4AA0326C6A5430DF0160689924346A5E68B0C3073808CA194E6C646BA6EE2425B67997A705E350889B2E73DC6ECB4ED`
SSDEEP | `384:YOSMnSzq+zF1Vv1/SaycVIC08PtNpJZ5qICOzwmbhJJCSH5PRU9SWMVW:YIG3F1Vd/SxcOzGNZwIDwmbB5W9I`
IMP | `EA17270B67FAE16B05714FD14BE68EA3`
PESHA1 | `7BC0C7A53DB3E6562F5CB363EB6FA1AABD0FDF9C`
PE256 | `2B3A6B7FBD2DEF5CF65077BDEB8B9AD58BDD2CE62B1F00B07E549484F1294B8D`

## Runtime Data

### Usage (stdout):
```cmhg
Change Install Mode.

CHANGE USER {/EXECUTE | /INSTALL | /QUERY}

  /EXECUTE  Enable execute mode (default).
  /INSTALL  Enable install mode.
  /QUERY    Display current settings.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Change Install Mode.

CHANGE USER {/EXECUTE | /INSTALL | /QUERY}

  /EXECUTE  Enable execute mode (default).
  /INSTALL  Enable install mode.
  /QUERY    Display current settings.


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\chgusr.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chgusr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/866fa19c2f5e84c01870f6838dd8ab12bad9c0d0c41a567b693da797c0adcf6e/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## chgusr

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes the install mode for the Remote Desktop Session Host server.

> [!NOTE]
> This command has been replaced by the **change user command**. For more information, including the syntax and parameter details, see [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


