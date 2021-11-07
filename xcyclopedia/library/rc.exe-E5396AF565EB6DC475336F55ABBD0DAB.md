---
title: rc.exe | Microsoft Resource Compiler
excerpt: What is rc.exe?
---

# rc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\rc.exe`
* Description: Microsoft Resource Compiler

## Hashes

Type | Hash
-- | --
MD5 | `E5396AF565EB6DC475336F55ABBD0DAB`
SHA1 | `D9369DB8E4A0582B750A0E513E25F25E849AA05C`
SHA256 | `D48522470FA7DCCA448C79781B8E7091CE16521DCEB2AB97BF0F62E7DFD137BC`
SHA384 | `BF487AFD7B1F09C6759EE7C78FD48A91E76617790991B2C346E6787E0FC9AAEE17AF192B61B429FCD2408B3BE933DA1B`
SHA512 | `9F13426F7BB31E05E79BEB3657F73FEB5BC270569D30426508A949542BF7A2B54BF9766EDFAA97B126D95627DE238CEDEE91719292715CFB810036E3B2B1F59A`
SSDEEP | `1536:vbj2+DH2P19sKLfI67+rNlhK7BI3Shv6FUXui:f2+DH2JbFgfK7BI32v6FU+i`
IMP | `14364FD8F9FE355C6DC3AB49D1F37AB6`
PESHA1 | `6351A3B0586B7C2E5A6F901019D8D7D4E2A88BDA`
PE256 | `B0F15BF5F23170E50755C4446A1F6158E4D82350FADDECF1F58118CD84169465`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\rc.exe |
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

* Original Filename: rc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d48522470fa7dcca448c79781b8e7091ce16521dceb2ab97bf0f62e7dfd137bc/detection


## Possible Misuse

*The following table contains possible examples of `rc.exe` being misused. While `rc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\rc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


