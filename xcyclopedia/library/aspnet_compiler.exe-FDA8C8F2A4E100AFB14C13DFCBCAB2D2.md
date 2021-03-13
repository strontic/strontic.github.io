---
title: aspnet_compiler.exe | aspnet_compiler.exe
excerpt: What is aspnet_compiler.exe?
---

# aspnet_compiler.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe`
* Description: aspnet_compiler.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `FDA8C8F2A4E100AFB14C13DFCBCAB2D2`
SHA1 | `19DFD86294C4A525BA21C6AF77681B2A9BBECB55`
SHA256 | `99A2C778C9A6486639D0AFF1A7D2D494C2B0DC4C7913EBCB7BFEA50A2F1D0B09`
SHA384 | `A078B71620EBD3CF44837940D6AED33F2C5B021D28D1AD108E25F72FF0B860CC70D00648040D1263B03601D1672279A8`
SHA512 | `94F0ACE37CAE77BE9935CF4FC8AAA94691343D3B38DE5E16C663B902C220BFF513CD02256C7AF2D815A23DD30439582DDBB0880009C76BBF36FF8FBC1A6DDC18`
SSDEEP | `768:fF9E8FLLs2Zokf85d9PTV6Iq8Fnqf7P+WxqWKnz8DH:ffE6EkfOd9PT86dWvKgb`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `03D5ACF8DDFA65448F33D8C2E241A9E0AAFD6B5C`
PE256 | `CFA2158EBD24040C702CA7F589CF478C74C477DDB482824F4C8D183313FFE9DE`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ASP.NET Compilation Tool version 4.8.4084.0
Utility to precompile an ASP.NET application
Copyright (C) Microsoft Corporation. All rights reserved.

Usage:
aspnet_compiler [-?] [-m metabasePath | -v virtualPath [-p physicalDir]]
                [[-u] [-f] [-d] [-fixednames] targetDir] [-c]
                [-x excludeVirtualPath [...]]
                [[-keyfile file | -keycontainer container]
                     [-aptca] [-delaySign]]
                [-errorstack]

-?            Prints this help text.
-m            The full IIS metabase path of the application. This switch cannot
              be combined with the -v or -p switches.
-v            The virtual path of the application to be compiled (e.g.
              "/MyApp"). If -p is specified, the physical path is used to
              locate the application. Otherwise, the IIS metabase is used, and
              the application is assumed to be in the default site (under
              "/LM/W3SVC/1/Root"). This switch cannot be combined with the -m
              switch.
-p            The physical path of the application to be compiled. If -p is
              missing, the IIS metabase is used to locate the app. This switch
              must be combined with -v.
-u            If specified, the precompiled application is updatable.
-f            Overwrites the target directory if it already exists. Existing
              contents are lost.
-d            If specified, the debug information is emitted during
              compilation.
targetDir     The physical path to which the application is compiled. If not
              specified, the application is precompiled in-place.
-c            If specified, the precompiled application is fully rebuilt. Any
              previously compiled components will be re-compiled. This option
              is always enabled when targetDir is specified.
-x            The virtual path of a directory that should be excluded from
              precompilation. This switch can be used multiple times.
-keyfile      The physical path to the strong name key file.
-keycontainer Specifies a strong name key container.
-aptca        If specified, the strong-name assembly will allow partially
              trusted callers.
-delaysign    If specified, the assembly is not fully signed when created. 
-fixednames   If specified, the compiled assemblies will be given fixed names.
-nologo       Suppress compiler copyright message.
-errorstack   Shows extra debugging information that can help debug certain
              conditions.

Examples:

The following two commands are equivalent, and rely on the IIS metabase. The
compiled application is deployed to c:\MyTarget:
    aspnet_compiler -m /LM/W3SVC/1/Root/MyApp c:\MyTarget
    aspnet_compiler -v /MyApp c:\MyTarget

The following command compiles the application /MyApp in-place. The effect is
that no more compilations will be needed when HTTP requests are sent to it:
    aspnet_compiler -v /MyApp

The following command does *not* rely on the IIS metabase, as it explicitly
specifies the physical source directory of the application:
    aspnet_compiler -v /MyApp -p c:\myapp c:\MyTarget


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: aspnet_compiler.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/99a2c778c9a6486639d0aff1a7d2d494c2b0dc4c7913ebcb7bfea50a2f1d0b09/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-DF5419B32657D2896514B6A1D041FE08.md) | 75




MIT License. Copyright (c) 2020-2021 Strontic.


