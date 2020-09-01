---
title: reset.exe | Remote Desktop Services Reset Utility
---

# reset.exe 

* File Path: `C:\windows\SysWOW64\reset.exe`
* Description: Remote Desktop Services Reset Utility

## Hashes

Type | Hash
-- | --
MD5 | `965976EEC978470073D538098AD76E48`
SHA1 | `BEE3FE31BBE71733B9C9CA9214CBD3EB1640061C`
SHA256 | `73E255675371774C25AD4717D5564E137EF70B087EC1F4767AB11EBB275328AB`
SHA384 | `00528716A37B52C522E22350B1437C4B28108912A5EE59046ECF77729FDB51CF587CDA6B82452E0B5794D6A537F716BD`
SHA512 | `8A76A91A83338AD57E1A353B024F33AA10404096B6DD79065A15FEE2FF4087E90E506A4686BABDB1740F4148598E2904D161F65D6F4D388530E70F237BC9B339`
SSDEEP | `192:N+3WPiZoUiMuUbyeA7MAPKOK+k9C0X9iTZjtmLsYBMJ9B9QkTk5WZgWqm+:eWPiwOQk9C0X9UxILsgk3E5WZgWX`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\SysWOW64\reset.exe |


## Signature

* Status: The file C:\windows\SysWOW64\reset.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\SysWOW64\change.exe](change.exe-CA35189103A7AF6FA37E42265A0EFBAC.md) | 65
[C:\windows\SysWOW64\query.exe](query.exe-CF07B03F443C3E3062FDFDEF6BDD6E6B.md) | 88


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

- [set command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/set_2.md)

- [load command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-load.md)

- [writer command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/writer.md)

---



MIT License. Copyright (c) 2020 Strontic.


