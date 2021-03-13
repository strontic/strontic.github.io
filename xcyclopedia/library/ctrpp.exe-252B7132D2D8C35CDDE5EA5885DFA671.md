---
title: ctrpp.exe | parse/validate performance counter manifest and generate helper source files
excerpt: What is ctrpp.exe?
---

# ctrpp.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ctrpp.exe`
* Description: parse/validate performance counter manifest and generate helper source files

## Hashes

Type | Hash
-- | --
MD5 | `252B7132D2D8C35CDDE5EA5885DFA671`
SHA1 | `60B34539D81C512A6085CA040A0F14A75CB8DA37`
SHA256 | `C0F782DEFF229A8D80B7EA3EE1FD623DB4D0B02DAFADD0CE474E2A7BD56ED07D`
SHA384 | `7C21FC85862766208B0CE72B6EE589CE274CBA4933F57AEA086683C8116CB2097E24BFF1C9C37266DA0E50CC4F9ECA5D`
SHA512 | `B4A2B4F7F7748C47D9145F2ADD6376C3A519C42CBDAEB417E0D4B6C392CDBDF0EA3471EA863AD931BDB4FFF4303E221BCD327B2849505283DBFCF170B8B7E148`
SSDEEP | `3072:X3PWrg5dlM8IgeVw70reqnl1PWiQ/B3lngY9MCKM48u44VnfaS+Kt1c2ieDF1dtW:PWrA305X44VfaS/tW`
IMP | `5D9B62E065F43FC3F962709B0D79F60C`
PESHA1 | `F08C7A5C6421A5586AD5A442FAA00493A9041E26`
PE256 | `0F82C1B91FBE5EF8D9A9DA84492E5802A5579D822DB7678B28FB1A94BBA2AF2D`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: ctrpp [-NotificationCallback] [-MemoryRoutines] [-o <filename>]
             [-rc <filename>] [-migrate <filename>] [-prefix <prefix>] <manifest>

    -NotificationCallback - Generate customized notification callback template.
                            Similar to "callback" attribute in <provider> element.
    -MemoryRoutines       - Generate memory allocation/free routine templates.
    -Legacy               - Revert to previous ctrpp file-output behavior (see below).
    -o <filename>         - Generate header file for provider.
    -ch <filename>        - Generate header file for containing counter names and ids.
    -rc <filename>        - Generate resource source file.
    -migrate <filename>   - Generate manifest file conforming to the latest schema version.
                            This switch cannot be used with other switches.
    -prefix <prefix>      - Prefix to be added to functions and variables generated.
    -backcompat           - Generates code that is binary compatible with OSs prior
                            to Windows 7.
    -summary <path>       - generate binary counter file per provider
                            generate summary global file GenSumResource.BIN
    -sumPath <path>       - Path to generate binary counter files
                            default .

    <manifest>            - counter manifest to be processed

Examples: ctrpp -o header.h -rc resource.rc component.man
          ctrpp -legacy component.man
          ctrpp -migrate new.man old.man

Legacy Mode:
The -legacy switch causes ctrpp to generate four output files: two header files, a resource file, and a source code file.  This mimics the behavior found in previous versions of ctrpp.  The -o, -ch, -rc and -prefix options cannot be used in conjunction with -legacy.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ctrpp.exe |
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

* Original Filename: CTRPP.EXE
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
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ctrpp.exe](ctrpp.exe-5DC2ABBECE32570B242E698F633F5EDB.md) | 40




MIT License. Copyright (c) 2020-2021 Strontic.


