---
title: tskill.exe | Remote Desktop Services End Process Utility
excerpt: What is tskill.exe?
---

# tskill.exe 

* File Path: `C:\Windows\system32\tskill.exe`
* Description: Remote Desktop Services End Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `2393D4F762FB671D92A59388109C24D4`
SHA1 | `2E27346B7CFF97619923C3E3199E68E7B91D142B`
SHA256 | `8D9373EBD69F42153B0B47DBDA2174811599DB91630651CA01627AC1795F8D56`
SHA384 | `11EA7C57DEE31D5E8F16B92DECAE49DBF05CD925C6A48E0B3F21E4794541CF48D0E573A72C64AE525A739D2CFA0B3FDC`
SHA512 | `9EAA9CD2813F8864244547FBC81BA6759F63E32F73ED2394DFA311FF60A9727E47DBDCF42D1AAFB5E6C5A40A43A83AE32F5FA443083319F5B6B1E73457C59758`
SSDEEP | `768:+IPzZhZGDotUMCZvNvNZ8LYIPxCHxCH9kG:+IjEVdJ6YIwYGG`
IMP | `0568AF4DCDD3B8A976BBBBC1530C6847`
PESHA1 | `FF78CF970784C966AB172C14A049A81DDB745490`
PE256 | `9E3FCE0B4154C5F94855B65FB926B6F19C96339DF235F2F1DC0B5A9A801EC0C4`

## Runtime Data

### Usage (stderr):
```cmhg
Invalid parameter(s)
Ends a process.

TSKILL processid | processname [/SERVER:servername] [/ID:sessionid | /A] [/V]

  processid           Process ID for the process to be terminated.
  processname         Process name to be terminated.
  /SERVER:servername  Server containing processID (default is current).
                         /ID or /A must be specified when using processname
                         and /SERVER
  /ID:sessionid       End process running under the specified session.
  /A                  End process running under ALL sessions.
  /V                  Display information about actions being performed.


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tskill.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/8d9373ebd69f42153b0b47dbda2174811599db91630651ca01627ac1795f8d56/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tskill

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends a process running in a session on a Remote Desktop Session Host server.

> [!NOTE]
> You can use this command to end only those processes that belong to you, unless you are an administrator. Administrators have full access to all **tskill** functions and can end processes that are running in other user sessions.
>
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
tskill {<processID> | <processname>} [/server:<servername>] [/id:<sessionID> | /a] [/v]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<processID>` | Specifies the ID of the process that you want to end. |
| `<processname>` | Specifies the name of the process that you want to end. This parameter can include wildcard characters. |
| /server:`<servername>` | Specifies the terminal server that contains the process that you want to end. If **/server** isn't specified, the current Remote Desktop Session Host server is used. |
| /id:`<sessionID>` | Ends the process that is running in the specified session. |
| /a | Ends the process that is running in all sessions. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- When all processes that are running in a session end, the session also ends.

- If you use the `<processname>` and the `/server:<servername>` parameters, you must also specify either the `/id:<sessionID>` or the **/a** parameter.

### Examples

To end process 6543, type:

```
tskill 6543
```

To end the process explorer running on session 5, type:

```
tskill explorer /id:5
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


