---
title: reset.exe | Remote Desktop Services Reset Utility
---

# reset.exe 

* File Path: `C:\Windows\system32\reset.exe`
* Description: Remote Desktop Services Reset Utility

## Hashes

Type | Hash
-- | --
MD5 | `FE84BB8BBAA4FA1FD3892BE328E78A3F`
SHA1 | `C4461ABC06352B344ACBB045E8BDB955A7BCF85E`
SHA256 | `0F45EE243CDC2AAEC85DC18B686A86B18D3416729751F273FC094DA0A5BCCF07`
SHA384 | `B6C6C2A02DD2EAD7537B3E7F68415E2C52CAB431DAB33B6EAD84DB6D20DA9B2972863B01A2E3843C356076BCFFC673B5`
SHA512 | `ABB113470F260496E8E905A9C482EA19636A9B2ED3B08B7D5B5B49823E41259CA30B593A687FA146E185CABD7192EFE74281E48AB84A336F556FAE8A474A2EBB`
SSDEEP | `192:/bOsPg02O0EAMuDzEAk3ZsThGdgo8jJIbO4kekhwxxth2GcDKI12m6W7gW:/bO5Z1M/Kg7y2bzyOxth20Cj6W7gW`

## Runtime Data

### Usage (stdout):
```Batchfile
RESET { SESSION }

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
RESET { SESSION }

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\reset.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\change.exe](change.exe-B5A2475E90B9970F16C50D392B9A16BB.md) | 75
[C:\Windows\system32\query.exe](query.exe-29043BC0B0F99EAFF36CAD35CBEE8D45.md) | 75


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


