---
title: help.exe | Command Line Help Utility
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\WINDOWS\system32\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `427289C85B8E929AE31D7691A876DDD7`
SHA1 | `40150F0106384E985E69E130C7E99EE59D56CFB0`
SHA256 | `3BAC7F4C58D01D7A72E54A19A46EF05BC8A5558C49368E2BB97C82DF4B847925`
SHA384 | `116045402984F8B946C85EDE7DEC7D2D56A21026323297A63B394283DEDAFB6B7FD51B4A5B8E406BC6A9EBA0315A8BD8`
SHA512 | `5C4AECF31E247DF90D45C1A4A4DAA14E448D4C98D0AFED6566933597B2EA2EB9AA7F949FEB7D6D8DC6201335D9F2C2CEF47EB2D655B07955A8711DEF09DEDAE1`
SSDEEP | `192:M7v65M6Oz61nHrpoLz7l/Nef98EP2tPYPxAvmQWDcW:wv8V66JLpoLz7l1ef9jO0ueQWDcW`
IMP | `AC4BF9C2AE25ADA7A4716EBEAF3CC839`
PESHA1 | `B1114CFF894484B7C0CC25956B742C9151BBBC96`
PE256 | `BDE51DBC71DD4FC27F73D1E097FBDA4CFEF983B3B17571DCE879DED9D7F4CA9B`

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
C:\WINDOWS\system32\help.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3bac7f4c58d01d7a72e54a19a46ef05bc8a5558c49368e2bb97c82df4b847925/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## help

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


