---
title: ServiceModelReg.exe | WCF Generic Command for Vista Setup
excerpt: What is ServiceModelReg.exe?
---

# ServiceModelReg.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ServiceModelReg.exe`
* Description: WCF Generic Command for Vista Setup
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `86A216436C5C68CF48875EE3A6DBAB4C`
SHA1 | `49D848D55A93B3F9040BC2D06DBB0C2BC316C4AD`
SHA256 | `4E6240E12755D0F48534A42F78B860FFBA993D94D386A7D64063A89AFA250814`
SHA384 | `237CEF16E02842B878EA874350B351E9DC7FEF7F1D41FF2F9F7A8F51B33365AB2E682CAD980611F1C15A6CFBBBC95DC8`
SHA512 | `31E6D2915E2642BF094AA2554C15F8A342FA25C001C5E5C32214A003BF6BD0181B38ED2ECC7AB4037FC4150DEB7BD79766529E680B9B112B06A1830A85896D41`
SSDEEP | `6144:tvni+/0U2UgDSU7uOWpuxlzebez16/g2cHbm+zcguAXedr2nW2:Ji+/0U2UgDSU7ujuxlzeqp6/gPpxel2`
IMP | `F237FB4E5A065A1C3DEE4A01B2EDC0C0`
PESHA1 | `14377B1F477FA0A42AC2AE8239CE88E86B216956`
PE256 | `9F95A7132C092A9C2F3FCDACFE6532D39415821C3C00CBD180846BABC01D6379`

## Runtime Data

### Usage (stdout):
```cmhg
[Error]Unknown switch '--help'.Microsoft (R) WCF/WF registration tool version 4.5.0.0 
Copyright (c) Microsoft Corporation.  All rights reserved. 
 
Administration utility that manages the installation and uninstallation of 
WCF and WF components on a single machine. 

Usage: 
    ServiceModelReg.exe [(-ia|-ua|-r)|((-i|-u) -c:<command>)] [-v|-q] [-nologo] [-h] 
  -ia 
    Install all components 
  -ua 
    Uninstall all components 
  -r 
    Repairs all components 
  -i 
    Install components specified with -c 
  -u 
    Uninstall components specified with -c 
  -c:<component> 
    Install/uninstall a component: 
      httpnamespace        - HTTP namespace reservation 
      tcpportsharing       - TCP port sharing service 
      tcpactivation        - TCP activation service 
      namedpipeactivation  - Named pipe activation service 
      msmqactivation       - MSMQ activation service 
      etw                  - ETW event tracing manifests (Windows Vista or later) 
    Can be used to install several components at the same time 
  -q 
    Quiet mode (only error logging) 
  -v 
    Verbose mode 
  -nologo 
    Suppress the copyright and banner message 
  -h 
    Displays this help text. 
 
Examples: 
    ServiceModelReg.exe -ia 
      Installs all components 
    ServiceModelReg.exe -i -c:httpnamespace -c:etw 
      Installs HTTP namespace reservation and ETW manifests 
    ServiceModelReg.exe -u -c:etw 
      Uninstalls ETW manifests 
    ServiceModelReg.exe -r 
      Repairs the installation
[Error]Switch '-c' requires a component to be specified for installation or uninstallation. Please specify which components to install or uninstall.


```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ServiceModelReg.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ServiceModelReg.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/4e6240e12755d0f48534a42f78b860ffba993d94d386a7d64063a89afa250814/detection/





MIT License. Copyright (c) 2020 Strontic.


