---
title: ildasm.exe | Microsoft .NET Framework IL disassembler
excerpt: What is ildasm.exe?
---

# ildasm.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\ildasm.exe`
* Description: Microsoft .NET Framework IL disassembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1EDEF2D2C5BE98582F8CBA566F3603F0`
SHA1 | `FA4B04167B54E727898CA0326FF08FEDAADD5428`
SHA256 | `16B83C1E88BF45EF528DA4FDA4CD0D174571D7597A6379492A12B26AB69DABA6`
SHA384 | `694D63472776602E8CAF2D65F8939C53CF6B8B7F2E2FEEC3FA1E8C20D5C02F42E3CC7011CE8BE4A3D8194D2FE4470932`
SHA512 | `6BB1CC8C7B6961AFA93A885EE03D42570132BC3008C4490EAFC44254F93631F654D4C0A1979FAAF986DE9AEA34389DDA08CB043E6E9B8647833A1BD13CAAE437`
SSDEEP | `12288:cArMxakG4g2X9/3L68Vzk4SMO7ky0VX2DIa6E4TDrVRe+JcbZTB6Xq3jmugHG5aO:pr1Z4g2X9/3L6YeMO7ky0VmDqNi+Jcbd`
IMP | `420AF2FBD6F4480F1FB6C114A447BB80`
PESHA1 | `559344F8246649B32C12356F366C232395E25F7E`
PE256 | `33077C8C2412A76924EB7561471589C6422C6D818C448B6E90119C8AA747202E`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework IL Disassembler.  Version 4.8.4084.0
Copyright (c) Microsoft Corporation.  All rights reserved.

INVALID COMMAND LINE OPTION: --help

Usage: ildasm [options] <file_name> [options]

Options for output redirection:
  /OUT=<file name>    Direct output to file rather than to GUI.
  /TEXT               Direct output to console window rather than to GUI.

  /HTML               Output in HTML format (valid with /OUT option only).
  /RTF                Output in rich text format (invalid with /TEXT option).
Options for GUI or file/console output (EXE and DLL files only):
  /BYTES              Show actual bytes (in hex) as instruction comments.
  /RAWEH              Show exception handling clauses in raw form.
  /TOKENS             Show metadata tokens of classes and members.
  /SOURCE             Show original source lines as comments.
  /LINENUM            Include references to original source lines.
  /VISIBILITY=<vis>[+<vis>...]    Only disassemble the items with specified
          visibility. (<vis> = PUB | PRI | FAM | ASM | FAA | FOA | PSC)
  /PUBONLY            Only disassemble the public items (same as /VIS=PUB).
  /QUOTEALLNAMES      Include all names into single quotes.
  /NOCA               Suppress output of custom attributes.
  /CAVERBAL           Output CA blobs in verbal form (default - in binary form).
  /NOBAR              Suppress disassembly progress bar window pop-up.

The following options are valid for file/console output only:
Options for EXE and DLL files:
  /UTF8               Use UTF-8 encoding for output (default - ANSI).
  /UNICODE            Use UNICODE encoding for output.
  /NOIL               Suppress IL assembler code output.
  /FORWARD            Use forward class declaration.
  /TYPELIST           Output full list of types (to preserve type ordering in round-trip).
  /PROJECT            Display .NET projection view if input is a .winmd file.
  /HEADERS            Include file headers information in the output.
  /ITEM=<class>[::<method>[(<sig>)]  Disassemble the specified item only

  /STATS              Include statistics on the image.
  /CLASSLIST          Include list of classes defined in the module.
  /ALL                Combination of /HEADER,/BYTES,/STATS,/CLASSLIST,/TOKENS

Options for EXE,DLL,OBJ and LIB files:
  /METADATA[=<specifier>] Show MetaData, where <specifier> is:
          MDHEADER    Show MetaData header information and sizes.
          HEX         Show more things in hex as well as words.
          CSV         Show the record counts and heap sizes.
          UNREX       Show unresolved externals.
          SCHEMA      Show the MetaData header and schema information.
          RAW         Show the raw MetaData tables.
          HEAPS       Show the raw heaps.
          VALIDATE    Validate the consistency of the metadata.
Options for LIB files only:
  /OBJECTFILE=<obj_file_name> Show MetaData of a single object file in library

Option key is '-' or '/', options are recognized by first 3 characters

Example:  ildasm /tok /byt myfile.exe /out=myfile.il


```

### Child Processes:
ildasm.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\ildasm.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ildasm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/16b83c1e88bf45ef528da4fda4cd0d174571d7597a6379492a12b26ab69daba6/detection





MIT License. Copyright (c) 2020 Strontic.


