---
title: rc.exe | Microsoft Resource Compiler
excerpt: What is rc.exe?
---

# rc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\rc.exe`
* Description: Microsoft Resource Compiler

## Hashes

Type | Hash
-- | --
MD5 | `960A2BB300F4F1058ADBD41B223D88FE`
SHA1 | `47A19B64AE62C15697448D5302462AE75E0EE1EC`
SHA256 | `CE6079CE8557C4DBE1F611B19919D70BB6FA9317C426801CC4A1E3B72646F532`
SHA384 | `21EBE1E5ED618D7F56036A3E83B05670B3584191CEBCFDC40EA3741C3D6061CD549FA99BB377457F55AD5487285633E0`
SHA512 | `57406A22A276DC8796CDB26A9FDF8E73647DBD9341E8625BAD74234CB571E49713E844473C6CD39948392C7BB5E2F5AEC879A0467884C189F30DD8AF37D2758E`
SSDEEP | `1536:Gk1QQKuZTIclwZ/dojlSNV36keeSkbMizJa:GaXKoXj4rqijJa`
IMP | `16E69F537C702FCF7AAA8D93096C0710`
PESHA1 | `1697AA5BA4A17261157B186C2AF940B00C32D1C9`
PE256 | `8600C7B62E73ECE9DB5B7E4C122399F89E9FB8F792C724E01D77D841452B6B81`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) Windows (R) Resource Compiler Version 10.0.10011.16384
Copyright (C) Microsoft Corporation.  All rights reserved.

Usage:  rc [options] .RC input file
Switches:
   /r       Emit .RES file (optional)
   /v       Verbose (print progress messages)
   /d       Define a symbol
   /u       Undefine a symbol
   /fo      Rename .RES file
   /l       Specify default language using language identifier
   /ln      Specify default language using language name
   /i       Add a path for INCLUDE searches
   /x       Ignore INCLUDE environment variable
   /c       Define a code page used by NLS conversion
   /w       Warn on Invalid codepage in .rc (default is an error)
   /y       Don't warn if there are duplicate control ID's
   /n       Append null's to all strings in the string tables
   /fm      Localizable resource only dll file name
   /q       RC Configuration file for the resource only DLL
   /g       Specify the ultimate fallback language using language identifier
   /gn      Specify the ultimate fallback language using language name
   /g1      Specify if version only MUI file can be created
   /g2      Specify the custom file version for checksum in MUI creation
   /nologo  Suppress startup logo
   /sl      Specify the resource string length limit in percentage
Flags may be either upper or lower case


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\rc.exe |
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

* Original Filename: rc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/ce6079ce8557c4dbe1f611b19919d70bb6fa9317c426801cc4a1e3b72646f532/detection


## Possible Misuse

*The following table contains possible examples of `rc.exe` being misused. While `rc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\rc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


