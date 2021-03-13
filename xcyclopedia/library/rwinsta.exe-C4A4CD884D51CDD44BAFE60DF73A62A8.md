---
title: rwinsta.exe | Reset Session Utility
excerpt: What is rwinsta.exe?
---

# rwinsta.exe 

* File Path: `C:\Windows\system32\rwinsta.exe`
* Description: Reset Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `C4A4CD884D51CDD44BAFE60DF73A62A8`
SHA1 | `C9381966B35C192EF52830B0BF00DEEA71B893E7`
SHA256 | `86E0F9AEE3C5676360F82049D1039419179857390243F9F07C36091343056304`
SHA384 | `C3FA9CC474105BA7706EDC0A6CFD7BB68E5F47899470F7AB0FFC64F3C249F310B0843DC9ABEB640A3C55BB8FADB2C5A8`
SHA512 | `5F994922ADCF79243E009F6DE0B6E9D4D3FB69BA28395347EC3B6E95844D701E8D91D805B4F2FB024AEB86B8B3C03EE3EE2279FBE410865A84928686FE969FEC`
SSDEEP | `384:DmM5jxq34/ziswyWZpA/NJ/tuUx7ED55mCRJ19FVA6NOszp5scyGMrUelRiHWpZW:aMpQ34risg4/hOgSn9L5XzDNelRiG`

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

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


