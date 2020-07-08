---
title: help.exe | Command Line Help Utility
---

# help.exe 

* File Path: `C:\windows\system32\help.exe`
* Description: Command Line Help Utility

## Hashes

Type | Hash
-- | --
MD5 | `50856FEA062AABFC1EC05A06CB94C9A0`
SHA1 | `2779F5FD74F3778779B1A07D49115DBE74D74937`
SHA256 | `9397EA5962B20BFF5E3648489686825EBF9F774443CD21D7AE2200D0C49DF45A`
SHA384 | `1098472114DA6D6D20A502F3A6EF5ACD77DAF48E9FD0C6F6D29E224B98367EA901CBC3233B279379133E09BB9E8AC63A`
SHA512 | `73E32E0CC505D60B5107747681EDA18DF5CEF25E194A5B44620FF5FAA6FC0F23EB00CB56BAACD1D12751E829F5E468583CF335EC4C7229658F6F7E5B64154696`
SSDEEP | `192:bHz1DjPwQP9T2CoLptpZ72zU4dG3AGT6x4eA08EQmwW6cW2:bHz1DnP9CxDL/Zs4eQUwW6cW2`

## Signature

* Status: The file C:\windows\system32\help.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Help.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


