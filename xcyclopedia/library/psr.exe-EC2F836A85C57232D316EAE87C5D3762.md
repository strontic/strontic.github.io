---
title: psr.exe | Steps Recorder
---

# psr.exe 

* File Path: `C:\WINDOWS\SysWOW64\psr.exe`
* Description: Steps Recorder
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EC2F836A85C57232D316EAE87C5D3762`
SHA1 | `ADA9697BF088333D97A3E7DA2A5EC66872E5969C`
SHA256 | `44A3E9F977CA6C8286E70577D163511CA222F8D99A7B0F0FD0890C3A2A9BF8BD`
SHA384 | `DB2E7B674DFBA4D3F470C0D7C3BFB515A1EA5B6A982DE0DD6C29D7651E1879A8CBA820109C836793B580A522B88391F5`
SHA512 | `504F91CBE50F4102B2902B02D014C626B6004EA39A280F842F04755D63E29B877CFAC4CA094E138B969484E29B57E8627CF8B451700854C4132CAC3E45DB373E`
SSDEEP | `3072:5XWREgol+AtjWRux5ZX6SBDbWOIGmteHBRR3FnXj+n/Ce3sLG+9r5OPhvvBif:pWREgW+AtjtxnX6SBHW5t+DECe3sLHsB`

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

* Original Filename: psr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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



MIT License. Copyright (c) 2020 Strontic.


