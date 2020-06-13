
# chglogon.exe 

* File Path: `C:\WINDOWS\system32\chglogon.exe`
* Description: Change Logon Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `495D25C8551F585A6C1967F720008439`
SHA1 | `D5A463674CE7FAF6B754D1B2CC30191B4A669E5A`
SHA256 | `F4FD41E25FA4E35606E00BA7EDB7572A6D130444DA0198B3FCE0FB740AA042DA`
SHA384 | `B0641767C925487207F39D3A6A46C4F109A3067818D2A3B08DFDF638585B23A206E279717B828926818A11D531FE74A6`
SHA512 | `B0CAE3D1093484975663F659C0356C53F61A2A3E03E8190B02139F79A546BCC71A90783C4C39854F46B245D026F9B27F3DE9BC364D611A641E5DA159125E3A59`
SSDEEP | `384:IHKiqXNzrO3TVneuEvz5+Yc1K8OSRHnhNAmaJP45HCMHnCUi7iWnEW:Iq7FrOj9edg91K8b01ACdj`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Enable, disable, or drain session logins.

CHANGE LOGON {/QUERY | /ENABLE | /DISABLE | /DRAIN | /DRAINUNTILRESTART}

  /QUERY    Query current session login mode.
  /ENABLE   Enable user login from sessions.
  /DISABLE  Disable user login from sessions.
  /DRAIN    Disable new user logons, but allow reconnections to existing sessions.
  /DRAINUNTILRESTART    Disable new user logons until the server is restarted, but allow reconnections to existing sessions.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chglogon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# chglogon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status.

> [!NOTE]
> This command has been replaced by the **change log command**. For more information, including the syntax and parameter details, see [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md).

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---


MIT License. Copyright (c) 2020 Strontic.


