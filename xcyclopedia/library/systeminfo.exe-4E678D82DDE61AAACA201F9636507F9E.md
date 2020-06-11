
# systeminfo.exe 

* File Path: `C:\WINDOWS\system32\systeminfo.exe`
* Description: Displays system information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4E678D82DDE61AAACA201F9636507F9E`
SHA1 | `BB6CD4B5CFE97EB64C071ADA39AC3B5F2F252FD6`
SHA256 | `F5B4FB293ADA97A8C4B92BB380747DA1D71336F144332C95DDEF3F8522F7CE87`
SHA384 | `DA484BD1E0ADC52C1F0597B6B718D0C251B3D40CE754D1F94290D212A76BCEE531D57B3A8689A214E16398293EAFE071`
SHA415 | `395BF5A1069AC4DA7893524337E8E90B4367392C58DED45B5590E02F1040A7522BCC4A93A40840C3CA3F7F0EB63AB7096474664DD71EE29C2C61902EA5357D8E`
SSDEEP | `1536:/WubkGjW3NtMsqQHwOuAUUm+ImTFOMGCQTjiLJUoc5waGG3JygbPL0sVTTyGTjNa:+ubgNtXRG3HwUwubZXBxM`

## Runtime Data

### Usage (stdout):
```Batchfile

SYSTEMINFO [/S system [/U username [/P [password]]]] [/FO format] [/NH]

Description:
    This tool displays operating system configuration information for
    a local or remote machine, including service pack levels.

Parameter List:
    /S      system           Specifies the remote system to connect to.

    /U      [domain\]user    Specifies the user context under which
                             the command should execute.

    /P      [password]       Specifies the password for the given
                             user context. Prompts for input if omitted.

    /FO     format           Specifies the format in which the output
                             is to be displayed.
                             Valid values: "TABLE", "LIST", "CSV".

    /NH                      Specifies that the "Column Header" should
                             not be displayed in the output.
                             Valid only for "TABLE" and "CSV" formats.

    /?                       Displays this help message.

Examples:
    SYSTEMINFO
    SYSTEMINFO /?
    SYSTEMINFO /S system
    SYSTEMINFO /S system /U user
    SYSTEMINFO /S system /U domain\user /P password /FO TABLE
    SYSTEMINFO /S system /FO LIST
    SYSTEMINFO /S system /FO CSV /NH

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "SYSTEMINFO /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sysinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


