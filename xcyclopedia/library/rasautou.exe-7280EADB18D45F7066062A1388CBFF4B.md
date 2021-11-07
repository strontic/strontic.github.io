---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\windows\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `7280EADB18D45F7066062A1388CBFF4B`
SHA1 | `B40C22C03391AE18CF620ABA3508604B81097199`
SHA256 | `165487D878513CFC082FE37100E52188938EC93675FF3B44F4712333C3C558C8`
SHA384 | `6266167BCE7E5AC91FAC97822A3788A255C86246633F551FD2A8FE209102CDED85C4615054405273E7D51595AC41F2CE`
SHA512 | `D23EE1E175E0C214173A0A23EDFFA964C26C7611F73CF3ED07972458F0C24599D8E502D70F5BAD7191ACF30E5721A4759FDB75C5538DAA10BF640290CD4E1051`
SSDEEP | `384:4Yd7P7H00G8e7FQL45uE4sDn/qwTki/UyIopUm6sW1BW:40H0Z5WFsn/jQyhp6v`

## Signature

* Status: The file C:\windows\system32\rasautou.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `title: DLL Execution via Rasautou.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `description: Detects using Rasautou.exe for loading arbitrary .DLL specified in -d option and executes the export specified in -p. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Rasautou/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `Image\|endswith: '\rasautou.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


