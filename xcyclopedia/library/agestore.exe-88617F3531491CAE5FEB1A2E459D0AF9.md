---
title: agestore.exe | Microsoft AgeStore
excerpt: What is agestore.exe?
---

# agestore.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\agestore.exe`
* Description: Microsoft AgeStore

## Hashes

Type | Hash
-- | --
MD5 | `88617F3531491CAE5FEB1A2E459D0AF9`
SHA1 | `B50180CDB8814718CA10968AFAD14F4D89EFB03C`
SHA256 | `3B9D6DF43E8A03106DBA49297B8E49D19515A9F2378AAD4D2AB3D4F88E8AF36A`
SHA384 | `6376A55E1F0CE9A9D698998EBAE8B93944F24D11725AF9AC13A5CF313AB53E785FFF96A113819F6B61C1061DF9D7FE52`
SHA512 | `5DEA7B479F98A9D2665406A7268D92C08ADE0AA2A9713A6CD67E611EA883B69955C0306A7CBB40C6D7195A5C7CDDE4D8598B8BACC10800E1E90976A7DEFF90FB`
SSDEEP | `384:cwnm2NSDomVlUXt5ZbCJuLOR2WSU6ZW+wGyVThf4JeRlFI:c6m2uomVszGiCIt4w`
IMP | `CB99E29B685C706E58643B7AF4AE6715`
PESHA1 | `7638ACF60EC4DD0964DDC33E526B9E813EEAC776`
PE256 | `19AC3A4D1131F646BF2EC483ED5071553F28930BA1EA978D0AFDC1E59A6F34DD`

## Runtime Data

### Usage (stdout):
```cmhg
Last-Access-Time support is disabled on this computer.
Please read the documentation for more details.
Agestore will use the file creation time as the last access time.
please select either -date, -days, or -size

agestore [pathspec]

Deletes all files from a directory based on the last access time of the files.
[pathspec] defines the root path and file specification.
The default is all files in the current working directory

It runs in one of these modes...

-date=mm-dd-yy    - deletes all files that were last accessed before the specified date.
-days=xx          - deletes all files that were last accessed before today minus the
                    amount of days specified by 'xx'. 
-size=xx          - deletes files in order of last access time (oldest first), until all the
                    files in the directory total to the amount of bytes specified by 'xx'.
-size             - lists the amount of bytes in the directory.
-lat=<on/off>     - toggles filesytem support for last-access-time.

These other command line switches alter the behavior of the program.

-l                - list files only, don't delete
-s                - include subdirectories.
-k                - keep empty subdirectories - normally they are removed.
-q                - quiet mode stops listing of files as they are deleted.
-y                - eliminates the (y/n) prompt.
-r                - deletes RO files

This program deletes files.  You should run agestore with the -l switch
to see what it will delete, before actual usage.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\agestore.exe |
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

* Original Filename: agestore.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/3b9d6df43e8a03106dba49297b8e49d19515a9f2378aad4d2ab3d4f88e8af36a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\agestore.exe](agestore.exe-794ECE80B607AD6A630D876BA29EADD8.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-crt-conio-l1-1-0.dll](api-ms-win-crt-conio-l1-1-0.dll-98BF1DFED24AD5EDF28B973FFF8E5B1F.md) | 29




MIT License. Copyright (c) 2020 Strontic.


