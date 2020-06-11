
# openfiles.exe 

* File Path: `C:\Windows\system32\openfiles.exe`
* Description: Displays the current open files list
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `47D7A64D4437F035712DC3238C25941C`
SHA1 | `BCD20CB9BA17FF4D0863CA7FA64FEB51643AA191`
SHA256 | `6A77E3CB63CC83EECFEEFC218F07BA02FD124690FC535475FD139ACC22B921A6`
SHA384 | `006C2BA6689685B34361888E836A85A83542EC7A23AED0968CF024F6D3819F33EB870ADEA17C9F8A87E639A695EAE8A8`
SHA415 | `3A373054E6F8D8CB0250ED19324291C826922498027CF7C9C8F8C2977C70A87C658267E24E5EDF0E5A751210ADC86C2FFAF7CB670C52B063C7E978D53C442E36`
SSDEEP | `1536:iaRkJmD6MTXtlujhsCnEdOpTFV8MN3CEsevGef3B7jOx5UW:Nki6mXhOpbpJCEXB7jOxt`

## Runtime Data

### Usage (stdout):
```Batchfile

OPENFILES /parameter [arguments]

Description:
    Enables an administrator to list or disconnect files and folders
    that have been opened on a system.

Parameter List:
    /Disconnect      Disconnects one or more open files.

    /Query           Displays files opened locally or from shared
                     folders.

    /Local           Enables / Disables the display of local open files.

    /?               Displays this help message.

Examples:
    OPENFILES /Disconnect /?
    OPENFILES /Query /?
    OPENFILES /Local /?

```

### Usage (stderr):
```Batchfile
ERROR: Invalid syntax.
Type "OPENFILES /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: opnfiles.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


