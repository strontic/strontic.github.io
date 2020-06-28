---
title: unlodctr.exe | Unload PerfMon Counters
---

# unlodctr.exe 

* File Path: `C:\Windows\SysWOW64\unlodctr.exe`
* Description: Unload PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EAF86537E26CC81C0767E58F66E01F52`
SHA1 | `D9F24D699714586148342700F4490F7597AB0E7B`
SHA256 | `68E5607D0AA1A52BFF70FE53C7EB0C5D27B342886BCBFEA7FBFEFD4168951F9B`
SHA384 | `E797E79E9DF90E0A881B1253E0FE5C39C83F09C4A53BB242C3D3C1B2BF4149793D53268D684B09284A9D85FCC708CCDC`
SHA512 | `75E591DBAC45ED1559559A47405D2E934D3D41D1E37CBB712F575DBF140509C3C60FE335E60006331C8E694558CE8635E116E7EDD244D5105664EAE79BFC2524`
SSDEEP | `768:jZlM8QoRNUQ8QkY6krH0CUEGuDSnhTUflUk:9lM8XUVYH0Cyu+nxUflU`

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

* Original Filename: UNLODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


