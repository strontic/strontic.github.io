---
title: TlbImp.exe | Microsoft .NET Assembly to Type Library Converter
excerpt: What is TlbImp.exe?
---

# TlbImp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\TlbImp.exe`
* Description: Microsoft .NET Assembly to Type Library Converter
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `8520418C8256FC21ECAE460653B00454`
SHA1 | `B85B4E5D3D2DBBAAB28FC83BECA9CCA4ACB77A81`
SHA256 | `75E2A025F5B20BA324AB0DBCF877F3FB3A9467D4736CB2BFBA9B79EFC68AFB04`
SHA384 | `D995C1287870C612250AE4B14218FCCFC7A9A9CF4D0C592D69813735A4BA74C04BC25CA8635B5A92D4A1643C3671E80B`
SHA512 | `9004C8490F20A54421F9BC477BE6C8272981E7E46B8281DABA9D59A60932A7CD14AEA2B399B72A8921B6E7B50AFC88EE9E1A0F3E8DD48B8CE8776A36115296C0`
SSDEEP | `3072:KGz3mZJiOWFd83yPdQ2l5E5nuQs3upGCFFHqdFdJ4U8hWFUy1zVwKwDr61pV+5:KGz3fOW/dr5knEaJ/QVwt6J6`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `016FE853D519F4D910C06D46D9B95159E0FAA320`
PE256 | `A18BD5FEEBDD35217907207A073F1EC3F97C5A1C2BD5F88A7D29F31DC4AE768A`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\TlbImp.exe |
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

* Original Filename: TlbImp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/75e2a025f5b20ba324ab0dbcf877f3fb3a9467d4736cb2bfba9b79efc68afb04/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\TlbImp.exe](TlbImp.exe-51E5E1DD5D979152AB92DFF0B0EA292B.md) | 80




MIT License. Copyright (c) 2020-2021 Strontic.


