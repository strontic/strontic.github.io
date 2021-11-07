---
title: qwinsta.exe | Query Session Utility
excerpt: What is qwinsta.exe?
---

# qwinsta.exe 

* File Path: `C:\windows\SysWOW64\qwinsta.exe`
* Description: Query Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `E1897B83712DC560D57BA19D8A410C08`
SHA1 | `D897D50C10EE6B1BAA36AA46BD63157328A6F29D`
SHA256 | `33E0694012804397159C9E4634DD749D497DE5A47C6DDC805510EDB2E7F222DC`
SHA384 | `99E4265A4CF7F5197C8B8B6FE2FABD1762A46186E1107758D98E2AC9187B8FCEF338B1B4B95377ABDD42C55DE53C4117`
SHA512 | `16DFC6173BDF48166CE197A38C79EE1C8D11A882409353D43287402A9EBA46438A739AFA81D65E8F6AC6C85D112E155C0B233E8330D4E00E947FE861971B86DA`
SSDEEP | `384:swmaU5mfH3l+imbguEAYx9wf3+xoxan5a0XIZvalid0vr+P7WI6Wd04m:CaU5UXlibgDAK1u9PfLm`

## Signature

* Status: The file C:\windows\SysWOW64\qwinsta.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: qwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `qwinsta.exe` being misused. While `qwinsta.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_downloader_v3.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_downloader_v3.yml) | `- '\qwinsta.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- '\qwinsta.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- qwinsta.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | qwinsta.exe /server:#{computer_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | qwinsta.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | for /F "tokens=1,2" %i in ('qwinsta /server:#{computer_name} ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > computers.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | @FOR /F %n in (computers.txt) DO @FOR /F "tokens=1,2" %i in ('qwinsta /server:%n ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qwinsta

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020-2021 Strontic.


