---
title: tsdiscon.exe | Session Disconnection Utility
excerpt: What is tsdiscon.exe?
---

# tsdiscon.exe 

* File Path: `C:\Windows\system32\tsdiscon.exe`
* Description: Session Disconnection Utility

## Hashes

Type | Hash
-- | --
MD5 | `FF6DB497822BC8A969A83E70F717EFA2`
SHA1 | `77910AECEA5906537F325738ECC103F24FDDB0AD`
SHA256 | `7D3104A15F906D28E302B00E440366DDC4C91A4CC9C2806ABD27C123E3009A79`
SHA384 | `D57273332387D94702A33FF1B841E23EEB8492982DB9E7EBCB91862B53A9355C40858CE1F7ABD4C3C5BE63E0B1412BE5`
SHA512 | `1D4CCFC0C299394BA1D4DBA6FD088A1A1CF52797BCBA19C79F13943E276C61B64A85A98A7E191AC9F5B70BEC48411CEF339D827D7EF794C7F4674E7AE7980F3F`
SSDEEP | `384:iHgA1skjOvoOAslmmRN0E4z5dIcK8umtsdbOwGVrffjdMrQoWjMcZVaUXWMqWW:iHgA1/ymskcNsEcK8ViOVrfZMr0dc`
IMP | `3FC6BB9BBEE32550C1847BB966FD1F6C`
PESHA1 | `46C48ACFE84F8CCF75C933D4C7C37EA0054B698C`
PE256 | `0A89973196DE9BA80D5FED8D462A99EF05291488BFC2588F622F63AF81EA99A3`

## Runtime Data

### Usage (stdout):
```cmhg
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7d3104a15f906d28e302b00e440366ddc4c91a4cc9c2806abd27c123e3009a79/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tsdiscon

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Disconnects a session from a Remote Desktop Session Host server. If you don't specify a session ID or session name, this command disconnects the current session.

> [!IMPORTANT]
> You must have **Full Control access** permission or **Disconnect special access** permission to disconnect another user from a session.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
tsdiscon [<sessionID> | <sessionname>] [/server:<servername>] [/v]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<sessionID>` | Specifies the ID of the session to disconnect. |
| `<sessionname>` | Specifies the name of the session to disconnect. |
| /server:`<servername>` | Specifies the terminal server that contains the session that you want to disconnect. Otherwise, the current Remote Desktop Session Host server is used. This parameter is required only if you run the **tsdiscon** command from a remote server. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- Any applications running when you disconnected the session are automatically running when you reconnect to that session with no loss of data. You can use the [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md) to end the running applications of the disconnected session, but this may result in loss of data at the session.

- The console session can't be disconnected.

### Examples

To disconnect the current session, type:

```
tsdiscon
```

To disconnect *Session 10*, type:

```
tsdiscon 10
```

To disconnect the session named *TERM04*, type:

```
tsdiscon TERM04
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

- [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


