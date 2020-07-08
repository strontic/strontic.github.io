---
title: iotstartup.exe | IotStartup
---

# iotstartup.exe 

* File Path: `C:\Windows\system32\iotstartup.exe`
* Description: IotStartup

## Hashes

Type | Hash
-- | --
MD5 | `3CDBF5BEDE229EAEC307F6AA547E5239`
SHA1 | `7D9A89234D5DEA57576BD378D392B1471CCDC7A0`
SHA256 | `1726E468963A71BE4445369BA4822EBB4E058154EFB887D33F3D0939E322F8AD`
SHA384 | `22C7FE45B0DD6C1616C38F4DFDABA563E077FEA6B9411A788EA084AACFFF303F438A2E242237A064B04F668851336271`
SHA512 | `0A9A6E3EFBBFC8348CCFD3BC3CFE365FDA70BE7245BFFF739E09DD45CD2610FB6FC8EF16B4488C87FFDD40F1A089FFF28801AC3E3EC1C2A989B768BB9379245C`
SSDEEP | `3072:1apgtemxd/Jc4Yx3WJ781aY1b/0EVCug8cEexFQG33UUt:UpgxxdB3Q3WJ78gC0EVDcXxFb9t`

## Runtime Data

### Usage (stdout):
```Batchfile
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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iotstartup.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


