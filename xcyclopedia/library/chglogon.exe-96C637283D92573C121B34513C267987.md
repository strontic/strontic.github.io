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
MD5 | `96C637283D92573C121B34513C267987`
SHA1 | `1556FDC9EE7E3F8C8729932E0D5E660DFD69CC53`
SHA256 | `A9CC2B03783896C6596D8F4E4CC3DB555A9096264BC8253478D1F0F0FBB2B74B`
SHA384 | `F4A07779DB4957DC86365F6165385B0056D5CA01099BC5BE32070DA905A00C4AFD3B5918E21AA4E5B07A9559071424BC`
SHA512 | `A7AA96670C2B1A2CF8511C4BEF0F2742FA3E2BBE8B797D380652B8BC8D57182FC97FE1FB41B6DE3279FEBDFEC9AF280C7C9DF9641BE0685FFB90219CAF68DFF2`
SSDEEP | `384:aoE7WrAWCBk4MAQhI/CtoeT5nj1Z8YuB+rtNsN7uEGVEkGuRVHIhjkKWiEW:aoSPW2k4MAQhI/n2h1Z8Ye+tiuD/0km`
IMP | `39CDC867B4449192C880F526495B2B10`
PESHA1 | `283D9110925B5F6064A65759EA0B5AF7BFFFE805`
PE256 | `FB40002BF1019B9BD699FDB1B60910A1E269E91251578360A1E523D135D4C51B`

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
C:\Windows\system32\chglogon.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chglogon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/a9cc2b03783896c6596d8f4e4cc3db555a9096264bc8253478d1f0f0fbb2b74b/detection



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


