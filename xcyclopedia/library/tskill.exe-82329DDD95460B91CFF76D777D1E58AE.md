---
title: tskill.exe | Remote Desktop Services End Process Utility
excerpt: What is tskill.exe?
---

# tskill.exe 

* File Path: `C:\Windows\SysWOW64\tskill.exe`
* Description: Remote Desktop Services End Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `82329DDD95460B91CFF76D777D1E58AE`
SHA1 | `9AA945C68B86243F7B075DA3393016F721272D64`
SHA256 | `7468A5DD894AD3B4EAB0CFB10ACF6347336356038EC9446ED3C15862088E4849`
SHA384 | `5225BB3E6166F781206F42E3144733DB658CD6302052BF819807E00876A8CF765C35D9D855A08C8789F3E9549E0178E9`
SHA512 | `F48DDBBA460BCB96987811EF6EAD67E4918B3254B9B2010CDA216A0A7F7D40B44F5356F7922E865BEEB4F88373BE8E29E1E4D94BB2DF1C7183839A47CAFA27F0`
SSDEEP | `384:gR2sOSALmDLzWsch/kWv3t9SDqBVEE9e4A/If27dSW4wQW:ToALmDP6/HwgB2Bx`
IMP | `82DB08E0613BAB949E41C09B91D85B62`
PESHA1 | `8770B80B6947C091E883248C5E840FF8C3153682`
PE256 | `97193706ED6A0A496AD1184A45807D0463BA81713F8277093008262873E74059`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tskill.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7468a5dd894ad3b4eab0cfb10acf6347336356038ec9446ed3c15862088e4849/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tskill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


