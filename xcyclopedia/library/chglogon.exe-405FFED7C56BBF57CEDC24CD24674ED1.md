---
title: chglogon.exe | Change Logon Utility
excerpt: What is chglogon.exe?
---

# chglogon.exe 

* File Path: `C:\WINDOWS\system32\chglogon.exe`
* Description: Change Logon Utility

## Hashes

Type | Hash
-- | --
MD5 | `405FFED7C56BBF57CEDC24CD24674ED1`
SHA1 | `6F8C7A8259C4137B2C5F8D7F7DA9C07DABCBC632`
SHA256 | `41DD31FED7C8AF3E2EE6786F863BA48D5F599E214DFDA58AD1C1FBF9C54B00E4`
SHA384 | `7BE4255C92B4B08E2B685EFFA9E94205CCEB9065BB28FC99AB9113A7B7F4AE52636E9DECA3897C1F7C5294C697CFAAF6`
SHA512 | `EF306598586260E74ED4DFF9B6014428A6A4D78FAF993554131CB1926014BFB03EA040048B575BC7E0074EB3E207242647A73C31473A410B9E2A2CE0DD26E511`
SSDEEP | `768:AB2gFL4aC0b/073OcXAA5smsBXr/U5S8d:AB2gB4abYBnEBXr/+d`
IMP | `39CDC867B4449192C880F526495B2B10`
PESHA1 | `48F6DF40604812DA35930372915EEBBDA83FFF20`
PE256 | `7ED3B019FFEA063D7FF5024E44DE92A00472817F5D844982C33F11ED5DCE88EF`

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
C:\WINDOWS\system32\chglogon.exe |
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

* Original Filename: chglogon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/41dd31fed7c8af3e2ee6786f863ba48d5f599e214dfda58ad1c1fbf9c54b00e4/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## chglogon

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status.

> [!NOTE]
> This command has been replaced by the **change log command**. For more information, including the syntax and parameter details, see [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


