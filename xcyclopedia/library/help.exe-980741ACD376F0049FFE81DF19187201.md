---
title: help.exe | Command Line Help Utility
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\Windows\system32\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `980741ACD376F0049FFE81DF19187201`
SHA1 | `B07BDA5BC58EB4F1721280709F838BD21C501D90`
SHA256 | `CDCC70D77775A9FADC1D6D70D8C8F0C83D7C9ABDB3507254AF5CBE64C86A3AA1`
SHA384 | `9FC8A59DD2F7616BA733F636A8652404FF235F74CE7C92A4BAB506CFE24CCE34271A27FC17F89475A12F035B2C2380AE`
SHA512 | `1CFCCB42BD15446B5305E9F3801542E48E74966CB2B007D2447E3766F1C45913BDCFCC3D7EC5EAAB73408C89609B16C12477A846222817BEC75A62CB0503D7A2`
SSDEEP | `192:eFN/8LSwljr+GTbpxtPOyYyUdouWib+LGc+31moWMcW:ef/8LS6jC6VWy4d5WhNoWMcW`
IMP | `AC4BF9C2AE25ADA7A4716EBEAF3CC839`
PESHA1 | `7B67A560484AE548F7339E0DBA051BC996654DCB`
PE256 | `543536622AFB1663020F04A75F34CD9BC4B62C1C6EAA8C81B4D97E7C6E41F934`

## Runtime Data

### Usage (stdout):
```cmhg
Provides help information for Windows commands.

HELP [command]

    command - displays help information on that command.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\help.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/cdcc70d77775a9fadc1d6d70d8c8f0c83d7c9abdb3507254af5cbe64c86a3aa1/detection



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


