---
title: WsatConfig.exe | MB Version update tool
excerpt: What is WsatConfig.exe?
---

# WsatConfig.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe`
* Description: MB Version update tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D7F8F9FE510F05C919F07DEEF56B8B3E`
SHA1 | `C462EF992AAFFC75CC7AC3661369224DBFFA4F13`
SHA256 | `1D2E773836CFFB7F8529A56B51B7AA385C8109EBC8BFD4D3EBC8818CD6D8C67C`
SHA384 | `F38BDB5E100840D73107CEE586291BF38B39E38CCF031B103064217C35B636E1CA21BBD4819BB5CFF3A8EB152B6FDF8B`
SHA512 | `5D4F233FAE99AA09BBC46561F2E16F4EE486A7C7DFE2A64CC20B9E7B539FF52BF29FCC45179D4D99B8BC0D75E451A9BF1D903A1B84A62AD603861CCBF0759C82`
SSDEEP | `3072:W95GnK+au5ef9xXMnbLUpdrsHvhoIfshxitOCq:mQdx5q9pOPh/fYiDq`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `1A3830961583B89523C424835A72DC507B538E2C`
PE256 | `A0BF75E9B36C2CC3EA0A29397B833FAEE2DABB0212CC1B1FC8919E6E1A384779`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) WS-AtomicTransaction Configuration Utility
[Microsoft (R) Windows (R) Communication Foundation, Version 4.8.4084.0]
Copyright (c) Microsoft Corporation.  All rights reserved.

Utility to configure WS-AtomicTransaction network support

                            -- OPTIONS --
        -network:{enable|disable} - Enables or disables the WS-AtomicTransaction network support

                  -port:<portNum> - Sets the HTTPS port for WS-AtomicTransaction

  -endpointCert:{machine|<thumb>| - Uses the machine certificate or another local endpoint certificate specified by thumbprint or Issuer\SubjectName pair. Use {EMPTY} for the subject name if it's empty.
            "Issuer\SubjectName"}   

             -accounts:<account,> - Specifies the comma-separated list of accounts that can participate

         -accountsCerts:{<thumb>| - Specifies the comma-separated list of thumbprint or Issuer\SubjectName identifiers for the certificates that can participate. Use {EMPTY} for the subject name if it's empty.
           "Issuer\SubjectName",}   

   -virtualServer:<virtualServer> - Specifies the DTC resource cluster name

                   -timeout:<sec> - Specifies the default outgoing timeout in seconds

                -maxTimeout:<sec> - Specifies the maximum incoming timeout in seconds

 -traceLevel:{Off|Error|Critical| - Sets the trace level
             Warning|Information|   
                     Verbose|All}   

  -traceActivity:{enable|disable} - Enables or disables the tracing of activity events

      -traceProp:{enable|disable} - Enables or disables the tracing of propagation events

       -tracePII:{enable|disable} - Enables or disables the tracing of personally identifiable information

                            -show - Shows the current WS-AtomicTransaction protocol settings

                         -restart - Restarts MSDTC to make changes active immediately. If not specified, the changes will take effect when MSDTC is next started.

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe |
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

* Original Filename: WsatConfig.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/1d2e773836cffb7f8529a56b51b7aa385c8109ebc8bfd4d3ebc8818cd6d8c67c/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe](WsatConfig.exe-37022D63226636484118C28197DB08B4.md) | 82
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\WsatConfig.exe](WsatConfig.exe-37022D63226636484118C28197DB08B4.md) | 82
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\WsatConfig.exe](WsatConfig.exe-D7F8F9FE510F05C919F07DEEF56B8B3E.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


