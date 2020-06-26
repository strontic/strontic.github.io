---
title: bootcfg.exe | BootCfg - Lists or changes the boot settings.
---

# bootcfg.exe 

* File Path: `C:\WINDOWS\system32\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DDAAFCC28EE660A1508007E7E4AC142B`
SHA1 | `74F8E49C2437329538DDB9F948AA84548DCD6FAE`
SHA256 | `3715EB1F20F2CA944DFB2F211A4430CB3BD82A65A63606381D19760933F7DCD5`
SHA384 | `36ED1B4598E7E7D7F91D71C3459006B339935847A2C71EBFB79D2D6FE8CB92B5438D128FEBF06628472A3D7DABFE7F47`
SHA512 | `B6B43580C326BB613569D4AB63868F6EAACBCB4B97C359AC96E27A3969C9B4EF3E69A75A3FF7F57EB4491B55DE558768F78B3813899468A3CF6621D5A41A14B1`
SSDEEP | `1536:b8Ysh0ZSHZ+WpvSN/v3bDCaCGmMtpfTnJQP+WU5tFa+U1:bfSIWpvS5CjaprK+WKtFa+Y`

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

### Child Processes:


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
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


