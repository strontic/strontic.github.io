
# getmac.exe 

* File Path: `C:\Windows\SysWOW64\getmac.exe`
* Description: Displays NIC MAC information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `934073BE2A7157BEF5CF6B88EDAE3D29`
SHA1 | `D4EC5BA75B46A754B47AD2B3375481583145C10B`
SHA256 | `A2B86C9C404568BAF6CDBD1D5F393C9893F71FD941523DEE9E576FF1979CCCA0`
SHA384 | `D45CB48096A9DDDE9F40D1CDC53348350EA63EE6D3D85CF9A66C033B1400643E95D9E8621A1F0DC5FD40B4EC61B71946`
SHA415 | `2E2424AB5C0035C11CF26BFAAA4A991F3C1DC64B35DA493E970A071DCCDE7D41F8758A43296D5360007E6DF6EBAB4DDABD9C4556616D422A1BE197C5AC026A27`
SSDEEP | `1536:Q4aTNS2pGY2hnDvwQbr+zI4f0YqmyVDiwOxKHulaOB7j:IS2pGY2aQmTf0hmyVsKOla+7j`

## Runtime Data

### Usage (stdout):
```Batchfile

GETMAC [/S system [/U username [/P [password]]]] [/FO format] [/NH] [/V]

Description:
    This tool enables an administrator to display the MAC address
    for network adapters on a system.

Parameter List: 
    /S     system            Specifies the remote system to connect to.

    /U     [domain\]user     Specifies the user context under 
                             which the command should execute.

    /P     [password]        Specifies the password for the given
                             user context. Prompts for input if omitted.

    /FO    format            Specifies the format in which the output
                             is to be displayed.
                             Valid values: "TABLE", "LIST", "CSV".

    /NH                      Specifies that the "Column Header" should
                             not be displayed in the output.
                             Valid only for TABLE and CSV formats.

    /V                       Specifies that verbose output is displayed.

    /?                       Displays this help message.

Examples: 
    GETMAC /? 
    GETMAC /FO csv 
    GETMAC /S system /NH /V
    GETMAC /S system /U user
    GETMAC /S system /U domain\user /P password /FO list /V
    GETMAC /S system /U domain\user /P password /FO table /NH

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "GETMAC /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GetMac.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


