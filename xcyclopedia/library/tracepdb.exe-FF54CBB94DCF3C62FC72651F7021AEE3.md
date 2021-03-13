---
title: tracepdb.exe | Get Trace Format info from PDB
excerpt: What is tracepdb.exe?
---

# tracepdb.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracepdb.exe`
* Description: Get Trace Format info from PDB

## Hashes

Type | Hash
-- | --
MD5 | `FF54CBB94DCF3C62FC72651F7021AEE3`
SHA1 | `E56DEEFEB2BCF3D5A928E609564C4B852BF0AD49`
SHA256 | `18FBB31F3B4FD3076BDE7EA32256B3C3960A629C601C36EBABD3D236318101EC`
SHA384 | `84C1E118C2D95B55318D40ECBBB23957210D5C6940FB16C0672BC3C72C2C3D7FA8A5B0CE5B376FD18B8FBD59BB11481E`
SHA512 | `33B555250314F45727CCFC86F616CA607C2CA7176C8C0F45EB298E8EB3E1F01EC01E3FAFA4F2DA4D1F7372DB775497A2EAEF32CAAD3D8E25A0FC6519019411CD`
SSDEEP | `768:m4t0NPM/GAtW4hF6gWIlhoNkdlKOlybc1Xreo09x4vw/d:BsPGtWVVWCWlybCre5xcw1`
IMP | `C563AF5DA2261C5F1E2DB0D3649C84F3`
PESHA1 | `5956170EB751DD355D42973A39AEF47F751C0540`
PE256 | `A8A8D944D21D2F657108C3CEC806F29D5EDAFFDE3CC14BCA3BFC212A61C3DCDC`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) TracePDB.Exe (10.0.19041.1)
 Microsoft Corporation. All rights reserved.

TracePDB creates TMF files from the specified PDB file. If you specify an image
file, TracePDB finds the PDB file for the image and then creates a TMF file.

Usage:

TracePDB.exe [-f <PDBFiles>] [-s] [-p <TMFDirectory>] [-v] [-c]
TracePDB.exe -i <ImageFiles> [-r <SymbolPaths>] [-p <TMFDirectory>] [-v] [-c]

Parameters:

-f <PDBFiles>     - Source of trace formatting instructions. 
                    Default=<LocalDirectory>\*.pdb.
                    Valid wildcards are ? and *.

-s                - Recursive. Creates TMF files for all PDB files
                    that match -f in all subdirectories of the -f path.

-p <TMFDirectory> - Output file location (directory only).
                    Default=Local directory.
                    Do not specify a file name; the file name is generated
                    automatically based on the message GUID.

-i ImageFiles     - Image Files for which to find PDBs and creates TMFs.
                    Valid wildcards are ? and *.

-r <SymbolPaths>  - Path to private PDB symbol files. Default 
                    is %_NT_SYMBOL_PATH% or srv*\\symbols\symbols.

-o <TmfFile>      - Name of single tmf file output.
                    Will generate a single TMF file

-c                - Generate TMC files.

-v                - Verbose.

Default values:

        <PDBFiles>     <LocalDirectory>\*.pdb.
        <TMFDirectory> Local directory.
        <SymbolPath>   %_NT_SYMBOL_PATH% or srv*\\symbols\symbols

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracepdb.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TracePDB.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


