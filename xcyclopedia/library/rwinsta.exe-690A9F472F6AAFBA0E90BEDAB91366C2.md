---
title: rwinsta.exe | Reset Session Utility
excerpt: What is rwinsta.exe?
---

# rwinsta.exe 

* File Path: `C:\Windows\system32\rwinsta.exe`
* Description: Reset Session Utility

## Hashes

Type | Hash
-- | --
MD5 | `690A9F472F6AAFBA0E90BEDAB91366C2`
SHA1 | `8F4E4A8634D704FD98D6DF491149CDB472BA30AB`
SHA256 | `44B1C84811495B426EC69A15888D5824A894421DF052CC378FD6ADA5C32A112F`
SHA384 | `F2620F7A2ABDB4F8007ED0DF4109384601AC2CA2E780CC4F8948D73D9A743F90AD3F2AF7339A5C91578C43761F65862B`
SHA512 | `764E35D03421B7FE881BCE684FF9754809DDC3A832FDC4B4A3AA7CA5315E4A0BBB62AE40839FB0B39DE117CB8A5A6E584B8B75B3CAB92770CD7E9E4AE30C3C01`
SSDEEP | `384:94dVwndNFFgbG3mrNOO0CLtRrT5tTVZ8pJxkkdmiQUWPhVMcrpXzvWSZW:OdVwBFV2rNOO0C7zVZ8LiydBK9Xzt`
IMP | `ACE7E1CA440DD0C4C63E4D2682CA6E8B`
PESHA1 | `78C34B11537C7F3AE08314AC45EA6CBF152E18F5`
PE256 | `11C6D2AA4E48A81192F168611912278306CF6D6EB5EF843C8860B0854A990D3D`

## Runtime Data

### Usage (stdout):
```cmhg
Reset the session subsytem hardware and software to known initial values.

RESET SESSION {sessionname | sessionid} [/SERVER:servername] [/V]

  sessionname         Identifies the session with name sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server containing the session (default is current).
  /V                  Display additional information.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Reset the session subsytem hardware and software to known initial values.

RESET SESSION {sessionname | sessionid} [/SERVER:servername] [/V]

  sessionname         Identifies the session with name sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server containing the session (default is current).
  /V                  Display additional information.


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rwinsta.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rwinsta.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/44b1c84811495b426ec69a15888d5824a894421df052cc378fd6ada5c32a112f/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## rwinsta

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Resets (deletes) a session on a Remote Desktop Session Host server.

> [!NOTE]
> This command is the same as the [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md).

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Additional References

- [reset session](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md)

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


