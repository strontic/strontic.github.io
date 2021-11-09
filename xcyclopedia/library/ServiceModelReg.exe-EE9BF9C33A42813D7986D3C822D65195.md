---
title: ServiceModelReg.exe | WCF Generic Command for Vista Setup
excerpt: What is ServiceModelReg.exe?
---

# ServiceModelReg.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ServiceModelReg.exe`
* Description: WCF Generic Command for Vista Setup
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `EE9BF9C33A42813D7986D3C822D65195`
SHA1 | `716F12EC7645F70FECACF1D88D7BBA2D74D5AB2E`
SHA256 | `73315373B0F6CB3CA57E7808A47BB538B44E84CEDBF2B2F76982036D1D7A94AC`
SHA384 | `963836BBA2EEF7002016F832A00A0E759C99C9D0907B3CD60215D5B090B971C2B275CDEC057098346F8685FC8E5FD372`
SHA512 | `435A0402C84B205E82D3417D39CB69C8CE3F296CA1A51171871D093BBDE0193297347EB68FB66837095CC5846CBF17AAD7F24C06DE0633B01357B2B7EF6C5558`
SSDEEP | `3072:ll8RCa6cA+aExtZ6bQJP/FS6UYwQHbKv4CpxQC2mCm1/ql70bN6qtoh5rK0ODk+o:Ab6r+/w0g60QHGJQ74ahQk+Q4o`
IMP | `2396F3556CB4EAD513113A1FA46E57C3`
PESHA1 | `602123474B8CF6EC25BB3E1DB1BB581CCDC06C15`
PE256 | `055A3270DC87444DBDD628BCB3D045304212D05EE198DAD34910B3E8F996E6C2`

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
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ServiceModelReg.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ServiceModelReg.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/73315373b0f6cb3ca57e7808a47bb538b44e84cedbf2b2f76982036d1d7a94ac/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ServiceModelReg.exe](ServiceModelReg.exe-1132E8E6A3C7B72E290E07BD48EB08E7.md) | 93




MIT License. Copyright (c) 2020-2021 Strontic.


