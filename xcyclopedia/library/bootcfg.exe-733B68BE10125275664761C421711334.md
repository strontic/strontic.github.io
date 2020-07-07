---
title: bootcfg.exe | BootCfg - Lists or changes the boot settings.
---

# bootcfg.exe 

* File Path: `C:\windows\system32\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `733B68BE10125275664761C421711334`
SHA1 | `43BDA398E0A6579CFAB22E61D3AE3DAB0C110193`
SHA256 | `ECA71E18BA0112E834AFA9AB087A3EF25431D720B3499EB790D069EBFC5138DF`
SHA384 | `B47459AEA6AC24E7A5E17F7A7A7018C329738A8819B63477D6ED050A0CC8D93D1299A862F06D4CD20763879AF3BA85C5`
SHA512 | `9CF9981C382A81485EA85B6F1E93118E4DB8FFEA3DD1BDA3047BB8294B20343E07AE2209149B9B8E443076D8D8E16B16C9A24844C663191B33EBBDEC459F1584`
SSDEEP | `1536:IxYILbDSbTjQO6MfyClGk2edS6nESsKetHWzaF5GE6nIYluCfhzL+e6LeNOKO0xK:KsTjQO5Zlx2edS6ESsKeAU5NgTjJ+3k0`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\bootcfg.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: bootcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## bootcfg

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Configures, queries, or changes Boot.ini file settings.

### Syntax

```
bootcfg <parameter> [arguments...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [bootcfg addsw](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-addsw.md) | Adds operating system load options for a specified operating system entry. |
| [bootcfg copy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-copy.md) | Makes a copy of an existing boot entry, to which you can add command-line options. |
| [bootcfg dbg1394](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-dbg1394.md) | Configures 1394 port debugging for a specified operating system entry. |
| [bootcfg debug](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-debug.md) | Adds or changes the debug settings for a specified operating system entry. |
| [bootcfg default](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-default.md) | Specifies the operating system entry to designate as the default. |
| [bootcfg delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-delete.md) | Deletes an operating system entry in the [operating systems] section of the Boot.ini file. |
| [bootcfg ems](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-ems.md) | Enables the user to add or change the settings for redirection of the Emergency Management Services console to a remote computer. |
| [bootcfg query](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-query.md) | Queries and displays the [boot loader] and [operating systems] section entries from Boot.ini. |
| [bootcfg raw](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-raw.md) | Adds operating system load options specified as a string to an operating system entry in the [operating systems] section of the Boot.ini file. |
| [bootcfg rmsw](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-rmsw.md) | Removes operating system load options for a specified operating system entry. |
| [bootcfg timeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bootcfg-timeout.md) | Changes the operating system time-out value. |

---



MIT License. Copyright (c) 2020 Strontic.


