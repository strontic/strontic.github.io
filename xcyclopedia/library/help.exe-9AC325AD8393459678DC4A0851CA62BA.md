---
title: help.exe | Command Line Help Utility
---

# help.exe 

* File Path: `C:\Windows\SysWOW64\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `9AC325AD8393459678DC4A0851CA62BA`
SHA1 | `7A76169F56A5EDB4BAA3A3A302EFE3E5D9DB3535`
SHA256 | `35D0C29DD223F03C58906A00B5CE3C1BE7FBDB493A8A4C9F4849B9B8C6E2DF80`
SHA384 | `92C3D5BAFA4957EB53F71DAB07828014C777BA49174E895FCD1C6779C9B3DE4D7DCDDEBA8296DAA539114D8C5A5DB6B6`
SHA512 | `918A6E2FBC73298FE08D35633CACD2A4943CF5D793008FB0F581FE3980B20F92B1DEEA9199DE283803B72B242FCAE768FC04D482BD35169ECAD7D20C38BBB75F`
SSDEEP | `192:gF5KNOSXvL9tT7DNV2qMAQckgWjcWfsb+z0:VFXvL39Va5gWjcW0F`

## Runtime Data

### Usage (stdout):
```Batchfile
Provides help information for Windows commands.

HELP [command]

    command - displays help information on that command.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## help

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of the available commands or detailed help information on a specified command. If used without parameters, **help** lists and briefly describes every system command.

### Syntax

```
help [<command>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies the command for which to display detailed help information. |

#### Examples

To view information about the **robocopy** command, type:

```
help robocopy
```

To display a list of all commands available in DiskPart, type:

```
help
```

To display detailed help information about how to use the **create partition primary** command in DiskPart, type:

```
help create partition primary
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


