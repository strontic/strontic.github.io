---
title: bootcfg.exe | BootCfg - Lists or changes the boot settings.
---

# bootcfg.exe 

* File Path: `C:\Windows\system32\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.

## Hashes

Type | Hash
-- | --
MD5 | `580B143C690E8921E365943B935C7854`
SHA1 | `921FAFCACF782D85C68122511CC748C3DF94B454`
SHA256 | `BE45A65C9A57A9B47B2656C057230D0C37C18299761AF5DBB24EE5DCE2429EC5`
SHA384 | `98D377B8B6A89336872951B5B16D89338A7CA90383575DEAE76D05CF7426245E369C25FC22E7DBAE150A3B7319DC824A`
SHA512 | `9ACA418370E5978848637003C64A4B5FF7457B7447EFAB9384AA0F5397E24A225DD25C3E5835DABF725304750B26620F13E819D6F2AF77F5F1E6BDEA1F4D4980`
SSDEEP | `1536:rijQlcYBI2AlQM8yBTSCUiC4dTLFjJwpH/sy0OJQv+KE5PFa+ctf:rijBlQZu+/iCYJwpH0p3+KaPFa+cp`

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

### Loaded Modules:

Path |
-- |
C:\Windows\system32\bootcfg.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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


