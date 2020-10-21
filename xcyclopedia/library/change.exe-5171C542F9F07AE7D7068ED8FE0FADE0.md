---
title: change.exe | Remote Desktop Services Change Utility
excerpt: What is change.exe?
---

# change.exe 

* File Path: `C:\Windows\system32\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `5171C542F9F07AE7D7068ED8FE0FADE0`
SHA1 | `85CA914A1441EF2F5209D06A02B8A501B9C83AF6`
SHA256 | `17CAC86C16CF40741B5E0FD87FF02830694E1DA2715F75E18231867B79E6DF45`
SHA384 | `240A4315D6514A4743C1D7152FCC62EA812E5F2E6D8958170525C91D2152C06086BF83B73EA76DC2E8B77411D3BE5244`
SHA512 | `7749EEAFCB3C39291E500B87BA2156BA351941C4F2EFB39A83648F3604A8A5047812D4E4C175726AE67C01BB08F9633F4114860912450C9C3558AFCC06253CD0`
SSDEEP | `384:PyyvwEHdWH1ZMqxdBeEh+9JnXfGHK2aanWZLW:ayv5SVBA9Jn4vG`
IMP | `CCC9DA4A55E90DFE34CBCDB066D6A6B3`
PESHA1 | `A56F8D983210C7835754E0DA8F4CBE23C7067FFD`
PE256 | `F50897D1F83802F46B34CCDB73D2448D853D0D40A7DBEA983ED1DA5C4795EFC9`

## Runtime Data

### Usage (stdout):
```cmhg
CHANGE { LOGON | PORT | USER }

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
CHANGE { LOGON | PORT | USER }

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/17cac86c16cf40741b5e0fd87ff02830694e1da2715f75e18231867b79e6df45/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\query.exe](query.exe-8A7520A6CC2A2968F4A8EE4DB946AD8D.md) | 80
[C:\Windows\system32\reset.exe](reset.exe-EDE443A63F4A5914F87DFDC6F8F59697.md) | 75


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## change

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes Remote Desktop Session Host server settings for logons, COM port mappings, and install mode.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

 ```
 change logon
 change port
 change user
 ```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [change logon command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-logon.md) | Enables or disables logons from client sessions on an Remote Desktop Session Host server, or displays current logon status. |
| [change port command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-port.md) | Lists or changes the COM port mappings to be compatible with MS-DOS applications. |
| [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md) | Changes the install mode for the Remote Desktop Session Host server. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


