
# sfc.exe 
* File Path: `C:\Windows\system32\sfc.exe`
* Description: System Integrity Check and Repair
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `297A8E78FFE3829BA90F0EB6F1B0B500`
SHA1 | `6A44318ECCE54F4B4FC2374D6B0C97BD9F1DCA2E`
SHA256 | `E4006F0CB1EE909A8CD04B8A56899C459473406C3A9A3DA53B891E5AE8F7E609`
SHA384 | `6CE8057AFB9F90E31B03282D6F74B95302C6073A079643C75A2FC30E5057A967AE7965197AE4E92A24CEBEF5CE58B179`
SHA415 | `8EA20360C35781E1C7053E08EDF9A0389495B2A70D45D5582C1512D77DD64BF15B967AFF23DF22E7DB39580EACBB0CEF67C1C045AB4359CF1CCC03E5680C9E87`
SSDEEP | `768:faUwq2S0k1U4BrNDzdhKA1k535H2SCwz8EjVEFx7aNPRpnF+VmGXrxg:S7fqU4BJz11k53Bz89z7symoxg`

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


