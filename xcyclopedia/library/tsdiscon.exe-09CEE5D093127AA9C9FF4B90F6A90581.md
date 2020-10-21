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
MD5 | `09CEE5D093127AA9C9FF4B90F6A90581`
SHA1 | `B67E776551F3A451F0D5FFBCB6C3A9F096920386`
SHA256 | `4FA837762A3A76BCEE46F7D34F8D2E3E4EA59A0D8F9094A8CA96144E137370F9`
SHA384 | `CA379FD997E16A67B6CA556AE019D26849DADF614E5538E20895B1067A0830AB9ABB80854385E7D542315872C3ED26C3`
SHA512 | `42E1EE5FCFCD638E03F381FADD4E37C9A637D7F42B2156359994A126F1EB428A0BD32BC2977CB8A70865DF915F21E728D1E44DF1F95CF271AFD2ED16D5EE55A0`
SSDEEP | `384:n46XIz3PLC0n2q3ifiljIeUtsT5uXRZ8pB+vJIiQa1TzPPhVMcrwXWMVWW:46XYTClq3ifYjIeZURZ8pBqR5nM3`
IMP | `3FC6BB9BBEE32550C1847BB966FD1F6C`
PESHA1 | `6B46C07FBDBE3CD274C7765A03DF4AB9B4C4475C`
PE256 | `AF9D03DB22FB767F986B5A53C273360E3DB61F1D07BE7D46B6CD03ED4BC771FB`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tsdiscon.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4fa837762a3a76bcee46f7d34f8d2e3e4ea59a0d8f9094a8ca96144e137370f9/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tsdiscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


