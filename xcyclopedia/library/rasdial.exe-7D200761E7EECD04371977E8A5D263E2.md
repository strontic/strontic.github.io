---
title: rasdial.exe | Remote Access Command Line Dial UI
---

# rasdial.exe 

* File Path: `C:\windows\system32\rasdial.exe`
* Description: Remote Access Command Line Dial UI
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7D200761E7EECD04371977E8A5D263E2`
SHA1 | `AFAE16D5B0A50A1BF2AF38EB1F568D41BF455A2A`
SHA256 | `F532D2031B53B90C1B851E4640C6F24DBFE9383A05CF0B3BDC0B580EBAADAF77`
SHA384 | `FEA8D592C35A7AE1B45F7E0FA2463721157CF27C9B2F82CA02A8039CA065E60020403D8562368B172A4441F78FEB0281`
SHA512 | `DFD957FFB7C47C6CEA9135926A47A07C8272E632E983A64413D544211F44769CB177E44752D5F9AFBE9F0AFBFA576C3B43155ECF2B7AE47607F6DC733BFD973B`
SSDEEP | `384:fxcmqdtuotHHJdyJuG0ZwitTH4aiwydFmMnTi4LokPHVIJKW5VW7:fxvqdtuoZKJuG0ztsaitdz+4oYVIJV`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\rasdial.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `            - rasdial` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


