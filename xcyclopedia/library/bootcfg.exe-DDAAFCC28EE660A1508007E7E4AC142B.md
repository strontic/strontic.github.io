
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
SHA415 | `B6B43580C326BB613569D4AB63868F6EAACBCB4B97C359AC96E27A3969C9B4EF3E69A75A3FF7F57EB4491B55DE558768F78B3813899468A3CF6621D5A41A14B1`
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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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

MIT License. Copyright (c) 2020 Strontic.


