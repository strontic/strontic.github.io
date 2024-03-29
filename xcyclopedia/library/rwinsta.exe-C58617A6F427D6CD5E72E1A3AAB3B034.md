﻿---
title: rwinsta.exe | Reset Session Utility
excerpt: What is rwinsta.exe?
---

# rwinsta.exe 

* File Path: `C:\WINDOWS\system32\rwinsta.exe`
* Description: Reset Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `C58617A6F427D6CD5E72E1A3AAB3B034`
SHA1 | `08AA9625F6F378513DD6E04D906096E44EB6705B`
SHA256 | `514620BBE95E8408DF43FAA2D85740722581756C7AC3B32B7F51C6B007A91F78`
SHA384 | `749D4C934ED6B827EEEC6EE95BED947E4CBF303ACD33D84A497C4C8B2ECBFF57B448944B349ECD8071106A138AE190EB`
SHA512 | `4108017C00538C86923B834FDBCF21073030239CB29A53F4EC2E789E3A94A7E5AB8EE929E3A469071E35B44AEAB91ADA33386527C85C1C4D65ED1D706868686D`
SSDEEP | `384:spssqyMYMx/kBrpVNcENkE1z5YcsK80Mnkt8HS+IL0jIWjMcZpefBVMfWnZW:TdbY8ErpV5NNHsK8JhvIA5LefBO8`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rwinsta.exe](rwinsta.exe-BB409E77E0EF5A6645A0E665586C7440.md) | 79


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


