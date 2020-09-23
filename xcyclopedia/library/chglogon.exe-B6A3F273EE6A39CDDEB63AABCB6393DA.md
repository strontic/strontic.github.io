---
title: chglogon.exe | Change Logon Utility
excerpt: What is chglogon.exe?
---

# chglogon.exe 

* File Path: `C:\Windows\system32\chglogon.exe`
* Description: Change Logon Utility

## Hashes

Type | Hash
-- | --
MD5 | `B6A3F273EE6A39CDDEB63AABCB6393DA`
SHA1 | `C0BFE8B5628D9DCFE2966721FB3F0BF7845EA93D`
SHA256 | `1C83A61F2FBCF0713498086E22786E105557CAEEDC9A9DAA8064DD19BAA85F0B`
SHA384 | `D1423EEC68A653823B00CFC2344C269B4E2C00674802ABCD20EB161F50792A575F5E295FD3A51B12E21FDD67D0A22A2E`
SHA512 | `56436EC4624ED30E469683C103F31210F8D1E8AF0E5083E61D4FCE11FDEB26A27D3AD7A98187012F51B1B68970736B97E5A915D74C7CA95E6E2982BE1973476E`
SSDEEP | `384:+zDWGx94ReeBLAJS5Zdt2QFiEt55l/W1Vf+6YZ9aM5mlpXMrPYPuqWZEW:+/uBLZdBp+jf+3NmwYPuV`

## Runtime Data

### Usage (stderr):
```cmhg
Invalid parameter(s)
Enable, disable, or drain session logins.

CHANGE LOGON {/QUERY | /ENABLE | /DISABLE | /DRAIN | /DRAINUNTILRESTART}

  /QUERY    Query current session login mode.
  /ENABLE   Enable user login from sessions.
  /DISABLE  Disable user login from sessions.
  /DRAIN    Disable new user logons, but allow reconnections to existing sessions.
  /DRAINUNTILRESTART    Disable new user logons until the server is restarted, but allow reconnections to existing sessions.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chglogon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## chglogon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status.

> [!NOTE]
> This command has been replaced by the **change log command**. For more information, including the syntax and parameter details, see [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


