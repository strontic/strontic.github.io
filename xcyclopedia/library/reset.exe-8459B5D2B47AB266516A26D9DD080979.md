---
title: reset.exe | Remote Desktop Services Reset Utility
---

# reset.exe 

* File Path: `C:\Windows\SysWOW64\reset.exe`
* Description: Remote Desktop Services Reset Utility

## Hashes

Type | Hash
-- | --
MD5 | `8459B5D2B47AB266516A26D9DD080979`
SHA1 | `71614B0B7D2B57E3FA63AFF933781415F2A3D54C`
SHA256 | `EF8641FDCBC876E51CEAA2FFF825D3E25A57B8694433FFF58588A6F35FA17908`
SHA384 | `FB45813646F3DB2EF0B3280EB445F2ECE99BBE1EB4E89EDF0D8AB5CF9F3E26DBC4D183DD182FFB4D4AA97CE2C929D9D3`
SHA512 | `6F2EB544B32C8AF136C722B8EE608CD4B23B17BC4022E765F352D8EA6507D0D6DD434CBCF16D3CA717125807D7F1CE274178E23392A96B636AFBB094565AEBE4`
SSDEEP | `192:1YzogF5/eyf1wzT4Fce1pN/1mt2Wco5kqWQgWF8:sVDGyf1wzT4ieh/1qlOqWQgW`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\SysWOW64\reset.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\change.exe](change.exe-582214B45CA2404BE73109AE47A8A6C7.md) | 54
[C:\Windows\SysWOW64\query.exe](query.exe-BCB053556213C5755EAEF97D2F68BF0C.md) | 82


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


