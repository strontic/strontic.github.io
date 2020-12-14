---
title: qwinsta.exe | Query Session Utility
excerpt: What is qwinsta.exe?
---

# qwinsta.exe 

* File Path: `C:\Windows\system32\qwinsta.exe`
* Description: Query Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `3ED9CCC06AF18EF822E1794FEAEC6183`
SHA1 | `61BB46E5D659EFE16E5C019EABCA1AA1D5CD8F8F`
SHA256 | `08AC265F1888731D6FF54D762FA08B06B172A9424B66CE113AFCEFEF9759C37B`
SHA384 | `7C29FFCF61B450043333A8E3505BFFDA7741F81120377AB6D5E54BF8E71E0038AE51EDE32750BC2467104EE360D19241`
SHA512 | `C07F8FB0CB5FB1C6E81AB7495653373F6D8F6AC4CE49CC04A337155EE22C9987E950F2676BE7B9BBDA94A72B3621BF32E607FBDC96D85ED416820A16B7D003E6`
SSDEEP | `768:HcqOE52Je/1ejPYAtXYpW3yMzXCki7aBzRIHZ8DjO9Dt:HcqOE52J6szYAtX0PZApj+t`
IMP | `D1DB32AE474C00FB7315E2D610E6A740`
PESHA1 | `E59D31CA1B8F0DBC41846330C5184EABFFDC7186`
PE256 | `E42513910BDE8D325A5B0C96194882D1889A1C76DA4EF7E52DA6800EC55187A3`

## Runtime Data

### Usage (stdout):
```cmhg
Display information about Remote Desktop Services sessions.

QUERY SESSION [sessionname | username | sessionid]
              [/SERVER:servername] [/MODE] [/FLOW] [/CONNECT] [/COUNTER] [/VM]

  sessionname         Identifies the session named sessionname.
  username            Identifies the session with user username.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).
  /MODE               Display current line settings.
  /FLOW               Display current flow control settings.
  /CONNECT            Display current connect settings.
  /COUNTER            Display current Remote Desktop Services counters information.
  /VM                 Display information about sessions within virtual machines.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Display information about Remote Desktop Services sessions.

QUERY SESSION [sessionname | username | sessionid]
              [/SERVER:servername] [/MODE] [/FLOW] [/CONNECT] [/COUNTER] [/VM]

  sessionname         Identifies the session named sessionname.
  username            Identifies the session with user username.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).
  /MODE               Display current line settings.
  /FLOW               Display current flow control settings.
  /CONNECT            Display current connect settings.
  /COUNTER            Display current Remote Desktop Services counters information.
  /VM                 Display information about sessions within virtual machines.


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\qwinsta.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/08ac265f1888731d6ff54d762fa08b06b172a9424b66ce113afcefef9759c37b/detection


## Possible Misuse

*The following table contains possible examples of `qwinsta.exe` being misused. While `qwinsta.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_downloader_v3.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_downloader_v3.yml) | `- '\qwinsta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- '\qwinsta.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- qwinsta.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | qwinsta.exe /server:#{computer_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | qwinsta.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | for /F "tokens=1,2" %i in ('qwinsta /server:#{computer_name} ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > computers.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | @FOR /F %n in (computers.txt) DO @FOR /F "tokens=1,2" %i in ('qwinsta /server:%n ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qwinsta

Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about sessions on a Remote Desktop Session Host server. The list includes information not only about active sessions but also about other sessions that the server runs.

> [!NOTE]
> This command is the same as the [query session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-session.md). To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
qwinsta [<sessionname> | <username> | <sessionID>] [/server:<servername>] [/mode] [/flow] [/connect] [/counter]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<sessionname>` | Specifies the name of the session that you want to query. |
| `<username>` | Specifies the name of the user whose sessions you want to query. |
| `<sessionID>` | Specifies the ID of the session that you want to query. |
| /server:`<servername>` | Identifies the rd Session Host server to query. The default is the current server. |
| /mode | Displays current line settings. |
| /flow | Displays current flow-control settings. |
| /connect | Displays current connect settings. |
| /counter | Displays current counters information, including the total number of sessions created, disconnected, and reconnected. |
| /? | Displays help at the command prompt. |

##### Remarks

- A user can always query the session to which the user is currently logged on. To query other sessions, the user must have special access permission.

- If you don't specify a session using the <*username*>, <*sessionname*>, or *sessionID* parameters, this query will display information about all active sessions in the system.

- When **qwinsta** returns information, a greater than `(>)` symbol is displayed before the current session. For example:

    ```
    C:\>qwinsta
        SESSIONNAME     USERNAME        ID STATE    TYPE    DEVICE
        console         Administrator1  0 active    wdcon
        >rdp-tcp#1      User1           1 active    wdtshare
        rdp-tcp                         2 listen    wdtshare
                                        4 idle
                                        5 idle
    ```

    Where:
  - **SESSIONNAME** specifies the name assigned to the session.
  - **USERNAME** indicates the user name of the user connected to the session.
  - **STATE** provides information about the current state of the session.
  - **TYPE** indicates the session type.
  - **DEVICE**, which isn't present for the console or network-connected sessions, is the device name assigned to the session.
  - Any sessions in which the initial state is configured as DISABLED won't show up in the **qwinsta** list until they're enabled.

#### Examples

To display information about all active sessions on server *Server2*, type:

```
qwinsta /server:Server2
```

To display information about active session *modeM02*, type:

```
qwinsta modeM02
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-session.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


