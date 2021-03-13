---
title: ResGen.exe | Microsoft .NET Framework Resource Generator
excerpt: What is ResGen.exe?
---

# ResGen.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\ResGen.exe`
* Description: Microsoft .NET Framework Resource Generator
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `2CE714E5B060916C5906D89652B1950A`
SHA1 | `2C5CFD46A12CE04C6FE221E81FF18B49AEA39386`
SHA256 | `2A6F7E904A822302C7D659EC976E897DFF8BCC7F3643DE877C6F87CA9B0A5DF9`
SHA384 | `DBF38279D1EB8AC43DC969B36421BB128DE4A1C5AC1D1E99D3CF5A912DE39E90967404569A3B86DEC053CEABD560298E`
SHA512 | `2296DBE9C10DC63CC55801A0FFDC22BA9E6514EE78FD447FB6E31A4E58FBBDDAA01A4F4AC064853482F888DF7915B10D82A45E4C3C388410F3053034ED1DF166`
SSDEEP | `1536:AKR6BqOrMJ0OjEirbeMlGQddeXHsYendvLHdjJXu6HV/EgLsqmXitf8TLCnffbe8:e+DEglG+deX2ndD1JeqtEg4qmXitf8TJ`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `845A7B3D5CC651723B548FBEE64AA4FC84D1D0EC`
PE256 | `6C75F0215DDF05C2334AAF7E2C501180FA6E0190D463F3227F15D4C748E4065C`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Resource Generator 
[Microsoft .Net Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation.  All rights reserved.

Usage:
   ResGen inputFile.ext [outputFile.ext] [/str:lang[,namespace[,class[,file]]]]
   ResGen [options] /compile inputFile1.ext[,outputFile1.resources] [...]
   ResGen inputFile.ext2 [outputDirectory]
Where .ext is .resX, .restext, .txt or .resources
and .ext2 is .resources.dll, .dll or .exe. outputDirectory must already exist.
Resources will be extracted under outputDirectory in resW format.

Converts files from one resource format to another.  If the output
filename is not specified, inputFile.resources will be used.
Options:
/compile        Converts a list of resource files from one format to another
                in one bulk operation.  By default, it converts into .resources
                files, using inputFile[i].resources for the output file name.
/str:<language>[,<namespace>[,<class name>[,<file name>]]]] 
                Creates a strongly-typed resource class in the specified
                programming language using CodeDOM. In order for the strongly
                typed resource class to work properly, the name of your output 
                file without the .resources must match the
                [namespace.]classname of your strongly typed resource class.
                You may need to rename your output file before using it or
                embedding it into an assembly. 
/useSourcePath  Use each source file's directory as the current directory
                for resolving relative file paths.
/publicClass    Create the strongly typed resource class as a public class.
                This option is ignored if the /str: option is not used.
/r:<assembly>   Load types from these assemblies. A ResX file with a previous
                version of a type will use the one in this assembly, when set.
/define:A[,B]   For #ifdef support in .ResText files, pass a comma-separated
                list of symbols.  ResText files can use "#ifdef A" or "#if !B".
/allowUntrustedFiles
                Process files that are in the Internet or Restricted zone or
                have the mark of the web on the file.

Miscellaneous:
@<file>         Read response file for more options. At most one response file
                may be specified, and its entries must be line-separated.

.restext & .txt files have this format:

    # Use # at the beginning of a line for a comment character.
    name=value
    more elaborate name=value

Example response file contents: 

    # Use # at the beginning of a line for a comment character.
    /useSourcePath
    /compile
    file1.resx,file1.resources
    file2.resx,file2.resources


Language names valid for the /str:<language> option are:
c#, cs, csharp, vb, vbs, visualbasic, vbscript, js, jscript, javascript, c++, mc, cpp

```

### Usage (stderr):
```cmhg
ResGen : error RG0000: The file named "help" does not have a known extension.  Managed resource files must end in .ResX, .restext, .txt, .resources, .resources.dll, .dll or .exe. Response files must end in .rsp and be specified as @respFile.rsp.

```

### Child Processes:
csrss.exe wininit.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\ResGen.exe |
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

* Original Filename: ResGen.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/2a6f7e904a822302c7d659ec976e897dff8bcc7f3643de877c6f87ca9b0a5df9/detection





MIT License. Copyright (c) 2020-2021 Strontic.


