---
title: xsd.exe | .NET Frameworks Xml Schema Tool
excerpt: What is xsd.exe?
---

# xsd.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\xsd.exe`
* Description: .NET Frameworks Xml Schema Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `0265FFFC84FCD1C9585A1F1E2F78BFCC`
SHA1 | `D10F74394E40F87256B1BCB28FCE05A36A9C44B6`
SHA256 | `212B8FBFF65F4B911FF30A07F5600698825822FF935B5C3BCA474B16D7FDF1C7`
SHA384 | `4C70CCCD8102C4008263A2FF67F8C8ABD69F88A21B33423551C9471D3B182E5D282B81F90B466D178141A78788C773EA`
SHA512 | `328B0E4FE768CEA06A06110A4B051F8A6713AD972DE69240374432C496A850EDF84FC5A7D712AE5CD6A1414F2108BD5B499D2912ACA4CC802DF00D374E644FB9`
SSDEEP | `1536:RQipoylcELO4r4MyoYvTFdryG2YCrNHuhb5YGB:UI4tHvZdFAchb`
IMP | `n/a`
PESHA1 | `440466790E31EDCDDE61A78E296A5A8ACE9DA3E7`
PE256 | `E38FC1E512FA9A0BF461863688B5C0FAF239305A7D510E57604A75616819DF7A`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Xml Schemas/DataTypes support utility
[Microsoft (R) .NET Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation. All rights reserved.

xsd.exe -
    Utility to generate schema or class files from given source.

xsd.exe <schema>.xsd /classes|dataset [/e:] [/l:] [/n:] [/o:] [/s] [/uri:]
xsd.exe <assembly>.dll|.exe [/outputdir:] [/type: [...]]
xsd.exe <instance>.xml [/outputdir:]
xsd.exe <schema>.xdr [/outputdir:]

     - OPTIONS -

/classes
    Generate classes for this schema. Short form is '/c'.

/dataset
    Generate sub-classed DataSet for this schema. Short form is '/d'.

/enableLinqDataSet
    Generate LINQ-enabled sub-classed Dataset for the schemas provided.  Short form is '/eld'.

/element:<element>
    Element from schema to process. Short form is '/e:'.

/fields
    Generate fields instead of properties. Short form is '/f'.

/order
    Generate explicit order identifiers on all particle members.

/enableDataBinding
    Implement INotifyPropertyChanged interface on all generated types
    to enable data binding. Short form is '/edb'.

/language:<language>
    The language to use for the generated code. Choose from 'CS', 'VB', 'JS',
    'VJS', 'CPP' or provide a fully-qualified name for a class implementing
    System.CodeDom.Compiler.CodeDomProvider. The default language
    is 'CS' (CSharp). Short form is '/l:'.

/namespace:<namespace>
    The namespace for generated class files. The default namespace
    is the global namespace. Short form is '/n:'.

/nologo
    Suppresses the banner.

/out:<directoryName>
    The output directory to create files in. The default
    is the current directory. Short form is '/o:'.

/type:<type>
    Type from assembly to generate schema for. Multiple types may be provided.
    If no types are provided, then schemas for all types in an assembly
    are generated. Short form is '/t:'.

/uri:<uri>
    Uri of elements from schema to process. Short form is '/u:'.

     - ADVANCED -

/parameters:<file>
    Read command-line options from the specified xml file. Short form is '/p:'.

     - ARGUMENTS -
<schema>.xsd       Name of a schema containing elements to import.
<assembly>.dll|exe Name of an assembly containing types to generate schema for.
<instance>.xml     Name of an xml file to infer xsd schema from.
<schema>.xdr       Name of an xdr schema to convert to xsd.
Multiple file arguments of the same type may be provided.

```

### Usage (stderr):
```cmhg
Error: invalid command line argument: '--help'.

```

### Child Processes:
Fondue.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\xsd.exe |
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

* Original Filename: xsd.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/212b8fbff65f4b911ff30a07f5600698825822ff935b5c3bca474b16d7fdf1c7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\xsd.exe](xsd.exe-513E71569647CB7729DBE8A87CB667FF.md) | 77




MIT License. Copyright (c) 2020 Strontic.


