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
MD5 | `C00C091EF0328E92268E0D00616A3EBF`
SHA1 | `6C055BA88914125BCBB67716093EF1C10548380A`
SHA256 | `368F9DE5F9198EB8FD3CD057D8FF0943993B53D6A021AA23224EC8026B71B755`
SHA384 | `3B417271FFC6F5301627320AD2338C7A26EE8151C49FED082B61065B1BFB6062A3C75E0036C91C3EA35A96A36CDA3AFC`
SHA512 | `1354FDA02F05A69C9BBA711E20780E8BCA2DA93F07B781D0D0C8044A068B2275B98493CB698C256C046708F626420B6BBB70A1F8487EBE1181F89703EB68BAE8`
SSDEEP | `96:Rk0vnD8mP+QOikMsR2BWhFDWzshd2tGSR1pEoWbg9DFhDJvkMhd0cebEWDcWwXxX:RkcDdNOFFG/Xj+oWbg9DFTkoWDcWU1`
IMP | `611805A7C3221EBB521E87BF9182D982`
PESHA1 | `C457AD3186EB9F54F5172794A8A5693BF63D8B8D`
PE256 | `A1222B6EEC8B95E0FAC79F3725DD0C7DA8933D01ED8D19E6BFA01BE68D3A2302`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\help.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Help.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/368f9de5f9198eb8fd3cd057d8ff0943993b53d6a021aa23224ec8026b71b755/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\help.exe](help.exe-DD40774E56D4C44B81F2DFA059285E75.md) | 40


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


