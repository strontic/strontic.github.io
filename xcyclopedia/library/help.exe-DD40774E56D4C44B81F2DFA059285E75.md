---
title: help.exe | Command Line Help Utility
---

# help.exe 

* File Path: `C:\Windows\SysWOW64\help.exe`
* Description: Command Line Help Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DD40774E56D4C44B81F2DFA059285E75`
SHA1 | `0461D593E5D7E38319DB5B57EF50EB773BAF8EE2`
SHA256 | `53827A12373901FCA002C3FC012D0BCE0C4AF422A7CF12CAD19C655C903314E3`
SHA384 | `5708BB7372D36795A99C3896FD2ADDB8887E9B63B223BBC3ED35B604A81552C734A512289C701E3926B16505E74D8E2F`
SHA512 | `7D10D778F785B12F62449E2B0D7AFF9A417B00074969AE85B7346196FCE67AAD989A6F81D08462EAA01E06551833DE90241A274A317B6B0745E347B96A1875D2`
SSDEEP | `96:xc7G/+oRECOajYzsp20jvfnDGjshvQluDbX1QJMfgzGDJvkMhd0cSEWMcWw:xc4nECOajY62ypDblQJMfgzKkgWMcW`

## Runtime Data

### Usage (stdout):
```Batchfile
Provides help information for Windows commands.

HELP [command]

    command - displays help information on that command.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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


