---
title: ildasm.exe | Microsoft .NET Framework IL disassembler
excerpt: What is ildasm.exe?
---

# ildasm.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\ildasm.exe`
* Description: Microsoft .NET Framework IL disassembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `6C579A66AE0B5BAA15C651E617977648`
SHA1 | `711334A1A639249CB178BE961FB4F49390650AF5`
SHA256 | `B40202B260210EEB597773CD14EF0FCB0E8E03597700C76E2D4130BE898BF26A`
SHA384 | `89CB570A151E65038854564E686F30F337231C1396923C3385F1970D9969FFCAED9184FE97BFC38442533A026BFBACD9`
SHA512 | `710678188A31EAA5638850F3FFF3D901AF1A2EDCDFC7E33B308C7925F4EEEBCB6483E6EE71EF170734EEED39BCEA6C653E239B4FD0425A4B8B0043151DE67043`
SSDEEP | `12288:P5EERjTVCej+lvCu2Ko22K3ugPGXPNhUHuE:P5nVCejyAKpdPOXUHl`
IMP | `B0FED2BCFEB483968154D53F991D8343`
PESHA1 | `B2BD704B0F3E22F18BB28627231DA762DC4F78BB`
PE256 | `D7DBCC936EA6F7C8F7E5030FC0E6FED307DDE596F980274727D50751DF02489C`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\ildasm.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b40202b260210eeb597773cd14ef0fcb0e8e03597700c76e2d4130be898bf26a/detection


## Possible Misuse

*The following table contains possible examples of `ildasm.exe` being misused. While `ildasm.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"ildasm",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


