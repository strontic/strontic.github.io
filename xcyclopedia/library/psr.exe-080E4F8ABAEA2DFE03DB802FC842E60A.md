---
title: psr.exe | Steps Recorder
---

# psr.exe 

* File Path: `C:\Windows\system32\psr.exe`
* Description: Steps Recorder
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `080E4F8ABAEA2DFE03DB802FC842E60A`
SHA1 | `DBD7D7E8A9AEBD5AA615F5FDC970F9C231A34F0C`
SHA256 | `88160871721148021A86D945BCB04FCD483776FF3F1480DE33EA8FD56BF4EA87`
SHA384 | `6A84E3CF50BCF8141D0821EC07634CF43AA7BC599213AE05A5BB4218AAE64535CC41A17F87FE66DF1E751C9A98546E3C`
SHA512 | `404D9746956325B1B4F1BED2D7E73CF182C6A47D5066961677DF08BC005EB45B60AD20D5545DAAD010CA806480CB83723B96BBB7FA37BC6370BF6CDE1C85E8C3`
SSDEEP | `6144:KnH4+bmsLdjcwQjk/g3SvUnOwi0Lpi8Qgm:KnH4mu95ivqOwiECg`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `psr.exe` being misused. While `psr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `title: Psr.exe Capture Screenshots` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `description: The psr.exe captures desktop screenshots and saves them on the local machine` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `        Image\|endswith: '\Psr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `Name: Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `  - Command: psr.exe /start /gui 0 /output c:\users\user\out.zip` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `  - Command: psr.exe /start /maxsc 100 /gui 0 /output c:\users\user\out.zip` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `  - Command: psr.exe /stop` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `  - C:\Windows\System32\Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `  - C:\Windows\SysWOW64\Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `Name: Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `  - Command: psr.exe /start /output D:\test.zip /sc 1 /gui 0` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `    Description: Record a user screen without creating a GUI. You should use "psr.exe /stop" to stop recording and create output file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `  - Path: c:\windows\system32\psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `  - Path: c:\windows\syswow64\psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `  - IOC: psr.exe spawned` | 



MIT License. Copyright (c) 2020 Strontic.


