---
title: ttdinject.exe | Time Traver Debugging Application Injector
excerpt: What is ttdinject.exe?
---

# ttdinject.exe 

* File Path: `C:\Windows\SysWOW64\ttdinject.exe`
* Description: Time Traver Debugging Application Injector

## Hashes

Type | Hash
-- | --
MD5 | `901A932FAE9B16AE4ABFB3FEFFFD54F9`
SHA1 | `A83078097C3F823E864B3ACF7F57C6FFF8DEC333`
SHA256 | `149306318334A101F6647718519477713A7ED2E50759258881AB28F4F04F5FA7`
SHA384 | `12217046EE4D7E9311D083F8B769BC30330DCEEC9E698D1B1469770F7645594EFC2EDB27CBD9C607A636398782FA6E29`
SHA512 | `B195819AC82BB7257DBCC216FD21EC4497B96770F80EF8EA15C51731B10CCCB893EC36A4BE39D379BC3D28542F1A8D8FD54B6821133F1218F6A23EA693DFA6E0`
SSDEEP | `6144:3LOdyc8ldPDGmSqJoCblTGq+yI/wSL/ZPELgaSdn:3L6yc6diqoCblTGq+XwSL/ZPEshh`
IMP | `A3665E1917D2E20AE758DA35DCB10292`
PESHA1 | `32A9CB1F46825B222DAD8C4431ABDBC94E7A2D41`
PE256 | `A7CCE6F87ECB455A4E72D1FBA16521A32DFBF3449B3066F67AD0F0F6F4824295`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) TTDInject Launcher 1.01.06
Release: 10.0.19041.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

### Usage (stderr):
```cmhg
!!! Unexpected string 'help' after 'C:\Windows\SysWOW64\ttdinject.exe'


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ttdinject.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/149306318334a101f6647718519477713a7ed2e50759258881ab28f4f04f5fa7/detection


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


