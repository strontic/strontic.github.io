---
title: gacutil.exe | Microsoft (R) .NET Framework Global Assembly Cache Utility
excerpt: What is gacutil.exe?
---

# gacutil.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\gacutil.exe`
* Description: Microsoft (R) .NET Framework Global Assembly Cache Utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `F2FE4DF74BD214EDDC1A658043828089`
SHA1 | `1777FD3BBB4584ED820682659C495E0696CB6E91`
SHA256 | `974226C200F8EDAD7F4F7444DF62D9E87D09DC631803A0EDB3723DC99C484920`
SHA384 | `D5F3AC6E1CC32729AA113DAD3477E27FCEF35C576A929ADE82C6146A7327933CB2E7CE5E5FA2414F9529167BA2D8F714`
SHA512 | `FD14428D59DDFBC9DAD7033BD4A654B0D73CE783DD88F493019489669CD994863C1D6319E509C075E80DD41D37BD3FA805A9FC950E2F4EFC69EDA46912DF0B9F`
SSDEEP | `3072:UzYgOrGCg5a3ADbR0d4/dA9lq/M8MjHIqfKqxFqNL9pf:VICg5AYR0SmnDRdFFaN`
IMP | `37EA4407B538D703D6E995D8E0E0DDE7`
PESHA1 | `54C9861FD298BF7510D8F2A643DB49DC00E01142`
PE256 | `37FA9A94A5E6D6CB2352046B13558E17E07E4DA05529B42C74B251370A72B25B`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Global Assembly Cache Utility.  Version 4.0.30319.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Usage: Gacutil <command> [ <options> ]
Commands:
  /i <assembly_path> [ /r <...> ] [ /f ]
    Installs an assembly to the global assembly cache. <assembly_path> is the
    name of the file that contains the assembly manifest.
    Example: /i myDll.dll /r FILEPATH c:\projects\myapp.exe "My App"

  /il <assembly_path_list_file> [ /r <...> ] [ /f ]
    Installs one or more assemblies to the global assembly cache.  
    <assembly_list_file> is the path to a text file that contains a list of 
    assembly manifest file paths. Individual paths in the text file must be 
    separated by CR/LF.
    Example: /il MyAssemblyList.txt /r FILEPATH c:\projects\myapp.exe "My App"
      myAssemblyList.txt content:
      myAsm1.dll
      myAsm2.dll

  /u <assembly_display_name> [ /r <...> ]
    Uninstalls an assembly. <assembly_name> is the name of the assembly
    (partial or fully qualified) to remove from the Global Assembly Cache.
    If a partial name is specified all matching assemblies will be uninstalled.
    Example:
      /u myDll,Version=1.1.0.0,Culture=en,PublicKeyToken=874e23ab874e23ab
      /r FILEPATH c:\projects\myapp.exe "My App"

  /uf <assembly_name>
    Forces uninstall of an assembly by removing all traced references.
    <assembly_name> is the full name of the assembly to remove.
    Assembly will be removed unless referenced by Windows Installer.
    !! Warning: use the /uf command with care as applications may fail to run !!
    Example: /uf myDll,Version=1.1.0.0,Culture=en,PublicKeyToken=874e23ab874e23ab

  /ul <assembly_display_name_list_file> [ /r <...> ]
    Uninstalls one or more assemblies from the global assembly cache.  
    <assembly_list_file> is the path to a text file that contains a list of 
    assembly names. Individual names in the text file must be 
    separated by CR/LF.
    Example: /ul myAssemblyList.txt/r FILEPATH c:\projects\myapp.exe "My App"
      myAssemblyList.txt content:
      myDll,Version=1.1.0.0,Culture=en,PublicKeyToken=874e23ab874e23ab
      myDll2,Version=1.1.0.0,Culture=en,PublicKeyToken=874e23ab874e23ab

  /l [ <assembly_name> ]
    Lists the contents of the global assembly cache. When the optional 
    <assembly_name> parameter is specified only matching assemblies are listed.

  /lr [ <assembly_name> ]
    Lists the contents of the global assembly cache including traced reference 
    information. When the optional <assembly_name> parameter is specified only 
    matching assemblies are listed.

  /cdl
    Deletes the contents of the download cache

  /ldl
    Lists the contents of the download cache

  /? 
    Displays a detailed help screen

Old command syntax:
  /if <assembly_path>
    equivalent to /i <assembly_path> /f

  /ir <assembly_path> <reference_scheme> <reference_id> <description>
    equivalent to /i <assembly_path> /r <...>

  /ur <assembly_name> <reference_scheme> <reference_id> <description>
    equivalent to /u <assembly_path> /r <...>

Options:
  /r <reference_scheme> <reference_id> <description>
    Specifies a traced reference to install (/i, /il) or uninstall (/u, /ul).
      <reference_scheme> is the type of the reference being added 
        (UNINSTALL_KEY, FILEPATH or OPAQUE). 
      <reference_id> is the identifier of the referencing application, 
        depending on the <reference_scheme>
      <description> is a friendly description of the referencing application.
    Example: /r FILEPATH c:\projects\myapp.exe "My App"

  /f 
    Forces reinstall of an assembly regardless of any existing assembly with 
    the same assembly name.

  /nologo
    Suppresses display of the logo banner

  /silent
    Suppresses display of all output


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\gacutil.exe |
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

* Original Filename: gacutil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/974226c200f8edad7f4f7444df62d9e87d09dc631803a0edb3723dc99c484920/detection





MIT License. Copyright (c) 2020-2021 Strontic.


