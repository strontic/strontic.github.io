---
title: ttdinject.exe | Time Traver Debugger Application Launcher
---

# ttdinject.exe 

* File Path: `C:\Windows\SysWOW64\ttdinject.exe`
* Description: Time Traver Debugger Application Launcher

## Hashes

Type | Hash
-- | --
MD5 | `B9269B78B1AEF3900F2864E98B766DE0`
SHA1 | `A276D84424F0AB97E888B024DA437F3F6334491B`
SHA256 | `6D42E1981E0B9D704351705B3F14E7E982766775CEDA9D6A8EF15E9D7EC32F99`
SHA384 | `DB25B8D526E75BC15695BE0EDA9304455AB240324C1EECB6854EBA154DE90074B03328D3016F75D204A09BDCB46B7BF8`
SHA512 | `136304E147300B06B6556A3A694DBC1382A03E71DE484E7BF5F8D648AB5BF27A1E45D186BFF061BB53D053651950D9E3E33BC30520488919E3614E2D501E2068`
SSDEEP | `3072:lrM6awV1wYDyyn5j7z/sczZTENm2eK7mnoUSgpAY8ODcDcm7cIsW7WB8ANRaBK9d:lVLjLscz1ENm2eK7mnoUSgpAY8ODcDc9`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) TTDInject Launcher 1.01.03
Release: 10.0.17763.1
Copyright (C) Microsoft Corporation. All rights reserved.


```

### Usage (stderr):
```Batchfile
!!! Unexpected string 'help' after 'C:\Windows\SysWOW64\ttdinject.exe'


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Steam\steamerrorreporter.exe](steamerrorreporter.exe-061E8A619CA76421823F147AC6F264FD.md) | 49

## Possible Misuse

*The following table contains possible examples of `ttdinject.exe` being misused. While `ttdinject.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Name: Ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - Command: TTDInject.exe /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /Launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `    Description: Execute calc using ttdinject.exe. Requires administrator privileges. A log file will be created in tmp.run. The log file can be changed, but the length (7) has to be updated.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - Command: ttdinject.exe /ClientScenario TTDRecorder /ddload 0 /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - Path: C:\Windows\System32\ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - Path: C:\Windows\Syswow64\ttdinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - IOC: Parent child relationship. Ttdinject.exe parent for executed command` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `  - IOC: Multiple queries made to the IFEO registry key of an untrusted executable (Ex. "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\payload.exe") from the ttdinject.exe process` | 



MIT License. Copyright (c) 2020 Strontic.


