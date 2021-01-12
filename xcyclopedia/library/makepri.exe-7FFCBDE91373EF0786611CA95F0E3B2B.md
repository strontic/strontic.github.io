---
title: makepri.exe | Command line tool for creating PRI files
excerpt: What is makepri.exe?
---

# makepri.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\makepri.exe`
* Description: Command line tool for creating PRI files

## Hashes

Type | Hash
-- | --
MD5 | `7FFCBDE91373EF0786611CA95F0E3B2B`
SHA1 | `C541C3D6DD0C9539D53C19E08775DDFFAC4E2A7E`
SHA256 | `D497C9ED1AC550CDA0CE18A5C94AD0F70A306B5E579019554EB2B2979495E316`
SHA384 | `34FFD65E5681DBC68FB3FDB8AC791A850D446E1EE2D811CCFFF4DC0E72ABDA66DB574EE7C46FDDAA98FF4B0A07472D1F`
SHA512 | `186ED93734D006A0DC01C876312D18847037964F555CFBE243F578CA01371EF2D9A2192B307C879D8D4623C1A74D1309A547AECCBDCC30F24966CA94E76570CD`
SSDEEP | `12288:JikF735N03e6BbWb+BFlLNqo1vk5YTdFrkugItWlOmE5yujmuC5yh4ZTyj:8kFLU9RNTLr9gItWlSC0KZTyj`
IMP | `E2CC7C2E396C44A413B2BAACEE086045`
PESHA1 | `A80157C6998EDCB16644D29339EEC8E68BAB82F3`
PE256 | `5ACA3AF986ECE5C0376987F8E9D21C3D8C246A56021131651483B53030ABEDBC`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\makepri.exe |
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

* Original Filename: Makepri.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d497c9ed1ac550cda0ce18a5c94ad0f70a306b5e579019554eb2b2979495e316/detection





MIT License. Copyright (c) 2020 Strontic.


