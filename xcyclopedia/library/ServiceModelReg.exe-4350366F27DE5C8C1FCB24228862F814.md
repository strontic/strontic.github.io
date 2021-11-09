---
title: ServiceModelReg.exe | WCF Generic Command for Vista Setup
excerpt: What is ServiceModelReg.exe?
---

# ServiceModelReg.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ServiceModelReg.exe`
* Description: WCF Generic Command for Vista Setup
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `4350366F27DE5C8C1FCB24228862F814`
SHA1 | `15EF980D0D28FD73129F8C2E280A16B5EF70F6B4`
SHA256 | `F1449D7E36137720FB1244DBEEC256E11986891ADF7D36250428DBC48E3B163B`
SHA384 | `42A08D7CE4149813C02F2B0ACF048AA726C1372DC2E45DC4E1192F75C6691868DF57E32B3534931CD6366EC1C95ED595`
SHA512 | `3C35720ED65586868C1DFE0C0CFE16299FA72B73652B4EFAA3F2646D971DB2B82A4B4BA83835A5EE95FD689279DCA04785FBEC709BB97EFF902F2CEF895BBDA1`
SSDEEP | `6144:Cvni+/0U2UgDSU7uOWpuxlzebez16/g2cHbm+zcguAXedranS:6i+/0U2UgDSU7ujuxlzeqp6/gPpxet`
IMP | `F237FB4E5A065A1C3DEE4A01B2EDC0C0`
PESHA1 | `AB6B8CCF8908E36EF2E6F1926C4CC8CF3A90A4F0`
PE256 | `25E6D7CDDA898E1A45BB9532E3D99728BBC53FAB748E12D60D4707AB6CA014DA`

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
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ServiceModelReg.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f1449d7e36137720fb1244dbeec256e11986891adf7d36250428dbc48e3b163b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ServiceModelReg.exe](ServiceModelReg.exe-86A216436C5C68CF48875EE3A6DBAB4C.md) | 94




MIT License. Copyright (c) 2020-2021 Strontic.


