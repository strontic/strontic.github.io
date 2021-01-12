---
title: sgen.exe | .NET Frameworks Xml serialization assembly generation Tool
excerpt: What is sgen.exe?
---

# sgen.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\sgen.exe`
* Description: .NET Frameworks Xml serialization assembly generation Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `2B3AA895D991740E5F04B2DE825A41A4`
SHA1 | `7E464CB8DBE13FB89EDCF3FB9FAF979810A2611F`
SHA256 | `1418BB188E22F5EE1210EDEEA96387A4FB3C37D1FB089CBC9CE2E016DFF0C096`
SHA384 | `146CC92FEC773FE38DCF782242AC3BB2E25B405762C17CF370CE09928CF5864602FB7F2D20AB3FEBEB2F834CDB5D1C3D`
SHA512 | `60CAFE735684C434707510015B1C1D19BDC2632F836618B4CA2592520E4434A4D0B95E13C5CFAD2C3EC8B49DABEF3E41F9C7A775279772FEAFE09C03EBB1B4AB`
SSDEEP | `768:yQC5IzfNcYPWpZbFdlHDqCUh6Iq8zNGOxyQIIIIvGdjpqW1m8eHCL0:w5IzfGmWpZxd52CUoKEO+drd+`
IMP | `n/a`
PESHA1 | `5347D603057E208A0127755E51DBB1C754D0F7E2`
PE256 | `D3A0652045A4ACB7F5DF122ED231A0551A26F81A3D37C14D09D1D128BC1DDE07`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\sgen.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/1418bb188e22f5ee1210edeea96387a4fb3c37d1fb089cbc9ce2e016dff0c096/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\sgen.exe](sgen.exe-B29B877FAF928A9C74E8173CE7A5BD6F.md) | 72




MIT License. Copyright (c) 2020 Strontic.


