---
title: disco.exe | .NET Frameworks Web Service Discovery Tool
excerpt: What is disco.exe?
---

# disco.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\disco.exe`
* Description: .NET Frameworks Web Service Discovery Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D4185B3B4A99F18237168473F3AA8AAA`
SHA1 | `E589ABC1C3EE4E96590B93848F24D30524176496`
SHA256 | `3912EF15D9D554C05E129ADDC0810ED0BCC66FB8458EBF49A1185EB2B347BD98`
SHA384 | `D42AF0964835D35F9BE06A314A6AA93F836F883D06C9E14932DAFF88174883478562D14E55CF5340B050F7F2F9853A64`
SHA512 | `698DB53BFFF88C8730B16F62974E0214DD2BB387F1B93CA180AA240AEF057463F6DA0AC8DEA2409A4E17B6BBD024D7570BDD24B41B784FEF7309459F719C7B31`
SSDEEP | `1536:v36g84qP7Oi8hK8RgdJlb60Fnhh1BkVpKm97L:v36gKP7OiUWdrFTkVpK0L`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `16BD5364256D988B4B314F9E349F8B6BDAA75764`
PE256 | `DB0291B3DBC4FB3726ABC22AA4CF9196C632334D97F02A374613744D934F4243`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\disco.exe |
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

* Original Filename: disco.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3912ef15d9d554c05e129addc0810ed0bcc66fb8458ebf49a1185eb2b347bd98/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\disco.exe](disco.exe-20DC8790BF695D7F3A429D7E16159D27.md) | 77




MIT License. Copyright (c) 2020 Strontic.


