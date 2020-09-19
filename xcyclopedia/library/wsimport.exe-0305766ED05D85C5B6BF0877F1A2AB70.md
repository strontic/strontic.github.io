---
title: wsimport.exe | OpenJDK Platform binary
---

# wsimport.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsimport.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `0305766ED05D85C5B6BF0877F1A2AB70`
SHA1 | `C7046D870DAB878A751DDE939B9B4C2049B5D741`
SHA256 | `75ACE0905B830CA97472C32DA7C9D71D8741C8CB538E68BD27107228CDA96605`
SHA384 | `6720EC8DABEE3785576E2EC425E85BE6984EA483AAA4CB9B3F04AE1FCE60DC69969BA8EE91F4ED9675A9CBD588BA0A86`
SHA512 | `BB8BB293CBB5808D0EB73CE00C2BEF486A364EC2A84BF7106BF3E209530792FB9E99F1450438699CD7181058F7313147CE4F2ABD1EB026F2A0F865A883C7C01C`
SSDEEP | `384:GpsKD5hnIqImSHhV8GseeK4SzvCK6jSt+gtLDgf2h6E:GpsAn/S/8GJeKJCKg0FUf2h6E`

## Runtime Data

### Usage (stdout):
```cmhg
"/?" is neither a file name nor an URL


Usage: wsimport [options] <WSDL_URI>

where [options] include:
  -b <path>                 specify jaxws/jaxb binding files or additional schemas
                            (Each <path> must have its own -b)
  -B<jaxbOption>            Pass this option to JAXB schema compiler
  -catalog <file>           specify catalog file to resolve external entity references
                            supports TR9401, XCatalog, and OASIS XML Catalog format.
  -classpath <path>         specify where to find user class files and wsimport extensions
  -cp <path>                specify where to find user class files and wsimport extensions
  -d <directory>            specify where to place generated output files
  -encoding <encoding>      specify character encoding used by source files
  -extension                allow vendor extensions - functionality not specified
                            by the specification.  Use of extensions may
                            result in applications that are not portable or
                            may not interoperate with other implementations
  -help                     display help
  -httpproxy:<proxy>        set a HTTP proxy. Format is [user[:password]@]proxyHost:proxyPort
                            (port defaults to 8080)
  -J<javacOption>           pass this option to javac
  -keep                     keep generated files
  -p <pkg>                  specifies the target package
  -quiet                    suppress wsimport output
  -s <directory>            specify where to place generated source files
  -target <version>         generate code as per the given JAXWS spec version
                            Defaults to 2.2, Accepted values are 2.0, 2.1 and 2.2
                            e.g. 2.0 will generate compliant code for JAXWS 2.0 spec
  -verbose                  output messages about what the compiler is doing
  -version                  print version information
  -fullversion              print full version information
  -wsdllocation <location>  @WebServiceClient.wsdlLocation value
  -clientjar <jarfile>      creates the jar file of the generated artifacts along with the
                            WSDL metadata required for invoking the web service.
  -generateJWS              generate stubbed JWS implementation file
  -implDestDir <directory>  specify where to generate JWS implementation file
  -implServiceName <name>   local portion of service name for generated JWS implementation
  -implPortName <name>      local portion of port name for generated JWS implementation

Extensions:
  -XadditionalHeaders              map headers not bound to request or response message to 
                                   Java method parameters
  -Xauthfile                       file to carry authorization information in the format 
                                   http://username:password@example.org/stock?wsdl
  -Xdebug                          print debug information
  -Xno-addressing-databinding      enable binding of W3C EndpointReferenceType to Java
  -Xnocompile                      do not compile generated Java files
  -XdisableAuthenticator           disable Authenticator used by JAX-WS RI,
                                   -Xauthfile option will be ignored if set
  -XdisableSSLHostnameVerification disable the SSL Hostname verification while fetching
                                   wsdls

Examples:
  wsimport stock.wsdl -b stock.xml -b stock.xjb
  wsimport -d generated http://example.org/stock?wsdl


```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsimport.exe |
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

* Original Filename: wsimport.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe](jmap.exe-81D3ACB320CE4324DBD75A746B210E6B.md) | 58




MIT License. Copyright (c) 2020 Strontic.


