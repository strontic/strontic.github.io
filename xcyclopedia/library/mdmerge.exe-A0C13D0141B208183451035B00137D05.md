---
title: mdmerge.exe | Microsoft MDMERGE Utility
excerpt: What is mdmerge.exe?
---

# mdmerge.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mdmerge.exe`
* Description: Microsoft MDMERGE Utility

## Hashes

Type | Hash
-- | --
MD5 | `A0C13D0141B208183451035B00137D05`
SHA1 | `1638FD613CBE9050272F1B773E3AD5626F460255`
SHA256 | `62506E8997DCD544DAB6EC7F792DAB643B1B25EEFF74A21A8C56AFBBA3A76CCD`
SHA384 | `50D90F3E83469F7805D25B28907B2519AE99B54617D0CC04D2AB520F1805F01ABE71C755D8318AA5818C75155A8F7E00`
SHA512 | `DC5A3A1517AEA67AD6355997249FA993CC6E6F24021507F5E473EE3F042ECEAA08DAFCFD108F03ACD654C88E0302872319028AAFB38F21321AEEC98764637CF7`
SSDEEP | `6144:ak/UoSAOf3bHRGyW3hVv0WbQpCh0V5ZsVxnnYvk8tswxzX2g+uhY3GG/5TN3BJ4y:qoSZgVTfU5+Vavk8tswxzX2fJtl4y`
IMP | `D35F09FFA2C37327CAF4D3C5A751464C`
PESHA1 | `88D6C50FA17BEA1D3C0104934E6FF9351F2B32E5`
PE256 | `893B41C44B742BD84EAEE834A104DED5CE9BEAF1E3DC0A3337B4E53F87FBC670`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft(R) Metadata Merge Utility Version 10.0.49.

Usage: C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mdmerge.exe [-/][Switch][:][Value]

Where Switch is one of the following: 
    -?: Print this help
    -h: Print this help
    -v: Validate - Validate metadata type references
    -i: Input directory - compose metadata files in this directory
    -metadata_dir: Metadata Directory - Directory which contains the master copy of Windows Metadata files
    -partial: Partial - resolve unresolved types against metadata files specified in the -metadata_dir switch
    -platform_filter: Platform filter - specifies a platform filter XML file
    -additional_platform_path: Additional platform path - specifies additional path to look for <platform>.xml file. Optional.
    -o: Output directory - put composed metadata files in this directory
    -n: Composition Depth - compose to this level of input
    -contracts: Sort metadata into contracts
    -platform: Target Platform - compose metadata for this platform
    -mdv: Metadata format version
    -contractMap: Specifies the filename to place the API contract maps
    -removeInternal: Removes types that are marked internal
    -resFile: A compiled resource file to embed in metadata files
    -keepOnlyInternal: Removes types that are not marked internal
    -createPublicMetadata: Creates metadata for public release
    -transformExperimental: Transform the experimental attribute
    -keepOnlyPrivate: Removes types that are not marked private
    -verbose: Prints verbose information to the console

```

### Usage (stderr):
```cmhg
MDMERGE : error MDM5003: Unrecognized command line switch: --help.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mdmerge.exe |
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

* Original Filename: mdmerge.exe
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


