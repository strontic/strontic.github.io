﻿
# getmac.exe 
* File Path: `C:\WINDOWS\system32\getmac.exe`
* Description: Displays NIC MAC information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `EDA93542A676EB67952B7BDCC652B217`
SHA1 | `D4BAEEB9180A4284B33FA3602D86CAD7EC05E6A0`
SHA256 | `94256542E235681BA64A20BC50910DD745D52347A89D36BE2DD4C1465901C52B`
SHA384 | `4AD99DB9A0D2687989E1D97DF34A8BBA6991CF0FD110B8C7D2A98B68D7ECBF5DC95FE2DD91A7E74E65BC99F04FB64B02`
SHA415 | `E7225C949A34A71177A73C7BAA546DC1651D343C20C0BC51BE61134C365A70E4216E2594C4C0D11C09BBE2795475814D96E956E29B44950FCB800978D7E1AACF`
SSDEEP | `1536:qAzqZOSQzH8y3kkt7Sg+CzgDfYazyl9CEH8fFGGUaZ/3:qAkV2kkNSNCzgY3HqAGUaZf`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GetMac.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

