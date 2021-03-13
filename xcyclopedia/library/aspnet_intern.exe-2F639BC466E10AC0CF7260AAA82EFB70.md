---
title: aspnet_intern.exe | aspnet_intern.exe
excerpt: What is aspnet_intern.exe?
---

# aspnet_intern.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\aspnet_intern.exe`
* Description: aspnet_intern.exe
* Comments: aspnet_intern.exe


## Hashes

Type | Hash
-- | --
MD5 | `2F639BC466E10AC0CF7260AAA82EFB70`
SHA1 | `14D3F01A0425C8AAB3E2A187558C000ACBC3F376`
SHA256 | `AA251111C007308805F3FE888298D52CA80DBE2D0C622C8FF5AD4B32BF38D573`
SHA384 | `D3162EA04F355305959F80148CE07A85DD00380C583983B76A85E833C4E1A7527E54D4C5F2ECAA0A104ADB31B31CC141`
SHA512 | `619F82ABBC3B12E6912AEEEEBDA4685EA315090971F95504631357E6E9ACD698A0379C309E5014CF3A335FF330E84159F905FD32238DFD84F5E8651679CF539E`
SSDEEP | `1536:oSVxegzJEgTb6MISFdrpgbAcoT1twP5kmr:oqMgz2gH6UFdr6bAcoTHwPpr`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `02F1A56AD7DD1F83FC3B2E61E54A7179AD9DDF02`
PE256 | `503EC558D8A28A5B875AD32A5CE113182DD97BAC84DAEB3EF338D9838A1FECC1`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ASP.NET Intern version 4.8.4084.0
Utility to analyze ASP.NET web applications and intern common .NET assemblies found in the Temporary ASP.NET Files directory.
Copyright (C) Microsoft Corporation. All rights reserved.

aspnet_intern [-mode analyze|exec|clean|query] [-sourcedir <input source path>] [-interndir <output target interned path>] 

-?                  Display this help text.
-mode analyze       Analyze source directory for managed assemblies that can be
                    interned for cross application sharing (default)
-mode exec          Perform interning of managed assemblies for cross
                    application sharing
-mode query         Display information about shared assemblies in the intern
                    directory
-mode clean         Deletes the intern directory and all symbolic links in the
                    source directory pointing at files in the intern directory
-sourcedir          Source directory to scan for potential assembly interning
                    candidates.  Use either the Temporary ASP.NET Files
                    directory location, or the location defined in the
                    system.web/compilation/tempDirectory web.config attribute.
-interndir          The location where interned assemblies are stored for
                    sharing across ASP.NET applications.
-v                  Verbose output
-bpc                Bypass platform checks
-minrefcount        The minimum number of times an assembly was found in
                    different locations for the assembly to be considered an
                    interning candidate. (Default: 3)
-whitelist          Only allows interning of managed assemblies that are
                    contained in this file.  Value should be the full file path
                    to a line delimited list of patterns which may contain a
                    trailing asterisk which will turn the pattern into a prefix
                    match.  i.e. MyAssembly-1.*

Examples:

       aspnet_intern -mode analyze -sourcedir "C:\Windows\Microsoft.NET\Framework\v4.0.30319\Temporary ASP.NET Files"
       aspnet_intern -mode exec -sourcedir "C:\Windows\Microsoft.NET\Framework\v4.0.30319\Temporary ASP.NET Files" -interndir C:\ASPNETCommonAssemblies
       aspnet_intern -mode clean -sourcedir "C:\Windows\Microsoft.NET\Framework\v4.0.30319\Temporary ASP.NET Files" -interndir C:\ASPNETCommonAssemblies
       aspnet_intern -mode query -interndir C:\ASPNETCommonAssemblies


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\aspnet_intern.exe |
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

* Original Filename: aspnet_intern.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/aa251111c007308805f3fe888298d52ca80dbe2d0c622c8ff5ad4b32bf38d573/detection





MIT License. Copyright (c) 2020-2021 Strontic.


