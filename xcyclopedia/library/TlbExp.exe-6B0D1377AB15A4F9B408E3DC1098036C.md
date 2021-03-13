---
title: TlbExp.exe | Microsoft .NET Assembly to Type Library Converter
excerpt: What is TlbExp.exe?
---

# TlbExp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\TlbExp.exe`
* Description: Microsoft .NET Assembly to Type Library Converter
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `6B0D1377AB15A4F9B408E3DC1098036C`
SHA1 | `DD456F55EBCF42C3843A8F718A6820B0D18CEE4B`
SHA256 | `60A2BDE6B8EEA903DD00660B9F9500BB9664004A13F62C9272B5ADB28F008BDD`
SHA384 | `127B1E2C7BA2852AB975CD2F5510BBCC7B5CC1386A58DD2120C333DE377ACF9D6D57AA22A684057FFE599CB209FB6DE0`
SHA512 | `3E7CECD0B434179111A4DF2664E9EAF55664F88AAA2C57EADFBDAD90A9DA5E9496FD7C16208D27A19C26FEC47330CC46229B7580BD6F8E678B72A9BA396FB72F`
SSDEEP | `1536:sN2wX1c9RNBx6IqvdG5xb2Hf0VDSqgD2LJ6lXz8kZal+:Xwy9RNBgIqvdG5xb2HfUDSFD2LJ6lXzt`
PESHA1 | `47611A1AF4ECD45CF0581C5F69AC9196E0A72CD7`
PE256 | `1E363CB7C1627123DE2839FA9D0029BBE341A269020023387A1B28A9DAD9BA19`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Assembly to Type Library Converter 4.8.4084.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Syntax: TlbExp AssemblyName [Options]
Options:
    /out:FileName               File name of type library to be produced
    /tlbreference:TypeLibrary   Type library used to resolve references
    /tlbrefpath:Path            Path used to resolve referenced type libraries
    /asmpath:Directory          Look for assembly references here
    /win32                      Create a 32-bit type library
    /win64                      Create a 64-bit type library
    /oldnames                   Do not ignore COM invisible types when
                                decorating names (old-rules)
    /nologo                     Prevents TlbExp from displaying logo
    /silent                     Suppresses all output except for errors
    /silence:WarningNumber      Suppresses output for the given warning 
                                (Can not be used with /silent)
    /verbose                    Displays extra information
    /names:FileName             A file in which each line specifies the
                                capitalization of a name in the type library.
    /? or /help                 Display this usage message

```

### Usage (stderr):
```cmhg
TlbExp : error TX0000 : Could not load file or assembly 'file:///C:\Users\user\help' or one of its dependencies. The module was expected to contain an assembly manifest.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\TlbExp.exe |
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

* Original Filename: TlbExp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/60a2bde6b8eea903dd00660b9f9500bb9664004a13f62c9272b5adb28f008bdd/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\TlbExp.exe](TlbExp.exe-3E5110E620F7742CBBE7DB9852D3483E.md) | 85




MIT License. Copyright (c) 2020-2021 Strontic.


