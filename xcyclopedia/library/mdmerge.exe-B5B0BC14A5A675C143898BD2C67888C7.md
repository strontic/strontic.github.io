---
title: mdmerge.exe | Microsoft MDMERGE Utility
excerpt: What is mdmerge.exe?
---

# mdmerge.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mdmerge.exe`
* Description: Microsoft MDMERGE Utility

## Hashes

Type | Hash
-- | --
MD5 | `B5B0BC14A5A675C143898BD2C67888C7`
SHA1 | `45A9C70881965A074FCC9E6E62673C350F436DA7`
SHA256 | `146EDCF2F69417071178E97ECA594C394130BFEBB9707843DAAF88F90B8CA521`
SHA384 | `755B6BDB944440DD0E7E30D74C78EE8659ADE4AB19F9E6F215CB8E8B08A4B248F22B30C4E86BEA34E52950C44DA00033`
SHA512 | `7310359756F894E10941A45AAB6F9FF7F8D88A88BA22FEFE0A67881DD025206F39568CBF418FF168F4C1F5173EA580FCA8A9157F0244FAC0594D54DF682DE061`
SSDEEP | `12288:4B7B6/Ovc1wkXq7sgUjrl8xDz2EGwiH13vwzoimBiP+wi:Q0/fwkXq7sgUjrcDzawiH13vwzlSiP7i`
IMP | `22B40D760520C08196FEA684FCB40352`
PESHA1 | `36FB051D21F4F0A5E0D36C78977EBE196D25BA0A`
PE256 | `F2D7C1CF0871B04D2BC24693E5D5A1713CB399126D1600C93ED25DE435C89104`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft(R) Metadata Merge Utility Version 10.0.49.

Usage: C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mdmerge.exe [-/][Switch][:][Value]

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mdmerge.exe |
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

* Original Filename: mdmerge.exe
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


