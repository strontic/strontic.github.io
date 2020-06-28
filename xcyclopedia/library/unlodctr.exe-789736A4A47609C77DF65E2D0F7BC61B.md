---
title: unlodctr.exe | Unload PerfMon Counters
---

# unlodctr.exe 

* File Path: `C:\Windows\system32\unlodctr.exe`
* Description: Unload PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `789736A4A47609C77DF65E2D0F7BC61B`
SHA1 | `7879DE7ABFBACE22C691F7C05C21A9518C28DDEF`
SHA256 | `E8EEAC85A29EB75A4CF41509EA982AE1B6256D0C7CDFF3299ED3DF3CE34356D9`
SHA384 | `3D7CA89804A9A75FC54F18C362E3426BFC58CE6462CEE8ED7BDAE82BD454991BDEFCE59ED166226289A13204D2A10A2C`
SHA512 | `35FF07C6038C74399176454416118853B48257BF003646E91C10F4D59DE31D4BB5BC502F5D2701C3E8576CB750530D2825C1688DD3C2B59C80BEDFAB5266758C`
SSDEEP | `768:Urp1PX8kHsc3L2CK7JhIlqyTDwI+pXn7M9DdRMTdplMcAujMFwf/wEdk:81PXtHZlqy4IMXn49DdRMTTlMcrCwf4x`

## Runtime Data

### Usage (stdout):
```Batchfile

 
UNLODCTR 
       uninstalls a performance counter provider. 
Usage: 
       UNLODCTR <service-name> 
             uninstalls the v1.0 performance counter provider associated 
             with the <service-name> service.
       UNLODCTR /m:<manifest> 
             uninstall a v2.0 performance counter provider using the 
             provider GUID from the specified XML manifest.
       UNLODCTR /g:{ProviderGuid} 
             uninstall a v2.0 performance counter provider using the 
             specified provider GUID. The GUID should be specified in 
             registry form, i.e. {nnnnnnnn-nnnn...}
       UNLODCTR /p:<ProviderName> 
             uninstall a v2.0 performance counter provider matching the 
             specified provider name.

Note: any arguments with spaces in the names must be enclosed within double 
quotation marks.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


