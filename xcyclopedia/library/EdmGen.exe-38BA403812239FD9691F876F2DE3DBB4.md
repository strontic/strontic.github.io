---
title: EdmGen.exe | EdmGen.exe
excerpt: What is EdmGen.exe?
---

# EdmGen.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\EdmGen.exe`
* Description: EdmGen.exe
* Comments: EdmGen.exe


## Hashes

Type | Hash
-- | --
MD5 | `38BA403812239FD9691F876F2DE3DBB4`
SHA1 | `14F8BE6630A069EEEF0D6AE6DF725BCFB7508099`
SHA256 | `83F32D1ED03C408E3387447AC9C527FE36D3AEFC46CEE37177800A7C3470D407`
SHA384 | `EFC3C9DCFF243F42529E34516C816932705EB894A7714AE16F0C261BEA00F8FB44651E07CBC4433DFB1D23034C97CC9A`
SHA512 | `55B97F49CBC04101FE7BFDA89504384AC0F1CF2A5AD29375BF9DE844365727E5333A1102B50F6F3BAB69DF11C71F908245C98F522D40B8A2B4468F83815D5DD7`
SSDEEP | `768:FWeBB6CB2k0pmBQklZXxRt/wMXfAYhnVTdJ/N6Iq8ZGMavlfILAQgARXqW080lF:l6CB2ksmOkl9xjw9YhtdNkUSfeAdArNM`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `78979905C81D310AA0784E9234BC4FD44822366D`
PE256 | `21FFCC6B438208CD1A108057E15CAFE05247F1A4AC032D8C41E45F607D0DD563`

## Runtime Data

### Usage (stdout):
```cmhg
EdmGen for Microsoft (R) .NET Framework version 4.8.4084.0
Copyright (C) Microsoft Corporation. All rights reserved.

                                 EdmGen Options
/mode:EntityClassGeneration             Generate objects from a csdl file
/mode:FromSsdlGeneration                Generate msl, csdl, and objects from an
                                        ssdl file
/mode:ValidateArtifacts                 Validate the ssdl, msl, and csdl files
/mode:ViewGeneration                    Generate mapping views from ssdl, msl,
                                        and csdl files 
/mode:FullGeneration                    Generate ssdl, msl, csdl, and objects
                                        from the database
/project:<string>                       The base name to be used for all the
                                        artifact files (short form: /p)
/provider:<string>                      The name of the ADO.NET data provider to                                        be used for ssdl generation (short form:                                        /prov)
/connectionstring:<connection string>   The connection string to the database
                                        that you would like to connect to (short                                        form: /c)
/incsdl:<file>                          The file to read the conceptual model
                                        from
/refcsdl:<file>                         A csdl file that contains types that the                                        /incsdl file is dependent upon
/inmsl:<file>                           The file to read the mapping from
/inssdl:<file>                          The file to read the storage model from
/outcsdl:<file>                         The file to write the generated
                                        conceptual model to
/outmsl:<file>                          The file to write the generated mapping
                                        to
/outssdl:<file>                         The file to write the generated storage
                                        model to
/outobjectlayer:<file>                  The file to write the generated object
                                        layer to
/outviews:<file>                        The file to write the pre generated view                                        objects to
/targetversion:<string>                 The .NET Framework version that will be
                                        used to compile the generated code. The
                                        supported versions are 4 and 4.5.
                                        Defaults to 4.
/language:CSharp                        Generate code using the C# language
/language:VB                            Generate code using the Visual Basic
                                        language
/namespace:<string>                     The namespace name to use for the
                                        conceptual model types
/entitycontainer:<string>               The name to use for the EntityContainer
                                        in the conceptual model
/pluralize                              Automatically pluralize or singularize
                                        entity set name, entity type name, and
                                        navigation property name using English
                                        language rules (short form: /pl)
/SuppressForeignKeyProperties           Exclude foreign key properties in entity                                        type definitions. (short form: /nofk)
/help                                   Display the usage message (short form:
                                        /?)
/nologo                                 Suppress copyright message

                                    Examples
To generate a full Entity Model from the Northwind sample database.
  EdmGen /mode:FullGeneration /project:Northwind /provider:System.Data.SqlClient    /connectionstring:"server=.\sqlexpress;integrated security=true;
    database=northwind" /targetversion:4.5

To generate an Entity Model starting from an ssdl file.
  EdmGen /mode:FromSSDLGeneration /inssdl:Northwind.ssdl /project:Northwind

To validate an Entity Model.
  EdmGen /mode:ValidateArtifacts /inssdl:Northwind.ssdl /inmsl:Northwind.msl
    /incsdl:Northwind.csdl


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\EdmGen.exe |
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

* Original Filename: EdmGen.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/83f32d1ed03c408e3387447ac9c527fe36d3aefc46cee37177800a7c3470d407/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\EdmGen.exe](EdmGen.exe-38BA403812239FD9691F876F2DE3DBB4.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


