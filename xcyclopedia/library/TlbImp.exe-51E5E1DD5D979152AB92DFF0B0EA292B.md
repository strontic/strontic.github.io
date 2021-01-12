---
title: TlbImp.exe | Microsoft .NET Assembly to Type Library Converter
excerpt: What is TlbImp.exe?
---

# TlbImp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\TlbImp.exe`
* Description: Microsoft .NET Assembly to Type Library Converter
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `51E5E1DD5D979152AB92DFF0B0EA292B`
SHA1 | `0B289B921EA567921138B069E76B5AC9AAF4B819`
SHA256 | `B03269A241B248F8703D0EEF439B5318A3F53B2D26BDB2DDB9B771ABC5074407`
SHA384 | `0549108EBDC23277BF977B3289ED6B6E7B526323321F2C4A079259FF9C821CE27718381D6A2EE74CDB3414C37CCF3917`
SHA512 | `95FB5942BC9AFF6BFAB5514080F47F24C845B4C36E2E7358B8D665D55D9A21E53B890646CAEAE8007FD34D0099E3CBF1859B4734B3947AB449756C2E53DCC6A4`
SSDEEP | `3072:/0z3mZJiOWFd83yPdQ2l5EmsFFIZupGCFFHqdFdJ4U8hWFUy1vVwKwDr61jREyIA:/0z3fOW/dr5/sFlJ/4Vwt6v1IA`
IMP | `n/a`
PESHA1 | `ACEF56EA4827AEA3C97911D9B54D325CC952427D`
PE256 | `D743E0B9418E0A1B0E882D065561D1F3C3B4157FE6EFDA84A74A1D1478A1BF7E`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Type Library to Assembly Converter 4.8.4084.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Syntax: TlbImp TypeLibName [Options]
Options:
    /out:FileName            File name of assembly to be produced
    /namespace:Namespace     Namespace of the assembly to be produced
    /asmversion:Version      Version number of the assembly to be produced
    /reference:FileName      File name of assembly to use to resolve references
    /tlbreference:FileName   File name of typelib to use to resolve references
    /publickey:FileName      File containing strong name public key
    /keyfile:FileName        File containing strong name key pair
    /keycontainer:FileName   Key container holding strong name key pair
    /delaysign               Force strong name delay signing
    /product:Product         The name of the product with which this assembly
                             is distributed
    /productversion:Version  The version of the product with which this
                             assembly is distributed
    /company:Company         The name of the company that produced this
                             assembly
    /copyright:Copyright     Describes all copyright notices, trademarks, and
                             registered trademarks that apply to this assembly
    /trademark:Trademark     Describes all trademarks and registered trademarks
                             that apply to this assembly
    /unsafe                  Produce interfaces without runtime security checks
    /noclassmembers          Prevents TlbImp from adding members to classes
    /nologo                  Prevents TlbImp from displaying logo
    /silent                  Suppresses all output except for errors
    /silence:WarningNumber   Suppresses output for the given warning (Can not 
                             be used with /silent)
    /verbose                 Displays extra information
    /primary                 Produce a primary interop assembly
    /sysarray                Import SAFEARRAY as System.Array
    /machine:MachineType     Create an assembly for the specified machine type
    /transform:TransformName Perform the specified transformation
    /strictref               Only use assemblies specified using /reference and
                             registered PIAs
    /strictref:nopia         Only use assemblies specified using /reference and
                             ignore PIAs
    /VariantBoolFieldToBool  Convert VARIANT_BOOL field in structures to bool.
    /Legacy35                Use legacy TlbImp 3.5 behavior.
    /? or /help              Display this usage message

The assembly version must be specified as: Major.Minor.Build.Revision.

Multiple reference assemblies can be specified by using the /reference option
multiple times.

Supported machine types:
    X86
    X64
    Itanium
    ARM
    Agnostic

Supported transforms:
    SerializableValueClasses Mark all value classes as serializable
    DispRet                  Apply the [out, retval] parameter transformation
                             to methods of disp only interfaces

A resource ID can optionally be appended to the TypeLibName when importing a
type library from a module containing multiple type libraries.
 example: TlbImp MyModule.dll\1

```

### Usage (stderr):
```cmhg
TlbImp : error TI1002 : The input file 'C:\Users\user\help' is not a valid type library.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\TlbImp.exe |
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

* Original Filename: TlbImp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/b03269a241b248f8703d0eef439b5318a3f53b2d26bdb2ddb9b771abc5074407/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\TlbImp.exe](TlbImp.exe-8520418C8256FC21ECAE460653B00454.md) | 80




MIT License. Copyright (c) 2020 Strontic.


