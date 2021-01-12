---
title: wsdl.exe | .NET Frameworks WebService install and administration tool
excerpt: What is wsdl.exe?
---

# wsdl.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\wsdl.exe`
* Description: .NET Frameworks WebService install and administration tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `C53785CE6D43450E46EAC1BC84E591B8`
SHA1 | `72377BA6738D4EC400B8A7BA32FDAABAC63B1FAC`
SHA256 | `BE565845988853858F285F3B007F9E1F1D3DA75E0F4C095371FA032D45389F83`
SHA384 | `EC68BEA84E0A41963F42B200BFF63712745E52870D4DC3AE4062119E106F0E55530153F63523661E6F4F1DBFF872FE52`
SHA512 | `F8290843577AF8AA0A33CCFE63B8E745766289593865E123223D03AFA8DFE45276DC36E57EFC777D5A94D3DAC5B025EB0C03866749421B8A8567530428B5012B`
SSDEEP | `1536:Au190NfjB1B+DRBz0B2lU/DWZiSwWN/lPhlMw8MTIBvdu0PfYcVOuj243yzB:eNfjB1B+DRBoB2pxlMo6dnxl2JB`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `B0F3175E5CEA51A8027DEAAF441AB51A4F0E9492`
PE256 | `03C7F01F99C8F327A3746BDBA098A7E96F178B41B08BF28765D427F83ABD9673`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Web Services Description Language Utility
[Microsoft (R) .NET Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation. All rights reserved.

wsdl.exe -
    Utility to generate code for xml web service clients and xml web services
    using ASP.NET from WSDL contract files, XSD schemas and .discomap
    discovery documents. This tool can be used in conjunction with disco.exe.

wsdl.exe <options> <url or path> <url or path> ...

     - OPTIONS -

<url or path> -
    A url or path to a WSDL contract, an XSD schema or .discomap document.

/nologo
    Suppresses the banner.

/language:<language>
    The language to use for the generated proxy class.  Choose from 'CS',
    'VB', 'JS', 'VJS', 'CPP' or provide a fully-qualified name for a class
    implementing System.CodeDom.Compiler.CodeDomProvider.  The default
    language is 'CS' (CSharp).  Short form is '/l:'.

/sharetypes
    Turns on type sharing feature. This feature creates one code file with
    a single type definition for identical types shared between different
    services (namespace, name and wire signature must be identical).
    Reference the services with http:// URLs as command-line parameters
    or create a discomap document for local files.

/verbose
    Displays extra information when the /sharetypes switch is specified.
    Short form is '/v'.

/fields
    Generate fields instead of properties. Short form is '/f'.

/order
    Generate explicit order identifiers on particle members.

/enableDataBinding
    Implement INotifyPropertyChanged interface on all generated types
    to enable data binding. Short form is '/edb'.

/namespace:<namespace>
    The namespace for the generated proxy or template.  The default namespace
    is the global namespace. Short form is '/n:'.

/out:<fileName|directoryPath>
    The filename or directory path for the generated proxy code. The default
    filename is derived from the service name. Short form is '/o:'.

/protocol:<protocol>
    Override the default protocol to implement.  Choose from 'SOAP',
    'SOAP12', 'HttpGet', 'HttpPost'.

/username:<username>
/password:<password>
/domain:<domain>
    The credentials to use when connecting to a server that
    requires authentication. Short forms are '/u:', '/p:' and '/d:'.

/proxy:<url>
    The url of the proxy server to use for http requests.
    The default is to use the system proxy setting.

/proxyusername:<username>
/proxypassword:<password>
/proxydomain:<domain>
    The credentials to use when the connecting to a proxy server that
    requires authentication. Short forms are '/pu:', '/pp:' and '/pd:'.

/appsettingurlkey:<key>
    The configuration key to use in the code generation to read the default
    value for the Url property. The default is to not read from the config
    file. Short form is '/urlkey:'.

/appsettingbaseurl:<baseurl>
    The base url to use when calculating the url fragment. The
    appsettingurlkey option must also be specified. The url fragment is
    the result of calculating the relative url from the appsettingbaseurl
    to the url in the WSDL document. Short form is '/baseurl:'.

/parsableerrors
    Print errors in a format similar to those reported by compilers.

     - ADVANCED -

/server
    Server switch has been deprecated. Please use /serverInterface instead.
    Generate an abstract class for an xml web service implementation using
    ASP.NET based on the contracts. The default is to generate client proxy
    classes.

/serverInterface
    Generates interfaces for server-side implementation of an ASP.Net 
    Web Service. An interface is generated for each binding in the wsdl 
    document(s). The wsdl alone implements the wsdl contract (classes 
    that implement the interface should not include either of the following
    on the class methods: Web Service attributes or Serialization 
    attributes that change the wsdl contract). Short form is '/si'.

/parameters:<file>
    Read command-line options from the specified xml file. This allows you
    to specify options not available from command line such as choosing
    which type of asynchronous programming model is generated. For details,
    please see the tool documentation. Short form is '/par:'.

```

### Usage (stderr):
```cmhg
Error: File 'help' missing a file extension.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\wsdl.exe |
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

* Original Filename: wsdl.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/be565845988853858f285f3b007f9e1f1d3da75e0f4c095371fa032d45389f83/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\wsdl.exe](wsdl.exe-C4E29F9BC7CBDE52C072F9C0D3B81799.md) | 88




MIT License. Copyright (c) 2020 Strontic.


