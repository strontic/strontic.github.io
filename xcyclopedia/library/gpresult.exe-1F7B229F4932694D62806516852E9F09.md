
# gpresult.exe 

* File Path: `C:\Windows\SysWOW64\gpresult.exe`
* Description: Query Group Policy RSOP Data
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1F7B229F4932694D62806516852E9F09`
SHA1 | `BB97C94356ECAAAE14CFF37DBBAFBB5C5BBDA343`
SHA256 | `02629EC2C3224B6EBE90E0AD49A192B5FD7C9CEF256ECD3F6048EEE504A4A274`
SHA384 | `2C3AACD65C227FB157EDB7300BE0A886E6E2A333F6CB20B75FFDE3E921F9C36540E34420FECF0A28F0A25D8AE9828B1D`
SHA415 | `7FFE08F4E19054468FBBBC35B04785C2B5C746988A653B64B064734DEA3FFD95E6CC6FDDF8A21780D016717C94CB262757E583EB470984FA5E0B8421ED948966`
SSDEEP | `3072:kQQOcvkTECaMX/TVHWpjn2dwbX1D6DHBOi2GXE05tPo0d5HQw8aESIsW6YzTwAd6:vylCLVH4qibXxSHwAo0d5HQw8bLr6Mfd`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gprslt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


