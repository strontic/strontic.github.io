---
title: runonce.exe | Run Once Wrapper
---

# runonce.exe 

* File Path: `C:\windows\system32\runonce.exe`
* Description: Run Once Wrapper

## Hashes

Type | Hash
-- | --
MD5 | `8AE95C9655D24787AC951D84C0999DDF`
SHA1 | `2B8AAB68D31C0C974EEBB8014494193C01AF3257`
SHA256 | `31F9A7FE6617B035DF0FD6BF0B21FCD33528B4962C15AF20CE617FDF0E57CF0A`
SHA384 | `3F6C6CFAE42F08907B32FE57D49CC2C10956587AF1BBA0487E5EAD8B30B05A7E1083C283BD641AEDD22A96990C2FD0F4`
SHA512 | `F5B3A6AB5A05E7E1169BF9896BA1B37BAA5FFAEB4883A486615CBFE62E5FEF422ED478C696D2661AFED8A441461EF3B11982041AE5415E76CBEA28F18A182327`
SSDEEP | `768:QddHN+igvj9/i1stBSnSDCwo9AktQLgaWH1hx6Kw/mpIaemN09og:QddHN+dZqmfo6tDmNg`

## Signature

* Status: The file C:\windows\system32\runonce.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: RUNONCE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `runonce.exe` being misused. While `runonce.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\runonce.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `Name: Runonce.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Command: Runonce.exe /AlternateShellStartup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\System32\runonce.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\SysWOW64\runonce.exe` | 



MIT License. Copyright (c) 2020 Strontic.


