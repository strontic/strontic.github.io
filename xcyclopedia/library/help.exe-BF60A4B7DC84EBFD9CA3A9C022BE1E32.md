---
title: help.exe | Command Line Help Utility
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\Windows\SysWOW64\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `BF60A4B7DC84EBFD9CA3A9C022BE1E32`
SHA1 | `D84D0ED9DC7722AA50B9CC0C3D49C6264DD36358`
SHA256 | `09948762942FC066EB07C479FA49B63F3CFF299AF2EE8256904BA9B098EC50DF`
SHA384 | `082DAD3C71D64E1D0A9E8D4A71DFA942A1A3CCD7093AB589E5C948277915D29A18849E507F0FA582BEAD8ADF603C1F2E`
SHA512 | `2E2E727AA539EDE54C7CFF92C984C025D6BD9E76816D51FA013AF5C5F30DE0F4B573D77E3E7052FCA1C1279CBDDC2F67483222F0728D5AF9A3BE7036F0F39DC3`
SSDEEP | `192:uEAbwN3O1nvZ7O183isM2WRfCkYWncWv9:l7gvZ7O18srYWncWv9`
IMP | `611805A7C3221EBB521E87BF9182D982`
PESHA1 | `701BC1CD855FC082801682A665454CD0A995D437`
PE256 | `3B9544072A357D1121002FD664013EBD23ED3A5C3F00184DA36928AB991C8041`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\help.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/09948762942fc066eb07c479fa49b63f3cff299af2ee8256904ba9b098ec50df/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\help.exe](help.exe-C55299D0BE2430DD0EF426CD072CC0C7.md) | 43


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


