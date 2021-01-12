---
title: srctool.exe | Microsoft Stream Utility
excerpt: What is srctool.exe?
---

# srctool.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\srcsrv\srctool.exe`
* Description: Microsoft Stream Utility

## Hashes

Type | Hash
-- | --
MD5 | `CC3DD5C588F411FA1E8A8488E1890A3A`
SHA1 | `B876383D85097D3353379F1C76AB8DEBD044D8A7`
SHA256 | `B910A86B3AE4A14030CC5A0EEB16241624C8F0B3C37D8E3E3114673C2978B6B0`
SHA384 | `96DA222CBFF93BF382AF295A5B560DC9A5FE527F4BFA2243273D6372B2EB10EB5182E6CC255845E06634249B7D50B844`
SHA512 | `B250C2E2586B85BF10DEE16ABCE3674287AB8ED5E6930F05F8F6A2160C9A8D2D11A2EA4D11D909792587D5B33FC4C560279B1852595BBA412DA9AD434A04D177`
SSDEEP | `768:A+nNFrLsApsLztiL2Kvl0kyNSqKYX9Zo2jMLc+y:A8rXsLztLKv+pNSqKYNZo0Mfy`
IMP | `4EA0CBA5DDF2B598E44CBA0FB1FE5764`
PESHA1 | `F5FE3AACF89EC2A131D5A8CB4B3311D85C66F9F9`
PE256 | `0B447F838D8E3D4FEA02958E7789140E66A7EE4363D4AC4FA919E2918202AA2A`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\srcsrv\srctool.exe |
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

* Original Filename: srctool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b910a86b3ae4a14030cc5a0eeb16241624c8f0b3c37d8e3e3114673c2978b6b0/detection





MIT License. Copyright (c) 2020 Strontic.


