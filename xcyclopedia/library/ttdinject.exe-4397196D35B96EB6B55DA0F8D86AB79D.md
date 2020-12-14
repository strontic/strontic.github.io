---
title: ttdinject.exe | Time Traver Debugger Application Launcher
excerpt: What is ttdinject.exe?
---

# ttdinject.exe 

* File Path: `C:\Windows\system32\ttdinject.exe`
* Description: Time Traver Debugger Application Launcher

## Hashes

Type | Hash
-- | --
MD5 | `4397196D35B96EB6B55DA0F8D86AB79D`
SHA1 | `C43DFC99F5F0EB3F0A133DA791CD5D1362DD27B1`
SHA256 | `C071BA0575AC5C43A97AAC99AB5AFC12B0D8B753FC575DE07E893906C1DC003E`
SHA384 | `EAE5F5F58810D22249D9753487138AC0EC4CEE44896F75ACC2784200840695059DE16975391BDAFFAF253017B64919AC`
SHA512 | `4CECB003425901BCB12ECE2F20862850C115D6359D4214E5B34DB11E6EAEB2BE024293F5B89526217264B10164DB9CD899028D0678BF50C3A37A9E8D0C221312`
SSDEEP | `6144:UXqEDI4QDdGJl7DSkMVIvQ6mkwgzj7vckk5kVbRle/CMrVMb/7Gv:UXtgip/fYKbRcDrVMr`
IMP | `8D51D50F8F759EDF48244E7F3AC1AE0A`
PESHA1 | `3C956A54504C62CA445F94362ABCA9342C325F9F`
PE256 | `7B1041097B7DD406D73CD77513376730A77BD32B0DBCFE8AF28CD26E88B6012E`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) TTDInject Launcher 1.01.03
Release: 10.0.17763.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

### Usage (stderr):
```cmhg
!!! Unexpected string 'help' after 'C:\Windows\system32\ttdinject.exe'


```

### Child Processes:
csrss.exe wininit.exe

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c071ba0575ac5c43a97aac99ab5afc12b0d8b753fc575de07e893906c1dc003e/detection/


## Possible Misuse

*The following table contains possible examples of `ttdinject.exe` being misused. While `ttdinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Name: Ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: TTDInject.exe /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /Launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Description: Execute calc using ttdinject.exe. Requires administrator privileges. A log file will be created in tmp.run. The log file can be changed, but the length (7) has to be updated.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: ttdinject.exe /ClientScenario TTDRecorder /ddload 0 /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\System32\ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\Syswow64\ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Parent child relationship. Ttdinject.exe parent for executed command` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Multiple queries made to the IFEO registry key of an untrusted executable (Ex. "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\payload.exe") from the ttdinject.exe process` | 



MIT License. Copyright (c) 2020 Strontic.


