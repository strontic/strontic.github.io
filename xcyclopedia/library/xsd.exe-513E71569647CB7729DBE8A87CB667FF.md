---
title: xsd.exe | .NET Frameworks Xml Schema Tool
excerpt: What is xsd.exe?
---

# xsd.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\xsd.exe`
* Description: .NET Frameworks Xml Schema Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `513E71569647CB7729DBE8A87CB667FF`
SHA1 | `5E8ABAAB5195EE7072370000BBEFB2148E3F1873`
SHA256 | `A0B8CC794ECD4AA173B651DE77F7D559CD66F66598AC33C42A65561F1E6ECA5A`
SHA384 | `06B3D7D00BA05F86EB37FB66D14E85631F8B145855E1B019A006A360CF4841D0BF4B7E9C6A10160F51FB7AA966F4D7EC`
SHA512 | `94402708CB928B1E07C2AEEFDE81C43940752BD735A33E58823B0F8A0CF62EE62C9ABB887223C17085058CE8D5808F3A26107C4A2C15D048826BFEC1CEEDB4F0`
SSDEEP | `1536:VQipoylcELO4r4MyPYvTFdryM2YCrNHBV9O8sTS:YI4tQvZd7AB9iTS`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `D7A2304FF08C0AF1FBD0D8EC17E5E347CADAD860`
PE256 | `85B4F6AF15C852E8E62A35017E43FA83BB33D29339E8C1D8F21DA788196E8D4A`

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

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\xsd.exe |
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

* Original Filename: xsd.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a0b8cc794ecd4aa173b651de77f7d559cd66f66598ac33c42a65561f1e6eca5a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\xsd.exe](xsd.exe-0265FFFC84FCD1C9585A1F1E2F78BFCC.md) | 77




MIT License. Copyright (c) 2020-2021 Strontic.


