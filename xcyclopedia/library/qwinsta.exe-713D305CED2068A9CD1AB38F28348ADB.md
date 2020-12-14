---
title: qwinsta.exe | Query Session Utility
excerpt: What is qwinsta.exe?
---

# qwinsta.exe 

* File Path: `C:\windows\system32\qwinsta.exe`
* Description: Query Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `713D305CED2068A9CD1AB38F28348ADB`
SHA1 | `69FA3CC801397BCFE499C57F1EB7F4C7570E1F8E`
SHA256 | `56272AFAE873484043BF272DDED0DE04FBD4C23704A129550663C425B134EBC2`
SHA384 | `0631A818F4ED248BEAA75409D16FE1420FE2D6749BB58FD78804921D966B74FAB6A91B38E0B9661373EC39D52340B723`
SHA512 | `373B03F4A239430809DF91A7B98B81E5152F9DEA2C16AB0F4698F004EBE90CD93BE7EE5CD5ED88ABC822E96DB49E0DF8E16916A777E6DE01D79C67B6CB352448`
SSDEEP | `768:zMh7G7oGyug+ZJiS9JUcyDjwTfPcf87hrru+GOzf:ghkpikNr3zf`

## Signature

* Status: The file C:\windows\system32\qwinsta.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


