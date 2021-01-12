---
title: jsconstraintdebug.exe | JS Print Constraint Debug Tool
excerpt: What is jsconstraintdebug.exe?
---

# jsconstraintdebug.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\jsconstraintdebug.exe`
* Description: JS Print Constraint Debug Tool

## Hashes

Type | Hash
-- | --
MD5 | `295E87A47895FD05365319B38264D231`
SHA1 | `7F42ED8DC654CFE99C86E9C61E9C9CA19FC8A050`
SHA256 | `9141732724610F808418A26E704E8F2BA09BBEF1B22F48CD544E2A53EE71259F`
SHA384 | `426FD78E6C4958E81C74A891987FAC6110B8DC9D442CBD421C83D7DD32A9AF639D5A996D7B00AC939A3FAD0B42694518`
SHA512 | `D13E5DC2CCC839CAE9E39B263AAC2187FB4D28C7BBADEA63FBE04A7695AE7AE1680D1E63F68AFB66B144B57FBCD43F21D82FE2C268B95C913D652494D60B7018`
SSDEEP | `768:jAHFCO/Ve02kAr981SVD4T0CCH+9D7ee8YBNggzipOa22:Exk02km98YV0fl9D7p/Be7pO`
IMP | `5ECB0D77F67F8C06DEFED00F7F2E8EF8`
PESHA1 | `C16EDFE47D7CEFE2A8275AAEDD910F4C81B7842B`
PE256 | `192A9F70517B407BBC8FA682C0B5778E8AD0E953008A785797CD9334AB2D5A6C`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\jsconstraintdebug.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


