
# systeminfo.exe 
* File Path: `C:\Windows\SysWOW64\systeminfo.exe`
* Description: Displays system information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `09FF3DC244D57B421358C4423FAD1C38`
SHA1 | `4C6497703BEB456A6426B4DCB50483479467163D`
SHA256 | `531794D32301B83BDC58D09A2AA3A37F4FFE46107BD796187CAF3CD132D1B755`
SHA384 | `E8ABFD0F1488E41E3EC8006E4783EB1D0D4341CF77803581EF1BD950B3FF545761159AC22BD6E7DDE20D8AF8E008AC3B`
SHA415 | `38879686834CCD1E227FC8F3F164E382BE9C9D68B5BC84FD17CA244018359FE9D575EF5DC351FDD57A7F266E125A3CBE17DA098CE856B7DA560EA37EDB6F850E`
SSDEEP | `1536:CHJilTu8wey5jcF/5fm5E5zWS+20R2SAynFCd9sG2aOtmxI4k:ffwR50fgE5zX+20QUCd9sjmxx`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sysinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


