---
title: ComSvcConfig.exe | ComSvcConfig.exe
excerpt: What is ComSvcConfig.exe?
---

# ComSvcConfig.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe`
* Description: ComSvcConfig.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `64F14E3BB2E3E1FFF089FDB76E8315F5`
SHA1 | `39DFD74AEE9C930B51CD107AB6C49044794C1F4E`
SHA256 | `4565B33BEE3128C1AF183140A1685F065FEA83AE987610515310FDAF44AED9CA`
SHA384 | `29E842BF05B0DE2651A410C714C55455D64128CFF3E9C20C089DC3C311507B68216486F9C72AC1C5ED2EF703BCE063D1`
SHA512 | `61F214DCA28D3901126E3EAD5594E3810CAE149CFC010DB309F5D26058BE78E449494694CD6447F933763B1448DF46119A38EC2AA6BF6456870038F468F31622`
SSDEEP | `3072:Wo7sKLcmOLrT0bLOi48nOE3dzxqacuzYaas8ZB1qoW66:bsKLcmOLgLln9ZD/v`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `440AC5249D60E4613EA512D3B18395ED6793BF1D`
PE256 | `56543784F98D465D2586DFDCD5EE6309329435449230DB3B7D37E91B8548F35A`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) COM+ Service Model Integration Configuration Tool
[Microsoft (R) Windows (R) Communication Foundation, Version 4.8.4161.0]
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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe |
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

* Original Filename: ComSvcConfig.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/4565b33bee3128c1af183140a1685f065fea83ae987610515310fdaf44aed9ca/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-D517F6B93C034F7C1FE68E379C01C417.md) | 82
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-64F14E3BB2E3E1FFF089FDB76E8315F5.md) | 100
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ComSvcConfig.exe](ComSvcConfig.exe-D517F6B93C034F7C1FE68E379C01C417.md) | 82




MIT License. Copyright (c) 2020-2021 Strontic.


