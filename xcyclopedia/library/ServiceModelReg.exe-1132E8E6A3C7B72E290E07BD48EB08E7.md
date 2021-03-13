---
title: ServiceModelReg.exe | WCF Generic Command for Vista Setup
excerpt: What is ServiceModelReg.exe?
---

# ServiceModelReg.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\ServiceModelReg.exe`
* Description: WCF Generic Command for Vista Setup
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1132E8E6A3C7B72E290E07BD48EB08E7`
SHA1 | `4AFA5141D45586FA4EAB89F275B002401BD567A4`
SHA256 | `2B7E4DD728F186AD6F6E55F53F863A560006773CC97D17AC847A305B29F96782`
SHA384 | `E5EFF017ED364CC6ACD532F4560720AB1C94A23A0CB27010FA886E417FE6420E1391D8F4F6E4CDD5CF21AD38A1E337E5`
SHA512 | `3EAB6F2B44E68E5DC0BAB9DF9BCD4657A460A74BFA88338A01C22C26119382AB7936D74B4F47BC49D5B8003FB3D6B7B8139FF71F9A3581224AE26031C8D39715`
SSDEEP | `3072:5l8RCa6cA+LExtZ6bQJP/FS6UYwQHbKv4CpxQC2mCm1/ql70bN6qtoh5rK0UBk+L:0b6rL/w0g60QHGJQ74ahwk+QA`
IMP | `2396F3556CB4EAD513113A1FA46E57C3`
PESHA1 | `713B6DBC36CA1278D5B47A5F685FB3DC8EC33E44`
PE256 | `7A5C78C46A1944AB63916AF0A5C6A31EDDDBEF34D4BB012DB9DCD5C840E58799`

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
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ServiceModelReg.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/2b7e4dd728f186ad6f6e55f53f863a560006773cc97d17ac847a305b29f96782/detection





MIT License. Copyright (c) 2020-2021 Strontic.


