---
title: quser.exe | Query User Utility
excerpt: What is quser.exe?
---

# quser.exe 

* File Path: `C:\Windows\system32\quser.exe`
* Description: Query User Utility

## Hashes

Type | Hash
-- | --
MD5 | `6309F1482DAB3BDE91074316892BDCA7`
SHA1 | `02FF8CF4670F02626DF7FD9868751819A402AF84`
SHA256 | `CCFAF494E520E4F265AD1DE5252979809F1A28EB002F0E79C52981B00E63AC4F`
SHA384 | `0495B01968C28A67BC6B7183F631342CE94127C69889C2068984AE0E58BB6D9C16230497F5A30CE81EAA6EEE12E072C2`
SHA512 | `C3AFEF77938B7E21A0438F9D06A65680EED07038314D7C7B7D3DF5ACD536EBF9CCFDBB3A4D02237FF09634E8855003AC1C3E291A95A15AF4FF45BE44B68548FB`
SSDEEP | `768:WdcgSIZE45pVrLSoYMmWyDwK89SaAY9JxxXp:69SgVrqySaAYpxXp`
IMP | `EA8421BD383CD44D7C13D5BBB67DDFA5`
PESHA1 | `1BD4DE1A2F2CAC59060157D895D8850BBA1C074C`
PE256 | `A34E9C89FA4240FDB6BA99DE94BEEE3DE7A7E4A76F021266ED900E1DE0B9877A`

## Runtime Data

### Usage (stdout):
```cmhg
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\browcli.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logoncli.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\quser.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\samcli.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\system32\srvcli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UTILDLL.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: quser.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ccfaf494e520e4f265ad1de5252979809f1a28eb002f0e79c52981b00e63ac4f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\quser.exe](quser.exe-3147F9B0C7089DD698778246E835C494.md) | 80

## Possible Misuse

*The following table contains possible examples of `quser.exe` being misused. While `quser.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- '\quser.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- quser.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\quser.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | quser /SERVER:"#{computer_name}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | quser | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## quser

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about user sessions on a Remote Desktop Session Host server. You can use this command to find out if a specific user is logged on to a specific Remote Desktop Session Host server. This command returns the following information:

- Name of the user

- Name of the session on the Remote Desktop Session Host server

- Session ID

- State of the session (active or disconnected)

- Idle time (the number of minutes since the last keystroke or mouse movement at the session)

- Date and time the user logged on

> [!NOTE]
> This command is the same as the [query user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md). To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
quser [<username> | <sessionname> | <sessionID>] [/server:<servername>]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<username>` | Specifies the logon name of the user that you want to query. |
| `<sessionname>` | Specifies the name of the session that you want to query. |
| `<sessionID>` | Specifies the ID of the session that you want to query. |
| /server:`<servername>` | Specifies the Remote Desktop Session Host server that you want to query. Otherwise, the current Remote Desktop Session Host server is used. This parameter is only required if you're using this command from a remote server. |
| /? | Displays help at the command prompt. |

##### Remarks

- To use this command, you must have Full Control permission or special access permission.

- If you don't specify a user using the <*username*>, <*sessionname*>, or *sessionID* parameters, a list of all users who are logged on to the server is returned. Alternatively, you can also use the **query session** command to display a list of all sessions on a server.

- When **quser** returns information, a greater than `(>)` symbol is displayed before the current session.

#### Examples

To display information about all users logged on the system, type:

```
quser
```

To display information about the user *USER1* on server *Server1*, type:

```
quser USER1 /server:Server1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


