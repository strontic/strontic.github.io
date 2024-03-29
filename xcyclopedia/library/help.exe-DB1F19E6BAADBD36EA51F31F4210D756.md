﻿---
title: help.exe | Command Line Help Utility
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\Windows\system32\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `DB1F19E6BAADBD36EA51F31F4210D756`
SHA1 | `B2EDFE4C13455B8683B93FAB63D0C1E1CAFFDD05`
SHA256 | `11863176A0FAD587304C0EE21474DBAA8F40650F34BC47F2666D379BD3A7D7AB`
SHA384 | `84B902BE73C027DAE8C071A1C8EC151F8E91CBCD664B06F23205E7896F2C3C5764A95290A5AA99914096FC5373AC7D54`
SHA512 | `7F0A6DC92768A609ADAE0B4D078316340E9DDB2D3CDF11D4EA5E81D7BDD371A49B181E6FE63A5D26C59D31F0615AA708D305BD2C827289885E37CB5683267CC4`
SSDEEP | `192:iPIFjwNw/KqfEyXAS/+aYUebe51RlwOs8e51woGsxcNzmAWncW:igt+wpc/S+Vtbe74Os8e7LXAWncW`
IMP | `AC4BF9C2AE25ADA7A4716EBEAF3CC839`
PESHA1 | `10FEF7B93DE3020F5DAC610D4E68C0A8491A91AF`
PE256 | `64076DC025E18BD2A5B31F96F7F0465C2646E2D1602ED4663ED279EEBBDBE7A2`

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
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/11863176a0fad587304c0ee21474dbaa8f40650f34bc47f2666d379bd3a7d7ab/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\help.exe](help.exe-80E14A673A0D00E6850E2D60FA4F6E7B.md) | 61


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


