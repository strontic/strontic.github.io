---
title: aspnet_compiler.exe | aspnet_compiler.exe
excerpt: What is aspnet_compiler.exe?
---

# aspnet_compiler.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe`
* Description: aspnet_compiler.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `209965064648C56880D8E9DFA3C15793`
SHA1 | `D4B0484687A0AEA6B9E928F1DC4ED032A726F72E`
SHA256 | `39BB2299B678812B87919543D83377ABB77D887E504AA418C1787889169332DC`
SHA384 | `E44530A0C04569FB8C239286D02C10BB50430690CDE02E0A182485CE656CCAA80FD0C2B04D58AEBB79397604DBFC21AA`
SHA512 | `BD6B33D5904064990A48624E337BD724B18DCD9A1BF9276F188FEC446899FD60BA573E18A40ABAD84EFB3E2812FF929A34B7403B3BD97E4BD0F59771BE0ECCD2`
SSDEEP | `768:BF9E8FLSs2Zokf85db6TX6Iq8bnqf7PTEmxW/C+Ql7:BfE6hkfOdb6TOUwEp/C+U`
PESHA1 | `AD4D742952B76D704A027D1CEA6296239182DE96`
PE256 | `C9150A06645259D8977C0E425946E7AD7E41E37D97301928C2CF2FAD20F31AAE`

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
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe |
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/39bb2299b678812b87919543d83377abb77d887e504aa418c1787889169332dc/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-1888E453E7FC66D13903009B2C68832E.md) | 72
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-FDA8C8F2A4E100AFB14C13DFCBCAB2D2.md) | 66
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-DF5419B32657D2896514B6A1D041FE08.md) | 66

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


