---
title: help.exe | Command Line Help Utility
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\WINDOWS\SysWOW64\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `C55299D0BE2430DD0EF426CD072CC0C7`
SHA1 | `BB128766206BDF91B669E8113BA6EFAAFE36FB9B`
SHA256 | `419C5215958DAAA3F4E47684DD104413831DBC0F273CBFD6501E8F2153B7CE07`
SHA384 | `164C4A787190D5D769486CE482EE4FBE8DBDD141E76153346860C876535E641DFD215CF77C5B6BB44BC33D65AA50946A`
SHA512 | `8D4127430FB54E2BA1B07FECC904BAA1900118B932C20FB800A6EF67271A1E6EF98B7809834D98A52F7C3B3B8E0C0FBD59C65FE1301BA27E7EE183024593A14D`
SSDEEP | `192:YuVkWfO6zY6WypD7VE3isM2WRqkoWdcWiH:Ysj7zBWy1VEs7oWdcWiH`

## Runtime Data

### Usage (stdout):
```cmhg
Provides help information for Windows commands.

HELP [command]

    command - displays help information on that command.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\help.exe](help.exe-BF60A4B7DC84EBFD9CA3A9C022BE1E32.md) | 43


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



MIT License. Copyright (c) 2020-2021 Strontic.


