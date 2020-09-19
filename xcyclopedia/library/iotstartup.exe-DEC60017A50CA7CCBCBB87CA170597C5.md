---
title: iotstartup.exe | IotStartup
---

# iotstartup.exe 

* File Path: `C:\WINDOWS\system32\iotstartup.exe`
* Description: IotStartup

## Hashes

Type | Hash
-- | --
MD5 | `DEC60017A50CA7CCBCBB87CA170597C5`
SHA1 | `773BDBB4FFBA1010D252F8657100F8C1105DE9F2`
SHA256 | `BC581FF81D05BE8C1CAD2C58D8E81C601F91C709ECD065621EE7CC402F9F2744`
SHA384 | `7B165292D3108EA5FF379B86D9ABAD24FF252DF03819E98CA90FAA2F35A53B7F37034D1299AA4BE744E8284F80FE70D3`
SHA512 | `3962DC1483D74051216C9383356F2A882E0EF5A8BE2B3714BDCB9069017BE68CC017772A7DC765AF6763F691D0F95E98A26736A0744B3777CEFD9E44F2320932`
SSDEEP | `3072:dbPAv9zchsC1B6KP/IMrbU8pzj10PePeM1RI0l4bXR+cirj9cuiV:dcv9zchz1B6KP/IMrbU8pXKEeiI0lu+s`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  IotStartup [list|add|remove|startup] ([headed|headless]) (suppress) (std::regex regular expression with implied ^ prepended)
  IotStartup [run|stop] (std::regex regular expression with implied ^ prepended)
  IotStartup [help|-?|-h|--help]

Examples:
  IotStartup list                   // list installed applications
  IotStartup list headed            // list installed headed applications
  IotStartup list headless          // list installed headless applications
  IotStartup list MyApp             // list installed applications that match pattern MyApp

  IotStartup add headed MyApp       // add headed application that matches pattern MyApp.  Pattern must match only one application.
  IotStartup add headless Task1     // add headless applications that match pattern Task1

  IotStartup remove headless Task1  // remove headless applications that match pattern Task1
  IotStartup remove headless suppress Task1  // remove headless applications that match pattern Task1 and suppress WNF notification

  IotStartup startup                // list headed and headless applications registered for startup
  IotStartup startup MyApp          // list headed and headless applications registered for startup that match pattern MyApp
  IotStartup startup headed MyApp   // list headed applications registered for startup that match MyApp
  IotStartup startup headless Task1 // list headless applications registered for startup that match Task1

  IotStartup run MyApp              // Start app identified by MyApp (see 'iotstartup list')
  IotStartup stop MyApp             // Stop app identified by MyApp (see 'iotstartup list')


```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iotstartup.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


