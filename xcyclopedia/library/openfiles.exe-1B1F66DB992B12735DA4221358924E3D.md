
# openfiles.exe 

* File Path: `C:\WINDOWS\system32\openfiles.exe`
* Description: Displays the current open files list
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1B1F66DB992B12735DA4221358924E3D`
SHA1 | `062AE56AE65969A95F7FB01F1F1B36A8B6F161BE`
SHA256 | `EDB368CB40CEC43A6C4F9EE9EE7ACF056E0F35B39797A93E80F502C4AA3739C3`
SHA384 | `9B13B8EDA6EBBBCA3A2822E3B116A2BE54D4F1050428172E6E4DF3A500FC9F163CC4206E6F9CD17AC752D0D45C41C8FD`
SHA415 | `2ED21F0758C8C2050615A22B08601CB3684C675961B02EAD2112DFC27212B070EC6A1C6B98B768D43F7D96690E2C23CC47ECFC4B76D6B2336A6E5D960402F4C3`
SSDEEP | `1536:57IvMFxeDvlygP84Og+rKJUxLniTItiefQtdgqxzBs:qvMmc1MJiniEutdgqxO`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: opnfiles.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


