---
title: ctrpp.exe | parse/validate performance counter manifest and generate helper source files
excerpt: What is ctrpp.exe?
---

# ctrpp.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ctrpp.exe`
* Description: parse/validate performance counter manifest and generate helper source files

## Hashes

Type | Hash
-- | --
MD5 | `5DC2ABBECE32570B242E698F633F5EDB`
SHA1 | `5ACA6D7C4E9361CAE24DC630008F19D664FD13FF`
SHA256 | `0FD458FDA1E397CFCBACE36FBFD83AB337D4203CBE3B6880CB00664D6734744A`
SHA384 | `59EF796040892402C8B70CDB81331F52903397EB8C5832880CB915D73ADF0C49C31B9E86EE616C27860233A1D09A6FCA`
SHA512 | `6537E3C904963B98F4531278CC1A64BDD83139CD44F6DA6EC0D21B40CB4C750A67A70CD6153B01422EEA4E1A9D7F9D1C1E4E227B6D7382277764D5434C55C857`
SSDEEP | `3072:Epr1jLGDbMtRM6Im/bQZU8oQNaK3vGbu9lMcIgeVw70reqnl1PWyHSb7Bt1c2iec:Epr5I6RM6IubQZU8oQkgGbZyb7Y`
IMP | `4A5023F965CE7575753F80A44E96FAD5`
PESHA1 | `DB93779DC17AC4C79BEA7F330A7868E52414BD49`
PE256 | `1AA8A9D493F5533ECCE19B8A8796B7962DAE4C283E42EC402EE452CE09FD497E`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ctrpp.exe |
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

* Original Filename: CTRPP.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ctrpp.exe](ctrpp.exe-252B7132D2D8C35CDDE5EA5885DFA671.md) | 40




MIT License. Copyright (c) 2020 Strontic.


