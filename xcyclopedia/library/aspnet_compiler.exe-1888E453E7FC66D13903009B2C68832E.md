---
title: aspnet_compiler.exe | aspnet_compiler.exe
excerpt: What is aspnet_compiler.exe?
---

# aspnet_compiler.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe`
* Description: aspnet_compiler.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1888E453E7FC66D13903009B2C68832E`
SHA1 | `5C49B59F6119D31F70503E69F2FDF6B056459536`
SHA256 | `ED0D718E30178E817FB642E787ADEA679C8843C16142AAA76FED93EB75569E63`
SHA384 | `78FC5B07D4DE1B93C7612B31A7892DB0448B30851A4517BD1FF0033BBCC1C484B3C7CF29311C22AB6EC7B289D94BD327`
SHA512 | `9CEE0217A0CC10AB4E17E68B5EE5058B2359628D30F127B0FAEB3F0F4CAA0396141F394BF4725F4514C4526EB68159A15CF64749BB845FD610E9C4215AF0FC15`
SSDEEP | `768:aF9E8FLLs2Zokf85db3TX6Iq8bnqf7PiI4WE6JZ:afE6EkfOdb3TOUtIPE6f`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `FF1DD315DF9A726606A255F7E9E51334ACE6C58D`
PE256 | `1D02DE409F3AC34ED239D0B29F5756F8EAFC33378CD0F21277E00DB9B39799B1`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ASP.NET Compilation Tool version 4.8.4161.0
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
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: aspnet_compiler.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/ed0d718e30178e817fb642e787adea679c8843c16142aaa76fed93eb75569e63/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-FDA8C8F2A4E100AFB14C13DFCBCAB2D2.md) | 68
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-209965064648C56880D8E9DFA3C15793.md) | 72
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-DF5419B32657D2896514B6A1D041FE08.md) | 65

## Possible Misuse

*The following table contains possible examples of `aspnet_compiler.exe` being misused. While `aspnet_compiler.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `Name: Aspnet_Compiler.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `- Command: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe -v none -p C:\users\cpl.internal\desktop\asptest\ -f C:\users\cpl.internal\desktop\asptest\none -u`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `- Path: c:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `- Path: c:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `- Link: https://ijustwannared.team/2020/08/01/the-curious-case-of-aspnet_compiler-exe/`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


