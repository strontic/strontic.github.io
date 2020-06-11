
# bootcfg.exe 

* File Path: `C:\Windows\system32\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DE200E259184C1E27A46A273826F4598`
SHA1 | `5A687E4901E1E09405239BEFB7745CC9A121D286`
SHA256 | `D788BE82341083FEFB8320CCC9F88CDEC21F9CD5582125AF4FEFBC441FD9A748`
SHA384 | `015C1EC93785398CD20351EA5337B7A8EEF24AE1AA7CE522FB91664354CB26113026E8E970487882935F92446034C22C`
SHA415 | `7B8654D2AE8679FDDB4B788DCE234B386E5DF36E8C86879499425C1AE1E8C6C8BB2719E4F6B3F00FB2D6A7DA407AB77C835F68C9F4BDE242D87A38326F12F202`
SSDEEP | `1536:M8P7Mxh11crAug4IRLeC0byqklCLzaAx+DVmsJQuutas7PTa:y711cEX4F/b48uAMxmtas7ra`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


