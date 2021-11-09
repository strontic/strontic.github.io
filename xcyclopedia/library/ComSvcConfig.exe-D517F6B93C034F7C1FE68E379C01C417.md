---
title: ComSvcConfig.exe | ComSvcConfig.exe
excerpt: What is ComSvcConfig.exe?
---

# ComSvcConfig.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe`
* Description: ComSvcConfig.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D517F6B93C034F7C1FE68E379C01C417`
SHA1 | `7413AC167789623B396CAAE4C932EF0F891DA07F`
SHA256 | `1AED983A83F653E4BEBDA5DBAC78E73AD5CBC1FACB1953D72512FA8CD613A074`
SHA384 | `C97824F7BAAB84B169D6A5D2310541B4D3B9804974D2E41BE562E16B8F67B52ED13BD6B234AD7D0051BB36CED1882E67`
SHA512 | `D35E81F8BC137F08E9C92E1825B686615595C29D17738E60E76A26025FDC3E75D31E720F66001761C6D8E748DFF545F793029BC61089D33396A8ECA7A8CC3553`
SSDEEP | `3072:Jo7sKLcmOLrT0bLOi48nOE3dz/qacuzYPa28Z31qB0Q:isKLcmOLgLln9ZRzQ`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `5C0C2BB73FFB81A0C0864C207DAF41401F07CFCA`
PE256 | `AE87A68C86823BFC0B664CFFAF4E77B2787B72F306CF4FE4B4E7A752D528DA7E`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) COM+ Service Model Integration Configuration Tool
[Microsoft (R) Windows (R) Communication Foundation, Version 4.8.4084.0]
Copyright (c) Microsoft Corporation.  All rights reserved.

Utility to configure Service Model integration for COM+ applications

   - USAGE -
 ComSvcConfig.exe mode [Options]

   - MODE - 
 /install    
   Configure Service Model integration for an application's component interfaces (short form /i)
 /uninstall 
   Uninstall Service Model integration for an application's interfaces (short form /u)
 /list  
   List applications and interfaces that are configured for Service Model integration (short form /l)

   - OPTIONS -
 /application:<ApplicationID|ApplicationName>
       Specify the COM+ application to configure (short form /a)
 /contract:<ClassID|ProgID|*, InterfaceID|InterfaceName|*[.*|{Method1,Method2,Method3}]>
       Specify the interface and methods (optional) to be configured (short form /c)
 /allowreferences
       Specify that object reference parameters are permitted (short form /r)
 /hosting:<complus|was>
       Specify the hosting process for the Service Model services (short form /h)
 /webSite:<WebsiteName>
       Specify the web site for web hosting (short form /w)
 /webDirectory:<WebDirectoryName>
       Specify the virtual directory for web hosting (short form /d)
 /mex
        Include an additional WS-MetadataExchange endpoint   (short form /x)
 /id
       Displays the application,component and interface information as identifiers (short form /k)
 /nologo
       Prevent ComSvcConfig from displaying logo (short form /n)
 /verbose
       Shows all warnings (short form /v)
 /? or /help
       Display this usage message

   - EXAMPLES -
  ComSvcConfig.exe /install /application:TestApp /contract:* /hosting:complus
  ComSvcConfig.exe /install /application:TestApp /contract:TestComponent,ITest /hosting:was /webDirectory:testdir /mex
  ComSvcConfig.exe /list
  ComSvcConfig.exe /list /hosting:complus
  ComSvcConfig.exe /list /hosting:was
  ComSvcConfig.exe /uninstall /application:OnlineStore /contract:* /hosting:complus
  ComSvcConfig.exe /uninstall /application:OnlineStore /contract:* /hosting:was


```

### Usage (stderr):
```cmhg
Error: The h option requires that a value be specified.

```

### Child Processes:
powershell.exe

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe |
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

* Original Filename: ComSvcConfig.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/1aed983a83f653e4bebda5dbac78e73ad5cbc1facb1953d72512fa8cd613a074/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-64F14E3BB2E3E1FFF089FDB76E8315F5.md) | 82
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-64F14E3BB2E3E1FFF089FDB76E8315F5.md) | 82
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-D517F6B93C034F7C1FE68E379C01C417.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


