﻿---
title: ttdinject.exe | Time Traver Debugging Application Injector
excerpt: What is ttdinject.exe?
---

# ttdinject.exe 

* File Path: `C:\Windows\system32\ttdinject.exe`
* Description: Time Traver Debugging Application Injector

## Hashes

Type | Hash
-- | --
MD5 | `B1116E05A2AEDA8E95F89E74C1525A6C`
SHA1 | `7685045CCD89E21943330C049A84E6F0184104BE`
SHA256 | `1CDF9D33B2C92A212C8A297802178127F354131D6D05641B6FDB6C52AFF5FDE3`
SHA384 | `AA77A344AC61C3922C5FDB57468773EA5FFFDED6BA634923BC92535435E02E2AFB07C6EB34828671F5AF21AF49AC19F0`
SHA512 | `37E875A1E35E89D4D1675C724B29E19BBF4A91E4E512952CE792F6BC040E8806544EC67B413024A9955453B80F76458367D545AA7E910DD99D001151329E6B63`
SSDEEP | `3072:r77GakXf+WXf4Zd6/7e2wyctvtOisrGr7xpKQi23rX8LcC/1IrM72tZzPaLArd5n:faHf4ZdMJisrE7XLPiUZzA2dwbDHu`
IMP | `B0F85C22544E7D82BA1D1F5B11B27088`
PESHA1 | `32693F44C6BA3B996182D90B4924DF13336B0527`
PE256 | `53D223A5323908F5BCAC0DFB29134778341BF9CD75311491D4BB1438FCF6C9B5`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) TTDInject Launcher 1.01.06
Release: 10.0.19041.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

### Usage (stderr):
```cmhg
!!! Unexpected string 'help' after 'C:\Windows\system32\ttdinject.exe'


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\ttdinject.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTDInject.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/1cdf9d33b2c92a212c8a297802178127f354131d6d05641b6fdb6c52aff5fde3/detection


## Possible Misuse

*The following table contains possible examples of `ttdinject.exe` being misused. While `ttdinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Name: Ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: TTDInject.exe /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /Launch "C:/Windows/System32/calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Description: Execute calc using ttdinject.exe. Requires administrator privileges. A log file will be created in tmp.run. The log file can be changed, but the length (7) has to be updated.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: ttdinject.exe /ClientScenario TTDRecorder /ddload 0 /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /launch "C:/Windows/System32/calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\System32\ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\Syswow64\ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Parent child relationship. Ttdinject.exe parent for executed command`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Multiple queries made to the IFEO registry key of an untrusted executable (Ex. "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\payload.exe") from the ttdinject.exe process`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


