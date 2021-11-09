---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\WINDOWS\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `1BE2CA2A358E1BA20E1EE09EE663B7EE`
SHA1 | `152C458E3BBA4499CD5A15DF818488867899F0DA`
SHA256 | `7DCAAE3F0FE609727C7B64B011AE6C5C839F9881415046726E945D1E9D1B9300`
SHA384 | `A0B87917D1FEE16D8CCBBFD4611709890FF131BD07B3125F1766E05845F436CBA01CC2C8774819C35A06AEFAE7443FDE`
SHA512 | `CDAD12B78AF398EAF9A438276A1287304754B4F90F3D6BD602D81A009783B9AF40697F1A04783C79C4728775A92F45DFAA5A0B24E76E8D795075761E45915595`
SSDEEP | `192:MzwAwDT180k7iIad3iwq3bSSKhWxu/UWFOW:MkAwP1Jk7iIBioxu/UWFOW`
IMP | `90A23F469BA0443719430CBA4569B220`
PESHA1 | `05F63E51649D27111AE08C8C2420B0D161ECBDE4`
PE256 | `1E14D3A97AEDE2C8591670689ACD71FD368374EFA808ED31C63F756666D0F713`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\system32\write.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7dcaae3f0fe609727c7b64b011ae6c5c839f9881415046726e945d1e9d1b9300/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\write.exe](write.exe-6F738A98257D152943A9E5DFAE1FBC44.md) | 43
[C:\WINDOWS\write.exe](write.exe-1BE2CA2A358E1BA20E1EE09EE663B7EE.md) | 100

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \write.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


