
# systeminfo.exe 
* File Path: `C:\WINDOWS\SysWOW64\systeminfo.exe`
* Description: Displays system information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `EFD674132AFF29322A3526A5541045C6`
SHA1 | `2BEA2BBE0495CCBB6D6C08F9FA641749540C63DC`
SHA256 | `9BC249377A01FB43CDF969F3AA673619A941DAD3BC07AA07E73DF5908CFBBF60`
SHA384 | `08FCDA7EE1BE11C443B7B16512DCDC279CC885578150BEADBE5BD25027E69F22E9230BFD058E07FD7A47BE8D829F69E7`
SHA415 | `EEEFC6E67224E0097B9653272B708A43E2F41DFEAC220DFE96FDF14903033F514DA44DA6F0F9E291EA545ED4C870BE464484BA947A3954121E7FB7FBBAD4189A`
SSDEEP | `1536:fHJidpyuhLhqeyMIXhELa8VQ7gcVxLitstS6CxRr:KYeyMIXhpAQ7gcrLij6CxJ`

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


