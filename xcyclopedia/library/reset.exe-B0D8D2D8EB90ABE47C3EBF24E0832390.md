---
title: reset.exe | Remote Desktop Services Reset Utility
excerpt: What is reset.exe?
---

# reset.exe 

* File Path: `C:\WINDOWS\system32\reset.exe`
* Description: Remote Desktop Services Reset Utility

## Hashes

Type | Hash
-- | --
MD5 | `B0D8D2D8EB90ABE47C3EBF24E0832390`
SHA1 | `227862EEFEE12B28C626C19A9C8CDFCE4A50A211`
SHA256 | `12644C9866833DCCF8F462044AC8AEDCBB4AB5FCD78EFB82C356D0CE57266243`
SHA384 | `49AB18E9D66428363BFB585D98AB6D08D39C3587294E191D2A4B94ED0C9A26B8A8EAA03EC577BC79B85BB4ED4720539B`
SHA512 | `6B88B173C75B2DB5E57B1481F9C70AEB65C8F6BF89267323D0721B4AF90ED3D4753B9C836C1AA7B3193CDC0F5C55933A554CCFFFE1E53AC1A3BF018B08FDFE93`
SSDEEP | `384:Rw7SbB9BPBb6lSQ8jWqUNvqhITHYyW0gW:a7SPBbW8yqUJ4A`
IMP | `CCC9DA4A55E90DFE34CBCDB066D6A6B3`
PESHA1 | `0FE1DC36359FEF0BA9D66FDD00F4262D46FEDB3F`
PE256 | `A940E2214F127EB546C6AB1ED26BCD9F2558D69452104ECD08FE1EA1C87A19A2`

## Runtime Data

### Usage (stdout):
```cmhg
RESET { SESSION }

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
RESET { SESSION }

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\reset.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/12644c9866833dccf8f462044ac8aedcbb4ab5fcd78efb82c356d0ce57266243/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\change.exe](change.exe-AD2E958EB48DEDD31378C710CE93FFD2.md) | 72
[C:\WINDOWS\system32\query.exe](query.exe-198E5A25B3F577F5E7C86F3A94909686.md) | 72


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## reset

Resets DiskShadow.exe to the default state. This command is especially useful in separating compound DiskShadow operations, such as **create**, **import**, **backup**, or **restore**.

> [!IMPORTANT
> After you run this command, you will lose state information from commands, such as **add**, **set**, **load**, or **writer**. This command also releases IVssBackupComponent interfaces and loses non-persistent shadow copies.

### Syntax

```
reset
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [create command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/create.md)

- [import command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/import_1.md)

- [backup command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-backup.md)

- [restore command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-restore.md)

- [add command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/add.md)

- [set command](./set.md)

- [load command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-load.md)

- [writer command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/writer.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


