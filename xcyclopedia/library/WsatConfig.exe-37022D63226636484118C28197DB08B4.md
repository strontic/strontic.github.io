---
title: WsatConfig.exe | MB Version update tool
excerpt: What is WsatConfig.exe?
---

# WsatConfig.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe`
* Description: MB Version update tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `37022D63226636484118C28197DB08B4`
SHA1 | `07C7D372C909C44E201F35D33A5C9A194AEB458F`
SHA256 | `D1FC722D5E6994AAEADE7B8B7E5B392A4F2BB7D93CA64BD058038A266480B2E6`
SHA384 | `B5AD5ECF7E63D3201C4282752E8A14DC15638B160BD699DB5F76D5AD560B7538E49AF5D2808AC18E302F3249B98E2CD8`
SHA512 | `F8C61774E7BFE403DECD15704B0726612B11B14053E807856784D6B62991B0669E6A2A99418B50E0A93C413E8BED42E487EAB99847CB2D21AFAD172FCE58883C`
SSDEEP | `3072:795GnK+au5ef9xXMnbLUpdrsHvhQOfshXitawsG:vQdx5q9pOPhNfmiF3`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `0768374E59727C3D837DAF2D816C9B6D609E5E26`
PE256 | `BAB803F8AAD30C7CEA45DFFFF3E42F2A69AB66DB2631FE16295AC9219615FB1A`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) WS-AtomicTransaction Configuration Utility
[Microsoft (R) Windows (R) Communication Foundation, Version 4.8.4161.0]
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
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe |
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

* Original Filename: WsatConfig.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d1fc722d5e6994aaeade7b8b7e5b392a4f2bb7d93ca64bd058038a266480b2e6/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\WsatConfig.exe](WsatConfig.exe-D7F8F9FE510F05C919F07DEEF56B8B3E.md) | 82
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\WsatConfig.exe](WsatConfig.exe-37022D63226636484118C28197DB08B4.md) | 100
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\WsatConfig.exe](WsatConfig.exe-D7F8F9FE510F05C919F07DEEF56B8B3E.md) | 82




MIT License. Copyright (c) 2020-2021 Strontic.


