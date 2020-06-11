
# gpresult.exe 

* File Path: `C:\WINDOWS\system32\gpresult.exe`
* Description: Query Group Policy RSOP Data
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C21C5600D1A9F0C43E7579B329947480`
SHA1 | `F9BAFCE7386ACC27E6EF492357D9D57EEE7874F5`
SHA256 | `88795DD89E4F3D7BDF4011846CFC863031D9217D7AB996A8ED8C488A1C73009F`
SHA384 | `F5AAFA9D9268D5FAFAB24F608FE3F37DD502BFE36E9305E9E3DC516A58545C52C8B65C9DCEA3BB772C3F7A670E1ED727`
SHA415 | `B544D2B9BC525974E3B951687228F5D6A2BEB8F391FCD9FFF3B32D2EE44EC4A8456C3FBC7C93B5F1CAA80B9E76E19E63EF12D8C7B0E7802AAD5A8635D7C1D52C`
SSDEEP | `6144:IqHAmk7jtxdElaoR3Ls10c8T4sJHJeAFVUQkM:IqZkX4aa3L+0c8T4e/VqM`

## Runtime Data

### Usage (stdout):
```Batchfile

GPRESULT [/S system [/U username [/P [password]]]] [/SCOPE scope]
           [/USER targetusername] [/R | /V | /Z] [(/X | /H) <filename> [/F]]

Description:
    This command line tool displays the Resultant Set of Policy (RSoP)
    information for a target user and computer.

Parameter List:
    /S        system           Specifies the remote system to connect to.

    /U        [domain\]user    Specifies the user context under which the
                               command should run.
                               Can not be used with /X, /H.

    /P        [password]       Specifies the password for the given user
                               context. Prompts for input if omitted.
                               Cannot be used with /X, /H.

    /SCOPE    scope            Specifies whether the user or the
                               computer settings need to be displayed.
                               Valid values: "USER", "COMPUTER".

    /USER     [domain\]user    Specifies the user name for which the
                               RSoP data is to be displayed.

    /X        <filename>       Saves the report in XML format at the
                               location and with the file name specified
                               by the <filename> parameter. (valid in Windows
                               Vista SP1 and later and Windows Server 2008 and later)

    /H        <filename>       Saves the report in HTML format at the
                               location and with the file name specified by
                               the <filename> parameter. (valid in Windows
                               at least Vista SP1 and at least Windows Server 2008)

    /F                         Forces Gpresult to overwrite the file name
                               specified in the /X or /H command.

    /R                         Displays RSoP summary data.

    /V                         Specifies that verbose information should
                               be displayed. Verbose information provides
                               additional detailed settings that have
                               been applied with a precedence of 1.

    /Z                         Specifies that the super-verbose
                               information should be displayed. Super-
                               verbose information provides additional
                               detailed settings that have been applied
                               with a precedence of 1 and higher. This
                               allows you to see if a setting was set in
                               multiple places. See the Group Policy
                               online help topic for more information.

    /?                         Displays this help message.


Examples:
    GPRESULT /R
    GPRESULT /H GPReport.html
    GPRESULT /USER targetusername /V
    GPRESULT /S system /USER targetusername /SCOPE COMPUTER /Z
    GPRESULT /S system /U username /P password /SCOPE USER /V

```

### Usage (stderr):
```Batchfile
ERROR: Invalid syntax. Value expected for '/h'.
Type "GPRESULT /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gprslt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


