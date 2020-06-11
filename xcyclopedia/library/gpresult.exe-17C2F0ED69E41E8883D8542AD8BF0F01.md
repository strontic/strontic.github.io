
# gpresult.exe 

* File Path: `C:\WINDOWS\SysWOW64\gpresult.exe`
* Description: Query Group Policy RSOP Data
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `17C2F0ED69E41E8883D8542AD8BF0F01`
SHA1 | `647421003B32E937DBA57B0D37D24DD06FAD4D29`
SHA256 | `880228D722D778B11CF5017BD7341034AD9C6B76C6EB0C295FDF3B1FD6F13E8A`
SHA384 | `C40EF38D287BEB49FAC5CBAF339435E6291AA3F5456272F556F9870DF8CC02926F24D080BEF7E6AC0996AB88E56E6732`
SHA415 | `17A7B21AF87EA03DB699912DABF60F1A10F672B72CC7C72C1EF8A269937089A18E6D9006E297B7BBFE0F6D515AB9F7CBE3A8DB6E644F7651A19F14C2159A6EB0`
SSDEEP | `3072:KP+sOKvkYU985BhbrSevZwp1kbbvF4dyJbTxJDxf7x+JZx1b+a1D/4Zt+a2Tv2t3:+BnU985KevZxR4Ur746MTCicuOxe9MD`

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

* Original Filename: gprslt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


