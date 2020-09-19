---
title: xjc.exe | OpenJDK Platform binary
---

# xjc.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\xjc.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `ED867085531234D4249A88EC309109CA`
SHA1 | `B29C0F259AF5E7A3960418E9CB606B89F15FD0E7`
SHA256 | `996F8DF6B043F105E46581039B2341C3BF9180F8C836F1F3129BF5F5FAA398AF`
SHA384 | `456715BCCE536AD7A5A235E068562699739EF1B18D9A38B0811BE824FF06FF406A73CBD870DE1A5CBACC82448D987A0C`
SHA512 | `C976C61F11B8CCB52021334884BC0326AFD445090326EDEF6924B716CC23FB16E4EB84844BC98ACBC131FD0C5250D8D877B4614F18AF5AC1CCBEA1ABF7339160`
SSDEEP | `384:Gps45hnprqKmSHhV8zSeeF4Szv3K6jSFJ0fUDgf2hJ:GpsinpCS/8zfeFJ3Kg0ZUf2hJ`

## Runtime Data

### Usage (stdout):
```cmhg
"/?" is neither a file name nor a URL

Usage: xjc [-options ...] <schema file/URL/dir/jar> ... [-b <bindinfo>] ...
If dir is specified, all schema files in it will be compiled.
If jar is specified, /META-INF/sun-jaxb.episode binding file will be compiled.
Options:
  -nv                :  do not perform strict validation of the input schema(s)
  -extension         :  allow vendor extensions - do not strictly follow the
                        Compatibility Rules and App E.2 from the JAXB Spec
  -b <file/dir>      :  specify external bindings files (each <file> must have its own -b)
                        If a directory is given, **/*.xjb is searched
  -d <dir>           :  generated files will go into this directory
  -p <pkg>           :  specifies the target package
  -httpproxy <proxy> :  set HTTP/HTTPS proxy. Format is [user[:password]@]proxyHost:proxyPort
  -httpproxyfile <f> :  Works like -httpproxy but takes the argument in a file to protect password 
  -classpath <arg>   :  specify where to find user class files
  -catalog <file>    :  specify catalog files to resolve external entity references
                        support TR9401, XCatalog, and OASIS XML Catalog format.
  -readOnly          :  generated files will be in read-only mode
  -npa               :  suppress generation of package level annotations (**/package-info.java)
  -no-header         :  suppress generation of a file header with timestamp
  -target (2.0|2.1)  :  behave like XJC 2.0 or 2.1 and generate code that doesnt use any 2.2 features.
  -encoding <encoding> :  specify character encoding for generated source files
  -enableIntrospection :  enable correct generation of Boolean getters/setters to enable Bean Introspection apis 
  -disableXmlSecurity  :  disables XML security features when parsing XML documents 
  -contentForWildcard  :  generates content property for types with multiple xs:any derived elements 
  -xmlschema         :  treat input as W3C XML Schema (default)
  -relaxng           :  treat input as RELAX NG (experimental,unsupported)
  -relaxng-compact   :  treat input as RELAX NG compact syntax (experimental,unsupported)
  -dtd               :  treat input as XML DTD (experimental,unsupported)
  -wsdl              :  treat input as WSDL and compile schemas inside it (experimental,unsupported)
  -verbose           :  be extra verbose
  -quiet             :  suppress compiler output
  -help              :  display this help message
  -version           :  display version information
  -fullversion       :  display full version information


Extensions:
  -Xinject-code      :  inject specified Java code fragments into the generated code
  -Xlocator          :  enable source location support for generated code
  -Xsync-methods     :  generate accessor methods with the 'synchronized' keyword
  -mark-generated    :  mark the generated code as @javax.annotation.Generated
  -episode <FILE>    :  generate the episode file for separate compilation
  -Xpropertyaccessors :  Use XmlAccessType PROPERTY instead of FIELD for generated classes

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\xjc.exe |
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

* Original Filename: xjc.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020





MIT License. Copyright (c) 2020 Strontic.


