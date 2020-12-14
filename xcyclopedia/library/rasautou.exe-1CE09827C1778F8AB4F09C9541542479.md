---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\Windows\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `1CE09827C1778F8AB4F09C9541542479`
SHA1 | `275DF18EE0F0B482708390B3A62C870CE303A9A8`
SHA256 | `EEC5DBDF411A89F65247679840DC7A902180C1D23C94B0D92C283B4130664263`
SHA384 | `23AF6F5C9B610B49095DB6AD1DB3BAF2A7992B1B5C622E80D78E261DC4BCC27C842696FD23BF9E40555FD22A8D606D9C`
SHA512 | `F414C423C1CF770A9DFA036CE98AA7B527A9B8C3CE476EA09C64FD74B8EDB7DC45D0250BA2C7062CD74008A07D8E5FC9E5A65027A17066BE11A17E04B3629573`
SSDEEP | `384:lMzAORLrDeL9wSi37rT8Oy11BTwt4hxPsWHBW:ls/D5SwT8OZ2xPt`
IMP | `0B915B3D21B94438146557937D698E77`
PESHA1 | `ECC4B7B29DD08BFDF2B00ED205C8FF952507EBE7`
PE256 | `81F3401A4463D218504CA4FF634FC30F5ACE05AD6C0ED7ED3F6B4D98E9DF1B22`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rasautou.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/eec5dbdf411a89f65247679840dc7a902180c1d23c94b0d92c283b4130664263/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rasautou.exe](rasautou.exe-749F7EE0E60F24A1C95C5667C7B05F77.md) | 55

## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


