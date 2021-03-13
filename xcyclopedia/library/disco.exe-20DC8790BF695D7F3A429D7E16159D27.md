---
title: disco.exe | .NET Frameworks Web Service Discovery Tool
excerpt: What is disco.exe?
---

# disco.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\disco.exe`
* Description: .NET Frameworks Web Service Discovery Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `20DC8790BF695D7F3A429D7E16159D27`
SHA1 | `3B59261752810566975F7008691EC83BD03C779F`
SHA256 | `1013BA5F76D06C88C89A286570B3F691F290180F1D8F60E4182F2824DF14A9F9`
SHA384 | `A338EB5DADB5F85634D4BD399883D7771E3D8FE9508EA40BCF83DDEC6115B4CFD7D13099F7CF9727E1C219A2BC68B9AB`
SHA512 | `B1398BF59874A8FF16FED40CBD2A2B51F6D86527974FBED3DF014D39044D0106C43BD7D2208470CC3771A7999A5C1AAAA7DE121DEDA5BBD47E040D34A741FC4B`
SSDEEP | `1536:U36g84qP7OibhK8RgdJlbb0Fnhh1BkVgWf66F:U36gKP7OiFWd8FTkVgWt`
PESHA1 | `7A463A35DCAECCB8CC1C6EA8DC887E3FDC9A4759`
PE256 | `DE5B448CD65F3038CA3118ACA80D659DD108A044DDD1AB900F3437570C6D5811`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Web Services Discovery Utility
[Microsoft (R) .NET Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation. All rights reserved.

disco.exe -
    Utility to discover the URLs of xml web services located on a web server
    and to save documents related to that xml web service on the local disk.
    The results.discomap, .wsdl and .xsd files produced by this tool can be
    used with wsdl.exe to produce web service clients and abstract web service
    servers using ASP.NET.

disco.exe <options> <url to discover>

     - OPTIONS -

/nologo
    Suppresses the banner.

/nosave
    Do not save the discovered documents or results to disk (for example
    wsdl, xsd and disco files). The default is to save the documents.

/out:<directoryName>
    The output directory to save the discovered documents in. The default
    is the current directory. Short form is '/o:'.

/username:<username>
/password:<password>
/domain:<domain>
    The credentials to use when the connecting to a server that
    requires authentication. Short forms are '/u:', '/p:' and '/d:'.

/proxy:<url>
    The url of the proxy server to use for http requests.
    The default is to use the system proxy setting.

/proxyusername:<username>
/proxypassword:<password>
/proxydomain:<domain>
    The credentials to use when the connecting to a proxy server that
    requires authentication. Short forms are '/pu:', '/pp:' and '/pd:'.

```

### Usage (stderr):
```cmhg
ERROR: help
  - Invalid URI: The format of the URI could not be determined.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\disco.exe |
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

* Original Filename: disco.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/1013ba5f76d06c88c89a286570b3f691f290180f1d8f60e4182f2824df14a9f9/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\disco.exe](disco.exe-D4185B3B4A99F18237168473F3AA8AAA.md) | 77




MIT License. Copyright (c) 2020-2021 Strontic.


