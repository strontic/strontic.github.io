
# getmac.exe 
* File Path: `C:\WINDOWS\SysWOW64\getmac.exe`
* Description: Displays NIC MAC information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `1F4B47509E3B2BF4AE9E6EBA191CF3E9`
SHA1 | `D18125DF129262045A4F642CAA880556CEB6A3BC`
SHA256 | `83A26A068E174E389B9793E93E65B802B6D923CC70EE8AFB06B49C885491B462`
SHA384 | `2D4C12F4A948D6AEAA1CFDCFED2BBB6462D9F6E689198F5315531D1D355A3A72438653970F5A92211E85A05296ABFEA5`
SHA415 | `C87BF1FDE6660A627F4F15EB340C118B47C2B43C2F80F8487F8299688BAB01B67FEE097A502729F48EC046AEC9096BD5839F8D26B97C6EF7F5D269582C58E302`
SSDEEP | `1536:Aq4azRifXs7Si9IOzIlEzYNgrscLvQipeSJHAFT0UaPH9:ALfXsei2OMUYerscbQiop0Ua/`

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

* Original Filename: GetMac.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


