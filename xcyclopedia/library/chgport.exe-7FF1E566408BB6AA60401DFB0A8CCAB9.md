---
title: chgport.exe | Change port Utility
---

# chgport.exe 

* File Path: `C:\Windows\system32\chgport.exe`
* Description: Change port Utility

## Hashes

Type | Hash
-- | --
MD5 | `7FF1E566408BB6AA60401DFB0A8CCAB9`
SHA1 | `21DD46155DE91B6196F0ADD2BB90BACF6DD51891`
SHA256 | `92E224A1E945B43143D74D1396B391C0FE9E123FD075C8FF368A7800B1FCD985`
SHA384 | `1FDAB386A5DF32A08FC4C084775BE4943A68FABB598700AED55320A2DB255EC98489CE650E2E9BFD16CC2AF98CBBFD14`
SHA512 | `3FA30CE26D3FBD2BF97EFD27D5A4953A90FBE8CEE455314F53F011B139612837080F527D0133EE4179E09692EACBBF210D24E746836033D0A88291C089D13859`
SSDEEP | `768:9r+otF1NLLreAtASiVnK8NV+HMAjMujy:cYPr8SykHjXy`

## Runtime Data

### Usage (stderr):
```Batchfile
Invalid parameter(s)
List or change COM port mappings for DOS application compatibility.

CHANGE PORT [portx=porty | /D portx | /QUERY]

  portx=porty  Map port x to port y.
  /D portx    Delete mapping for port x.
  /QUERY      Display current mapping ports.


```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\chgport.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chgport.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\chgport.exe](chgport.exe-879A0A757FD993B5D860863F8CE0C68F.md) | 74


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## chgport

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Lists or changes the COM port mappings to be compatible with MS-DOS applications.

> [!NOTE]
> This command has been replaced by the **change port command**. For more information, including the syntax and parameter details, see [change port command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-port.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change port command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-port.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


