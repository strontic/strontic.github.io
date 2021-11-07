---
title: aspnet_compiler.exe | aspnet_compiler.exe
excerpt: What is aspnet_compiler.exe?
---

# aspnet_compiler.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe`
* Description: aspnet_compiler.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `DF5419B32657D2896514B6A1D041FE08`
SHA1 | `EAE192043F75CA972697C3B1875988BEBD66F713`
SHA256 | `9ED0AA0A40C864F65FF867FD6B8491467786CE1BC60FD1E55F300A0FAE5A77B4`
SHA384 | `6C26ACC88CBF1EB9F1432FD02E1CFFC3D1B405B1D7CAA5A81302D2488BB4366476069D34C59B1F0A7218707C9E32632A`
SHA512 | `F1A7A409C99942B39060D327BBC2F0B7CF600E8C3D8E60164AE27A78E1A16C07DE58872B8864A0783D71CCAD5800C02ADE0AC14954B30A75A6B5C8D4B1FCD560`
SSDEEP | `768:TF9E8FLSs2Zokf85d9ITV6Iq8Fnqf7PxoqHpqWSd8sa8:TfE6hkfOd9IT86lqnSesa8`
PESHA1 | `705BB671A4C19169099E27ED41D9958C49E8B5D8`
PE256 | `79FBE5C1ABE4D3EA8985062A5508D299FE8E6EF56A483FB28506741E2BC6C987`

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
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_compiler.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9ed0aa0a40c864f65ff867fd6b8491467786ce1bc60fd1e55f300a0fae5a77b4/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_compiler.exe](aspnet_compiler.exe-FDA8C8F2A4E100AFB14C13DFCBCAB2D2.md) | 75

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


