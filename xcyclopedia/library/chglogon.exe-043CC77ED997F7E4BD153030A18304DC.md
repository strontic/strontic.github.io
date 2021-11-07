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
MD5 | `043CC77ED997F7E4BD153030A18304DC`
SHA1 | `A2F0F37CA9072E048C8CE9FE8E9F09F37C5E1EC4`
SHA256 | `C91F6B286B59AE125BC039512FF9801354C10E74DCA9CD803067D2CD1441592F`
SHA384 | `A738E63FFEC8E070BFA1868266B1B7A48C692080128B17845EBF8BA633365B5DA5F1028210BA4B53B6C0ABCD1E7122DF`
SHA512 | `62188CA77C4220B4C5CBFC3E6524463A592C20182EAC3898976255E407C3D2FA3EAB60A658DC3F22C2A1C87FCA9A96011AC118FE9CADED7EF04B9EB8BCD3660A`
SSDEEP | `384:BHKiqXNzrO3TVneuEvz5+Yc1K8OSGHnhNAmd2P45HCMHtC4qCW9EW:Bq7FrOj9edg91K8E0rAEjp`
IMP | `39CDC867B4449192C880F526495B2B10`
PESHA1 | `0B20715E2F46DE6D9F89FD6846C878C113209A9B`
PE256 | `698D6317016FDE34AB9E6244E903B523E04A78E29F0B6F1B45AB8EA0F1F52C09`

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c91f6b286b59ae125bc039512ff9801354c10e74dca9cd803067d2cd1441592f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\chglogon.exe](chglogon.exe-495D25C8551F585A6C1967F720008439.md) | 83


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


