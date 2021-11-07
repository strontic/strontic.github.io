---
title: rwinsta.exe | Reset Session Utility
excerpt: What is rwinsta.exe?
---

# rwinsta.exe 

* File Path: `C:\Windows\SysWOW64\rwinsta.exe`
* Description: Reset Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `7CF7A16E8E5C70D95D9658C0BDD6FF8C`
SHA1 | `FF18B0A8DA344759F3B8D677BB723A8E42CA49D7`
SHA256 | `DD736D92D7889E04D001486F0434AB7006A6688AA1842E1B4278A0BADDEF8AAD`
SHA384 | `7F063D4F0C0E42B3854105508474E9E275B615CB8F780885359D3AF6CFB31D223F74923A154F6E26D2652BB15E12F31C`
SHA512 | `5CB166DEA6B6DCE2E1E95CDE4D61819F3CAD92D6F0C74DDA0CCD2AD74D07CFD0FF7B1EC31A416CC0CAA2C7DB1E6C36DF2DD2A9F2F4740980C2BC6E7836053594`
SSDEEP | `384:ZCB2LyLQlg9a0nSESiaEXCtf/nE8onWpZWm:ZtykSXGomL`

## Runtime Data

### Usage (stdout):
```cmhg
Reset the session subsytem hardware and software to known initial values.

RESET SESSION {sessionname | sessionid} [/SERVER:servername] [/V]

  sessionname         Identifies the session with name sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server containing the session (default is current).
  /V                  Display additional information.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Reset the session subsytem hardware and software to known initial values.

RESET SESSION {sessionname | sessionid} [/SERVER:servername] [/V]

  sessionname         Identifies the session with name sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server containing the session (default is current).
  /V                  Display additional information.


```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## rwinsta

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Resets (deletes) a session on a Remote Desktop Session Host server.

> [!NOTE]
> This command is the same as the [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md).

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Additional References

- [reset session](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md)

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


