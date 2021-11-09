---
title: change.exe | Remote Desktop Services Change Utility
excerpt: What is change.exe?
---

# change.exe 

* File Path: `C:\WINDOWS\system32\change.exe`
* Description: Remote Desktop Services Change Utility

## Hashes

Type | Hash
-- | --
MD5 | `AD2E958EB48DEDD31378C710CE93FFD2`
SHA1 | `9A14FFFC28E1F41AA79BB98D2937F29F4635EE78`
SHA256 | `D5150CE8166B97F76916FFE2683CA99B293E4AE8E450C14EA2031A7A767F3B9A`
SHA384 | `ACE969A96787F7E8D3E7F00D61D29D3756A8EC02071A21E198DD1F2C70D240346F899291252CB16A02175D3F1857BE3A`
SHA512 | `99AC1DED404619232AC4C49459BDBF6D12FA87BEEFF6607A7B6D65953DCEC7590C2FAA1F4BAA9F5D27F192525C8B146E1D13DCF97BF8503F0F0437EF89DD1CD7`
SSDEEP | `384:Qw7SbB9BPsgulSQ8jWqUTevqhITHVXWdLW:j7SPsg68yqUT41K`
IMP | `CCC9DA4A55E90DFE34CBCDB066D6A6B3`
PESHA1 | `3FCB622A2E9DDFA8341E0140F73C631239621464`
PE256 | `16D6FA3DEE44396BC143E1FAE259C1E270E04BBD07E53A5D8CC9B4E4224B51CC`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\change.exe |
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

* Original Filename: change.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/d5150ce8166b97f76916ffe2683ca99b293e4ae8e450c14ea2031a7a767f3b9a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\query.exe](query.exe-198E5A25B3F577F5E7C86F3A94909686.md) | 77
[C:\WINDOWS\system32\reset.exe](reset.exe-B0D8D2D8EB90ABE47C3EBF24E0832390.md) | 72


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## change

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020-2021 Strontic.


