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
MD5 | `ECB28BE6AB10EC79A0E817A27F9AA6DD`
SHA1 | `2D2F4442D825FBF47E9D4081738211BB2C6532D7`
SHA256 | `56E8D6C41D904C855FC44BC50E7460AC0D1803111C0C8032B12C00B3C0482816`
SHA384 | `4D7843AA7B77A4F52EB5E82946722A9C5BD87F2B88F22B8FF7FD6F39DB6C95E98AD9D83042574EB0D864C7C0C43A5015`
SHA512 | `06DD864E107E835100F31E20EE32D70600E1914A9F017D90EF6A7C183EC735C50F10D55F2351781B9212C64FA8FE12D556585EAA26BFDFE66D32845382540EC5`
SSDEEP | `384:i3siK/v9kWMiajErDSPVQgE4z5mtpBK8bgqKl4uwkU2oTAUHWqSUZp51wCW4wQW:i8Ph9TrDS9QwA7BK8brKZwPXAQLIB`
IMP | `0568AF4DCDD3B8A976BBBBC1530C6847`
PESHA1 | `BC46D5579AE3FE633C2B78747A394F1E44774575`
PE256 | `C48509A6853221E7E4C85BB8CEEA7D09D6D0FD420C4835624275638B1CDF455D`

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
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tskill.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/56e8d6c41d904c855fc44bc50e7460ac0d1803111c0c8032b12c00b3c0482816/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\tskill.exe](tskill.exe-6E732DAB005F94B46D56DF34B5EF7D85.md) | 47


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


