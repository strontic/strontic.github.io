
# bootcfg.exe 

* File Path: `C:\Windows\SysWOW64\bootcfg.exe`
* Description: BootCfg - Lists or changes the boot settings.
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E5B1E1FD8CE4B20B80DA6DC411AB196A`
SHA1 | `D643EA0672F511C7CAA5497C86A0354A5204E40C`
SHA256 | `CF7686C65EE7B2BCDA9624D56BC548147A9B1B66CE32A5BB0AC8C0141D841519`
SHA384 | `E539467AA1A2FB2575E2133DFDDD7FF012B19907C240357BA7F6A137CD5E6B552B5B62A2B286308A545953643F3199AC`
SHA415 | `3FA2B483BC9BBF0F44ADB51F9C20F1EBDC2238B942EA2798099C775FDBDCF5AD56FD223CEB4A735027994D62A64F3EB1BADA80BAB7A097F34C9D0E229E8FCD47`
SSDEEP | `1536:A5Qv8jJDyRbCu6SRbq9itNkNdK7me3fXqcXYMhnETnRpuBaEb3V:mjERbCu6SRbqSNkNdK7mMfXpoEnETaBl`

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


