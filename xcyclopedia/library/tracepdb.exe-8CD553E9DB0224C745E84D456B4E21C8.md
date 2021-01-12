---
title: tracepdb.exe | Get Trace Format info from PDB
excerpt: What is tracepdb.exe?
---

# tracepdb.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracepdb.exe`
* Description: Get Trace Format info from PDB

## Hashes

Type | Hash
-- | --
MD5 | `8CD553E9DB0224C745E84D456B4E21C8`
SHA1 | `4A79415CB75C7F160FB735F22D53C92D17918643`
SHA256 | `BB5C60D1D3BB2351544B08B5D5862BA283CDEACA04946F6AAC74CEBCB896A0AC`
SHA384 | `8B6F54D290C822C18030337308639B7AF15A5528CA6AB0D9EAA2644ED6284A90E411BFF5923CBCAEE3BBC75FE20E579D`
SHA512 | `EC8D7E956A5A1F5B8C3F384C87CB219FF83A4095E81DBA8B444FC179714AC0F0923D371656D91A206D62AB6AF25D315AB8956535814743F21DC63ECB68E533BF`
SSDEEP | `768:unc1XrwsG4bS+5BE06AArxSz6odxNYr5rvtP:unCrwSWEBd6h+xNYFrp`
IMP | `277FD7663C88CA65910CB9EBBB6589D7`
PESHA1 | `07FFCA4EAACE8F154D6DD0765910EC5B9197993B`
PE256 | `420D8E3CD645F46666FDEAFF70D15C5953525DEE1A4CF5530CCB97341DDA69A1`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracepdb.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


