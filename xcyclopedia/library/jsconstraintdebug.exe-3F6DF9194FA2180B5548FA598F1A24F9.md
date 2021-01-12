---
title: jsconstraintdebug.exe | JS Print Constraint Debug Tool
excerpt: What is jsconstraintdebug.exe?
---

# jsconstraintdebug.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\jsconstraintdebug.exe`
* Description: JS Print Constraint Debug Tool

## Hashes

Type | Hash
-- | --
MD5 | `3F6DF9194FA2180B5548FA598F1A24F9`
SHA1 | `DEF3B3D30C82031CBA2736A9C0348D7C96174571`
SHA256 | `015D28A5FF13F1C55A8906E962524F41F38BABC27B00D35C42120157A4AE235A`
SHA384 | `0450590FA47881D5D713A0598D512055ACC4CCE45A7B1EA2AA9FAFA92A356C3EACF1DD59F75F2E9D44532F66304FC62E`
SHA512 | `A342BFFEFD944D69CACF1437E38D1E1F5BDE169ADFF4C3FD29637AD0BE9AC6F3B0FC492092360422085FCB3C5D2BDE702369720F64E33980693483C5266FCEE6`
SSDEEP | `1536:HHuul8o9iz2jwFAoh5NXlU9yF5LVCT0/dKgwj8:58Y3jwFAoh31YyF5Lq0/ojj8`
IMP | `2605D1053D66F712DCFAD974C3BD94F7`
PESHA1 | `A026A5CD23A93D47523139AD814B8F5A92D6516E`
PE256 | `D654EC4D972E40B07B85744FC52988D7D812DA2339FE0CA5B6E0E2553337A2A2`

## Runtime Data

### Usage (stdout):
```cmhg


    Usage: JSPrintContstraintDebug.exe <PrinterName> <PrintTicket1.xml>[<PrintTicket2.xml>][<JsFile.js>]

    PrinterName      : Printer name which contains driver JS files to be debugged.

    PrintTicket1.xml : Path to Print Ticket XML file which will be passed to
                      JavaScript Print Ticket APIs.

    PrintTicket2.xml : Path to optional second Print Ticket XML file which will
                      be passed to Merge and Validate API.

                      If PrintTicket2.xml is not set the default DevMode will
                      be converted to a Print Ticket and will be passed to
                      the Merge and Validate API.

    JsFile.js        : Path to optional replacement JavaScript constraints
                      source file

                      If the optional JsFile.js parameter is set, the passed
                      file replaces the JS file in the target print driver
                      before debugging.

    NOTE : This tool assumes that user has installed the printer previously, and the
           machine has Visual Studio debugger installed.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\jsconstraintdebug.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: JSPrintConstraintDebug.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


