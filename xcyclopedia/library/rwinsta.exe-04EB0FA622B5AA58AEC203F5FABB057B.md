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
MD5 | `04EB0FA622B5AA58AEC203F5FABB057B`
SHA1 | `59EBADE1AB55A2B7157D4EE64D562126FD5287BF`
SHA256 | `0C5B4F925D9EAEE1F899B5497B807402F00B20BB19706285218F1A7D8EEB85C2`
SHA384 | `463EBAF97847D463FF5A193795B5B9478632131F8B5BB84689DC532CBD7A5673C0CA45BE4C78B504CE01E9E5B7147940`
SHA512 | `687FF3E5CCC78F07CCE2CDEC7E4517F04FFA38CE6D09ADFBBB69AD7B1D074C2D30400AB9DBE27571A86C5F02DAFB755EBD400E4868D8715CE184DC46E4DF8A65`
SSDEEP | `384:3gMiaCE0mL0M8WTsFapjPSWfOl52o2j47nx278PWdZW/CM:wbE0moDQc2o222QytM`
IMP | `09B3435A74D77CE7C500B1C424B63FD1`
PESHA1 | `21903E3CF3616623D9613584C4CA0953495CBAEE`
PE256 | `B999ECF5F7209080F8B7D6E0B9C50E91FF4B98B8F89CC85A54A1DF0953FB1648`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rwinsta.exe |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/0c5b4f925d9eaee1f899b5497b807402f00b20bb19706285218f1a7d8eeb85c2/detection/



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


