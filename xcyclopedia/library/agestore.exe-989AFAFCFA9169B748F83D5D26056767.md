---
title: agestore.exe | Microsoft AgeStore
excerpt: What is agestore.exe?
---

# agestore.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\agestore.exe`
* Description: Microsoft AgeStore

## Hashes

Type | Hash
-- | --
MD5 | `989AFAFCFA9169B748F83D5D26056767`
SHA1 | `1111BD760FD5DACD23DA58AD0E9B41131B0A1E7D`
SHA256 | `66E7E3434376EBF4CD942D9D942317187E1841F295ABC74A5C5B71166E18DECC`
SHA384 | `DC917E25FBF6A884B88C2B0A44202B674AA2D958A46B04A08A98D7096F163C74676DE498E6B3C96A1F59BEEC7679133F`
SHA512 | `2185DB81C23D67993E1724588B8D6A523613C26ED43CDAB79A4DCB656A5F81792B27AEF2C21CBF58784B662CC5E371589F7949A06E75FFC5F4B834448D54452B`
SSDEEP | `384:H5WEH1ZKMloTObvK8X7DaOePKteWSU6ZWvh+uwGy6ifl/zde:ZbHN7DQytg8+ui`
IMP | `8377D170587C399850EDF9713DDCA88D`
PESHA1 | `F3C95B657B28EDE9C4421A1091A56C1C9EA1D560`
PE256 | `420DA9187B47133532C0E9F379F0B84BEE31D70AEC0386BA91CB480A9993233D`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\agestore.exe |
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

* Original Filename: agestore.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\agestore.exe](agestore.exe-E04D7BB216C5BB4A8B0323AE61030558.md) | 29




MIT License. Copyright (c) 2020-2021 Strontic.


