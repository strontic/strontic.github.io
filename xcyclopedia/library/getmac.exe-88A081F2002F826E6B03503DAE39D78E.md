
# getmac.exe 
* File Path: `C:\Windows\system32\getmac.exe`
* Description: Displays NIC MAC information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `88A081F2002F826E6B03503DAE39D78E`
SHA1 | `92ADE156DFAC19A41A2E8FCE47ADF9E9269C3F88`
SHA256 | `3D7AF74B6313751663D28A68084CAD9C1F5E9F82B01FD5352880CBE86A06AAB2`
SHA384 | `6ABBA09E84484DAA21823B3726F05DD55AF4EF2A9899A1F61BEDCD1BA5DE51E9E4E33C621C7B1EC649A21073969FBABF`
SHA415 | `794C8D7D848FA57AE1E8504F6F39B8EF7D4B35F9188276BE17CD576DFF1B9AA6D4CE3B4930729F58EF2F3A441334F2901DAB3B6BB0C3D8B840B686DF0C95AAB2`
SSDEEP | `1536:dsWiKpuWkdLyfEEWHGiTgmeZEYXGY6zMb+usa6YkR:dDpumf/WvVeZEiRjsaRw`

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


