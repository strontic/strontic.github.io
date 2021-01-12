---
title: SvcUtil.exe | svcutil.exe
excerpt: What is SvcUtil.exe?
---

# SvcUtil.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\SvcUtil.exe`
* Description: svcutil.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `A4453C2ED9B130AAC6860E8410799F1F`
SHA1 | `50208B407ECB23A4EC2D7418A471E59BB06AD114`
SHA256 | `6793C7139163A02A67EB0380A462025DC10748837AAA25AB5DE16ADADFA13927`
SHA384 | `AD32E4C66A97C5609C352AF22BB875923C1B99064BA41386AAF9C1A7AFB92A261D70EFF6603217A325CF823C207C9115`
SHA512 | `1E0EF91CF9C4A7C7F20856A68DC3E4D5DF7A9635861C04B47E46CEA9FC25FDC0901DD6EC5B07B8CFD81F5A34DA67F9B3094DDAAB19CB8CCF9AACF64B06492AF1`
SSDEEP | `3072:CysdQTmv0xhnwz/cHYePxMdU0xgN8gJh2y64vlli7/qUH+Pz/tYWvyH:UCTJLwz/c4ePxhnLy`
IMP | `n/a`
PESHA1 | `A2B96FAF4DBEB62E21120ADF7740731CB8E8ABB5`
PE256 | `E879F68885015AC0B96134894B3932C19AE4292AA45E74E0D5972DB8E402BD6B`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Service Model Metadata Tool
[Microsoft (R) Windows (R) Communication Foundation, Version 4.8.4084.0]
Copyright (c) Microsoft Corporation.  All rights reserved.

USES:

 - Generate code from running services or static metadata documents. 
 - Export metadata documents from compiled code.
 - Validate compiled service code.
 - Download metadata documents from running services.
 - Pre-generate serialization code.


               -= COMMON OPTIONS =-

Options:

 /target:<output type>       - The target output for the tool: code, metadata or xmlSerializer.
 /directory:<directory>      - Directory to create files in (default: current directory) (Short Form: /d)

 /svcutilConfig:<configFile> - Custom configuration file to use in place of the app config file. This can be used to register system.serviceModel extensions without altering the tool's config file.
 /noLogo                     - Suppress the copyright and banner message.
 /help                       - Display command syntax and options for the tool. (Short Form: /?)



               -= CODE GENERATION =-

Description: svcutil.exe can generate code for service contracts, clients and data types from metadata documents. These metadata documents can be on disk or retrieved online. Online retrieval follows either the WS-Metadata Exchange protocol or the DISCO protocol.

Syntax: svcutil.exe [/t:code]  <metadataDocumentPath>* | <url>* | <epr>

 <metadataDocumentPath> - The path to a metadata document (wsdl or xsd). Standard command-line wildcards can be used in the file path.
 <url>                  - The URL to a service endpoint that provides metadata or to a metadata document hosted online. For more information on how these documents are retrieved see the Metadata Download section.
 <epr>                  - The path to an XML file that contains a WS-Addressing EndpointReference for a service endpoint that supports WS-Metadata Exchange. For more information see the Metadata Download section.

Options:

 /out:<file>                        - The filename for the generated code. Default: derived from the WSDL definition name, WSDL service name or targetNamespace of one of the schemas. (Short Form: /o)
 /config:<configFile>               - The filename for the generated config file. Default: output.config
 /mergeConfig                       - Merge the generated config into an existing file instead of overwriting the existing file.	
 /noConfig                          - Do not generate config
 /dataContractOnly                  - Generate code for Data Contract types only. Service Contract types will not be generated. (Short Form: /dconly)

 /language:<language>               - The programming language to use for generating code. Provide either a language name registered in the machine.config file or provide the fully-qualified name of a class that inherits from System.CodeDom.Compiler.CodeDomProvider. Examples of language names to use are CS and VB. Default: C#. (Short Form: /l)
 /namespace:<string,string>         - A mapping from a WSDL or XML Schema targetNamespace to a CLR namespace. Using the '*' for the targetNamespace maps all targetNamespaces without an explicit mapping to that CLR namespace. Default: derived from the target namespace of the schema document for Data Contracts. The default namespace is used for all other generated types. (Short Form: /n)

 /messageContract                   - Generate Message Contract types. (Short Form: /mc)
 /enableDataBinding                 - Implement the System.ComponentModel.INotifyPropertyChanged interface on all Data Contract types to enable data binding. (Short Form: /edb)
 /serializable                      - Generate classes marked with the Serializable Attribute. (Short Form: /s)
 /async                             - Generate both synchronous and begin/end asynchronous method signatures. Default: generate synchronous and task-based asynchronous method signatures. (Short Form: /a)
 /internal                          - Generate classes that are marked as internal. Default: generate public classes. (Short Form: /i)

 /reference:<file path>             - Reference types in the specified assembly. When generating clients, use this option to specify assemblies that might contain types representing the metadata being imported.  (Short Form: /r)
 /collectionType:<type>             - A fully-qualified or assembly-qualified name of the type to use as a collection data type when code is generated from schemas. (Short Form: /ct)
 /excludeType:<type>                - A fully-qualified or assembly-qualified type name to exclude from referenced contract types. (Short Form: /et)
 /noStdLib                          - Do not reference standard libraries. By default mscorlib.dll and system.servicemodel.dll are referenced.

 /serializer:Auto                   - Automatically select the serializer. This tries to use the Data Contract serializer and uses the XmlSerializer if that fails. (Short Form: /ser)
 /serializer:DataContractSerializer - Generate data types that use the Data Contract Serializer for serialization and deserialization
 /serializer:XmlSerializer          - Generate data types that use the XmlSerializer for serialization and deserialization
 /importXmlTypes                    - Configure the Data Contract serializer to import non-Data Contract types as IXmlSerializable types.
 /useSerializerForFaults            - This option specifies whether the serializer specified in the 'serializer' switch is used for fault contract types. DataContractSerializer is used for faults if this switch is not specified. (Short Form: /fault)

 /targetClientVersion:Version30     - Generate code that references functionality in .NET Framework assemblies 3.0 and before. Use this switch if you are generating code for clients that use .NET Framework version 3.0.(Short Form: /tcv)
 /targetClientVersion:Version35     - Generate code that references functionality in .NET Framework assemblies 3.5 and before. Use this switch if you are generating code for clients that use .NET Framework version 3.5.(Short Form: /tcv)
 /wrapped                           - Generated code will not unwrap "parameters" member of document-wrapped-literal messages.
 /serviceContract                   - Generate code for Service Contracts. Client class and configuration will not be generated. (Short Form: /sc)
 /syncOnly                          - Generate only synchronous method signature. Default: generate synchronous and task-based asynchronous method signatures.



               -= METADATA EXPORT =-

Description: svcutil.exe can export metadata for services, contracts and data types in compiled assemblies. To export metadata for a service, you must use the /serviceName option to indicate the service you would like to export. To export all Data Contract types within an assembly use the /dataContractOnly option. By default metadata is exported for all Service Contracts in the input assemblies.

Syntax: svcutil.exe [/t:metadata] [/serviceName:<serviceConfigName>] [/dataContractOnly] <assemblyPath>*

 <assemblyPath> - The path to an assembly that contains services, contracts or Data Contract types to be exported. Standard command-line wildcards can be used to provide multiple files as input.

Options:

 /serviceName:<serviceConfigName> - The config name of a service to export. If this option is used, an executable assembly with an associated config file must be passed as input. Svcutil will search through all associated config files for the service configuration. If the config files contain any extension types, the assemblies containing these types must either be in the GAC or explicitly provided using the /r option.
 /reference:<file path>           - Add the specified assembly to the set of assemblies used for resolving type references. If you are exporting or validating a service that uses 3rd-party extensions (Behaviors, Bindings and BindingElements) registered in config use this option to locate extension assemblies that are not in the GAC.  (Short Form: /r)
 /dataContractOnly                - Operate on Data Contract types only. Service Contracts will not be processed. (Short Form: /dconly)
 /excludeType:<type>              - The fully-qualified or assembly-qualified name of a type to exclude from export. This option can be used when exporting metadata for a service or a set of service contracts to exclude types from being exported. This option cannot be used with the /dconly option. (Short Form: /et)



             -= SERVICE VALIDATION =-

Description: Validation is useful to detect errors in service implementations without hosting the service. You must use the /serviceName option to indicate the service you would like to validate.

Syntax: svcutil.exe /validate /serviceName:<serviceConfigName>  <assemblyPath>*

 <assemblyPath> - The path to an assembly containing service types to be validated. The assembly must have an associated config file to provide service configuration. Standard command-line wildcards can be used to provide multiple assemblies.

Options:

 /validate                        - Validate a service implementation. To validate a service, you must use the /serviceName option to indicate the service you would like to validate. If this option is used, an executable assembly with an associated config file must be passed as input. (Short Form: /v)
 /serviceName:<serviceConfigName> - The config name of a service to validate. To validate a service this option must be provided. Svcutil will search through the associated config files of all input assemblies for the service configuration. If the associated configuration file contain any extension types, the assemblies containing these types must either be in the GAC or explicitly provided using the /r option.
 /reference:<file path>           - Add the specified assembly to the set of assemblies used for resolving type references. If you are exporting or validating a service that uses 3rd-party extensions (Behaviors, Bindings and BindingElements) registered in config use this option to locate extension assemblies that are not in the GAC.  (Short Form: /r)
 /dataContractOnly                - Operate on Data Contract types only. Service Contracts will not be processed. (Short Form: /dconly)
 /excludeType:<type>              - The fully-qualified or assembly-qualified name of a service type to exclude from validation. (Short Form: /et)



              -= METADATA DOWNLOAD =-

Description: svcutil.exe can be used to download metadata from running services and save the metadata to local files. To download metadata, you must explicitly specify the /t:metadata option. Otherwise, client code will be generated. For http and https URL schemes svcutil.exe will try to retrieve metadata using WS-Metadata Exchange and DISCO. For all other URL schemes svcutil.exe will only try WS-Metadata Exchange. By default, svcutil.exe uses the bindings defined in the System.ServiceModel.Description.MetadataExchangeBindings class. To configure the binding used for WS-Metadata Exchange you must define a client endpoint in config that uses the IMetadataExchange contract. This can be defined either in svcutil.exe's config file or in another config file specified using the /svcutilConfig option.

Syntax: svcutil.exe /t:metadata  <url>* | <epr>

 <url> - The URL to a service endpoint that provides metadata or an URL that points to a metadata document hosted online. 
 <epr> - The path to an XML file that contains a WS-Addressing EndpointReference for a service endpoint that supports WS-Metadata Exchange.



        -= XMLSERIALIZER TYPE GENERATION =-

Description: svcutil.exe can pre-generate C# serialization code that is required for types that can be serialized using the XmlSerializer. svcutil.exe will only generate code for types used by Service Contracts found in the input assemblies.

Syntax: svcutil.exe /t:xmlSerializer  <assemblyPath>*

 <assemblyPath> - The path to an assembly containing Service Contract types. Serialization types will be generated for all Xml Serializable types in each contract

Options:

 /reference:<file path> - Add the specified assembly to the set of assemblies used for resolving type references. (Short Form: /r)
 /excludeType:<type>    - Fully-qualified or assembly-qualified type name to exclude from export or validation. This option can be used when exporting metadata for a service or a set of service contracts to exclude types from being exported. This option cannot be used with the /dataContractOnly option. (Short Form: /et)
 /out:<file>            - Filename for the generated code. This option will be ignored when multiple assemblies are passed as input to the tool. Default: derived from the assembly name. (Short Form: /o)



                  -= EXAMPLES =-

 svcutil http://service/metadataEndpoint
    - Generate client code from a running service or online metadata documents.

 svcutil *.wsdl *.xsd /language:C#
    - Generate client code from local metadata documents.

 svcutil /dconly *.xsd /language:VB
    - Generate Data Contract types in VisualBasic from local schema documents.

 svcutil /t:metadata http://service/metadataEndpoint
    - Download metadata documents from running services

 svcutil myAssembly.dll
    - Generate metadata documents for Service Contracts and associated types in an assembly

 svcutil myServiceHost.exe /serviceName:myServiceName 
    - Generate metadata documents for a service, and all associated Service Contracts and data types in an assembly

 svcutil myServiceHost.exe /dconly 
    - Generate metadata documents for data types in an assembly

 svcutil /validate /serviceName:myServiceName myServiceHost.exe
    - Verify service hosting

 svcutil /t:xmlserializer myContractLibrary.exe
    - Generate serialization types for XmlSerializer types used by any Service Contracts in the assembly




```

### Usage (stderr):
```cmhg
Error: Cannot read help.

    Cannot load file C:\Users\user\help as an Assembly. Check the FusionLogs for more Information.

    Could not load file or assembly 'file:///C:\Users\user\help' or one of its dependencies. The module was expected to contain an assembly manifest.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\SvcUtil.exe |
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

* Original Filename: svcutil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6793c7139163a02a67eb0380a462025dc10748837aaa25ab5de16adadfa13927/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\SvcUtil.exe](SvcUtil.exe-0F32F1595A0169D195D9B2D85F6F9E7B.md) | 86




MIT License. Copyright (c) 2020 Strontic.


