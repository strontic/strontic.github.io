---
title: srctool.exe | Microsoft Stream Utility
excerpt: What is srctool.exe?
---

# srctool.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\srctool.exe`
* Description: Microsoft Stream Utility

## Hashes

Type | Hash
-- | --
MD5 | `EEA8C0C3F61C62609C8B3302C42B9151`
SHA1 | `549DA686DB806F357D515C5EA1A4B406220D36C7`
SHA256 | `00EDAA35802553A531E934A819BDA1EBF47A1D4C7C710245923D66884F8F85AF`
SHA384 | `84EF2F2CF938106BCB27D7AA4B8796847AFD1B735340C0FA4DDD413F58A9B8DA29CFD7A063BCCA963BDF18ADD2DDA5DE`
SHA512 | `F19CED2FC8A7DFFC27A2856F613250939DF7A6FB7326475B8A90807C0AA68BB9D9F64D42A357F43FA1C6C0F82F247220A67F32437232C0FBBB1FD413F5346827`
SSDEEP | `768:d/8VlU0C9yqKy2BF/CLqmrU2zVo0Fdhh6qASX:du+Z9yqKy/2mr7zVo0FcDSX`
IMP | `EB5E6B0512D3A3012D57AC991444B74A`
PESHA1 | `04F8248490A758ED485E0F794A95690707E85871`
PE256 | `1FC7EB84E5FAD3D041663E4EF25719FE263BD97F2B8492A0AE4A61C3C5C519F3`

## Runtime Data

### Usage (stdout):
```cmhg
srctool:
  Dumps source information from a pdb or srcsrv stream file.
  You must specify a pdb, executable, or srcsrv stream file on the
  command line.
Optional Parameters:
  -u  Displays only source files that are not indexed.
  -r  Dumps raw source data from the pdb.
  -s  Recurses subdirectories.
  -h  Dumps the hash/checksum of the source file.
      It is valid only when the -r or -u option is selected.
  -l:<mask>   Limits output to only source files that match this wildcard
              expression.
  -lf:<mask>  Same as -l except that the mask is applied only to the filename.
              Directory paths are ignored and all are matched.
  -x  Extracts the files, instead of simply listing them.
  -f  Extracts files to a flat directory.
  -n  shows version control commands and output while extracting.
  -d:<dir>  Specifies the directory to extract to.
  -c  Displays only the count of indexed files - no detail.
  -z  Returns zero on success or nonzero on failure.
  -o  Displays the full original version control extraction commands,
      disabling any VCS-specific output formatting heuristics.
  -a  Applies all available VCS-specific heuristics to parse the commands
      and output their contents in some user-friendly way.
      Without this flag, only the Source Depot (Microsoft internal) heuristic
      is applied.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\srctool.exe |
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

* Original Filename: srctool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


