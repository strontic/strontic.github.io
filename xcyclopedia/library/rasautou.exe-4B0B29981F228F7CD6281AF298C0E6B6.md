---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\Windows\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `4B0B29981F228F7CD6281AF298C0E6B6`
SHA1 | `3A0AF8EB6E4E9C2B59495768FD016A4E23C1C466`
SHA256 | `F5FE16960331D2CB819706BAA6E1935097CC09A843A4747FFBCD3C8E27ED1CD5`
SHA384 | `BDF0A0AF5A277342A814528913398E69B7B4EBF9A134E538C915709C4B7AB46D66A738759C10042320DA5FFB7991426E`
SHA512 | `806663DBEF0DA05E2911689DCE2A52BCC1BB497398027939B8238AA33312888775D89628C89608FCE393432428E04BDB03C943D1C126878003806DDC1A72AD2A`
SSDEEP | `384:tKILjqA5B9v4YCOSPQlxZuHfs2CWMBWlGB7wp:t7rQYof/s24sM7wp`
IMP | `6FD6CB5E209EBD24A870B74D8EE7F599`
PESHA1 | `753BE8A7CA5DC598D61D25B8F8B1B7C921A418D4`
PE256 | `3ABA7A4E76F381145973EC81B0EDABFB4636C1B2A78FB87B5D5A8E9B44346083`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rasautou.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/f5fe16960331d2cb819706baa6e1935097cc09a843a4747ffbcd3c8e27ed1cd5/detection/


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


