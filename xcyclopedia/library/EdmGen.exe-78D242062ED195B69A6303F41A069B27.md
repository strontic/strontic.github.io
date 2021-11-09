---
title: EdmGen.exe | EdmGen.exe
excerpt: What is EdmGen.exe?
---

# EdmGen.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\EdmGen.exe`
* Description: EdmGen.exe
* Comments: EdmGen.exe


## Hashes

Type | Hash
-- | --
MD5 | `78D242062ED195B69A6303F41A069B27`
SHA1 | `319E67C0594A73BBAB33B2A89E4975D6028945E4`
SHA256 | `B78824371D82E671841C7BC68C18E98191793388CAAAE4E3C8C0638C1999668F`
SHA384 | `9E7665CEE47EDAC2772E0DAEED9B9D0EEBAD8D36369E02767D823A8E678EFDAB6BEFD677C9612F1A88C6E14904DE8E31`
SHA512 | `10516685172103C083BD51E0D5D04C56975C2F99E5B247F21C2F32411DBC0DD11D53472C515F36A8000F00CC9F44E16D45A2BE93C822B44FA2042170C935C481`
SSDEEP | `1536:A6CB2ksmOkl9xjw9YhtdumUEfeANG2kbg:A6cXt5P53dumWANG9`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `2597EB0D2CF32E2D138832464F522A458F13714F`
PE256 | `9D6644B015635B382BB9A24601311C1EA182A8C3A38F246FD4541B9525E07F0F`

## Runtime Data

### Usage (stdout):
```cmhg
EdmGen for Microsoft (R) .NET Framework version 4.8.4161.0
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
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\EdmGen.exe |
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

* Original Filename: EdmGen.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0
* Product Version: 4.8.4161.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b78824371d82e671841c7bc68c18e98191793388caaae4e3c8c0638c1999668f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\EdmGen.exe](EdmGen.exe-38BA403812239FD9691F876F2DE3DBB4.md) | 75
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\EdmGen.exe](EdmGen.exe-38BA403812239FD9691F876F2DE3DBB4.md) | 75
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\EdmGen.exe](EdmGen.exe-78D242062ED195B69A6303F41A069B27.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


