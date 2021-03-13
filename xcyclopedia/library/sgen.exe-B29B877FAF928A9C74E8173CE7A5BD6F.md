---
title: sgen.exe | .NET Frameworks Xml serialization assembly generation Tool
excerpt: What is sgen.exe?
---

# sgen.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\sgen.exe`
* Description: .NET Frameworks Xml serialization assembly generation Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `B29B877FAF928A9C74E8173CE7A5BD6F`
SHA1 | `2974CDCC3A2B5CFC4E4FFD42CE70AFC8E64CBA57`
SHA256 | `609ACC482C1712F6AF8F7B1314CB7896BABBD1B1D65BD2A181951975FD76551B`
SHA384 | `B87618CB9458E35EDC108A391ADEBF5CD518C2463B24D3CCB74A939E7BE16F877630C46E15301136A03C31054114F1AF`
SHA512 | `5D9943B1EDD90A12F09C203C2DC71D1229BBF1C89C98D5F5B5AF2583DC362282A40554C4AC0F7B22E1EAF06D97962953A09BEC6465F325EB7B3A6CED02A7DF83`
SSDEEP | `768:rQC5IzfNUYPWpZbFdlHDqCZh6Iq8zNGO2QIIIIzGJaqWFnr8U/Tbf:95IzfumWpZxd52CZoKEOEJ4Kof`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `3A585E05E4F2898587EA14DDD62B8FE07B7858B3`
PE256 | `A44AC420A9B461118312B8453CC701EB2F4DD2FDB79A79324D7CA7555EF21268`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Xml Serialization support utility
[Microsoft (R) .NET Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation. All rights reserved.

Generates serialization assemblies for use with XmlSerializer.
The utility allows developers to pre-generate assemblies for serialization
and deploying the assemblies with the application.

Usage: sgen.exe [[/assembly:<assembly name>] | [<assembly file location>]]
    [/type:] [/reference:] [/compiler:] [/debug] [/keep] [/nologo]
    [/silent] [/verbose]


  Developer options:
    /assembly:   Assembly location or display name. Short form is '/a:'.
    /type:       Generate code for serialization/deserialization of the
                 specified type from the input assembly. Short form is '/t:'.
    /reference:  Reference metadata from the specified assembly files.
                 Short form is '/r:'.
    /compiler:   Visual C# compiler options to use while compiling generated
                 code. Short form is '/c'.
                 For complete list of available options see c# compiler help.
    /proxytypes  Generate serialization code only for proxy classes and web
                 method parameters. Short form is '/p'.
    /debug       Generate image which can be used under a debugger.
                 Short form is '/d'.
    /keep        Keep source code and compiler temp files. Short form is '/k'.
    /force       Forces overwrite of a previously generated assembly.
                 Short form is '/f'.
    /out:        Output directory name (default: target assembly location).
                 Short form is '/o:'.
    /parsableerrors
                 Print errors in a format similar to those reported by
                 compilers.

  Miscellaneous options:
    /? or /help  Show this message
    /nologo      Prevents displaying of logo. Short form is '/n'.
    /silent      Prevents displaying of success messages. Short form is '/s'.
    /verbose     Displays verbose output for debugging. Short form is '/v'.
                 List types from the target assembly that cannot be serialized
                 with XmlSerializer.

```

### Usage (stderr):
```cmhg
Warning: Ignoring invalid command line argument: '--help'.
Missing required command-line argument: The name of the source assembly.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\sgen.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sgen.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/609acc482c1712f6af8f7b1314cb7896babbd1b1d65bd2a181951975fd76551b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\sgen.exe](sgen.exe-2B3AA895D991740E5F04B2DE825A41A4.md) | 72




MIT License. Copyright (c) 2020-2021 Strontic.


