---
title: gacutil.exe | Microsoft (R) .NET Framework Global Assembly Cache Utility
excerpt: What is gacutil.exe?
---

# gacutil.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\gacutil.exe`
* Description: Microsoft (R) .NET Framework Global Assembly Cache Utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `B832833BB3D6DE53EE50DA48667A5AC2`
SHA1 | `ECA3E57F47B220392FD883EE112C95F51793609C`
SHA256 | `C4884B1CD4BF6726056382DA620BDD7C16BFEC4D2E6FB8AA450E9AAAFDFC7DA0`
SHA384 | `60E1FD1F9923C3D259CD3C28B0859A0E7F651FC96638887C94C0C7CDA48BCBF523DE1F98609175B2BB3E6D3C354FB0C5`
SHA512 | `994A53478DF9FB5BC1C5F0E929D5584AD0523FDE74A4ADF3873EDD613FD82F4CB525E32DE30F0FA316D6295A2AFFAC25163DDA2AF3927B7877DBF9B201577E5C`
SSDEEP | `3072:KQKlsv+7uScu58rRTFtE/ZLO63uIIzc1VofMJvaj9YfTOJpYb:K3I+Wu58rlCH1IzcTpNTO/C`
IMP | `AD8FD1BD9FF6D25B8E1A4F2AB0155FF4`
PESHA1 | `DB1E6919D19CE64406592D18C7061FD73DEA6AF6`
PE256 | `4A586317F2895A08EC34F124D5DD953E121118C0E1FEE353DCDDFD8C2AC30E44`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\gacutil.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c4884b1cd4bf6726056382da620bdd7c16bfec4d2e6fb8aa450e9aaafdfc7da0/detection





MIT License. Copyright (c) 2020 Strontic.


