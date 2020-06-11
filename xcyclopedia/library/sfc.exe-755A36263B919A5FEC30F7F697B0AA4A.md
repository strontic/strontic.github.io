
# sfc.exe 

* File Path: `C:\Windows\SysWOW64\sfc.exe`
* Description: System Integrity Check and Repair
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `755A36263B919A5FEC30F7F697B0AA4A`
SHA1 | `AEEDAF44353BF628B9C503611786AFF59EA0732F`
SHA256 | `6FB46313A33ADD50FF813D6EDA76487BEEEC6000439C3F25A1F679E7DCFE47C4`
SHA384 | `461B4F2C93D3B3E351A32C20658D87F94DD124284CF29EEF0B571295478FB3E2909D5F5747E8F2919CD9C8F2CAB56F9F`
SHA415 | `A5CD04C177614491B8DA8D4888B95C368836ED74F68FB7FE7740149F3A9B930853D638B22D7C80CFDB5F5CC2A11BAA68167E4E579D1BCB86ED2145116046313A`
SSDEEP | `768:n8pfRks4ZxJXxTnrJikirB7ILn5FvYzmMPljmmpgFUG:S09RnrJikirZdlmmpgB`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft (R) Windows (R) Resource Checker Version 6.0
Copyright (C) Microsoft Corporation. All rights reserved.

Scans the integrity of all protected system files and replaces incorrect versions with 
correct Microsoft versions.

SFC [/SCANNOW] [/VERIFYONLY] [/SCANFILE=<file>] [/VERIFYFILE=<file>]
    [/OFFWINDIR=<offline windows directory> /OFFBOOTDIR=<offline boot directory>]

/SCANNOW        Scans integrity of all protected system files and repairs files with
                problems when possible.
/VERIFYONLY     Scans integrity of all protected system files. No repair operation is
                performed.
/SCANFILE       Scans integrity of the referenced file, repairs file if problems are
                identified. Specify full path <file>
/VERIFYFILE     Verifies the integrity of the file with full path <file>.  No repair
                operation is performed.
/OFFBOOTDIR     For offline repair specify the location of the offline boot directory
/OFFWINDIR      For offline repair specify the location of the offline windows directory

e.g.

        sfc /SCANNOW
        sfc /VERIFYFILE=c:\windows\system32\kernel32.dll
        sfc /SCANFILE=d:\windows\system32\kernel32.dll /OFFBOOTDIR=d:\ /OFFWINDIR=d:\windows
        sfc /VERIFYONLY

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


