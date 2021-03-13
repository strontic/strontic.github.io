---
title: chglogon.exe | Change Logon Utility
excerpt: What is chglogon.exe?
---

# chglogon.exe 

* File Path: `C:\Windows\SysWOW64\chglogon.exe`
* Description: Change Logon Utility

## Hashes

Type | Hash
-- | --
MD5 | `CFEE172286F48AA1A6A2B2AA3645F699`
SHA1 | `1BD3492FBC72369F22749FB58197897B89222402`
SHA256 | `AF8EFCA7D19796276A3B6A9FCB352A9B15B2626DDCE0EE0AEEABCD756CF3788E`
SHA384 | `166A11919A72BD534BD12AE07259C957BA9869546241C5ED3AC1982097E462D475F8082571EB57F28FF92128918D5512`
SHA512 | `005FC9B063EF1A237DC344B75916A6BCB0B47152A2C7619BA81DB0EA9A82C91A14AF683CC8AA0BCF7BEF79A1BA6868D48A1A872633751F12C3B5DE01645E5C7B`
SSDEEP | `384:s4pwPylhbRXSQJxDbLafHRzd2oc6W9EWp:npZxzar2Pxv`
IMP | `F6FC784018617DBB3B914E1E40B3A303`
PESHA1 | `9F5F8B232FD5AC7D132F1EB1E4AC204B1277DA89`
PE256 | `1DA5C4C3C3A7A5D2DF598D76948BCBEB6E39CE2B578811128AC708B50325F649`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\chglogon.exe |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/af8efca7d19796276a3b6a9fcb352a9b15b2626ddce0ee0aeeabcd756cf3788e/detection/



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



MIT License. Copyright (c) 2020-2021 Strontic.


