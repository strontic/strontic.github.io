---
title: makepri.exe | Command line tool for creating PRI files
excerpt: What is makepri.exe?
---

# makepri.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\makepri.exe`
* Description: Command line tool for creating PRI files

## Hashes

Type | Hash
-- | --
MD5 | `EDB9A599FE4DE49FB5D70A805FEDD63D`
SHA1 | `17DA68AF745BF8B5E6A4B2C5C73BFB5B9D4FFA51`
SHA256 | `1B2A8914D473C652C8CA0A6C870B25035B6ACA5BF44290CFA53374C23F1929B2`
SHA384 | `F49800623EB3FA2604FFF96CF4B6347003433756C54F088801FB27601F56ACC837E67C5DF005139F47E027384399ED5C`
SHA512 | `83B5A82B67A48D670769314CB9062CE634C2755894D431A2DFB042C0A6B070AA58993E69A511C8616B2EE850A8AC7EE29F8EB0E92151312D74F70A5F46EB6856`
SSDEEP | `12288:s/qIT5H9ZLGXZZJMcrrjYApf/OeIkW6JO5+wcjxZoFHl4WgnHRIul8Y5NU+:HIFeZJMGHYzkW/502FFT6/lfN`
IMP | `7E43F6BBEA9D1E7AAB6DB0933316A62B`
PESHA1 | `B9BF70F036B7FD183929F4A3BD797EA172CACCA8`
PE256 | `6D667CD124214083E3BAE77D4197F3E0E7FFF35F251CD82458B4E32B07681ADD`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) MakePRI Tool
Copyright (C) 2013 Microsoft. All rights reserved.


Usage:
------
    MakePri.exe <Command> [options]

Example:
--------
    MakePri.exe new /pr C:\MyApp\src\ /cf C:\MyApp\priconfig.xml /in PackageName

Description:
------------
    MakePri.exe creates, dumps and does utility functions on a PRI file.
    A PRI file is an index of application resources (i.e. strings, files, etc).

Command Options:
----------------
    MakePri.exe createconfig   Creates a PRI Config file for use with other
                               commands
    MakePri.exe new            Creates a new PRI file from scratch
    MakePri.exe versioned      Creates a PRI file based off a previous version
    MakePri.exe resourcepack   Creates a PRI file that contains additional
                               resource variants for a base PRI
    MakePri.exe dump           Dumps the contents of a PRI file
    MakePri.exe help           Show this help page

Help:
    Specify a command with help for more detailed help
    MakePri.exe new /?


```

### Usage (stderr):
```cmhg
ERROR: PRI104: 0x80070057 - Unknown option specified - '-help'

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\makepri.exe |
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

* Original Filename: Makepri.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1b2a8914d473c652c8ca0a6c870b25035b6aca5bf44290cfa53374c23f1929b2/detection





MIT License. Copyright (c) 2020-2021 Strontic.


