---
title: bootcfg.exe | BootCfg - Lists or changes the boot settings.
---

# bootcfg.exe 

* File Path: `C:\Windows\system32\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.

## Hashes

Type | Hash
-- | --
MD5 | `EC92EDA497062006DCFC1D200DFD8C97`
SHA1 | `1DDFD9E8224E4CCF18C6F6DAE69DD7D8655D6716`
SHA256 | `3AE4009D8722649281C1F352CFD65186198FC6EE8FD62B436869789F8D06D348`
SHA384 | `897545988520D78C56B5392E232E650A47795C5DFE8C14573BE0E2B6A86B010AD6A40306E0F6589505125C61E139D14E`
SHA512 | `82E9A336BC5ADEF11914C04FB94589BF24AB0123757F502F854CEC3578BF242E149714F0EB74961B9BFBC7A83D37A701546DB4D4EB029694AA64CE9E70F0533B`
SSDEEP | `1536:XKHR/57Ggj0+HPJwQWifFLAAHV1eH1OCUUjgnO18JQy+u5sFa+I38s:MpNDB/JRAt1OCUUxe+UsFa+Ix`

## Runtime Data

### Usage (stdout):
```Batchfile

BOOTCFG /parameter [arguments]

Description:
    This command line tool can be used to configure, query, change or 
    delete the boot entry settings in the BOOT.INI file.

Parameter List:
    /Copy       Makes a copy of an existing boot entry.

    /Delete     Deletes an existing boot entry from the BOOT.INI file.

    /Query      Displays the current boot entries and their settings.

    /Raw        Allows the user to specify any switch to be added.

    /Timeout    Allows the user to change the Timeout value.

    /Default    Allows the user to change the Default boot entry.

    /EMS        Allows the user to configure the /redirect switch
                for headless support.

    /Debug      Allows the user to specify the port and baudrate for 
                remote debugging.

    /Addsw      Allows the user to add predefined switches.

    /Rmsw       Allows the user to remove predefined switches.

    /Dbg1394    Allows the user to configure 1394 port for debugging.

    /?          Displays this help message.

Examples:
    BOOTCFG /Copy /?
    BOOTCFG /Delete /?
    BOOTCFG /Query /?
    BOOTCFG /Raw /?
    BOOTCFG /Timeout /?
    BOOTCFG /EMS /?
    BOOTCFG /Debug /?
    BOOTCFG /Addsw /?
    BOOTCFG /Rmsw /?
    BOOTCFG /Dbg1394 /?
    BOOTCFG /Default /?
    BOOTCFG /?

WARNING: BOOT.INI is used for boot options on Windows XP and earlier
         operating systems.  Use the BCDEDIT command line tool to modify
         Windows Vista boot options.

```

### Usage (stderr):
```Batchfile
ERROR: Invalid syntax.
Type "BOOTCFG /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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


