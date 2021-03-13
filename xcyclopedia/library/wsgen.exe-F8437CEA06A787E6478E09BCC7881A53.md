---
title: wsgen.exe | OpenJDK Platform binary
excerpt: What is wsgen.exe?
---

# wsgen.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsgen.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `F8437CEA06A787E6478E09BCC7881A53`
SHA1 | `78CE3860D64C90CE05FE9740566950D1679EBEC4`
SHA256 | `A7DF6BB97A29B5F6A0C56F64C4181C29211247C1A103562CAA2AA2F108B14ED1`
SHA384 | `82679F3DECE9F4D206EE1561F16FEC56CE69E81A81973BCF517D309BDC8559D76D67A1D00CEF9622440B4E1DDFCC8819`
SHA512 | `CDEA11AC3FE50003AD62AF3AB5B18B4E584DC2D7B51707D5261C6385B4755564677671B81F23FF7C5756767C4BE4A8C584B791EC6D4C59C1BE28C6E6E257BD33`
SSDEEP | `384:GpsQ5hnuqkmSHhV8mCee74SzwK6jSOxpPDgf2hT+A:Gps6n5S/8mve7iKgbUf2hyA`

## Runtime Data

### Usage (stdout):
```cmhg
unrecognized parameter --help


Usage: WSGEN [options] <SEI>

where [options] include:
  -classpath <path>          specify where to find input class files and wsgen extensions
  -cp <path>                 specify where to find input class files and wsgen extensions
  -d <directory>             specify where to place generated output files
  -encoding <encoding>       specify character encoding used by source files
  -extension                 allow vendor extensions - functionality not specified
                             by the specification.  Use of extensions may
                             result in applications that are not portable or
                             may not interoperate with other implementations
  -help                      display help
  -J<javacOption>            pass this option to javac
  -keep                      keep generated files
  -r <directory>             resource destination directory, specify where to
                             place resouce files such as WSDLs
  -s <directory>             specify where to place generated source files
  -verbose                   output messages about what the compiler is doing
  -version                   print version information
  -fullversion               print full version information
  -wsdl[:protocol]           generate a WSDL file. The protocol is optional.
                             Valid protocols are [soap1.1, Xsoap1.2],
                             the default is soap1.1.
                             The non standard protocols [Xsoap1.2]
                             can only be used in conjunction with the
                             -extension option.
  -inlineSchemas             inline schemas in the generated wsdl. Must be
                             used in conjunction with the -wsdl option.
  -servicename <name>        specify the Service name to use in the generated WSDL
                             Used in conjunction with the -wsdl option.
  -portname <name>           specify the Port name to use in the generated WSDL
                             Used in conjunction with the -wsdl option.
  -x <file>                  specify External Web Service Metadata xml descriptor

Extensions:
  -Xnocompile                do not compile generated Java files

Examples:
  wsgen -cp . example.Stock
  wsgen -cp . example.Stock -wsdl -servicename {http://mynamespace}MyService


```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsgen.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: wsgen.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe](jmap.exe-81D3ACB320CE4324DBD75A746B210E6B.md) | 61
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jps.exe](jps.exe-5AFACE3595288F9EF62F39721DEEC88C.md) | 71




MIT License. Copyright (c) 2020-2021 Strontic.


